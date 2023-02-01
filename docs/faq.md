# FAQ

??? question "What deployment solutions are available for Fortify"

    OnPremise, Hosted, and Fortify OnDemand

    - **Fortify OnPremise** is a customer hosted solution for Fortify. 

    - **Fortify Hosted** is a PaaS (Platform as a Service) offering that contains the same components as Fortify OnPremise.
    This solution is hosted on a cloud provider and the entire infrastructure is maintained by MicroFocus.

    - **Fortify OnDemand** (FOD) is a SaaS offering that is managed by MicroFocus. Customer log into to the FOD web portal and their data is separated by a **tenant ID**.  

??? question "How do I scan a maven project"

    To scan a maven project you need to install the sca-maven plugin that.
    See the [documentation](https://www.microfocus.com/documentation/fortify-static-code-analyzer-and-tools/2220/SCA_Help_22.2.0/index.htm#BuildIntegration/MavenIntegration/MavenIntegration.htm?TocPath=Integrating%2520into%2520a%2520Build%257CMaven%2520Integration%257C_____0){:target_blank}

??? question "Do you support AWS Codestar"
    Yes, the repositories below can be used to download fortify software and run security scans using command line utilities.

    - :material-source-repository: [Tools Installer](https://github.com/fortify/FortifyToolsInstaller){:target="_blank"}

    - :material-source-repository: [Fortify CLI](https://github.com/fortify-ps/fcli){:target="_blank"}