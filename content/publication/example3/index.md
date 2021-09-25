---
title: "Clustering Enabled Few-Shot Load Forecasting"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Qiyuan Wang
- Chenye Wu

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"
- "Correspondence Author"

date: ""
doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Southern Power Electronics Conference*
publication_short: In *IEEE SPEC*

abstract: 申请公开了基于聚类的小样本负荷预测方法和预测装置，其中预测方法包括：对历史电力负荷和待预测电力负荷进行特征提取，获得特征向量；根据得到特征向量将历史电力负荷和待预测电力负荷集成聚类，得到聚类结果；采用小波降噪算法对聚类结果进行降噪，并将降噪后的数据进行均值化处理，得到预设长度的时序数据；其中预设长度的时序数据包括历史时序数据和待预测时序数据；将预设长度的时序数据输入二阶长短期记忆神经网络，得到电力负荷的预测结果；其中历史时序数据用于训练二阶长短期记忆神经网络，待预测时序数据用于调整训练完成后的二阶长短期记忆神经网络。本申请在待预测电力负荷稀缺情况下仍然有优秀预测表现。
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
