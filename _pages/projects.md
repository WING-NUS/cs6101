---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

Here we archive and cross link all of the past projects done by our first year Ph.D. students, undergraduate and external guests that take part in our reading group.  Generally, when students and participants outside of WING join the reading group they must also complete a related project touching on some part of the lecture topics.  These projects often get presented publicly in the forum of our School of Computing's Term Project Showcase (STePS).

## Projects from Semester 2020 (AY 20/21, Sem II) featured at <a href="https://uvents.nus.edu.sg/event/18th-steps">18th STePs</A>, held on 14 April 2021.

In AY20/21 Sem II, CS6101 was topically oriented on **[Conversational Recommendation Systems](https://uvents.nus.edu.sg/event/18th-steps/module/CS6101)**.  There were 26 students in 10 teams whose projects focused on recent research on the topics of Conversational Systems, Recommender Systems and their intersections.

<i class='fa fa-home'></i>

<style>
.image-cover-modal {
    display: flex;
    align-items: center;
    justify-content: center;
    opacity: 0;
    position: fixed;
    z-index: 30;
    left: 0;
    top: 0;
    width: 100%;
    height: 100%;
    overflow: auto;
    background-color: rgb(0,0,0);
    background-color: rgba(0,0,0,0.9);
    transition: opacity ease 0.3s;
    pointer-events: none;
}

.model-shown {
    pointer-events: all;
    opacity: 1;
}

.image-cover-modal-content {
    display: block;
    max-width: 80%;
    max-height: 80%;
}

#image-cover-caption {
    display: block;
    position: absolute;
    width: 100%;
    height: 3rem;
    bottom: 0;
    line-height: 3rem;
    text-align: center;
    color: #fff;
    background: rgba(255, 255, 255, 0.33);
}

@media only screen and (max-width: 45rem){
    .image-cover-modal-content {
        max-width: 100%;
        max-height: 100%;
    }
}
</style>

<scripts>
// Get the DOM
var modal = document.getElementById('image-cover-modal');
var modalImg = document.getElementById("image-cover-image");
var captionText = document.getElementById("image-cover-caption");
var span = document.getElementsByClassName("image-cover-close")[0];

// When the user clicks on <span> (x), close the modal
modal.onclick = function() {
    this.classList.remove("model-shown");
}

var i;
for (i = 0; i < document.images.length; i++) {

    // Get the image and insert it inside the modal - use its "alt" text as a caption
    var img = document.images[i];

    img.onclick = function(){
        modal.classList.add("model-shown");
        modalImg.src = this.src;
        captionText.innerHTML = this.alt;
    }
}
</scripts>

<!--Table Content-->
<table>
  <tbody>
    <!-- Team 07-->
    <tr id="row1">
      <td width="60%">
        <h1>
          🏆 1st place, Team 07: Extending Neural Collaborative Filtering
        </h1>
        <h2>📖 Abstract </h2>
        <p style="font-size:18px">Extending the Neural Collaborative Filtering Framework to improve model understanding and robustness. Using additional Convolutional layers, Pairwise Loss Function and Auxiliary Information Embedding to explore potential model improvements.<BR /></p>

        <h2>✍️ Description </h2>
        <p style="font-size:18px">In our project, we explore the potential extensions to the Neural Collaborative Filtering (NCF) Framework to improve model understanding and robustness. Using additional Convolutional layers, Pairwise Loss Function and Auxiliary Information Embedding, we experiment with the MovieLens-1M dataset to attain better model performance on Hit Rate and NDCG metrics while attempting to improve model understanding through auxiliary embeddings.<BR /></p>

        <h2>☀️ Team Member </h2>
        <ul style="font-size:18px">
          <li>Gabriel Loye, NUS SoC Undergraduate</li>
          <li>Clarence Ong, NUS SoC Undergraduate [&nbsp;<a href="https://www.linkedin.com/in/clarenceong97/?originalSubdomain=sg">LinkedIn</a>&nbsp;]</li>
          <li>Nham Quoc Hung, NUS SoC Undergraduate [&nbsp;<a href="https://www.linkedin.com/in/quoc-hung-nham/?originalSubdomain=sg">LinkedIn</a>&nbsp;]</li>
          <li>Sashankh CK, External Guest</li>
        </ul>

        <h2>📻 Media Links</h2>
        [&nbsp;<a href="https://github.com/gabrielloye/neural_collaborative_filtering" style="font-size:18px">Homepage</a>&nbsp;]
        [&nbsp;<a href="https://raw.githubusercontent.com/gabrielloye/neural_collaborative_filtering/master/assets/CS6101_Neural_Collaborative_Filtering_Poster.png" style="font-size:18px">Poster</a>&nbsp;]
      </td>
        
      <td width="40%">
          <div id="image-cover-modal" class="image-cover-modal">
  <img class="image-cover-modal-content" src="https://raw.githubusercontent.com/gabrielloye/neural_collaborative_filtering/master/assets/CS6101_Neural_Collaborative_Filtering_Poster.png"/>
  <div id="image-cover-caption"></div>
</div>

  <img class="image-cover-modal-content" src="https://raw.githubusercontent.com/gabrielloye/neural_collaborative_filtering/master/assets/CS6101_Neural_Collaborative_Filtering_Poster.png" width="400px"/>
      </td>

    </tr>
 <!-- Team 04-->
    <tr id="row2">
      <td width="60%">
        <h1>
          🥈 2nd place, Team 04: Causal Estimation for Conversational Recommender Systems
        </h1>
        <h2>📖 Abstract </h2>
        <p style="font-size:18px">In this project, we study popularity bias in Recommender System (RecSys), Conversational Recsys, and their interplays.<BR /></p>

        <h2>✍️ Description </h2>
        <p style="font-size:18px">We discover (1) conversation can significantly mitigate popularity bias for traditional RecSys; (2) Conversation RecSys suffers from popularity bias itself. We propose a method to mitigate popularity bias in Conversational RecSys. Please refer to our poster for technical details. Our experiment is still WIP, we will update on this github repo: https://github.com/YisongMiao/cs6101 <BR/></p>

        <h2>☀️ Team Member </h2>
        <ul style="font-size:18px">
          <li>Yisong Miao, NUS Postgraduate Student  [&nbsp;<a href="https://yisong.me/">Personal Website</a>&nbsp;]</li>
          <li>Chenxin Wang, NUS Postgraduate Student [&nbsp;<a href="https://www.linkedin.com/in/chengxin-wang-086304113/?originalSubdomain=sg">LinkedIn</a>&nbsp;]</li>
        </ul>

        <h2>📻 Media Links</h2>
        [&nbsp;<a href="https://github.com/YisongMiao/cs6101">Homepage</a>&nbsp;]
        [&nbsp;<a href="https://yisong.me/publications/CausalEst-Poster.jpeg">Poster</a>&nbsp;]
      </td>
      <td width="40%">
        <img src="https://yisong.me/publications/CausalEst-Poster.jpeg" alt="Poster">
      </td>

    </tr>
  </tbody>
</table>


<!-- Team 09-->
**🥉 3rd place, Team 09: Beyond IGMC**

📖 Abstract <BR/>
We extend the state-of-the-art Inductive Graph Matrix Completion recommender system by introducing Graph Normalization and Layer Aggregation variants, and explore the models' potent transfer learning capabilities.<BR/>

✍️ Description <BR/>
In this project, we investigate how recent advances in Graph Neural Network models can impact and even improve the ability of the state-of-the-art Inductive Graph Matrix Completion (IGMC) recommender system to predict ratings in the setting of only having ratings of each user-item interaction. We show this through measuring the baseline model performance against the extensions using the RMSE scoring. 

The IGMC is able to perform inductive matrix completion without any reliance on side-information. This allows the model to be highly applicable in many recommender system settings. It is also able to successfully transfer learning to other datasets with completely different recommender tasks and user bases.
We contribute 2 main extensions to the model, in particular: Graph-Normalisation and Layer Aggregation alternatives. We also extended the model visualisation and conducted meso-analysis on training examples with the greatest contributions to RMSE values. Furthermore, we explore the transfer learning capabilities of these inductive models, and benchmark the results against external datasets.<BR/>

☀️ Team Member <BR/>
- Stephen Tan, NUS SoC Undergraduate [&nbsp;<a href="https://www.linkedin.com/in/stephen-tan-hin-khai/?originalSubdomain=sg">LinkedIn</a>&nbsp;]
- Axel Lau Wei En, NUS SoC Undergraduate [&nbsp;<a href="https://www.linkedin.com/in/axel-lau/?originalSubdomain=sg">LinkedIn</a>&nbsp;]
- Joel Tan Wan Rong, NUS SoC Undergraduate [&nbsp;<a href="https://www.linkedin.com/in/joeltanwr/?originalSubdomain=sg">LinkedIn</a>&nbsp;]
- Wendi Ren, External Guest
- Chan Guan Hao, External Guest 

📻 Media Links<BR/> 
[&nbsp;<a href="https://linktr.ee/BeyondIGMC">Homepage</a>&nbsp;]
[&nbsp;<a href="https://www.youtube.com/watch?v=pEQxq7r-lgY">Video</a>&nbsp;]
[&nbsp;<a href="https://drive.google.com/file/d/1Hso_rqGMXnJsRt1V9QmLUUGgbO6OcvZI/view">Poster</a>&nbsp;]

<!-- Team 01-->
**Team 01: Explore Multiple Response Modalities of DialogWAE**

📖 Abstract <BR/>
This project is focusing on assessing and interpreting the GMM prior components in DialogWAE.<BR/>

✍️ Description <BR/>
Neural response generation is a typical task in NLP community. DialogWAE is a new approach for dialogue modeling and response generation, which achieves SOTA result on popular datasets. In this work, we focus on exploring the various modalities of the generated responses. To be specific, we propose to: 
•	Analyze how the number K of prior components influences the overall performance.
•	Explore what each prior component of the Gaussian mixture distribution captures when K > 3.<BR/>

☀️ Team Member <BR/>
- Liu Ruofan, NUS Postgraduate Student [&nbsp;<a href="https://www.linkedin.com/in/ruofanliu/?originalSubdomain=sg">LinkedIn</a>&nbsp;]
- Liu Hongfu, NUS Postgraduate Student 
- Liu Yong, NUS Postgraduate Student [&nbsp;<a href="https://www.linkedin.com/in/yong-liu-b1037513/?originalSubdomain=sg">LinkedIn</a>&nbsp;]
 
📻 Media Links<BR/> 
[&nbsp;<a href=" https://github.com/lindsey98/DialogWAE">Homepage</a>&nbsp;]
[&nbsp;<a href="https://postimg.cc/sQN3hscm">Poster</a>&nbsp;]

<!-- Team 02-->
**Team 02: FiBiNET**

📖 Abstract <BR/>
This project is focusing on combining feature importance and bilinear feature interaction for click-through rate prediction<BR/>

✍️ Description <BR/>
We explore potential extensions to one of the state-of-the-art recommender systems named FiBiNET which assigns importance to feature embeddings.
<BR/>

☀️ Team Member <BR/>
- Qiao Rui, NUS Postgraduate Student [&nbsp;<a href="https://www.linkedin.com/in/rui-qiao/?originalSubdomain=sg">LinkedIn</a>&nbsp;]
- Sng Weicong, NUS Postgraduate Student [&nbsp;<a href="https://www.linkedin.com/in/weicong-sng-42456ba8/?originalSubdomain=sg">LinkedIn</a>&nbsp;]
- Li Zihan, NUS Postgraduate Student [&nbsp;<a href="https://www.linkedin.com/in/zihan-li-nus/?originalSubdomain=sg">LinkedIn</a>&nbsp;]
 
📻 Media Links<BR/> 
[&nbsp;<a href="https://raw.githubusercontent.com/lizihan97/FiBiNET/main/FiBiNET.png">Poster</a>&nbsp;]

<!-- Team 03-->
**Team 03: Feedback-guided Preference Adaptation Network (FPAN)**

📖 Abstract <BR/>
Multi-round conversational recommender systems (CRS), which interact with users by asking questions about attributes and recommending items multiple times in one conversation.<BR/>

✍️ Description <BR/>
FPAN uses gating modules to adapt the user embedding and item-level feedback, according to attribute-level feedback. This project looks to improve the offline and online training of FPAN. It does this by conducting a survey into the effectiveness of GraphSAGE convolutions. And, by introducing a function to calculate user & item bias.<BR/>

☀️ Team Member <BR/>
- Henry Kasim, NUS Podtgraduate Student [&nbsp;<a href="https://www.linkedin.com/in/henrykasim/?originalSubdomain=sg">LinkedIn</a>&nbsp;]
- Samuel Broughton, NUS Podtgraduate Student 

📻 Media Links<BR/> 
[&nbsp;<a href="https://drive.google.com/file/d/1SoAqjjmq48rMtvpQvCt-Wne5dXmiXOkA/view">Poster</a>&nbsp;]

<!-- Team 05-->
**Team 05: Counterfactual Recommender**

📖 Abstract <BR/>
Relevance Matrix Factorization and Asymmetric Tri-training are employed to build a recommendation system. Its algorithm is evaluated by using Coat dataset to simulate a scenario that we have only “biased” observational data for model training while evaluating on “unbiased” data.<BR/>

✍️ Description <BR/>
Implicit feedback is easy to collect and can be useful to build a recommendation system in online service. However, the feedback suffered from popularity bias because a user gives feedback to an item only if it is exposed. To build an unbiased recommendation system, counterfactual learning and meta learning approaches are applied to deal with such observational data.<BR/>

☀️ Team Member <BR/>
- Aadit Rahul Kamat, NUS Undergraduate Student [&nbsp;<a href="https://www.linkedin.com/in/aaditkamat/?originalSubdomain=sg">LinkedIn</a>&nbsp;]
- Takanori Aoki, External Guest 

📻 Media Links<BR/> 
[&nbsp;<a href="https://drive.google.com/file/d/1nZ40KXyccOxUJRD53c0m2VcWtBiVWkBb/view">Poster</a>&nbsp;]

<!-- Team 06-->
**Team 06: Diversifying Dialogue Generation with Non-Conversational Text**

📖 Abstract <BR/>
Implementation for the paper Diversifying Dialogue Generation with Non-Conversational Text on English.<BR/>

✍️ Description <BR/>
Traditional neural network-based sequence-to-sequence (seq2seq) models strongly suffer from the low diversity problem when it comes to open domain dialogue generation. The authors aim to diversify the dialogue generation with non-conversational text corpus in Chinese language. We attempt to extend this work to conversational and non-conversational datasets in English Analysis on how filtering the non-conversational corpus based on topic affects the result (selected topics: Politics, Attitude & Emotion, Health).<BR/>

☀️ Team Member <BR/>
- Yeo Qi Xun, NUS Postgraduate Student [&nbsp;<a href="https://www.linkedin.com/in/yeo-qi-xun-8975a114b/?originalSubdomain=sg">LinkedIn</a>&nbsp;]
- Yuxi Xie, NUS Postgraduate Student [&nbsp;<a href="https://www.linkedin.com/in/yuxi-xie-494265181/">LinkedIn</a>&nbsp;]
- Tian Zhen, NUS Postgraduate Student

📻 Media Links<BR/> 
[&nbsp;<a href="https://github.com/YuxiXie/Diversifying-Dialogue-Generation-with-Non-Conversational-Text">Homepage</a>&nbsp;]
[&nbsp;<a href="https://www.youtube.com/watch?v=PWOr1ay1CNM">Video</a>&nbsp;]
[&nbsp;<a href="https://i.imgur.com/J3tzCR5.png">Poster</a>&nbsp;]

<!-- Team 08-->
**Team 08: NN for Ad Recommendation**

📖 Abstract <BR/>
The project extends the popular DeepFM neural network to better predict users' click-through-rate of advertisements.<BR/>

✍️ Description <BR/>
DeepFM is a popular click-through-rate (CTR) model developed by Huawei's Noah's Ark Lab. In this project, we modifies the original neural network structure for better CTR predictions. More specifically, we introduced pooling layers to better capture the higher order feature interactions and b. added a linear layer to assign weights to the constituent deep model and factorisation machine (FM) model when combining the outputs. Our experimental results show that both extensions are able to improve the accuracy of the original DeepFM model.<BR/>

☀️ Team Member <BR/>
- Muhammad Assyarul Ariffin Bin Omar, NUS Undergraduate Student [&nbsp;<a href="https://www.linkedin.com/in/muhd-assyarul-ariffin-bin-omar/?originalSubdomain=sg">LinkedIn</a>&nbsp;]
- Lee Xiong An, External Guest
- Xu Pengtai, External Guest

📻 Media Links<BR/> 
[&nbsp;<a href="https://i.ibb.co/vVzJdLq/WING-Poster-STe-PS-2021-6101-08.jpg">Poster</a>&nbsp;]

<!-- Team 10-->
**Team 10: KGRecSys**

📖 Abstract <BR/>
Implementation of the paper "KGAT: Knowledge Graph Attention Network for Recommendation".<BR/>

✍️ Description <BR/>
In this project, we implement the KGAT model as described in the paper "KGAT: Knowledge Graph Attention Network for Recommendation".<BR/>

☀️ Team Member <BR/>
- Evan Chong, External Guest
- Rabiul Awal, External Guest

📻 Media Links<BR/> 
[&nbsp;<a href="https://github.com/evantkchong/cs6101_kgrecsys">Homepage</a>&nbsp;]
[&nbsp;<a href="https://raw.githubusercontent.com/evantkchong/cs6101_kgrecsys/main/docs/KGRecSys_poster_STePS_2021.png">Poster</a>&nbsp;]





 
 




