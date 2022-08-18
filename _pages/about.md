---
permalink: /
#layout: archive
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class="small_font">I am a MS by Research student at International Institute of Information Technology, Hyderabad (IIIT-H). I am advised by Professor <a target="_blank" href="https://faculty.iiit.ac.in/~jawahar/">CV Jawahar</a> and Professor <a target="_blank" href="https://vinaypn.github.io/">Vinay Namboodiri</a> at the Center for Visual Information Technology (CVIT) Lab. I am also advised by Professor <a target="_blank" href="https://www.iiit.ac.in/people/faculty/mkrishna/">K. Madhav Krishna</a> and Professor <a target="_blank" href="https://cs.brown.edu/people/ssrinath/">Srinath Sridhar</a> at the Robotics Research Center (RRC). </span>

<span class="small_font">My primary research interest is computer vision to aid robotics applications. Specifically, I am interested in Implicit Neural Representations, 3D Computer Vision, and Neural Planners for Autonomous Machines. </span>

<span class="small_font">Before IIIT-H, I was a Data Scientist at Microsoft Research & Development, Hyderabad. I led the recommendation and suggestion team for the world's biggest enterprise facing email client - Outlook. These features are used by more than 100 million users per month, my hunch is that you might have seen some of them! <img class="tiny-emoji" with="18px" src="images/grin.svg">
</span>

<span class="small_font">I am also a musician, I sing and play guitar. I have toured and performed at several places with my previous band, <a target="_blank" href="https://www.facebook.com/AndroMetaBand">Andrometa</a>. I also tried my hands out travel vlogging and YouTubing! My brother is a (really awesome) piano player and has taken over the channel now - find them <a target="_blank" href="https://www.youtube.com/channel/UCU1TMnEt0J1UJZfMW1Gixgg?view_as=subscriber" target="_blank">here!</a>. I also love traveling.</span>

<span class="small_font">In 2018, I travelled solo to 6 countries, 13 states and interviewed 128 independent musicians!</span>

<div class="recent_updates">Recent Updates</div>

<ul class="updates">
	<li><b><i>August 2022</i></b>, 2 papers accepted at WACV 2023!</li>
	<li><b><i>August 2022</i></b>, Gave a tutorial on "Computer Vision challenges in Table-top rearrangement and Planning" at the 6<sup>th</sup> Summer School of AI! <b>[ <a target="_blank" href="https://youtu.be/Olhf4c6OR0w"><span class="green">YouTube Link</span></a> ]</b></li>
	<li><b><i>June 2022</i></b>, We are in <a target="_blank" href="https://www.iiit.ac.in/files/media/Sakshi-RRC.jpeg">news</a>!</li>
	<li><b><i>April 2022</i></b>, We came 3<sup>rd</sup> in <a target="_blank" href="http://ocrtoc.org/">ICRA 2022 Open Cloud Robot Table Organization Challenge</a>!</li>
	<li><b><i>December 2021</i></b>, Granted a Provisional Patent on "SYSTEM AND METHOD FOR TRAINING USERS TO LIP READ"!</li>
	<li><b><i>November 2021</i></b>, Joined Robotics Research Center as a Research Fellow!</li>
	<li><b><i>August 2021</i></b>, Joined MS by Research at IIIT-H!</li>
	<li><b><i>June 2021</i></b>, "<a target="_blank" href="https://www.bmvc2021-virtualconference.com/assets/papers/1468.pdf">Personalized One-Shot Lipreading for an ALS Patient</a>" accepted at BMVC 2021!</li>
	<li><b><i>March 2021</i></b>, Joined Center for Visual Information Technology as a Research Fellow!</li>
</ul>

<div class="recent_updates">Selected Research</div>

<div class="research-block">
	<div class="left">
		<span class="research-img">
			<img src="/images/teasers/inr-v.gif">
		</span>
	</div>
	<div class="right">
		<div class="title">INR-V: A continuous representation space for videos.</div>
		<div class="sub-title"><b>Bipasha Sen*</b>, Aditya Agarwal*, Vinay Namboodiri, CV Jawahar, <i>Under Review</i></div>
		<span class="research-text">
		Images are considered a complete signal, whereas videos are usually broken down into a set of temporally coherent images. Consequently, an image space is leveraged for various video-based tasks, such as novel video generation and future video segment prediction. This limits the expressivity of videos to only image-based operations needing network designs to obtain temporally coherent trajectories in the image space. We propose INR-V, a video representation network that learns a continuous latent space directly for videos. INR-V regards videos as complete units parameterized by implicit neural representations (INRs), a multi-layered perceptron with only a few thousand parameters. A meta-network is then used to predict these few thousand parameters allowing it to learn a continuous space over the neural representations. Later, the meta-network can generate novel neural representations by sampling diverse points over the learned space leading to novel videos. Interestingly, we find that conditional regularization and progressive weight initialization play a crucial role in obtaining INR-V. In this work, we analyze INR-V's several video-based properties. For instance, we show smooth interpolation of coherent videos between two videos by traversing along their latent points in the underlying video space. Moreover, learning a video space allows the network to directly invert an unseen video to its latent point in the latent space. We show the various applications of video inversion. Lastly, INRs learn a continuous signal independent of the input dimension letting INR-V generate multi-resolution videos (like 32 x 32 or 100 x100) directly at inference without any finetuning or architectural changes. We conduct several comparisons and evaluate each of the properties, ultimately demonstrating the potential of a continuous representation space for videos. 
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
		<div class="sub-title">Aditya Agarwal*, <b>Bipasha Sen*</b>, Rudrabha Mukhopadhyay, Vinay Namboodiri, CV Jawahar, <i><b>WACV 2023</b></i>, [ <a target="_blank" href="files/faceoff.pdf">preprint</a> ] [ <a target="_blank" href="https://www.youtube.com/watch?v=3TCugwmMjzo&t=2s">video</a> ] </div>
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
		<div class="sub-title">Aditya Agarwal*, <b>Bipasha Sen*</b>, Rudrabha Mukhopadhyay, Vinay Namboodiri, CV Jawahar, <i><b>WACV 2023</b></i>, [ <a target="_blank" href="files/moocs.pdf">preprint</a> ]</div>
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
		<div class="win"><img src="images/trophy-icon.webp" width="10px">3rd in ICRA 2022 Open Cloud Robot Table Organization Challenge</div>
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
		<div class="sub-title"><b>Bipasha Sen</b>*, Aditya Agarwal*, Rudrabha Mukhopadhyay, Vinay Namboodiri, CV Jawahar, <i><b>BMVC 2021</b></i>, [ <a target="_blank" href="https://www.bmvc2021-virtualconference.com/assets/papers/1468.pdf">paper</a> ] [ <a target="_blank" href="https://youtu.be/_famGVaem-8">video</a> ]</div>
		<span class="research-text">
		Lipreading or visually recognizing speech from the mouth movements of a speaker is a challenging and mentally taxing task. Unfortunately, multiple medical conditions force people to depend on this skill in their day-to-day lives for essential communication. Patients suffering from Amyotrophic Lateral Sclerosis (ALS) often lose muscle control, consequently their ability to generate speech and communicate via lip movements. Existing large datasets do not focus on medical patients or curate personalized vocabulary relevant to an individual. Collecting a large-scale dataset of a patient, needed to train mod-ern data-hungry deep learning models is, however, extremely challenging. In this work, we propose a personalized network to lipread an ALS patient using only one-shot examples. We depend on synthetically generated lip movements to augment the one-shot scenario. A Variational Encoder based domain adaptation technique is used to bridge the real-synthetic domain gap. Our approach significantly improves and achieves high top-5accuracy with 83.2% accuracy compared to 62.6% achieved by comparable methods for the patient. Apart from evaluating our approach on the ALS patient, we also extend it to people with hearing impairment relying extensively on lip movements to communicate.
		</span>
	</div>
</div>