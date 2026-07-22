<h1>Arduino RTC Timing Switch: Automated AC Appliance Control with DS3231 and Relay Module</h1>
<img src="https://i.postimg.cc/mgq8nCWs/Project-Thumbnail.jpg" alt="Project Thumbnail" style="max-width: 100%; height: auto;">
<h3>This project is compatible with various Arduino boards, and the connections are similar. I'm using Arduino Uno, but I've included connection diagrams for both Arduino Uno and Nano. Most Arduino boards share similar pin configurations refer to the provided connection diagrams.</h3>
<img src="https://i.postimg.cc/k4W1K4Zd/Arduino-Uno-Connection-Diagram.png" alt="Arduino Uno Connection Diagram" style="max-width: 100%; height: auto;">
<img src="https://i.postimg.cc/RhRgpY4s/Arduino-Nano-Connection-Diagram.png" alt="Arduino Nano Connection Diagram" style="max-width: 100%; height: auto;"><br>
<h1>Switching RTC Modules in Arduino:</h1>
<img src="https://i.postimg.cc/FsrWkhV2/Other-modules.jpg" alt="Other RTC Modules" style="max-width: 100%; height: auto;">
<img src="https://i.postimg.cc/KcVWrKJD/Difference.png" alt="Difference Between Why I am using these Codes for different module." style="max-width: 100%; height: auto;">

<h3>DS3231 Code (rtc.lostPower()):</h3> <h4>The DS3231 RTC module has a built-in feature to detect power loss, and this is checked using rtc.lostPower(). If power is lost, it indicates that the RTC might have been without power and could have lost its timekeeping information. In such cases, it adjusts the time using the compilation timestamp.</h4><br>

<h3>DS1307 Code (!rtc.isrunning()):</h3> <h4>The DS1307 RTC module lacks a direct method to check for power loss. Instead, it uses rtc.isrunning() to determine if the RTC is actively keeping time. If it's not running, it suggests that the RTC may not have power or may have lost its timekeeping ability. In this case, it adjusts the time using the compilation timestamp.
If you were to use either code for both RTC modules, there could be issues.</h4><br> 

<h3>For example:</h3>
<h4>* Using rtc.lostPower() with DS1307 might not work correctly because it doesn't have the lostPower feature.<br>
* Using !rtc.isrunning() with DS3231 might not effectively check for power loss, and you may miss cases where the DS3231 has lost power.</h4><br>

<h1><a href="https://www.youtube.com/watch?v=w8OTqcr_Fnw">Watch this video for Proper Instructions by clicking on the image.</a></h1>
<a href="https://www.youtube.com/watch?v=w8OTqcr_Fnw" target="_blank">
  <img src="https://i.postimg.cc/QCXYjqGt/Youtube-Thumbnail.jpg" alt="Youtube Video" style="max-width: 100%; height: auto;" />
</a>

<h3>When uploading the code in Arduino IDE, make sure to choose the correct board and COM port.</h3>
<img src="https://i.postimg.cc/W35YpKqB/Board-and-Com-port.jpg" alt="Select Board and Com Ports" style="max-width: 100%; height: auto;"><br>
<h2></h2>
<br>
<h2>About me:</h2> <h1 align="center"><a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=900&size=23&pause=1000&color=F7CB00&center=true&vCenter=true&width=435&lines=Hi%2C+I+am+Shahil+S" alt="Typing SVG" /></a></h1>

 <h3 align="center">🚀 Open-Source & Freelance Developer | Turning Ideas into Tools</h3>

<h4 align="center">💡 Passionate about building practical, smart, and user-friendly solutions.</h4>

<h3 align="center">
  With a foundation in tech and a love for problem-solving, Currently learning Windows app development, building automation with Google Apps Script, and experimenting with new ways to make technology more useful.<br><br>
  
  🛠️ From simple productivity tools to efficient desktop utilities, I enjoy crafting solutions that just work.<br>
  🌐 Open source is my playground — I believe in sharing knowledge and collaborating to create better tech for everyone.<br>
  📚 Always learning, always improving — because great software is built on curiosity and persistence.
</h3>

<h3 align="center">
  Let’s build something awesome together — one project at a time. 🤝
</h3>

<h2 align="center">#TechEnthusiast</h2>

<img align="right" alt="Coding" width="300" src="https://i.postimg.cc/CL981DpX/DEVELOPER.gif">

<table border="0" cellspacing="0" cellpadding="0">
  <tr>
    <td valign="top">
      <h3 align="left">Connect with me:</h3>
      <p align="left">
        <a href="https://www.linkedin.com/in/shahilshajahan/" target="_blank" rel="noreferrer">
          <picture>
            <source media="(prefers-color-scheme: dark)" srcset="https://i.postimg.cc/02ZQ9ft7/linkedin-dark.png" />
            <source media="(prefers-color-scheme: light)" srcset="https://i.postimg.cc/XvKFcFjL/linkedin.png" />
            <img src="https://i.postimg.cc/XvKFcFjL/linkedin.png" width="35" height="auto" />
          </picture>
        </a>
        &nbsp;
        <a href="https://github.com/shahilshajahan" target="_blank" rel="noreferrer">
          <picture>
            <source media="(prefers-color-scheme: dark)" srcset="https://i.postimg.cc/Bn6vbKyk/github-dark.png" />
            <source media="(prefers-color-scheme: light)" srcset="https://i.postimg.cc/LsFL1vph/github.png" />
            <img src="https://i.postimg.cc/LsFL1vph/github.png" width="32" height="32" />
          </picture>
        </a>
      </p>
    </td>
  </tr>
</table>

### 🤝 Support My Open Source Work

I build and maintain free, open-source software to solve real-world problems.
If you find my projects useful, you can support future development here:

<div align="left" style="display: flex; gap: 10px; justify-content: center; flex-wrap: wrap;">
  <a href="https://buymeacoffee.com/shahils">
    <img src="https://i.postimg.cc/SKLqz7BH/kofi.png" height="50" width=auto alt="shahils" />
  </a>
  <a>
    <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="50" width="210" alt="https://buymeacoffee.com/shahils" />
  </a>
  <a href="https://paypal.me/MohamedShahil">
    <img src="https://i.postimg.cc/d3WThfdv/paypal.png" height="55" width=auto />
  </a>
</div>

- ☕ Ko-fi → https://ko-fi.com/shahilshajahan
- 💛 Buy Me a Coffee → https://buymeacoffee.com/shahils
- 💙 PayPal → https://paypal.me/MohamedShahil

Your support helps me dedicate more time to developing and maintaining open-source projects. Thank you! ❤️

<div align="left" style="display: flex; gap: 10px; justify-content: center; flex-wrap: wrap;">
  <a href="https://buymeacoffee.com/shahils">
    <img src="https://i.postimg.cc/SQdPYtnh/UPI.png" height=auto width="270" alt="shahils" />
  </a>
 <br>
  <a>
    <img src="https://i.postimg.cc/wMrCJkh5/phonepe.png" height="290" width=auto />
  </a>
</div>

<p>
</p>

# 💻 Tech Stack:
![C](https://img.shields.io/badge/c-%2300599C.svg?style=flat&logo=c&logoColor=white) ![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=flat&logo=c%2B%2B&logoColor=white) ![Windows Terminal](https://img.shields.io/badge/Windows%20Terminal-%234D4D4D.svg?style=flat&logo=windows-terminal&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=flat&logo=python&logoColor=ffdd54) ![PowerShell](https://img.shields.io/badge/PowerShell-%235391FE.svg?style=flat&logo=powershell&logoColor=white) ![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=flat&logo=markdown&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=flat&logo=javascript&logoColor=%23F7DF1E) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=flat&logo=html5&logoColor=white) ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=flat&logo=openjdk&logoColor=white) ![Adobe Audition](https://img.shields.io/badge/Adobe%20Audition-9999FF.svg?style=flat&logo=Adobe%20Audition&logoColor=white) ![Adobe Photoshop](https://img.shields.io/badge/adobe%20photoshop-%2331A8FF.svg?style=flat&logo=adobe%20photoshop&logoColor=white) ![Canva](https://img.shields.io/badge/Canva-%2300C4CC.svg?style=flat&logo=Canva&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=flat&logo=github&logoColor=white) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=flat&logo=git&logoColor=white) ![Arduino](https://img.shields.io/badge/-Arduino-00979D?style=flat&logo=Arduino&logoColor=white) ![OpenSea](https://img.shields.io/badge/OpenSea-%232081E2.svg?style=flat&logo=opensea&logoColor=white) ![Power Bi](https://img.shields.io/badge/power_bi-F2C811?style=flat&logo=powerbi&logoColor=black) ![Tampermonkey](https://img.shields.io/badge/tampermonkey-%2300485B.svg?style=flat&logo=tampermonkey&logoColor=white) ![TOR](https://img.shields.io/badge/tor-%237E4798.svg?style=flat&logo=tor-project&logoColor=white)
