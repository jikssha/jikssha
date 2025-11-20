<p align="center">
  <img src="https://imphub.pepeth.qzz.io/file/pepe/1763451865718_GLsxwKuXsAAkunN.jpg" width="100%" alt="banner" />
</p>

<h1 align="center">Hi, I'm <strong>vaghr / jikssha</strong> 👋</h1>

<p align="center">
  <a href="https://github.com/jikssha"><img src="https://img.shields.io/badge/GitHub-Profile-black?logo=github" alt="GitHub" /></a>
  <img src="https://img.shields.io/github/stars/jikssha?style=social" alt="Stars" />
  <img src="https://img.shields.io/badge/Version-1.0.0-brightgreen" alt="Version" />
  <!-- Social badges (TG / X) as you requested -->
  [![Telegram](https://img.shields.io/badge/Telegram-Chat-blue)](https://t.me/johnjay78956)
  [![Twitter](https://img.shields.io/badge/Twitter-访问我的X-Black)](https://x.com/tong_hu59806)
</p>

---

## 🚀 About Me

* **加密货币交易员**
* 专注：**Web3 / Meme / 自动化脚本 / 黑天鹅监控**
* 风格：极简、模块化、可复用

---

## 🧰 技术栈（简要）

* **语言**：Python、JavaScript (Node.js)
* **工具**：Docker、GitHub Actions、Linux / Shell
* **领域**：EVM 交互、DEX 监控、链上/链下自动化

---

## 📌 代表性项目（Highlights）

* **价差 / 脱锚监控脚本**：多交易所实时价差检测 + 报警（TG / 邮件）
* **Telegram 双向防骚扰机器人**：过滤规则 + 群-私聊联动，支持 VPS 一键部署

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=jikssha&show_icons=true&hide_title=true&hide_border=true" height="160" alt="GitHub stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=jikssha&layout=compact&hide_border=true" height="160" alt="Top languages" />
</p>

---

## 🐍 Contribution Snake (自动生成)

* 我已为你准备好 **GitHub Actions workflow**，它会使用 `Platane/snk` 自动生成蛇形贡献图（SVG 或 GIF）并输出到 `output/` 目录。
* 将下面的 workflow 保存为：`.github/workflows/snake.yml`（需要在仓库 Actions 中启用，并在仓库设置里给 Actions **read & write** permissions）。

**.github/workflows/snake.yml**

```yaml
name: Generate contribution snake

on:
  schedule:
    # every 12 hours
    - cron: "0 */12 * * *"
  workflow_dispatch:

jobs:
  generate-snake:
    runs-on: ubuntu-latest
    permissions:
      # required to read contributions and create output files in the repo
      contents: write
    steps:
      - name: Checkout
        uses: actions/checkout@v4
        with:
          fetch-depth: 0

      - name: Generate snake (SVG)
        uses: Platane/snk@v3
        with:
          # default to the repository owner (you)
          github_user_name: ${{ github.repository_owner }}
          files: |
            output/github-contribution-grid-snake.svg?palette=github&color_snake=%23ffb86b&color_dots=eeeeee,85e089,4caf50
      - name: Commit and push generated image
        run: |
          git config user.name "github-actions[bot]"
          git config user.email "github-actions[bot]@users.noreply.github.com"
          git add output/github-contribution-grid-snake.svg || true
          git commit -m "chore: update contribution snake" || echo "no changes to commit"
          git push
```

* 在 README 中引用（已在本 README 中示例）：

  ```markdown
  ![Contribution snake](https://raw.githubusercontent.com/jikssha/jikssha/output/github-contribution-grid-snake.svg)
  ```
* 注意事项：

  * 在仓库 **Settings → Actions → General** 中把 **Workflow permissions** 设置为 **Read and write permissions**，并勾选 **Allow GitHub Actions to create and approve pull requests**（如果需要）。
  * 首次运行可手动在 Actions 页触发 `workflow_dispatch`。

---

<p align="center">
  <!-- 示例：直接显示生成后的 snake（当 workflow 已运行并生成 output 文件时会显示） -->
  ![Contribution snake](https://raw.githubusercontent.com/jikssha/jikssha/output/github-contribution-grid-snake.svg)
</p>

---

## 🔧 个性化小组件（一键整合示例）

* **访客计数（Visitor Badge）**

  ```markdown
  ![visitor badge](https://visitor-badge.laobi.icu/badge?page_id=jikssha.jikssha)
  ```
* **Spotify（当前播放 / 最近播放）**

  * 推荐使用 `anuraghazra/spotify-readme` 或第三方「now-playing」服务（需要你授权 Spotify）。示例（占位）：

  ```markdown
  ![Spotify - Now playing](https://spotify-now-playing-example-url/your-spotify-widget)
  ```

  * 若需要，我可以帮你生成具体的 Spotify 授权步骤和可直接使用的 widget。
* **动态名片（Profile card）**

  * 简单 Badge 风格：

  ```markdown
  [![Profile](https://img.shields.io/badge/Profile-jikssha-informational?logo=linkedin)](https://github.com/jikssha)
  ```

  * 更高级的动态名片可用 GitHub Actions 每日更新个人状态（需要你确认想展示的字段：当前项目 / 可合作 / 在看书籍 等等）。

---

## 📫 联系我

<p align="left">
  <a href="https://github.com/jikssha"><img src="https://img.shields.io/badge/GitHub-@jikssha-black?logo=github" alt="GitHub" /></a>
  <a href="mailto:your-email@example.com"><img src="https://img.shields.io/badge/Email-Contact-red?logo=gmail" alt="Email" /></a>
  [![Telegram](https://img.shields.io/badge/Telegram-Chat-blue)](https://t.me/johnjay78956)
  [![Twitter](https://img.shields.io/badge/Twitter-访问我的X-Black)](https://x.com/tong_hu59806)
</p>

---

<p align="center">✨ Minimal & Clean · Always Building ✨</p>
