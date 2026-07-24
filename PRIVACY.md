# Odin Fun Plugin 隐私权政策 / Privacy Policy

最后更新 / Last updated: 2026-07-24

---

## 中文

Odin Fun Plugin(以下简称“本扩展”)尊重并保护您的隐私。本政策说明本扩展如何处理数据。

**我们收集的数据**
本扩展默认不会收集、存储或向开发者或任何第三方服务器上传您的任何个人数据。仅当您主动注册并登录可选的云同步功能时,您的备注数据才会上传至云端(详见下文“云同步(可选)”)。

**本地存储**
您在本扩展中创建的备注、界面语言偏好和显示设置,默认仅保存在您本地浏览器的存储空间(chrome.storage.local)中。未启用云同步时,这些数据不会离开您的设备。您可随时在扩展的备注管理页面查看、编辑、删除或导出这些数据。

**云同步(可选)**
若您主动注册并登录云同步账号,您的备注数据(用户 ID、用户名、备注文本)将通过加密连接(HTTPS/WSS)传输并存储于云端数据库(Supabase),仅用于您本人的跨设备同步;服务端通过行级安全策略保证每个账号只能访问自己的数据。退出登录即停止同步;本地数据始终保留。交易缓存等派生数据始终仅存本地,不上云。

**网络请求**
为实现功能,本扩展会向以下接口发起请求:
- api.odin.fun:读取 odin.fun 上公开的持有人交易活动,用于计算并展示交易统计。
- api.coingecko.com:读取比特币价格,用于将数值换算为美元显示。
- *.supabase.co:仅在您登录云同步后,用于同步您的备注数据。

**数据共享**
本扩展不会出售、转移或与任何第三方共享您的数据。

**权限**
本扩展申请 storage 权限(在本地保存备注与设置)、alarms 权限(云同步的定时兜底拉取),以及在 odin.fun 上运行内容脚本所需的主机权限(https://odin.fun/*)和云同步所需的主机权限(https://*.supabase.co/*)。

**联系方式**
如有疑问,请通过 https://x.com/rex00618 联系。

---

## English

Odin Fun Plugin ("the extension") respects and protects your privacy. This policy explains how the extension handles data.

**Data we collect**
By default, the extension does not collect, store, or transmit any of your personal data to the developer or any third-party server. Only if you voluntarily sign up and log in to the optional cloud sync feature will your remarks data be uploaded to the cloud (see "Cloud Sync (optional)" below).

**Local storage**
Remarks, language preference, and display settings you create are stored by default only in your browser's local storage (chrome.storage.local). Without cloud sync enabled, this data never leaves your device. You can view, edit, delete, or export it at any time from the extension's remarks management page.

**Cloud Sync (optional)**
If you voluntarily sign up and log in to a cloud sync account, your remarks data (user ID, username, remark text) is transmitted over encrypted connections (HTTPS/WSS) and stored in a cloud database (Supabase), solely for syncing across your own devices; row-level security ensures each account can only access its own data. Signing out stops syncing; your local data is always retained. Derived data such as trading caches always stays local and is never uploaded.

**Network requests**
To provide its features, the extension makes requests to the following endpoints:
- api.odin.fun: to read public holder trading activity on odin.fun and compute/display trading statistics.
- api.coingecko.com: to read the Bitcoin price for USD-conversion display.
- *.supabase.co: only after you log in to cloud sync, to sync your remarks data.

**Data sharing**
The extension does not sell, transfer, or share your data with any third party.

**Permissions**
The extension requests the "storage" permission (to save remarks and settings locally), the "alarms" permission (periodic fallback pull for cloud sync), the host access needed to run its content script on odin.fun (https://odin.fun/*), and the host access needed for cloud sync (https://*.supabase.co/*).

**Contact**
For questions, contact https://x.com/rex00618.
