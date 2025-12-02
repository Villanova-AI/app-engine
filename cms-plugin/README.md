[![Build Status](https://img.shields.io/endpoint?url=https%3A%2F%2Fstatusbadge-jx.apps.serv.run%2Fvillanova%2Fvillanova-plugin-jacms)](https://github.com/villanova/devops-results/tree/logs/jenkins-x/logs/villanova/villanova-plugin-jacms/master)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=villanova_villanova-plugin-jacms&metric=alert_status)](https://sonarcloud.io/dashboard?id=villanova_villanova-plugin-jacms)
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=villanova_villanova-plugin-jacms&metric=coverage)](https://villanova.github.io/devops-results/villanova-plugin-jacms/master/jacoco/index.html)
[![Vulnerabilities](https://sonarcloud.io/api/project_badges/measure?project=villanova_villanova-plugin-jacms&metric=vulnerabilities)](https://villanova.github.io/devops-results/villanova-plugin-jacms/master/dependency-check-report.html)
[![Code Smells](https://sonarcloud.io/api/project_badges/measure?project=villanova_villanova-plugin-jacms&metric=code_smells)](https://sonarcloud.io/dashboard?id=villanova_villanova-plugin-jacms)
[![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=villanova_villanova-plugin-jacms&metric=security_rating)](https://sonarcloud.io/dashboard?id=villanova_villanova-plugin-jacms)
[![Technical Debt](https://sonarcloud.io/api/project_badges/measure?project=villanova_villanova-plugin-jacms&metric=sqale_index)](https://sonarcloud.io/dashboard?id=villanova_villanova-plugin-jacms)

villanova-plugin-jacms
============

**CMS**

**Code**: ```jacms```

**Description**

CMS is a plugin that allows to registered users to manage in the Back Office dynamic contents and digital assets.

**Installation**

In order to install the CMS plugin, you must insert the following dependency in the pom.xml file of your project:

```
<dependency>
       <groupId>org.villanova.villanova.bundles.app-view</groupId>
       <artifactId>villanova-app-view-cms-default</artifactId>
       <version>${villanova.version}</version>
       <type>war</type>
</dependency>
```

# Developing against local versions of upstream projects (e.g. admin-console,  villanova-engine).

Full instructions on how to develop against local versions of upstream projects are available in the
[villanova-parent-bom](https://github.com/villanova/villanova-core-bom) project. 
