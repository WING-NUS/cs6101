---
permalink: /
title: "WING.NUS Large Language Models"
author_profile: true
redirect_from:
  - /about/
  - /about.html
header:
  overlay_image: ricardo-gomez-angel-9AdeEdYB2yk-unsplash.jpg
  overlay_filter: rgba(2, 115, 94, 0.5)
  caption: "Photo credit: Ricardo Gomez Angel @ [**Unsplash**](https://unsplash.com/@rgaleriacom)"
---
WING.NUS's CS6101 lab section will be conducted as a public course, with class participants nominating themselves and presenting the materials and leading the discussion.  In Semester I of AY2023/2024, we will focus on the topics of 

**Large Language Models (LLMs)**.  

This course is based on materials from Percy Liang, Tatsunori Hashimoto and Christopher Ré's [CS324 Large Language Models](https://stanford-cs324.github.io/winter2022/) course at Stanford; Danqi Chen's [COS 597G Understanding Large Language Models](https://www.cs.princeton.edu/courses/archive/fall22/cos597G/) course at Princeton; and Ryan Cotterell's [Large Language Models](https://rycolab.io/classes/llm-s23/) course at ETH.  All three sets of instructors have given their explicit permission to allow us to re-use and build upon their fantastic resources.  There will be 14 reading sessions, which will be held from 16:00 pm to 18:00 pm on Fridays. On alternate Thursdays, 13:00-15:00 pm, we will have project consultation sessions. 

Click on **Details** to see how to participate in the course.

**Discussion Group**. <a href="http://cs6101.slack.com/">A mandatory discussion group is on Slack</a>. Students and guests, please login when you are free. If you have a @comp.nus.edu.sg, @u.nus.edu, @nus.edu.sg, @a-star.edu.sg, @dsi.a-star.edu.sg or @i2r.a-star.edu.sg. email address you can create your Slack account for the group discussion without needing an invite.

If you need an invite to the Slack group.  The Slack group is being reused from previous semesters.  Once you are in the Slack group, you can consider yourself registered for the group.

It is not a lecture-oriented course and not as in-depth as the original source courses we are drawing from (with explicit permission).  Hence, our course is not a replacement, but rather a class to spur local interest in the topics of large language models.

Please see the detailed schedule in the table.

## Schedule  {#schedule}

The sessions will be broadcast live via the customized Zoom link as advertised on the [Slack group](http://cs6101.slack.com).  For semi-privacy reasons, the group meeting ID and access is not publicly disseminated here on the webpage.

**The schedule below is preliminary (last updated 18 Jul 2023.)** We may make slight changes on the allocation for topics and provide alternative suggestions for papers.

<table class="table table-striped">
<thead class="thead-inverse"><tr><th>Date</th><th width="80%">Description</th></tr></thead>
<tbody>
<!-- Support Staff ********************************** 
  Use this first row as an exemplar.  You can get the Youtube offsets for each segment by using the share button and checking the "start at" checkbox and then pasting it.  The t parameter is the number of second from the start of the video.
 ************************************************** -->
<tr>
<!--
  <td><b>NUS Week XX</b><br />Fri, 22 Jan<br />
  </td>
  <td>
    <p>
      <strong>Topic</strong><br/>
      <iframe width="560" height="315" src="https://www.youtube.com/embed/Cw2hNnDcigc" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
    </p>
  <a href="https://wing-nus.github.io/cs6101/paper-ConvSys">Reading List for Surveys and Research Papers</a>
  <p>
    Lecturers: Lecturers<br/>
    Support Staff: Support
</p>
  <p>
    [&nbsp;<a href="http://bit.ly/cs6101-t2310-w00">Lecture Slides</a>&nbsp;]
    [&nbsp;<a href="http://bit.ly/cs6101-t2310-w00-scribe">Scribe Notes</a>&nbsp;]
    <br/></p> 
<P>Description:
<ul>
  <li>[&nbsp;<a href="https://www.youtube.com/watch?v=Cw2hNnDcigc&t=0s">00:00</a>&nbsp;] Start - CS6101 / DYC1401 administration, presented by Min-Yen Kan </li>
  <li>[&nbsp;<a href="https://www.youtube.com/watch?v=Cw2hNnDcigc&t=2160s">36:00</a>&nbsp;] Overview of Dialogue Systems, presented by Yisong Miao </li>
  <li>[&nbsp;<a href="https://www.youtube.com/watch?v=Cw2hNnDcigc&t=2711s">45:11</a>&nbsp;] Qin et al. (2020) "DCR-Net: A Deep Co-Interactive Relation Network for Joint Dialog Act
Recognition and Sentiment Classification". [&nbsp;<a href = "http://ir.hit.edu.cn/~car/papers/AAAI2020-Qin-dcrnet.pdf">PDF</a>&nbsp;] In AAAI'2020, presented by Min-Yen Kan </li>
  <li>[&nbsp;<a href="https://www.youtube.com/watch?v=Cw2hNnDcigc&t=5205s">1:26:45</a>&nbsp;] Rishabh Joshi, Vidhisha Balachandran, Shikhar Vashishth, Alan Black, Yulia Tsvetkov. "DialoGraph: Incorporating Interpretable Strategy-Graph Networks into Negotiation Dialogues" [&nbsp;<a href = "https://openreview.net/pdf?id=kDnal_bbb-E">PDF@OpenReview</a>&nbsp;], Accepted@ICLR '21, presented by Lin Xu </li>
  <li>[&nbsp;<a href="https://www.youtube.com/watch?v=Cw2hNnDcigc&t=7680s">2:08:00</a>&nbsp;] Li et al. (2020) "Don’t Say That! Making Inconsistent Dialogue Unlikely with Unlikelihood Training". [&nbsp;<a href = " https://www.aclweb.org/anthology/2020.acl-main.428/">PDF</a>&nbsp;] In ACL'2020, presented by Yuxi Xie </li> 
 </ul>
    </p>
  </td>
  -->
    <td><b>NUS Week 00</b><br />Fri, 11 Aug<br />
      <a href="http://nus.edu.sg/registrar/docs/info/calendar/ay2023-2024.pdf">NUS Calendar (PDF)</a>
    </td>
    <td>
      <p>
      <strong>Introduction</strong> and <strong>Orientation</strong><br/>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/seEv0xrt56c" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe> 
      </p>
          <p>
            Lecturers: Kan Min Yen, Michael Xie Qizhe<br/>
          </p>
          <p>
            [&nbsp;<a href="http://bit.ly/cs6101-t2310-w00">Lecture Slides</a>&nbsp;]
            <!-- [&nbsp;<a href="http://bit.ly/cs6101-t2310-w00-scribe">Scribe Notes</a>&nbsp;]  --> 
            <br/>
          </p> 
    </td>
  </tr>
  <tr>
    <td><b>NUS Week 01</b><br />Fri, 18 Aug<br />
    </td>
    <td>
      <p>
        <strong>What are Large Language Models?</strong><br/>
      </p>
    </td>
  </tr>
  <tr>
    <td>
      <b>NUS Week 02</b><br />Fri, 25 Aug<br />
    </td>
    <td>
      <p>
        <strong>Adaptation</strong><br/>
      </p>
    </td>
  </tr>
  <tr>
    <td><b>NUS Week 03</b><br />Fri, 1 Sep<br />
    </td>
    <td>
      <p>
        <strong>Prompting</strong> and <strong>Zero-shot Inference</strong><br/>
      </p>
    </td>
  </tr>
  <tr>
    <td><b>NUS Week 04</b><br />Fri, 8 Sep<br />
    </td>
    <td>
      <p>
        <strong>Representation Capacity</strong><br/>
      </p>
    </td>
  </tr>
  <tr>
    <td><b>NUS Week 05</b><br />Fri, 15 Sep<br />
    </td>
    <td>
      <p>
        <strong>Modeling</strong><br/>
      </p>
    </td>
  </tr>
  <tr>
    <td><b>NUS Week 06</b><br />Fri, 22 Sep<br />
    </td>
    <td>
      <p>
        <strong>Scaling Up</strong>, <strong>Training</strong> and <strong>Parallelism</strong><br/>
      </p>
    </td>
  </tr>
  <tr>
    <td><b>NUS Recess Week </b><br />Fri, 29 Sep<br />
    </td>
    <td>
      <p>
        <strong>Preliminary Project Reports</strong><br/>
      </p>
    </td>
  </tr>
  <tr>
    <td><b>NUS Week 07</b><br />Fri, 6 Oct<br />
    </td>
    <td>
      <p>
        <strong>Data</strong> and <strong>Knowledge</strong><br/>
      </p>
    </td>
  </tr>
  <tr>
    <td><b>NUS Week 08</b><br />Fri, 13 Oct<br />
    </td>
    <td>
      <p>
        <strong>Reasoning</strong><br/>
      </p>
    </td>
  </tr>
  <tr>
    <td><b>NUS Week 09</b><br />Fri, 20 Oct<br />
    </td>
    <td>
      <p>
        <strong>Transfer Learning</strong><br/>
      </p>
    </td>
  </tr>
  <tr>
    <td><b>NUS Week 10</b><br />Fri, 27 Oct<br />
    </td>
    <td>
      <p>
        <strong>Retrieval Based LLMs</strong><br/>
      </p>
    </td>
  </tr>
  <tr>
    <td><b>NUS Week 11</b><br />Fri, 3 Nov<br />
    </td>
    <td>
      <p>
        <strong>Multimodal LLMs</strong><br/>
      </p>
    </td>
  </tr>
  <tr>
    <td><b>NUS Week 12</b><br />Fri, 10 Nov<br />
    </td>
    <td>
      <p>
        <strong>Harms</strong><br/>
      </p>
    </td>
  </tr>
  <tr>
    <td><b>NUS Week 13</b><br />Fri, 17 Nov<br />
    </td>
    <td>
      <p>
        <strong>Privacy</strong> and <strong>Memorization</strong><br/>
      </p>
    </td>
  </tr>
</tbody></table>

## Organizers {#org}

This version of CS6101 is jointly run by [WING@NUS](http://wing.comp.nus.edu.sg/) and incoming faculty [Michael Qizhe Xie](https://www.michaelxie.com/)

The current organisation team includes following members (alphabetical order):

[Hengchang Hu](http://holdenhu.cn/), 
[Min-Yen Kan](https://www.comp.nus.edu.sg/~kanmy/), 
[Xinyuan Lu](https://www.linkedin.com/in/xinyuan-lu-34762585/?originalSubdomain=sg), 
[Yisong Miao](https://yisong.me/)
[Michael Qizhe Xie](https://www.michaelxie.com/)
