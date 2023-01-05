---
permalink: /
#layout: archive
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class="small_font">I am a MS by Research student at International Institute of Information Technology, Hyderabad (IIIT-H). I am advised by Professor <a target="_blank" href="https://faculty.iiit.ac.in/~jawahar/">C V Jawahar</a> and Professor <a target="_blank" href="https://vinaypn.github.io/">Vinay Namboodiri</a> at the Center for Visual Information Technology (CVIT) Lab. I am also advised by Professor <a target="_blank" href="https://www.iiit.ac.in/people/faculty/mkrishna/">K. Madhav Krishna</a> and Professor <a target="_blank" href="https://cs.brown.edu/people/ssrinath/">Srinath Sridhar</a> at the Robotics Research Center (RRC). </span>

<span class="small_font">Before IIIT-H, I was a Data Scientist at Microsoft Research & Development, Hyderabad. I led the recommendation and suggestion team for the world's biggest enterprise facing email client - Outlook. These features are used by more than 100 million users per month, my hunch is that you might have seen some of them! <img class="tiny-emoji" with="18px" src="images/grin.svg">
</span>

<span class="small_font">I am also a musician, I sing and play guitar. I have toured and performed at several places with my previous band, <a target="_blank" href="https://www.facebook.com/AndroMetaBand">Andrometa</a>. I also tried my hands out travel vlogging and YouTubing! My brother is a (really awesome) piano player and has taken over the channel now - find them <a target="_blank" href="https://www.youtube.com/channel/UCU1TMnEt0J1UJZfMW1Gixgg?view_as=subscriber" target="_blank">here!</a>. I also love traveling.</span>

<span class="small_font"><b>Research Interest</b>: My primary research interest is computer vision to aid robotics applications. Specifically, I am interested in Implicit Neural Representations, 3D Computer Vision, and Neural Planners for Autonomous Machines. </span>

<span class="small_font">In 2018, I travelled solo to 6 countries, 13 states and interviewed 128 independent musicians!</span>

<div class="recent_updates">Recent Updates</div>

<ul class="updates">
	<li><b>[ October 2022 ]</b> INR-V: A Continuous Representation Space for Video-based Generative Tasks accepted at <b>TMLR 2022</b>!</li>
	<li><b>[ September 2022 ]</b> I am grateful to Microsoft Research for awarding me a travel grant of $2000 for <b>WACV 2023</b>!</li>
	<li><b>[ August 2022 ]</b> 2 papers accepted at <b>WACV 2023</b>!</li>
	<li><b>[ August 2022 ]</b> Gave a tutorial on "Computer Vision challenges in Table-top rearrangement and Planning" at the <a target="_blank" href="https://cvit.iiit.ac.in/summerschool2022/">6<sup>th</sup> Summer School of AI</a>, IIIT-H! <b><span class="green">(find the talk <a href="blog#ttrp-talk">here</a>)</span></b></li>
	<li><b>[ June 2022 ]</b> We are in <a target="_blank" href="https://www.iiit.ac.in/files/media/Sakshi-RRC.jpeg">news</a>!</li>
	<li><b>[ April 2022 ]</b> We came 3<sup>rd</sup> in <a target="_blank" href="http://ocrtoc.org/"><b>ICRA 2022</b> Open Cloud Robot Table Organization Challenge</a>!</li>
	<li><b>[ December 2021 ]</b> Granted a Provisional Patent on "SYSTEM AND METHOD FOR TRAINING USERS TO LIP READ"!</li>
	<li><b>[ November 2021 ]</b> Joined Robotics Research Center as a Research Fellow!</li>
	<li><b>[ August 2021 ]</b> Joined MS by Research at IIIT-H!</li>
	<li><b>[ June 2021 ]</b> "<a target="_blank" href="https://www.bmvc2021-virtualconference.com/assets/papers/1468.pdf">Personalized One-Shot Lipreading for an ALS Patient</a>" accepted at <b>BMVC 2021</b>!</li>
	<li><b>[ March 2021 ]</b> Joined Center for Visual Information Technology as a Research Fellow!</li>
</ul>

<div class="recent_updates">Selected Research</div>

<div class="research-block">
	<div class="left">
		<span class="research-img">
			<img src="/images/teasers/scarp_banner.gif">
		</span>
	</div>
	<div class="right">
		<div class="title">SCARP: 3D <b>S</b>hape <b>C</b>ompletion in <b>AR</b>bitrary <b>P</b>oses for Improved Grasping</div>
		<div class="sub-title"><b>Bipasha Sen*</b>, Aditya Agarwal*, Gaurav Singh*, Brojeshwar Bhowmick, Srinath Sridhar, Madhava Krishna, <i><b>Under Review @ ICRA 2023</b></i>, [ <a target="_blank" href="https://bipashasen.github.io/scarp/">Project Page</a> ] [ <a target="_blank" href="https://www.youtube.com/watch?v=o2PuRVZ3jJA">video</a> ]</div>
		<span class="research-text">
		Recovering full 3D shapes from partial observations is a challenging task that has been extensively addressed in the computer vision community. Many deep learning methods tackle this problem by training 3D shape generation networks to learn a prior over the full 3D shapes. In this training regime, the methods expect the inputs to be in a fixed canonical form, without which they fail to learn a valid prior over the 3D shapes. We propose SCARP, a model that performs Shape Completion in ARbitrary Poses. Given a partial pointcloud of an object, SCARP learns a disentangled feature representation of pose and shape by relying on rotationally equivariant pose features and geometric shape features trained using a multi-tasking objective. Unlike existing methods that depend on an external canonicalization, SCARP performs canonicalization, pose estimation, and shape completion in a single network, improving the performance by 45% over the existing baselines. In this work, we use SCARP for improving grasp proposals on tabletop objects. By completing partial tabletop objects directly in their observed poses, SCARP enables a SOTA grasp proposal network improve their proposals by 71.2% on partial shapes.
		</span>
	</div>
</div>

<div class="research-block">
	<div class="left">
		<span class="research-img">
			<img src="/images/teasers/inr-v.gif">
		</span>
	</div>
	<div class="right">
		<div class="title">INR-V: A Continuous Representation Space for Video-based Generative Tasks</div>
		<div class="sub-title"><b>Bipasha Sen*</b>, Aditya Agarwal*, Vinay Namboodiri, C V Jawahar, <i><b>TMLR 2022</b></i>, [ <a target="_blank" href="https://openreview.net/forum?id=aIoEkwc2oB&referrer=%5BTMLR%5D(%2Fgroup%3Fid%3DTMLR)">OpenReview</a> ] [ <a target="_blank" href="https://skymanaditya1.github.io/INRV/">Project Page</a> ] [ <a target="_blank" href="https://youtu.be/ViIwnu5vcck">video</a> ]</div>
		<span class="research-text">
		Generating videos is a complex task that is accomplished by generating a set of temporally coherent images frame-by-frame. This limits the expressivity of videos to only image-based operations on the individual video frames needing network designs to obtain temporally coherent trajectories in the underlying image space. We propose INR-V, a video representation network that learns a continuous space for video-based generative tasks. INR-V parameterizes videos using implicit neural representations (INRs), a multi-layered perceptron that predicts an RGB value for each input pixel location of the video. The INR is predicted using a meta-network which is a hypernetwork trained on neural representations of multiple video instances. Later, the meta-network can be sampled to generate diverse novel videos enabling many downstream video-based generative tasks. Interestingly, we find that conditional regularization and progressive weight initialization play a crucial role in obtaining INR-V. The representation space learned by INR-V is more expressive than an image space showcasing many interesting properties not possible with the existing works. For instance, INR-V can smoothly interpolate intermediate videos between known video instances (such as intermediate identities, expressions, and poses in face videos). It can also in-paint missing portions in videos to recover temporally coherent full videos. In this work, we evaluate the space learned by INR-V on diverse generative tasks such as video interpolation, novel video generation, video inversion, and video inpainting against the existing baselines. INR-V significantly outperforms the baselines on several of these demonstrated tasks, clearly showing the potential of the proposed representation space.
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
		<div class="sub-title">Aditya Agarwal*, <b>Bipasha Sen*</b>, Rudrabha Mukhopadhyay, Vinay Namboodiri, C V Jawahar, <i><b>WACV 2023</b></i>, [ <a target="_blank" href="files/faceoff.pdf">preprint</a> ] [ <a target="_blank" href="https://www.youtube.com/watch?v=3TCugwmMjzo&t=2s">video</a> ] </div>
		<span class="research-text">
		Doubles play an indispensable role in the movie industry. They take the place of the actors in dangerous stunt scenes or in scenes where the same actor plays multiple characters. The double's face is later replaced with the actor's face and expressions manually using expensive CGI technology, costing millions of dollars and taking months to complete. An automated, inexpensive, and fast way can be to use face-swapping techniques that aim to swap an identity from a source face video (or an image) to a target face video. However, such methods can not preserve the source expressions of the actor important for the scene's context. To tackle this challenge, we introduce video-to-video (V2V) face-swapping, a novel task of face-swapping that can preserve (1) the identity and expressions of the source (actor) face video and (2) the background and pose of the target (double) video. We propose FaceOff, a V2V face-swapping system that operates by learning a robust blending operation to merge two face videos following the constraints above. It first reduces the videos to a quantized latent space and then blends them in the reduced space. FaceOff is trained in a self-supervised manner and robustly tackles the non-trivial challenges of V2V face-swapping. As shown in the experimental section, FaceOff significantly outperforms alternate approaches qualitatively and quantitatively. 
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
		<div class="sub-title">Aditya Agarwal*, <b>Bipasha Sen*</b>, Rudrabha Mukhopadhyay, Vinay Namboodiri, C V Jawahar, <i><b>WACV 2023</b></i>, [ <a target="_blank" href="files/moocs.pdf">preprint</a> ]</div>
		<span class="research-text">
		Many people with some form of hearing loss consider lipreading as their primary mode of day-to-day communication. However, finding resources to learn or improve one's lipreading skills can be challenging. This is further exacerbated in COVID$19$ pandemic due to restrictions on direct interactions with peers and speech therapists. Today, online MOOCs platforms like Coursera and Udemy have become the most effective form of training for many kinds of skill development. However, online lipreading resources are scarce as creating such resources is an extensive process needing months of manual effort to record hired actors. Because of the manual pipeline, such platforms are also limited in the vocabulary, supported languages, accents, and speakers, and have a high usage cost. In this work, we investigate the possibility of replacing real human talking videos with synthetically generated videos. Synthetic data can be used to easily incorporate larger vocabularies, variations in accent, and even local languages, and many speakers. We propose an end-to-end automated pipeline to develop such a platform using state-of-the-art talking heading video generator networks, text-to-speech models, and computer vision techniques. We then perform an extensive human evaluation using carefully thought out lipreading exercises to validate the quality of our designed platform against the existing lipreading platforms. Our studies concretely point towards the potential of our approach for the development of a large-scale lipreading MOOCs platform that can impact millions of people with hearing loss.
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
		<div class="sub-title">Aditya Agarwal*, <b>Bipasha Sen</b>*, Shankara Narayanan V*, Vishal Reddy Mandadi*, Brojeshwar Bhowmick, K Madhava Krishna, <i><b>Arxiv 2022</b></i>, [ <a target="_blank" href="https://arxiv.org/abs/2205.04090">paper</a> ] [ <a target="_blank" href="https://youtu.be/GrOXEmwzxlA">video</a> ]</div>
		<div class="win"><img src="images/trophy-icon.webp" width="10px">3rd in <a href="https://rpal.cse.usf.edu/rgmc_icra2022/">ICRA 2022 Open Cloud Robot Table Organization Challenge</a></div>
		<span class="research-text">
		Table-top Rearrangement and Planning is a challenging problem that relies heavily on an excellent perception stack. The perception stack involves observing and registering the 3D scene on the table, detecting what objects are on the table, and how to manipulate them. Consequently, it greatly influences the system's task-planning and motion-planning stacks that follow. We present a comprehensive overview and discuss the different challenges associated with the perception module. This work is a result of our extensive involvement in the ICRA 2022 Open Cloud Robot Table Organization Challenge, in which we stood third in the final rankings.
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
		<div class="sub-title"><b>Bipasha Sen</b>*, Aditya Agarwal*, Rudrabha Mukhopadhyay, Vinay Namboodiri, C V Jawahar, <i><b>BMVC 2021</b></i>, [ <a target="_blank" href="https://www.bmvc2021-virtualconference.com/assets/papers/1468.pdf">paper</a> ] [ <a target="_blank" href="https://youtu.be/_famGVaem-8">video</a> ]</div>
		<span class="research-text">
		Lipreading or visually recognizing speech from the mouth movements of a speaker is a challenging and mentally taxing task. Unfortunately, multiple medical conditions force people to depend on this skill in their day-to-day lives for essential communication. Patients suffering from Amyotrophic Lateral Sclerosis (ALS) often lose muscle control, consequently their ability to generate speech and communicate via lip movements. Existing large datasets do not focus on medical patients or curate personalized vocabulary relevant to an individual. Collecting a large-scale dataset of a patient, needed to train mod-ern data-hungry deep learning models is, however, extremely challenging. In this work, we propose a personalized network to lipread an ALS patient using only one-shot examples. We depend on synthetically generated lip movements to augment the one-shot scenario. A Variational Encoder based domain adaptation technique is used to bridge the real-synthetic domain gap. Our approach significantly improves and achieves high top-5accuracy with 83.2% accuracy compared to 62.6% achieved by comparable methods for the patient. Apart from evaluating our approach on the ALS patient, we also extend it to people with hearing impairment relying extensively on lip movements to communicate.
		</span>
	</div>
</div>
