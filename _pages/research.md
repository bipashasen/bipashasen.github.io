---
title: "Research"
permalink: /research/
author_profile: true
---

<br>

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