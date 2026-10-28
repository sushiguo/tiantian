# 天天影视 / 优优影视 / 乐乐影视 · 发布仓库

本仓库只存放「应用内升级」与「源订阅」所需的配置文件和安装包。
一体三面：**天天**（全量 353 源）、**优优**（纯菲 207 源）、**乐乐**（纯壁 146 源），三面 versionCode 同步。

## 应用端地址（固定不变）

| 用途 | 天天 | 优优 | 乐乐 |
| --- | --- | --- | --- |
| 版本清单 | https://raw.githubusercontent.com/sushiguo/tiantian/main/tiantian/update.json | .../youyou/update.json | .../lele/update.json |
| 源订阅 | https://raw.githubusercontent.com/sushiguo/tiantian/main/sources/tiantian.json | .../sources/youyou.json | .../sources/lele.json |
| APK 直链 | https://github.com/sushiguo/tiantian/releases/latest/download/tiantian.apk | .../youyou.apk | .../lele.apk |

> 中国大陆直连 `raw.githubusercontent.com` / `github.com` 会超时。应用端已内置镜像候选
> （`ghfast.top`、`gh-proxy.com` 优先，直连与 jsDelivr 兜底），逐个尝试。

## 应用内升级

设置 → 检查更新 → 拉取 `{面}/update.json` → 与本地 versionCode 比较 → 下载 APK → 系统安装器。
首次安装需在系统设置里允许本应用「安装未知应用」。

## 源订阅

应用内订阅管理 → 填入对应面的 `sources/*.json` 地址 → 导入。
三份源文件即各面 `assets/config.json` 原文件（单 json 含 `sites` + `lives`），与安装包内置内容一致。

| 文件 | 大小 | 源数 | 说明 |
| --- | --- | --- | --- |
| `sources/tiantian.json` | 12.6 MB | 353 | 天天全量（菲精选/菲普通/壁精选/壁普通 + lives） |
| `sources/youyou.json` | 2.2 MB | 207 | 优优纯菲（菲精选/菲普通） |
| `sources/lele.json` | 10.4 MB | 146 | 乐乐纯壁（壁精选/壁普通） |

## 当前版本

- versionCode: 610282031
- 三面 versionName 同步 610282031
- 更新时间: 2026-10-28 21:03:46
