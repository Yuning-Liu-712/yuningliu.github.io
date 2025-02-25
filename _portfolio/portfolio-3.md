---
title: "Project 3: Digital well-being designs of social media platforms"
excerpt: "Applying LLM-assisted content analysis for 4,000+ social media platform news releases on digital well-being practices, we found most practices lack harm identification and impact evaluation, focusing on content moderation rather than addressing harmful design features"
collection: portfolio
---

- Collaborator: [Prof. Kasisomayajula (Vish) Viswanath](https://hsph.harvard.edu/profile/kasisomayajula-viswanath/), [Dr. Ravi Iyer](https://www.polipsych.com/), [Emily Xing](https://emxing.netlify.app/), [Stanley Huang](https://www.linkedin.com/in/stanley-huang-b8471b1bb/) 
- [Postor](https://drive.google.com/file/d/1cIRa7wQenqGiVQjdFasQdXzGtGP0smxf/view?usp=sharing)

- Abstract: 
  - Background: Adolescent mental health crises and regulations have prompted social media platforms to adopt digital well-being practices, yet systematic research on these practices remains limited. We propose the Harm-Responsive Design Process to evaluate platform well-being strategies through social media news releases.
  - Method: We collected all news releases related to digital well-being, safety, and privacy from Meta, TikTok, YouTube, Snapchat, and Twitter/X, totaling over 4,500 news releases. We developed an LLM-assisted content analysis pipeline with a codebook designed following the Harm-Responsive Design Process framework. The pipeline employs few-shot prompting for 15 content analysis tasks, including deductive classification, named entity recognition, text summarization, and inductive thematic analysis. Performance was assessed through comparisons between human coders and the machine coder.
  - Result: GPT-4o performed well for most tasks but underperformed with identifying distinct digital well-being practices and their targeted harms. Alternative methods, including supervised learning, fine-tuning GPT, and active learning, are in development for the underperformed tasks. Among 1,000 randomly sampled news releases, 735 distinct digital well-being practices were identified. However, 32% lacked harm specification, and 81% had no evaluation plans. Most practices focus on content moderation and promoting positive content rather than addressing design features linked to user harms. The LLM pipeline refinement and analysis of remaining news releases are ongoing and will be updated soon.
  - Implication: This study demonstrates the potential of LLMs in multidimensional content analysis and highlights the need for a harm-responsive approach to ensure platform interventions (1) address harmful design elements and (2) conduct systematic impact evaluation.
