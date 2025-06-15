---
title: Nav
aliases: [nav]
type: nav
url: /nav
layout: nav

# ====================================
# 左侧导航菜单配置（可沿用之前的数据文件或Front Matter配置）
# 如果你选择沿用数据文件 (data/nav_menu.yml)，则以下部分可删除
menu_title: "导航"
menu_items:
- name: "我的 MINE"
  icon: "🌞"
  url: "#mine"
- name: "工具 TOOL"
  icon: "🔨"
  url: "#tools"
- name: "AI LLM"
  icon: "🤖"
  url: "#ai"
- name: "文档 DOC"
  icon: "📑"
  url: "#docs"
- name: "博客 BLOG"
  icon: "🍺"
  url: "#blogs"
- name: "休闲 LEISURE"
  icon: "☕️"
  url: "#leisure"
- name: "友链 LINK"
  icon: "🧲"
  url: "#links"
- name: "标签 BOOKMARK"
  icon: "🔖"
  url: "#bookmarks"


# ====================================
# 右侧内容区配置
right_sections:
- id: "mine"
  title: "🌞 我的 MINE"
  groups: # 使用 groups 统一处理，即使没有子标题也用一个 group 包裹
    - links:
        - title: "笔记"
          url: "https://notes.einscat.com/"
          logo_letter: "夜"
        - title: "腾讯云"
          url: "https://console.cloud.tencent.com/"
          logo_letter: "腾"
        - title: "微信公众平台"
          url: "https://mp.weixin.qq.com/"
          logo_letter: "微"
        - title: "Github"
          url: "https://github.com/finnley"
          logo_letter: "G"
        - title: "Gitee"
          url: "https://gitee.com/finnley"
          logo_letter: "G"
        - title: "LeetCode"
          url: "https://leetcode-cn.com/"
          logo_letter: "L"

- id: "tools"
  title: "🔨 工具 TOOL"
  groups:
    - links:
        - title: "Sci-Hub中文社区"
          url: "https://discuss.sci-hub.org.cn/d/2579"
          logo_letter: "S"
        - title: "ZLibrary"
          url: "https://zh.z-lib.gs/"
          logo_letter: "Z"
        - title: "DrawIO"
          url: "https://app.diagrams.net/"
          logo_letter: "D"
        - title: "Google Fonts"
          url: "https://fonts.google.com/"
          logo_letter: "G"
        - title: "Cloudflare"
          url: "https://www.cloudflare.com/zh-cn/"
          logo_letter: "C"
        - title: "AnimateCSS"
          url: "https://animate.style/"
          logo_letter: "A"
        - title: "Mermaid Live Editor"
          url: "https://mermaid.live/"
          logo_letter: "M"
        - title: "Mermaid Live Editor"
          url: "https://sms-activate.org/cn"
          logo_letter: "S"

- id: "ai"
  title: "🤖 AI LLM"
  groups: # AI 模块包含多个子标题，每个 group 有一个 group_title
    - group_title: "AI 综合平台"
      links:
        - title: "Gemini"
          url: "https://gemini.google.com/"
          logo_letter: "G"
        - title: "智谱AI开放平台"
          url: "https://open.bigmodel.cn/"
          logo_letter: "智"
        - title: "ChatGPT"
          url: "https://chatgpt.com/"
          logo_letter: "C"
        - title: "豆包"
          url: "https://www.doubao.com/chat/"
          logo_letter: "豆"
    - group_title: "AI 写作与办公"
      links:
        - title: "Kimi"
          url: "https://kimi.moonshot.cn/"
          logo_letter: "K"
        - title: "Coze"
          url: "https://www.coze.cn/home"
          logo_letter: "C"
    - group_title: "AI 绘画与设计"
      links:
        - title: "MJ绘画中文站"
          url: "https://www.mxai.cn/home/#/mj"
          logo_letter: "M"
    - group_title: "AI 换脸"
      links:
        - title: "FaceHub"
          url: "https://www.facengine.ai/"
          logo_letter: "F"
        - title: "DeepFakes"
          url: "https://deepfakesweb.com/"
          logo_letter: "F"
    - group_title: "AI 变音"
      links:
        - title: "RASK"
          url: "https://zh.rask.ai/"
          logo_letter: "F"
        - title: "DeepFakes"
          url: "https://deepfakesweb.com/"
          logo_letter: "F"

- id: "docs"
  title: "📑 文档 DOCs"
  groups:
    - links:
        - title: "MySQL"
          url: "https://www.mysql.com/downloads/"
          logo_letter: "M"
        - title: "MongoDB"
          url: "https://www.mongodb.com/try/download/community-kubernetes-operator"
          logo_letter: "M"

- id: "blogs"
  title: "🍺 博客 BLOGs"
  groups:
    - links:
        - title: "Notes"
          url: "https://notes.einscat.com/"
          logo_letter: "N"
        - title: "Geekinney"
          url: "https://geekinney.com/"
          logo_letter: "G"
---