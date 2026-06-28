from pathlib import Path
import pypandoc

md = r'''<div align="center">

# Hi 👋, I'm **Sumit Mali**

### 🚀 Full Stack Developer | MERN Stack | AI/ML Enthusiast | Computer Engineer

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Poppins&weight=600&size=28&duration=3000&pause=1000&center=true&vCenter=true&width=800&lines=Full+Stack+Developer;MERN+Stack+Developer;AI%2FML+Enthusiast;Open+Source+Learner;Always+Learning+New+Things)](https://git.io/typing-svg)

![](https://komarev.com/ghpvc/?username=YOUR_GITHUB_USERNAME&style=for-the-badge&color=blueviolet)

</div>

---

# 🚀 About Me

- 🎓 Computer Engineering Graduate
- 💻 Passionate Full Stack Developer
- 🌱 Currently learning **Advanced MERN Stack & System Design**
- 🤖 Interested in **Artificial Intelligence & Machine Learning**
- 📄 Presented an **IEEE Research Paper**
- 💬 Ask me about **Java, JavaScript, React, Node.js, MongoDB**
- 📍 Maharashtra, India

---

# 🌐 Connect with Me

<p align="center">
<a href="mailto:YOUR_EMAIL@gmail.com"><img src="https://skillicons.dev/icons?i=gmail" height="48"/></a>
&nbsp;&nbsp;
<a href="tel:+91XXXXXXXXXX"><img src="https://img.icons8.com/color/48/phone.png" height="48"/></a>
&nbsp;&nbsp;
<a href="https://linkedin.com/in/YOUR_LINKEDIN"><img src="https://skillicons.dev/icons?i=linkedin" height="48"/></a>
&nbsp;&nbsp;
<a href="https://instagram.com/YOUR_INSTAGRAM"><img src="https://skillicons.dev/icons?i=instagram" height="48"/></a>
&nbsp;&nbsp;
<a href="https://YOUR_PORTFOLIO.vercel.app"><img src="https://skillicons.dev/icons?i=vercel" height="48"/></a>
</p>

---

# 💻 Tech Stack

### Languages
<p>
<img src="https://skillicons.dev/icons?i=java,js,python,c,cpp"/>
</p>

### Frontend
<p>
<img src="https://skillicons.dev/icons?i=html,css,bootstrap,tailwind,react,vite"/>
</p>

### Backend
<p>
<img src="https://skillicons.dev/icons?i=nodejs,express"/>
</p>

### Database
<p>
<img src="https://skillicons.dev/icons?i=mongodb,mysql"/>
</p>

### Tools
<p>
<img src="https://skillicons.dev/icons?i=git,github,vscode,postman,firebase,npm"/>
</p>

### AI / ML
<p>
<img src="https://skillicons.dev/icons?i=tensorflow,opencv"/>
</p>

---

# 🚀 Featured Projects

## 🌍 WanderLust
- MERN Stack hotel booking platform
- Authentication, CRUD, Cloudinary, Maps

## ♻ Waste Classification using CNN
- TensorFlow, Keras, Streamlit

## 🎥 Intelligent Audio Video Dubbing
- Wav2Lip, Whisper, Neural TTS
- IEEE Research Project

## 📱 MediConnect
- Flutter + Firebase

## 🌐 Personal Portfolio
- HTML, CSS, JavaScript

---

# 📊 GitHub Stats

<p align="center">
<img height="170" src="https://github-readme-stats.vercel.app/api?username=YOUR_GITHUB_USERNAME&show_icons=true&theme=tokyonight"/>
<img height="170" src="https://streak-stats.demolab.com?user=YOUR_GITHUB_USERNAME&theme=tokyonight"/>
</p>

<p align="center">
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_GITHUB_USERNAME&layout=compact&theme=tokyonight"/>
</p>

---

# 🏆 GitHub Trophies

<p align="center">
<img src="https://github-profile-trophy.vercel.app/?username=YOUR_GITHUB_USERNAME&theme=tokyonight&row=1&column=7"/>
</p>

---

# 📈 Contribution Graph

<p align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=YOUR_GITHUB_USERNAME&theme=tokyo-night"/>
</p>

---

# 🐍 Snake Animation

> Create `.github/workflows/snake.yml` in this repository and use the latest Platane/snk workflow.

<p align="center">
<img src="https://raw.githubusercontent.com/YOUR_GITHUB_USERNAME/YOUR_GITHUB_USERNAME/output/github-contribution-grid-snake-dark.svg"/>
</p>

---

# 💬 Random Developer Quote

<p align="center">
<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight"/>
</p>

---

# 📫 Reach Me

- 📧 YOUR_EMAIL@gmail.com
- 💼 https://linkedin.com/in/YOUR_LINKEDIN
- 🌐 https://YOUR_PORTFOLIO.vercel.app
- 📱 +91 XXXXXXXXXX

---

<div align="center">

### ⭐ Thanks for visiting my profile! ⭐

</div>

---

## 🔧 Replace these placeholders

- `YOUR_GITHUB_USERNAME`
- `YOUR_EMAIL@gmail.com`
- `YOUR_LINKEDIN`
- `YOUR_INSTAGRAM`
- `YOUR_PORTFOLIO`
- `+91XXXXXXXXXX`
'''
out="/mnt/data/README.md"
Path(out).write_text(md,encoding="utf-8")
print(out)
