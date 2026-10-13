# CleanFlow Pro (净流) · 官方门户与下载中枢

<p align="center">
  <img src="assets/icon.svg" width="96" height="96" alt="CleanFlow Pro icon" />
</p>

<p align="center">
  <b>磁盘治理与全盘秒搜，本该如此从容。</b><br />
  <b>Storage governance & instant search, brilliantly native.</b><br />
  专为 Windows 10 与 11 打造的纯 Rust 原生工业级桌面资产治理中枢。<br />
  NTFS MFT 裸盘秒级直读、国民社办深度瘦身、跨卷目录透明软搬迁、系统原生 SQLite 挤水分与全天候智能自愈。<br />
  单一二进制绿色便携，零外部依赖，100% 本地离线毫秒运转。
</p>

<p align="center">
  <a href="https://manhua-man.github.io/cleanflow-pro-web/"><img alt="Official Website" src="https://img.shields.io/badge/website-live%20portal-8b5cf6?style=flat-square" /></a>
  <a href="https://github.com/manhua-man/cleanflow-pro-web/releases/latest"><img alt="Latest Release" src="https://img.shields.io/badge/release-v0.5.0-0ea5e9?style=flat-square" /></a>
  <a href="https://github.com/manhua-man/cleanflow-pro-web/releases"><img alt="Package" src="https://img.shields.io/badge/package-portable%20zip-10b981?style=flat-square" /></a>
  <a href="#"><img alt="Platform" src="https://img.shields.io/badge/platform-Windows%2010%20%7C%2011%20(x64)-0078d4?style=flat-square" /></a>
  <a href="#"><img alt="License" src="https://img.shields.io/badge/tier-Free%20%2B%20Pro-f59e0b?style=flat-square" /></a>
  <a href="#"><img alt="Privacy" src="https://img.shields.io/badge/privacy-100%25%20local%20only-6366f1?style=flat-square" /></a>
  <a href="#"><img alt="Style" src="https://img.shields.io/badge/style-zero%20emoji-ec4899?style=flat-square" /></a>
</p>

---

## 官方网站 (Official Website)

- **线上体验门户**: [https://manhua-man.github.io/cleanflow-pro-web/](https://manhua-man.github.io/cleanflow-pro-web/)

---

## 快速下载 (Download)

| 分发版本 | 适用系统 | 文件类型与大小 | 说明 |
| :--- | :--- | :--- | :--- |
| **绿色便携包 (推荐)** | Windows 10 / 11 (64位) | [CleanFlow-Pro-v0.5.0-win64.zip](https://github.com/manhua-man/cleanflow-pro-web/releases/latest) (~2.85 MB) | 解压即用，内含主程序、配置规则与体验者快速上手指南 |
| **独立便携可执行文件** | Windows 10 / 11 (64位) | [cleanflow.exe](https://github.com/manhua-man/cleanflow-pro-web/releases/latest) (~10.6 MB) | 单文件独立运行，内置全量 Fluent 2 UI 与嵌入式规则引擎 |

---

## 核心特性矩阵

1. **MFT 裸盘流式直读**: 纯 Rust 直读 NTFS 裸卷簇链，全盘数百万文件 1~3 秒建立拓扑，0.18ms 级实时模糊检索。
2. **国民社办深度瘦身**: 动态识别微信（3.x/4.0）、QQ、钉钉、飞书数据目录；按时间跨度清理视频与缩略图缓存，BLAKE3 副本识别去重，硬编码熔断保护聊天记录库。
3. **跨盘透明软搬迁 (Junction)**: C 盘大型应用资产（微信文件、Ollama 权重、Android SDK）一键热搬迁至 D 盘并在原位创建 NTFS Reparse Point，软件零感知平滑运行。
4. **原生 SQLite 挤水分**: 动态调用 Windows 内置 `winsqlite3.dll` 执行 WAL 截断与 VACUUM，无损物理压缩 99% 数据库碎片空洞。
5. **C 盘 10GB+ 级系统扩容向导**: 覆盖 `hiberfil.sys` 三档休眠瘦身、`SoftwareDistribution` 更新缓存清理、`DriverStore` 受保护驱动池治理与页面文件调优。
6. **QuickLook 秒级内联预览**: 按下空格键即可零解压透视 `.zip` / `.jar` 归档目录树或流式预览代码与文本。
7. **全天候智能自愈守护**: 感知全屏游戏与 PPT 独占避让，离席空闲触发低优先级维护，时序滑动窗口预测空间耗尽倒计时。

---

## 商业版本分级与授权 (Freemium Model)

- **免费社区版 (Community Edition)**: 永久免费、无广告、零弹窗、100% 离线。包含全盘 MFT 秒搜、拼音检索、1-Edit 容错纠错、国民社交与办公深度瘦身以及基础系统治理。
- **专业商业版 (CleanFlow Pro Edition)**: 针对极客、开发者与重度用户，提供底层系统黑科技与高阶效率特权。包括跨卷 Junction 软搬迁、ReFS 零拷贝块克隆、Restart Manager 进程死锁穿透、Quick Switch 对话框无限制穿透、3-Gram 源码千万行 Grep、C 盘隐藏巨无霸 4 维调优以及全天候静默自动化守护。支持离线硬件指纹一次性买断激活码。

---

## 反馈与支持 (Support & Issues)

欢迎在 [Issues 讨论区](https://github.com/manhua-man/cleanflow-pro-web/issues) 提交使用体验反馈、功能建议与缺陷汇报。
