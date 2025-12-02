[![Build Status](https://img.shields.io/endpoint?url=https%3A%2F%2Fstatusbadge-jx.apps.serv.run%2Fvillanova%2Fvillanova-plugin-jpmail)](https://github.com/villanova/devops-results/tree/logs/jenkins-x/logs/villanova/villanova-plugin-jpmail/master)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=villanova_villanova-plugin-jpmail&metric=alert_status)](https://sonarcloud.io/dashboard?id=villanova_villanova-plugin-jpmail)
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=villanova_villanova-plugin-jpmail&metric=coverage)](https://villanova.github.io/devops-results/villanova-plugin-jpmail/master/jacoco/index.html)
[![Vulnerabilities](https://sonarcloud.io/api/project_badges/measure?project=villanova_villanova-plugin-jpmail&metric=vulnerabilities)](https://villanova.github.io/devops-results/villanova-plugin-jpmail/master/dependency-check-report.html)
[![Code Smells](https://sonarcloud.io/api/project_badges/measure?project=villanova_villanova-plugin-jpmail&metric=code_smells)](https://sonarcloud.io/dashboard?id=villanova_villanova-plugin-jpmail)
[![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=villanova_villanova-plugin-jpmail&metric=security_rating)](https://sonarcloud.io/dashboard?id=villanova_villanova-plugin-jpmail)
[![Technical Debt](https://sonarcloud.io/api/project_badges/measure?project=villanova_villanova-plugin-jpmail&metric=sqale_index)](https://sonarcloud.io/dashboard?id=villanova_villanova-plugin-jpmail)

villanova-plugin-jpmail
**Mail Plugin**

**Code**: ```jpmail```

**Description**

Mail Plugin is a component that let Villanova users configure SMTP server and create new senders to send email messages.

**Installation**

In order to install the Mail Plugin, you must insert the following dependency in the pom.xml file of your project:

```
<dependency>
    <groupId>org.villanova.villanova.plugins</groupId>
    <artifactId>villanova-plugin-jpmail</artifactId>
    <version>${villanova.version}</version>
    <type>war</type>
</dependency>
````

**Configuration**

From Villanova’s back office, you have to:

 1. create new **Sender**: you have to create a new Sender with a _Code_ and an _Email_. You can have a List of Senders; the Sender will be choosed on the base of its Code. 
 2. configure the **SMTP server**: you have to active the SMTP server, and then to set _Host_ (mandatory), _Port_, _Security Certification_, _Timeout_ parameter.
 
Please leave _Username_ and _Password_ blank if the SMTP does not require authentication.
 


# Developing against local versions of upstream projects (e.g. admin-console,  villanova-engine).

Full instructions on how to develop against local versions of upstream projects are available in the
[villanova-parent-bom](https://github.com/villanova/villanova-core-bom) project.     