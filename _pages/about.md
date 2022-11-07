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

I am currently a Ph.D. student majoring in Formal Verification at Northwestern Polytechnical University under the supervison of [Prof. Zhiming Liu](https://teacher.nwpu.edu.cn/zliu.html). I am a detail oriented PhD student interested in Theorem Proving, ​Concurrent Program Verification, Operating System Formal Development Method and Verification. I love to collaborate and work with different people on multi-disciplinary projects. And from extensive course work, I have built up a solid background in mathematics and dynamic modeling. ​

Previously during my master’s study at Case Western Reserve University (CWRU), I worked on the hexapod design and control project in the CRAB lab supervised by [Prof. Kathryn Daltorio](https://engineering.case.edu/research/labs/Daltorio/), and the joint hexapods locomotion project with National University of Singapore(NUS) supervised by Prof. [Guillaume Sartoretti](https://www.marmotlab.org). 

I received my Bachelor’s degree from Southern University of Science and Technology (SUSTech), China in 2019 with my major in Mechanical Engineering. During this period, I worked on quadruped robot design and control in CLEAR Lab with [Prof. Wei Zhang](https://www.wzhanglab.site).

Please find my CV here for more about my research projects and background. And please feel free to contact me for any questions or opportunities. 

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2022.09*: &nbsp;🎉🎉 I will continue my Ph.D. study at Northwestern Polytechnical University. I am honoured to have the guidance of Prof.Liu.
- *2022.03*: &nbsp;🎉🎉 I received my master degree at Northwestern Polytechnical University. I am very grateful to my supervisors Prof. Zheng, as well as my dear friends and roommates.

# 📝 Publications 

<div id="Conference" style="float:left;margin-top: 5px;">
    <h1 class="content_title">Conference</h1>
    <ol class="main_ul" style="margin-top: 5px;">
    <li><span style="color:green;font-weight: 600;">[TSE’22]</span> <span style="font-weight: 600;">Ying Wang</span>, Yibo Wang, Sinan Wang, <a target="_blank" href="https://yepangliu.github.io/">Yepang Liu*</a>, <a target="_blank" href="https://cs.nju.edu.cn/changxu/">Chang Xu</a>, <a target="_blank" href="https://www.cse.ust.hk/~scc/">Shing-Chi Cheung</a>, <a target="_blank" href="http://faculty.neu.edu.cn/yuhai/">Hai Yu</a>,  and <a target="_blank" href="http://faculty.neu.edu.cn/zzl/">Zhiliang Zhu</a>.
                            Runtime Permission Issues in Android Apps: Taxonomy, Practices, and Ways Forward [J], IEEE Transactions on Software Engineering, To appear.
						    <span style="color:rgb(138, 22, 6);font-weight: 600;">(CCF-A)</span></br> 
    </li>
    <li><span style="color:green;font-weight: 600;">[ICSE’22]</span> Zhenming Li, <span style="font-weight: 600;">Ying Wang*</span>, <a target="_blank" href="https://www.microsoft.com/en-us/research/people/zelin/">Zeqi Lin*</a>, <a target="_blank" href="https://www.cse.ust.hk/~scc/">Shing-Chi Cheung</a>,
							<a target="_blank" href="https://www.microsoft.com/en-us/research/people/jlou/">Jianguang Lou</a>.
                            Nufix: Escape From NuGet Dependency Maze [C], ICSE 2022, To appear. (通讯作者, 学生第一)
							(Acceptance ratio 26.0%=197/751) <span style="color:rgb(138, 22, 6);font-weight: 600;">(CCF-A)</span></br>
							<span style="color:firebrick;font-weight: 600;">[Artifact]</span> <a href="http://www.nufix-dependency-maze.com/" style="font-weight: 600;">NuFix</a>: it helps .NET developers combat dependency hell issues.</br>
							</li>
						<li><span style="color:green;font-weight: 600;">[ICSE’21]</span> <span style="font-weight: 600;">Ying Wang</span>, Liang Qiao, <a target="_blank" href="https://cs.nju.edu.cn/changxu/">Chang Xu*</a>, <a target="_blank" href="https://yepangliu.github.io/">Yepang Liu</a>, <a target="_blank" href="https://www.cse.ust.hk/~scc/">Shing-Chi Cheung</a>, <a target="_blank" href="http://people.cs.vt.edu/nm8247/">Na Meng</a>, <a target="_blank" href="http://faculty.neu.edu.cn/yuhai/">Hai Yu</a> and <a target="_blank" href="http://faculty.neu.edu.cn/zzl/">Zhiliang Zhu</a>.
                            Hero: On the Chaos When PATH Meets Modules [C], ICSE 2021: 99-111.
							(Acceptance ratio 22.4%=138/615) <span style="color:rgb(138, 22, 6);font-weight: 600;">(CCF-A)</span></br> 
							<img src="images/Award.png"/> <span style="color:rgb(209, 36, 13);font-weight: 600;">ACM SIGSOFT Distinguished Paper Award.</span></br>
							<span style="color:firebrick;font-weight: 600;">[Artifact]</span> <a href="http://www.hero-go.com/" style="font-weight: 600;">Hero</a>: it diagnoses dependency management issues for Golang ecosystem.
						</li>
					</ol>
				</div>
<div id="Journal" style="float:left;margin-top: 5px;">
    <h1 class="content_title">Journal</h1>
    <ol class="main_ul" style="margin-top: 5px;">

<li>孟繁祎, <span style="font-weight: 600;">王莹</span>, <a target="_blank" href="http://faculty.neu.edu.cn/yuhai/">于海*</a>, <a target="_blank" href="http://faculty.neu.edu.cn/zzl/">朱志良</a>. 复杂软件系统的重构技术: 现状、问题与展望. 计算机科学. 2020, 47(12): 1-10. <span style="color:rgb(138, 22, 6);font-weight: 600;">封面论文, (CCF-B)</span>
						</li>
</ol>
				</div>	    
[ISSRE'21] Wei Zheng, Manqing Zhang, Hui Tang, Yuanfang Cai, Xiang Chen, Xiaoxue Wu, Abubakar Omari Abdallah Semasaba. Automatically Identifying Bug Reports with Tactical Vulnerabilities by Deep Feature Learning. 2021 IEEE 32nd International Symposium on Software Reliability Engineering. (CCF-B)

[ESEC/FSE'19] Yulei Sui, Yifei Zhang, Wei Zheng, Manqing Zhang, Jingling Xue. Proceedings of the 2019 27th ACM Joint Meeting on European Software Engineering Conference and Symposium on the Foundations of Software Engineering. (CCF-A)

- *Journal articles:

[计算机研究与发展'22] Zheng Wei, Tang Hui, Chen Xiang, Zhang Manqing, Xia Xin. State-of-the-Art Survey of Compatibility Test for Android Mobile Application. Journal of Computer Research and Development, 2022, 59(6): 1370-1387. (CCF-A)

# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Master of Engineering, [School of Mechanical Engineering](https://me.sjtu.edu.cn//) at Shanghai Jiao Tong University.
- *2015.09 - 2019.06*, Bachelor of Engineering (Distinguished Engineer Class), [School of Mechanical Engineering](https://meccol.dhu.edu.cn//) at Donghua University.

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 📚 Reviewer
- IEEE Transactions on Intelligent Transportation Systems (USA, SCI, JCR Q1)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
