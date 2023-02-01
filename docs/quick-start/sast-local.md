# Local Static Analysis
Here you will see how to quickly get started with performing static code analysis from a local machine

## Analyis Process
There are four distinct phases that make up the analysis process:

1. **Build Integration** — Choose whether to integrate Fortify Static Code Analyzer into your build tool. For descriptions of build integrationClosed options, see Integrating into a Build.
2. **Translation** — Gathers source code using a series of commands and translates it into an intermediate format associated with a build 
IDClosed. The build ID is usually the name of the project you are translating. For more information, see Translation Phase.

3. **Analysis** — Scans source files identified in the translation phase and generates an analysis result file (typically in the Fortify Project Results (FPRClosed) format). FPR files have the .fpr file extension. For more information, see Analysis Phase.

4. Verification of translation and analysis—Verifies that the source files were scanned using the correct Rulepacks and that no errors were reported. For more information, see Translation and Analysis Phase Verification.

```
sourceanalyzer -b <build_id> -clean
sourceanalyzer -b <build_id> ...
sourceanalyzer -b <build_id> -scan -f MyResults.fpr
```

## Command line

### Translating Source Code
The process of translating source code allows for 

!!! tip ""

    === "Java"
        ``` bash
        # syntax
        # sourceanalyzer -b <build_id> -cp <classpath> <files>

        # example
        sourceanalyzer -b MyProject -cp "lib/*.jar" "src/**/*.java"
        ```
    === "Go"

        ``` bash
        sourceanalyzer -b <build_id> [-gopath <dir>] [-goroot <dir>] <files>
        ```
        ??? warning
            For best results, your project must be compilable and you must have all required dependencies available.

            The following entities are excluded from the translation (and the scan):

            Vendor folder

            All projects defined by any go.mod files in subfolders, except the project defined by the go.mod file under the %PROJECT_ROOT%

            All files with the _test.go suffix (unit tests)
    
    === Kotlin