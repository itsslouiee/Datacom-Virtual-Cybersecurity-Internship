# My Virtual Cybersecurity Internship Experience with Datacom (Forage)

Recently, I completed the **Datacom Virtual Cybersecurity Internship** on Forage.  
Even though it lasted only a few hours, it gave me a realistic glimpse of what it’s like to be on a cybersecurity team that investigates live threats, analyzes risks, and documents findings clearly for both technical and executive audiences.  
I was given two tasks to work on, each simulating a real world cybersecurity challenge.


## 🚨 Task 1: Ransomware Attack at Orion Health Services

The first scenario was a **ransomware attack** at Orion Health Services, a healthcare software provider. Several employees were locked out of systems, and a ransom note appeared on shared drives.

The attack began with a **phishing email** sent to a finance staff member. The email contained a malicious Excel file with a **macro** which is a script embedded in the document designed to run automatically when opened. In this case, the macro triggered the ransomware and helped the attacker steal credentials. Forensic signs showed the attacker used **Mimikatz** to harvest passwords, and encrypted files carried the `.orionlock` extension.

In this task, which focused on **incident response**, I was asked to write a **Security Breach Report** that concisely summarized the incident how the attack started, how it spread, its business impact, and what went wrong, along with recommendations that minimize the consequences and prevent attacks like this from happening in the future. The report should be written in a way that non-technical readers could easily understand what happened.


### 🛡️ My Recommendations
- Strengthen **email filtering** and enable **attachment sandboxing**
- Block macro execution from external sources.
- Enforce **Multi-Factor Authentication (MFA)** on all privileged accounts to limit the spread of the attack. 
- Regularly test backup integrity and store off-site copies to guarantee a fast recovery.
- Conduct regular phishing simulations and awareness programs.


### 💡 Insights
From this small task we can see how a single human error JUST ONE CLICK can compromise critical systems in a company, and how structured assessment can help minimize the damages.



## 🧩 Task 2: Risk Assessment for RetailNova
  
This task was a bit different where I played the role of a **Cybersecurity Consultant** reviewing the digital infrastructure of *RetailNova*, a national retail company running both physical stores and a large e-commerce platform.  
My job was to perfom a **risk assessment** by chosing three key risks and do a complete assessments for each by identify high-value assets, assess vulnerabilities, and prioritizing them using a **5x5 Cyber Risk Matrix**.  


### 🎯 Assets and Risks

I focused on these three areas: **customer data**, **cloud infrastructure**, and the **e-commerce platform**, where I identified potential threats, vulnerabilities, and mitigations for each.

- **Customer Data:** Protect sensitive information like personal and payment details.  
- **Cloud Infrastructure:** Secure hosting and access controls to prevent misconfigurations and leaks.  
- **E-commerce Platform:** Ensure safe, reliable customer-facing systems against attacks and downtime.  


### ⚙️ What I Learned
This exercise taught me how to prioritize risks, evaluate their likelihood and potential impact, and communicate recommendations in business language. 



## 🧾 Certificate of Completion

You can view my completion certificate [here](https://forage-uploads-prod.s3.amazonaws.com/completion-certificates/gCW7Xki5Y3vNpBmnn/yTszJTvkHFBH6zAn3_gCW7Xki5Y3vNpBmnn_tNuWnmRWqNQps2pwp_1762452366632_completion_certificate.pdf).

Best,  
**itsslouiee**
