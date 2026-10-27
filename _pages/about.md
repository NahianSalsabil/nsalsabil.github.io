---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi! I'm **Nahian Salsabil**, a PhD student in Computer Science at the [University of Virginia](https://engineering.virginia.edu/department/computer-science), where I work as a Graduate Research Assistant in the **LESS Lab** with Prof. Sebastian Elbaum.

My research is in **software engineering for autonomous driving**. I focus on testing and verifying autonomous vehicle (AV) systems in rare, safety-critical scenarios, and more broadly on using **AI for autonomous vehicles**. My recent work, [TRACE](https://dl.acm.org/doi/abs/10.1145/3803437.3806426) (FSE 2026), reconstructs real-world accidents in the CARLA simulator with topology-aware road layouts to evaluate AVs.

Before UVA, I earned my B.Sc. in Computer Science and Engineering from **Bangladesh University of Engineering and Technology (BUET)**. My undergraduate thesis proposed new pooling methods for CNN-based semantic segmentation of driving videos. I'm also a Lecturer (currently on study leave) in the [Department of CSE at BRAC University](https://www.bracu.ac.bd/about), where I taught programming, data structures and algorithms.

News
======
- **2026:** Won both the **Best Poster Award (Faculty Choice)** and the **Best Poster Award (Audience Choice)** at the UVA Research Symposium.
- **2026:** *TRACE: Topology Aware Reconstruction of Accidents in CARLA for AV Evaluation* was published at **FSE 2026**.
- **Aug 2025:** Started my PhD in Computer Science at the University of Virginia.
- **Jun 2023:** Joined BRAC University as a Lecturer in CSE.
- **May 2023:** Graduated with a B.Sc. in CSE from BUET.

Work Experience
======
- **Graduate Research Assistant**, LESS Lab, University of Virginia, *Aug 2025 – Present*
- **Lecturer (on leave)**, Department of Computer Science and Engineering, BRAC University, Dhaka, *Jun 2023 – Present*
  - Taught CSE110 (Programming Language I), CSE220 (Data Structures) and CSE221 (Algorithms Sessional)

Publications
======
<ul>
{% for post in site.publications reversed %}
  <li>{{ post.citation | replace: "Nahian Salsabil", "<strong>Nahian Salsabil</strong>" }}
    {% if post.paperurl %} [<a href="{{ post.paperurl }}">Paper</a>]{% endif %}
    {% if post.codeurl %} [<a href="{{ post.codeurl }}">Code</a>]{% endif %}
  </li>
{% endfor %}
</ul>

Honors and Awards
======
- Best Poster Award (Faculty Choice), UVA Research Symposium, 2026
- Best Poster Award (Audience Choice), UVA Research Symposium, 2026
- Top 10 on both the 1st and 2nd leaderboards, DhakaAI Object Detection Challenge (5-member team)
- Regional Champion, Bangladesh Mathematical Olympiad, 2015
- Winner, Bangladesh Physics Olympiad (National Round), 2014

Services
======
- Batch Representative, BWCSE (Bangladesh Women in Computer Science and Engineering). Helped organize seminars, workshops and competitions featuring women leaders in computing.

Outside Research
======
I'm interested in human psychology. In my free time I enjoy cooking, traveling, and binge-watching thrillers, dramas and sitcoms.
