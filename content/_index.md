---
title: ''
summary: 'Wenlong Zhang is a Young Researcher at Shanghai AI Laboratory working on AI for Science, scientific foundation models, multimodal evaluation, and scientific agents.'
date: 2026-08-13
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      headings:
        about: ''
      recruitment:
        title: "Join Shanghai AI Lab's Elite Team!"
        text: "We're recruiting PhD candidates (2027/2028 intake) & Researchers (June 2026/March 2027 start) to pioneer Agent model, Agent evaluation, AI-Scientist, and Recursive self-improvement."
        contact: 'Contact now with your CV + research vision:'
        email: zhangwenlong@pjlab.org.cn
    design:
      name:
        size: sm
      avatar:
        size: medium
        shape: circle
  - block: collection
    id: news
    content:
      title: Recent news
      page_type: blog
      count: 6
      filters:
        exclude_featured: false
        exclude_future: false
        exclude_past: false
      order: desc
    design:
      view: date-title-summary
      spacing:
        padding: [0, 0, 0, 0]
  - block: collection
    id: papers
    content:
      title: Featured publications
      count: 12
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: featured-publications
      columns: 1
  - block: markdown
    id: service
    content:
      title: Academic service
      text: |-
        ## Conference reviewing

        - Computer Vision and Pattern Recognition (CVPR)
        - International Conference on Computer Vision (ICCV)
        - European Conference on Computer Vision (ECCV)
        - International Conference on Learning Representations (ICLR)
        - Advances in Neural Information Processing Systems (NeurIPS)
        - International Conference on Machine Learning (ICML)
        - AAAI Conference on Artificial Intelligence (AAAI)
        - International Joint Conferences on Artificial Intelligence (IJCAI)
        - Pattern Recognition and Computer Vision (PRCV)

        ## Journal reviewing

        - IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)
        - IEEE Transactions on Geoscience and Remote Sensing (TGRS)

        ## Teaching

        Teaching Assistant at The Hong Kong Polytechnic University:

        - COMP6708: Advanced Big Data Computing (Master Course)
        - COMP2121: E-Business (Undergraduate Course)
        - COMP5221: Software Project Management (Master Course)
        - COMP5523: Computer Vision and Image Processing (Master Course)
    design:
      columns: '1'
      spacing:
        padding: [2rem, 0, 2rem, 0]
---
