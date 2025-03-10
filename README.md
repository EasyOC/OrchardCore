# Orchard Core 

Orchard Core consists of two distinct projects:

- __Orchard Core Framework__: An application framework for building modular, multi-tenant applications on ASP.NET Core.
- __Orchard Core CMS__: A Web Content Management System (CMS) built on top of the Orchard Core Framework.

[![Join the chat at https://gitter.im/OrchardCMS/OrchardCore](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/OrchardCMS/OrchardCore?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![BSD-3-Clause License](https://img.shields.io/badge/license-BSD--3--Clause-blue.svg)](LICENSE)
[![Documentation](https://readthedocs.org/projects/orchardcore/badge/)](https://docs.orchardcore.net/)
[![Crowdin](https://badges.crowdin.net/orchard-core/localized.svg)](https://crowdin.com/project/orchard-core)

## Build Status

Stable (release/1.8.2): 

[![Build status](https://github.com/OrchardCMS/OrchardCore/actions/workflows/release_ci.yml/badge.svg)](https://github.com/OrchardCMS/OrchardCore/actions?query=workflow%3A%22Release+-+CI%22)
[![NuGet](https://img.shields.io/nuget/v/OrchardCore.Application.Cms.Targets.svg)](https://www.nuget.org/packages/OrchardCore.Application.Cms.Targets)

Nightly (main): 

[![Build status](https://github.com/OrchardCMS/OrchardCore/actions/workflows/preview_ci.yml/badge.svg)](https://github.com/EasyOC/OrchardCore/actions?query=workflow%3A%22Preview+-+CI%22)
[![Cloudsmith](https://api-prd.cloudsmith.io/badges/version/easyoc/orchardcore/nuget/OrchardCore.Application.Cms.Targets/latest/x/?render=true&badge_token=gAAAAABey9hKFD_C-ZIpLvayS3HDsIjIorQluDs53KjIdlxoDz6Ntt1TzvMNJp7a_UWvQbsfN5nS7_0IbxCyqHZsjhmZP6cBkKforo-NqwrH5-E6QCrJ3D8%3D)](https://cloudsmith.io/~easyoc/repos/orchardcore/packages/detail/nuget/OrchardCore.Application.Cms.Targets/latest/)

## Status

### 1.8.2

The software is production-ready, and capable of serving large mission-critical applications as well, and we're not aware of any fundamental bugs or missing features we deem crucial. Orchard Core continues to evolve, with each version bringing new improvements, and keeping up with the cutting-edge of .NET.

Check out [the Reference of Built-in Modules](https://docs.orchardcore.net/en/latest/docs/reference/) to see what kind of features Orchard Core provides built-in.

See the [issue milestones](https://github.com/OrchardCMS/OrchardCore/milestones) for information on what we have planned for the next releases and what are the priorities.

## Getting Started and Documentation

The documentation can be accessed under <https://docs.orchardcore.net/>. See [the getting started docs](https://docs.orchardcore.net/en/latest/docs/getting-started/) on how to start using Orchard Core.

You can also run Orchard Core from Docker:

```
docker run --name orchardcms -p 8080:80 orchardproject/orchardcore-cms-linux:latest
```

Docker images and parameters can be found at <https://hub.docker.com/u/orchardproject/>. See [our Docker documentation](https://docs.orchardcore.net/en/latest/docs/topics/docker/) for more details, especially if you're new to Docker.

## Help and Support

Do you need some help with Orchard Core? Don't worry, there are ways to get help from the community:

- Did you find a bug or have a feature request? Open an issue [in the issue tracker](https://github.com/OrchardCMS/OrchardCore/issues).
- Do you have a question about how to do something with Orchard Core, or would like a second opinion on your code? Open [a discussion](https://github.com/OrchardCMS/OrchardCore/discussions).

## Get in Touch

- [X (Twitter)](https://twitter.com/orchardcms)
- [LinkedIn](https://www.linkedin.com/groups/13605669/)
- [Meta (Facebook)](https://www.facebook.com/groups/244928199422062/user/100063629920864)

## Local Communities

中文资源

[![Orchard Core CN 中文讨论组](https://docs.orchardcore.net/en/latest/docs/assets/images/orchard-core-cn-community-logo.png)](https://shang.qq.com/wpa/qunwpa?idkey=48721591a71ee7586316604a7a4ee99d26fd977c6120370a06585085a5936f62)

## Contributing

It's great that you're thinking about contributing to Orchard Core! You'd join [our wonderful community of contributors](https://docs.orchardcore.net/en/latest/docs/community/).

First, clone the repository using the command `git clone https://github.com/OrchardCMS/OrchardCore.git` and checkout the `main` branch. Then, you have multiple options, see below. And when you're ready, head over to [our contribution guide](CONTRIBUTING.md).

### Command Line

1. Install the latest version of the .NET SDK from this page: <https://dotnet.microsoft.com/download>.
2. Navigate to `./OrchardCore/src/OrchardCore.Cms.Web`.
3. Run `dotnet run`.
4. Open the `http://localhost:5000` URL in your browser.

### Visual Studio

1. Download Visual Studio 2022 (v17.8+) from <https://www.visualstudio.com/downloads>.
2. Launch the solution by clicking on `OrchardCore.sln`. Give Visual Studio time to restore all missing Nuget packages.
3. Ensure `OrchardCore.Cms.Web` is set as the startup project. Then run the app.

## Code of Conduct

See [our Code of Conduct](./CODE-OF-CONDUCT.md).

## .NET Foundation

This project is supported by the [.NET Foundation](http://www.dotnetfoundation.org).
