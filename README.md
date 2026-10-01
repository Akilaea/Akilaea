<div align="center">

# Akilaea

桌面端应用 · 自动化工具链 · 协议分析

把重复劳动自动化掉，也做一些注重细节的桌面端软件。

</div>

---

## 方向

### 🎧 桌面端应用

基于 Electron 的 Windows 应用开发。做过一个沉浸式音乐播放器：接入多家音源并实现**跨源自动 fallback**，
本地缓存统一收进安装目录不再污染 C 盘，关闭窗口后**常驻系统托盘后台播放**。

在意的是进程生命周期、离线可用性，以及安装包本身够不够干净。

### 🤖 Python 自动化工具链

把批量重复流程做成可编排的工具：并发调度、失败重试、出口管理、结果落库。

配套用 PyInstaller 打成**免安装包**，能直接丢到没有 Python 环境的 Windows Server 上双击运行。

### 🔬 协议与接口分析

抓包、重放、字段级 diff，搞清客户端与服务端究竟在交换什么。

习惯写探针脚本还原状态机，把"偶尔才复现"的问题变成可稳定复现的用例。

### ☁️ 云端小工具

Vercel / Cloudflare Workers 上的一次性服务：Webhook 中转、临时域名邮箱、定时任务。

能塞进 GitHub Actions 在云端跑完的流程，就不放在本地跑。

---

## 技术栈

**语言**　`Python` · `JavaScript / TypeScript` · `PowerShell` · `Bash`

**界面**　`Electron` · `HTML / CSS` · `Canvas`

**交付**　`Docker` · `GitHub Actions` · `PyInstaller`

**云**　`Vercel` · `Cloudflare Workers` · `Linux`

---

<div align="center">
<sub>持续构建中。</sub>
</div>
