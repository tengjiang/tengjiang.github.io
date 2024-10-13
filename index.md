---
layout: default
---
<h2 class="flappy">
<img src="/assets/img/flappy_default.png" alt="flappy" style="width: 28px; height: 28px;">  
About Me
</h2>

<!--
<a href="#publications">Go to Publications</a>
<a href="#news">Go to News</a>


<a href="#publications">Go to Publications</a>
<a href="#publications">Go to Publications</a>

```
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```
-->


I’m Teng, a Master of Science in Computer Science student at Columbia University, working my way to becoming a savvy **system programmer**, **hacker**, and **researcher**!

My research interests revolve around modern **operating systems**. Currently, I’m looking into how advancements across the software and hardware stack can enhance the performance, reliability, and environmental sustainability of established technologies such as virtualization and memory management. Some of my ongoing projects are:

* **Scheduling for over-subscribed virtual CPUs** (vCPUs) at a microsecond time scale.
* **Custom page fault handling with eBPF** for use cases like VM migration and memory management. See <a href="#publications">publication</a>.
* **Formal verification** of an open-source Rust library developed by Cloudflare: [mmap-sync](https://github.com/cloudflare/mmap-sync).
<!-- Keywords: Operating Systems, Virtualization, eBPF, Scheduling, FPGA, Programmable Networks, smartNICs -->

I mostly go by Teng, occasionally by Sebastian, a name not of my heritage but somehow I feel connected to (See [Why Sebastian?](/why-sebastian)). See my life outside of work [here](/fun-life).
<!--I am a die-hard fan of Beyoncé and and have seen her performing live for [5 times](http://iris.usc.edu/people/nevatia/) in 2023.-->

❗️❗️❗️ **I'm looking for PhD opportunities in computer systems starting in Fall 2025. Feel free to get in touch if you know of any!** ❗️❗️❗️

<br>

<h2 class="fire" id="news">
<img src="/assets/img/flappy_default.png" alt="flappy" style="width: 28px; height: 28px;">
News & Updates
</h2>
<div class="updates-container">
  <div class="updates">
    <p><b>10/05/2024:</b> I'll be at SOSP 2024—see you all there! 🤠 </p>
    <p><b>08/03/2024:</b> At SIGCOMM'24 presenting our work on custom page fault handling. </p>
    <p><b>06/13/2024:</b> Our vision paper <i><b>Custom Page Fault Handling With eBPF</b></i> was accepted to eBPF'24! </p>
    <p><b>01/11/2024:</b> I started my master’s degree in Computer Science at Columbia University! </p>
    <!-- Add more updates as needed -->
  </div>
</div>

<br>

{% include_relative _includes/publications.md %}

<br>

<h2 class="flappy" id="news">
<img src="/assets/img/flappy_default.png" alt="flappy" style="width: 28px; height: 28px;">
Education
</h2>

<div align="left">
        <strong> Columbia University, New York, NY (Aug 2022 - May 2025) </strong>
        <a href="https://cs.columbia.edu/" target="_blank" rel="external">
            <img src="/assets/img/columbia_new.png" style="float: right; margin-top: -10px; margin-left: 0px;" width="70" height="70">
        </a>
        <ul>
        <li>
          Master of Science, Computer Science</li>
        <li>
          Advisor: <a href="https://www.asafcidon.com/">Prof. Asaf Cidon</a> and <a href="https://www.cs.columbia.edu/~kkaffes/index.html">Prof. Kostis Kaffes</a></li>
      </ul>      
      </div>

<div align="left">
        <strong> Peking University, Beijing, China (Aug 2018 - Jun 2022) </strong>
          <a href="https://english.pku.edu.cn" target="_blank" rel="external">
            <img border="0" src="/assets/img/PKU_icon.png" align="right" width="70" height="70">
          </a> 
        <ul>
        <li>
          Bachelor of Science, Computer Engineering </li>
        <li>
          Graduated Magna Cum Laude</li>
      </ul>      
      </div>
<br>

<h2 class="fire" id="professional">
<img src="/assets/img/flappy_default.png" alt="flappy" style="width: 28px; height: 28px;">
Profession Experience
</h2>

<div align="left">
        <strong> Amazon, Seattle, WA (May 2023 - Aug 2023) </strong>
        <a href="https://amazon.com/" target="_blank" rel="external">
            <img src="/assets/img/amazon.png" style="float: right; margin-top: -10px; margin-left: 0px;" width="70" height="70">
        </a>
        <ul>
        <li>
          I worked as a software development intern at Amazon Fulfillment Technology during the summer of 2023. I migrated the existing storage bin validation service from internal frameworks to Native AWS. 
</li>
      </ul>      
      </div>

<div align="left">
        <strong> Tesla, Beijing, China (May 2022 - August 2022) </strong>
          <a href="https://tesla.com" target="_blank" rel="external">
            <img border="0" src="/assets/img/tesla.svg" align="right" width="70" height="70">
          </a> 

        <ul>
        <li>
        My work at Tesla's Roadside Service team during summer 2022 could be divided into two parts:
          Log data analysis, visualization, error forecast and prevention with Splunk; Microservice decoupling with RabbitMQ.</li>

      </ul>      
      </div>

<br>

{% include_relative _includes/projects.md %}

<br>

<h2 class="flappy" id="teaching">
<img src="/assets/img/flappy_default.png" alt="flappy" style="width: 28px; height: 28px;">
Teaching Experience
</h2>
* I am the TA for **EECS 6891: Extensible Operating Systems**, and I've designed **[homework on process off-cpu tracing](/assets/pdf/EECS6891_fa24_homework.pdf)**, inspired by Brendan Gregg's [post](https://www.brendangregg.com/offcpuanalysis.html) on off-cpu analysis. **[Recording](https://youtu.be/Z5wciVIjRV4)** on Youtube of the eBPF crash course I gave.
* TA for **COMS 4111 Introduction to Databases** (Fall 2023) and **COMS 6111 Advanced Database Systems** (Spring 2023).

<br>

<h2 class="fire" id="involvement">
<img src="/assets/img/flappy_default.png" alt="flappy" style="width: 28px; height: 28px;">
Involvement
</h2>
* Columbia University [Cyber Security Club](https://cucyber.cs.columbia.edu/)
* Columbia Engineering [qSTEM](https://egsc.engineering.columbia.edu/content/qstem-club).

<br>

<small>Design and source code modified from <a href="https://jiyanggao.github.io/" target="_blank">Jiyang Gao's website</a>. Edit <a href="https://github.com/jiyanggao/jiyanggao.github.io" target="_blank">here</a>. Also borrowed layout for publications from <a href="https://github.com/yaoyao-liu/minimal-light" target="_blank">minimal-light</a>.</small>