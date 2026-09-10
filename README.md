🚀 The Problem & Our Solution

The current landscape for public sector upskilling faces critical challenges: iGOT catalog overload, lack of baseline diagnostics, unexplained test scores, and siloed digital/physical training streams.

SwaRuchi solves this by delivering a unified, AI-driven learning ecosystem. We automate role profiling across MoSPI's 4 FRAC pillars, provide zero-hallucination diagnostic assessments, and synchronize asynchronous iGOT modules with live NSSTA cohorts to create a seamless hybrid learning roadmap.

✨ Key Features & Innovation

🎯 Precision Upskilling: Deficit-based training assignment derived from adaptive baseline diagnostics to eliminate redundant learning hours.

🧠 Multimodal RAG Engine: Real-time generation of unique, structured MCQ banks ingested from internal MoSPI manuals and multimedia via Whisper ASR.

📊 Deterministic FRAC Math: Mathematical, zero-hallucination benchmark scoring for highly accurate skill-gap analysis.

🔍 Source-Cited Feedback: Delivers instant grading with contextual rationales by deep-linking directly to exact manual pages and video timestamps.

🔄 Dual Stream Sync: A decoupled bridge architecture that syncs national digital training (iGOT) with on-site physical schedules (NSSTA) without altering the core iGOT codebase.

🗣️ GIGW 3.0 & Voice AI: A scalable, bilingual AI chatbot providing localized statistical tutoring and native-language support for field investigators.

🛠️ Tech Stack Architecture

Frontend & UI

Framework: Next.js, React, TypeScript

Mobile/Cross-Platform: Flutter

Styling & Components: Tailwind CSS, Shadcn UI

Backend & Database

Server: Node.js + Express (Core), Python/Flask (AI Microservices)

Database: MongoDB

Infrastructure: AWS Cloud Hosting

AI & Machine Learning

LLM Engine: Google Gemini

Audio/Speech: Whisper ASR (for multimedia ingestion)

Search: Vector search & OCR pipeline for manual indexing

📈 Feasibility & Market Size

SwaRuchi is designed to scale across the government workforce ecosystem:

TAB (Total Addressable Beneficiaries): 46,00,000 Public Sector Workforce (Full Mission Karmayogi Central mandate)

SAB (Serviceable Available Beneficiaries): 25,000 - 40,000 National Statistical Workforce (Central + State)

SOB (Serviceable Obtainable Beneficiaries): 15,000 Core MoSPI & NSSO Personnel

Revenue Streams:

B2G Revenue: MoSPI implementation, DoPT integration fees, and state government deployments.

Secondary Revenue: Content-creation-as-a-service, premium analytics dashboards, and proctored certification fees.

⚙️ Setup & Installation

1. Clone the Project

git clone https://github.com/your-username/swaruchi.git
cd swaruchi


2. Frontend Setup (Next.js)

cd client
npm install
npm run dev


🌐 Frontend runs on: http://localhost:3000

3. Backend Setup (Node & Python)

Node.js Core Server:

cd server
npm install
npm run start


Python AI Microservices:

cd ai-service
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
flask run


4. Environment Variables

Create .env files in your respective directories with these keys:

MONGODB_URI (Your MongoDB Connection String)

GEMINI_API_KEY (For AI Quiz/Feedback Generation)

AWS_ACCESS_KEY (For cloud storage/hosting)

Built with ❤️ by Code_Cadets 




Developed for Smart India Hackathon 2026 to revolutionize public sector upskilling.
