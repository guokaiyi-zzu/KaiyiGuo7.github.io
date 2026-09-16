---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

- **C7.** Jiale Zhang, Shufeng Yin, Lingxiao Yang, Jisu Yim, **<u>Kaiyi Guo</u>**, Yuxuan Miao, Daniel Vena, Pei Zhang, Yiyue Luo, Junyi Zhu, **SleepVibe: Sleep Stage Monitoring Through Active Bed Frame Vibration**, In Proceedings of ACM Interact. Mob. Wearable Ubiquitous Technol (IMWUT)/UbiComp'27.

- **C6.** ZhiChao Huang, Yingnian Guo, Chiyue Wang, Zhengte Cai, Xiongfeng Ying, Yu He, Yingjing Xiao, **<u>Kaiyi Guo</u>**, Qian Zhang, Zhanpeng Jin, Yang Gao, **EmbodiedRecall: A Ring-to-Glasses System for Preserving Valuable, Fleeting Moments in Daily Activities**, In Proceedings of ACM Interact. Mob. Wearable Ubiquitous Technol (IMWUT)/UbiComp'26.

- **C5.** Cong Liu *, Ruihao Zheng *, Jvbin Ren, **<u>Kaiyi Guo</u>**, Qian Zhang, She Dong, Yuting Bai, Zhanpeng Jin, Yang Gao, **RageSense: Leveraging Acoustic Sensing and LLM-Based Intervention for Privacy-Preserving Emotion Regulation in Mobile Gaming**, In Proceedings of the 2026 CHI Conference on Human Factors in Computing Systems (CHI'26). <span style="color: red;">[[pdf](https://dl.acm.org/doi/full/10.1145/3772318.3791076)]</span>

- **J2.** Ahsan Jamal Akbar, **<u>Kaiyi Guo</u>**, Qian Zhang, Dong Wang, **EchoLip: Pushing the Limit of Acoustic-Based Silent Speech Interface on Mobile Devices**, In Proceedings of IEEE Internet of Things Journal (IEEE IOTJ). <span style="color: red;">[[pdf](https://ieeexplore.ieee.org/abstract/document/11146579)]</span>

- **C4.** **<u>Kaiyi Guo</u>** *, Tianyu Wu *, Yang Gao, Qian Zhang, Dong Wang, **EchoTouch: Low-power Face-touching Behavior Recognition Using Active Acoustic Sensing on Glasses**, In Proceedings of ACM Interact. Mob. Wearable Ubiquitous Technol (IMWUT)/Ubicomp'25. <span style="color: red;">[[pdf](https://dl.acm.org/doi/10.1145/3729481)]</span>

- **J1.** **<u>Kaiyi Guo</u>**, Qian Zhang, Dong Wang, **EchoExpress: Facial Expression Recognition in the Wild via Acoustic Sensing on Smart Glasses**, In Proceedings of IEEE Transactions on Mobile Computing (IEEE TMC). <span style="color: red;">[[pdf](https://www.computer.org/csdl/journal/tm/5555/01/11002603/26F3rIaWVr2)]</span>

- **C3.** **<u>Kaiyi Guo</u>**, Qian Zhang, Dong Wang, **EchoBreath: Continuous Respiratory Behavior Recognition in the Wild via Acoustic Sensing on Smart Glasses**, In Proceedings of the 2025 CHI Conference on Human Factors in Computing Systems (CHI'25).
<span style="color: red;">[[pdf](https://dl.acm.org/doi/10.1145/3706598.3714171)]</span>

- **C2.** Qian Zhang, **<u>Kaiyi Guo</u>**, Yifei Yang, Dong Wang, **WearSE: Enabling Streaming Speech Enhancement on Eyewear Using Acoustic Sensing**, In Proceedings of ACM Interact. Mob. Wearable Ubiquitous Technol (IMWUT)/Ubicomp'25.
<span style="color: red;">[[pdf](https://dl.acm.org/doi/10.1145/3712288)]</span>

- **C1.** Qian Zhang, Yubin Lan, **<u>Kaiyi Guo</u>**, Dong Wang, **Lipwatch: Enabling Silent Speech Recognition on Smartwatches using Acoustic Sensing**, In Proceedings of ACM Interact. Mob. Wearable Ubiquitous Technol (IMWUT)/Ubicomp'24. <span style="color: red;">[[pdf](https://dl.acm.org/doi/10.1145/3659614)]</span>

<sup>*</sup> Equal Contribution

You can also find my articles on my [Google Scholar profile](https://scholar.google.com/citations?user=dCuMUU4AAAAJ&hl=zh-CN).

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
