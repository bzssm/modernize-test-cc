# showmyjvm

> Consolidated assessment across all units detected under this component root. Each unit's full report is inlined below; raw per-unit artefacts (report JSON, facts, scenarios) remain in their subfolders.

## Units

| Unit |
|------|
| [showmyjvm](#showmyjvm) |
| [showmyjvm.e2e-tests](#showmyjvm-e2e-tests) |

## showmyjvm

### showmyjvm (Java)


#### Summary

| Metric | Value |
|--------|-------|
| Total Issues | 11 |
| Mandatory Blockers | 4 |
| Potential Issues | 3 |

#### Component Information

| Property | Value |
|----------|-------|
| Language | Java, JavaScript, C#, Smalltalk, Shell |
| Frameworks | net9.0, Quarkus, Spring Boot, Spring, JakartaEE |
| Build tools | Maven, NodeJs |
| JDK version | 25 |

#### Cloud Readiness Issues

| Issue Name | Criticality | Story Points | Occurrences |
|------------|-------------|--------------|-------------|
| Hardcoded IP Address | Mandatory | 3 | [2](#Hardcoded_IP_Address) |
| Local HTTP Calls | Mandatory | 3 | [1](#Local_HTTP_Calls) |
| Use of unsecured network protocols or URI libraries | Mandatory | 3 | [1](#Use_of_unsecured_network_protocols_or_URI_libraries) |
| No Dockerfile found | Mandatory | 3 | 1 |
| Detects usage of Jakarta RESTful Web Services (JAX-RS) APIs | Potential | 5 | [2](#Detects_usage_of_Jakarta_RESTful_Web_Services_JAX-RS_APIs) |
| Server port configuration found | Potential | 1 | [1](#Server_port_configuration_found) |
| Restricted configurations found | Potential | 2 | [1](#Restricted_configurations_found) |
| Environment variables/system properties | Optional | 3 | [6](#Environment_variables_system_properties) |
| Avoid using hardcoded URLs (HTTP protocol) in source code | Optional | 3 | [1](#Avoid_using_hardcoded_URLs_HTTP_protocol_in_source_code) |

##### Issue Details

<details id="Hardcoded_IP_Address">
<summary><b>Hardcoded IP Address</b> — affected files</summary>

- `quarkus/src/main/resources/application.properties (line 3, col 0)`
- `helidon-mp/src/main/resources/META-INF/microprofile-config.properties (line 3, col 0)`

</details>

<details id="Local_HTTP_Calls">
<summary><b>Local HTTP Calls</b> — affected files</summary>

- `helidon/src/main/java/io/helidon/examples/quickstart/se/Main.java (line 21, col 0)`

</details>

<details id="Use_of_unsecured_network_protocols_or_URI_libraries">
<summary><b>Use of unsecured network protocols or URI libraries</b> — affected files</summary>

- `helidon/src/main/java/io/helidon/examples/quickstart/se/Main.java (line 21, col 0)`

</details>

<details id="Detects_usage_of_Jakarta_RESTful_Web_Services_JAX-RS_APIs">
<summary><b>Detects usage of Jakarta RESTful Web Services (JAX-RS) APIs</b> — affected files</summary>

- `quarkus/pom.xml (line 44, col 0)`
- `helidon-mp/pom.xml (line 59, col 0)`

</details>

<details id="Server_port_configuration_found">
<summary><b>Server port configuration found</b> — affected files</summary>

- `spring-boot/src/main/resources/application.properties (line 1, col 0)`

</details>

<details id="Restricted_configurations_found">
<summary><b>Restricted configurations found</b> — affected files</summary>

- `spring-boot/src/main/resources/application.properties (line 1, col 0)`

</details>

<details id="Environment_variables_system_properties">
<summary><b>Environment variables/system properties</b> — affected files</summary>

- `helidon/src/main/java/io/helidon/examples/quickstart/se/Main.java (line 15, col 0)`
- `core/src/main/java/io/brunoborges/showmyjvm/core/ShowJVM.java (line 135, col 0)`
- `core/src/main/java/io/brunoborges/showmyjvm/core/ShowJVM.java (line 174, col 0)`
- `javalin/src/main/java/io/brunoborges/showmyjvm/javalin/Application.java (line 9, col 0)`
- `ratpack/src/main/java/io/brunoborges/showmyjvm/ratpack/RatpackStart.java (line 17, col 0)`
- `sparkjava/src/main/java/io/brunoborges/showmyjvm/sparkjava/SparkStart.java (line 13, col 0)`

</details>

<details id="Avoid_using_hardcoded_URLs_HTTP_protocol_in_source_code">
<summary><b>Avoid using hardcoded URLs (HTTP protocol) in source code</b> — affected files</summary>

- `helidon/src/main/java/io/helidon/examples/quickstart/se/Main.java (line 21, col 0)`

</details>

#### Upgrade Issues

| Issue Name | Criticality | Story Points | Occurrences |
|------------|-------------|--------------|-------------|
| Java Version is not the latest LTS | Optional | 8 | [1](#Java_Version_is_not_the_latest_LTS) |
| Jakarta EE Version is not the latest stable | Optional | 8 | [1](#Jakarta_EE_Version_is_not_the_latest_stable) |

##### Issue Details

<details id="Java_Version_is_not_the_latest_LTS">
<summary><b>Java Version is not the latest LTS</b> — affected files</summary>

- `serverless/azure-functions/pom.xml.versionsBackup (line 22, col 0)`

</details>

<details id="Jakarta_EE_Version_is_not_the_latest_stable">
<summary><b>Jakarta EE Version is not the latest stable</b> — affected files</summary>

- `sparkjava/pom.xml (line 37, col 0)`

</details>

#### DotNET Upgrade Issues [View Details](showmyjvm/scenarios/dotnet-version-upgrade/assessment.md)

| Issue Category | Criticality | Story Points |
|----------------|-------------|--------------|
| 需要更改项目的目标框架 | Mandatory | 1 |
| 建议升级 NuGet 包 | Potential | 1 |
| NuGet 包已弃用 | Optional | 1 |

##### Issue Details

<details>
<summary><b>需要更改项目的目标框架</b> — affected files</summary>

- `aspire\showmyjvm.csproj`

</details>

<details>
<summary><b>建议升级 NuGet 包</b> — affected files</summary>

- `aspire\showmyjvm.csproj`

</details>

<details>
<summary><b>NuGet 包已弃用</b> — affected files</summary>

- `aspire\showmyjvm.csproj`

</details>

---

#### Codebase Insights

> **Note:** These documents are generated by AI and may contain inaccuracies or incomplete information. Please review carefully.

> **Codebase Insights aren't available yet.**
>
> These documents are generated when assessment runs with **Full analysis** coverage. Re-run the assessment and set `analysisCoverage: full` to enable them.

[Share feedback](https://aka.ms/ghcp-appmod/feedback)


### showmyjvm (.NET)


#### Summary

| Metric | Value |
|--------|-------|
| Total Issues | 0 |
| Mandatory Blockers | 0 |
| Potential Issues | 0 |

#### Component Information

| Property | Value |
|----------|-------|
| Language | C# |
| Frameworks | net9.0 |
| Build tools | MSBuild |

#### DotNET Upgrade Issues [View Details](showmyjvm/scenarios/dotnet-version-upgrade/assessment.md)

| Issue Category | Criticality | Story Points |
|----------------|-------------|--------------|
| 需要更改项目的目标框架 | Mandatory | 1 |
| 建议升级 NuGet 包 | Potential | 1 |
| NuGet 包已弃用 | Optional | 1 |

##### Issue Details

<details>
<summary><b>需要更改项目的目标框架</b> — affected files</summary>

- `aspire\showmyjvm.csproj`

</details>

<details>
<summary><b>建议升级 NuGet 包</b> — affected files</summary>

- `aspire\showmyjvm.csproj`

</details>

<details>
<summary><b>NuGet 包已弃用</b> — affected files</summary>

- `aspire\showmyjvm.csproj`

</details>

---

#### Codebase Insights

> **Note:** These documents are generated by AI and may contain inaccuracies or incomplete information. Please review carefully.

> **Codebase Insights aren't available yet.**
>
> These documents are generated when assessment runs with **Full analysis** coverage. Re-run the assessment and set `analysisCoverage: full` to enable them.

[Share feedback](https://aka.ms/ghcp-appmod/feedback)


## showmyjvm.e2e-tests

### showmyjvm.e2e-tests (JavaScript/TypeScript)


JavaScript/TypeScript Dependency Assessment

#### Component Information

| Property | Value |
|----------|-------|
| Language | JavaScript/TypeScript |
| Build tools | npm |

#### Summary

| Update Type | Count |
|-------------|-------|
| **Total Updates** | **2** |
| Patch | 0 |
| Minor | 1 |
| Major | 1 |

#### Dependency Updates

| Package | Current | Target | Type |
|---------|---------|--------|------|
| @playwright/test | ^1.48.0 | ^1.61.1 | Minor |
| @types/node | ^22.0.0 | ^26.0.0 | Major |

#### Recommendations

| Update Type | Guidance |
|-------------|---------|
| Patch & Minor | Generally safe to apply. Consider updating these first. |
| Major | Review breaking changes in package release notes before updating. |
| Major (0.x) | Exercise caution — these packages follow unstable version semantics. |

---

#### Codebase Insights

> **Note:** These documents are generated by AI and may contain inaccuracies or incomplete information. Please review carefully.

> **Codebase Insights aren't available yet.**
>
> These documents are generated when assessment runs with **Full analysis** coverage. Re-run the assessment and set `analysisCoverage: full` to enable them.

[Share feedback](https://aka.ms/ghcp-appmod/feedback)


