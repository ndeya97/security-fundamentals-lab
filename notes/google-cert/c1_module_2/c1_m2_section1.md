---
title: "Module 2 – Section 1 : The History of Cybersecurity"
course: "Google Cybersecurity Certificate"
date: "2025-11-03"
status: "completed"
quiz_score: "100%"
source: "Coursera"
link_pdf: "https://www.notion.so/Test-your-knowledge_-The-history-of-cybersecurity-Coursera_-Module-2-2a0c513f71e781458a16fde139c81d6f?pvs=21"
---

# 🧩 Module 2 — Section 1 : *The History of Cybersecurity*

> 🎓 **Google Cybersecurity Certificate**  
> 📅 Date : 3 novembre 2025  
> 🧠 Résultat du quiz : **100 % dès la 1ʳᵉ tentative**  
> 📎 Capture PDF : [Delivrables – Phase 1 / Coursera](https://www.notion.so/Test-your-knowledge_-The-history-of-cybersecurity-Coursera_-Module-2-2a0c513f71e781458a16fde139c81d6f?pvs=21)

---

## 👋 Introduction

One reason there are so many jobs in the security field today is because of attacks that happened in the 1980s and 1990s.  
Decades later, security professionals are still actively working to protect organizations and people from variations of these early computer attacks.

---

## 🎯 What We’ll Learn

- Viruses  
- Malware  
- Social engineering (introduction of the concept)  
- Digital age (how it ushered in a new era of threat actors)  
- Security domains  

> Next up, we'll travel back in time to explore some of the viruses, data breaches, and malware attacks that have helped shape the industry as we know it today.

---

## 🕰️ Past Cybersecurity Attacks

> The security industry is constantly evolving, but many present-day attacks are not entirely new.  
> Attackers often alter or enhance previous methods. Understanding past attacks can provide direction for how to handle or investigate incidents in your job as a security analyst.

### 🧩 Key Terms

#### **Computer Virus**
Malicious code written to interfere with computer operations and cause damage to data and software.  
The virus attaches itself to programs or documents on a computer, then spreads and infects one or more computers in a network.  

Today, viruses are more commonly referred to as **malware**, which is software designed to harm devices or networks.  

Two examples of early malware attacks are the **Brain Virus** and the **Morris Worm**.  
They were created by malware developers to accomplish specific tasks. However, the developers underestimated the impact their malware would have and the number of infected computers.

---

### 🦠 The Brain Virus (1986)

Created by the Alvi brothers.  
Although the intention was to track illegal copies of medical software and prevent pirated licenses, what the virus actually did was unexpected.

- Once a person used a pirated copy of the software, the virus infected that computer.  
- Any disk inserted into the computer was also infected.  
- The virus spread globally within a couple of months.  

Although it did not destroy data or hardware, it slowed down productivity and impacted business operations.

> 💡 The Brain virus fundamentally altered the computing industry, emphasizing the need for a plan to maintain security and productivity.  
> As a security analyst, you will follow and maintain strategies to ensure your organization has a plan to keep its data and people safe.

---

### 🪱 The Morris Worm (1988)

Developed by Robert Morris to assess the size of the internet.  
The program crawled the web and installed itself onto other computers to tally how many were connected.

- It failed to keep track of computers already compromised.  
- It re-installed itself repeatedly until systems ran out of memory and crashed.  
- About 6,000 computers (≈10% of the internet at the time) were affected.  

💰 **Impact :** Millions of dollars in damages due to business disruptions and cleanup.

> After the Morris Worm, **Computer Emergency Response Teams (CERTs®)** were established to respond to computer security incidents.  
> CERTs still exist today and now have expanded responsibilities.

---

## 🌐 Attacks in the Digital Age

With high-speed internet, malware could now spread online—no more physical disks.  
Two notable internet-based attacks: the **LoveLetter (ILOVEYOU)** virus and the **Equifax breach**.

---

### 💌 The LoveLetter (2000)

Created by Onel De Guzman to steal internet login credentials.

- Spread via email with the subject **“I Love You”** and attachment **“Love Letter For You”**.  
- When opened, it scanned the user’s address book and sent itself to all contacts.  
- It installed a program to collect information and passwords.

💥 **Impact :** 45 million computers infected, ≈ 10 billion $ in damages.  
💡 **First major example of social engineering.**

---

### 🧠 Social Engineering

A manipulation technique that exploits human error to gain private information, access, or valuables.  
After the LoveLetter, attackers understood the power of human manipulation.

> The number of social engineering attacks keeps increasing with every new social media application that allows public access to people’s data.  
> Convenience often outweighs privacy, increasing vulnerability.

As a security professional, you must identify and manage inappropriate use of technology that could place your organization at risk.  
A common safeguard: **regular internal trainings** to teach how to identify phishing and similar attacks.

---

### ✉️ Phishing

Use of digital communications to trick people into revealing sensitive data or deploying malicious software.

---

### 🏢 The Equifax Breach (2017)

Attackers infiltrated the **credit reporting agency Equifax**, causing one of the largest known data breaches.

- 143 million+ customer records stolen (~40% of Americans).  
- Data included SSNs, birth dates, driver’s licenses, home addresses, and credit card numbers.  
- Multiple unpatched vulnerabilities exploited.  

💰 **Settlement :** Over $575 million to resolve complaints and fines.  
💡 **Lesson :** Patch management is critical; prevention is cheaper than recovery.

> The large settlement with the U.S. government highlighted the financial impact of breaches and the need for preventative measures.

---

## 📖 Reading — Common Attacks and Their Effectiveness

Previously discussed: LoveLetter (ILOVEYOU), Morris Worm → led to **Computer Security Incident Response Teams (CSIRTs)**.  
Learning goal : understand **common attack methods** and evolving **tactics & techniques** used by threat actors.

---

### 🐟 Phishing

Use of digital communications to trick people into revealing sensitive data or deploying malicious software.

**Common forms :**
- **BEC (Business Email Compromise)** : Impersonate a known source to gain money/information.  
- **Spear phishing** : Target specific users with realistic emails.  
- **Whaling** : Target executives for sensitive data.  
- **Vishing** : Voice-based impersonation.  
- **Smishing** : SMS-based impersonation.

---

### 💣 Malware

Software designed to harm devices or networks — often to obtain money or intelligence.

**Common types :**
- **Viruses** : Require user action (attachment or download). Insert code to damage/destroy data.  
- **Worms** : Self-replicating; spread automatically across networks.  
- **Ransomware** : Encrypts data; demands payment to restore access.  
- **Spyware** : Gathers and sells information without consent (emails, texts, locations).

---

### 🧑‍💻 Social Engineering

Manipulation technique exploiting human trust or error to gain access or valuables.  
Attackers create **false trust** environments to deceive as many people as possible.

**Common types :**
- **Social media phishing** : Gather info from social media before attacking.  
- **Watering hole attack** : Compromise websites frequently visited by a target group.  
- **USB baiting** : Leave infected USBs for victims to plug in.  
- **Physical SE** : Impersonate employee/vendor to enter restricted areas.

---

### ⚙️ Social Engineering Principles

Social engineering is effective because humans are naturally trusting and respect authority.

**Main principles :**
- **Authority** – Pretending to be someone in power.  
- **Intimidation** – Bullying or pressuring into compliance.  
- **Consensus / Social proof** – “Others have done it too” tactic.  
- **Scarcity** – Creating a sense of limited opportunity.  
- **Familiarity** – Building false emotional connections.  
- **Trust** – Developing a long-term relationship to extract data.  
- **Urgency** – Forcing fast reactions without thought.

---

### 🧩 Key Takeaways

- Common attacks include **phishing**, **malware**, and **social engineering**.  
- Humans remain the weakest link — training and awareness are crucial.  
- Patterns from past attacks help predict and prevent future ones.  
- Understanding human psychology is as vital as technical skills.

---

## 🃏 Flashcards — Identify Methods of Attack

**Malware** → Software designed to harm devices or networks.  
**Virus** → Inserts own code; damages/destroys data. *(Type of malware)*  
**Worm** → Self-replicates across network. *(Type of malware)*  
**Ransomware** → Encrypts data; demands payment. *(Type of malware)*  
**Spyware** → Spies and steals user data. *(Type of malware)*  
**Phishing** → Tricks users via digital communications.  
**Spear phishing** → Targeted phishing to specific people/groups.  
**Whaling** → Phishing targeting executives.  
**BEC** → Impersonation attack for financial gain.  
**Vishing** → Voice-based phishing.  
**Social engineering** → Exploiting human error/trust.  
**Social media phishing** → Info gathering via social platforms.  
**Watering hole** → Compromising trusted websites.  
**Physical SE** → Impersonation to gain physical access.  
**USB baiting** → Leaving infected USBs intentionally.

---

## 🧩 Sean’s Advice — *Keep Your Cool During a Data Breach*

> “The first thing you're going to do is contain the breach.  
> If you’re still hemorrhaging data, your priority is to stop the leak — shut down servers, data centers, communications if necessary.  
> Your job as an incident manager or responder is to **stop the breach, then investigate**.  
> Execute your incident management plan calmly and methodically.”

---

✅ **Practice Assignment → Test Your Knowledge: The History of Cybersecurity**  
✔️ *Result : 100 % on first attempt*  
📎 *PDF stored in Deliverables – Phase 1 / Coursera*

---

<p align="center">
  ◀️ <a href="../c1_module_1/c1_m1_section3-review.md">Previous — Module 1 : Section 3 & Review</a>
</p>
