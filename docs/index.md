# Fortify DevOps Guide

This guide is meant to provide guidance and demonstrations on how to use the Fortify software in a developer environment.

## What is Fortify

Microfocus **Fortify** is a comprehensive set of tools for software security that includes both static and dynamic analysis capabilities.

**Static analysis** is performed by scanning the source code of a program and identifying potential vulnerabilities without executing the code. Fortify provides a variety of static analysis tools, including the Fortify SCA (Software Composition Analysis) that can identify known vulnerabilities in third-party libraries and components, and the Fortify SAST (Static Application Security Testing) that can identify issues such as SQL injection and cross-site scripting.

**Dynamic analysis**, on the other hand, involves executing the code and analyzing its behavior at runtime. Fortify provides dynamic analysis tools, such as ScanCentral DAST as WebInspect (Dynamic Application Security Testing) that can identify issues.

## Deployment Solutions

- **[Fortify OnPremise](solutions/onpremise_overview.md)** is installed and run on the customer's own infrastructure

- **[Fortify Hosted](solutions/hosted_overview.md)** is the cloud-hosted equivalent of Fortify OnPremise with the main difference being that the infrastructre, maintenance, upgrades, etc are managed entirely by MicroFocus.  

- **[Fortify OnDemand](solutions/fod_overview.md)** is a SaaS version of the software that is hosted by Microfocus and can be accessed via the web.

Regardless of the deployment solution, Fortify is designed to help developers identify and fix vulnerabilities in their code, and offer a wide range of capabilities and features to support secure software development.


## Next
Use the navigation links on the left hand side for more information.

See the [References](references.md) for official documentation that does deeper into the Fortify products and tools

