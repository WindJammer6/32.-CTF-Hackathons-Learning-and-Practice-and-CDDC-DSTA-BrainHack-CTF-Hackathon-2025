# 32.-CTF-Hackathons-Learning-and-Practice-and-CDDC-DSTA-BrainHack-CTF-Hackathon-2025 🚩🛡️
This repository stores my learning process about Capture-The-Flag (CTF) Cybersecurity hackathons, as well as some information about the first CTF hackathon I took part in, the [Cyber Defenders Discovery Camp (CDDC) Defence Science and Technology Agency (DSTA) BrainHack CTF Hackathon 2025](https://www.dstabrainhack.com/activities-cddc). [Defence Science and Technology Agency (DSTA)](https://www.dsta.gov.sg/) is a statutory board under the purview of the Ministry of Defence of the Government of Singapore.

<p align="center">
  <img src="https://ctftime.org/media/events/picoCTF_logo_4c.png" width="250"/>
</p>

Prior to this CTF hackathon, I knew next to nothing about cybersecurity, much less about CTF hackathons. So, in order to start out, I googled around and stumbled upon [John Hammond's YouTube playlist about 'Getting Started in CTF: PicoCTF 2017'](https://www.youtube.com/playlist?list=PL1H1sBF1VAKVTu-v1XcJV9VVdhEEALvkY), and decided I will start my cybersecurity and CTF hackathon journey here. Turns out, in this YouTube playlist, he is basically just going through CTF questions from a past international CTF hackathon, [PicoCTF 2017](https://www.picoctf.org/), organised by [Carnegie Mellon University (CMU)](https://www.cmu.edu/). I decided to do my own write up on his videos to explain to myself how to answer the CTF questions, from the perspective of someone with some prior knowledge in some programming languages (Python, Java, SQL, JavaScript, HTML, CSS, etc.), but with no prior knowledge on the Internet, Bash command-line language, etc. (because this was the skill level I was at at the time of writing this write up).

This repository stores this write up, and some information about the first CTF hackathon I took part in, the [Cyber Defenders Discovery Camp (CDDC) Defence Science and Technology Agency (DSTA) BrainHack CTF Hackathon 2025](https://www.dstabrainhack.com/activities-cddc). 

I have learnt much about CTF hackathons, and more importantly, about cybersecurity in preperation for this [Cyber Defenders Discovery Camp (CDDC) Defence Science and Technology Agency (DSTA) BrainHack CTF Hackathon 2025](https://www.dstabrainhack.com/activities-cddc). I also learnt the Bash programming language as well! (though not the normal high-level programming language like Python or Java, but more of a command-line/scripting language)

<br>

**Disclaimer:**  
- [PicoCTF 2017](https://www.picoctf.org/) is a past CTF hackathon, and all of its resources has long since been taken down by the [PicoCTF](https://www.picoctf.org/) website. Only CTF questions on the current [PicoCTF 2025](https://www.picoctf.org/) exists on the website. Hence, the website links and resources in the [John Hammond's YouTube playlist about 'Getting Started in CTF: PicoCTF 2017'](https://www.youtube.com/playlist?list=PL1H1sBF1VAKVTu-v1XcJV9VVdhEEALvkY) no longer exists on the [PicoCTF website](https://www.picoctf.org/).

  To tackle this issue, I went to google around I found write-ups about the [PicoCTF 2017](https://www.picoctf.org/) CTF questions, on GitHub and was lucky to find some the CTF questions, and resources that I could play around with (though limited) from [PicoCTF 2017](https://www.picoctf.org/), which helped with my learning. Here are the write-ups about the [PicoCTF 2017](https://www.picoctf.org/) CTF questions I referened to:
  - https://github.com/pdelteil/picoctf_2017_writeup (pdelteil) (the main write-up I referenced to)
  - https://github.com/vabhishek-me/picoctf-2017-write-up (vabhishek-me)

- My own write up is incomplete, as I only documented the [PicoCTF 2017](https://www.picoctf.org/) Level 1 and some Level 2 CTF questions, following only videos 1 to 24, as well as video 35 in [John Hammond's YouTube playlist about 'Getting Started in CTF: PicoCTF 2017'](https://www.youtube.com/playlist?list=PL1H1sBF1VAKVTu-v1XcJV9VVdhEEALvkY) (Unfortunately, I forsee myself unlikely to complete it due to time constraints and personal interest)

<br>

## What are Capture-The-Flag (CTF) hackathons?
Capture-the-Flag (CTF) hacking competitions are exactly like the first-person shooter game mode. One team of players attempts to locate and capture an opposing team's "flag" while also defending their flag. 

In CTF competitions, the flag is typically a snippet of code, a piece of hardware on a network, or perhaps a file. In other cases, the competition may progress through a series of questions, like a race.

<br>

There are 3 types of CTF hackathons:
1. Jeopardy-Style CTF: Like a quiz board (Jeopardy), you pick challenges from categories, solve them, and get points.
2. Attack-and-Defense (A&D) CTF: Teams are given their own vulnerable servers or apps. You defend your system and attack others.
3. King-of-the-Hill (KoTH) CTF: Compete to gain and maintain control over a single system or resource.

Note: [PicoCTF](https://www.picoctf.org/) and [Cyber Defenders Discovery Camp (CDDC) Defence Science and Technology Agency (DSTA) BrainHack CTF Hackathon 2025](https://www.dstabrainhack.com/activities-cddc) are both Jeopardy-Style CTFs

<br>

In a CTF hackathon, there are generally different types of categories. Here are the common ones (applies across all CTF hackathon formats):
| Category               | What It Involves                                                                 |
|------------------------|----------------------------------------------------------------------------------|
| 🔍 Web Exploitation     | Finding bugs in websites (e.g., XSS, SQLi, authentication flaws)                |
| 🔐 Cryptography         | Cracking or breaking poor cryptographic implementations                         |
| 🧪 Forensics            | Analyzing files, memory dumps, or network traffic                               |
| 💥 Binary Exploitation (Pwn) | Exploiting compiled programs using overflows or custom shellcode        |
| 🧠 Reverse Engineering   | Analyzing compiled binaries to uncover logic or hidden secrets                  |
| 🧩 Misc / OSINT         | Trivia, steganography, or real-world investigation and recon                    |


Source:
- https://www.cbtnuggets.com/blog/training/exam-prep/how-to-prepare-for-a-capture-the-flag-hacking-competition (CBTnuggets)

<br>

## About the Cyber Defenders Discovery Camp (CDDC) Defence Science and Technology Agency (DSTA) BrainHack CTF Hackathon 2025
<p align="center">
  <img src="https://static.wixstatic.com/media/807b15_524e092c9d7541589d621cd0e9bf6e4b~mv2.jpg/v1/fill/w_1200,h_627,al_c,q_85/brainhack2024-meta-preview.jpg" width="400"/>
</p>

[Cyber Defenders Discovery Camp (CDDC) Defence Science and Technology Agency (DSTA) BrainHack CTF Hackathon 2025](https://www.dstabrainhack.com/activities-cddc) is a Jeopardy-Style CTF hackathon structured with,
- 2 weeks of Training phase
- 1 day of Qualifiers phase
- 2 days of Finals phase (only top 100 teams are chosen)

Unfortunately did not make it to finals, they only took top 100 teams (Overall category) for finals, my team ended at **109th** place out of 400+ teams (Overall category) (so close!!! :() and **64th** place out of 200+ teams (University category) that participated in the Qualifiers phase.

I won't have time to do a write up for the questions in this CTF hackathon that I took part in due to time constraints.

It was still a really enjoyable experience, and while I did not make it to the finals phase, I felt like I had a big push in my understanding of the theory and tools used in the field of Cybersecurity throughout my first CTF hackathon at the [Cyber Defenders Discovery Camp (CDDC) Defence Science and Technology Agency (DSTA) BrainHack CTF Hackathon 2025](https://www.dstabrainhack.com/activities-cddc).

### DSTA BrainHack Hackathon 2025 results:  
**Training phase (just for fun):**  
Screenshots of my standing in the training phase (my username is WindJammer6!):
<p align="center">
  <img src="https://github.com/WindJammer6/32.-CTF-Hackathons-Learning-and-Practice-and-CDDC-DSTA-BrainHack-CTF-Hackathon-2025/blob/main/CDDC%20DSTA%20BrainHack%20CTF%20Hackathon%202025%20Training%20Ranking%20Image%201.png" width=750/>
    <img src="https://github.com/WindJammer6/32.-CTF-Hackathons-Learning-and-Practice-and-CDDC-DSTA-BrainHack-CTF-Hackathon-2025/blob/main/CDDC%20DSTA%20BrainHack%20CTF%20Hackathon%202025%20Training%20Ranking%20Image%202.png" width=750/>
    <img src="https://github.com/WindJammer6/32.-CTF-Hackathons-Learning-and-Practice-and-CDDC-DSTA-BrainHack-CTF-Hackathon-2025/blob/main/CDDC%20DSTA%20BrainHack%20CTF%20Hackathon%202025%20Training%20Ranking%20Image%203.png" width=750/>
</p>


**Qualifers phase:**  
Screenshots of my standing in the qualifiders phase (my team name is Comptooter Science!):
<p align="center">
  <img src="https://github.com/WindJammer6/32.-CTF-Hackathons-Learning-and-Practice-and-CDDC-DSTA-BrainHack-CTF-Hackathon-2025/blob/main/CDDC%20DSTA%20BrainHack%20CTF%20Hackathon%202025%20Qualifiers%20Ranking%20Image%201.jpg" width=300/>
    <img src="https://github.com/WindJammer6/32.-CTF-Hackathons-Learning-and-Practice-and-CDDC-DSTA-BrainHack-CTF-Hackathon-2025/blob/main/CDDC%20DSTA%20BrainHack%20CTF%20Hackathon%202025%20Qualifiers%20Ranking%20Image%202.jpg" width=300/>
</p>


