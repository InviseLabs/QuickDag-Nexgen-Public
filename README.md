# QuickDag & Nexgen Public Repo
###### QuickDag is a project of [Invise Labs](https://inviselabs.com/) – A division of [Invise Solutions Computer Repair and IT Services Utah](https://invisesolutions.com/)

**This page and our webiste is being re-written, so bear with us.**

QuickDag emerges as an indispensable tool for IT professionals and Cyber Security Pros. We meticulously engineered two parts, an algorithm to diagnose and detect computer issues, and a **malware and malicious file detection engine, called Nexgen.** At the core of QuickDag is an intuitive dashboard, thoughtfully designed to provide a comprehensive summary **at a glance**. It presents critical information such as current scan status of Nexgen, detected hardware or system issues, system temperatures, hardware specifications, and noteworthy event log entries that merit further investigation. Our tool offers IT experts a centralized hub for monitoring and resolving technical challenges. 

The true essence of QuickDag’s innovation is our **malware and malicious file detection algorithm, Nexgen.** This engine is the product of **relentless dedication**, designed to detect a wide array of threats without the need for constant updates or internet connectivity. Nexgen’s three-part structure—comprising a Dynamic Algorithm, ML Sentry, and Baseline — all 3 combined ensure a proactive stance against digital threats, providing a nuanced analysis that goes beyond traditional security measures.

QuickDag embodies the hard work of our team, a tool that not only identifies issues but also empowers IT experts to take decisive action. It’s more than a diagnostic tool; it’s a guardian of cybersecurity, safeguarding systems with the intelligence and foresight born from years of development and refinement. 💪 👊

­

-----
— ***From the Founder*** —

**“** From **2017 to 2024**, an immense collective effort **totaling hundreds of thousands of hours** has been dedicated to our project. It’s hard to grasp that **seven years** have flown by. There were stretches when I found myself coding relentlessly, staying awake for 24 to 48 hours straight, immersed in a cycle of writing, testing, and refining.

Following the initial beta release, the pace of development naturally decelerated somewhat. Yet, QuickDag remained a constant across every computer we handled and serviced. By integrating QuickDag into our toolkit, it became the default diagnostic tool, launching automatically with a menu that guided our technicians through preliminary assessments. It served as a crucial indicator of potential issues and informed the subsequent steps we needed to take.

Through years of meticulous beta testing, we’ve honed our algorithm to near perfection. The anticipation to unveil our creation is palpable, and we’re eager to extend an invitation to all interested parties to engage with and evaluate our work. **”**

***~Mike Lierman – Founder, Managing Director***

-----

­

**Let's discuss how Nexgen, the malicous detection engine we wrote, works:**

Introducing Nexgen: The Pioneering Malware Detection Engine

Nexgen stands at the forefront of cybersecurity, boasting the capability to identify malicious files and software swiftly—often within minutes—without the need for an internet connection or frequent updates. This innovative 3-part engine is the culmination of our commitment to advanced security solutions.

### The Three Pillars of Nexgen by Invise Labs

**1. The Dynamic Algorithm**

At the heart of Nexgen is our dynamic algorithm, a paradigm shift in security strategies. We decided to forgo traditional methods like signature matching or infector code identification, they are too dated, too unreliable, and only detect things seen before. Even ML implemtations of signaure matching are still extremely unreliable. Instead, our algorithm emulates the meticulous process of manual malware hunting and system cleansing. It evaluates hundreds of indicators, both malicious and benign, to calculate a nuanced maliciousness score. The inherent stealth of malware, designed to evade detection, ironically becomes its downfall—our algorithm detects by definition.

**2. ML Sentry: The Machine Learning Component**

Our machine learning component, ML Sentry, complements the algorithm without overshadowing it. While we recognize the potential of AI and machine learning in refining detection scores and identifying elusive malware, we also understand their limitations. Encrypted malware, for instance, remains inscrutable without decryption keys. We respect the legitimate encryption needs of software developers protecting their intellectual property and investments. Therefore, we maintain that sophisticated algorithms, crafted by expert researchers, are indispensable in discerning the intent behind encrypted code.

**3. Baseline: The Separate Hybrid Algorithm**

Baseline represents a hybrid approach, blending machine learning with crowd-sourced insights and similarity matching. It learns from historical data, what it's seen before, and patterns of integrity such as signatures and timestamps. Each file is cataloged in an anonymous database, with a scoring system that considers factors such as: The code signing certificate - seen before, does it chain verify, has this cert info been seen before; user / technician actions, like Mark as Safe, Ignore, etc.; its history; and crowd trust factors. Files scoring above zero undergo further scrutiny, ensuring our algorithm's efficiency without impacting scan times. All of these considerations are processed into a score to determine if the malicousness score should be adjusted, and if the file should be "Identified Safe by Baseline."
