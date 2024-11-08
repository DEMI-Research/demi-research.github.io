---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        数据工程与多模态智能实验室
      image:
        filename: 人大照片.png
      text: |
        <br>
        <font size="4">
        中国人民大学数据工程与多模态智能实验室（简称DEMI Lab），实验室负责人为李直旭教授，现为中国人民大学信息学院、智慧治理学院双聘教授，博士生导师。实验室主要从事大语言模型、知识图谱、数据工程与知识工程、数据治理、自然语言处理、多模态智能等方面的研究工作。多年来，实验室在国家自然科学基金、省部委基金和各类校企联合项目的支持下，发表了大量高水平学术论文，其中包括中国计算机学会推荐的A/B类国际会议和期刊论文（TKDE、ICDE、ACL、AAAI、IJCAI等）200余篇，拥有专利60余项，与科大讯飞、华为、阿里等公司保持长期校企合作。已为国家与社会培养研究生30余人。</font>

  
        
  
  - block: markdown
    content:
      title: 研究方向
      subtitle: Research Directions
      text: 
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>研究方向</title>
    <style>
        /* 全局样式 */
        body {
            font-family: Arial, sans-serif;
            background-color: #f5f5f5;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            color: #333;
        }

        /* 容器样式 */
        .container {
            text-align: center;
            max-width: 1200px;
            padding: 20px;
        }

        /* 标题样式 */
        .title {
            font-size: 36px;
            font-weight: bold;
            margin-bottom: 10px;
        }

        .subtitle {
            font-size: 16px;
            color: #777;
            margin-bottom: 40px;
        }

        /* 研究方向布局 */
        .research-directions {
            display: flex;
            justify-content: space-around;
            text-align: center;
        }

        /* 每个方向的样式 */
        .direction {
            max-width: 300px;
        }

        /* 图标样式 */
        .icon {
            font-size: 50px;
            color: #4285f4; /* 图标蓝色 */
            margin-bottom: 20px;
        }

        /* 标题样式 */
        .direction-title {
            font-size: 20px;
            font-weight: bold;
            margin-bottom: 10px;
        }

        /* 描述文本样式 */
        .description {
            font-size: 14px;
            color: #666;
        }
    </style>
</head>
# <body>

#     <div class="container">
#         <div class="title">主研方向</div>
#         <div class="subtitle">我们做什么</div>
#         <div class="research-directions">
#             <!-- 多模态智能信息处理 -->
#             <div class="direction">
#                 <div class="icon">🔗</div> <!-- 使用 Emoji 图标表示 -->
#                 <div class="direction-title">多模态智能信息处理</div>
#                 <div class="description">
#                     基于文本、语音、视频（图片）等模态的信息情感分类、情绪分析和意图识别等模型。
#                 </div>
#             </div>
#             <!-- 智能移动机器人关键技术 -->
#             <div class="direction">
#                 <div class="icon">🤖</div> <!-- 使用 Emoji 图标表示 -->
#                 <div class="direction-title">智能移动机器人关键技术</div>
#                 <div class="description">
#                     人机对话技术，智能移动机器人的控制技术和场景应用（商业智能服务机器人、双模式智能消毒机器人）
#                 </div>
#             </div>
#             <!-- 智能优化方法研究 -->
#             <div class="direction">
#                 <div class="icon">💾</div> <!-- 使用 Emoji 图标表示 -->
#                 <div class="direction-title">智能优化方法研究</div>
#                 <div class="description">
#                     基于演化的优化理论，（高维、稀疏、昂贵）多目标优化问题
#                 </div>
#             </div>
#         </div>
#     </div>

# </body>
</html>
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: coders.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen

  # - block: collection
  #   content:
  #     title: Latest Preprints
  #     text: ""
  #     count: 5
  #     filters:
  #       folders:
  #         - publication
  #       publication_type: 'article'
  #   design:
  #     view: citation
  #     columns: '1'

  # - block: markdown
  #   content:
  #     title:
  #     subtitle:
  #     text: |
  #       {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
  #   design:
  #     columns: '1'
---
