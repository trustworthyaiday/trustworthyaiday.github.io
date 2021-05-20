---
title: Deep Learning Day
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: single
classes: wide
author_profile: false
organizers_row:
  - image_path: assets/images/hima.png
    alt: "Himabindu Lakkaraju"
    title: "Hima Lakkaraju"
    excerpt: "Harvard University"
    url: "https://himalakkaraju.github.io/"
    btn_label: "Homepage"
    btn_class: "btn--primary"
  - image_path: assets/images/sameer.png
    alt: "Sameer Singh"
    title: "Sameer Singh"
    excerpt: "UC Irvine"
    url: "http://sameersingh.org"
    btn_label: "Homepage"
    btn_class: "btn--primary"
  - image_path: assets/images/baharan.jpg
    alt: "Baharan Mirzasoleiman"
    title: "Baharan Mirzasoleiman"
    excerpt: "UCLA"
    url: "http://web.cs.ucla.edu/~baharan/"
    btn_label: "Homepage"
    btn_class: "btn--primary"
  - image_path: assets/images/xiang.jpg
    alt: "Xiang Ren"
    title: "Xiang Ren"
    excerpt: "USC"
    url: "http://ink-ron.usc.edu/xiangren/"
    btn_label: "Homepage"
    btn_class: "btn--primary"
# venue_row:
#   - image_path: assets/images/neurips.png
#     alt: "NeurIPS 2020"
#     title: "NeurIPS 2020"
#     # excerpt: "Harvard University"
#     url: "/neurips20"
#     btn_label: "Materials"
#     btn_class: "btn--primary"
#   - image_path: assets/images/aaai.png
#     alt: "AAAI 2021"
#     title: "AAAI 2021"
#     excerpt: "Coming Soon"
---

# About

It is impossible to overlook the transformative effect that the field of deep learning has had on the world and sciences. Deep neural networks have been growing omnipresent, thanks to their state-of-the-art performance in a number of domains (computer vision, speech recognition and generation, natural language understanding and translation, etc). Research and newest applications continue sprouting regularly, thus only widening the existing lead. The large swarm of new applications introduces new challenges, including the ones like data and compute efficiency, reliability, robustness and safety, ethical considerations and privacy constraints, and others. 

To reflect on the recent advancements of the deep learning field at KDD 2021, Deep Learning Day will focus on “Understanding Limits and Pushing the Boundaries of Deep Learning”, with topics including theoretical understanding, scaling deep learning, fairness and transparency, and testing and evaluation.

On behalf of the Deep Learning Day and KDD 2021 organizing committee, we welcome you all to attend this event!


<!-- #Call

We plan to solicit short paper submissions for “deep learning critique” from the community, which aims to better understand and to improve all stages of the research process in deep learning. Accepted papers will be given a 15-min slot for contributed talk on the DL day. We invite you to refer to an earlier effort to register trends and debates, analyze bad practices and inventorize open problems at “Critiquing and Correcting Trends in Machine Learning 2018” Workshop: https://ml-critique-correct.github.io/.
 -->



## Call for Submissions

We invite position and/or perspective papers that critically examine common practices and/or trends in theory, methodology, datasets, empirical or ethical standards, publication models, or any other aspect of deep learning research. While we are happy to bring attention to problems with no immediate solutions, we particularly encourage papers which propose a solution or indicate a way forward. Topics of interest include, but are not limited to: 
1. Theoretical understanding of deep learning 
2. Scalability challenges and solutions for deep learning
3. Fairness, transparency, privacy, and ethical implications of deep learning
4. Evaluating and debugging deep learning models
 
While we are interested in submissions that can be broadly characterized as position and/or perspective papers, we particularly welcome submissions that fall into one or more of the following categories. 
 
**Flawed Research Processes and Practices** (4 pages)

We welcome submissions that highlight commonly encountered flawed practices at any stage of the research process. These can either be technical pitfalls pertaining to theoretical, methodological, empirical or ethical aspects of deep learning (See e.g., [1,2,3]), or more procedural practices (e.g, [4]). When possible, papers should also try to highlight work which does not fall pretty to flawed practices, as examples of how they can be avoided.
 
**Unjustified Intuitions or Assumptions** (4 pages)

We welcome submissions that call into question commonly held intuitions or provide clear evidence either for or against assumptions that are regularly taken for granted in the field of deep learning without proper justification. For example, we would like to see papers which provide empirical assessments to test out metrics, verify intuitions, or compare popular current approaches with historic baselines. Such submissions are encouraged regardless of whether these assessments ultimately result in positive or negative results. We would also like to see work which provides results which makes us rethink our intuitions or the assumptions we typically make in the field of deep learning.
 
**Negative Results** (4 pages)

We welcome submissions that show failure modes of theoretical, methodological, empirical or ethical aspects of deep learning or suggest new approaches which one might expect to perform well but which do not. The goal here is to provide a venue for such research on deep learning which is of interest to the broader community but which might otherwise go unpublished. We believe that such research could be incredibly useful in dissuading other researchers from pursuing similar ultimately unsuccessful approaches. Though submitted papers are typically expected to explain why the approach performs poorly, this is not essential if the paper is able to demonstrate why the negative result is of interest to the community in its own right.
 
**Open Problems** (4 pages)

We welcome submissions that describe either (a) unresolved questions in theoretical, methodological, empirical or ethical aspects of deep learning that need to be addressed (See e.g., [5]), (b) desirable operating characteristics for deep learning models in particular application areas that are yet to be achieved, or (c) new frontiers of deep learning research that require rethinking current practices.


### Submission Instructions and Logistics
Each accepted submission will be presented as a talk at the deep learning day of the KDD 2021 conference which will be held virtually on August 18th, 2021. 
Submissions should be formatted using the [ACM paper template](https://www.acm.org/publications/proceedings-template) and uploaded as PDFs. Submissions should contain no more than 4 pages including tables and figures. Each 4-page submission should also include a brief (1-2 paragraph) bio of the main speaker at the end. Authors are free to include an additional two pages of appendix/supplementary material in the submission pdf. **Author names should be anonymized.**   
**Submission Website**:  [https://cmt3.research.microsoft.com/KDDDLD2021/Submission/Index]([https://cmt3.research.microsoft.com/KDDDLD2021/Submission/Index])


### Important Dates:

**Paper Submission Deadline:**  July 1st, 2021 11.59pm AoE  
**Author Notification:**        July 14th, 2021 11.59pm AoE  
**Camera Ready Deadline:**    August 1st, 2021 11.59pm AoE  

# Organizers

{% include feature_row id="organizers_row" %}


<!-- # Tutorials

{% include feature_row id="venue_row" %} -->

<!-- <h3 class="archive__subtitle">{{ site.data.ui-text[site.locale].recent_posts | default: "Recent Posts" }}</h3> -->

<!-- {% if paginator %}
  {% assign posts = paginator.posts %}
{% else %}
  {% assign posts = site.posts %}
{% endif %}

{% for post in posts %}
  {% include archive-single.html %}
{% endfor %}

{% include paginator.html %} -->