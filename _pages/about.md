---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

# About Me

<span class='anchor' id='about-me'></span>

Hi! I'm Yang Liu (柳洋, E-mail: liuyang232@mails.ucas.ac.cn). Now I am a PhD. student of **School of Computer Science and Technology, University of Chinese Academy of Sciences (SCST, UCAS)**, supervised by Prof. [Qingming Huang (黄庆明)](https://qmhuang-ucas.github.io/) (IEEE Fellow) and [Qianqian Xu (许倩倩)](https://qianqianxu010.github.io/) (Professor at ICT, CAS). I have received the B.E. degree in Software Engineering from [HIT](https://www.hit.edu.cn/) in 2023. My research interest includes self-supervised learning, video understanding, and computer vision. 
<!-- I have authored or co-authored several academic papers in top-tier international conferences and journals, including ICML. If you are interested in my research, please email me at liuyang232@mails.ucas.ac.cn. -->




# 🔥 News
- *2026.09*: &nbsp;🎉🎉 One paper has been accepted by NeurIPS 2026.
- *2026.02*: &nbsp;🎉🎉 Two papers have been accepted by CVPR 2026.
- *2025.09*: &nbsp;🎉🎉 One paper has been accepted by NeurIPS 2025.
- *2025.06*: &nbsp;🎉🎉 Winning two first-prizes of the CVPR 2025 Challenges.
- *2025.02*: &nbsp;🎉🎉 One paper has been accepted by CVPR 2025.
- *2024.10*: &nbsp;🎉🎉 Our ACM MultiMedia 2024 paper has been presented as Honourable Mention Award!
<!-- - *2024.10*: &nbsp;🎉🎉 Our ACM MultiMedia 2024 paper has been nominated for best paper awards. -->
- *2024.07*: &nbsp;🎉🎉 One paper has been accepted by ACM MultiMedia 2024 and further selected as an oral.


# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/papers/cvpr26a.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[From Static to Dynamic: Exploring Self-supervised Image-to-Video Representation Transfer Learning](https://arxiv.org/abs/2603.26597)

**Yang Liu**,  [Qianqian Xu\*](https://qianqianxu010.github.io/), [Peisong Wen](https://scholar.google.com.hk/citations?user=Zk2XLWYAAAAJ&hl=zh-CN&oi=ao), [Siran Dai](https://scholar.google.com.hk/citations?user=_6gw9FQAAAAJ&hl=zh-CN&oi=ao), Xilin Zhao, [Qingming Huang\*](https://people.ucas.ac.cn/~qmhuang). 
Conference on Computer Vision and Pattern Recognition (**CVPR, CCF-A**) 2026. | 
[[Code]](https://github.com/yafeng19/Co-Settle) | [[Slides]](https://github.com/yafeng19/Co-Settle) | [[Project]](https://github.com/yafeng19/Co-Settle) 
<!--<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
-->
- This paper proposes a self-supervised image-to-video transfer learning method for effective trade-off between intra-video temporal consistency and inter-video semantic separability.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/papers/cvpr25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[When the Future Becomes the Past: Taming Temporal Correspondence for Self-supervised Video Representation Learning](https://arxiv.org/abs/2503.15096)

**Yang Liu**,  [Qianqian Xu\*](https://qianqianxu010.github.io/), [Peisong Wen](https://scholar.google.com.hk/citations?user=Zk2XLWYAAAAJ&hl=zh-CN&oi=ao), [Siran Dai](https://scholar.google.com.hk/citations?user=_6gw9FQAAAAJ&hl=zh-CN&oi=ao), [Qingming Huang\*](https://people.ucas.ac.cn/~qmhuang). 
Conference on Computer Vision and Pattern Recognition (**CVPR, CCF-A**) 2025. | 
[[Code]](https://github.com/yafeng19/T-CORE) | [[Slides]](https://github.com/yafeng19/T-CORE) | [[Project]](https://github.com/yafeng19/T-CORE) 
<!--<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
-->
- This paper proposes a self-supervised framework for dense-level video representation learning with temporal correspondence.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACMMM 2024 (Oral)</div><img src='images/papers/acmmm24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Not All Pairs are Equal: Hierarchical Learning for Average-Precision-Oriented Video Retrieval](https://arxiv.org/abs/2407.15566)

**Yang Liu**,  [Qianqian Xu\*](https://qianqianxu010.github.io/), [Peisong Wen](https://scholar.google.com.hk/citations?user=Zk2XLWYAAAAJ&hl=zh-CN&oi=ao), [Siran Dai](https://scholar.google.com.hk/citations?user=_6gw9FQAAAAJ&hl=zh-CN&oi=ao), [Qingming Huang\*](https://people.ucas.ac.cn/~qmhuang). 
ACM International Conference on Multimedia (**ACM MultiMedia, CCF-A**) 2024.  **<font color='red'> (Honourable Mention Award) </font>**  **<font color='red'> (Oral, 3.97%) </font>** | 
[[Code]](https://github.com/yafeng19/HAP-VR) | [[Slides]](https://github.com/yafeng19/yafeng19.github.io/tree/master/resources/ACMMM2024_Oral.pdf) | [[Project]](https://github.com/yafeng19/HAP-VR) 
<!--<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
-->
- This paper proposes a self-supervised video retrieval framework with hierarchical AP optimization from the view of aligning the training objective and the evaluation metric.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2026</div><img src='images/papers/neurips26.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Improving Self-Supervised Vision Transformers with Cross Distillation]()

[Siran Dai](https://scholar.google.com.hk/citations?user=_6gw9FQAAAAJ&hl=zh-CN&oi=ao), [Qianqian Xu\*](https://qianqianxu010.github.io/), [Peisong Wen](https://scholar.google.com.hk/citations?user=Zk2XLWYAAAAJ&hl=zh-CN&oi=ao), **Yang Liu**, [Xiaochun Cao](https://scst.sysu.edu.cn/teacher/CaoXiaochun), [Qingming Huang\*](https://people.ucas.ac.cn/~qmhuang).
Annual Conference on Neural Information Processing Systems (**NeurIPS, CCF-A**) 2026. |
[[Code]]() | [[Slides]]() | [[Project]]()
- This paper proposes cross distillation to transfer global class-token semantics into masked patch targets, improving both dense prediction and image classification in self-supervised Vision Transformers.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='images/papers/neurips25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Exploring Structural Degradation in Dense Representations for Self-supervised Learning](https://arxiv.org/abs/2510.17299)

[Siran Dai](https://scholar.google.com.hk/citations?user=_6gw9FQAAAAJ&hl=zh-CN&oi=ao), [Qianqian Xu\*](https://qianqianxu010.github.io/), [Peisong Wen](https://scholar.google.com.hk/citations?user=Zk2XLWYAAAAJ&hl=zh-CN&oi=ao), **Yang Liu**, [Qingming Huang\*](https://people.ucas.ac.cn/~qmhuang).
Annual Conference on Neural Information Processing Systems (**NeurIPS, CCF-A**) 2025. | 
[[Code]]() | [[Slides]]() | [[Project]]() 
<!--<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
-->
- This paper provides an observation of dense degradation phenomenon in self-supervised learning and introduces a Dense representation Quality Estimator to mitigate dense degradation.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CJC 2026</div><img src='images/papers/cjc26.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Collaborative Salient Object Detection via Complex Background Semantic Modeling](https://kns.cnki.net/kcms2/article/abstract?v=OGEEvuKkrhYso5Gd6juhmcmlnUp3D_muDen3-Jo4giItV_wJzCz_3k8WUqib_5DSppwCslKSMhQIINa445GY61nHGzHC7AjY8y-xztS7Gp2JwL74qLXTBr7upyUmpKzKSpz55lI55kydLNiG1HulgWkPk4EfqNv5VGW6v4ne041433d1b2-jTw==&uniplatform=NZKPT&language=CHS)

[Zitai Wang](https://wang22ti.com/), [Qianqian Xu\*](https://qianqianxu010.github.io/), Yuchen Cao, **Yang Liu**, [Qingming Huang\*](https://people.ucas.ac.cn/~qmhuang). 
Chinese Journal of Computers (**计算机学报, CCF-A**) 2026. | 
[[Code]]() | [[Slides]]() | [[Project]]() 
<!--<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
-->
- This paper introduces a co-salient object detection method that improves detection accuracy by explicitly addressing the semantic ambiguity and heterogeneity of background regions.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/papers/cvpr26b.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Safe Codebook: Token-Level Moderation for Safer Visual Autoregressive Generation]()

Jiaxuan Zhang, [Qianqian Xu\*](https://qianqianxu010.github.io/), [Peisong Wen](https://scholar.google.com.hk/citations?user=Zk2XLWYAAAAJ&hl=zh-CN&oi=ao), [Siran Dai](https://scholar.google.com.hk/citations?user=_6gw9FQAAAAJ&hl=zh-CN&oi=ao), **Yang Liu**, [Qingming Huang\*](https://people.ucas.ac.cn/~qmhuang). 
Conference on Computer Vision and Pattern Recognition (**CVPR Findings, CCF-A**) 2026. | 
[[Code]]() | [[Slides]]() | [[Project]]() 
<!--<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
-->
- This paper proposes a training-free controllable framework for Visual Autoregressive models to effectively suppress harmful content while maintaining high fidelity to the original image.
</div>
</div>

- [Bootstrapping Physics-Grounded Video Generation through VLM-Guided Iterative Self-Refinement](https://arxiv.org/abs/2511.20280), **Yang Liu**, Xilin Zhao, Peisong Wen, Siran Dai, Qingming Huang. ICCV Workshop on Physics-IQ × Perception Test Challenge, 2025.

- [Exploring Non-contrastive Self-supervised Representation Learning for Image-based Profiling](https://arxiv.org/abs/2506.14265), Siran Dai, Qianqian Xu, Peisong Wen, **Yang Liu**, Qingming Huang. CVPR Workshop on Computer Vision for Drug Discovery, 2025.

# 💬 Invited Talks
- *2025.11*: Talk on University of Chinese Academy of Sciences 2025 Graduate Academic Forum. [\[Website\]](https://cnic.cas.cn/yjsjy/pygl/202511/t20251119_8014065.html)
- *2025.10*: Talk on third-place solution for ICCV 2025 Physics-IQ × Perception Test Challenge. [\[Slides\]](https://github.com/yafeng19/yafeng19.github.io/tree/master/resources/ICCV_PhyIQ_talk.pdf)
- *2025.10*: Talk on 2025 China Journal of Image and Graphics Graduate Student Academic Salon. [\[Website\]](https://mp.weixin.qq.com/s/6-cKZ01YnX3ASSqN_8q2XQ)
- *2025.06*: Talk on first-place solution for CVPR 2025 AVA Challenge of 3D Human Motion Generation Track. [\[Slides\]](https://github.com/yafeng19/yafeng19.github.io/tree/master/resources/CVPR2025_AVA_Talk.pdf)
- *2024.12*: Talk on Young Scientists Conference of CSIG 2024. [\[Poster\]](https://github.com/yafeng19/yafeng19.github.io/tree/master/resources/CSIG2024_Poster.pdf)
- *2024.10*: Oral presentation of ACM MultiMedia 2024. [\[Slides\]](https://github.com/yafeng19/yafeng19.github.io/tree/master/resources/ACMMM2024_Oral.pdf)



# 🏅 Honors and Awards
### Research Awards
- *2026.10*: NeurIPS 2026 Top Reviewer. [\[Website\]](https://neurips.cc/Conferences/2026/ProgramCommittee).
- *2025.10*: Third place in ICCV 2025 Physics-IQ × Perception Test Challenge. [\[Website\]](https://physics-iq.github.io/workshop/physics-iq-challenge.html).
- *2025.10*: Outstanding report on 2025 China Journal of Image and Graphics Graduate Student Academic Salon. [\[Website\]](https://mp.weixin.qq.com/s/6-cKZ01YnX3ASSqN_8q2XQ)
- *2025.06*: First place in CVPR 2025 AVA Challenge of 3D Human Motion Generation Track. [\[Website\]](https://accessibility-cv.github.io/).
- *2025.06*: First place in CVPR 2025 Computer Vision for Drug Discovery Challenge. [\[Website\]](https://cvdd-cvpr25.github.io/challenge.html).
- *2024.12*: Excellent Poster on Young Scientists Conference of CSIG 2024. [\[Website\]](http://youth.csig.org.cn/CSIG2024/index.html#/announcement/2024-12-21-success).
- *2024.10*: ACM MultiMedia 2024 Honourable Mention Award. (<font color='red'>ACM MultiMedia 2024 最佳论文荣誉提名奖</font>) [\[Website\]](https://2024.acmmm.org/awards).


### Honorary Prizes
<!-- - *2026.11*: Youth Talents Support Project - Doctoral Student Special Program, 2026 December. (中国科协青年人才托举工程-博士生专项) -->
- *2026.05*: Excellent Student Leader‌ of UCAS. (优秀学生干部)
- *2026.01*: Excellent Students of Beijing. (北京市三好学生)
- *2025.12*: National Scholarship for Doctoral Students. (博士研究生国家奖学金)
- *2025.05*: President of Chinese Academy of Sciences Excellence Award. (中国科学院院长优秀奖)
- *2025.05*: Pacemaker to Merit Student of UCAS. (三好学生标兵)
- *2023.07*: Excellent Graduates of Shandong Province. (山东省优秀毕业生)
- *2023.05*: Excellent Students of Shandong Province. (山东省优秀学生)
- *2023.04*: The 21st Top Ten Undergraduates of HIT. (哈工大威海十佳大学生)
- *2020.12*: National Scholarship for Undergraduates. (本科生国家奖学金)


# 📖 Academic Services
### Journal
- IEEE Transactions on Multimedia (IEEE T-MM): Reviewer
- IEEE Transactions on Circuits and Systems for Video Technology (IEEE T-CSVT): Reviewer
- Multimedia Systems: Reviewer
- Artificial Intelligence In Medicine: Reviewer

### Conference
- ICLR: Reviewer (2027)
- NeurIPS: Reviewer (2026)
- CVPR: Reviewer (2026)
- ECCV: Reviewer (2026)
- ACM MultiMedia: Reviewer (2024)


# 🎓 Educations
<div class='school-box'>
<div><img src='images/ucas.jpg' alt="sym" width="80"></div>
<div class='school-box-text' markdown="1">
2023.09 - Now, **Ph.D. Student**.<br>
School of Computer Science and Technology.<br>
University of Chinese Academy of Sciences (UCAS), Beijing.
</div>
</div>

<div class='school-box'>
<div><img src='images/hit.png' alt="sym" width="80"></div>
<div class='school-box-text' markdown="1">
2019.09 - 2023.06, **Undergraduate**.<br>
School of Computer Science and Technology.<br>
Harbin Institute of Technology (HIT), Weihai.
</div>
</div>


<!--


# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
-->

<!--
How to update
1. run `jekyll serve -l -H localhost` in bash
2. git add .
3. git commit -m "xxx"
4. git push origin master
-->