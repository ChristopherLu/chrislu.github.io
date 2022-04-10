---
layout: page
permalink: /research/
title: research
description: Ongoing and completed research projects
nav: true
navigation_weight: 15
---

<!-- **Overview:** During my PhD, I was a **Machine Learning Research Intern** at <a href="https://www.microsoft.com/en-us/research/lab/microsoft-research-cambridge/">Microsoft Research Cambridge </a> (Summer 2019) where I was supervised by <a href="https://www.tschiatschek.net/">Dr. Sebastian Tschiatschek</a>. I was a **NLP Intern** at <a href="https://www.apple.com/uk/siri/">Apple Siri Cambridge</a> (Summer 2017) where I was supervised by <a href="https://www.linkedin.com/in/thomas-voice-a67b9ab9/">Dr. Thomas Voice</a>. -->

---
## **Robust Spatial Perception for Autonomous Vehicles in the Wild**

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/av.png" title="Example Submodular Settings" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

Autonomous driving, aka. mobile autonomy, promises to radically change the cityscape and save many human lives. A pillar component for achieving mobile autonomy is **spatial perception - the ability for vehicles to perceive the ambient environment and position themselves on the road**. Thanks to the recent advances in computer vision and solid-state technology, great improvement in spatial perception has been witnessed in controlled environments. Nevertheless, the perception robustness of many systems is still far from meeting the safety requirement of autonomous driving when it comes to the wild condition, such as bad weather, unfavourable illumination and massive dynamic objects. In the MAPS lab, we study the robust spatial perception problems in full-stack, ranging from the single-modality based methods to multi-sensory fusion, and to the perception uncertainty quantification. More recently, a traction to my lab is unfolding the potential of **4D automotive radar in localization and scene understanding**. As an emerging sensor, automotive radars are reputable for their sensing robustness against bad weather and adverse illumination. However, due to their significantly lower data quality, it remains largely unknown how one can transform the radar sensing robustness to vehicle perception effectiveness - a question my lab aims to answer. 

<!-- 
Automotive radars, aka. single-chip mmWave radars, have been long known for their sensing robustness against bad weather and adverse illumination conditions, lending themselves one of the essential sensors on autonomous vehicles. Benefited from the increasingly advanced CMOS technology, today's automotive radars start coming with smaller form factors (e.g., palm-size), lower cost (< $100) and richer measurements (3D spatial + Doppler). We are keen to unfold the full potential of **4D automotive radar in localization and scene understanding**, and work on AI-empowered solutions to transform radar sensing robustness to perception effectiveness.  -->

Research Output: [<a href="https://arxiv.org/abs/2203.01137">RaFlow(pre-print)</a>], [<a href="https://arxiv.org/abs/2203.01137">STUN(pre-print)</a>], [<a href="https://intranet.csc.liv.ac.uk/~ramdrop/autoplace.html">ICRA'2022a</a>], [<a href="https://qqqgpe.github.io/2022-02-11/DC-Loc">ICRA'2022b</a>], [<a href="https://arxiv.org/abs/1912.13077">TNNLS'2022</a>], [<a href="http://arxiv.org/abs/1909.03557">AAAI'2020</a>], [<a href="http://openaccess.thecvf.com/content_CVPR_2019/html/Chen_Selective_Sensor_Fusion_for_Neural_Visual-Inertial_Odometry_CVPR_2019_paper.html">CVPR'2020</a>], 

---
## **Robust and Rapid Spatial Awareness Support for First Responders**

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/firefighters.png" title="Example Submodular Settings" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<!-- <div class="caption">
    Example Submodular Settings
</div> -->

From the equator to the Arctic, fire disasters are going to happen more often as a result of anthropogenic climate change. This consequently results in more frequent duty calls of firefighters. However, at the present, firefighting is still regarded as one of the most strenuous and dangerous jobs in the world. A fire incident is often accompanied by a variety of airborne obscurants (e.g., smoke and dust) and poor illumination, making firefighters difficult to navigate themselves and understand the fire ground. We aim to design robust yet real-time **localization, mapping and scene understanding** services that can be directly integrated into the **augmented reality wearables and firefighting robots**. These support systems will, in turn, enhance firefighters' operational capacity and safety in visually-degraded conditions and on resource-constrained platforms.

Research Output: [<a href="https://arxiv.org/abs/2104.07196">TR-O'2022</a>], [<a href="https://arxiv.org/pdf/2112.05665.pdf">CPS-ER'2022</a>], [<a href="https://ieeexplore.ieee.org/document/9561738">ICRA'2021</a>], [<a href="https://arxiv.org/abs/2006.02266">SenSys'2020a</a>], [<a href="https://arxiv.org/abs/1911.00398">MobiSys'2020b</a>], [<a href="https://ieeexplore.ieee.org/document/8968430">RA-L'2020</a>]

---
## **AI-empowered, Privacy-respectful Indoor Localization**

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/ips.png" title="Example Submodular Settings" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

Indoor positioning systems (IPS) enable locating the position of objects or people within buildings. Since GPS is unreliable in interior spaces due to the non-line-of-sight to GPS satellites, an IPS must use other positioning methods. Despite a plethora of methods being proposed in the last decades, today's IPS still from the reliability issue in the wild or privacy concerns when cameras are used in domestic environments. On the other side of the problem, unlike designing localization methods for cameras, it is much more challenging for us to design intuitive algorithms for **privacy-respectful localization sensors, e.g., mmWave, WiFi, UWB, BLE and inertial measurement units** - as humans do not use these modalities to navigate ourselves, nor relate our everyday experience in algorithm development for them. By exploiting the recent advances in machine learning, we advocate **AI-empowered methods** to model these underdog sensory data and push their localization limits in indoor environments. Another question of our interest is - how to combine multiple non-visual sensors for the sake of privacy yet achieve the accuracy level of visual localization? 

Research Output: [<a href="https://arxiv.org/abs/2103.01055">ICCV'2021</a>], [<a href="https://ieeexplore.ieee.org/document/8937008">TMC'2021</a>], [<a href="https://ieeexplore.ieee.org/document/9547669">TNNLS'2021</a>], [<a href="https://ieeexplore.ieee.org/document/8402111">TMC'2019</a>], [<a href="https://doi.org/10.1609/aaai.v33i01.33018009">AAAI'2019</a>], [<a href="https://doi.org/10.1109/DCOSS.2019.00028">DCOSS'2019</a>], [<a href="http://arxiv.org/abs/1802.02209">AAAI'2018</a>], [<a href="http://www.cs.ox.ac.uk/files/10769/%5BMobiCom2018%5Demr_slam.pdf">MobiCom'2018</a>], [<a href="https://doi.org/10.1109/TWC.2015.2487963">TWC'2016</a>]

---
## **Robust Identity Inference across Digital and Physical Worlds (completed)**

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/id_inference.png" title="Example Submodular Settings" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

Key to realizing the vision of human-centred computing is the ability for machines to recognize people, so that spaces and devices can become truly personalized. However, the unpredictability of real-world environments impacts robust recognition, limiting usability. In real conditions, human identification systems have to handle issues such as out-of-set subjects and domain deviations, where conventional supervised learning approaches for training and inference are poorly suited. With the rapid development of Internet of Things (IoT), we advocate a new labelling method that exploits signals of opportunity hidden in heterogeneous IoT data. The key insight is that **one sensor modality can leverage the signals measured by other co-located sensor modalities to improve its own labelling performance**. If identity associations between heterogeneous sensor data can be discovered, it is possible to automatically label data, leading to more robust human recognition, without manual labelling or enrolment. On the other side of the coin, we also study the privacy implication for such cross-modal identity association.

Research Output: [<a href="https://arxiv.org/abs/2001.08211">WWW'2020</a>], [<a href="https://arxiv.org/abs/1908.09002">WWW'2019</a>], [<a href="https://ieeexplore.ieee.org/document/8755294">IoT-J'2019</a>], [<a href="https://arxiv.org/abs/1912.04836">UbiComp'2018</a>], [<a href="https://dl.acm.org/doi/10.1145/3267242.3267252">ISWC'2018</a>], [<a href="https://dl.acm.org/doi/10.1145/3055031.3055073">IPSN'2017</a>]