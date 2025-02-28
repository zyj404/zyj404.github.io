---
layout: archive
title: "Notes"
permalink: /Notes/
author_profile: true
---

{% include base_path %}

- 我的笔记不止包含书面整理, 部分还会有**辅助完成作业/整理复习资料**等能够提高效率, 节省重复性工作时间的**Python程序**
- 这些资料不会包含任何 **不被允许公开** 的 **课件, 往年题** 等, 仅供学习交流使用, 请勿用于商业用途. 如有侵权, 请联系我删除.



## 观点与本站发展
**2022 秋** : 入燕园, 初窥计算机语言与 Github, 度过了浑浑噩噩的第一个学期.

**2023 春** : 开始接触 **markdown, LaTeX** 等书面语言, 用了一个学期熟练掌握了数学公式的书写, 即背诵了绝大多数符号的代码, 初学者可以善用 [Detexify](http://detexify.kirelabs.org/classify.html) . 此前我连 word + 公式编辑器的配置都做不到随堂记录.

**2024 春** : 疲于应付图班硬课和双学位的我意识到 : 学长们祖传资料有**补天之能**, 迥异于信科陈腐教学体系. 我开始大规模记, 主要是用 markdown. 同时小范围传播, 无形中作为筹码换取信息. 以下观点:
  - 在高等教育领域，信息获取能力是继智力因素后的第二竞争力.
  - 技术文档能力已成为学术共同体的新型准入壁垒.
  - 知识共享可重构传统师生关系，推动新的教育公平进程.
  - 大概陈腐的不是信科, 而是授课-学习-考试的模式, 常为新的北大可以有更先进更高效的方法.

**2024 暑假** : 我的项目 [PKU-2024-IBAL-cracked-version](https://github.com/ICUlizhi/PKU-2024-IBAL-cracked-version) 大幅提升了身边同学的分数并将课外学习时长缩短整整 5 倍, 而此项目不过是调调 API, 根本没有用上多少我的技术能力. 我萌生了将这种模式**推广**的想法. 

**2024 秋** : 本站建成, 初志鬻文籍, 半藏半公, 兼营个人主页. 然初志浅狭, **今尽开我藏. 岂在锱铢之利?**
  - 我的课程大多理科, 自然语言处理又不可带入考场, 写有固定答案的作业上大模型则是杀鸡用牛刀. 因此 python 脚本少了, latex整理多了. 但这不代表前者不够先进, 如果有文科的同学掌握了简单的 API 调用和 finetune, 我想会大放异彩. 

**2025 春** : 经娄学长指点, 我决定全面采用基于 LaTeX 的 [ElegantBook](https://github.com/ElegantLaTeX/ElegantBook) 模版, 这意味着教材/专著级的笔记质量, 可刻印成书.


## News

- 本学期新开坑: ych中宏, 数理经济学, cv导论 (继承自 [lyt学长](https://www.lyt0112.com/) )
  - 本学期较忙, 操统与计组力有不逮
- 加入相应[学习小组](https://iculizhi.github.io/Blogs/%E5%8E%BB%E4%B8%AD%E5%BF%83%E5%8C%96%E5%AD%A6%E4%B9%A0%E5%B0%8F%E7%BB%84)请戳我

## 专业课

{% assign paths = "cvdl.md,概论统计A(现为信概统).md,hjfpython.md,Data-Structure-and-Algorithm-A-of-pku.md,数学分析3.md,信数.md" | split: "," %}

{% for post in site.Notes reversed %}
  {% for path in paths %}
    {% if post.path contains path %}
      {% include archive-single.html %}
      {% break %}
    {% endif %}
  {% endfor %}
{% endfor %}


## 公共课
{% assign paths = "PKU-2024-IBAL-cracked-version.md,金融学概论.md,地震概论.md" | split: "," %}

{% for post in site.Notes reversed %}
  {% for path in paths %}
    {% if post.path contains path %}
      {% include archive-single.html %}
      {% break %}
    {% endif %}
  {% endfor %}
{% endfor %}

## 经双
{% assign paths = "ych中宏.md,数理经济学.md,博弈论.md,宏观经济与健康.md" | split: "," %}

{% for post in site.Notes reversed %}
  {% for path in paths %}
    {% if post.path contains path %}
      {% include archive-single.html %}
      {% break %}
    {% endif %}
  {% endfor %}
{% endfor %}

## 其他
{% assign paths = "社会主义学习.md" | split: "," %}

{% for post in site.Notes reversed %}
  {% for path in paths %}
    {% if post.path contains path %}
      {% include archive-single.html %}
      {% break %}
    {% endif %}
  {% endfor %}
{% endfor %}


## 说明

- 部分资料是**收费**的. 如果您需要获取这部分资料, 请浏览[此页](https://iculizhi.github.io/Notes/notes).
- 也欢迎同学们来我的网站[卖笔记](https://iculizhi.github.io/Notes/notes),已有合作者: [qlc](https://github.com/Achyutace)

<script src="https://giscus.app/client.js"
        data-repo="ICUlizhi/ICUlizhi.github.io"
        data-repo-id="R_kgDOKfCXRQ"
        data-category="Announcements"
        data-category-id="DIC_kwDOKfCXRc4CknGa"
        data-mapping="url"
        data-strict="0"
        data-reactions-enabled="1"
        data-emit-metadata="1"
        data-input-position="top"
        data-theme="light"
        data-lang="zh-CN"
        data-loading="lazy"
        crossorigin="anonymous"
        async>
</script>