---
layout: page
title: 游荣强 - 技术总监/CTO
permalink: /resume/
---

{% assign resume = site.data.resume %}

# {{ resume.name }}
## {{ resume.title }}

### 基本信息
- 年龄：{{ resume.age }}岁
- 工作年限：{{ resume.experience_years }}年
- 期望薪资：{{ resume.salary }}
- 联系电话：{{ resume.contact.phone }}
- 电子邮箱：{{ resume.contact.email }}
- 所在地：{{ resume.contact.location }}

### 个人优势
{% for item in resume.summary %}
- {{ item }}
{% endfor %}

### 专业技能
- 英语水平：{{ resume.skills.english }}

### 工作经历
{% for exp in resume.work_experience %}
#### {{ exp.company }} - {{ exp.position }}
**{{ exp.period }}**

{% for resp in exp.responsibilities %}
- {{ resp }}
{% endfor %}

{% endfor %}

### 教育背景
{% for edu in resume.education %}
#### {{ edu.school }}
- 学位：{{ edu.degree }}
- 专业：{{ edu.major }}
- 时间：{{ edu.period }}

{% endfor %}

### 专业认证
{% for cert in resume.certifications %}
- {{ cert }}
{% endfor %} 