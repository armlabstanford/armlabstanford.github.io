---
layout: post
title: Robotic Autonomy and Collaboration
date: 2014-06-10 11:21:29
summary: Research on robot autonomy and collaboration
categories: robotics research collaboration
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

## Robotic Autonomy and Collaboration

ARMLab performs research in advancing the capabilites of autonomous robots and making them effective collaborators.



## Research Topics

---

## **<u>Collaboration and Shared Autonomy</u>**

### Description:
In this work we investigate instances where a human and robot may have shared control or need to transition control of the motion of a robot or vehicle. The robot must understand the scene and potential danger, and when necessary take control from the human to maintain safety. The robot should also make its strategy legible to the human for the human to take over if necessary and hand-over control safely.

<div style="text-align: center;">
    <img src="/research_media/shared_autonomy_concept2020.png" alt="Control Diagram for Shared Autonomy" style="max-width: 100%; height: auto; border-radius: 10px; box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);">
</div>


<div class="video-wrapper" style="border-radius: 10px; overflow: hidden; width: 100%; height: auto; aspect-ratio: 16/9; margin: 0 auto; padding: 0;">
    <video width="100%" height="100%" autoplay muted loop playsinline style="object-fit: cover; display: block; margin: 0; padding: 0;">
        <source src="/papers/teaser_safer_splat2024.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
</div>

#### <span style="color: red;">Papers and Videos:</span> 

<button onclick="toggleVisibility('papers-shared-autonomy-section')" style="background-color: #f1f1f1; border: none; padding: 10px 20px; font-size: 16px; cursor: pointer; border-radius: 5px;">Show/Hide Papers and Videos</button>

<div id="papers-shared-autonomy-section" style="display: none; margin-top: 20px;">
    <figure style="max-width: 75%; margin: 0 auto; text-align: center;">
        <div class="video-wrapper" style="border-radius: 10px; overflow: hidden; width: 100%; height: auto; aspect-ratio: 16/9; margin: 0 auto; padding: 0;">
            <video width="100%" height="100%" autoplay muted loop playsinline style="object-fit: cover; display: block; margin: 0; padding: 0;">
                <source src="/research_media/safer_splat2024.mp4" type="video/mp4">
                Your browser does not support the video tag.
            </video>
        </div>
        <figcaption style="margin-top: 10px;">
            <a href="https://chengine.github.io/safer-splat/" target="_blank">SAFER-Splat: Safety with Control Barrier Functions in Online Gaussian Splatting Maps</a>
        </figcaption>
    </figure>
</div>

---

## **<u>Collaboration from Observation: Human-Robot Cooperative Transport</u>**

### Description:
In this project, we investigated how a robot could learn to collaborate with a human by observing two humans work together in a data-driven approach. We studied this in the context of cooperatively transporting an object, generative models are able to capture human-teammate behavior conditioned on the state of the task and surrounding obstacles and can be transferred to the robot in a human-robot team. 


<div style="text-align: center;">
    <img src="/research_media/hrcc_concept.png" alt="Human robot cooperative transport" style="max-width: 100%; height: auto; border-radius: 10px; box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);">
</div>


<div class="video-wrapper" style="border-radius: 10px; overflow: hidden; width: 100%; height: auto; aspect-ratio: 16/9; margin: 0 auto; padding: 0;">
    <video width="100%" height="100%" autoplay muted loop playsinline style="object-fit: cover; display: block; margin: 0; padding: 0;">
        <source src="/papers/hrcc.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
</div>

#### <span style="color: red;">Papers and Videos:</span> 

<button onclick="toggleVisibility('papers-hrcc-section')" style="background-color: #f1f1f1; border: none; padding: 10px 20px; font-size: 16px; cursor: pointer; border-radius: 5px;">Show/Hide Papers and Videos</button>

<div id="papers-hrcc-section" style="display: none; margin-top: 20px;">
    <div style="text-align: center;">
        <figure>
            <iframe width="560" height="315" src="https://www.youtube.com/embed/w0Za1-5_i7c?si=EUumdBH_Ik06KIsQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
            <figcaption><a href="https://sites.google.com/view/diffusion-co-policy-hrc">Diffusion Co-Policy for Synergistic Human-Robot Collaborative Tasks</a></figcaption>
        </figure>
    </div>
    <div style="text-align: center;">
        <figure>
            <iframe width="560" height="315" src="https://www.youtube.com/embed/CqWh-yWOgeA?si=O71t2sRhO31WGtI4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
            <figcaption><a href="https://sites.google.com/view/cooperative-carrying">It Takes Two: Learning to Plan for Human-Robot Cooperative Carrying</a></figcaption>
        </figure>
    </div>
        <div style="text-align: center;">
        <figure>
            <iframe width="560" height="315" src="https://www.youtube.com/embed/lAFTWSGOi40?si=yaGXSefU4gA53Ls5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
            <figcaption><a href="https://repository.upenn.edu/entities/publication/3befc894-2c95-4279-b09d-d2973ae6ffe0">Modeling And Control For Robotic Assistants: Single And Multi-Robot Manipulation</a></figcaption>
        </figure>
    </div>
</div>



---

