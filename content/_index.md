---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        <div style="font-size: 32px; font-weight: bold;">数据工程与多模态智能实验室   </div><div style="font-size: 18px; font-weight: bold; line-height: 2.5;">Data Engineering & Multimodal Intelligence Laboratory (DEMI)</div>
      image:
        filename: 人大照片.png
      text: |
        <font size="4">
        中国人民大学数据工程与多模态智能实验室（简称DEMI Lab），实验室主任为李直旭教授，现为中国人民大学信息学院、智慧治理学院双聘教授，博士生导师。实验室主要从事大语言模型、知识图谱、数据工程与知识工程、数据治理、自然语言处理、多模态智能等方面的研究工作。多年来，实验室在国家自然科学基金、省部委基金和各类校企联合项目的支持下，发表了大量高水平学术论文，其中包括中国计算机学会推荐的A/B类国际会议和期刊论文(TKDE、ICDE、ACL、AAAI、IJCAI等)200余篇，拥有专利60余项，与科大讯飞、华为、阿里等公司保持长期校企合作。已为国家与社会培养研究生30余人。</font>
  
  - block: collection
    id: section-1
    content:
      title: 研究方向
      subtitle: Research Directions
      # text: 
      # Display content from the `content/post/` folder
      filters:
        folders:
          - post
      sort_by: Params.priority
      sort_ascending: true
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      # Choose your content listing view - here we use the `showcase` view
      view: showcase
      # For the Showcase view, do you want to flip alternate rows?
      flip_alt_rows: true

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="团队成员 →" %}}
    design:
      columns: '1'
    
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        <script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=EQlzbYG8AHpo0ulfHm23padGhx0xu5Ffpj981o6hJSo&cl=ffffff&w=a"></script>

---
