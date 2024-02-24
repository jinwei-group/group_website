---
# Leave the homepage title empty to use the site title
title:
date: 2024-2-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Jin Wei
        Research Group
      image:
        filename: welcome.jpg
      text: |
        <br>
        香港理工大学（理大）靳伟教授研究团队聚焦微纳结构光纤光子学的研究前沿，积极探索其在精密测量仪器、光子传感等领域的应用，并已在上述领域取得了突出的研究成果，近期在Nature Communications、Optica 等顶级专业期刊发表论文多篇，博士研究生多次在International Conference on Optical Fiber Sensors (OFS)等高层次国际会议上斩获优秀论文奖。
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---