# RuoYi-Cloud

> Consolidated assessment across all units detected under this component root. Each unit's full report is inlined below; raw per-unit artefacts (report JSON, facts, scenarios) remain in their subfolders.

## Units

| Unit |
|------|
| [RuoYi-Cloud](#ruoyi-cloud) |
| [RuoYi-Cloud.ruoyi-ui](#ruoyi-cloud-ruoyi-ui) |

## RuoYi-Cloud

### RuoYi-Cloud (Java)


#### Summary

| Metric | Value |
|--------|-------|
| Total Issues | 27 |
| Mandatory Blockers | 12 |
| Potential Issues | 10 |

#### Component Information

| Property | Value |
|----------|-------|
| Language | Java, JavaScript, Batchfile, Dockerfile |
| Frameworks | Spring Cloud, Spring, Vue, Spring Boot, JakartaEE |
| Build tools | Maven, NodeJs |
| JDK version | 17 |

#### Cloud Readiness Issues

| Issue Name | Criticality | Story Points | Occurrences |
|------------|-------------|--------------|-------------|
| Avoid File System Logging in Configuration | Mandatory | 1 | [29](#Avoid_File_System_Logging_in_Configuration) |
| Caching - Spring Boot Cache library | Mandatory | 5 | [15](#Caching_-_Spring_Boot_Cache_library) |
| Caching - Redis Cache library | Mandatory | 5 | [9](#Caching_-_Redis_Cache_library) |
| File system - Java IO | Mandatory | 3 | [9](#File_system_-_Java_IO) |
| CRA: Default or well-known password detected | Mandatory | 3 | [5](#CRA_Default_or_well-known_password_detected) |
| CRA: Use of insecure random number generator java.util.Random | Mandatory | 5 | [3](#CRA_Use_of_insecure_random_number_generator_java_util_Random) |
| Hardcoded IP Address | Mandatory | 3 | [3](#Hardcoded_IP_Address) |
| File system - Java NIO | Mandatory | 3 | [2](#File_system_-_Java_NIO) |
| File system - java.net.URL/URI | Mandatory | 3 | [1](#File_system_-_java_net_URL_URI) |
| CRA: Use of weak hash algorithm MD5 | Mandatory | 5 | [1](#CRA_Use_of_weak_hash_algorithm_MD5) |
| Use of unsecured network protocols or URI libraries | Mandatory | 3 | [1](#Use_of_unsecured_network_protocols_or_URI_libraries) |
| Restricted configurations found | Potential | 2 | [7](#Restricted_configurations_found) |
| MySQL database found | Potential | 5 | [5](#MySQL_database_found) |
| The java.net.URLEncoder.encode method uses UTF-8 by default | Potential | 3 | [5](#The_java_net_URLEncoder_encode_method_uses_UTF-8_by_default) |
| Oracle database found | Potential | 8 | [2](#Oracle_database_found) |
| Java Mail API | Potential | 5 | [2](#Java_Mail_API) |
| CRA: Use of ThreadLocalRandom in potential security context | Potential | 3 | [2](#CRA_Use_of_ThreadLocalRandom_in_potential_security_context) |
| Embedded framework - Spring Security | Potential | 5 | [1](#Embedded_framework_-_Spring_Security) |
| Password found in configuration file | Potential | 3 | [1](#Password_found_in_configuration_file) |
| HTTP Session data storage | Potential | 5 | [1](#HTTP_Session_data_storage) |
| The java.net.URLDecoder.decode method uses UTF-8 by default | Potential | 3 | [1](#The_java_net_URLDecoder_decode_method_uses_UTF-8_by_default) |
| Localhost Usage | Optional | 3 | [19](#Localhost_Usage) |
| Quartz Scheduler usage detected | Optional | 13 | [1](#Quartz_Scheduler_usage_detected) |
| Environment variables/system properties | Optional | 3 | [1](#Environment_variables_system_properties) |

##### Issue Details

<details id="Avoid_File_System_Logging_in_Configuration">
<summary><b>Avoid File System Logging in Configuration</b> — affected files</summary>

- `ruoyi-auth/src/main/resources/logback.xml (line 16, col 0)`
- `ruoyi-auth/src/main/resources/logback.xml (line 17, col 0)`
- `ruoyi-auth/src/main/resources/logback.xml (line 38, col 0)`
- `ruoyi-auth/src/main/resources/logback.xml (line 39, col 0)`
- `ruoyi-modules/ruoyi-file/src/main/resources/logback.xml (line 4, col 0)`
- `ruoyi-modules/ruoyi-file/src/main/resources/logback.xml (line 16, col 0)`
- `ruoyi-modules/ruoyi-file/src/main/resources/logback.xml (line 17, col 0)`
- `ruoyi-modules/ruoyi-file/src/main/resources/logback.xml (line 38, col 0)`
- `ruoyi-modules/ruoyi-file/src/main/resources/logback.xml (line 39, col 0)`
- `ruoyi-visual/ruoyi-monitor/src/main/resources/logback.xml (line 16, col 0)`
- `ruoyi-visual/ruoyi-monitor/src/main/resources/logback.xml (line 17, col 0)`
- `ruoyi-visual/ruoyi-monitor/src/main/resources/logback.xml (line 38, col 0)`
- `ruoyi-visual/ruoyi-monitor/src/main/resources/logback.xml (line 39, col 0)`
- `ruoyi-gateway/src/main/resources/logback.xml (line 16, col 0)`
- `ruoyi-gateway/src/main/resources/logback.xml (line 17, col 0)`
- `ruoyi-gateway/src/main/resources/logback.xml (line 38, col 0)`
- `ruoyi-gateway/src/main/resources/logback.xml (line 39, col 0)`
- `ruoyi-modules/ruoyi-system/src/main/resources/logback.xml (line 16, col 0)`
- `ruoyi-modules/ruoyi-system/src/main/resources/logback.xml (line 17, col 0)`
- `ruoyi-modules/ruoyi-system/src/main/resources/logback.xml (line 38, col 0)`
- `ruoyi-modules/ruoyi-system/src/main/resources/logback.xml (line 39, col 0)`
- `ruoyi-modules/ruoyi-gen/src/main/resources/logback.xml (line 16, col 0)`
- `ruoyi-modules/ruoyi-gen/src/main/resources/logback.xml (line 17, col 0)`
- `ruoyi-modules/ruoyi-gen/src/main/resources/logback.xml (line 38, col 0)`
- `ruoyi-modules/ruoyi-gen/src/main/resources/logback.xml (line 39, col 0)`
- `ruoyi-modules/ruoyi-job/src/main/resources/logback.xml (line 16, col 0)`
- `ruoyi-modules/ruoyi-job/src/main/resources/logback.xml (line 17, col 0)`
- `ruoyi-modules/ruoyi-job/src/main/resources/logback.xml (line 38, col 0)`
- `ruoyi-modules/ruoyi-job/src/main/resources/logback.xml (line 39, col 0)`

</details>

<details id="Caching_-_Spring_Boot_Cache_library">
<summary><b>Caching - Spring Boot Cache library</b> — affected files</summary>

- `ruoyi-gateway/pom.xml (line 76, col 0)`
- `ruoyi-modules/ruoyi-system/pom.xml (line 59, col 0)`
- `ruoyi-auth/pom.xml (line 52, col 0)`
- `ruoyi-modules/ruoyi-file/pom.xml (line 60, col 0)`
- `ruoyi-common/ruoyi-common-redis/pom.xml (line 29, col 0)`
- `ruoyi-common/ruoyi-common-security/pom.xml (line 28, col 0)`
- `ruoyi-common/ruoyi-common-core/pom.xml (line 29, col 0)`
- `ruoyi-common/ruoyi-common-log/pom.xml (line 23, col 0)`
- `ruoyi-common/ruoyi-common-sensitive/pom.xml (line 23, col 0)`
- `ruoyi-modules/ruoyi-job/pom.xml (line 59, col 0)`
- `ruoyi-common/ruoyi-common-datascope/pom.xml (line 23, col 0)`
- `ruoyi-modules/ruoyi-gen/pom.xml (line 59, col 0)`
- `ruoyi-api/ruoyi-api-system/pom.xml (line 23, col 0)`
- `ruoyi-common/ruoyi-common-redis/src/main/java/com/ruoyi/common/redis/configure/RedisConfig.java (line 4, col 0)`
- `ruoyi-common/ruoyi-common-redis/src/main/java/com/ruoyi/common/redis/configure/RedisConfig.java (line 3, col 0)`

</details>

<details id="Caching_-_Redis_Cache_library">
<summary><b>Caching - Redis Cache library</b> — affected files</summary>

- `ruoyi-modules/ruoyi-system/pom.xml (line 59, col 0)`
- `ruoyi-common/ruoyi-common-security/pom.xml (line 34, col 0)`
- `ruoyi-modules/ruoyi-job/pom.xml (line 59, col 0)`
- `ruoyi-gateway/pom.xml (line 76, col 0)`
- `ruoyi-auth/pom.xml (line 52, col 0)`
- `ruoyi-modules/ruoyi-gen/pom.xml (line 59, col 0)`
- `ruoyi-common/ruoyi-common-redis/pom.xml (line 23, col 0)`
- `ruoyi-common/ruoyi-common-datascope/pom.xml (line 23, col 0)`
- `ruoyi-common/ruoyi-common-log/pom.xml (line 23, col 0)`

</details>

<details id="File_system_-_Java_IO">
<summary><b>File system - Java IO</b> — affected files</summary>

- `ruoyi-common/ruoyi-common-core/src/main/java/com/ruoyi/common/core/exception/file/FileUploadException.java (line 4, col 0)`
- `ruoyi-common/ruoyi-common-core/src/main/java/com/ruoyi/common/core/utils/ExceptionUtil.java (line 3, col 0)`
- `ruoyi-common/ruoyi-common-core/src/main/java/com/ruoyi/common/core/utils/file/FileTypeUtils.java (line 3, col 0)`
- `ruoyi-common/ruoyi-common-core/src/main/java/com/ruoyi/common/core/utils/file/FileUtils.java (line 3, col 0)`
- `ruoyi-common/ruoyi-common-core/src/main/java/com/ruoyi/common/core/utils/file/FileUtils.java (line 5, col 0)`
- `ruoyi-common/ruoyi-common-core/src/main/java/com/ruoyi/common/core/utils/file/FileUtils.java (line 4, col 0)`
- `ruoyi-modules/ruoyi-file/src/main/java/com/ruoyi/file/config/ResourcesConfig.java (line 3, col 0)`
- `ruoyi-modules/ruoyi-file/src/main/java/com/ruoyi/file/utils/FileUploadUtils.java (line 3, col 0)`
- `ruoyi-modules/ruoyi-gen/src/main/java/com/ruoyi/gen/service/GenTableServiceImpl.java (line 4, col 0)`

</details>

<details id="CRA_Default_or_well-known_password_detected">
<summary><b>CRA: Default or well-known password detected</b> — affected files</summary>

- `docker/docker-compose.yml (line 43, col 0)`
- `docker/nacos/conf/application.properties (line 5, col 0)`
- `ruoyi-api/ruoyi-api-system/src/main/java/com/ruoyi/system/api/domain/SysUser.java (line 208, col 0)`
- `ruoyi-auth/src/main/java/com/ruoyi/auth/form/LoginBody.java (line 37, col 0)`
- `ruoyi-auth/src/main/java/com/ruoyi/auth/form/UnLockBody.java (line 22, col 0)`

</details>

<details id="CRA_Use_of_insecure_random_number_generator_java_util_Random">
<summary><b>CRA: Use of insecure random number generator java.util.Random</b> — affected files</summary>

- `ruoyi-gateway/src/main/java/com/ruoyi/gateway/config/KaptchaTextCreator.java (line 19, col 0)`
- `ruoyi-common/ruoyi-common-core/src/main/java/com/ruoyi/common/core/utils/uuid/UUID.java (line 6, col 0)`
- `ruoyi-gateway/src/main/java/com/ruoyi/gateway/config/KaptchaTextCreator.java (line 3, col 0)`

</details>

<details id="Hardcoded_IP_Address">
<summary><b>Hardcoded IP Address</b> — affected files</summary>

- `ruoyi-common/ruoyi-common-core/src/main/java/com/ruoyi/common/core/utils/ip/IpUtils.java (line 68, col 0)`
- `ruoyi-common/ruoyi-common-core/src/main/java/com/ruoyi/common/core/utils/ip/IpUtils.java (line 80, col 0)`
- `ruoyi-common/ruoyi-common-core/src/main/java/com/ruoyi/common/core/utils/ip/IpUtils.java (line 228, col 0)`

</details>

<details id="File_system_-_Java_NIO">
<summary><b>File system - Java NIO</b> — affected files</summary>

- `ruoyi-modules/ruoyi-file/src/main/java/com/ruoyi/file/utils/FileUploadUtils.java (line 5, col 0)`
- `ruoyi-modules/ruoyi-file/src/main/java/com/ruoyi/file/utils/FileUploadUtils.java (line 87, col 0)`

</details>

<details id="File_system_-_java_net_URL_URI">
<summary><b>File system - java.net.URL/URI</b> — affected files</summary>

- `ruoyi-common/ruoyi-common-core/src/main/java/com/ruoyi/common/core/utils/file/ImageUtils.java (line 66, col 0)`

</details>

<details id="CRA_Use_of_weak_hash_algorithm_MD5">
<summary><b>CRA: Use of weak hash algorithm MD5</b> — affected files</summary>

- `ruoyi-common/ruoyi-common-core/src/main/java/com/ruoyi/common/core/utils/uuid/UUID.java (line 119, col 0)`

</details>

<details id="Use_of_unsecured_network_protocols_or_URI_libraries">
<summary><b>Use of unsecured network protocols or URI libraries</b> — affected files</summary>

- `ruoyi-common/ruoyi-common-core/src/main/java/com/ruoyi/common/core/constant/Constants.java (line 43, col 0)`

</details>

<details id="Restricted_configurations_found">
<summary><b>Restricted configurations found</b> — affected files</summary>

- `ruoyi-gateway/src/main/resources/bootstrap.yml (line 41, col 0)`
- `ruoyi-auth/src/main/resources/bootstrap.yml (line 26, col 0)`
- `ruoyi-visual/ruoyi-monitor/src/main/resources/bootstrap.yml (line 26, col 0)`
- `ruoyi-modules/ruoyi-gen/src/main/resources/bootstrap.yml (line 26, col 0)`
- `ruoyi-modules/ruoyi-system/src/main/resources/bootstrap.yml (line 26, col 0)`
- `ruoyi-modules/ruoyi-file/src/main/resources/bootstrap.yml (line 26, col 0)`
- `ruoyi-modules/ruoyi-job/src/main/resources/bootstrap.yml (line 26, col 0)`

</details>

<details id="MySQL_database_found">
<summary><b>MySQL database found</b> — affected files</summary>

- `ruoyi-modules/ruoyi-gen/pom.xml (line 53, col 0)`
- `ruoyi-modules/ruoyi-system/pom.xml (line 47, col 0)`
- `ruoyi-modules/ruoyi-job/pom.xml (line 53, col 0)`
- `docker/nacos/conf/application.properties (line 3, col 0)`

</details>

<details id="The_java_net_URLEncoder_encode_method_uses_UTF-8_by_default">
<summary><b>The java.net.URLEncoder.encode method uses UTF-8 by default</b> — affected files</summary>

- `ruoyi-common/ruoyi-common-core/src/main/java/com/ruoyi/common/core/utils/ServletUtils.java (line 250, col 0)`
- `ruoyi-common/ruoyi-common-core/src/main/java/com/ruoyi/common/core/utils/file/FileUtils.java (line 147, col 0)`
- `ruoyi-common/ruoyi-common-core/src/main/java/com/ruoyi/common/core/utils/file/FileUtils.java (line 158, col 0)`
- `ruoyi-common/ruoyi-common-core/src/main/java/com/ruoyi/common/core/utils/file/FileUtils.java (line 163, col 0)`
- `ruoyi-common/ruoyi-common-core/src/main/java/com/ruoyi/common/core/utils/file/FileUtils.java (line 250, col 0)`

</details>

<details id="Oracle_database_found">
<summary><b>Oracle database found</b> — affected files</summary>

- `ruoyi-common/ruoyi-common-datasource/pom.xml (line 30, col 0)`
- `ruoyi-modules/ruoyi-system/pom.xml (line 53, col 0)`

</details>

<details id="Java_Mail_API">
<summary><b>Java Mail API</b> — affected files</summary>

- `ruoyi-api/ruoyi-api-system/src/main/java/com/ruoyi/system/api/domain/SysDept.java (line 132, col 0)`
- `ruoyi-api/ruoyi-api-system/src/main/java/com/ruoyi/system/api/domain/SysUser.java (line 158, col 0)`

</details>

<details id="CRA_Use_of_ThreadLocalRandom_in_potential_security_context">
<summary><b>CRA: Use of ThreadLocalRandom in potential security context</b> — affected files</summary>

- `ruoyi-common/ruoyi-common-core/src/main/java/com/ruoyi/common/core/utils/uuid/UUID.java (line 482, col 0)`
- `ruoyi-common/ruoyi-common-core/src/main/java/com/ruoyi/common/core/utils/uuid/UUID.java (line 7, col 0)`

</details>

<details id="Embedded_framework_-_Spring_Security">
<summary><b>Embedded framework - Spring Security</b> — affected files</summary>

- `ruoyi-visual/ruoyi-monitor/pom.xml (line 53, col 0)`

</details>

<details id="Password_found_in_configuration_file">
<summary><b>Password found in configuration file</b> — affected files</summary>

- `docker/nacos/conf/application.properties (line 5, col 0)`

</details>

<details id="HTTP_Session_data_storage">
<summary><b>HTTP Session data storage</b> — affected files</summary>

- `ruoyi-common/ruoyi-common-core/src/main/java/com/ruoyi/common/core/utils/ServletUtils.java (line 14, col 0)`

</details>

<details id="The_java_net_URLDecoder_decode_method_uses_UTF-8_by_default">
<summary><b>The java.net.URLDecoder.decode method uses UTF-8 by default</b> — affected files</summary>

- `ruoyi-common/ruoyi-common-core/src/main/java/com/ruoyi/common/core/utils/ServletUtils.java (line 268, col 0)`

</details>

<details id="Localhost_Usage">
<summary><b>Localhost Usage</b> — affected files</summary>

- `ruoyi-auth/src/main/resources/bootstrap.yml (line 17, col 0)`
- `ruoyi-auth/src/main/resources/bootstrap.yml (line 20, col 0)`
- `ruoyi-modules/ruoyi-gen/src/main/resources/bootstrap.yml (line 17, col 0)`
- `ruoyi-modules/ruoyi-gen/src/main/resources/bootstrap.yml (line 20, col 0)`
- `ruoyi-modules/ruoyi-file/src/main/resources/bootstrap.yml (line 17, col 0)`
- `ruoyi-modules/ruoyi-file/src/main/resources/bootstrap.yml (line 20, col 0)`
- `ruoyi-gateway/src/main/resources/bootstrap.yml (line 17, col 0)`
- `ruoyi-gateway/src/main/resources/bootstrap.yml (line 20, col 0)`
- `ruoyi-gateway/src/main/resources/bootstrap.yml (line 26, col 0)`
- `ruoyi-gateway/src/main/resources/bootstrap.yml (line 31, col 0)`
- `ruoyi-modules/ruoyi-job/src/main/resources/bootstrap.yml (line 17, col 0)`
- `ruoyi-modules/ruoyi-job/src/main/resources/bootstrap.yml (line 20, col 0)`
- `ruoyi-common/ruoyi-common-core/src/main/java/com/ruoyi/common/core/utils/ip/IpUtils.java (line 68, col 0)`
- `ruoyi-common/ruoyi-common-core/src/main/java/com/ruoyi/common/core/utils/ip/IpUtils.java (line 80, col 0)`
- `ruoyi-common/ruoyi-common-core/src/main/java/com/ruoyi/common/core/utils/ip/IpUtils.java (line 228, col 0)`
- `ruoyi-modules/ruoyi-system/src/main/resources/bootstrap.yml (line 17, col 0)`
- `ruoyi-modules/ruoyi-system/src/main/resources/bootstrap.yml (line 20, col 0)`
- `ruoyi-visual/ruoyi-monitor/src/main/resources/bootstrap.yml (line 17, col 0)`
- `ruoyi-visual/ruoyi-monitor/src/main/resources/bootstrap.yml (line 20, col 0)`

</details>

<details id="Quartz_Scheduler_usage_detected">
<summary><b>Quartz Scheduler usage detected</b> — affected files</summary>

- `ruoyi-modules/ruoyi-job/pom.xml (line 47, col 0)`

</details>

<details id="Environment_variables_system_properties">
<summary><b>Environment variables/system properties</b> — affected files</summary>

- `ruoyi-modules/ruoyi-gen/src/main/java/com/ruoyi/gen/service/GenTableServiceImpl.java (line 550, col 0)`

</details>

#### Upgrade Issues

| Issue Name | Criticality | Story Points | Occurrences |
|------------|-------------|--------------|-------------|
| java.net.URL Constructors Are Deprecated | Mandatory | 3 | [1](#java_net_URL_Constructors_Are_Deprecated) |
| Jakarta EE Version is not the latest stable | Optional | 8 | [14](#Jakarta_EE_Version_is_not_the_latest_stable) |
| Java Version is not the latest LTS | Optional | 8 | [1](#Java_Version_is_not_the_latest_LTS) |

##### Issue Details

<details id="java_net_URL_Constructors_Are_Deprecated">
<summary><b>java.net.URL Constructors Are Deprecated</b> — affected files</summary>

- `ruoyi-common/ruoyi-common-core/src/main/java/com/ruoyi/common/core/utils/file/ImageUtils.java (line 66, col 0)`

</details>

<details id="Jakarta_EE_Version_is_not_the_latest_stable">
<summary><b>Jakarta EE Version is not the latest stable</b> — affected files</summary>

- `ruoyi-modules/ruoyi-gen/pom.xml (line 59, col 0)`
- `ruoyi-gateway/pom.xml (line 70, col 0)`
- `ruoyi-gateway/pom.xml (line 76, col 0)`
- `ruoyi-common/ruoyi-common-core/pom.xml (line 95, col 0)`
- `ruoyi-common/ruoyi-common-log/pom.xml (line 23, col 0)`
- `ruoyi-api/ruoyi-api-system/pom.xml (line 23, col 0)`
- `ruoyi-modules/ruoyi-job/pom.xml (line 59, col 0)`
- `ruoyi-modules/ruoyi-file/pom.xml (line 60, col 0)`
- `ruoyi-common/ruoyi-common-datascope/pom.xml (line 23, col 0)`
- `ruoyi-common/ruoyi-common-sensitive/pom.xml (line 23, col 0)`
- `ruoyi-common/ruoyi-common-security/pom.xml (line 28, col 0)`
- `ruoyi-modules/ruoyi-system/pom.xml (line 59, col 0)`
- `ruoyi-common/ruoyi-common-redis/pom.xml (line 29, col 0)`
- `ruoyi-auth/pom.xml (line 52, col 0)`

</details>

<details id="Java_Version_is_not_the_latest_LTS">
<summary><b>Java Version is not the latest LTS</b> — affected files</summary>

- `pom.xml (line 19, col 0)`

</details>

---

#### Codebase Insights

> **Note:** These documents are generated by AI and may contain inaccuracies or incomplete information. Please review carefully.

> **Codebase Insights aren't available yet.**
>
> These documents are generated when assessment runs with **Full analysis** coverage. Re-run the assessment and set `analysisCoverage: full` to enable them.

[Share feedback](https://aka.ms/ghcp-appmod/feedback)


## RuoYi-Cloud.ruoyi-ui

### RuoYi-Cloud.ruoyi-ui (JavaScript/TypeScript)


JavaScript/TypeScript Dependency Assessment

#### Component Information

| Property | Value |
|----------|-------|
| Language | JavaScript/TypeScript |
| Build tools | npm |

#### Summary

| Update Type | Count |
|-------------|-------|
| **Total Updates** | **25** |
| Patch | 3 |
| Minor | 7 |
| Major | 14 |
| Major (0.x) | 1 |

#### Dependency Updates

| Package | Current | Target | Type |
|---------|---------|--------|------|
| clipboard | 2.0.8 | 2.0.11 | Patch |
| js-cookie | 3.0.1 | 3.0.8 | Patch |
| quill | 2.0.2 | 2.0.3 | Patch |
| connect | 3.6.6 | 3.7.0 | Minor |
| core-js | 3.37.1 | 3.49.0 | Minor |
| js-beautify | 1.13.0 | 1.15.4 | Minor |
| jsencrypt | 3.0.0-rc.1 | 3.5.4 | Minor |
| sass | 1.32.13 | 1.101.0 | Minor |
| sortablejs | 1.10.2 | 1.15.7 | Minor |
| vue-template-compiler | 2.6.12 | 2.7.16 | Minor |
| @vue/cli-plugin-babel | 4.4.6 | 5.0.9 | Major |
| @vue/cli-service | 4.4.6 | 5.0.9 | Major |
| axios | 0.30.3 | 1.18.1 | Major |
| chalk | 4.1.0 | 5.6.2 | Major |
| compression-webpack-plugin | 6.1.2 | 12.0.0 | Major |
| echarts | 5.4.0 | 6.1.0 | Major |
| fuse.js | 6.4.3 | 7.4.2 | Major |
| highlight.js | 9.18.5 | 11.11.1 | Major |
| sass-loader | 10.1.1 | 17.0.0 | Major |
| screenfull | 5.0.2 | 6.0.2 | Major |
| svg-sprite-loader | 5.1.1 | 6.0.11 | Major |
| vue | 2.6.12 | 3.5.38 | Major |
| vue-router | 3.4.9 | 5.1.0 | Major |
| vuex | 3.6.0 | 4.1.0 | Major |
| vue-cropper | 0.5.5 | 0.6.5 | Major (0.x) |

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


