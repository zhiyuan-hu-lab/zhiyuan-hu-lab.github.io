---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team / 团队

胡致远课题组依托医学研究院。  
Hu Lab is based at the Medical Research Institute.

课题组成员 / Lab Members

{% include section.html %}

<div class="grid" data-style="team">
{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}
{% include list.html data="members" component="portrait" filter="role == 'phd'" %}
{% include list.html data="members" component="portrait" filter="role == 'master'" %}
{% include list.html data="members" component="portrait" filter="role == 'undergrad'" %}
</div>

{% include section.html background="images/background.jpg" dark=true %}

课题组热忱欢迎有兴趣的科研助理、学生和博士后加入我们的团队！

We warmly welcome interested research assistants, students, and postdoctoral fellows to join our team.
