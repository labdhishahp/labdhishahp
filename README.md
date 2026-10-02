<img src="assets/labdhi.jpg" alt="Photo of Labdhi Shah" width="130" align="right">

# Labdhi Shah

AI & Data Science engineering student building practical AI systems.

Most of my work is about what happens after you call the model: making sure an answer is grounded in real evidence, measuring whether it's actually right, and keeping the decisions that matter in deterministic code. I'm in my final year at Thakur College of Engineering and Technology, Mumbai, graduating in 2027.

Previously a Software Developer Intern at **Miscot Systems Pvt. Ltd.** (Dec 2025 – Feb 2026).

<br clear="right">

### Projects

**[L-Mart](https://github.com/labdhishahp/ai_loyalty)**: AI loyalty operations agent<br>
An agent that investigates questions about a fictional retailer's loyalty programme and drafts campaigns to fix them. The model only asks questions and interprets answers. Typed tools fetch the data, policy code checks every proposal, and nothing runs without a person's approval.<br>
`Python` `FastAPI` `PostgreSQL` `MCP`

**[Knowledge Assistant](https://github.com/labdhishahp/rag)**: document Q&A with citations · [live demo](https://rag-ivory-phi.vercel.app)<br>
Upload a PDF, Word document or source file and ask questions about it. Answers cite the page and section they came from, and the system declines to answer when retrieval finds no good evidence. I evaluated retrieval on a 28-question test set (0.826 recall@3) and used the same set to decide where it should refuse.<br>
`Python` `FastAPI` `Next.js` `PostgreSQL`

**Document intelligence and OCR**: internship work, Miscot Systems Pvt. Ltd.<br>
During my internship, I worked on document-intelligence and OCR pipelines: a PaddleOCR pipeline (DBNet + PARSeq) benchmarked against DocTR, YOLO-based field detection, Aadhaar masking, and FastAPI endpoints for other services. This was company work, so the code isn't public.

**CarbonGrid** · [live demo](https://carbongrids.netlify.app)<br>
A campus sustainability platform built in 24 hours with a team of four for the IndiaNext national hackathon. Our team placed 2nd of 234 teams.

### How I work

- **Measure before making claims.** The refusal threshold and chunking strategy in the Knowledge Assistant were chosen from test results, not intuition.
- **Keep the decisions that matter in deterministic code.** Models are good at reading and drafting. Whether something is allowed, and whether it runs, belongs in code and with people.
- **Fail honestly.** When the evidence isn't there, the system should say so. A clear refusal is better than a confident wrong answer.

### Tools

Python · TypeScript · SQL · FastAPI · Next.js · PostgreSQL · pgvector · MCP · Claude and Gemini APIs · PaddleOCR · YOLO

[LinkedIn](https://www.linkedin.com/in/labdhishahsp) · [Email](mailto:labdhishah102005@gmail.com)
