---
layout: default
title: Brandone Fonya
description: Brandone Fonya's website
---

<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">
<link href="/static/css/styles.css" rel="stylesheet">

<div class="container">
  <header class="header">
    <h1>Brandone Fonya</h1>
    <img src="/static/profile.jpg" alt="Brandone Fonya" class="profile-img"/>
  </header>

  <section class="about">
    <p>I am a graduate research assistant and a final-year Master's student in Engineering Artificial Intelligence at <a href="https://engineering.cmu.edu/">Carnegie Mellon University's College of Engineering</a>, specializing in machine learning and computer vision. My research focuses on deep learning for computer vision and their applications in medical imaging and healthcare.</p>

    <p>Prior to CMU, I earned a Bachelor's degree (Hons) in Software Engineering from <a href="https://ictuniversity.org/">The ICT University</a> in Cameroon (May 2024), graduating first in my department. I also had my Higher national diploma (HND) in July 2022, ranked overall 3rd best in Cameroon for Software Engineering</p>

    <p>Beyond work, I enjoy traveling, reading, and watching documentaries.</p>

    <div class="links">
      <a href="/static/Brandone Fonya CV - Fall 2025.pdf">CV</a> | 
      <a href="https://orcid.org/0009-0004-5793-9323">Google Scholar</a> |
      <a href="https://orcid.org/0009-0004-5793-9323">ORCID</a>
    </div>
  </section>

  <section class="contact">
    <h2>Contact</h2>
    <p><strong>Email:</strong> bfonya@andrew.cmu.edu</p>
    <div class="links">
      <a href="https://www.linkedin.com/in/brandone-fonya-217654240/">LinkedIn</a> | 
      <a href="https://github.com/fonyabrandone">GitHub</a> | 
      <a href="https://twitter.com/princebrandone">Twitter</a>
    </div>
  </section>

  <section class="updates">
    <h2>Recent Updates</h2>
    <ul>
      <li><strong>09/2025</strong> – Started role as Graduate Teaching Assistant for <a href="https://courses.ece.cmu.edu/18751">(18-751) Applied Stochastic Processes</a>, Fall 2025</li>
      <li><strong>07/2025</strong> – Joined the <a href='https://westlake-autolab.github.io/' target='_blank'>Autonomous Intelligence Lab (AutoLab)</a> as a research intern under <a href="https://en.westlake.edu.cn/faculty/kaicheng-yu.html">Prof. Kaicheng Yu</a> at Westlake University, Hangzhou, China.</li>
      <li><strong>07/2025</strong> – Led the Carnegie Mellon-MakCHS research team meeting with Prof. Mary-Anne Hartley of <a href="https://www.light-laboratory.org/">LiGHT Laboratory</a> at EPFL, discussing <a href="https://ai.epfl.ch/ai-making-it-easier-to-diagnose-tuberculosis-in-sub-saharan-africa/">tuberculosis research</a>.</li>
      <li><strong>06/2025</strong> – Paper accepted for poster presentation at the <a href="https://ephconference.eu/">European Public Health Conference 2025</a>, Helsinki, Finland.</li>
      <li><strong>06/2025</strong> – Accepted to the <a href="https://dighum.kcrc.rw/">Digital Humanism Summer School 2025</a>.</li>
      <li><strong>06/2025</strong> – Attended the 2025 <a href="https://engineering.cmu.edu/afretec/index.html">Afretech</a> Network's Annual Conference in Kigali, Rwanda.</li>
      <li><strong>05/2025</strong> – Visited <a href="https://www.uct.ac.za/">University of Cape Town</a>, Africa's top-ranked university, to explore AI research.</li>
      <li><strong>04/2025</strong> – Roundtable discussion with <a href="https://www.gatesfoundation.org/about/leadership/trevor-mundel">Trevor Mundel</a>, President of Global Health at the Gates Foundation, on AI for African healthcare challenges.</li>
      <li><strong>02/2025</strong> – One-on-one with <a href="https://people.epfl.ch/mary-anne.hartley?lang=en">Prof. Mary-Anne Hartley</a> of LiGHT Laboratory at EPFL on AI tools for resource-constrained communities.</li>
      <li><strong>01/2025</strong> – Attended the <a href="https://events.dell.com/event/ce14c9e1-18e7-4347-aa04-f0e2ce851129/summary">Dell Technologies AI Forum 2025</a>, Dubai.</li>
    </ul>
  </section>

  <section class="research">
    <h2>Research</h2>
    <div class="research-item">
      <img src="/static/heatmap.png" alt="Health Facility Distribution" class="research-img"/>
      <div class="research-content">
        <h3><a href="https://github.com/FonyaBrandone/MBDA_Research" target='_blank'>Evaluating Health Facility Distribution and Disease Prevalence in Rwanda</a></h3>
        <p><em>*Brandone Fonya, Irene Busah, Michaella Rugumbira, Nchofon Tagha, Emily Aiken</em><br>
        <strong>Accepted for poster presentation at <a href="https://ephconference.eu/app/programme/programme.php?d=displays">European Public Health Conference 2025, under the <i>"Health services and systems research"</i> section</a></strong></p>
        <p>This paper analyzed health facility distribution in Rwanda relative to disease prevalence (malaria, tuberculosis, HIV) using geospatial mapping and machine learning to propose equitable resource allocation strategies. In this paper we showed that allocating healthcare facilities (Hospitals, reseasrch centers, clinics, pharmacies) relative to population distribution and density does not meet the need compared to using disease prevalence. We ended up by building and comparing regression models able at predicting healthcare facility needs in various districts of Rwanda, our case study</p>
      </div>
    </div>

    <div class="research-item">
      <img src="/static/medblipnet3d_pipeline.png" alt="MedBLIPNet3D" class="research-img"/>
      <div class="research-content">
        <h3><a href="https://github.com/FonyaBrandone/medblipnet3d/"  target='_blank'>MedBLIPNet3D: Text Prompt-Guided Vision-Language Model for 3D MRI Prostate Segmentation</a></h3>
        <p><em>*Brandone Fonya, Kaicheng Yu</em><br>
        <strong><a href="https://arxiv.org">Arxiv (Coming soon)</a></strong></p>
        <p>A novel framework for text prompt guided 3D medical image segmentation, evaluated on cross-site 3D prostate MRI data using Dice score and Hausdorff distance as evaluation metric. Our framework combined both visual and text encodings from our encoder layers through our architecture. Both encodings were fused via cross-fusion, achieving a single encoded feature matrix passed to the decoder to generate segmentation mask over the region of interest.</p>
      </div>
    </div>

    <div class="research-item">
      <img src="/static/tb-screening-cough.gif" alt="Tuberculosis Screening" class="research-img"/>
      <div class="research-content">
        <h3>Low-Cost Tuberculosis Screening with Deep Learning Using Solicited Cough Sounds</h3>
        <p><em>Carnegie Mellon-Africa – MakCHS Joint Research</em><br>
        <strong>Summer research - (In Progress)</strong></p>
        <p>Explores audio-only and multimodal approaches for non-invasive Tuberculosis screening using cough audio recodings together with Clinical and Demographic data, targeting early detection in low-resource settings. We are building Web/Mobile together with IOT systems to implement the solution in resource constraint settings.</p>
      </div>
    </div>

    <div class="research-item">
      <img src="/static/cancer-medical-imaging.gif" alt="Adversarial Attacks" class="research-img"/>
      <div class="research-content">
        <h3>CAM-FD: Improving Adversarial Robustness without Sacrificing Generalization in Medical Imaging</h3>
        <p><em>*Brandone Fonya, Denis Musinguzi, Prasenjit Mitra</em><br>
        <strong>Capstone - In progress</strong></p>
        <p>Developing a practical training framework called CAM-FD, a Curriculum Adversarial Mixup with Feature Denoising framework while exploring other approaches for Robust and Generalizable Medical Imaging. CAM-FD aims at increasing robustness to adversarial attacks on downstream medical imaging tasks while minimising degradation in model generalization to unseen data and modalities.</p>
      </div>
    </div>

    <div class="research-item">
      <img src="/static/pesdestrian-modeling.gif" alt="Autonomous Driving" class="research-img"/>
      <div class="research-content">
        <h3><a href="https://drive.google.com/file/d/1wT99_8svqf21GBSp--bEycTQ9OksaFJ3/view"  target='_blank'>Uncertainty-Aware Autonomous Driving in African Cities</a></h3>
        <p><em>Victor Miene, *Brandone Fonya, Joshua Momo, Ozan Tonguz</em><br>
        <strong>Spring 2025 - Course Research</strong></p>
        <p>Our study developed a pipeline to quantify uncertainty-aware driving scenarios using pedestrian visual cues in dense traffic and highly chaotic cities around Africa. We were focused on modeling a cross and not cross intent of pedestrians at any point in time. Using ConvLSTM and other architectures we model pedestrian behaviors in unstructured urban environments, enabling behaviorial planning for autonomous vehicles.</p>
      </div>
    </div>
  </section>

  <section class="projects">
    <h2>Projects</h2>
    <div class="project-item">
      <h3>Real-Time Sign Language Recognition and Speech Transcription</h3>
      <p><em>Supervised by <a href="https://insights.sei.cmu.edu/authors/clarence-worrell/">Clarence Worrell</a></em><br>
      Uses CNNs and Mediapipe for real-time ASL gesture recognition and text-to-speech conversion.<br>
      <em>January 2025 - May 2025</em> | <a href="http://arxiv.org/abs/2508.12713">arxiv</a> | <a href="https://github.com/FonyaBrandone/Sign-language-project-deep-learning">code</a></p>
    </div>
    <div class="project-item">
      <h3>ClimateSmart: Smart Agriculture</h3>
      <p>Provides data-driven farming recommendations based on location and environmental data.<br>
      <em>December 2023 - May 2024</em> | <a href="https://climatesmart.000webhostapp.com/">website</a></p>
    </div>
    <div class="project-item">
      <h3>Eschools LMS</h3>
      <p>Online learning platform for crisis-affected Cameroonian students, featuring AI study bots and live classes.<br>
      <em>December 2022 - July 2024</em> | <a href="https://eschools.netlify.app/">website</a></p>
    </div>
  </section>

  <section class="work-experience">
    <h2>Work Experience</h2>
    <div class="work-item">
      <img src="/static/westlake-logo.jpg" alt="Westlake Logo" class="work-img"/>
      <div class="work-content">
        <h3>Research Intern, Autonomous Intelligence Lab</h3>
        <p>Westlake University (Full-time)<br>
        Supervisor: <a href="https://www.yukaicheng.cn/">Kaicheng Yu</a><br>
        <em>July 2025 - Present</em></p>
      </div>
    </div>
    <div class="work-item">
      <img src="/static/cmu.png" alt="CMU Logo" class="work-img"/>
      <div class="work-content">
        <h3>Graduate Research Assistant, AI for Healthcare</h3>
        <p>Carnegie Mellon University (Full-time)<br>
        Supervisors: <a href="https://engineering.cmu.edu/directory/bios/tucker-conrad.html">Conrad Tucker</a>, <a href="https://scholars.cmu.edu/6761-edwin-mugume/publications">Edwin Mugume</a><br>
        <em>May 2025 - Present</em></p>
      </div>
    </div>
    <div class="work-item">
      <img src="/static/cmu.png" alt="CMU Logo" class="work-img"/>
      <div class="work-content">
        <h3>Graduate IT Associate - Full Stack Developer</h3>
        <p>Carnegie Mellon University (Part-time)<br>
        <em>August 2024 - May 2025</em></p>
      </div>
    </div>
  </section>

  <section class="education">
    <h2>Education</h2>
    <div class="education-item">
      <img src="/static/cmu.png" alt="CMU Logo" class="education-img"/>
      <div class="education-content">
        <h3>Carnegie Mellon University</h3>
        <p>Master of Science in Engineering Artificial Intelligence (MSEAI)<br>
        <em>August 2024 – May 2026 (Expected)</em></p>
      </div>
    </div>
    <div class="education-item">
      <img src="/static/ICTULogoNew.png" alt="ICTU Logo" class="education-img"/>
      <div class="education-content">
        <h3>The ICT University</h3>
        <p>Bachelor of Science (Hons) in Software Engineering<br>
        GPA: 3.65/4.0, Ranked 1st in Department<br>
        <em>September 2020 – May 2024</em></p>
      </div>
    </div>
  </section>

  <section class="teaching-service">
    <h2>Teaching & Service</h2>
    <ul>
      <!-- <li>Graduate Teaching Assistant, <a href="https://courses.ece.cmu.edu/18661">Introduction to Machine Learning for Engineers (18-661)</a>, under <a href="https://www.ece.cmu.edu/directory/bios/joe-wong-carlee.html">Carlee Joe-Wong</a>, <em>Fall 2025</em></li>
      -->
      <li>Graduate Teaching Assistant, <a href="https://courses.ece.cmu.edu/18751">(18-751)   Applied Stochastic Processes</a>, <em>Fall 2025</em></li>
      <li>Conference Reviewer, <a href="https://appliedmldays.org/">Applied Machine Learning Days (AMLD) Africa, 2026</a></li>
      <li>IEEE Student Member, <em>2024 - Present</em></li>
    </ul>
  </section>

  <footer>© Brandone Fonya | Last updated: August 2025</footer>
</div>