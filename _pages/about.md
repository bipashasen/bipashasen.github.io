---
permalink: /
#layout: archive
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<div hidden="hidden">
<script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=P0DmcjPhTVQDSVsO6eLpfLlblpD7aYEdFi8dEehI1TI&cl=ffffff&w=a"></script>
</div>

<span class="small_font">I am a first-year <b>Ph.D. at the CSAIL, MIT</b> advised by Prof. <a target="_blank" href="https://people.csail.mit.edu/pulkitag/">Pulkit Agrawal</a>. I am supported by the <b>Ida Green Fellowship</b>. I am grateful to have worked with some of the best researchers around the world, including Prof. <a target="_blank" href="https://faculty.iiit.ac.in/~jawahar/">C V Jawahar</a>, <a target="_blank" href="https://vinaypn.github.io/">Vinay Namboodiri</a>, <a target="_blank" href="https://www.iiit.ac.in/people/faculty/mkrishna/">K. Madhav Krishna</a>, <a target="_blank" href="https://cs.brown.edu/people/ssrinath/">Srinath Sridhar</a>, <a target="_blank" href="http://liampaull.ca/">Liam Paull</a>, and <a target="_blank" href="http://www.cs.toronto.edu/~florian/">Florian Shkurti</a>.
<br>&emsp;&emsp;&emsp;<b>Prior Experience.</b> I was also a <b>Data Scientist at Microsoft</b>. I led a segment of the recommendation and suggestion team for the world's biggest enterprise-facing email client - Outlook. The product features I worked on are used by more than 100 million users per month!
<br>&emsp;&emsp;&emsp;<b>Creative Outlet.</b> I am a musician. I sing and play guitar. I have toured and performed at several places with my previous band, <a target="_blank" href="https://www.facebook.com/AndroMetaBand">Andrometa</a>. I also LOVE traveling and used to create travel vlogs and music covers on YouTube! My <b>brother</b> is an amazing pianist and has taken over the channel now: <a target="_blank" href="https://www.youtube.com/channel/UCU1TMnEt0J1UJZfMW1Gixgg?view_as=subscriber" target="_blank">Insen: Outdoor Pianist</a>. 

<h3>Research Interest</h3>

<!-- <span class="small_font">My interest lies at the intersection of <b>3D computer vision and Robotics</b>. Specifically, I am interested in designing improved representations of the 3D world to enable embodied agents acquire a holistic view of the world. This way, an agent can make better-informed control decisions for achieving a given downstream goal, for example, manipulation or autonomous navigation. <br>&emsp;&emsp;&emsp;Today, most works rely on explicit representation forms like pointclouds or voxel-based representations. But they are limiting in many ways - they are high dimensional, discrete, and, most importantly, incomplete -- they do not sense the underlying structure and only capture explicit values at specific locations. I am more interested in <b>implicit representations</b> of the world and how to design improved task-specific representations. Ultimately, I am excited to see embodied AI become a part of the real world and seamlessly integrate with humans!</span> -->

<span class="small_font">What drives my research is the idea of seeing robots become a commonplace - a part of our daily lives - imbibed with the ability to interact and manipulate the environment it lives in. In order to build such a generic enough robotic system that can perform most day-to-day tasks, scaling up the data needed to train them is, I believe, the primary challenge that we need to address in robotics. 
<br>&emsp;&emsp;&emsp;My approach to addressing this is rethinking - (1) the kind of data we should be collecting (i.e. the learning objective), and (2) the method of collecting this data (i.e. scalable hardware). I am building towards the these two directions and hoping to make data collection for robotic manipulation as seemless as possible!
</span>

<div class="recent_updates">Selected Research</div>
<span style="font-size:14px;margin-bottom: -25px;display: block;">*Equal Authors / <span class="highlight">Highlighted Papers</span></span>

<div class="research-block">
	<div class="left">
		<span class="research-img">
			<img src="/images/teasers/cgdf.gif">
		</span>
	</div>
	<div class="right">
		<div class="title">Constrained 6-DoF Grasp Generation on Complex Shapes for Improved Dual-Arm Manipulation</div>
		<div class="sub-title">Gaurav Singh, Sanket Kalwar, Md Faizal Karim, <b style="color:#a115a0">Bipasha Sen (in advising capacity)</b>, Nagamanikandan Govindan, Srinath Sridhar and K Madhava Krishna, <i><br><b>IROS 2024</b></i><a target="_blank" class="tab_paper" href="https://constrained-grasp-diffusion.github.io/">project page</a><a target="_blank" class="tab_paper" href="https://arxiv.org/abs/2404.04643">ArXiv</a></div>
		<span class="research-text">
		CGDF: Constrained Grasp Diffusion Fields is a diffusion-based grasp generative model that generalizes to objects with arbitrary geometries, as well as generates dense grasps on the target regions. CGDF uses a part-guided diffusion approach that enables it to get high sample efficiency in constrained grasping without explicitly training on massive constraint-augmented datasets. CGDF generalizes to stable grasps on complex objects, especially useful for dual-arm manipulation settings.
		</span>
	</div>
</div>

<div class="research-block">
	<div class="left">
		<span class="research-img">
			<img src="/images/teasers/conceptgraphs.gif">
		</span>
	</div>
	<div class="right">
		<div class="title">ConceptGraphs: Open-Vocabulary 3D Scene Graphs for Perception and Planning</div>
		<div class="sub-title">Qiao Gu*, Ali Kuwajerwala*, Sacha Morin*, Krishna Murthy Jatavallabhula*, <b style="color:#a115a0">Bipasha Sen</b>, Aditya Agarwal, Kirsty Ellis, Celso Miguel de Melo, Corban Rivera, William Paul, Rama Chellappa, Chuang Gan, Joshua B. Tenenbaum, Antonio Torralba, Florian Shkurti, Liam Paull <i><br><b>ICRA 2024, CoRL-W 2024</b></i><a target="_blank" class="tab_paper" href="https://concept-graphs.github.io/">project page</a><a target="_blank" class="tab_paper" href="https://arxiv.org/abs/2309.16650">ArXiv</a></div>
		<span class="research-text">
		For robots to perform a wide variety of tasks, they require a 3D representation of the world that is semantically rich, yet compact and efficient for task-driven perception and planning. ConceptGraphs is an open-vocabulary graph-structured representation for 3D scenes that generalize to novel semantic classes, without the need to collect large 3D datasets or finetune models. 
		</span>
	</div>
</div>

<div class="research-block highlight">
	<div class="left">
		<span class="research-img">
			<img src="/images/teasers/edmp.gif">
		</span>
	</div>
	<div class="right">
		<div class="title">EDMP: Ensemble-of-costs-guided Diffusion for Motion Planning</div>
		<div class="sub-title">Kallol Saha*, Vishal Mandadi*, Jayaram Reddy*, Ajit Srikanth, Aditya Agarwal, <b style="color:#a115a0">Bipasha Sen (in advising capacity)</b>, Arun Singh, Madhava Krishna <br><i><b>ICRA 2024, CoRL-W 2023</b></i><a target="_blank" class="tab_paper" href="https://ensemble-of-costs-diffusion.github.io/">project page</a><a target="_blank" class="tab_paper" href="https://arxiv.org/pdf/2309.11414.pdf">ArXiv</a></div>
		<span class="research-text">
		EDMP combines the strength of classical planning and deep learning by leveraging a diffusion policy to learn a prior over kinematically valid trajectories and guide it directly at the time of inference using scene-specific costs such as "collision-cost". Instead of using a single-cost, we propose using multiple-cost functions (ensemble-of-cost-guidance) to capture variations across scenes, thereby generalizing to diverse scenes.
		</span>
	</div>
</div>

<div class="research-block">
	<div class="left">
		<span class="research-img">
			<img src="/images/teasers/hypnerf.gif">
		</span>
	</div>
	<div class="right">
		<div class="title">HyP-NeRF: Learning Improved NeRF Priors using a HyperNetwork</div>
		<div class="sub-title"><b style="color:#a115a0">Bipasha Sen</b>*, Gaurav Singh*, Aditya Agarwal*, Rohith Agaram, Madhava Krishna, Srinath Sridhar <i><br><b>NeurIPS 2023</b></i><a target="_blank" class="tab_paper" href="https://hypnerf.github.io">project page</a><a target="_blank" class="tab_paper" href="https://arxiv.org/abs/2306.06093">ArXiv</a></div>
		<span class="research-text">
		Learning generalizable NeRF priors over categories of scenes or objects has been challenging due to the high dimensionality of network weight space. To address the limitations of existing work on generalization, multi-view consistency and to improve quality, we propose HyP-NeRF, a latent conditioning method for learning generalizable category-level NeRF priors using hypernetworks. 
		</span>
	</div>
</div>
<!-- 
<div class="research-block">
	<div class="left">
		<span class="research-img">
			<img src="/images/teasers/case2023.gif">
		</span>
	</div>
	<div class="right">
		<div class="title">Disentangling Planning and Control for Non-prehensile Tabletop Manipulation</div>
		<div class="sub-title">Vishal Mandadi, Kallol Saha, Dipanwita Guhathakurta, Mohammad Nomaan Qureshi, Aditya Agarwal, <b style="color:#a115a0">Bipasha Sen (in advising capacity)</b>,
Dipanjan Das, Brojeshwar Bhowmick, Arun Kumar Singh, Madhava Krishna <i><br><b>CASE 2023</b></i></div>
		<span class="research-text">
		Our novel framework disentangles planning and control enabling us to operate in a context- free manner. Our method consists of an A* planner and a low-level RL controller. The low-level RL controller is agnostic of the scene context and A* is idependent of the low-level control and only takes scene context into account.
		</span>
	</div>
</div> --->

<!-- <div class="research-block">
	<div class="left">
		<span class="research-img">
			<img src="/images/teasers/indie-icmpc.jpg">
		</span>
	</div>
	<div class="right">
		<div class="title">Uncovering hidden biases against Indian independent artists in the perception of music quality by Indian
Audience</div>
		<div class="sub-title"><b style="color:#a115a0">Bipasha Sen</b>*, Aditya Agarwal*, Vinoo Alluri <i><br><b>ICMPC 2023</b></i></div>
		<span class="research-text">
		Unlike well-established (W-E) music artists, Indian indie (In-In) music artists are small-scale artists unsigned by major music labels. Consequently, In-In music receives less publicity and resources during music production. Thus, In-In may be perceived to be lower in quality by the Indian audience compared to W-E. In this work, we aim to investigate if the Indian audience's perception of music quality is biased.
		</span>
	</div>
</div> -->

<div class="research-block">
	<div class="left">
		<span class="research-img">
			<img src="/images/teasers/scarp_banner.gif">
		</span>
	</div>
	<div class="right">
		<div class="title">SCARP: 3D <b>S</b>hape <b>C</b>ompletion in <b>AR</b>bitrary <b>P</b>oses for Improved Grasping</div>
		<div class="sub-title"><b style="color:#a115a0">Bipasha Sen</b>*, Aditya Agarwal*, Gaurav Singh*, Brojeshwar Bhowmick, Srinath Sridhar, Madhava Krishna <i><br><b>ICRA 2023, RSS-W 2023</b></i><a target="_blank" class="tab_paper" href="https://bipashasen.github.io/scarp/">project page</a><a target="_blank" class="tab_paper" href="https://www.youtube.com/watch?v=o2PuRVZ3jJA">video</a></div>
		<span class="research-text">
		We propose SCARP, a model that performs Shape Completion in ARbitrary Poses. Given a partial pointcloud of an object, SCARP learns a disentangled feature representation of pose and shape by relying on rotationally equivariant pose features and geometric shape features trained using a multi-tasking objective. 
		</span>
	</div>
</div>

<div class="research-block highlight">
	<div class="left">
		<span class="research-img">
			<img src="/images/teasers/inr-v.gif">
		</span>
	</div>
	<div class="right">
		<div class="title">INR-V: A Continuous Representation Space for Video-based Generative Tasks</div>
		<div class="sub-title"><b style="color:#a115a0">Bipasha Sen</b>*, Aditya Agarwal*, Vinay Namboodiri, C V Jawahar <i><br><b>TMLR 2022</b></i><a target="_blank"  class="tab_paper" href="https://openreview.net/forum?id=aIoEkwc2oB&referrer=%5BTMLR%5D(%2Fgroup%3Fid%3DTMLR)">OpenReview</a><a target="_blank" class="tab_paper" href="https://skymanaditya1.github.io/INRV/">project page</a><a target="_blank" class="tab_paper" href="https://youtu.be/ViIwnu5vcck">video</a></div>
		<span class="research-text">
		We propose INR-V, a video representation network that learns a continuous space for video-based generative tasks. INR-V parameterizes videos using implicit neural representations (INRs), a multi-layered perceptron that predicts an RGB value for each input pixel location of the video.
		</span>
	</div>
</div>

<div class="research-block">
	<div class="left">
		<span class="research-img">
			<img src="/images/teasers/faceoff.gif">
		</span>
	</div>
	<div class="right">
		<div class="title">FaceOff: A Video-to-Video Face Swapping System</div>
		<div class="sub-title">Aditya Agarwal*, <b style="color:#a115a0">Bipasha Sen</b>*, Rudrabha Mukhopadhyay, Vinay Namboodiri, C V Jawahar <i><br><b>WACV 2023</b></i><a target="_blank" class="tab_paper"  href="https://openaccess.thecvf.com/content/WACV2023/html/Agarwal_FaceOff_A_Video-to-Video_Face_Swapping_System_WACV_2023_paper.html">project page</a><a target="_blank" class="tab_paper"  href="https://bipashasen.github.io/FaceOff">paper</a><a target="_blank" class="tab_paper" href="https://www.youtube.com/watch?v=3TCugwmMjzo&t=2s">video</a> </div>
		<span class="research-text">
		We introduce video-to-video (V2V) face-swapping, a novel task of face-swapping that can preserve (1) the identity and expressions of the source (actor) face video and (2) the background and pose of the target (double) video. We propose FaceOff, a V2V face-swapping system that operates by learning a robust blending operation to merge two face videos following the constraints above. 
		</span>
	</div>
</div>

<div class="research-block">
	<div class="left">
		<span class="research-img">
			<img src="/images/teasers/lipreading.gif">
		</span>
	</div>
	<div class="right">
		<div class="title">Towards MOOCs for Lipreading: Using Synthetic Talking Heads to Train Humans in Lipreading at Scale</div>
		<div class="sub-title">Aditya Agarwal*, <b style="color:#a115a0">Bipasha Sen</b>*, Rudrabha Mukhopadhyay, Vinay Namboodiri, C V Jawahar <i><br><b>WACV 2023</b></i><a target="_blank" class="tab_paper" class="tab_paper" href="https://openaccess.thecvf.com/content/WACV2023/html/Agarwal_Towards_MOOCs_for_Lipreading_Using_Synthetic_Talking_Heads_To_Train_WACV_2023_paper.html">paper</a></div>
		<span class="research-text">
		We propose an end-to-end automated pipeline to a lipreading training platform using state-of-the-art talking heading video generator networks, text-to-speech models, and computer vision techniques. We then perform an extensive human evaluation using carefully thought out lipreading exercises to validate the quality of our designed platform against the existing lipreading platforms. 
		</span>
	</div>
</div>


<div class="research-block">
	<div class="left">
		<span class="research-img">
			<img src="/images/teasers/ocrtoc.gif">
		</span>
	</div>
	<div class="right">
		<div class="title">Approaches and Challenges in Robotic Perception for Table-top Rearrangement and Planning</div>
		<div class="sub-title">Aditya Agarwal*, <b style="color:#a115a0">Bipasha Sen</b>*, Shankara Narayanan V*, Vishal Reddy Mandadi*, Brojeshwar Bhowmick, K Madhava Krishna <i><br><b>Arxiv 2022</b></i><a target="_blank" class="tab_paper" href="https://arxiv.org/abs/2205.04090">paper</a><a target="_blank" class="tab_paper" href="https://youtu.be/GrOXEmwzxlA">video</a></div>
		<div class="win"><img src="images/trophy-icon.webp" width="10px">3rd in <a class="prize" href="https://rpal.cse.usf.edu/rgmc_icra2022/">ICRA 2022 OCRTOC</a></div>
		<span class="research-text">
		Table-top Rearrangement and Planning is a challenging problem that relies heavily on an excellent perception stack. We present a comprehensive overview and discuss the different challenges associated with the perception module. This work is a result of our extensive involvement in the ICRA 2022 OCRTOC Challenge.
		</span>
	</div>
</div>

<div class="research-block">
	<div class="left">
		<span class="research-img">
			<img src="/images/teasers/personalized.gif">
		</span>
	</div>
	<div class="right">
		<div class="title">Personalized One-Shot Lipreading for an ALS Patient</div>
		<div class="sub-title"><b style="color:#a115a0">Bipasha Sen</b>*, Aditya Agarwal*, Rudrabha Mukhopadhyay, Vinay Namboodiri, C V Jawahar <i><br><b>BMVC 2021</b></i><a class="tab_paper" target="_blank" href="https://www.bmvc2021-virtualconference.com/assets/papers/1468.pdf">paper</a><a target="_blank"  class="tab_paper" href="https://youtu.be/_famGVaem-8">video</a><a target="_blank"  class="tab_paper" href="http://bhaasha.iiit.ac.in/lipwav">portal</a></div>
		<span class="research-text">
		We propose a personalized network to lipread an ALS patient using only one-shot examples. Our approach significantly improves and achieves high top-5accuracy with 83.2% accuracy compared to 62.6% achieved by comparable methods for the patient. Apart from evaluating our approach on the ALS patient, we also extend it to people with hearing impairment relying extensively on lip movements to communicate.
		</span>
	</div>
</div>

