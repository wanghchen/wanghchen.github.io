---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "<https://cdn.jsdelivr.net/gh/>" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "<https://raw.githubusercontent.com/>" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

My name is Huanchen Wang (王焕辰). I am a Ph.D. candidate in the Department of Computer Science, City University of Hong Kong (<a href="https://www.cityu.edu.hk/">CityUHK</a>) from Sep. 2022 under CityU-SUSTech Joint PhD Programme, supervised by Prof. <a href="https://cse.sustech.edu.cn/faculty/~mayx/">Yuxin Ma</a> (from Southern University of Science and Technology), Prof. <a href="https://luzhc.github.io/">Zhicong Lu</a> (from George Mason University, previously at CityUHK),, and <a href="https://www.cs.cityu.edu.hk/~zhichalu/">Zhichao Lu</a> (CityuHK). I am a member of DEER Lab and DVA Lab.

I received my BEng degree from the Department of Computer Science and Engineering, Southern University of Science and Technology (<a href="https://www.sustech.edu.cn/">SUSTech</a>) in July, 2022, under the supervision of Professor [Xuan Song](https://www.sustech.edu.cn/en/faculties/songxuan.html).

My current research primarily focuses on Human-Computer Interaction (HCI) in the context of Creativity Supporting and Human-AI Collaboration, particularly as it relates to [Intangible Cultural Heritage (ICH)](https://ich.unesco.org/en/what-is-intangible-heritage-00003). I am also interested in Interactive Visual Analytics, with a focus on Explainable AI (XAI) and multi-modal models.

<span class='anchor' id='-news'></span>

<body>

<h1>🔥 News</h1>

<ul id="news-list">
<li>
<strong>2025.11</strong>: Attending to IEEE VIS 2025 (Vienna, Austria)!
</li>
<li>
<strong>2025.10</strong>: Attending to ACM UIST 2025 (Busan, Korea)!
</li>
<li>
<strong>2025.07</strong>: 🎉🎉 One paper is accepted by IEEE VIS 2025. Congrats to all the co-authors! 
</li>
<li>
<strong>2025.07</strong>: 🎉🎉 One paper is accepted by ACM UIST 2025. Thanks to all the co-authors! 
</li>
<li>
<strong>2025.04</strong>: Attending to ACM CHI 2025 (Yokohama, Kanagawa, Japan)!
</li>
<li>
<strong>2025.02</strong>: 🎉🎉 One paper is accepted by ACM CSCW 2025. Thanks to all the co-authors! 
</li>
<li  class="hidden-item">
<strong>2025.01</strong>: 🎉🎉 One paper is accepted by ACM CHI 2025. Congrats to all the co-authors! 
</li>
<li  class="hidden-item">
<strong>2024.10</strong>: 🎉🎉 One paper is accepted by ACM CSCW 2025. Thanks to all the co-authors! 
</li>
<li class="hidden-item">
<strong>2024.05</strong>: Attending to ACM CHI 2024 (Honolulu, Hawaii, USA)!
</li>
<li class="hidden-item">
<strong>2024.01</strong>: 🎉🎉  One paper is accepted by ACM CHI 2024. Congrats to all the co-authors! 
</li>
<li class="hidden-item">
<strong>2023.01</strong>: 🎉🎉 One paper is accepted by ACM CHI 2023. Thanks to all the co-authors! 
</li>
<li class="hidden-item">
<strong>2022.10</strong>: 🎉🎉 Two papers are accepted by IEEE BigData 2022. Thanks to all the co-authors! 
</li>
</ul>
<div>
	<a href="#" onclick="toggleNews(); return false;" id="more-link">More</a>
</div>

<script>         
    // 页面加载时初始化隐藏项         
    document.addEventListener('DOMContentLoaded', function() {
        const hiddenItems = document.getElementsByClassName('hidden-item');             
        for (let item of hiddenItems) {                 
            item.style.display = 'none';             
        }         
    });                  
    function toggleNews() {             
        const hiddenItems = document.getElementsByClassName('hidden-item');             
        const moreLink = document.getElementById('more-link');                          
        if (hiddenItems[0].style.display === 'none') {                 
            // 显示所有隐藏项                 
            for (let item of hiddenItems) {                     
                item.style.display = 'list-item';                 
            }                 
            moreLink.textContent = 'Collapse';             
        } else {                 
            // 隐藏所有项                 
            for (let item of hiddenItems) {                     
                item.style.display = 'none';                 
            }                 
            moreLink.textContent = 'More';             
        }         
    }     
</script>

</body>

<span class='anchor' id='-publications'></span>

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">VIS 2025</div><img src='images/vismodal.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[VisMoDAl: Visual Analytics for Evaluating and Improving Corruption Robustness of Vision-Language Models](https://arxiv.org/pdf/2509.14571) \\
[**Huanchen Wang**](https://wanghchen.github.io)\*, Wencheng Zhang\*, Zhiqiang Wang, [Zhicong Lu](https://luzhc.github.io/),  [Yuxin Ma](https://cse.sustech.edu.cn/faculty/~mayx/)

(* = equal contribution)

IEEE Transactions on Visualization and Computer Graphics (VIS 2025), 2026. (to appear)

[<a href="https://arxiv.org/pdf/2509.14571">arxiv</a>] | [<a href="/publications/vismodal/vismodal.mp4">demo</a>]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">UIST  2025</div><img src='images/ragtrace.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[RAGTrace: Understanding and Refining Retrieval-Generation Dynamics in Retrieval-Augmented Generation](https://arxiv.org/pdf/2508.06056) \\
Sizhe Chen\*, Jiaping Li\*, [**Huanchen Wang**](https://wanghchen.github.io),  [Yuxin Ma](https://cse.sustech.edu.cn/faculty/~mayx/)

(* = equal contribution)

Proceedings of the 37th Annual ACM Symposium on User Interface Software and Technology (UIST 2025), 2025.

[<a href="https://dl.acm.org/doi/10.1145/3746059.3747741">ACM Digital Library</a>] | [<a href="https://arxiv.org/pdf/2508.06056">arxiv</a>] | [<a href="/publications/ragtrace/video-figure.mp4">demo</a>]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CSCW  2025</div><img src='images/polymind.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Polymind: Parallel Visual Diagramming with Large Language Models to Support Prewriting Through Microtasks](https://arxiv.org/pdf/2502.09577) \\
[Qian Wan](https://llewynwan.github.io/), [Jiannan Li](https://jchrisli.github.io/), [**Huanchen Wang**](https://wanghchen.github.io), [Zhicong Lu](https://luzhc.github.io/)

Proceedings of the ACM on Human-Computer Interaction, 9(7):1-29  (CSCW 2025), 2025.

[<a href="https://dl.acm.org/doi/10.1145/3757497">ACM Digital Library</a>] | [<a href="https://arxiv.org/pdf/2508.06056">arxiv</a>] 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CSCW  2025</div><img src='images/danmodcap.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DanModCap: Designing a Danmaku Moderation Tool for Video-Sharing Platforms that Leverages Impact Captions](https://arxiv.org/pdf/2408.02574) \\
[Siying Hu](https://scholar.google.com/citations?user=BJg8enwAAAAJ), [**Huanchen Wang**](https://wanghchen.github.io), [Yu Zhang](https://scholar.google.com/citations?user=IoPD6n4AAAAJ), [Piaohong Wang](https://sites.google.com/view/wamgpiaohong/homepage), [Zhicong Lu](https://luzhc.github.io/)

Proceedings of the ACM on Human-Computer Interaction, 9(2):1-27 (CSCW 2025), 2025.

[<a href="https://dl.acm.org/doi/10.1145/3706598.3714159">ACM Digital Library</a>] | [<a href="https://arxiv.org/pdf/2408.02574">arxiv</a>] 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CHI  2025</div><img src='images/harmonycut.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[HarmonyCut: Supporting Creative Chinese Paper-cutting Design with Form and Connotation Harmony](https://arxiv.org/pdf/2502.07628) \\
[**Huanchen Wang**](https://wanghchen.github.io)\*, Tianrun Qiu\*, Jiaping Li, [Zhicong Lu](https://luzhc.github.io/),  [Yuxin Ma](https://cse.sustech.edu.cn/faculty/~mayx/)

(* = equal contribution)

Proceedings of the ACM CHI Conference on Human Factors in Computing Systems (CHI 2025), 2025.

[<a href="https://dl.acm.org/doi/10.1145/3710954">ACM Digital Library</a>] | [<a href="https://arxiv.org/pdf/2502.07628">arxiv</a>] |   [<a href="https://www.youtube.com/watch?v=0JNOF7ceFig">presentation</a>] | [<a href="/publications/papercutting/video-figure.mp4">demo</a>]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CHI  2024</div><img src='images/CHSICH.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<a href="/publications/chs-ich-douyin/2024-CHI-CHSICH.pdf">Critical Heritage Studies as a Lens to Understand Short Video Sharing of Intangible Cultural Heritage on Douyin</a>
\\
[**Huanchen Wang**](https://wanghchen.github.io), [Minzhu Zhao](https://mindyzhaominzhu.github.io), Wanyang Hu, [Yuxin Ma](https://cse.sustech.edu.cn/faculty/~mayx/), [Zhicong Lu](https://luzhc.github.io/)

Proceedings of the ACM CHI Conference on Human Factors in Computing Systems (CHI 2024), 2024.

[<a href="https://dl.acm.org/doi/10.1145/3613904.3642138">ACM Digital Library</a>] | [<a href="https://www.youtube.com/watch?v=5_u8UBYTmVE">presentation</a>] 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CHI  2023</div><img src='images/bilisci.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<a href="/publications/understanding-sci-bili/2023-CHI-BiliSci.pdf">Understanding Communication Strategies and Viewer Engagement with Science Knowledge Videos on Bilibili</a> \\
[Yu Zhang](https://scholar.google.com/citations?user=IoPD6n4AAAAJ), [Changyang He](https://hechangyang.com/), [**Huanchen Wang**](https://wanghchen.github.io), [Zhicong Lu](https://luzhc.github.io/)

Proceedings of the ACM CHI Conference on Human Factors in Computing Systems (CHI 2023), 2023.

[<a href="https://dl.acm.org/doi/10.1145/3544548.3581476">ACM Digital Library</a>] | [<a href="https://www.youtube.com/watch?v=-KpemLOBt1s">presentation</a>]
</div>
</div>

- **A Geomagnetic Sensor Dataset for Traffic Flow Prediction**

  [**Huanchen Wang**](https://wanghchen.github.io)\*, [Quanjun Chen](https://scholar.google.com/citations?user=_PKwzTwAAAAJ)\*, [Zheng Dong](https://scholar.google.com/citations?user=Bgq0fbYAAAAJ), [Xuan Song](https://www.sustech.edu.cn/en/faculties/songxuan.html), Hao Tian, Donglong Yang, Manxia Liu

  (* = equal contribution)

  IEEE International Conference on Big Data (Big Data '22), 2022.

  [<a  href="/publications/geomagnetic-dataset/2022-IEEEBigData-Geomagnetic.pdf">pdf</a>]

- **Learning Latent Road Correlations from Trajectories**

  [Zheng Dong](https://scholar.google.com/citations?user=Bgq0fbYAAAAJ), [Quanjun Chen](https://scholar.google.com/citations?user=_PKwzTwAAAAJ), [Renghe Jiang](https://www.renhejiang.com/), [**Huanchen Wang**](https://wanghchen.github.io), [Xuan Song](https://www.sustech.edu.cn/en/faculties/songxuan.html), Hao Tian

  IEEE International Conference on Big Data (Big Data '22), 2022.

  [<a href="/publications/latent-road-correlations/2022-IEEEBigData-Road.pdf">pdf</a>]

<span class='anchor' id='-honors-and-awards'></span>
# 🎖 Honors and Awards

- *2022-2026* Postgraduate Scholarship, SUSTech & CityU.
- *2018* Third-class Outstanding Freshmen Scholarship, SUSTech.

<span class='anchor' id='-educations'></span>
# 📖 Educations

- *2022.09 - current*, PhD candidate, Department of Computer Science, City University of Hong Kong, Hong Kong SAR, China.
- *2018.09 - 2022.07*, Undergraduate, Department of Computer Science and Engineering, Southern University of Science and Technology, Shenzhen, China.

<span class='anchor' id='-services'></span>
# 🔨 Services

- Reviewer of ACM CHI 2023-2026.
- Reviewr of IEEE PacificVis 2026.
- Reviewer of ACM UIST 2025.
- Reviewer of ACM CSCW 2024, 2025.
- PC Member of Special Track on Cultural Heritage of VINCI 2025.
- Reviewer of ICHEC (Chinese CHI) 2024, 2025.
- Reviewer of ChinaVis 2024.

<span class='anchor' id='-teaching-experiences'></span>
# 🏫 Teaching Experiences

- Fall 2025: TA for CS5489 Machine Learning: Algorithm & Applications (CityU)
- Spring 2023: TA for CS2303 Data Structures for Media (CityU)
- Fall 2022: TA for JC2066 IT Professionals: Ethical, Legal and Social Issues (CityU)
