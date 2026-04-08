# Abhishek

I build enterprise systems that run in production. Currently a third-year CS student.

**I built [BharatPACS](https://github.com/CodingWoding) — a cloud PACS and radiology workflow platform running in 1,000+ hospitals across India.** Solo-built in 3 months. ₹50K/month infrastructure serving the entire network.

It handles DICOM study ingestion, integrated OHIF viewer, online radiology reporting with a custom-built document engine, multi-tenant architecture with 12+ role types, real-time WebSocket collaboration, and a complete verification/assignment workflow — from study upload to final report download.

I also built the **C# document generation engine** from scratch — handles PDF/DOCX output with dynamic headers, footers, embedded images, tables, signatures, watermarks, and QR codes. Built it because existing tools couldn't do what I needed at the cost I needed.

---

### What I work with

**Core:** Node.js · React · MongoDB · Express · TypeScript  
**Infrastructure:** Docker · Nginx · Redis · GitHub Actions · DigitalOcean  
**Storage:** Cloudflare R2 · Wasabi S3  
**Medical imaging:** Orthanc (DICOM) · OHIF Viewer  
**Document engine:** C# · Puppeteer (fallback)  
**Other:** Python · PostgreSQL · WebSockets · REST APIs

---

### Architecture decisions I've made in production

- **Multi-tenant data isolation** across 1,000+ organizations with per-org middleware
- **Cloudflare R2 + Wasabi S3** over AWS S3 — cut storage costs by 3-4x at scale with zero egress fees
- **Custom C# rendering engine** over Puppeteer — full control over layout precision, cost, and speed
- **Redis queuing** for study processing pipelines and real-time notifications
- **JWT + refresh token auth** with tab-isolated sessions and constant-time API key comparison
- **Workflow state machine** modeling the full radiology lifecycle: 12 states from ingestion to archive

---

### What I'm building next

Exploring enterprise data infrastructure — document processing pipelines, AI-assisted radiology reporting, and API-first document generation services.

Open to conversations about healthcare tech, enterprise architecture, and building complex systems as a solo developer.

---

<p>
<a href="https://www.linkedin.com/in/codingwoding"><img src="https://img.shields.io/badge/LinkedIn-0a77b6?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
</p>
