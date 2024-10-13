---
layout: post
title: Intent Estimation, Wearables and teleoperation
date: 2014-06-09 11:21:29
summary: Research on robotic intent estimation, wearables, and teleoperation.
categories: robotics research teleoperation
---

<!-- I shouldn't need to do this, but the toggle for website button was not working natively on this page without this script -->
<script>
function toggleVisibility(id) {
    var element = document.getElementById(id);
    if (element.style.display === "none") {
        element.style.display = "block";
    } else {
        element.style.display = "none";
    }
}
</script>

## Robotic Intent Estimation, Wearables, Teleoperation and Learning from Demonstration

ARMLab performs research in robot's estimating teammate intent, wearable robotic platforms and efficient robot teleoperation. Projects include improving upper-limb prosthesis, improving teleoperation and learning from demonstration by leveraging advances in augmented reality, and developing a wearable sensor capable of predicting the wearers path for fall prevention and exoskeleton enhancement.

## Research Topics

---

## **<u>Intelligent Prosthetic Arm (IPArm)</u>**

### Description:
One key challenge in upper limb prosthetics is controlling the many degrees of freedom required for dexterous tasks, especially as functionality approaches that of a natural arm. Limited user input, combined with complex control demands, calls for a solution that interprets human intent and enables the prosthesis to perform tasks autonomously. The IPARM project aims to provide prosthetics and assitive arms with autonomy that seamlessly integrates with the user’s intentions, allowing for precise, dexterous movements.

Our research explores whether robotic prosthetics and assistive arms can use situational awareness and predictive modeling to reduce the learning curve and improve accuracy. We investigate how inputs like EMG signals and gaze tracking can determine desired actions and how natural arm motions and task affordances can confirm user intent.

<b>Research Objectives:</b>

1.	Reduce the time required for users to achieve full dexterity through intent estimation.
2.	Enhance overall dexterity by integrating situational awareness for complex tasks.

This project seeks to make upper-limb prosthetics and assistive arms more intuitive and effective, empowering users to perform complex tasks with ease.

<div style="text-align: center;">
    <img src="/research_media/proact_splash.png" alt="Touch-GS mirror visualization" style="max-width: 100%; height: auto; border-radius: 10px; box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);">
</div>


<div class="video-wrapper" style="border-radius: 10px; overflow: hidden; width: 100%; height: auto; aspect-ratio: 16/9; margin: 0 auto; padding: 0;">
    <video width="100%" height="100%" autoplay muted loop playsinline style="object-fit: cover; display: block; margin: 0; padding: 0;">
        <source src="/papers/proact_all_methods_compressed.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
</div>

#### <span style="color: red;">Papers and Videos:</span> 

<button onclick="toggleVisibility('papers-iparm-section')" style="background-color: #f1f1f1; border: none; padding: 10px 20px; font-size: 16px; cursor: pointer; border-radius: 5px;">Show/Hide Papers and Videos</button>

<div id="papers-iparm-section" style="display: none; margin-top: 20px;">
    <figure style="max-width: 75%; margin: 0 auto; text-align: center;">
        <div class="video-wrapper" style="border-radius: 10px; overflow: hidden; width: 100%; height: auto; aspect-ratio: 16/9; margin: 0 auto; padding: 0;">
            <video width="100%" height="100%" autoplay muted loop playsinline style="object-fit: cover; display: block; margin: 0; padding: 0;">
                <source src="/papers/proact_all_methods_compressed.mp4" type="video/mp4">
                Your browser does not support the video tag.
            </video>
        </div>
        <figcaption style="margin-top: 10px;">
            <a href="https://armlabstanford.github.io/proact" target="_blank">ProACT: An Augmented Reality Testbed for Intelligent Prosthetic Arms</a>
        </figcaption>
    </figure>
</div>

---

## **<u>Efficient Teleoperation and Learning from Demonstration</u>**

### Description:
Human demonstrators often have expert knoweldge on how to perform a manipulation task, but transfering this knoweldge to a robot can be tedious, especially for demonstrators who are not accustomed to working with robots. In this work, we leverage Augmented Reality (AR) to provide efficient methods of teaching a robot a new task and performing teleoperation.

<div style="text-align: center;">
    <img src="/research_media/ar_teleop_2024.png" alt="Touch-GS mirror visualization" style="max-width: 100%; height: auto; border-radius: 10px; box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);">
</div>

<div class="video-wrapper" style="border-radius: 10px; overflow: hidden; width: 100%; height: auto; aspect-ratio: 16/9; margin: 0 auto; padding: 0;">
    <video width="100%" height="100%" autoplay muted loop playsinline style="object-fit: cover; display: block; margin: 0; padding: 0;">
        <source src="/papers/lfd_ar_9_2024.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
</div>

#### <span style="color: red;">Papers and Videos:</span> 

<button onclick="toggleVisibility('papers-eff-teleop-lfd-section')" style="background-color: #f1f1f1; border: none; padding: 10px 20px; font-size: 16px; cursor: pointer; border-radius: 5px;">Show/Hide Papers and Videos</button>

<div id="papers-eff-teleop-lfd-section" style="display: none; margin-top: 20px;">
    <div style="text-align: center;">
        <figure>
            <iframe width="560" height="315" src="https://www.youtube.com/embed/w-M58ohPgrA?si=HnuQ1CVWGkTZgByp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
            <figcaption><a href="https://arxiv.org/abs/2409.18394">An Augmented Reality Interface for Teleoperating Robot Manipulators: Reducing Demonstrator Task Load through Digital Twin Control</a></figcaption>
        </figure>
    </div>
</div>

---

## **<u>Wearable Motion Prediction: Path Prediction, Fall Prevention and Exoskeleton Enhancment</u>**

### Description:
Humans who experience challenges with balance or who wear exoskeletons may have their locomotion or balance challenged by obstacles and variability of their path. A wearable sensor that can observe past motion and surrounding obstacles can use data-driven approaches to approximate the path(s) the wearer might take and anticipate challenges in terrain or balance the wearer may experience. 

In this project we developed a wearable robotic system that consists of multiple cameras and computation, and is capable of observing the past motion and surrounding obstacles and terrain and using this input to predict possible paths the human may take and anticipating challenges to their locomotion. This system can be interfaced with an exoskeleton to provide anticipatory control conditioned on the surrounding terrain and objects which may influence expected motion.

<div style="text-align: center;">
    <img src="/research_media/smart_belt_view.png" alt="Touch-GS mirror visualization" style="max-width: 100%; height: auto; border-radius: 10px; box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);">
</div>


<div class="video-wrapper" style="border-radius: 10px; overflow: hidden; width: 100%; height: auto; aspect-ratio: 16/9; margin: 0 auto; padding: 0;">
    <video width="100%" height="100%" autoplay muted loop playsinline style="object-fit: cover; display: block; margin: 0; padding: 0;">
        <source src="/papers/ego_nav2024.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
</div>

#### <span style="color: red;">Papers and Videos:</span> 

<button onclick="toggleVisibility('papers-path-pred-section')" style="background-color: #f1f1f1; border: none; padding: 10px 20px; font-size: 16px; cursor: pointer; border-radius: 5px;">Show/Hide Papers and Videos</button>

<div id="papers-path-pred-section" style="display: none; margin-top: 20px;">
    <div style="text-align: center;">
        <figure>
            <iframe width="560" height="315" src="https://www.youtube.com/embed/wtjqA_oGn0s?si=iZ0ZGLXDSIvuhSWm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
            <figcaption><a href="http://mmego.weizhuowang.com/">Egocentric Scene-aware Human Trajectory Prediction</a></figcaption>
        </figure>
    </div>
    <div style="text-align: center;">
        <figure>
            <iframe width="560" height="315" src="https://www.youtube.com/embed/4S2FaRdK2RQ?si=SVjWzDiHF6KgMJhX" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
            <figcaption><a href="https://ieeexplore.ieee.org/document/10161361">Trajectory and Sway Prediction Towards Fall Prevention</a></figcaption>
        </figure>
    </div>
</div>

