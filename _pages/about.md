---
permalink: /
title: ''
excerpt: About me
author_profile: true
redirect_from:
  - /about/
  - /about.html
published: true
---

<head>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
</head>

I am an Assistant Professor at the University of Macau, where I direct the [Embodied Intelligence (UMEI) lab](https://um-ei.github.io/). Prior to joining UM, I was a postdoctoral scholar at Stanford University, working with [Prof. Shuran Song](https://shurans.github.io/) and [Prof. Jeannette Bohg](https://web.stanford.edu/~bohg/). I received my Ph.D. from Northeastern University, where I was advised by [Prof. Robert Platt](https://www2.ccs.neu.edu/research/helpinghands/people/) and [Prof. Robin Walters](http://www.robinwalters.com/).

My research interests include embodied AI, robot learning, robotic manipulation, geometric deep learning, and reinforcement learning. My work was selected as an Outstanding Paper Award Finalist at the Conference on Robot Learning (CoRL) 2024 and received a Best Paper Award Honorable Mention from IEEE Robotics and Automation Letters (RA-L) in 2025. During my Ph.D., I was a recipient of the JPMorgan Chase Ph.D. Fellowship.

Email: dianwang at um dot edu dot mo / [CV](dian_wang_CV.pdf)

## News
<style>
#myList {
    margin-bottom: 0;
}
#myList li:nth-child(n+6) {
    display: none;
}
#more {
    cursor: pointer;
    color: #52adc8; /* Replace with your desired color */
    margin-left: 1.5em; /* Adjust as needed */
    margin-top: 0;
    display: inline-block;
}
</style>
<script>
document.addEventListener("DOMContentLoaded", function() {
  document.getElementById("more").addEventListener("click", function(){
      var listItems = document.querySelectorAll('#myList li:nth-child(n+6)');
      for(var i=0; i<listItems.length; i++){
        listItems[i].style.display = 'list-item';
      }
      this.style.display = 'none';
  });
});
</script>

<ul id="myList">
  <li>08/2026: Very excited to begin my new role as an Assistant Professor at the University of Macau!</li>
  <li>05/2026: I will give a talk at the <a href="https://sites.google.com/view/icra-2026-tutorial-geometry/">3rd Tutorial on Geometric Methods in Robot Learning, Optimization and Control</a> at ICRA, see you in Vienna!</li>
  <li>05/2026: <a href="https://mingxi-jia.github.io/gem_page/">Learning Efficient and Robust Language-conditioned Manipulation using Textual-Visual Relevancy and Equivariant Language Mapping</a> is selected as RAL 2025 Best Paper Award Honorable Mention!</li>
  <li>07/2025: Super excited to start my postdoc at Stanford with Prof. Shuran Song and Prof. Jeannette Bohg!</li>
  <li>04/2025: Honored to receive <a href="https://academic-honors.provost.northeastern.edu/graduate-awards/graduate-research-awards/">Northeastern Outstanding Ph.D. Student Award in Research</a>!</li>
  <li>03/2025: Invited talk at <a href="https://bostonsymmetry.github.io/">Boston Symmetry Day</a>.</li>
  <li>11/2024: <a href="https://equidiff.github.io/">Equivariant Diffusion Policy</a> is nominated as an Outstanding Paper Award Finalist at CoRL 2024!</li>
  <li>10/2024: Robin and I presented <a href="https://www.youtube.com/watch?v=MU6wpz_8kEA">Pushing the Limits of Equivariant Neural Networks</a> at the <a href="https://www.neurreps.org/speaker-series">NeurReps Speaker Series</a> at MIT.</li>
  <li>09/2024: Three papers are accepted at CoRL 2024, <a href="https://equidiff.github.io/">Equivariant Diffusion Policy</a> is accepted as an oral presentation.</li>
  <li>09/2024: I had a great time visiting the UPenn GRASP lab and presenting at the GRASP SFI seminar. Recording of my talk: <a href="https://www.youtube.com/watch?v=dJG83-6CZMY">link</a>.</li>
  <li>07/2024: We are organizing the <a href="https://sites.google.com/view/gas-rl-rss2024">Workshop on Geometric and Algebraic Structure in Robot Learning</a> at RSS 2024.</li>
  <li>07/2024: Blogpost in GRAM Workshop @ ICML 2024: <a href="https://gram-blogposts.github.io/blog/2024/extrinsic/">Correct, Incorrect and Extrinsic Equivariance</a>.</li>
  <li>06/2024: I am proud to be part of the <a href="https://www.youtube.com/watch?v=B9g2yhHs5Wg">Khoury Story</a>!</li>
  <li>04/2024: I will be returning to the Boston Dynamics AI Institute as a summer intern.</li>
  <li>09/2023: Our paper <a href="https://arxiv.org/pdf/2303.04745.pdf">A General Theory of Correct, Incorrect, and Extrinsic Equivariance</a> is accepted at NeurIPS 2023.</li>
  <li>07/2023: Recording of our <a href="https://sites.google.com/view/rss23-sym">Workshop on Symmetries in Robot Learning</a> is available <a href="https://www.youtube.com/watch?v=E2l16T0biu4">here</a>.</li>
  <li>06/2023: I am honored to receive the <a href="https://www.jpmorgan.com/technology/artificial-intelligence/research-awards/phd-fellowship-2023">2023 JP Morgan Chase PhD Fellowship</a>!</li>
  <li>04/2023: I give a guest lecture, <a href="https://www.youtube.com/watch?v=dx5rDtdv7LM">Equivariant Learning for Robotic Manipulation</a>. The lecture summarizes our latest research, so be sure to check it out!</li>
  <li>03/2023: We are organizing the <a href="https://sites.google.com/view/rss23-sym">Workshop on Symmetries in Robot Learning</a> at RSS 2023.</li>
  <li>02/2023: I will be joining the Boston Dynamics AI Institute as a summer intern.</li>
  <li>01/2023: Our paper <a href="https://arxiv.org/pdf/2211.09231.pdf">The Surprising Effectiveness of Equivariant Models in Domains with Latent Symmetry</a> is accepted at ICLR 2023 as a spotlight presentation.</li>
  <li>01/2023: Two papers are accepted at ICRA 2023.</li>
</ul>
<a id="more" href="javascript:void(0)">more ▾</a>

## Publications

For publications, see the [my lab’s research page](https://um-ei.github.io/research/).

<!-- ## Service
**Organizer:** RSS2023 Workshop on Symmetries in Robot Learning; RSS 2024 Workshop on Geometric and Algebraic Structure in Robot Learning  
**Reviewer:** Science Robotics 2025. Pattern Recognition 2025. RSS 2025. IJRR 2024. ICML 2024. ICLR 2023-2025. NeurIPS 2023, 2025. ICRA 2019, 2022-2024. CoRL 2022-2025. IROS 2021, 2023, 2025. RAL 2022-2025. T-RO 2022.

## Education
+ (2020-2025) Ph.D., Computer Science, Northeastern University, Boston, USA
+ (2017-2019) M.S, Computer Science, Northeastern University, Boston, USA
+ (2013-2017) B.Eng, Computer Science & Technology, Sichuan University, Chengdu, China -->
