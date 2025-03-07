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

<span class='anchor' id='about-me'></span>
Manqing Zhang is a third-year PhD student at Northwestern Polytechnical University under the supervision of [Prof. Zhiming Liu](https://www.rise-swu.cn/en/liuzhiming.html). I got my master degree of Software Engineering from Northwestern Polytechnical University in 2022. I am a visiting student at Southern University of Science and Technology (SUSTech), supervised by Prof. [Yepang Liu](https://yepangliu.github.io).

My research is focused on using formal verification techniques to ensure system software security. Specifically, my current research focuses on designing techniques to improve the efficiency of interactive theorem proving script synthesis and evolution. In addition, I am also interested in learning and exploring related theories and techniques of model checking. 

I am very fond of discussions and exchanges, if you are interested in my research, please email me.<img src="images/jiaoliu.png" width="25" height="25">  I also welcome the whiz in formal verification research to take me off the ground.<img src="images/xiaoku.png" width="25" height="25">

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2024.09*: &nbsp;🎉🎉 I will be a visiting student at Southern University of Science and Technology. I am honored to work under the guidance of Prof. Yepang.
- *2022.09*: &nbsp;🎉🎉 I will continue my Ph.D. study at Northwestern Polytechnical University. I am honoured to have the guidance of Prof.Liu.
- *2022.03*: &nbsp;🎉🎉 I received my master degree at Northwestern Polytechnical University. I am very grateful to my supervisors Prof. Zheng, as well as my dear friends and roommates.

# 📝 Publications 
<!-- <img src="images/Award.png"/> <span style="color:rgb(209, 36, 13);font-weight: 600;">ACM SIGSOFT Distinguished Paper Award.</span><br /> -->

<div id="Conference" style="float:left;margin-top: 5px;">
    <p class="a">
      <img src="images/google_scholar.png" width="25" height="25">
      <a href="https://scholar.google.com.hk/citations?hl=zh-CN&pli=1&user=9C3ekxYAAAAJ">Google Scholar</a>
      &nbsp;&nbsp;
      <img src="images/dblp.png" width="25" height="25">
      <a href="https://dblp.org/pid/246/5343.html">DBLP</a>
    </p>
    <p style="color:blue"># means co-first author; * means corresponding author</p>
    <h1 class="content_title">Conference</h1>
    <ol class="main_ul" style="margin-top: 5px;">
    <li><span style="color:green;font-weight: 600;">[QRS’24]</span> <span style="font-weight: 600;">Manqing Zhang</span>, Renliang Wu, Kang Su, Yunwei Dong and Tao Zhang. <strong>Application Scenario Modeling and Verification for Unmanned Aerial Vehicle Swarm.</strong> The 24th IEEE International Conference on Software Quality, Reliability, and Security.   
    <span style="color:rgb(138, 22, 6);font-weight: 600;">(CCF-C)</span>
	    <a href="publications/saner21.pdf"><img src="images/pdf.png" width="25" height="25"></a>
    </li>  
    <li><span style="color:green;font-weight: 600;">[ISSRE’21]</span> Wei Zheng, <span style="font-weight: 600;">Manqing Zhang*</span>, Hui Tang, <a target="_blank" href="https://www.cs.drexel.edu/~yfcai/index.html">Yuanfang Cai</a>, <a target="_blank" href="https://smartse.github.io/">Xiang Chen</a>, Xiaoxue Wu and Abubakar Omari Abdallah Semasaba. <strong>Automatically Identifying Bug Reports with Tactical Vulnerabilities by Deep Feature Learning.</strong> 2021 IEEE 32nd International Symposium on Software Reliability Engineering. (Acceptance ratio 27.5%=52/189)  
        <span style="color:rgb(138, 22, 6);font-weight: 600;">(CCF-B)</span>
	    <a href="publications/issre21.pdf"><img src="images/pdf.png" width="25" height="25"></a>
	    <a href="https://github.com/zmqgeek/Itactivul"> <img src="images/github.png" width="25" height="25"></a>
	    <img src="images/slides.png" width="25" height="25">
    </li>
    <li><span style="color:green;font-weight: 600;">[SANER’21]</span> Wei Zheng, Guoliang Liu, <span style="font-weight: 600;">Manqing Zhang</span>, <a target="_blank" href="https://smartse.github.io/">Xiang Chen</a> and Wenqiao Zhao. <strong>Research Progress of Flaky Tests.</strong> 2021 IEEE International Conference on Software Analysis, Evolution and Reengineering.   
    <span style="color:rgb(138, 22, 6);font-weight: 600;">(CCF-B)</span>
	    <a href="publications/saner21.pdf"><img src="images/pdf.png" width="25" height="25"></a>
    </li>    
    <li><span style="color:green;font-weight: 600;">[ESEC/FSE’19]</span> <a target="_blank" href="https://yuleisui.github.io">Yulei Sui</a>, Yifei Zhang, Wei Zheng, <span style="font-weight: 600;">Manqing Zhang</span> and <a target="_blank" href="https://www.cse.unsw.edu.au/~jingling/">Jingling Xue</a>. <strong>Event Trace Reduction for Effective Bug Replay of Android Apps via Differential GUI State Analysis.</strong> Proceedings of the 2019 27th ACM Joint Meeting on European Software Engineering Conference and Symposium on the Foundations of Software Engineering. 
        <span style="color:rgb(138, 22, 6);font-weight: 600;">(CCF-A)</span>
	    <a href="publications/fse19.pdf"><img src="images/pdf.png" width="25" height="25"></a>
	    <a href="https://github.com/zmqgeek/Echo"> <img src="images/github.png" width="25" height="25"></a>
	    <img src="images/slides.png" width="25" height="25">
	    <a href="https://www.youtube.com/watch?v=0UCVIIEigEI"><img src="images/video.png" width="25" height="25"></a><br />
	<span style="color:firebrick;font-weight: 600;">[Artifact]</span> <a href="https://github.com/zmqgeek/Echo" style="font-weight: 600;">Echo</a>: it replay and reduce Android GUI test cases.
    </li>
    </ol>
</div>
				
				
<div id="Journal" style="float:left;margin-top: 5px;">
    <h1 class="content_title">Journal</h1>
    <ol class="main_ul" style="margin-top: 5px;">
    <li><span style="color:green;font-weight: 600;">[JSS'25]</span> <span style="font-weight: 600;">Manqing Zhang</span>, Yunwei Dong, Tao Zhang, Kang Su and Zeshan Li. <strong>Modeling and Verifying Resources and Capabilities of Ubiquitous Scenarios for Unmanned Aerial Vehicle Swarm.</strong> Journal of Systems and Software (JSS) 2025. 
    <span style="color:rgb(138, 22, 6);font-weight: 600;">(SCI 2区)</span><a href="publications/jcrd22.pdf"><img src="images/pdf.png" width="25" height="25"></a>
    </li>
    <li><span style="color:green;font-weight: 600;">[TMM'24]</span> Lingru Zhou, Yiqi Gao, <span style="font-weight: 600;">Manqing Zhang</span>, Peng Wu, Peng Wang and Yanning Zhang. <strong>Human-centric Behavior Description in Videos: New Benchmark and Model.</strong> IEEE Transactions on Multimedia (TMM) 2024. 
    <span style="color:rgb(138, 22, 6);font-weight: 600;">(SCI 1区)</span><a href="publications/jcrd22.pdf"><img src="images/pdf.png" width="25" height="25"></a>
    </li>
    <li><span style="color:green;font-weight: 600;">[计算机研究与发展'22]</span> 郑炜, 唐辉, <a target="_blank" href="https://smartse.github.io/">陈翔</a>, <span style="font-weight: 600;">张满青</span>, <a target="_blank" href="https://xin-xia.github.io/">夏鑫</a>. <strong>安卓移动应用兼容性测试综述.</strong> 计算机研究与发展, 2022, 59(6): 1370-1387. 
    <span style="color:rgb(138, 22, 6);font-weight: 600;">(CCF-A)</span><a href="publications/jcrd22.pdf"><img src="images/pdf.png" width="25" height="25"></a>
    </li>
    </ol>
</div>	   

# 🎖 Honors and Awards

- ![Award1](images/Award1.png) *2022.08*, 西北工业大学优秀硕士学位论文奖. \[[Reference](https://gs.nwpu.edu.cn/info/2141/15244.htm)\]
- ![Award1](images/Award1.png) *2019.04*, 安徽省普通高等学校品学兼优毕业生.

# 📖 Educations
- *2022.09 - now*, School of Software, Northwestern Polytechnical University
  
  Ph.D., Software Engineering, Supervisors: [Prof. Zhiming Liu](https://www.rise-swu.cn/en/liuzhiming.html)
  
- *2019.09 - 2022.04*, School of Software, Northwestern Polytechnical University

  Master of Engineering, Software Engineering, Supervisors: [Prof. Wei Zheng](https://teacher.nwpu.edu.cn/zhengwei.html)
  
- *2015.09 - 2019.06*, School of Computer and Information, Anhui Polytechnic University

  Bachelor of Engineering, Computer Science & Technology, Supervisors: [Prof. Yu Xiu](https://www.ahpu.edu.cn/jsjyxxgc/2014/0524/c5472a75718/page.htm)

# 💬 Invited Talks

- Academic newbie, has not been invited yet.<img src="images/xiaobai.png" width="25" height="25">

# 📚 Reviewer

- Not enough level to be a reviewer.<img src="images/xiaoku.png" width="25" height="25">

# 💻 Internships

- When the research is done well, it may be possible to do an internship for a period of time.<img src="images/idea.png" width="25" height="25">
