---
# Leave the homepage title empty to use the site title
title:
date: 2024-11-7
type: landing

sections:
  - block: hero
    content:
      title: |
        数据工程与多模态智能实验室
      image:
        filename: welcome.png
      text: |
        <br>
        本实验室是**数据工程与多模态智能实验室（简称DEMI）**，隶属于中国人民大学。实验室负责人李直旭教授，现为中国人民大学信息学院、智慧治理学院双聘教授，博士生导师。研究组主要从事数据工程与知识工程、数据治理、自然语言处理、多模态数据处理与知识图谱构建、跨模态认知智能等方面的研究工作。多年来，研究组在国家自然科学基金、省部委基金和各类校企联合项目的支持下，发表了大量高水平学术论文，其中包括中国计算机学会推荐的A/B类国际会议和期刊论文（TKDE、ICDE、ACL、AAAI、IJCAI等）200余篇，拥有专利60余项，与科大讯飞、华为、阿里等公司保持长期校企合作。已为国家与社会培养研究生30余人。
        
  
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
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
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
