# ZavaAccountManager

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

- `modernize-cc-assess\019ed9c2-cac9-76e2-be22-fe9a93c1a25a\repos\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 4301)`
- `modernize-cc-assess\019ed9c2-cac9-76e2-be22-fe9a93c1a25a\repos\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 4316)`
- `modernize-cc-assess\019ed9c2-cac9-76e2-be22-fe9a93c1a25a\repos\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 5031)`
- `modernize-cc-assess\019ed9c2-cac9-76e2-be22-fe9a93c1a25a\repos\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 5046)`

</details>

<details id="检测到硬编码的_URL">
<summary><b>检测到硬编码的 URL</b> — affected files</summary>

- `modernize-cc-assess\019ed9c2-cac9-76e2-be22-fe9a93c1a25a\repos\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 4386)`
- `modernize-cc-assess\019ed9c2-cac9-76e2-be22-fe9a93c1a25a\repos\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 5116)`
- `modernize-cc-assess\019ed9c2-cac9-76e2-be22-fe9a93c1a25a\repos\ghcpapdw\ZavaAccountManager\Login.aspx.cs (line 0, col 472)`
- `modernize-cc-assess\019ed9c2-cac9-76e2-be22-fe9a93c1a25a\repos\ghcpapdw\ZavaAccountManager\Logout.aspx.cs (line 0, col 306)`

</details>

<details id="检测到_SQL_数据库连接">
<summary><b>检测到 SQL 数据库连接</b> — affected files</summary>

- `modernize-cc-assess\019ed9c2-cac9-76e2-be22-fe9a93c1a25a\repos\ghcpapdw\ZavaAccountManager\web.config`

</details>

<details id="检测到_System_Data_SqlClient_依赖项">
<summary><b>检测到 System.Data.SqlClient 依赖项</b> — affected files</summary>

- `modernize-cc-assess\019ed9c2-cac9-76e2-be22-fe9a93c1a25a\repos\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 3156)`
- `modernize-cc-assess\019ed9c2-cac9-76e2-be22-fe9a93c1a25a\repos\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 3166)`
- `modernize-cc-assess\019ed9c2-cac9-76e2-be22-fe9a93c1a25a\repos\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 4020)`
- `modernize-cc-assess\019ed9c2-cac9-76e2-be22-fe9a93c1a25a\repos\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 4030)`
- `modernize-cc-assess\019ed9c2-cac9-76e2-be22-fe9a93c1a25a\repos\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 6101)`
- `modernize-cc-assess\019ed9c2-cac9-76e2-be22-fe9a93c1a25a\repos\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 6111)`
- `modernize-cc-assess\019ed9c2-cac9-76e2-be22-fe9a93c1a25a\repos\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 3597)`
- `modernize-cc-assess\019ed9c2-cac9-76e2-be22-fe9a93c1a25a\repos\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 3607)`
- `modernize-cc-assess\019ed9c2-cac9-76e2-be22-fe9a93c1a25a\repos\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 2179)`
- `modernize-cc-assess\019ed9c2-cac9-76e2-be22-fe9a93c1a25a\repos\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 2189)`
- `modernize-cc-assess\019ed9c2-cac9-76e2-be22-fe9a93c1a25a\repos\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 3326)`
- `modernize-cc-assess\019ed9c2-cac9-76e2-be22-fe9a93c1a25a\repos\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 3336)`
- `modernize-cc-assess\019ed9c2-cac9-76e2-be22-fe9a93c1a25a\repos\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 3800)`
- `modernize-cc-assess\019ed9c2-cac9-76e2-be22-fe9a93c1a25a\repos\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 3810)`
- `modernize-cc-assess\019ed9c2-cac9-76e2-be22-fe9a93c1a25a\repos\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 2924)`
- `modernize-cc-assess\019ed9c2-cac9-76e2-be22-fe9a93c1a25a\repos\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 2934)`
- `modernize-cc-assess\019ed9c2-cac9-76e2-be22-fe9a93c1a25a\repos\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 5807)`
- `modernize-cc-assess\019ed9c2-cac9-76e2-be22-fe9a93c1a25a\repos\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 5817)`
- `modernize-cc-assess\019ed9c2-cac9-76e2-be22-fe9a93c1a25a\repos\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 1185)`
- `modernize-cc-assess\019ed9c2-cac9-76e2-be22-fe9a93c1a25a\repos\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 1195)`
- `modernize-cc-assess\019ed9c2-cac9-76e2-be22-fe9a93c1a25a\repos\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 2280)`
- `modernize-cc-assess\019ed9c2-cac9-76e2-be22-fe9a93c1a25a\repos\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 2292)`
- `modernize-cc-assess\019ed9c2-cac9-76e2-be22-fe9a93c1a25a\repos\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 3427)`
- `modernize-cc-assess\019ed9c2-cac9-76e2-be22-fe9a93c1a25a\repos\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 3439)`
- `modernize-cc-assess\019ed9c2-cac9-76e2-be22-fe9a93c1a25a\repos\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 3901)`
- `modernize-cc-assess\019ed9c2-cac9-76e2-be22-fe9a93c1a25a\repos\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 3913)`
- `modernize-cc-assess\019ed9c2-cac9-76e2-be22-fe9a93c1a25a\repos\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 3025)`
- `modernize-cc-assess\019ed9c2-cac9-76e2-be22-fe9a93c1a25a\repos\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 3037)`
- `modernize-cc-assess\019ed9c2-cac9-76e2-be22-fe9a93c1a25a\repos\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 5908)`
- `modernize-cc-assess\019ed9c2-cac9-76e2-be22-fe9a93c1a25a\repos\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 5920)`
- `modernize-cc-assess\019ed9c2-cac9-76e2-be22-fe9a93c1a25a\repos\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 1286)`
- `modernize-cc-assess\019ed9c2-cac9-76e2-be22-fe9a93c1a25a\repos\ghcpapdw\ZavaAccountManager\Default.aspx.cs (line 0, col 1298)`
- `modernize-cc-assess\019ed9c2-cac9-76e2-be22-fe9a93c1a25a\repos\ghcpapdw\ZavaAccountManager\web.config`

</details>

<details id="检测到没有配置生成器的连接字符串">
<summary><b>检测到没有配置生成器的连接字符串</b> — affected files</summary>

- `modernize-cc-assess\019ed9c2-cac9-76e2-be22-fe9a93c1a25a\repos\ghcpapdw\ZavaAccountManager\web.config`

</details>

---

#### Codebase Insights

> **Note:** These documents are generated by AI and may contain inaccuracies or incomplete information. Please review carefully.

> **Codebase Insights aren't available yet.**
>
> These documents are generated when assessment runs with **Full analysis** coverage. Re-run the assessment and set `analysisCoverage: full` to enable them.

[Share feedback](https://aka.ms/ghcp-appmod/feedback)


