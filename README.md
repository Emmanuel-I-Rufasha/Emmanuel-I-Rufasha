# 👋 Hi, I'm Emmanuel

I'm a **Graduate Software Engineer** with a strong focus on **C#**, **ASP.NET Core**, and **Clean Architecture**.  
I recently completed a **Software Engineering Apprenticeship** with a **cybersecurity company specializing in OT & IT security for oil and gas environments**.  
Now, I’m expanding my technical depth by developing a full-scale learning project im naming **RigAtlas**.

---

## 🚧 Current Project: RigAtlas
**RigAtlas** is a rig-centric cybersecurity & compliance project that applies **Domain-Driven Design (DDD)**, **Test-Driven Development (TDD)**, and **Clean Architecture** principles to model complex engineering structures with various operational technology hardware. Offshore oil rig data is generally not publicly available, as it is considered proprietary, commercially sensitive and a matter of security for the operating companies. Not to mention the fact that keeping this information private helps to protect the trade secrets and competitive advantage of the companies involved. 

## 🧠 Domain Knowldege
While proprietary trade secrets in this industry are generally guarded... Data pertinent to major safety incidents and environmental impact such as the Deepwater Horizon's 2010 oil spill incident, is often released to the public due to legal requirements, government investigations, and the need for scientific research and improved safety standards across the industry. As such, my biggest sources of domain knowledge for the offshore oil rig industry has been limited documentation available online via multiple lengthy investigation reports made by government bodies such as the US Coast Guard; the Bureau of Ocean Energy Management, Regulation & Enforcement (BOEMRE) and many other reports which have been referenced in my documentation

closely guarded to protect trade secrets, operational efficiency, and security.
proprietary business information, essential for maintenance and operations, and not released to the public.
 raw and interpreted exploration data is highly confidential to protect the competitive advantage of the companies involved
operational offshore oil rig are generally not publicly available. This information is considered proprietary, commercially sensitive, and a matter of security for the operating companies. 


## What Problem Does this Project Solve ?
One of the major pain points of companies that run these offshore oil rigs, are the multiple audits they have to deal with every year. If an auditor is not happy about something, these large businesses can be shut down temporarily, which would be a huge loss of money. What i will be building is a platform that allows these companies to self audit in preparation for their auditing dates. My application will include all the things listed below, all in one place. which will make auduiting relatively easiers, as auditors can simply come to one place to look for the data/evidence of the data that they are lookign for.

- **Asset visibility in context**: map devices to **Rig → Deck → Area** and to security **Zones/Conduits (IEC-62443)**.  
- **Vulnerability posture**: ingest **NVD/MSRC** data, normalize names, link to devices, and roll up **CVE & CVSS Scores** by area/zone/rig. 
- **Self-audit workflows**: small control library (IEC-62443/IMO/USCG-inspired), auto-checks, sampling, and evidence capture.  
- **Offline-first thinking**: design for intermittent connectivity (sync queues + conflict handling).
- **Dynamic Device/Data visualisation** of how the IT and OT Network looks like 
- **An Imbedded SCADA/HMI System** : Typically HMI's and SCADA Systems are standalone, but i will have a section of those, As they will offer visual representation of the areas of the oil rigs that are being secured/protected from cyber attacks etc. To avoid going too far from my domain, i will be focusing only on the digital security aspect of the SCADA systems, to ensure that the data being recorded is secured before its sent out.
- **Risk Managament Functionality**: Currently done via MS Excel. I will be introducing this functionality within the application itself to make everything easily accessible for adutors




**Tech Stack**
1. C# / ASP.NET Core Application
3. EF Core (SQL Server, since my data will have a lot of relationships)
4. Electron (Since oil rigs are typically offline most of the day and use satelite dishes to send data to the main offices on land)
5. React (later)
6. Swagger (For endpoint testing),
7. xUnit (For TDD).
8. MongoDB (for diagrams versions)
9. Azure DevOps Pipelines & Terraform (DevOps stage)  


**Goals**
- Deepen my understanding of **C# fundamentals and .NET internals**  
- Learn to design scalable APIs and domain models  
- Practice **secure coding** and **DevSecOps** workflows  
- Build complete CI/CD pipelines from scratch

---

## 🧩 Technical Interests
- Software Architecture & Design Patterns  
- Cyber Security & OT System Hardening  
- Infrastructure as Code (Terraform / Bicep)  
- Continuous Integration & Deployment (CI/CD)  
- Cloud Platforms (Azure, AWS)

---

## My Mindset, As I Embark On This Project
I believe in **learning by building**. Turning theory into something tangible and useful.  
RigAtlas is both a study tool and a proof of concept showing how good architecture can make complex domains manageable.

---

## 📫 Let’s Connect
- 🌐 [LinkedIn](#)  
- 📧 [Email](#)  
- 🧰 [RigAtlas Repository](#)
