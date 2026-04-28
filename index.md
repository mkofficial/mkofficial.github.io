---
layout: default
title: Home
---

# 👋 Welcome to My Cybersecurity Blog

Hi, I am Manas 👨‍💻

🚀 I specialize in:
- Web Application Security
- Vulnerability Assessment
- Ethical Hacking Labs

---

## 🔥 Latest Blogs

{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}

---

## 🛠️ Tools I Use
- Nmap  
- Burp Suite  
- Metasploit  

---

👉 Explore more in the Blog section!
