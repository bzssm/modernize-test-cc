# baget

> Consolidated assessment across all units detected under this component root. Each unit's full report is inlined below; raw per-unit artefacts (report JSON, facts, scenarios) remain in their subfolders.

## Units

| Unit |
|------|
| [baget](#baget) |

## baget

### baget (.NET)


#### Summary

| Metric | Value |
|--------|-------|
| Total Issues | 1 |
| Mandatory Blockers | 0 |
| Potential Issues | 1 |

#### Component Information

| Property | Value |
|----------|-------|
| Language | C# |
| Frameworks | netstandard2.0 |
| Build tools | MSBuild |

#### Cloud Readiness Issues

| Issue Name | Criticality | Story Points | Occurrences |
|------------|-------------|--------------|-------------|
| 检测到 Azure 外部云服务的依赖项 | Potential | 3 | [8](#检测到_Azure_外部云服务的依赖项) |

##### Issue Details

<details id="检测到_Azure_外部云服务的依赖项">
<summary><b>检测到 Azure 外部云服务的依赖项</b> — affected files</summary>

- `src\BaGet.Aliyun\AliyunApplicationExtensions.cs (line 23, col 27)`
- `src\BaGet.Aliyun\AliyunStorageService.cs (line 15, col 25)`
- `src\BaGet.Aliyun\AliyunStorageService.cs (line 17, col 84)`
- `src\BaGet.Aliyun\AliyunStorageService.cs (line 62, col 12)`
- `src\BaGet.Aliyun\AliyunStorageService.cs (line 62, col 31)`
- `src\BaGet.Aliyun\AliyunStorageService.cs (line 39, col 16)`
- `src\BaGet.Aliyun\AliyunStorageService.cs (line 67, col 12)`
- `src\BaGet.Aliyun\AliyunStorageService.cs (line 67, col 39)`

</details>

#### DotNET Upgrade Issues [View Details](baget/scenarios/dotnet-version-upgrade/assessment.md)

| Issue Category | Criticality | Story Points |
|----------------|-------------|--------------|
| 需要更改项目的目标框架 | Mandatory | 1 |
| 对所选 .NET 版本二进制不兼容 | Mandatory | 1 |
| 所选 .NET 版本中的行为变化 | Potential | 1 |
| 建议升级 NuGet 包 | Potential | 1 |
| 对所选 .NET 版本源代码不兼容 | Potential | 1 |
| NuGet 包已弃用 | Optional | 1 |
| NuGet 包有安全漏洞 | Optional | 1 |

##### Issue Details

<details>
<summary><b>需要更改项目的目标框架</b> — affected files</summary>

- `tests\BaGet.Core.Tests\BaGet.Core.Tests.csproj`
- `src\BaGet\BaGet.csproj`
- `samples\BaGet.Protocol.Samples.Tests\BaGet.Protocol.Samples.Tests.csproj`
- `tests\BaGet.Protocol.Tests\BaGet.Protocol.Tests.csproj`
- `tests\BaGet.Tests\BaGet.Tests.csproj`
- `src\BaGet.Web\BaGet.Web.csproj`
- `tests\BaGet.Web.Tests\BaGet.Web.Tests.csproj`
- `samples\BaGetWebApplication\BaGetWebApplication.csproj`

</details>

<details>
<summary><b>对所选 .NET 版本二进制不兼容</b> — affected files</summary>

- `src\BaGet\Startup.cs (line 79, col 12)`

</details>

<details>
<summary><b>所选 .NET 版本中的行为变化</b> — affected files</summary>

- `src\BaGet.Aliyun\AliyunStorageService.cs (line 52, col 12)`
- `src\BaGet.Aws\S3StorageService.cs (line 68, col 12)`
- `src\BaGet.Azure\Table\PackageEntityExtensions.cs (line 46, col 8)`
- `src\BaGet.Azure\Table\PackageEntityExtensions.cs (line 48, col 12)`
- `src\BaGet.Azure\Table\PackageEntityExtensions.cs (line 12, col 12)`
- `src\BaGet.Azure\Storage\BlobStorageService.cs (line 38, col 12)`
- `src\BaGet.Core\Upstream\PackageDownloadsJsonSource.cs (line 96, col 12)`
- `src\BaGet.Core\Upstream\Clients\V3UpstreamClient.cs (line 119, col 8)`
- `src\BaGet.Core\Upstream\Clients\V3UpstreamClient.cs (line 123, col 12)`
- `src\BaGet.Core\Upstream\Clients\V3UpstreamClient.cs (line 90, col 12)`
- `src\BaGet.Core\Upstream\Clients\V2UpstreamClient.cs (line 132, col 12)`
- `src\BaGet.Core\Upstream\Clients\V2UpstreamClient.cs (line 48, col 12)`
- `src\BaGet.Core\Upstream\Clients\V2UpstreamClient.cs (line 39, col 12)`
- `src\BaGet.Core\Storage\FileStorageService.cs (line 42, col 12)`
- `src\BaGet.Core\Extensions\PackageArchiveReaderExtensions.cs (line 133, col 12)`
- `src\BaGet.Core\Extensions\PackageArchiveReaderExtensions.cs (line 127, col 12)`
- `src\BaGet.Core\Extensions\PackageArchiveReaderExtensions.cs (line 102, col 8)`
- `src\BaGet.Core\Extensions\PackageArchiveReaderExtensions.cs (line 106, col 12)`
- `src\BaGet.Core\Extensions\PackageArchiveReaderExtensions.cs (line 49, col 12)`
- `src\BaGet.Core\Extensions\DependencyInjectionExtensions.cs (line 192, col 12)`
- `src\BaGet.Core\Entities\Package.cs (line 73, col 59)`
- `src\BaGet.Core\Entities\Package.cs (line 73, col 45)`
- `src\BaGet.Core\Entities\Package.cs (line 72, col 53)`
- `src\BaGet.Core\Entities\Package.cs (line 72, col 42)`
- `src\BaGet.Core\Entities\Package.cs (line 71, col 53)`
- `src\BaGet.Core\Entities\Package.cs (line 71, col 42)`
- `src\BaGet.Core\Entities\Package.cs (line 70, col 47)`
- `src\BaGet.Core\Entities\Package.cs (line 70, col 39)`
- `src\BaGet.Core\Entities\Package.cs (line 52, col 40)`
- `src\BaGet.Core\Entities\Package.cs (line 52, col 35)`
- `src\BaGet.Core\Entities\Package.cs (line 52, col 8)`
- `src\BaGet.Core\Entities\Package.cs (line 50, col 37)`
- `src\BaGet.Core\Entities\Package.cs (line 50, col 32)`
- `src\BaGet.Core\Entities\Package.cs (line 50, col 8)`
- `src\BaGet.Core\Entities\Package.cs (line 49, col 37)`
- `src\BaGet.Core\Entities\Package.cs (line 49, col 32)`
- `src\BaGet.Core\Entities\Package.cs (line 49, col 8)`
- `src\BaGet.Core\Entities\Package.cs (line 48, col 34)`
- `src\BaGet.Core\Entities\Package.cs (line 48, col 29)`
- `src\BaGet.Core\Entities\Package.cs (line 48, col 8)`
- `src\BaGet.Core\Entities\Converters\UriToStringConverter.cs (line 12, col 21)`
- `src\BaGet.Core\Entities\Converters\UriToStringConverter.cs (line 11, col 21)`
- `src\BaGet.Core\Entities\AbstractContext.cs (line 89, col 12)`
- `src\BaGet.Core\Entities\AbstractContext.cs (line 85, col 12)`
- `src\BaGet.Core\Entities\AbstractContext.cs (line 81, col 12)`
- `src\BaGet.Core\Entities\AbstractContext.cs (line 77, col 12)`
- `src\BaGet.Core\Configuration\MirrorOptions.cs (line 34, col 16)`
- `src\BaGet.Core\Configuration\MirrorOptions.cs (line 32, col 12)`
- `src\BaGet.Core\Configuration\MirrorOptions.cs (line 17, col 40)`
- `src\BaGet.Core\Configuration\MirrorOptions.cs (line 17, col 35)`
- `src\BaGet.Core\Configuration\MirrorOptions.cs (line 17, col 8)`
- `src\BaGet\Startup.cs (line 87, col 12)`
- `src\BaGet.Gcp\GoogleCloudStorageService.cs (line 40, col 12)`
- `src\BaGet.Protocol\Search\RawSearchClient.cs (line 82, col 16)`
- `src\BaGet.Protocol\Search\RawSearchClient.cs (line 80, col 16)`
- `src\BaGet.Protocol\PackageContent\RawPackageContentClient.cs (line 81, col 12)`
- `src\BaGet.Protocol\PackageContent\RawPackageContentClient.cs (line 60, col 12)`
- `src\BaGet.Protocol\Extensions\HttpClientExtensions.cs (line 65, col 16)`
- `src\BaGet.Protocol\Extensions\HttpClientExtensions.cs (line 32, col 16)`
- `tests\BaGet.Protocol.Tests\Support\TestDataHttpMessageHandler.cs (line 53, col 12)`
- `tests\BaGet.Protocol.Tests\Support\TestDataHttpMessageHandler.cs (line 45, col 16)`
- `tests\BaGet.Protocol.Tests\Support\TestDataHttpMessageHandler.cs (line 42, col 12)`
- `tests\BaGet.Tests\NuGetClientIntegrationTests.cs (line 37, col 12)`
- `tests\BaGet.Tests\NuGetClientIntegrationTests.cs (line 36, col 12)`
- `tests\BaGet.Tests\MirrorIntegrationTests.cs (line 150, col 12)`
- `tests\BaGet.Tests\MirrorIntegrationTests.cs (line 86, col 12)`
- `tests\BaGet.Tests\MirrorIntegrationTests.cs (line 53, col 12)`
- `tests\BaGet.Tests\MirrorIntegrationTests.cs (line 32, col 12)`
- `tests\BaGet.Tests\BaGetClientIntegrationTests.cs (line 31, col 12)`
- `tests\BaGet.Tests\BaGetClientIntegrationTests.cs (line 28, col 12)`
- `tests\BaGet.Tests\ApiIntegrationTests.cs (line 345, col 12)`
- `tests\BaGet.Tests\ApiIntegrationTests.cs (line 315, col 12)`
- `tests\BaGet.Tests\ApiIntegrationTests.cs (line 240, col 12)`
- `tests\BaGet.Tests\ApiIntegrationTests.cs (line 181, col 12)`
- `tests\BaGet.Tests\ApiIntegrationTests.cs (line 162, col 12)`
- `tests\BaGet.Tests\ApiIntegrationTests.cs (line 143, col 12)`
- `tests\BaGet.Tests\ApiIntegrationTests.cs (line 124, col 12)`
- `tests\BaGet.Tests\ApiIntegrationTests.cs (line 105, col 12)`
- `tests\BaGet.Tests\ApiIntegrationTests.cs (line 85, col 12)`
- `tests\BaGet.Tests\ApiIntegrationTests.cs (line 43, col 12)`
- `tests\BaGet.Tests\ApiIntegrationTests.cs (line 31, col 12)`

</details>

<details>
<summary><b>建议升级 NuGet 包</b> — affected files</summary>

- `src\BaGet.Aws\BaGet.Aws.csproj`
- `src\BaGet.Azure\BaGet.Azure.csproj`
- `src\BaGet.Core\BaGet.Core.csproj`
- `src\BaGet\BaGet.csproj`
- `src\BaGet.Database.Sqlite\BaGet.Database.Sqlite.csproj`
- `src\BaGet.Database.SqlServer\BaGet.Database.SqlServer.csproj`
- `src\BaGet.Protocol\BaGet.Protocol.csproj`
- `tests\BaGet.Tests\BaGet.Tests.csproj`

</details>

<details>
<summary><b>对所选 .NET 版本源代码不兼容</b> — affected files</summary>

- `src\BaGet.Azure\Storage\BlobStorageService.cs (line 31, col 12)`
- `src\BaGet.Core\Extensions\DependencyInjectionExtensions.cs (line 182, col 12)`
- `src\BaGet\ConfigureRazorRuntimeCompilation.cs (line 18, col 8)`
- `src\BaGet\ConfigureBaGetOptions.cs (line 74, col 12)`
- `src\BaGet.Web\Extensions\IServiceCollectionExtensions.cs (line 21, col 20)`
- `src\BaGet.Web\Extensions\IServiceCollectionExtensions.cs (line 14, col 12)`

</details>

<details>
<summary><b>NuGet 包已弃用</b> — affected files</summary>

- `src\BaGet.Azure\BaGet.Azure.csproj`
- `src\BaGet.Core\BaGet.Core.csproj`
- `tests\BaGet.Core.Tests\BaGet.Core.Tests.csproj`
- `src\BaGet.Database.MySql\BaGet.Database.MySql.csproj`
- `src\BaGet.Protocol\BaGet.Protocol.csproj`
- `samples\BaGet.Protocol.Samples.Tests\BaGet.Protocol.Samples.Tests.csproj`
- `tests\BaGet.Protocol.Tests\BaGet.Protocol.Tests.csproj`
- `tests\BaGet.Tests\BaGet.Tests.csproj`
- `tests\BaGet.Web.Tests\BaGet.Web.Tests.csproj`

</details>

<details>
<summary><b>NuGet 包有安全漏洞</b> — affected files</summary>

- `src\BaGet.Core\BaGet.Core.csproj`
- `tests\BaGet.Tests\BaGet.Tests.csproj`

</details>

---

#### Codebase Insights

> **Note:** These documents are generated by AI and may contain inaccuracies or incomplete information. Please review carefully.

> **Codebase Insights aren't available yet.**
>
> These documents are generated when assessment runs with **Full analysis** coverage. Re-run the assessment and set `analysisCoverage: full` to enable them.

[Share feedback](https://aka.ms/ghcp-appmod/feedback)


