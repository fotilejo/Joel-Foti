# Joel Foti — Portfolio

**Information Systems Specialist | Metadata & Data Architecture | Buenos Aires, Argentina**

🌐 [fotilejo.github.io/joel-foti](https://fotilejo.github.io/Joel-Foti)

---

## About

I'm a library and information science professional with a strong technical focus on legacy systems modernization, metadata architecture, and database engineering. My technical scope covers the entire data lifecycle, from building robust backend architectures and managing complex databases to designing highly functional, modern frontend web interfaces.

My background is unusual in the tech space: I hold degrees from the Universidad de Buenos Aires (UBA) in both Library and Information Science and in History. This academic foundation gives me a rigorous, structured approach to modeling complex data at scale (Information Architecture, Semantic Web, and Knowledge Graphs). My teaching experience provides me with strong communication skills and group management abilities, essential for translating complex technical architectures to stakeholders. I currently work as a professional librarian at INTI (Argentina's National Institute of Industrial Technology), where I architect and build the library's web systems.

I leverage AI tools (Claude, Gemini) as delivery multipliers to develop applications—a methodology known as *vibe coding*. Crucially, my core value in this process is the **Human-in-the-loop** engineering approach: I do not merely prompt the AI, but actively steer the software architecture, audit generated code, and troubleshoot complex logical or semantic bugs based on deep data observation and technical corrections. 

I studied English for eight years at the UBA Language Lab, holding a B2 Upper-Intermediate certification, allowing me to engage seamlessly with technical documentation and international environments.

---

## Featured Projects

### 1. Semantic Knowledge Graph & Recommendation Engine
**Status:** Completed (Phase 2) | **Stack:** `Neo4j` · `Cypher` · `Python (ETL)` · `JSON`

Transformed a flat, legacy library catalog into a dynamic, interconnected Property Graph database to enable advanced data discovery and machine-readable context.
* Designed an ETL pipeline to parse and normalize bibliographic metadata into a structured JSON topology (992 nodes, over 2.200 relations).
* Engineered Cypher ingestion scripts to materialize the network in a Neo4j backend environment.
* **Human-in-the-loop & Debugging:** Actively audited AI-generated ingestion logic, successfully debugging silent operational failures by identifying semantic mapping discrepancies (e.g., JSON key mismatches like `enlaces` vs `relaciones`) and refactoring code to bypass local security restrictions via cloud data fetching.
* Developed a **Content-Based Filtering Recommendation Engine** that calculates semantic distance between documents via shared thematic descriptors.
* Implemented multi-hop data retrieval queries (GraphRAG architecture) to extract precise, hallucination-free entity profiles, preparing the catalog for future LLM/AI integrations.

### 2. INTI Library Web System Core Modernization
**Live:** [www-biblio.inti.gob.ar/prueba](http://www-biblio.inti.gob.ar/prueba/) | **Stack:** `ISIS/WXIS` · `Apache` · `HTML5/CSS3/JS`

Led the technical redesign and modernization of the institutional library web system, which runs on legacy ISIS databases with a WXIS/Apache backend engine.
* Reverse-engineered existing `.xis` scripts and ISIS format files to map the full search and display logic.
* Rewrote core search logic scripts from scratch to optimize multi-field queries and special character sanitization.
* Engineered a real-time search suggestion interface by extracting and normalizing the full thesaurus into a JSON API.
* Designed a responsive, modern, and symmetrical frontend UI, including block navigation, modal transitions, and tonal gray search components.
* Connected isolated data silos (Technical Dictionaries) to the main catalog network.
* Applied Apache server hardening: security headers, caching, and baseline SEO configuration.

---

## Skills & Knowledge Areas

| Area | Details |
|---|---|
| Data Architecture & Backend | Neo4j, Cypher, Relational Databases (SQL/MySQL), Knowledge Graphs, ETL Pipelines |
| Web Development (Frontend) | HTML5, CSS3, JavaScript, JSON APIs, UI/UX (modern, symmetrical design) |
| Library Systems | ISIS/ABCD, Koha, ExLibris Alma, Greenstone 3, DSpace, WXIS scripting |
| Metadata & Semantic Web | RDA, MARC21, AACR2, RDF, OWL/Ontologies, controlled vocabularies |
| AI & Software Engineering | Prompt-driven development (vibe coding), Human-in-the-loop debugging, AI steering |
| Infrastructure | Apache server administration, system troubleshooting, hardware driver management |
| Languages | Spanish (native) · English B2 Upper-Intermediate (UBA Language Lab) |

---

## Education 

- **Licenciatura en Ciencia de la Información** — UBA *(in progress)*
- **Profesorado de Enseñanza Media y Superior en Bibliotecología y Ciencia de la Información** — UBA
- **Profesorado de Enseñanza Media y Superior en Historia** — UBA

**Certifications:** English B2 Upper-Intermediate (Laboratorio de Idiomas, UBA) | Databases SQL & MySQL | Introduction to Python

---

## Contact

- 📧 fotilejo@gmail.com
- 💼 [LinkedIn](https://www.linkedin.com/in/joel-foti)
- 🐙 [GitHub](https://github.com/fotilejo)
