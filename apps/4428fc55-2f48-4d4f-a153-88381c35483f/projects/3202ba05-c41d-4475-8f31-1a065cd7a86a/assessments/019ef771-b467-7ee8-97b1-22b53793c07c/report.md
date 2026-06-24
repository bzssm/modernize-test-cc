# ghcpapdw/ZavaAccountManager

> Consolidated assessment across all units detected under this component root. Each unit's full report is inlined below; raw per-unit artefacts (report JSON, facts, scenarios) remain in their subfolders.

## Units

| Unit |
|------|
| [ZavaAccountManager](#zavaaccountmanager) |

## ZavaAccountManager

### ZavaAccountManager (.NET)


#### Summary

| Metric | Value |
|--------|-------|
| Total Issues | 5 |
| Mandatory Blockers | 0 |
| Potential Issues | 3 |

#### Component Information

| Property | Value |
|----------|-------|
| Language | C# |
| Frameworks | .NETFramework,Version=v4.8 |
| Build tools | MSBuild |

#### Cloud Readiness Issues

| Issue Name | Criticality | Story Points | Occurrences |
|------------|-------------|--------------|-------------|
| 检测到通过 HTTP 访问外部资源 | Potential | 3 | [4](#检测到通过_HTTP_访问外部资源) |
| 检测到硬编码的 URL | Potential | 1 | [4](#检测到硬编码的_URL) |
| 检测到 SQL 数据库连接 | Potential | 3 | [1](#检测到_SQL_数据库连接) |
| 检测到 System.Data.SqlClient 依赖项 | Optional | 3 | [33](#检测到_System_Data_SqlClient_依赖项) |
| 检测到没有配置生成器的连接字符串 | Optional | 3 | [2](#检测到没有配置生成器的连接字符串) |

##### Issue Details

<details id="检测到通过_HTTP_访问外部资源">
<summary><b>检测到通过 HTTP 访问外部资源</b> — affected files</summary>

- `modernize-cc-assess\019ef771-b467-7ee8-97b1-22b53793c07c\repos\monotestmatrix\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 4301)`
- `modernize-cc-assess\019ef771-b467-7ee8-97b1-22b53793c07c\repos\monotestmatrix\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 4316)`
- `modernize-cc-assess\019ef771-b467-7ee8-97b1-22b53793c07c\repos\monotestmatrix\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 5031)`
- `modernize-cc-assess\019ef771-b467-7ee8-97b1-22b53793c07c\repos\monotestmatrix\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 5046)`

</details>

<details id="检测到硬编码的_URL">
<summary><b>检测到硬编码的 URL</b> — affected files</summary>

- `modernize-cc-assess\019ef771-b467-7ee8-97b1-22b53793c07c\repos\monotestmatrix\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 4386)`
- `modernize-cc-assess\019ef771-b467-7ee8-97b1-22b53793c07c\repos\monotestmatrix\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 5116)`
- `modernize-cc-assess\019ef771-b467-7ee8-97b1-22b53793c07c\repos\monotestmatrix\ghcpapdw\ZavaAccountManager\Login.aspx.cs (line 0, col 472)`
- `modernize-cc-assess\019ef771-b467-7ee8-97b1-22b53793c07c\repos\monotestmatrix\ghcpapdw\ZavaAccountManager\Logout.aspx.cs (line 0, col 306)`

</details>

<details id="检测到_SQL_数据库连接">
<summary><b>检测到 SQL 数据库连接</b> — affected files</summary>

- `modernize-cc-assess\019ef771-b467-7ee8-97b1-22b53793c07c\repos\monotestmatrix\ghcpapdw\ZavaAccountManager\web.config`

</details>

<details id="检测到_System_Data_SqlClient_依赖项">
<summary><b>检测到 System.Data.SqlClient 依赖项</b> — affected files</summary>

- `modernize-cc-assess\019ef771-b467-7ee8-97b1-22b53793c07c\repos\monotestmatrix\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 3156)`
- `modernize-cc-assess\019ef771-b467-7ee8-97b1-22b53793c07c\repos\monotestmatrix\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 3166)`
- `modernize-cc-assess\019ef771-b467-7ee8-97b1-22b53793c07c\repos\monotestmatrix\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 4020)`
- `modernize-cc-assess\019ef771-b467-7ee8-97b1-22b53793c07c\repos\monotestmatrix\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 4030)`
- `modernize-cc-assess\019ef771-b467-7ee8-97b1-22b53793c07c\repos\monotestmatrix\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 6101)`
- `modernize-cc-assess\019ef771-b467-7ee8-97b1-22b53793c07c\repos\monotestmatrix\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 6111)`
- `modernize-cc-assess\019ef771-b467-7ee8-97b1-22b53793c07c\repos\monotestmatrix\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 3597)`
- `modernize-cc-assess\019ef771-b467-7ee8-97b1-22b53793c07c\repos\monotestmatrix\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 3607)`
- `modernize-cc-assess\019ef771-b467-7ee8-97b1-22b53793c07c\repos\monotestmatrix\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 2179)`
- `modernize-cc-assess\019ef771-b467-7ee8-97b1-22b53793c07c\repos\monotestmatrix\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 2189)`
- `modernize-cc-assess\019ef771-b467-7ee8-97b1-22b53793c07c\repos\monotestmatrix\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 3326)`
- `modernize-cc-assess\019ef771-b467-7ee8-97b1-22b53793c07c\repos\monotestmatrix\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 3336)`
- `modernize-cc-assess\019ef771-b467-7ee8-97b1-22b53793c07c\repos\monotestmatrix\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 3800)`
- `modernize-cc-assess\019ef771-b467-7ee8-97b1-22b53793c07c\repos\monotestmatrix\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 3810)`
- `modernize-cc-assess\019ef771-b467-7ee8-97b1-22b53793c07c\repos\monotestmatrix\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 2924)`
- `modernize-cc-assess\019ef771-b467-7ee8-97b1-22b53793c07c\repos\monotestmatrix\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 2934)`
- `modernize-cc-assess\019ef771-b467-7ee8-97b1-22b53793c07c\repos\monotestmatrix\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 5807)`
- `modernize-cc-assess\019ef771-b467-7ee8-97b1-22b53793c07c\repos\monotestmatrix\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 5817)`
- `modernize-cc-assess\019ef771-b467-7ee8-97b1-22b53793c07c\repos\monotestmatrix\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 1185)`
- `modernize-cc-assess\019ef771-b467-7ee8-97b1-22b53793c07c\repos\monotestmatrix\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 1195)`
- `modernize-cc-assess\019ef771-b467-7ee8-97b1-22b53793c07c\repos\monotestmatrix\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 2280)`
- `modernize-cc-assess\019ef771-b467-7ee8-97b1-22b53793c07c\repos\monotestmatrix\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 2292)`
- `modernize-cc-assess\019ef771-b467-7ee8-97b1-22b53793c07c\repos\monotestmatrix\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 3427)`
- `modernize-cc-assess\019ef771-b467-7ee8-97b1-22b53793c07c\repos\monotestmatrix\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 3439)`
- `modernize-cc-assess\019ef771-b467-7ee8-97b1-22b53793c07c\repos\monotestmatrix\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 3901)`
- `modernize-cc-assess\019ef771-b467-7ee8-97b1-22b53793c07c\repos\monotestmatrix\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 3913)`
- `modernize-cc-assess\019ef771-b467-7ee8-97b1-22b53793c07c\repos\monotestmatrix\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 3025)`
- `modernize-cc-assess\019ef771-b467-7ee8-97b1-22b53793c07c\repos\monotestmatrix\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 3037)`
- `modernize-cc-assess\019ef771-b467-7ee8-97b1-22b53793c07c\repos\monotestmatrix\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 5908)`
- `modernize-cc-assess\019ef771-b467-7ee8-97b1-22b53793c07c\repos\monotestmatrix\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 5920)`
- `modernize-cc-assess\019ef771-b467-7ee8-97b1-22b53793c07c\repos\monotestmatrix\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 1286)`
- `modernize-cc-assess\019ef771-b467-7ee8-97b1-22b53793c07c\repos\monotestmatrix\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 1298)`
- `modernize-cc-assess\019ef771-b467-7ee8-97b1-22b53793c07c\repos\monotestmatrix\ghcpapdw\ZavaAccountManager\web.config`

</details>

<details id="检测到没有配置生成器的连接字符串">
<summary><b>检测到没有配置生成器的连接字符串</b> — affected files</summary>

- `modernize-cc-assess\019ef771-b467-7ee8-97b1-22b53793c07c\repos\monotestmatrix\ghcpapdw\ZavaAccountManager\web.config`

</details>

#### DotNET Upgrade Issues [View Details](ZavaAccountManager/scenarios/dotnet-version-upgrade/assessment.md)

| Issue Category | Criticality | Story Points |
|----------------|-------------|--------------|
| 对所选 .NET 版本二进制不兼容 | Mandatory | 1 |
| 项目文件需要转换为 SDK 样式。 | Mandatory | 1 |
| 需要更改项目的目标框架 | Mandatory | 1 |
| Legacy Configuration System | Mandatory | 2 |
| ASP.NET Framework (System.Web) | Mandatory | 4 |
| 对所选 .NET 版本源代码不兼容 | Potential | 1 |

##### Issue Details

<details>
<summary><b>对所选 .NET 版本二进制不兼容</b> — affected files</summary>

- `Site.Master.designer.cs (line 0, col 430)`
- `Site.Master.designer.cs (line 0, col 353)`
- `Site.Master.designer.cs (line 0, col 293)`
- `Site.Master.designer.cs (line 0, col 230)`
- `Site.Master.designer.cs (line 0, col 168)`
- `Site.Master.designer.cs (line 0, col 107)`
- `Site.Master.cs (line 0, col 372)`
- `Site.Master.cs (line 0, col 337)`
- `Site.Master.cs (line 0, col 308)`
- `Site.Master.cs (line 0, col 248)`
- `Site.Master.cs (line 0, col 157)`
- `Site.Master.cs (line 0, col 94)`
- `Logout.aspx.cs (line 0, col 349)`
- `Logout.aspx.cs (line 0, col 230)`
- `Logout.aspx.cs (line 0, col 200)`
- `Logout.aspx.cs (line 0, col 143)`
- `Login.aspx.designer.cs (line 0, col 171)`
- `Login.aspx.designer.cs (line 0, col 106)`
- `Login.aspx.cs (line 0, col 567)`
- `Login.aspx.cs (line 0, col 387)`
- `Login.aspx.cs (line 0, col 333)`
- `Login.aspx.cs (line 0, col 286)`
- `Login.aspx.cs (line 0, col 258)`
- `Login.aspx.cs (line 0, col 190)`
- `Login.aspx.cs (line 0, col 133)`
- `Default.aspx.designer.cs (line 0, col 577)`
- `Default.aspx.designer.cs (line 0, col 513)`
- `Default.aspx.designer.cs (line 0, col 439)`
- `Default.aspx.designer.cs (line 0, col 369)`
- `Default.aspx.designer.cs (line 0, col 308)`
- `Default.aspx.designer.cs (line 0, col 235)`
- `Default.aspx.designer.cs (line 0, col 173)`
- `Default.aspx.designer.cs (line 0, col 102)`
- `Default.aspx.cs (line 0, col 6326)`
- `Default.aspx.cs (line 0, col 6294)`
- `Default.aspx.cs (line 0, col 6231)`
- `Default.aspx.cs (line 0, col 6197)`
- `Default.aspx.cs (line 0, col 4232)`
- `Default.aspx.cs (line 0, col 4197)`
- `Default.aspx.cs (line 0, col 4168)`
- `Default.aspx.cs (line 0, col 4151)`
- `Default.aspx.cs (line 0, col 4071)`
- `Default.aspx.cs (line 0, col 3717)`
- `Default.aspx.cs (line 0, col 3693)`
- `Default.aspx.cs (line 0, col 3232)`
- `Default.aspx.cs (line 0, col 3207)`
- `Default.aspx.cs (line 0, col 1702)`
- `Default.aspx.cs (line 0, col 2813)`
- `Default.aspx.cs (line 0, col 2768)`
- `Default.aspx.cs (line 0, col 2126)`
- `Default.aspx.cs (line 0, col 2000)`
- `Default.aspx.cs (line 0, col 1912)`
- `Default.aspx.cs (line 0, col 1848)`
- `Default.aspx.cs (line 0, col 1786)`
- `Default.aspx.cs (line 0, col 902)`
- `Default.aspx.cs (line 0, col 1634)`
- `Default.aspx.cs (line 0, col 1584)`
- `Default.aspx.cs (line 0, col 1551)`
- `Default.aspx.cs (line 0, col 1506)`
- `Default.aspx.cs (line 0, col 1145)`
- `Default.aspx.cs (line 0, col 1085)`
- `Default.aspx.cs (line 0, col 987)`
- `Default.aspx.cs (line 0, col 822)`
- `Default.aspx.cs (line 0, col 788)`
- `Default.aspx.cs (line 0, col 722)`
- `Default.aspx.cs (line 0, col 678)`
- `Default.aspx.cs (line 0, col 559)`
- `Default.aspx.cs (line 0, col 508)`
- `Default.aspx.cs (line 0, col 454)`
- `Default.aspx.cs (line 0, col 370)`
- `Default.aspx.cs (line 0, col 341)`
- `Default.aspx.cs (line 0, col 230)`

</details>

<details>
<summary><b>项目文件需要转换为 SDK 样式。</b> — affected files</summary>

- `ZavaAccountManager.csproj`

</details>

<details>
<summary><b>需要更改项目的目标框架</b> — affected files</summary>

- `ZavaAccountManager.csproj`

</details>

<details>
<summary><b>对所选 .NET 版本源代码不兼容</b> — affected files</summary>

- `Site.Master.cs (line 0, col 248)`
- `Site.Master.cs (line 0, col 157)`
- `Logout.aspx.cs (line 0, col 349)`
- `Logout.aspx.cs (line 0, col 230)`
- `Login.aspx.cs (line 0, col 387)`
- `Login.aspx.cs (line 0, col 333)`
- `Login.aspx.cs (line 0, col 286)`
- `Login.aspx.cs (line 0, col 258)`
- `Login.aspx.cs (line 0, col 190)`
- `Default.aspx.cs (line 0, col 6176)`
- `Default.aspx.cs (line 0, col 6132)`
- `Default.aspx.cs (line 0, col 6095)`
- `Default.aspx.cs (line 0, col 5902)`
- `Default.aspx.cs (line 0, col 5801)`
- `Default.aspx.cs (line 0, col 5024)`
- `Default.aspx.cs (line 0, col 4294)`
- `Default.aspx.cs (line 0, col 4051)`
- `Default.aspx.cs (line 0, col 4014)`
- `Default.aspx.cs (line 0, col 3895)`
- `Default.aspx.cs (line 0, col 3794)`
- `Default.aspx.cs (line 0, col 3673)`
- `Default.aspx.cs (line 0, col 3628)`
- `Default.aspx.cs (line 0, col 3591)`
- `Default.aspx.cs (line 0, col 3421)`
- `Default.aspx.cs (line 0, col 3320)`
- `Default.aspx.cs (line 0, col 3187)`
- `Default.aspx.cs (line 0, col 3150)`
- `Default.aspx.cs (line 0, col 3019)`
- `Default.aspx.cs (line 0, col 2918)`
- `Default.aspx.cs (line 0, col 2745)`
- `Default.aspx.cs (line 0, col 2736)`
- `Default.aspx.cs (line 0, col 2698)`
- `Default.aspx.cs (line 0, col 2604)`
- `Default.aspx.cs (line 0, col 2565)`
- `Default.aspx.cs (line 0, col 2527)`
- `Default.aspx.cs (line 0, col 2274)`
- `Default.aspx.cs (line 0, col 2173)`
- `Default.aspx.cs (line 0, col 1466)`
- `Default.aspx.cs (line 0, col 1457)`
- `Default.aspx.cs (line 0, col 1413)`
- `Default.aspx.cs (line 0, col 1280)`
- `Default.aspx.cs (line 0, col 1179)`
- `Default.aspx.cs (line 0, col 454)`
- `Default.aspx.cs (line 0, col 370)`
- `Default.aspx.cs (line 0, col 341)`

</details>

---

#### Codebase Insights

> **Note:** These documents are generated by AI and may contain inaccuracies or incomplete information. Please review carefully.

> **Codebase Insights aren't available yet.**
>
> These documents are generated when assessment runs with **Full analysis** coverage. Re-run the assessment and set `analysisCoverage: full` to enable them.

[Share feedback](https://aka.ms/ghcp-appmod/feedback)


