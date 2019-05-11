# Snapper V2
**Bringing Jest-esque Snapshot testing to C#**

Type   | Snapper | Snapper.Nunit
------ | ------- | -------------
NuGet  | [![Nuget (with prereleases)](https://img.shields.io/nuget/vpre/Snapper.svg?style=flat-square)](https://www.nuget.org/packages/Snapper) | [![Nuget (with prereleases)](https://img.shields.io/nuget/vpre/Snapper.svg?style=flat-square)](https://www.nuget.org/packages/Snapper.Nunit)
Build  | [![AppVeyor](https://img.shields.io/appveyor/ci/theramis/snapper.svg?style=flat-square)](https://ci.appveyor.com/project/theramis/snapper) | [![AppVeyor](https://img.shields.io/appveyor/ci/theramis/snapper.svg?style=flat-square)](https://ci.appveyor.com/project/theramis/snapper)
Github | [![GitHub release](https://img.shields.io/github/release/theramis/snapper.svg?style=flat-square)](https://github.com/theramis/Snapper) | [![GitHub release](https://img.shields.io/github/release/theramis/snapper.svg?style=flat-square)](https://github.com/theramis/Snapper)

Snapper is a [NuGet library](https://www.nuget.org/packages/Snapper) which captures snapshots of objects to simplify testing.
It is very heavily based on Jest Snapshot Testing.

See [https://theramis.github.io/Snapper/](https://theramis.github.io/Snapper/) for more documentation.


## Snapper V1 is deprecated
After a lot of thought I've decided to deprecate Snapper V1.
Snapper V1 was my first attempt at an OSS library and some of the decisions I made very early on made it very difficult to add new features.
Snapper V2 is my second attempt at making the library easier to use and update.

Snapper V1 consisted of the following NuGet packages all of which are deprecated:
- Snapper.Core
- Snapper.Json
- Snapper.Json.Xunit
- Snapper.Json.Nunit

There is a migration guide available [here](https://theramis.github.io/Snapper/migration.html)

The changes in V2 are documented in the [Changelog](https://theramis.github.io/Snapper/changelog.html)

## Todo
- Add logo to Nuget
- Write tests for testing json store.
- Update V1 package descriptions to mention deprecated
- Use appveyor logger on all test projects
- Add sourcelink to nuget packages once this issue is fixed https://github.com/appveyor/ci/issues/2753
