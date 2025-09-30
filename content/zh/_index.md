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
      #   text: 下载简历
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
      title: 研究成果
      text: |
        ### [DexFlyWheel: A Scalable and Self-improving Data Generation Framework for Dexterous Manipulation](https://arxiv.org/abs/2509.23829)
        **Kefei Zhu, Fengshuo Bai, YuanHao Xiang, Yishuai Cai, Xinglin Chen, Ruochong Li, Xingtao Wang, Hao Dong, Yaodong Yang, Xiaopeng Fan, Yuanpei Chen**  
        *NeurIPS 2025 (Spotlight)* | 2025年9月
        
        提出了一个可扩展的数据生成框架，用于灵巧操作，通过自我改进循环不断丰富数据多样性。实验结果表明，在四个具有挑战性的任务中生成了超过2000个不同的演示，平均成功率达到81.9%。
        
        ---
        
        ### [DexGraspVLA: A Vision-Language-Action Framework Towards General Dexterous Grasping](https://dexgraspvla.github.io/)
        **Yifan Zhong, Xuchuan Huang, Ruochong Li, Ceyao Zhang, Zhang Chen, Tianrui Guan, Fanlian Zeng, Ka Nam Lui, Yuyao Ye, Yitao Liang, Yaodong Yang, Yuanpei Chen**  
        *arXiv preprint* | 2025年2月
        
        提出了一个分层的视觉-语言-动作框架，用于通用灵巧抓取。在数千个具有挑战性的未见场景中，实现了90%以上的抓取成功率，并首次同时展示了自由形式的长时间提示执行、对抗性对象的鲁棒性和人为干扰。
    design:
      columns: '1'
  # - block: skills
  #   content:
  #     title: 技能与爱好
  #     username: admin
  # - block: awards
  #   content:
  #     title: 奖项与证书
  #     username: admin
  # - block: languages
  #   content:
  #     title: 语言能力
  #     username: admin
---
