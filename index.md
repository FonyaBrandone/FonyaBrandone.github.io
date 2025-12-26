---
layout: default
title: Brandone Fonya
description: Brandone Fonya's website
---

<!-- Font pairing: modern academic style -->
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=Merriweather:wght@300;400;700&display=swap" rel="stylesheet">

<!-- Base styles -->
<style>
  body {
    font-family: 'Inter', sans-serif;
    background-color: #fafafa;
    color: #1e1e1e;
    line-height: 1.7;
    margin: 0;
    padding: 0;
    display: block;
    margin-left: auto;
    margin-right: auto;
  }

  .container {
    max-width: 900px;
    margin: 0 auto;
    padding: 2rem 1.5rem;
  }

  h1, h2, h3 {
    font-family: 'Merriweather', serif;
    color: #111;
    margin-bottom: 0.4rem;
  }

  h1 {
    font-size: 2.4rem;
    font-weight: 700;
    margin-top: 0;
  }

  h2 {
    border-bottom: 2px solid #e5e5e5;
    padding-bottom: 0.4rem;
    margin-top: 2.5rem;
  }

  a {
    color: #0056d6;
    text-decoration: none;
    transition: color 0.2s ease;
  }

  a:hover {
    color: #003a8c;
    text-decoration: underline;
  }

  p {
    margin-bottom: 1rem;
    font-weight: 400;
  }

  .header {
    display: flex;
    align-items: center;
    justify-content: space-between;
    flex-wrap: wrap;
  }

  .profile-img {
    width: 140px;
    height: 140px;
    border-radius: 50%;
    object-fit: cover;
    border: 2px solid #ddd;
    box-shadow: 0 3px 6px rgba(0,0,0,0.1);
  }

  .header h3 {
    font-weight: 400;
    font-size: 1.1rem;
    margin-top: 0.3rem;
    color: #444;
  }

  .links a {
    margin-right: 0.5rem;
  }

  ul {
    padding-left: 1.2rem;
  }

  li {
    margin-bottom: 0.5rem;
  }

  .research-item, .project-item, .work-item, .education-item {
    display: flex;
    gap: 1.5rem;
    margin: 1.5rem 0;
    align-items: flex-start;
  }

  .research-img, .work-img, .education-img {
    width: 120px;
    height: auto;
    border-radius: 12px;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
  }

  .research-content, .work-content, .education-content {
    flex: 1;
  }

  footer {
    text-align: center;
    font-size: 0.9rem;
    color: #777;
    margin-top: 3rem;
    border-top: 1px solid #eaeaea;
    padding-top: 1rem;
  }

  /* Responsive adjustments */
  @media (max-width: 700px) {
    .header {
      flex-direction: column;
      text-align: center;
    }
    .profile-img {
      margin-top: 1rem;
    }
    .research-item, .work-item, .education-item {
      flex-direction: column;
      align-items: center;
    }
    .research-img, .work-img, .education-img {
      width: 100%;
      max-width: 400px;
    }
  }
</style>

<link href="/static/css/styles.css" rel="stylesheet">

<div class="container">
  <header class="header">
    <div>
      <h1>Brandone Fonya</h1>
      <h3><i>MEng. Artificial Intelligence</i></h3>
    </div>
    <img src="/static/profile.jpg" alt="Portrait of Brandone Fonya" class="profile-img"/>
  </header>

  <section class="about">
    <p>I am a graduate research assistant and a final year Masters student in Engineering Artificial Intelligence at <a href="https://engineering.cmu.edu/">Carnegie Mellon University's College of Engineering</a>, specializing in machine learning and computer vision. My research focuses on deep learning for medical imaging and healthcare. Before CMU, I earned a Bachelor's (Hons) in Software Engineering from <a href="https://ictuniversity.org/">The ICT University</a>, Cameroon (May 2024), graduating first in my department. I also obtained a Higher National Diploma (HND) in 2022, ranked 3rd nationwide in Software Engineering. Currently, I work with <a href="http://www.africa.engineering.cmu.edu/upanzi">Upanzi Network</a> on generative models for precision oncology in Africa, integrating multi-omics, clinical, and environmental data using Variational Autoencoders (VAE), Bayesian networks, and diffusion models.</p>

    <p>Beyond research, I enjoy traveling, reading, and watching documentaries.</p>

    <div class="links">
      <a href="/static/Brandone Fonya CV - Fall (Nov) 2025.pdf">CV</a> | 
      <a href="https://scholar.google.com/citations?user=bBsCFWUAAAAJ&hl=en">Google Scholar</a> |
      <a href="https://orcid.org/0009-0004-5793-9323">ORCID</a>
    </div>
  </section>

  <section class="contact">
    <h2>Contact</h2>
    <p><strong>Email:</strong> bfonya@andrew.cmu.edu</p>
    <div class="links">
      <a href="https://www.linkedin.com/in/brandone-fonya-217654240/">LinkedIn</a> | 
      <a href="https://github.com/fonyabrandone">GitHub</a> | 
      <a href="https://twitter.com/princebrandone">Twitter (X)</a>
    </div>
  </section>

  <section class="updates">
    <h2>Recent Updates</h2>
    <ul>
      <li><strong>12/2025</strong> – Made the news, Carnegie Mellon University spotlighted my research journey to China. <a href="https://www.africa.engineering.cmu.edu/news/2025/12/3-fonya-feature.html">Read here</a></li>

      <li><strong>09/2025</strong> – Started role as Graduate Teaching Assistant for <a href="https://courses.ece.cmu.edu/18751">(18-751) Applied Stochastic Processes</a>, Fall 2025</li>

      <li><strong>08/2025</strong> – Highlights of my summer research at AutoLab, China. <a href="https://mp.weixin.qq.com/s/C5NlUEWbFy9yRJGseO3iog">More here</a></li>
      
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
    <p>I am committed towards research that ensures that AI benefits the society, specifically in the healthcare sector. I am focused on developing efficient deep learning models for computer vision applications with particular interest in medical imaging and analysis. My long-term goal is to build intelligent systems that can perceive, understand and continually learn from the ever-changing dynamics of the world we live in</p>

    <div class="research-item">
      <img src="/static/workflow.png" alt="EEG Brain decoding" class="research-img"/>
      <div class="research-content">
        <h3><a href="https://baimamboukar.github.io/eeg-decoding-web/" target='_blank'>Zero-Shot Neural Priors for Generalizable Cross-Subject and Cross-Task EEG Decoding</a></h3>
        <p><em>Baimam Boukar, *Brandone Fonya, Nchofon Tagha, Pauline Nyaboe</em><br>
        <i><a href="https://baimamboukar.github.io/eeg-decoding-web/">Project website</a></i></p>
        <p>Our project develops a zero-shot EEG decoding framework that learns subject and task-invariant neural priors from large-scale HBN data. This approach enables robust cross-subject generalization and zero-shot transfer to unseen cognitive tasks without any subject-specific calibration. The work advances scalable EEG-based biomarkers and supports next-generation applications in computational psychiatry and adaptive brain-computer interfaces</p>
      </div>
    </div>

    <div class="research-item">
      <img src="/static/heatmap.png" alt="Health Facility Distribution" class="research-img"/>
      <div class="research-content">
        <h3><a href="https://github.com/FonyaBrandone/MBDA_Research" target='_blank'>Optimizing healthcare facility distribution in Rwanda: a data-driven approach</a></h3>
        <p><em>*Brandone Fonya, Irene Busah, Michaella Rugumbira, Nchofon Tagha, Emily Aiken</em><br>
        Accepted at <a href="https://ephconference.eu/app/programme/programme.php?d=displays">European Public Health Conference 2025</a><br><i><a href="https://academic.oup.com/eurpub/article/35/Supplement_4/ckaf161.1554/8302027">Journal Article</a></i></p>
        <p>This paper analyzed health facility distribution in Rwanda relative to disease prevalence (malaria, tuberculosis, HIV) using geospatial mapping and machine learning to propose equitable resource allocation strategies. In this paper we showed that allocating healthcare facilities (Hospitals, reseasrch centers, clinics, pharmacies) relative to population distribution and density does not meet the need compared to using disease prevalence. We ended up by building and comparing regression models able at predicting healthcare facility needs in various districts of Rwanda, our case study</p>
      </div>
    </div>

    <div class="research-item">
      <img src="/static/medblipnet3d_pipeline.png" alt="MedBLIPNet3D" class="research-img"/>
      <div class="research-content">
        <h3><a href="https://github.com/FonyaBrandone/medblipnet3d/"  target='_blank'>MedBLIPNet3D: Text Prompt-Guided Vision-Language Model for 3D MRI Prostate Segmentation</a></h3>
        <p><em>*Brandone Fonya, Kaicheng Yu</em><br>
        <i><a href="https://arxiv.org">arXiv preprint (coming soon)</a></i></p>
        <p>A novel framework for text prompt guided 3D medical image segmentation, evaluated on cross-site 3D prostate MRI data using Dice score and Hausdorff distance as evaluation metric. Our framework combined both visual and text encodings from our encoder layers through our architecture. Both encodings were fused via cross-fusion, achieving a single encoded feature matrix passed to the decoder to generate segmentation mask over the region of interest.</p>
      </div>
    </div>

    <div class="research-item">
      <img src="/static/tb-screening-cough.gif" alt="Tuberculosis Screening" class="research-img"/>
      <div class="research-content">
        <h3>Low-Cost Tuberculosis Screening with Deep Learning Using Solicited Cough Sounds</h3>
        <p><em>Carnegie Mellon-Africa – MakCHS Joint Research</em><br>
        <i>arXiv preprint - (coming soon)</i></p>
        <p>Explores audio-only and multimodal approaches for non-invasive Tuberculosis screening using cough audio recodings together with Clinical and Demographic data, targeting early detection in low-resource settings. We are building Web/Mobile together with IOT systems to implement the solution in resource constraint settings.</p>
      </div>
    </div>

    <div class="research-item">
      <img src="/static/cancer-medical-imaging.gif" alt="Adversarial Attacks" class="research-img"/>
      <div class="research-content">
        <h3>CAM-FD: Improving Adversarial Robustness without Sacrificing Generalization in Medical Imaging</h3>
        <p><em>*Brandone Fonya, Denis Musinguzi, Prasenjit Mitra</em><br>
        <i>Masters Capstone (In progress)</i></p>
        <p>Developing a practical training framework called CAM-FD, a Curriculum Adversarial Mixup with Feature Denoising framework while exploring other approaches for Robust and Generalizable Medical Imaging. CAM-FD aims at increasing robustness to adversarial attacks on downstream medical imaging tasks while minimizing degradation in model generalization to unseen data and modalities.</p>
      </div>
    </div>

    <div class="research-item">
      <img src="/static/pesdestrian-modeling.gif" alt="Autonomous Driving" class="research-img"/>
      <div class="research-content">
        <h3><a href="https://drive.google.com/file/d/1wT99_8svqf21GBSp--bEycTQ9OksaFJ3/view"  target='_blank'>Uncertainty-Aware Autonomous Driving in African Cities</a></h3>
        <p><em>Victor Miene, *Brandone Fonya, Joshua Momo, Ozan Tonguz</em><br>
        <strong><a href='https://drive.google.com/file/d/1wT99_8svqf21GBSp--bEycTQ9OksaFJ3/view?usp=sharing&usp=embed_facebook' target='_blank'>preprint</a></strong>
        <i>Spring 2025 - Course Research</i></p>
        <p>Our study developed a pipeline to quantify uncertainty-aware driving scenarios using pedestrian visual cues in dense traffic and highly chaotic cities around Africa. We were focused on modeling a cross and not cross intent of pedestrians at any point in time. Using ConvLSTM and other architectures we model pedestrian behaviors in unstructured urban environments, enabling behaviorial planning for autonomous vehicles.</p>
      </div>
    </div>
  </section>

  <section class="projects">
    <h2>Projects</h2>
    <div class="project-item">
      <h3>Real-Time Sign Language Gestures to Speech Transcription using Deep Learning</h3>
      <p><em>Supervised by <a href="https://insights.sei.cmu.edu/authors/clarence-worrell/">Clarence Worrell</a></em><br>
      Uses CNNs and Mediapipe for real-time ASL gesture recognition and text-to-speech conversion.<br>
      <em>January 2025 - May 2025</em> | <a href="https://arxiv.org/abs/2508.12713v1">arXiv preprint</a> | <a href="https://github.com/FonyaBrandone/Sign-language-project-deep-learning">code</a></p>
    </div>
    <div class="project-item">
      <h3>Eschools LMS</h3>
      <p>Online learning platform for crisis-affected Cameroonian students, featuring AI study bots and live classes.<br>
      <em>December 2022 - July 2024</em> | <a href="https://eschools.netlify.app/">website</a></p>
    </div>
    <div class="project-item">
      <h3>ClimateSmart: AI driven Smart Agriculture application</h3>
      <p>Provides data-driven farming recommendations based on location and environmental data.<br>
      <em>December 2023 - May 2024</em> | <a href="https://climatesmart.000webhostapp.com/">website</a></p>
    </div>
  </section>

  <section class="work-experience">
    <h2>Work Experience</h2>
    <div class="work-item">
      <img src="/static/cylabafrica_logo.jpg" alt="Upanzi Network logo" class="work-img"/>
      <div class="work-content">
        <h3>Research Intern, Upanzi Network</h3>
        <p>Upanzi Network (Part-time)<br>
        Supervisor: <a href="https://ece.cmu.edu/directory/bios/gueye-assane.html">Assane Gueye</a><br>
        <em>September 2025 - Present</em></p>
      </div>
    </div>
    <div class="work-item">
      <img src="/static/westlake-logo.jpg" alt="Westlake Logo" class="work-img"/>
      <div class="work-content">
        <h3>Research Intern, Autonomous Intelligence Lab</h3>
        <p>Westlake University (Full-time)<br>
        Supervisor: <a href="https://www.yukaicheng.cn/">Kaicheng Yu</a><br>
        <em>July 2025 - September 2025</em></p>
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
    <p>I am currently serving as a graduate teaching assistant for CMU Engineering’s graduate level ECE course, (18-751) Applied Stochastic Processes (https://courses.ece.cmu.edu/18751), for Fall 2025.
    My roles include: Grading assignments and exams to assess student performance, Holding weekly office hours, lead recitations solving set of exercises and problems, Helping students understand the course concepts and problems.</p>
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




<!-- 
---
layout: default
title: Brandone Fonya
description: Brandone Fonya's website
---

<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&family=Merriweather:wght@300;400;700&display=swap" rel="stylesheet">

<link href="/static/css/styles.css" rel="stylesheet">

<div class="container">
  <header class="header">
    <h1>Brandone Fonya <br><i>MEng. Artificial Intelligence</i></h1>
    <img src="/static/profile.jpg" alt="Brandone Fonya" class="profile-img"/>
  </header>

  <section class="about">
    <p>I am a graduate research assistant and a final year Master student in Engineering Artificial Intelligence at <a href="https://engineering.cmu.edu/">Carnegie Mellon University's College of Engineering</a>, specializing in machine learning and computer vision. My research focuses on deep learning for computer vision and their applications in medical imaging and healthcare. Prior to CMU, I earned a Bachelor's degree (Hons) in Software Engineering from <a href="https://ictuniversity.org/">The ICT University</a> in Cameroon (May 2024), graduating first in my department. I also had my Higher national diploma (HND) in July 2022, ranked overall 3rd best in Cameroon for Software Engineering. I am currently working with <a href="http://www.africa.engineering.cmu.edu/upanzi">Upanzi Network</a> AI research team on advancing precision oncology through a generative pipeline for breast cancer generation for Africa. Our work integrates multi-omics, clinical and environmental data from Africa for a larger synthetic dataset generation using Variational Autoencoders (VAE), Bayesian networks and diffusion models.</p>

    <p>Beyond work, I enjoy traveling, reading, and watching documentaries.</p>

    <div class="links">
      <a href="/static/Brandone Fonya CV - Fall 2025.pdf">CV</a> | 
      <a href="https://orcid.org/0009-0004-5793-9323">Google Scholar</a> |
      <a href="https://orcid.org/0009-0004-5793-9323">ORCID</a>
    </div>
  </section>

  
  <footer>© Brandone Fonya | Last updated: August 2025</footer>
</div> -->