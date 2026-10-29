# 天天影视 · 发布仓库

本仓库只存放「应用内升级」与「源订阅」所需的配置文件和安装包，由 scripts\publish_release.ps1 自动发布。
三面共用一仓：tiantian（全量）/ youyou（纯菲）/ lele（纯壁）。

## 应用端地址（固定不变，应用内自动逐个尝试镜像/直连/CDN）

| 用途 | 地址 |
| --- | --- |
| 版本清单 | https://raw.githubusercontent.com/sushiguo/tiantian/main/{face}/update.json |
| 源订阅 | https://raw.githubusercontent.com/sushiguo/tiantian/main/sources/{face}.json |
| APK 直链 | https://github.com/sushiguo/tiantian/releases/latest/download/{face}.apk |

> 国内直连 raw.githubusercontent.com / github.com 会超时；镜像 ghfast.top 首选、gh-proxy.com 垫底、jsDelivr 缓存兜底。

## 应用内升级

设置 → 关于 → 打开自动检查 update.json → 有新版本点「升级」→ 前台服务下载（通知栏进度、断点续传）→ 四重校验 → 系统安装器。
首次安装需在系统设置里允许本应用「安装未知应用」。

## 当前版本

- versionName: 610290858
- versionCode: 610290858
- 更新时间: 2026-10-29 09:18:23