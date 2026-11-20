<!-- ===================== HEADER ===================== -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=200&color=0:0F172A,100:4F46E5&text=Yalla%20Gnaneswar&fontColor=FFFFFF&fontSize=48&fontAlignY=38&desc=Software%20Engineer%20%C2%B7%20AI%20%26%20Full-Stack%20Systems&descSize=18&descAlignY=60&animation=fadeIn" alt="Yalla Gnaneswar - Software Engineer, AI and Full-Stack Systems" width="100%"/>

<a href="https://github.com/Gnanigit">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&pause=1800&color=6366F1&center=true&vCenter=true&width=720&lines=Production+RAG+pipelines+and+LLM-based+matching;Custom+MCP+server+on+Claude;Enterprise+apps+on+AWS+and+Azure+for+AstraZeneca" alt="Typing animation of core expertise" />
</a>

<br/>

<a href="https://www.linkedin.com/in/gnaneswar-yalla-730ba4250"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:gnani4412@gmail.com"><img src="https://img.shields.io/badge/Email-Get%20in%20touch-4F46E5?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<!-- Uncomment once your portfolio is live and replace the URL:
<a href="https://YOUR-PORTFOLIO-URL"><img src="https://img.shields.io/badge/Portfolio-Visit-0F172A?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/></a>
-->

</div>

<br/>

<!-- ===================== ABOUT ===================== -->
## About

Software Engineer with 2 years of experience building **production AI and full-stack systems** on AWS and Azure. I work where LLMs meet real enterprise constraints: document-heavy inputs, access control, cost, latency, and hallucination risk.

- Built **RAG pipelines**, **hybrid search**, and **LLM-based requirement matching** for an enterprise RFP and proposal platform
- Built a **custom MCP server** that lets Claude securely query project data, proposals, and requirements
- Delivered **enterprise applications for AstraZeneca**, covering SSO, serverless architecture, and AWS provisioning
- Comfortable across the stack: React and Next.js on the front end, FastAPI and Node.js on the back end, plus cloud infrastructure

<br/>

<!-- ===================== TECH ===================== -->
## Technical Expertise

**AI / LLM Engineering**

![Anthropic Claude API](https://img.shields.io/badge/Claude_API-D97757?style=flat-square&logo=anthropic&logoColor=white)
![Gemini](https://img.shields.io/badge/Google_Gemini-4285F4?style=flat-square&logo=googlegemini&logoColor=white)
![AWS Bedrock](https://img.shields.io/badge/AWS_Bedrock-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Azure AI Studio](https://img.shields.io/badge/Azure_AI_Studio-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![MCP](https://img.shields.io/badge/Model_Context_Protocol-4F46E5?style=flat-square)
![Agentic RAG](https://img.shields.io/badge/Agentic_RAG-0F172A?style=flat-square)
![Prompt Caching](https://img.shields.io/badge/Prompt_Caching-0F172A?style=flat-square)
![pgvector](https://img.shields.io/badge/pgvector-336791?style=flat-square&logo=postgresql&logoColor=white)

**Languages**

<img src="https://skillicons.dev/icons?i=python,ts,js,java" alt="Python, TypeScript, JavaScript, Java"/> &nbsp; SQL

**Frontend**

<img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,html,css" alt="React, Next.js, Tailwind CSS, HTML, CSS"/> &nbsp; React Native

**Backend**

<img src="https://skillicons.dev/icons?i=fastapi,nodejs,express" alt="FastAPI, Node.js, Express"/> &nbsp; SQLAlchemy · Alembic · REST APIs

**Cloud and DevOps**

<img src="https://skillicons.dev/icons?i=aws,azure,docker,githubactions,linux" alt="AWS, Azure, Docker, GitHub Actions, Linux"/>

`Lambda` `API Gateway` `Aurora` `S3` `EC2` `VPC` `KMS` `Secrets Manager` `CloudFront` `Route 53` `App Service` `Container Apps` `Blob Storage` `Azure AD`

**Databases**

<img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis,firebase" alt="PostgreSQL, MySQL, MongoDB, Redis, Firebase"/>

**Tools**

<img src="https://skillicons.dev/icons?i=git,github,figma" alt="Git, GitHub, Figma"/>

<br/>

<!-- ===================== EXPERIENCE ===================== -->
## Professional Experience

### Forward Deployed Engineer · Quadric Information Technology Pvt. Ltd.
`March 2026 – Present` · Hyderabad

- Co-engineered **Tendorix AI**, an enterprise SaaS platform that automates RFP analysis and proposal writing using RAG, with an AI compliance engine and an adversarial auditor loop to reduce hallucinations
- Built **hybrid search** (pgvector + keyword) and **LLM-based requirement matching** using Claude and GPT-4o
- Developed **layout-preserving PDF/DOCX/XLSX ingestion** with PyMuPDF, pdfplumber, and Azure Document Intelligence for table recovery
- Built the **Next.js 14 / FastAPI collaborative editor** (TipTap) with version diffing and SharePoint / Google Drive sync
- Developed **ConQit**, a multi-tenant event-management PWA (iOS, Android, web) with per-event data isolation, an admin portal, SSO, and deployment on private AWS infrastructure

### Full Stack Developer · Quadric Information Technology Pvt. Ltd.
`January 2025 – March 2026` · Hyderabad

- Designed and delivered an enterprise **Conference Management Application for AstraZeneca**, owning full-stack development, Azure AD SSO, and AWS provisioning (Lambda, API Gateway, KMS, RDS Proxy, Aurora PostgreSQL)
- Built the **US OBU Planning Calendar for AstraZeneca** (React, SPFx, SharePoint Lists), serving **3,000 concurrent users across 10 business units**
- Led end-to-end development of **Hack2Build**, a white-label hackathon platform with multi-stage workflows
- Contributed to an AI-driven project for a Telangana government department and prototyped an AI solution for the judicial sector

### Full Stack Developer Intern · Quadric Information Technology Pvt. Ltd.
`June 2024 – September 2024` · Hyderabad

- Built features for **CloFast**, an AI reconciliation platform using NLP and generative AI to automate enterprise finance workflows

<br/>

<!-- ===================== PROJECTS ===================== -->
## Featured Projects

Much of my work was delivered for enterprise and government clients, so the source is private. Here is what I built and how.

<table>
<tr>
<td width="50%" valign="top">

### Tendorix AI
**Tender and proposal platform** · `Jul 2026 – Present`

4-phase proposal workflow (Understand → Plan → Draft → Finalize) using Claude Haiku and Sonnet, with prompt caching and model routing. Includes a vision-OCR and semantic-chunking pipeline, a capability-matching engine (embeddings + LLM evaluation), and a custom MCP server for Claude.

<sub>`Next.js` `TypeScript` `FastAPI` `PostgreSQL` `Redis` `Claude API` `Azure`</sub>

</td>
<td width="50%" valign="top">

### Conference Application · AstraZeneca
**Serverless conference platform** · `Dec 2025 – Apr 2026`

Role-based access for admins and attendees, with event, session, venue, and favourites management. Microsoft SSO via Azure AD. Full AWS stack provisioned from scratch.

<sub>`React` `Lambda` `Aurora PostgreSQL` `API Gateway` `Azure AD` `CloudFront` `KMS`</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### CloFast
**AI reconciliation platform** · `Jun 2024 – Jun 2025`

Multi-way (2, 3, and n-way) financial reconciliation on AWS Bedrock (Claude 3.5 Sonnet), **reducing manual effort by over 90%**. Textract and Gemini extract data from unstructured statements, and a real-time dashboard gives AI-generated recommendations for unresolved transactions.

<sub>`React` `Node.js` `AWS Textract` `Bedrock` `Gemini`</sub>

</td>
<td width="50%" valign="top">

### Hack2Build
**Hackathon management platform** · `Sep 2025 – Jan 2026`

Led as project lead: multi-stage workflows, reviewer assignment, automated scoring, and leaderboards for four user roles. Added NLP features for hackathon creation, resume parsing, and personalised recommendations, with CI/CD to Azure App Service.

<sub>`React` `Node.js` `MongoDB` `Azure` `Docker` `GitHub Actions`</sub>

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### Anusan and Nibandhana
**AI legal translation** · `Mar 2025 – Jul 2025`

English-to-Telugu translation platforms for Telangana High Court judgments and Secretariat documents, including headnote generation. Deployed on AWS (EC2, S3, Route 53) with Docker and GitHub Actions CI/CD.

<sub>`MERN` `Gemini` `AWS` `Docker`</sub>

</td>
</tr>
</table>

<br/>

<!-- ===================== CERTS & ACHIEVEMENTS ===================== -->
## Certifications and Achievements

**Certifications**

| Certificate | Issuer | Date |
|---|---|---|
| Advanced React | Meta | Dec 2023 |
| Full Stack Web Development | Codinza, powered by StudyOwl | Dec 2023 |
| Cloud Foundations | AWS Academy | Oct 2023 |
| Machine Learning Foundations | AWS Academy | Nov 2023 |
| Natural Language Processing | NPTEL | Apr 2023 |

**Achievements**

- Top 1% rank (12 of 3,000) at GeeksforGeeks Institute; 600+ problems solved on LeetCode and GeeksforGeeks
- AWS AI Agent Hackathon participant (2025), built CloFast POS reconciliation
- 2nd Prize, IoT Protothon (2023) · Best Full Stack Project Award, Codinza (2023)
- Smart India Hackathon participant (2022, 2023)
- B.Tech in Computer Science and Engineering (Honors), Vishnu Institute of Technology · CGPA 9.02/10

<br/>

<!-- ===================== GITHUB ACTIVITY ===================== -->
## GitHub Activity

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=Gnanigit&show_icons=true&hide_border=true&bg_color=0D111700&title_color=818CF8&icon_color=818CF8&text_color=C9D1D9&hide_title=false&count_private=true">
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api?username=Gnanigit&show_icons=true&hide_border=true&bg_color=FFFFFF00&title_color=4F46E5&icon_color=4F46E5&text_color=24292F&hide_title=false&count_private=true">
  <img alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=Gnanigit&show_icons=true&hide_border=true&bg_color=0D111700&title_color=818CF8&icon_color=818CF8&text_color=C9D1D9&count_private=true" height="165"/>
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=Gnanigit&layout=compact&hide_border=true&bg_color=0D111700&title_color=818CF8&text_color=C9D1D9">
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=Gnanigit&layout=compact&hide_border=true&bg_color=FFFFFF00&title_color=4F46E5&text_color=24292F">
  <img alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Gnanigit&layout=compact&hide_border=true&bg_color=0D111700&title_color=818CF8&text_color=C9D1D9" height="165"/>
</picture>

<br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=Gnanigit&theme=transparent&hide_border=true&ring=818CF8&fire=818CF8&currStreakLabel=C9D1D9&sideLabels=C9D1D9&currStreakNum=C9D1D9&sideNums=C9D1D9&dates=8B949E">
  <source media="(prefers-color-scheme: light)" srcset="https://streak-stats.demolab.com?user=Gnanigit&theme=transparent&hide_border=true&ring=4F46E5&fire=4F46E5&currStreakLabel=24292F&sideLabels=24292F&currStreakNum=24292F&sideNums=24292F&dates=57606A">
  <img alt="GitHub streak" src="https://streak-stats.demolab.com?user=Gnanigit&theme=transparent&hide_border=true&ring=818CF8&fire=818CF8&currStreakLabel=C9D1D9&sideLabels=C9D1D9&currStreakNum=C9D1D9&sideNums=C9D1D9&dates=8B949E"/>
</picture>

</div>

<br/>

<!-- ===================== LEARNING ===================== -->
## Currently Learning

- Evaluation and observability for **agentic RAG** systems
- Designing **MCP servers** and tool interfaces for LLM agents
- Cost and latency optimization for LLM workloads (prompt caching, model routing)
- Production patterns for **multi-tenant, secure cloud architectures** on AWS and Azure

<br/>

<!-- ===================== CONNECT ===================== -->
## Connect With Me

I'm open to conversations about AI engineering, RAG systems, and full-stack product work.

<a href="https://www.linkedin.com/in/gnaneswar-yalla-730ba4250"><img src="https://img.shields.io/badge/LinkedIn-gnaneswar--yalla-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:gnani4412@gmail.com"><img src="https://img.shields.io/badge/Email-gnani4412@gmail.com-4F46E5?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="https://github.com/Gnanigit"><img src="https://img.shields.io/badge/GitHub-Gnanigit-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>

<!-- ===================== FOOTER ===================== -->
<div align="center">

<sub>Hyderabad, India · Building practical AI systems that ship.</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&height=100&color=0:4F46E5,100:0F172A&section=footer" alt="" width="100%"/>

</div>
