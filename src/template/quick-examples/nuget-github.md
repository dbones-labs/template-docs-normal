---
title: Installing Nuget packages
parent: Quick Examples
has_children: false
nav_order: 2
---

# Installing Nuget packages

`project-name` is available via Nuget packages in order to use


## From Github

Setup the github source

```sh
dotnet nuget add source https://nuget.pkg.github.com/organisation-name/index.json -n gh-dbones-labs -u YOUR_USER_NAME -p GH_TOKEN [--store-password-in-clear-text]
```

Install the required packages

```sh
dotnet add ProjectName package project-name
```

All the `auditable` are listed here: [![Nuget](https://img.shields.io/badge/nuget-project-name-blue)](https://github.com/orgs/organisation-name/packages?repo_name=project-name)