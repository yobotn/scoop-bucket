# yobotn Scoop bucket

[![Tests](https://github.com/yobotn/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/yobotn/scoop-bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/yobotn/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/yobotn/scoop-bucket/actions/workflows/excavator.yml)

[Scoop](https://scoop.sh) manifests for apps by [yobotn](https://github.com/yobotn).

| App | What it does |
|---|---|
| [RigSweep](https://rigsweep.com/) | Frees RAM, CPU and disk on Windows dev machines: leftover dev servers and agent CLIs, `node_modules`, Rust `target` folders, package caches. Every change is reversible. |

## Install

```powershell
scoop bucket add yobotn https://github.com/yobotn/scoop-bucket
scoop install yobotn/rigsweep
```

RigSweep installs for all users with its own installer, which asks for admin rights.

Manifests are updated automatically when a new release is published.
