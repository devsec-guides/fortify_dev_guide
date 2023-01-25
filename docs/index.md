# Fortify DevOps Guide

This guide is meant to provide guidance and demonstrations on how to use the Fortify software in a developer environment.

# What is Fortify

Microfocus **Fortify** is a comprehensive set of tools for software security that includes both static and dynamic analysis capabilities.

**Static analysis** is performed by scanning the source code of a program and identifying potential vulnerabilities without executing the code. Fortify provides a variety of static analysis tools, including the Fortify SCA (Software Composition Analysis) that can identify known vulnerabilities in third-party libraries and components, and the Fortify SAST (Static Application Security Testing) that can identify issues such as SQL injection and cross-site scripting.

**Dynamic analysis**, on the other hand, involves executing the code and analyzing its behavior at runtime. Fortify provides dynamic analysis tools, such as ScanCentral DAST as WebInspect (Dynamic Application Security Testing) that can identify issues.

# Deployment Solutions

- **Fortify OnPremise** is installed and run on the customer's own infrastructure

- **Fortify Hosted** is the cloud-hosted equivalent of Fortify OnPremise with the main difference being that the infrastructre, maintenance, upgrades, etc are managed entirely by MicroFocus.  

- **Fortify OnDemand** is a SaaS version of the software that is hosted by Microfocus and can be accessed via the web.

Regardless of the deployment solution, Fortify is designed to help developers identify and fix vulnerabilities in their code, and offer a wide range of capabilities and features to support secure software development.

# Next
Use the navigation links on the left hand side for tutorials.

For the full documentation including requirements visit the links below

- [Fortify Static Code Analyzer and Tools 22.2.x Documentation](https://www.microfocus.com/documentation/fortify-static-code-analyzer-and-tools/)

- [ScanCentral DAST](https://www.microfocus.com/documentation/fortify-ScanCentral-DAST/)

``` mermaid
sequenceDiagram
  autonumber
  Alice->>John: Hello John, how are you?
  loop Healthcheck
      John->>John: Fight against hypochondria
  end
  Note right of John: Rational thoughts!
  John-->>Alice: Great!
  John->>Bob: How about you?
  Bob-->>John: Jolly good!
```
