<style>
ul.custom-list, ul.custom-list2, ul.custom-list3, ul.custom-list4 {
  list-style: none;
  padding-left: 0;
}

ul.custom-list li, ul.custom-list2 li, ul.custom-list3 li, ul.custom-list4 li {
  position: relative;
  padding-left: 30px;
}

ul.custom-list li::before, ul.custom-list2 li::before, ul.custom-list3 li::before, ul.custom-list4 li::before {
  content: "";
  background-repeat: no-repeat;
  background-position: center;
  background-size: 20px 20px;
  width: 20px;
  height: 20px;
  position: absolute;
  left: 0;
  top: 0;
}

ul.custom-list li::before {
  background-image: url('assets/utad.png');
}

ul.custom-list2 li::before {
  background-image: url('assets/icmat.png');
}

ul.custom-list3 li::before {
  background-image: url('assets/hpe.png');
}
ul.custom-list4 li::before {
  background-image: url('assets/linkedin.png');
}

.code-block {
  background-color: #151b23; /* GitHub light gray background */
  border: 1px solid #e1e4e8; /* Light border */
  border-radius: 6px; /* Rounded corners */
  font-family: 'SFMono-Regular', Consolas, 'Liberation Mono', Menlo, monospace;
  font-size: 14px;
  line-height: 1;
  animation: borderPulse 3s infinite alternate;
}

@keyframes borderPulse {
  0% {
    border-color: #0065EF;
  }
  50% {
    border-color: #F8AA25; /* Light Blue */
  }
  100% {
    border-color: #01A982; /* Green */
  }
}
.profile-block {
  display: flex;
  align-items: center;
  gap: 20px; /* Space between image and text */
  padding: 10px;
  font-family: Arial, sans-serif;
}

.profile-block img {
  width: 100px;
  height: auto;
}

.profile-block .profile-text {
  flex: 1; /* Allows text to occupy remaining space */
}
</style>




<div class="profile-block">
  <img src="assets/illidan.gif" alt="Illidan GIF" />
  <div class="profile-text">
    <h3>Hey! 👋</h3>
    <p>
      I’m <strong>Alexis Gómez</strong>, <em>AI & Data Engineer</em> at <strong>HPE</strong> 
      and <strong>BSc in Software Engineering and Mathematics</strong>. Take a look at the projects 
      I've developed over the years and can publicly share.
    </p>
  </div>
</div>

<div class="code-block">
    <h3 align="center">🚀 Enjoy exploring 🚀</h3>
</div>                                


## 🎓 Education
<ul class="custom-list">
  <li>U-TAD - BSc Software Engineering</li>
  <li>U-TAD - BSc Computational Mathematics</li>
</ul>
<ul class="custom-list2">
  <li>ICMAT - Student Researcher in Symplectic Optimization and Lie Groups</li>
</ul>

## 💼 Career Journey
<ul class="custom-list3">
  <li>HPE - AI & Data consultant</li>
</ul>


## 📚 Personal Projects

### [Intelligent Energy Optimization Using Photovoltaic Batteries in Residential Environments](https://github.com/AlexisGitHu/SmartMicrogrids)


Focused on optimizing energy consumption and storage for residential systems with solar technology

---

### [Spectral Characterization of Null Models in Ecological Networks](https://github.com/AlexisGitHu/BipartiteNetworks_SAA)

Analyzing ecological network structures using spectral methods to better understand ecosystem dynamics


## ⚙️ Tech Stack

### Currently focusing on

[![My Skills](https://skillicons.dev/icons?i=bash,linux,github,vscode,javascript,python,fastapi,pytorch,mongodb,redis,docker,nginx,kubernetes)](https://skillicons.dev)

### Foundational knowledge

[![My Skills](https://skillicons.dev/icons?i=html,css,bootstrap,javascript,typescript,nodejs,postgresql,cassandra,kafka,java,c,tensorflow)](https://skillicons.dev)

## 📱 Contact
Feel free to connect with me:
<ul class="custom-list4">
 <li><a href="https://www.linkedin.com/in/alexis-g%C3%B3mez-chimeno/">About me</a></li>
</ul>
