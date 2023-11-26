- 👋 ## Hi There, I’m @Trojan-254 ....hope you like it here
- 👀 I’m interested in solving problems and creating solutions
- 🌱 I’m currently learning Nodejs
- 💞️ I’m looking to collaborate on any problem solving task
- 📫 How to reach me samwuels254@gmail.com
- Connect with me:
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-blue?style=flat&logo=LinkedIn&logoColor=white)](Your LinkedIn URL)
### About Me
<p id="typing"></p>
<style>
#typing {
    font-size: 1.5em;
    border-right: 1px solid #000;
    padding-right: 5px;
    white-space: nowrap;
    overflow: hidden;
    display: inline-block;
    vertical-align: bottom;
}
</style>


<script>
const words = ["Passionate Developer", "Tech Enthusiast", "Open Source Contributor"];
let cursor = "|";
let wordIndex = 0;
let charIndex = 0;
const typingDiv = document.getElementById("typing");

function type() {
    if (charIndex < words[wordIndex].length) {
        typingDiv.innerHTML += words[wordIndex].charAt(charIndex);
        charIndex++;
        setTimeout(type, 100);
    } else {
        setTimeout(erase, 1500);
    }
}

function erase() {
    if (charIndex > 0) {
        typingDiv.innerHTML = words[wordIndex].substring(0, charIndex - 1) + cursor;
        charIndex--;
        setTimeout(erase, 50);
    } else {
        wordIndex = (wordIndex + 1) % words.length;
        setTimeout(type, 1000);
    }
}

setTimeout(type, 1000);
</script>

<!---
Trojan-254/Trojan-254 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
