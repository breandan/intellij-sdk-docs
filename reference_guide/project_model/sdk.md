---
title: SDK
---

Every project uses a Software Development Kit (SDK).
For Java projects, SDK is referred to as JDK (Java Development Kit).
SDK determines which API library is used to build the project. If your project is multi-module, the project SDK by default is common for all modules within the project.
Optionally, you can configure individual SDK for each module.
For more information about SDKs, see
[JDKs](http://www.jetbrains.com/idea/webhelp/jdks.html)
and
[Configuring Project JDK](http://www.jetbrains.com/idea/webhelp/configuring-project-jdk.html)
in IntelliJ IDEA Web Help.

### Getting Project Sdk Information

Main information about the project Sdk can be accessed via
[ProjectRootManager.java](https://github.com/JetBrains/intellij-community/blob/master/platform/projectModel-api/src/com/intellij/openapi/roots/ProjectRootManager.java)
like the following example shows

```java
String projectSdk = ProjectRootManager.getInstance(project).getProjectSdk();
```

### Getting And Setting Project SDK Attributes

* To get the project-level SDK

  ```java
  Sdk projectSDK = ProjectRootManager.getInstance(project).getProjectSdk();
  ```

* To get the project-level SDK name:
 
  ```java 
  String projectSDKName = ProjectRootManager.getInstance(project).getProjectSdkName();
  ```

* To set the project-level SDK:
 
  ```java
  ProjectRootManager.getInstance(project).setProjectSdk(Sdk jdk);
  ```

* To set the project-level SDK name:
 
  ```java
  ProjectRootManager.getInstance(project).setProjectSdkName(String name);
  ```
  
See the following [code sample](https://github.com/JetBrains/intellij-sdk/blob/master/code_samples/project_model/src/com/intellij/plugins/project/model/ProjectSdkAction.java)
to get more familiar with SDK manipulation tool set.
