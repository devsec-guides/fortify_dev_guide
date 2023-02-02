# Fortify DevOps Guide

This guide is meant to provide guidance and demonstrations on how to use the Fortify software in a developer environment.

## Fortify Overview
!!! note ""

### :fortify-cyberres: <span class="marquee">**What is Fortify**</span>

**Fortify** is a suite of software security products offered by MicroFocus. It provides a comprehensive solution for organizations to identify, manage, and remediate security risks in their software applications. Fortify offers products that support Static, Dynamic, Mobile, and Open Source scanning.
Using this suite of tools / products, organizations are able to integrate security testing across throughout their entire SDLC and have a holistic view of an org's application security posture.


### :fortify-cyberres: <span class="marquee">**Deployment Solutions**</span>

- **[Fortify OnPremise](#fortify-onpremise)** is installed and run on the customer's own infrastructure.

- **[Fortify OnDemand](#fortify-ondemand)** is a SaaS version of the software that is hosted by Microfocus and can be accessed via the web.

Regardless of the deployment solution, Fortify is designed to help developers identify and fix vulnerabilities in their code, and offer a wide range of capabilities and features to support secure software development.


## Product Overview
!!! note ""

This section will help you to get to speed on how to use the Fortify software both OnPremise and Fortify OnDemand.
There are a number of different ways to scan that's because Fortify focusing on **Shift Everywhere** in order to meet your needs no matter your workflow.

### :fortify-cyberres: <span class="marquee">**Fortify OnPremise**</span>

!!! info ""
    **Fortify OnPremise** is customer managed solution and central 
    platform.  
    
    **Software Security Center (SSC)** is that web portal that provides a complete solution for managing application security. It combines security assessments from Fortify Static Code Analyzer and other tools to give an overall view of your app security. It has features for managing security assessments, tracking fixes, and reporting, making it easier for security and development teams to work together to improve app security. The platform supports various types of security testing, including static, dynamic, mobile, API, and open-source testing.

    [:material-card-account-details-star: Learn More](#){ .md-button }

### :fortify-cyberres: <span class="marquee">**Fortify OnDemand**</span>

!!! info ""
    **Fortify on Demand** is a SaaS based solution that is software security testing service and is vendor hosed and managed. Organizations can quickly and easily assess the security of their web applications, mobile applications, and APIs. 
    
    By using Fortify on Demand, organizations can identify potential security vulnerabilities and weaknesses in their software systems and prioritize remediation efforts based on risk severity. The service is designed to be fast, efficient, and cost-effective, and is hosted and maintained by the vendor.

    [:material-card-account-details-star: Learn More](#){ .md-button }

### :octicons-codescan-16: <span class="marquee">**Static Analysis**</span>

!!! info "Source Code Analyzer (SCA)"
    The heart of static analysis.  Identifies insecure code allowing developers to quickly identify and remediation vulnerabilities in their source code.  Integrations and plugins are available for IDEs and CI/CD pipelines.  Deep customizations allows developers to fine tune scan results.  Support 26+ languages

    
    <span>[:material-card-account-details-star: Learn More](#){ .md-button }</span>

!!! info inline "Security Assistant"
    IDE Plugin that gives real time suggestions and code fixes related to security vulnerabilities.

    [:material-card-account-details-star: Learn More](#){ .md-button }

!!! info "Scan Central SAST"
    Distributed SAST scanning solution that can automated scanning by using dedicated machines that have SCA installed.  Offloads the working of scanning source code and uploading results to SSC

    [:material-card-account-details-star: Learn More](#){ .md-button }

!!! info "Audit Assistant"
    Utilizes machine learning to automate code reviews by identify false postives and true vulnerabilities for SAST.  Available as an OnPremise installation as well as in SSC

    [:material-card-account-details-star: Learn More](#){ .md-button }


### :material-web-refresh: <span class="marquee">**Dynamic Analysis**</span>

!!! info "WebInspect"
    An automated DAST solution that provides comprehensive vulnerability detection and helps security professionals and QA testers identify security vulnerabilities and configuration issues. 

    [:material-card-account-details-star: Learn More](#){ .md-button }

!!! info inline "Fast Proxy"
    Record functional tests for a web application or API that can be saved and used for future scanning

    [:material-card-account-details-star: Learn More](#){ .md-button }

!!! info "Scan Central DAST"
    Orchestration for Dynamic scanning using distributed dast scanning machines

    [:material-card-account-details-star: Learn More](#){ .md-button }

### :material-source-repository: <span class="marquee">**Open Source Analyis**</span>

!!! info "Debricked"
    Identifies vulnerabilites in 3rd party open source libraries.

    [:material-card-account-details-star: Learn More](#){ .md-button }

### :fontawesome-solid-laptop-code: <span class="marquee">**IDE Integrations**</span>

[:material-android: Android Studio](/ide/android){ .md-button }
[:simple-eclipseide: Eclipse](/ide/eclipse){ .md-button }
[:simple-intellijidea: IntelliJ](/ide/intellij){ .md-button }


[:material-microsoft-visual-studio-code: VS Code](/ide/vscode){ .md-button }
[:material-microsoft-visual-studio: Visual Studio](/ide/visualstudio){ .md-button }

### :material-circle-double: <span class="marquee">**CI/CD Integrations**</span>

[:fontawesome-brands-aws: AWS](#){ .md-button }
[:simple-azurepipelines: Azure DevOps](/quickstart/cicd/#azuredevops){ .md-button }
[:simple-github: Github](/quickstart/cicd/#github){ .md-button }

[:simple-gitlab: Gitlab](/quickstart/cicd/#gitlab){ .md-button }
[:simple-jenkins: Jenkins](/quickstart/cicd/#jenkins){ .md-button }
[:fortify-cyberres: Fortify CI](/quickstart/cicd/#fortifyci){ .md-button }

### :fontawesome-solid-bug: <span class="marquee">**Bug Tracker Integration**</span>

[:simple-azurepipelines: Azure DevOps](#){ .md-button }
[:simple-jira: Jira](#){ .md-button }
[:simple-gitlab: GitLab](#){ .md-button }
[:simple-github: Github](#){ .md-button }
