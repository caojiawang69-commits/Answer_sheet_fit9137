# FIT9137 Wireshark 练习

打开 `index.html`（或 GitHub Pages 地址）即可开始。

| 文件 | 内容 |
|---|---|
| `index.html` | 目录页，含抓包下载 |
| `coach-v1.html` | 第 1 套逐题带练 |
| `sheet-v2.html` / `sheet-v3.html` | 第 2、3 套答题卡 |
| `mock-v1.html` – `mock-v3.html` | 模拟卷（2024 S1 真题格式） |
| `real-2024s1.html` | 2024 S1 真题答题卡（能检查对错，答案默认隐藏；抓包需从 Moodle 下载） |
| `FIT9137_Wireshark_cheatsheet.pdf` | 可打印速查表（2 页 A4） |
| `selfcheck.html` | 看题定协议（自查表） |
| `tcp-faq.html` | TCP 题答疑 |
| `pcap/` | 练习抓包文件 |

## 发布成网页（GitHub Pages）

1. GitHub 新建仓库，比如 `fit9137-practice`。
2. Add file → Upload files，把本文件夹里的全部内容（包括 `pcap` 文件夹）拖进去，Commit。
3. Settings → Pages → Build and deployment → Source 选 **Deploy from a branch**，Branch 选 **main** 和 **/ (root)**，Save。
4. 等一两分钟，网址是 `https://<你的用户名>.github.io/fit9137-practice/`。

练习抓包是根据课程样例改写的模拟数据。真题抓包 `apollo_eth0_sample_10.pcap` 没有放进来，也不要上传到公开仓库。

真题答题卡里的答案只是编码隐藏，懂网页代码的人仍能解出来。公开仓库任何人都能看到，发布前请确认符合课程对分享真题和学习材料的规定；拿不准就把仓库设成 Private（Private 仓库的 GitHub Pages 需要付费账户），或者只在本机双击 `index.html` 打开。
