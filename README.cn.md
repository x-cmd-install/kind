# kind

[English version](./README.md)

Kubernetes IN Docker - local clusters for testing Kubernetes

![kind](https://repo.x-cmd.io/kind.svg?lang=zh)

## 安装

```sh
x install kind
```

## 代码洞察

合计: **24,114** 行代码（覆盖前 5 种语言、共 **281** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Go | 17,840 | 6,171 | 2,317 | 216 |
| Bash | 3,036 | 879 | 475 | 6 |
| Yaml | 1,013 | 61 | 1 | 25 |
| Sh | 873 | 866 | 234 | 33 |
| Css | 357 | 18 | 64 | 1 |

## OpenSSF Scorecard 评分

总评分: **6.6 / 10**

评分最低的几项:

- **Packaging** (-1/10) — packaging workflow not detected
- **CII-Best-Practices** (0/10) — no effort to earn an OpenSSF best practices badge detected
- **Fuzzing** (0/10) — project is not fuzzed

## 源代码

- **上游仓库**: <https://github.com/kubernetes-sigs/kind>
- **官网**: <https://kind.sigs.k8s.io/>
- **许可证**: Apache-2.0

## 发布

- **最新版本**: `v0.33.0` (2026-08-26)
- **最近提交**: 2026-09-04
- **Release 含资产**: 10 个

## 流行度

- **Star**: 15,484 · **Fork**: 1,793 · **开放 issue**: 2,061 · **贡献者**: 723

## 累计统计

- **发布数**: 39 · **已合并 PR**: 1648 · **开放 PR**: 41 · **已关闭 issue**: 1857 · **开放 issue**: 204 · **提交数**: 4865

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-12 | 1 | 9 | 7 | 4 | 5 | 13 |
| last60d | 2026-07-13 | 1 | 14 | 13 | 6 | 8 | 18 |
| 90d | 2026-06-13 | 1 | 22 | 20 | 9 | 10 | 28 |
| last180d | 2026-03-15 | 2 | 59 | 27 | 19 | 17 | 91 |
| 360d | 2025-09-16 | 3 | 100 | 37 | 44 | 29 | 179 |
| last720d | 2024-09-21 | 9 | 203 | 38 | 147 | 57 | 555 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
| [kind-darwin-amd64](https://github.com/kubernetes-sigs/kind/releases/download/v0.33.0/kind-darwin-amd64) | 10.2 MiB | `native/darwin/x64` |
| [kind-darwin-amd64.sha256sum](https://github.com/kubernetes-sigs/kind/releases/download/v0.33.0/kind-darwin-amd64.sha256sum) | 84 B | `native/darwin/x64` |
| [kind-darwin-arm64](https://github.com/kubernetes-sigs/kind/releases/download/v0.33.0/kind-darwin-arm64) | 9.5 MiB | `native/darwin/arm64` |
| [kind-darwin-arm64.sha256sum](https://github.com/kubernetes-sigs/kind/releases/download/v0.33.0/kind-darwin-arm64.sha256sum) | 84 B | `native/darwin/arm64` |
| [kind-linux-amd64](https://github.com/kubernetes-sigs/kind/releases/download/v0.33.0/kind-linux-amd64) | 10.0 MiB | `native/linux/x64` |
| [kind-linux-amd64.sha256sum](https://github.com/kubernetes-sigs/kind/releases/download/v0.33.0/kind-linux-amd64.sha256sum) | 83 B | `native/linux/x64` |
| [kind-linux-arm64](https://github.com/kubernetes-sigs/kind/releases/download/v0.33.0/kind-linux-arm64) | 9.3 MiB | `native/linux/arm64` |
| [kind-linux-arm64.sha256sum](https://github.com/kubernetes-sigs/kind/releases/download/v0.33.0/kind-linux-arm64.sha256sum) | 83 B | `native/linux/arm64` |
| [kind-windows-amd64](https://github.com/kubernetes-sigs/kind/releases/download/v0.33.0/kind-windows-amd64) | 10.3 MiB | `native/win/x64` |
| [kind-windows-amd64.sha256sum](https://github.com/kubernetes-sigs/kind/releases/download/v0.33.0/kind-windows-amd64.sha256sum) | 85 B | `native/win/x64` |

## 发行版状态

在 [repology.org](https://repology.org/project/kind) 上共有 **97** 个发行版报告此项目。**13** 个 ✅ 已是最新上游版本，**59** 个 ⚠️ 使用旧版本。

| 发行版 | 版本 | 状态 |
|--------|------|------|
| Debian unstable | `0.31.0` | ⚠️ outdated |
| Debian 14 | `0.31.0` | ⚠️ outdated |
| Debian 13 | `0.27.0` | ⚠️ outdated |
| Ubuntu 26.04 LTS | `0.30.0` | ⚠️ outdated |
| Arch | `0.33.0` | ✅ latest |
| Homebrew | `0.33.0` | ✅ latest |
| Fedora rawhide | `0.33.0` | ✅ latest |
| Nix unstable | `0.32.0` | ⚠️ outdated |
| Alpine edge | `0.31.0` | ⚠️ outdated |
| openSUSE Tumbleweed | `0.33.0` | ✅ latest |

## 改进这些数据

kind 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `kind` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/kind.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/260911.yml` · 2026-09-11T20:15:53Z._
