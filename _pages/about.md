---
permalink: /
#layout: archive
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class="small_font">I am working as a Research Fellow at the CVIT lab of IIIT-H under the supervision of <a target="_blank" href="https://faculty.iiit.ac.in/~jawahar/">Prof. CV Jawahar</a> and <a target="_blank" href="https://vinaypn.github.io/">Prof. Vinay Namboodiri</a>. I also as a visiting research at the LTRC lab between 2019 and 2020. I was advised by <a target="_blank" href="https://www.iiit.ac.in/people/faculty/anilvuppala/">Prof. Anil Kumar Vuppala</a>.</span>

<span class="small_font">I used to work as a Data Scientist at Microsoft Research & Development - Hyderabad. I developed intelligent features on the world's biggest enterprise facing email client - Outlook. These features increase the productivity of our users and reduce their time to task completion. These features are used by more than 100 million users per month, my hunch is that you might have seen some of them! <img class="tiny-emoji" with="18px" src="images/grin.svg">
</span>

<div id="ex_mic"> 
	<div class="main_img_d"><img class="main_p_img" id="sugg_att" src="images/sugg_att.jpeg"><div>Suggested Attachments (Outlook)</div></div>
	<div class="main_img_d"><img class="main_p_img" id="meet_in" src="images/meet_in.jpeg"><div>Meeting Insights (Outlook)</div></div>
</div>
<br>

<span class="small_font">I am primarily interested in developing deep learning models to accentuate a human's visual, auditory, and interactive experiences. I think this can be achieved by training the models to use multimodal environmental cues (video, sound, interaction, etc.) to improve their own understanding of the environment and generate novel content inspired by the environment across different modalities. In this pursuit, I am exploring the areas of audio-visual generative modeling, complex scene understanding, and human intent forecasting. My primary motivation is aiding the space of AR/VR. I think these multimodal generative models can improve the content generation in AR/VR. </span>

<span class="small_font"> My favorite language is Python, merely because it is so simple, yet elegant and powerful! You can find a sample of my code <a target="_blank" href="https://github.com/bipashasen/CTC-Transformer-Spech-Recognition/blob/master/run.py">here</a>. Below I have listed some of my major projects I've undertaken in the past few years. </span>

<span class="small_font">PS. I am a musician, I sing and play guitar. I have toured and performed at several places with my previous band, <a target="_blank" href="https://www.facebook.com/AndroMetaBand">Andrometa</a>. I also tried my hands out travel vlogging and YouTubing! Find them <a target="_blank" href="https://www.youtube.com/channel/UCU1TMnEt0J1UJZfMW1Gixgg?view_as=subscriber" target="_blank">here!</a></span>


# Major Projects

## BReQS: Self-Supervised Meeting Summarization

**Self-Supervision, Natural Language Processing, Deep Learning**, Ongoing

<span class="research-img">
	<img width="500" src="/images/aut_gan.png">
	<span id="img_cit">*cited from <i>`Adversarial Text Generation Without Reinforcement Learning'.</i></span>
</span>

<span class="research-text">
A self-supervised framework to generate summary of long meetings with multiple participants and speakers. The model is called BReQS, which stands for <b>B</b>revity, <b>Re</b>levance, <b>Q</b>uality and <b>S</b>pan. I'm using the four metrics as a measure to train the model. <b>B</b>revity keeps summary concise which is achieved by using an Autoencoder to compress the meeting transcript into a short latent space. The Autoencoder is trained using the reconstruction loss. <b>Re</b>levance is a measure of information loss. To obtain the training data for relevance, I exploited an interesting meeting property. In a meeting, a continuous utterance by a single speaker barring pauses and short interruptions by the participants can be considered as a single context. These short interruptions are predominantly queries to the context shared by the speaker. Thus, they underscore the most relevant points covered in the meeting. A pre-trained Question/Answering model determines if the generated summary for the meeting answers the queries (short interruptions). <b>Q</b>uality is a measure of readability. This is achieved by using a Discriminator (a combination of autoencoder + generative adversarial network) that can discriminate between human generated and machine generated summaries. 
Lastly, a loss based on the length of the summary maintains the <b>S</b>pan. This measure keeps the summary from getting too short. A combination of these losses are used to train the model. 

## Reed:  An approach towards quickly bootstrapping multilingual acoustic models

**Speech Recognition, Deep Learning** [ <a href="files/Reed_Long.pdf" target="_blank">paper</a> ] [ <a href="files/REED_presentation.pdf" target="_blank">presentation</a> ] (accepted at SLT, 2021)

<span class="research-img">
	<img width="500" src="/images/slt.svg">
</span>

<span class="research-text">
<b>Abstract: </b>Multilingual automatic speech recognition (ASR) system is a single entity capable of transcribing multiple languages sharing a common phone space. Performance of such a system is highly dependent on the compatibility of the languages. State of the art speech recognition systems are built using sequential architectures based on recurrent neural networks (RNN) limiting the computational parallelization in training. This poses a significant challenge in terms of time taken to bootstrap and validate the compatibility of multiple languages for building a robust multilingual system. Complex architectural choices based on self-attention networks are made to improve the parallelization thereby reducing the training time. In this work, we propose Reed, a simple system based on 1D convolutions which uses very short context to improve the training time. To improve the performance of our system, we use raw time-domain speech signals directly as input. This enables the convolutional layers to learn feature representations rather than relying on handcrafted features such as MFCC. We report improvement on training and inference times by
atleast a factor of 4× and 7.4× respectively with comparable WERs against standard RNN based baseline systems on SpeechOcean’s multilingual low resource dataset.</span>

## An Approach Towards Action Recognition using Part Based Hierarchical Fusion

**Computer Vision, Deep Learning** [ <a href="files/PBAR.pdf" target="_blank">paper</a> ] [ <a href="files/PBAR_presentation.pdf" target="_blank">presentation</a> ] (accepted at ISVC, 2020)

<span class="research-img">
	<img src="/images/pbar.jpeg" width="500px">
</span>

<span class="research-text">
<b>Abstract:</b> The human body can be represented as an articulation of rigid and hinged joints which can be combined to form the parts of the body. Human actions can be thought of as a collective action of these parts. Hence, learning an effective spatio-temporal representation of the collective motion of these parts is key to action recognition. In this work, we propose an end-to-end pipeline for the task of human action recognition on video sequences using 2D joint trajectories estimated from a pose estimation framework. We use a Hierarchical Bidirectional Long Short Term Memory Network (HBLSTM) to model the spatio-temporal dependencies of the motion by fusing the pose based joint trajectories in a part based hierarchical fashion. To denote the effectiveness of our proposed approach, we compare its performance with six comparative architectures based on our model.

## Sentence Modelling for Contextual Meeting Segmentation

**Natural Language Processing, Summarization** [ <a target="_blank" href="/files/CMS___Synapse__V2.pdf" target="_blank">short paper</a> ]

<span class="research-img">
	<img src="/images/pn.png" width="600px">
</span>

<span class="research-text">
<b>Abstract:</b> We propose a novel technique of contextual meeting segmentation for the task of meeting summarization. Unlike documents, meetings span over multiple topics spread throughout the course of the meeting. In order to capture the true summary of the meeting, it is important to capture the summary of each of the topics present in the meeting. The segmentation approaches existing today ignore the fact that sentences belonging to the same context can be continuous or non-continuous in nature. We solve the problem of contextual meeting segmentation using pointer mechanism to extract the related sentences from a meeting transcription without assuming that the sentences are consecutive in nature. 

## Knowledge Graph (AiGraph) Based Meeting Insights

**Information Retrieval, Recommendation** [ <a target="_blank" href="/files/l1.pdf" target="_blank">short paper</a> ]

<span class="research-img">
	<img src="/images/pu.svg" width="500px">
</span>

<span class="research-text">
<b>Abstract: </b>In this paper we present AiGraph, an enterprise knowledge graph, representing details about how an employee communicates through emails, meetings, and documents. By representing all her communication in the form of a graph, we are able to extract complex insights which are computationally expensive in silo’ed applications. We consider a recommendation application – Meeting Insights – to show power of AiGraph. This application recommends related emails and documents for a given meeting. There are a number of ways in which AiGraph can improve the Meeting Insights – most signifcantly, it can improve the relevance of the system by providing better candidate emails; and features for a ranker to rank these candidates. In this paper we describe various ways to improve relevance of Meeting Insights using AiGraph.</span>

## Anterior Segment Imaging - MIT Media Lab's REDX

**Computer Vision, Anamoly Detection, Hardware** [ <a target="_blank" href="/files/asi.pdf" target="_blank">poster</a> ]

<span class="research-img">
	<img src="/images/redx.jpeg" width="600px">
</span>

<span class="research-text">
Rethinking Engineering Design Execution (REDX) is an interdisciplinary platform that enables collaboration between world-renowned medical professionals, engineers and computer scientists to build solutions for society's most pressing healthcare challenges. I collaborated with Hyderabad's leading Eye-Care Institute, L.V.Prasad Eye Institute to build a low-cost, wearable solid-state device as a replacement to existing Ophthalmic Slit Lamps, a device extensively used by Ophthalmologists for examining the eye. The device is bulky, expensive and consequently, extremely difficult to carry out of the hospitals, particularly to the remote locations in India which limits the eye-care facility in such locations. I, along with my team, worked on a simple portable device that could capture  high definition stills of the cornea (anterior segment of the eye) through multiple viewpoints. The multiple viewpoints enabled me to reconstruct the stills into a 3D model of the cornea. I built an anomaly detector to identify any abnormalities in the reconstructed cornea which, along with the reconstructed 3D corneal model served as a preliminary report to the medical professional for further analysis.  </span>

## Cloud Based Group Oriented File Sharing Network - TheBhaad

**Cloud Computing, Security, User Behavioral Study** [ <a href="https://www.youtube.com/watch?v=S9Oq2n2rIaY" target="_blank">video</a> ]

<span class="research-img">
	<img src="/images/thebhaad.jpg" style="height:300px">
</span>

<span class="research-text">
An one-stop online-environment that complimented the real-environment in terms of the interactions between students and professors. Built a file-sharing <i>network</i> instead of just a portal. Back in 2013, there were limited means for sharing assignments and coursework online (such as Facebook groups) and weren't user-friendly. Moreover, they were inconvinient for group interaction. In the dire need of an organized file-sharing group-based platform, I single-handedly developed TheBhaad over a course of 5 months. TheBhaad had an operating system like user-interface for easy operation with an advanced search features across groups (classrooms), contacts, personalized document realignment, discussion forum, request and push-notification features. <i class="underline">This was extensively used by my undergraduate institution at a time having on an average of 5000 active users per month. I was awarded Best Enterpreneur by my institue for my work on TheBhaad</i></span>

<!-- ## Reinforced and Collaborative Music Recommendation

**Reinforcement Learning, Collaborative Recommendation**, (Undergraduate Thesis)

<span class="research-img">
	<img src="/images/m.webp" style="height:300px">
</span>

<span class="research-text">
A prediction model that could predict the songs that a user would want toplay next without requiring his intervention based on the current history. The model works by detecting similarity between songs to learn a predictive model without using metadata such as sound-wave, song-name, genre etc. The idea was that similarity between two songs is quite subjective and differs heavily between individuals when the set of available songs is limited. Two songs with completely different meta properties can be perceived similar by an individual. For the prediction model, I employed an Ensemble Model of Reinforcement Learning bundled with unsupervised Learning algorithms taking the user play history as the input. The skip rate and the duration of the song played were used as reward to devise relationships.</span>
 -->
## Virtual Shopping Assitant Bot

**Reinforcment Learning, Conversational Bot** [ <a href="https://www.microsoft.com/en-us/research/project/multi-world-testing-mwt/" target="_blank">Reference</a> ] (Microsoft - Data Science Intern)

<span class="research-img">
	<img src="/images/bots.jpg" style="height:300px">
</span>

<span class="research-text">
Developed a virtual shopping assistant bot that proactively engaged users and assisted them in placing an order. From a a set of curated questions, the agent learned the optimal order of questions to ask to maximize user engagement. I integrated multi-world testing (MWT), a machine learning toolbox based on reinforcement learning for principled and efficient experimentation, into the bot.</span>

<br>

# Other Projects
<br>

## COVID-19 fact checker

Developed a pipeline to fact-check covid-19 news queried on Bing by validating the facts against curated authentic sources. 

## PianoAR 

Developed an application that a projected and augmented a pinao on any table top and detected finger positions on the projection to play the corresponding piano notes.

## Football Match - Emotion Segregation

Developed a model using word-2-vec and RNNs to detect emotion on Twitter feeds during football matches and segregate the tweets into buckets representing the supporters of competing teams. 

## Hoverboard

As a part of the IEEE chapter of my undergraduate, I, along with my team, developed a hoverboard.
