---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

- **C4.** **<u>Kaiyi Guo</u>**<sup>*</sup>, Tianyu Wu<sup>*</sup>, Yang Gao, Qian Zhang, Dong Wang, **EchoTouch: Low-power Face-touching Behavior Recognition Using Active Acoustic Sensing on Glasses**, Submit to ACM Interact. Mob. Wearable Ubiquitous Technol (IMWUT)/Ubicomp'25 (Major Revision).

- **J1.** **<u>Kaiyi Guo</u>**, Qian Zhang, Dong Wang, **EchoExpress: Facial Expression Recognition in the Wild via Acoustic Sensing on Smart Glasses**, IEEE Transactions on Mobile Computing (Minor Revision).

- **C3.** **<u>Kaiyi Guo</u>**, Qian Zhang, Dong Wang, **EchoBreath: Continuous Respiratory Behavior Recognition in the Wild via Acoustic Sensing on Smart Glasses**, In (To Appear) Proceedings of the 2025 CHI Conference on Human Factors in Computing Systems (CHI'25).

- **C2.** Qian Zhang, **<u>Kaiyi Guo</u>**, Yifei Yang, Dong Wang, **WearSE: Enabling Streaming Speech Enhancement on Eyewear Using Acoustic Sensing**, In (To Appear) Proceedings of ACM Interact. Mob. Wearable Ubiquitous Technol (IMWUT)/Ubicomp'25.

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
