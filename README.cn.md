# kind

[English version](./README.md)

Kubernetes IN Docker - local clusters for testing Kubernetes

[![x-cmd/install — kind Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/kind.svg?lang=zh)](https://x-cmd.com/install/kind)

## 安装

```sh
x install kind
```

## 代码洞察

合计: **24,169** 行代码（覆盖前 5 种语言、共 **281** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Go | 17,855 | 6,171 | 2,318 | 216 |
| Bash | 3,036 | 879 | 475 | 6 |
| Yaml | 1,013 | 61 | 1 | 25 |
| Sh | 913 | 864 | 237 | 33 |
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
- **最近提交**: 2026-10-22
- **Release 含资产**: 10 个

## 流行度

- **Star**: 15,578 · **Fork**: 1,824 · **开放 issue**: 2,064 · **贡献者**: 745

## 累计统计

- **发布数**: 39 · **已合并 PR**: 1654 · **开放 PR**: 48 · **已关闭 issue**: 1864 · **开放 issue**: 200 · **提交数**: 4877

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-09-27 | 0 | 4 | 9 | 0 | 1 | 3 |
| last60d | 2026-08-28 | 0 | 7 | 14 | 5 | 3 | 7 |
| 90d | 2026-07-29 | 1 | 16 | 18 | 8 | 7 | 20 |
| last180d | 2026-04-30 | 2 | 59 | 28 | 22 | 12 | 78 |
| 360d | 2025-11-01 | 3 | 93 | 42 | 36 | 23 | 171 |
| last720d | 2024-11-06 | 9 | 194 | 45 | 138 | 54 | 537 |

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

在 [repology.org](https://repology.org/project/kind) 上共有 **97** 个发行版报告此项目。**18** 个 ✅ 已是最新上游版本，**54** 个 ⚠️ 使用旧版本。

| 发行版 | 版本 | 状态 |
|--------|------|------|
| Debian unstable | `0.33.0` | ✅ latest |
| Debian 14 | `0.33.0` | ✅ latest |
| Debian 13 | `0.27.0` | ⚠️ outdated |
| Ubuntu 26.04 LTS | `0.30.0` | ⚠️ outdated |
| Arch | `0.33.0` | ✅ latest |
| Homebrew | `HEAD` | 🔄 rolling |
| Fedora rawhide | `0.33.0` | ✅ latest |
| Nix unstable | `0.33.0` | ✅ latest |
| Alpine edge | `0.31.0` | ⚠️ outdated |
| openSUSE Tumbleweed | `0.33.0` | ✅ latest |

## 改进这些数据

kind 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `kind` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/kind.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/261027.yml` · 2026-10-27T05:17:31Z._
