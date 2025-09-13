---
permalink: /
title: "WING.NUS Retrieval Augmented Generation"
author_profile: true
redirect_from:
  - /about/
  - /about.html
header:
  overlay_image: 
  overlay_image: paul-buffington-Lwe2hbm5XKk-unsplash.jpg
  caption: "Photo credit: Paul Buffington @ [**Unsplash**](https://unsplash.com/@photobuffs)"
#  overlay_filter: rgba(2, 115, 94, 0.5)
---
WING.NUS's CS6101 lab section will be conducted as a public course, with class participants nominating themselves and presenting the materials and leading the discussion.  In Semester I of AY2025/2026, we will examine

## Retrieval Augmented Generation (RAG)

The physical class will take place at Seminar Room 31 (COM4 #03-01), at the School of Computing.

<!-- This course is based on materials from Percy Liang, Tatsunori Hashimoto and Christopher Ré's [CS324 Large Language Models](https://stanford-cs324.github.io/winter2022/) course at Stanford; Danqi Chen's [COS 597G Understanding Large Language Models](https://www.cs.princeton.edu/courses/archive/fall22/cos597G/) course at Princeton; and Ryan Cotterell's [Large Language Models](https://rycolab.io/classes/llm-s23/) course at ETH.  All three sets of instructors have given their explicit permission to allow us to re-use and build upon their fantastic resources.  There will be 14 reading sessions, which will be held from 16:00 pm to 18:00 pm on Fridays. On alternate Thursdays, 13:00-15:00 pm, we will have project consultation sessions. -->

Click on **Details** to see how to participate in the course.

**Discussion Group**. <a href="http://cs6101.slack.com/">A mandatory discussion group is on Slack</a>. Students and guests, please login when you are free. If you have a @comp.nus.edu.sg, @u.nus.edu, @nus.edu.sg, @a-star.edu.sg, @dsi.a-star.edu.sg or @i2r.a-star.edu.sg. email address you can create your Slack account for the group discussion without needing an invite.

If you need an invite to the Slack group.  The Slack group is being reused from previous semesters.  Once you are in the Slack group, you can consider yourself registered for the group.

It is not a lecture-oriented course and not as in-depth as the original sources we are drawing from.  Hence, our course is not a replacement, but rather a class to spur local interest in the topics of information retrieval and retrieval augmented generation.

Please see the detailed schedule in the table.

## Schedule  {#schedule}

The sessions will be broadcast live via the customized Zoom link as advertised on the [Slack group](http://cs6101.slack.com).  For privacy reasons, the group meeting ID and access is not publicly disseminated here on the webpage.

We may make slight changes on the allocation for topics and provide alternative suggestions for papers as we progress throughout the semester.

<table class="table table-striped">
<thead class="thead-inverse"><tr><th>Date</th><th width="80%">Description</th></tr></thead>
<tbody>
<!-- Support Staff **********************************
  Use this first row as an exemplar.  You can get the Youtube offsets for each segment by using the share button and checking the "start at" checkbox and then pasting it.  The t parameter is the number of second from the start of the video.
 ************************************************** -->
<tr>
  <th colspan=2><b>Introduction</b></th>
</tr>
<tr>
    <td><b>NUS Week 00</b><br />Thu, 7 Aug<br />
      <a href="http://nus.edu.sg/registrar/docs/info/calendar/ay2025-2026.pdf">NUS Calendar (PDF)</a>
    </td>
    <td>
      <p>
      <strong>Introduction and Orientation</strong><br/>
      <iframe width="560" height="315" src="https://www.youtube.com/embed/sshRKwol1B0" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
      </p>
          <p>
            Lecturers: Min [ <a href="http://www.comp.nus.edu.sg/~kanmy/">Website</a> ] <br/>

            Note: the RAG introduction part starts at 1h07m; the first part is on course logistics.

          </p>
          <p>
            [&nbsp;<a href="http://soc-n.us/cs6101-t2510-w00">Lecture Slides</a>&nbsp;]
            <!-- [&nbsp;<a href="http://bit.ly/cs6101-t2310-w00-scribe">Scribe Notes</a>&nbsp;]  -->
            <br/>
          </p>
    </td>
  </tr>

<tr>
    <td><b>NUS Week 01</b><br />Thu, 14 Aug<br />
    </td>
    <td>
      <p>
      <strong>RAG Overview</strong><br/>referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
      <iframe width="560" height="315" src="https://www.youtube.com/embed/eRm1HQnG_tc" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
      </p>
          <p>
            Lecturers: Min [ <a href="http://www.comp.nus.edu.sg/~kanmy/">Website</a> ] Haitao [ <a href="https://ii-research-yu.github.io/">Website</a> ]<br/>

            Note: Lecture starts at 24m19s.

            <ul>
              <li>Section 1: <a href="https://www.youtube.com/embed/eRm1HQnG_tc?start=1459">Definition & Preliminaries (Min)</a></li>
              <li>Section 2: <a href="https://www.youtube.com/embed/eRm1HQnG_tc?start=2339">Retrieval Orchestration (Haitao)</a></li>
              <li>Section 3: <a href="https://www.youtube.com/embed/eRm1HQnG_tc?start=6900">Optimization (Min)</a></li>
            </ul>

          </p>
          <p>
            [&nbsp;<a href="http://soc-n.us/cs6101-t2510-w01">Lecture Slides</a>&nbsp;]
            <!-- [&nbsp;<a href="http://bit.ly/cs6101-t2310-w00-scribe">Scribe Notes</a>&nbsp;]  -->
            <br/>
          </p>
    </td>
  </tr>

<tr>
  <th colspan=2><b>LLM Generation</b></th>
</tr>
  <tr>
    <td><b>NUS Week 02</b><br />Thu, 21 Aug<br />
    </td>
    <td>
      <p>
      <strong>Foundations of Large Language Models</strong><br/>
      <iframe width="560" height="315" src="https://www.youtube.com/embed/6BA8C2AcaBY" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
      </p>
          <p>
            Lecturers: Sahej [ <a href="https://www.linkedin.com/in/sahej-agarwal/">LinkedIn</a> | <a href="https://www.github.com/SahejAgarwal05">Github</a> ] Chuen Yang [ <a href="https://www.linkedin.com/in/chuen-yang-beh-27545b201/">LinkedIn</a> ] Benjamin [ <a href="https://www.linkedin.com/in/benjamin-chek">LinkedIn</a> ]<br/>
            Ervin [ <a href="https://www.linkedin.com/in/ervinteo/">LinkedIn</a> ] Jiaying [<a href="https://www.linkedin.com/in/jiayingwu19/">LinkedIn</a> ] Yajing [<a href="https://www.linkedin.com/in/yajing-yang-737629140/">LinkedIn</a> ]<br/>
          
          Note: Lecture starts at 12m46s.
          
           <ul>
              <li> <a href="https://www.youtube.com/embed/6BA8C2AcaBY?start=0">Kahoot from W01 (Min)</a></li>
              <li> Lecture Starts - Section 1:<a href="https://www.youtube.com/embed/6BA8C2AcaBY?start=766">Overview of LLMs (Beh Chuen Yang)</a></li>
              <li> Section 2: <a href="https://www.youtube.com/embed/6BA8C2AcaBY?start=2610">Bottlenecks of LLMs - Bottleneck 1: Prevalence of factual errors (Ervin Teo)</a></li>
              <li> Bottleneck 2: <a href="https://www.youtube.com/embed/6BA8C2AcaBY?start=3500">Difficulty of verification (Yajing Yang)</a></li>
              <li> Bottleneck 4: <a href="https://www.youtube.com/embed/6BA8C2AcaBY?start=4112">Computationally expensive adaptation costs (Sahej Agarwal)</a></li>
              <li> Bottleneck 3: <a href="https://www.youtube.com/embed/6BA8C2AcaBY?start=4829">Difficulty of data opt-out (Jiaying Wu)</a></li>
              <li> Bottleneck 5: <a href="https://www.youtube.com/embed/6BA8C2AcaBY?start=5455">Prohibitively large model size (Benjamin Chek)</a></li>
              <li> Section 3: <a href="https://www.youtube.com/embed/6BA8C2AcaBY?start=5796">Key Takeaways (Jiaying Wu)</a></li>
              <li> Lecture End - <a href="https://www.youtube.com/embed/6BA8C2AcaBY?start=6168">Discussion and Logistics</a></li>
              </ul>
          </p>
          <p>
            [&nbsp;<a href="http://soc-n.us/cs6101-t2510-w02">Lecture Slides</a>&nbsp;]
            <!-- [&nbsp;<a href="http://bit.ly/cs6101-t2310-w00-scribe">Scribe Notes</a>&nbsp;]  -->
            <br/>
          </p>
    </td>
  </tr>

  <tr>
    <td><b>NUS Week 03</b><br />Thu, 28 Aug<br />
    </td>
    <td>
      <p>
      <strong>LLM Prompting</strong><br/>
      <iframe width="560" height="315" src="https://www.youtube.com/embed/NO4Q3ghfYKU" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
      </p>
          <p>
            Lecturers: Sahajpreet Singh [ <a href="https://www.linkedin.com/in/sahajpreet-singh">LinkedIn</a> | <a href="https://x.com/Phy_Shro">Twitter</a> ] Ng Xuan Hern [ <a href="http://www.linkedin.com/in/ngxuanhern">LinkedIn</a> ] Aaron Toh [ <a href="https://www.linkedin.com/in/aaron-toh">LinkedIn</a> ] Yong Ee [ <a href="https://www.linkedin.com/in/yongee">LinkedIn</a> ] Shweta Patel [ <a href="https://wing-nus.github.io/cs6101">LinkedIn</a> ]<br/>

            Note: Lecture starts at 14m40s.

            <ul>
              <li>Section 1: <a href="https://www.youtube.com/embed/NO4Q3ghfYKU?start=880">Basics of Prompting (Sahajpreet Singh)</a></li>
              <li>Section 2: <a href="https://www.youtube.com/embed/NO4Q3ghfYKU?start=1990">Prompt Sensitivity (Ng Xuan Hern)</a></li>
              <li>Section 3: <a href="https://www.youtube.com/embed/NO4Q3ghfYKU?start=2980">Hallucinations & Factual Errors (Aaron Toh)</a></li>
              <li>Section 4: <a href="https://www.youtube.com/embed/NO4Q3ghfYKU?start=4050">Jailbreaking & Privacy Concerns (Yong Ee)</a></li>
              <li>Section 5: <a href="https://www.youtube.com/embed/NO4Q3ghfYKU?start=5540">LLM Blender (Shweta Patel)</a></li>
            </ul>

          </p>
          <p>
            [&nbsp;<a href="http://soc-n.us/cs6101-t2510-w03">Lecture Slides</a>&nbsp;]
            <!-- [&nbsp;<a href="http://bit.ly/cs6101-t2310-w00-scribe">Scribe Notes</a>&nbsp;]  -->
            <br/>
          </p>
    </td>
  </tr>

  <tr>
    <td><b>NUS Week 04</b><br />Thu, 4 Sep<br />
    </td>
    <td>
      <p>
      <strong>Vector Stores</strong><br/>
      <iframe width="560" height="315" src="https://www.youtube.com/embed/GFQd2of7ZNY" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
      </p>
          <p>
            Lecturers: Barid Xi Ai [ <a href="https://baridxiai.github.io">Website</a> ] Frederick Amal Emerson [ <a href="about:blank">Website</a>] Lin Hong Yi [ <a href="https://www.hongyiii.dev/">Website</a> | <a href=" https://www.linkedin.com/in/hong-yiii/">LinkedIn</a>] Benn Tan [ <a href="https://findbenn.com">Website</a> | <a href="https://linkedin.com/in/benntan">LinkedIn</a>] Choong Kai Zhe [<a href="https://linkedin.com/in/choongkaizhe">LinkedIn</a>] Miao Yisong [ <a href="https://yisong.me/">Website</a> | <a href="https://x.com/YisongMiao">X</a> ] Lee Kwan Tze [<a href="https://www.linkedin.com/in/leekwantze/">LinkedIn</a>] <br/>
            
          Note: Lecture starts at 14m20s.
          
           <ul>
              <li> <a href="https://www.youtube.com/embed/6BA8C2AcaBY?start=0">Kahoot from W03 (Erwin)</a></li>
              <li> Lecture Starts - Section 1: <a href="https://youtu.be/GFQd2of7ZNY?t=860">Introduction to Vector Stores for RAG (Barid Xi Ai)</a></li>
              <li> Section 2: <a href="https://youtu.be/GFQd2of7ZNY?t=1518">Popular Vector Storage Techniques (Frederick Amal Emerson)</a></li>
              <li> Section 3a: <a href="https://youtu.be/GFQd2of7ZNY?t=2543">Vector Retrieval: Quantization-Based (Lin Hong Yi)</a></li>
              <li> Section 3b: <a href="https://youtu.be/GFQd2of7ZNY?t=3795">Vector Retrieval: Graph-Based (Benn Tan)</a></li>
              <li> Section 4a: <a href="https://youtu.be/GFQd2of7ZNY?t=5404">RAG-related Challenges and Optimisations for Vector Storage: Speed \& Latency (Choong Kai Zhe)</a></li>
              <li> Section 4b: <a href="https://youtu.be/GFQd2of7ZNY?t=6394">RAG-related challenges and optimisation for Vector Storage (Miao Yisong)</a></li>
              <li> Lecture End - Section 5: <a href="https://youtu.be/GFQd2of7ZNY?t=7277">Commercial / Open-source frameworks for RAG for Vector Stores (Lee Kwan Tze)</a></li>
            </ul>
          </p>
          <p>
            [&nbsp;<a href="http://soc-n.us/cs6101-t2510-w04">Lecture Slides</a>&nbsp;]
            <!-- [&nbsp;<a href="http://bit.ly/cs6101-t2310-w00-scribe">Scribe Notes</a>&nbsp;]  -->
            <br/>
          </p>
    </td>
  </tr>

  <tr>
    <td><b>NUS Week 05</b><br />Thu, 11 Sep<br />
    </td>
    <td>
      <p>
      <strong>Training: Fine Tuning, In Context Learning and Model Scaling</strong><br/>
      <iframe width="560" height="315" src="https://www.youtube.com/embed/Xd3LZvhzofs?si=_BGCp7wYW608Q5dn"  frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
      </p>
          <p>
            Lecturers: Takanori Aoki [ <a href="https://www.linkedin.com/in/takanori-aoki-7900a438">LinkedIn</a> ] Vangmay Sachan [ <a href="https://vangmay.github.io/">Website</a> ] Zihang Fu [ <a href="https://wing.comp.nus.edu.sg/author/zihang-fu/">Website</a> ] Hongxu Liu, Benjamin Goh [ <a href="https://www.linkedin.com/in/benjamin-goh-45a0a7307">LinkedIn</a> ]<br/>

          <ul>
            <li>Section 1: <a href="https://www.youtube.com/embed/Xd3LZvhzofs?si=U-fGAEdf4FYzIKod&amp;start=40">Intro to SFT, ICL, Scaling and Scaling Laws (Vangmay)</a></li>
            <li>Section 2: <a href="https://www.youtube.com/embed/Xd3LZvhzofs?si=Sh6A1oPCnYv5kiZX&amp;start=406">Supervised fine-tuning (SFT) (Vangmay)</a></li>
            <li>Section 3A: <a href="https://www.youtube.com/embed/Xd3LZvhzofs?si=nghRCZPuKESC0-Ly&amp;start=1662">In-context learning (ICL) (Zihang)</a></li>
            <li>Section 3B: <a href="https://www.youtube.com/embed/Xd3LZvhzofs?si=BsTydcWIiKBiu0ev&amp;start=2990">Mechanistic Interpretability (Hongxu)</a></li>
            <li>Section 4: <a href="https://www.youtube.com/embed/Xd3LZvhzofs?si=jCEZ36PShvunxGw7&amp;start=6083">Model Scaling (Takanori)</a></li>
          </ul>

          </p>
          <p>
            [&nbsp;<a href="http://soc-n.us/cs6101-t2510-w05">Lecture Slides</a>&nbsp;]
            <!-- [&nbsp;<a href="http://bit.ly/cs6101-t2310-w00-scribe">Scribe Notes</a>&nbsp;]  -->
            <br/>
          </p>
    </td>
  </tr>

<tr>
  <th colspan=2><b>Retrieval and Augmentation</b></th>
</tr>
  <tr>
    <td><b>NUS Week 06</b><br />Thu, 18 Sep<br />
    </td>
    <td>
      <p>
      <strong>Retrieval and Re-ranking Models</strong><br/>
      Video link. 
      </p>
          <p>
            Lecturers: <br/>
          </p>
          <p>
            [&nbsp;<a href="http://example.com">Lecture Slides</a>&nbsp;]
            <!-- [&nbsp;<a href="http://bit.ly/cs6101-t2310-w00-scribe">Scribe Notes</a>&nbsp;]  -->
            <br/>
          </p>
    </td>
  </tr>

  <tr>
    <td><b>NUS Week 07</b><br />Thu, 2 Oct<br />
    </td>
    <td>
      <p>
      <strong>RAG Models</strong><br/>
      i.e., REALM, FID.  

      Video link. 
      </p>
          <p>
            Lecturers: <br/>
          </p>
          <p>
            [&nbsp;<a href="http://example.com">Lecture Slides</a>&nbsp;]
            <!-- [&nbsp;<a href="http://bit.ly/cs6101-t2310-w00-scribe">Scribe Notes</a>&nbsp;]  -->
            <br/>
          </p>
    </td>
  </tr>

  <tr>
    <td><b>NUS Week 08</b><br />Thu, 9 Oct<br />
    </td>
    <td>
      <p>
      <strong>Document Representation</strong><br/>
      What to Retrieve.  Chunking.

      Video link. 
      </p>
          <p>
            Lecturers: <br/>
          </p>
          <p>
            [&nbsp;<a href="http://example.com">Lecture Slides</a>&nbsp;]
            <!-- [&nbsp;<a href="http://bit.ly/cs6101-t2310-w00-scribe">Scribe Notes</a>&nbsp;]  -->
            <br/>
          </p>
    </td>
  </tr>

  <tr>
    <td><b>NUS Week 09</b><br />Thu, 16 Oct<br />
    </td>
    <td>
      <p>
      <strong>Bootstrapping and Iterative Retrieval</strong><br/>
      Relevance Feedback / Rocchio.

      Video link. 
      </p>
          <p>
            Lecturers: <br/>
          </p>
          <p>
            [&nbsp;<a href="http://example.com">Lecture Slides</a>&nbsp;]
            <!-- [&nbsp;<a href="http://bit.ly/cs6101-t2310-w00-scribe">Scribe Notes</a>&nbsp;]  -->
            <br/>
          </p>
    </td>
  </tr>

<tr>
  <th colspan=2><b>Advanced RAG</b></th>
</tr>
  <tr>
    <td><b>NUS Week 10</b><br />Thu, 23 Oct<br />
    </td>
    <td>
      <p>
      <strong>Multimodal RAG</strong><br/>
      Video link. 
      </p>
          <p>
            Lecturers: <br/>
          </p>
          <p>
            [&nbsp;<a href="http://example.com">Lecture Slides</a>&nbsp;]
            <!-- [&nbsp;<a href="http://bit.ly/cs6101-t2310-w00-scribe">Scribe Notes</a>&nbsp;]  -->
            <br/>
          </p>
    </td>
  </tr>

  <tr>
    <td><b>NUS Week 11</b><br />Thu, 30 Oct<br />
    </td>
    <td>
      <p>
      <strong>Graph RAG</strong><br/>
      Video link. 
      </p>
          <p>
            Lecturers: <br/>
          </p>
          <p>
            [&nbsp;<a href="http://example.com">Lecture Slides</a>&nbsp;]
            <!-- [&nbsp;<a href="http://bit.ly/cs6101-t2310-w00-scribe">Scribe Notes</a>&nbsp;]  -->
            <br/>
          </p>
    </td>
  </tr>

  <tr>
    <td><b>NUS Week 12</b><br />Thu, 6 Nov<br />
    </td>
    <td>
      <p>
      <strong>Source Credibility Assessment</strong><br/>
      Video link. 
      </p>
          <p>
            Lecturers: <br/>
          </p>
          <p>
            [&nbsp;<a href="http://example.com">Lecture Slides</a>&nbsp;]
            <!-- [&nbsp;<a href="http://bit.ly/cs6101-t2310-w00-scribe">Scribe Notes</a>&nbsp;]  -->
            <br/>
          </p>
    </td>
  </tr>

  <tr>
    <td><b>NUS Week 13</b><br />Thu, 13 Nov<br />
    </td>
    <td>
      <p>
      <strong>RAG Efficiency</strong><br/>
      Speculative RAG.  Long Context Problems (Lost in the Middle).

      Video link. 
      </p>
          <p>
            Lecturers: <br/>
          </p>
          <p>
            [&nbsp;<a href="http://example.com">Lecture Slides</a>&nbsp;]
            <!-- [&nbsp;<a href="http://bit.ly/cs6101-t2310-w00-scribe">Scribe Notes</a>&nbsp;]  -->
            <br/>
          </p>
    </td>
  </tr>

</tbody></table>




## Organizers {#org}

This version of CS6101 is jointly run by [WING@NUS](http://wing.comp.nus.edu.sg/) and sabbatical visitor [Haitao Yu](https://ii-research-yu.github.io/) (University of Tsukuba)

The current organisation team includes following members (alphabetical order):

[Min-Yen Kan](https://www.comp.nus.edu.sg/~kanmy/),
[Yisong Miao](https://yisong.me/), and 
[Haitao Yu](https://ii-research-yu.github.io/)