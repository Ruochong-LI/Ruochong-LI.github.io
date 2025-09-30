---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: '4rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: biography
    content:
      username: admin
      # Show a call-to-action button under your biography? (optional)
      # button:
      #   text: Download Resume
      #   url: uploads/resume.pdf
    design:
      banner:
        # Upload your cover image to the `assets/media/` folder and reference it here
        filename: kalen-emsley-Bkci_8qcdvQ-unsplash.jpg
      biography:
        # Customize the style of your biography text
        style: 'text-align: justify; font-size: 0.8em;'
      # Avatar customization
      avatar:
        size: large # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: rounded # Options: circle (default), square, rounded
  - block: experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
  - block: markdown
    content:
      title: Publications
      text: |
        ### [DexFlyWheel: A Scalable and Self-improving Data Generation Framework for Dexterous Manipulation](https://arxiv.org/abs/2509.23829)
        **Kefei Zhu, Fengshuo Bai, YuanHao Xiang, Yishuai Cai, Xinglin Chen, Ruochong Li, Xingtao Wang, Hao Dong, Yaodong Yang, Xiaopeng Fan, Yuanpei Chen**  
        *NeurIPS 2025 (Spotlight)* | September 2025
        
        A scalable data generation framework that employs a self-improving cycle to continuously enrich data diversity for dexterous manipulation. Experimental results demonstrate over 2,000 diverse demonstrations across four challenging tasks with an average success rate of 81.9%.
        
        ---
        
        ### [DexGraspVLA: A Vision-Language-Action Framework Towards General Dexterous Grasping](https://dexgraspvla.github.io/)
        **Yifan Zhong, Xuchuan Huang, Ruochong Li, Ceyao Zhang, Zhang Chen, Tianrui Guan, Fanlian Zeng, Ka Nam Lui, Yuyao Ye, Yitao Liang, Yaodong Yang, Yuanpei Chen**  
        *arXiv preprint* | February 2025
        
        A hierarchical Vision-Language-Action framework for robust generalization in language-guided dexterous grasping. Achieves 90%+ success rate across thousands of unseen cluttered scenes, with demonstrated capabilities in free-form long-horizon prompts, adversarial robustness, and human disturbance recovery.
    design:
      columns: '1'
  # - block: skills
  #   content:
  #     title: Skills & Hobbies
  #     username: admin
  # - block: awards
  #   content:
  #     title: Awards
  #     username: admin
  # - block: languages
  #   content:
  #     title: Languages
  #     username: admin
---
