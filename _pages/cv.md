---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.S. in Computer Engineering,**Northwestern University**, Evanston, IL, United States  2023 - 2025(expected)
* B.S. in Mathematics and Physics Fundamentals, **Tsinghua University**, Beijing, China  2018 - 2022

Research experience
======
### Research Assistant, Northwestern University Seda Ogrenci Lab – Evanston, IL  
**Jan 2024 – Present**

- Conducted research on the development of an open-source design automation tool aimed at supporting neural network (NN) hardware design, utilizing HLS4ML within the Vitis Unified IDE for experimental purposes.
- Focused on optimizing hardware resource utilization by linearizing activation layers (e.g., replacing nonlinear functions such as exponential and tanh) and enforcing resource sharing across layers.
- Investigated the potential benefits of linearization in enhancing hardware resource sharing, particularly in environments with limited FPGA resources.
- Explored how this approach could make it feasible to implement highly computational neural networks on small FPGA boards, providing a potential solution for resource-constrained hardware designs.
  
### Research Assistant, Professor Jiancheng Ye, Cornell University (Remote)
**Aug 2024 - Present**

- Modify the MedSAM model by freezing the prompt encoder and focusing on training the image encoder and mask decoder for automatic segmentation of 3D medical images. This modification optimizes model performance while reducing computational overhead, enabling more efficient and accurate segmentation of anatomical structures from multi-organ CT datasets.

### Software Engineer Intern, VMware – Beijing, China  
**Aug 2022 – May 2023**

- Developed an end-to-end YOLO V5 API for water meter detection, improving task efficiency by 20% on Kubeflow.
- Deployed object detection and image classification models on Kubernetes deep learning containers.
- Designed a tool to transform raw ancient Chinese text into unified LaTeX format with original text, translation, and notation, improving efficiency by approximately 30% using Hugging Face's language model.

### Research Assistant, Professor Lucia Specia, Imperial College London – London, Britain  
**Jan 2021 – Aug 2021**

- Developed HIMA-Net, a self-attention-based model for humor detection, combining 1D-CNN and Bi-directional LSTM with attention to improve accuracy in short text humor prediction.
- Led the integration of BERT tokenizer for text encoding and implemented CNN for extracting key humor-related features, followed by Att-BLSTM for global context understanding.
- Achieved up to 15% higher accuracy across three datasets (Headlines, Pun of the Day, Short Jokes) compared to traditional models (CNN, BLSTM), and notable improvements in precision and recall for humor classification tasks.

### Research Assistant, Tsinghua University the Future Laboratory – Beijing, China  
**Sep 2020 – Jul 2021**

- Worked on the topic of Educational and Entertainment Application of Swarm Robotics. Enhanced car obstacle avoidance functionality using a potential field algorithm, achieving a 20% reduction in errors.
- Implemented a GUI for easy controlling. Optimized the obstacle avoidance algorithm by 20%.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Projects
======

### [PurplePlace: An app designed for finding student housing](https://purple-place-1d5d9.web.app/)
- Developed a React-based application enabling efficient student housing searches with features such as dynamic sorting, filtering, posting/viewing reviews by verified users, and Google Maps integration.
- Implemented a Firebase backend for real-time data handling and user authentication, ensuring responsive and personalized user experiences across various devices.

### [Streamlytics](https://streaming-trends-ai.web.app/)
- Contributed to the development of a dynamic web application designed for internet advertising agencies, providing comprehensive tools for analyzing viewer sentiments and comments on major streaming platforms such as Paramount+.
- Led the backend development, focusing on web scraping movie reviews from various review platforms to collect and analyze user feedback in real-time.
- Integrated GPT API to power the AI assistant, enabling sentiment analysis, engagement tracking, and summarization of viewer comments to assist advertising agencies in optimizing their strategies.

### [AutoPod: An AI-powered Podcast Generator](https://github.com/bugman1215/podcastpage)
- Developed a Starlette-based app with Python, JavaScript, HTML, and CSS utilizing Text to Audio APIs for producing high-quality podcast recordings with only brief descriptions of the podcast.
- Applied GPT-4 for script generation and Eleven Labs for flexible speaker selection with conversational features.

### Wireless Communication Exhibit: An interactive science exhibit for children, Oakton Elementary School, Evanston, IL
- Led the design and implementation of an interactive science exhibit focused on teaching children between 2nd to 6th grade the concepts of radar, sonar, and echolocation.
- Developed three main components: a "Where’s Waldo" style radar/sonar identification game, a sonar chamber using tubes and bells to simulate echolocation, and a "Batvision" walking stick equipped with an ultrasonic sensor and Arduino for obstacle detection.
- Integrated user feedback and testing, achieving high engagement and understanding of wireless communication concepts among students.

### [Unity Game Dev Projects](https://github.com/bugman1215/maze)
- Developed several games including Pac-Man, Angry Birds, pool, dodgeball, flight simulation, etc.
- Built interaction systems using Unity3D and Oculus Quest, applying hand gestures for controlling input and response design.

---

Technical Skills
======
**Languages**: Python, C++, C#, HTML, CSS, Verilog  
**Operating Systems**: Linux, Windows, Kubernetes  
**Frameworks and Libraries**: React, Tensorflow, PyTorch  
**Tools**: Git, MATLAB, Mathematica, Unity, Vitis HLS

---

Service and Leadership
======

### Olympics Family Assistant, 2022 Beijing Winter Olympics  
**Feb 2022**
- Coordinated transportation for IOC members and volunteers, ensuring smooth operations throughout the event.

### Head of Publicity and Arts, Student Union, Tsinghua University  
**Sep 2019 – Dec 2020**
- Trained and organized over 20 team members, producing media content for events with over 1000 attendees.
- Managed backstage operations and coordinated with multiple departments for live performances.

### Head Teaching Assistant, Huangcao Elementary School, Chongqing, China  
**Jul 2019**
- Led a team of 15 volunteer teachers to conduct a teaching program at Huangcao Primary School, located in one of Chongqing’s 75 designated poverty-stricken villages.
- Organized and delivered well-prepared, educational, and enriching courses to the students, addressing both academic and personal development.
- Conducted home visits to families of economically disadvantaged students, investigating living conditions and liaising with district officials to discuss poverty alleviation strategies.

### Wigs, Hair & Makeup Designer, Department of Theatre, Northwestern University  
**Oct 2023 – Present**
- Assisted as a makeup designer in musical productions under the theater department, including Kinky Boots, Little Mermaid, and Rodgers + Hammerstein's Cinderella, with a total audience of over 10,000.

### Photographer, Campus Events & Freelance Portraits, Beijing, China  
**Sep 2018 – Jun 2023**
- Volunteered as a photographer for various campus events throughout undergraduate studies.
- Worked as a freelance photographer with a focus on portrait photography, building a portfolio and working with diverse clients via social media.




<!-- Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul> -->
  

