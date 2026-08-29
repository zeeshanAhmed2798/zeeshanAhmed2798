<!--
  DRAFT profile README for github.com/zeeshanAhmed2798/zeeshanAhmed2798
  This is a complete, ready-to-paste replacement for the current Readme.md
  Search this file for "TODO" / HTML comments before publishing — a few items
  need Zeeshan's confirmation (employer name, portfolio URL, a couple of live
  demo links) and are deliberately left as placeholders rather than guessed
  See RECOMMENDATIONS.md for the reasoning behind each change
-->

# 💫 About Me

🤖 AI/ML Engineer building production **agentic AI and voice AI systems**
📊 Data Scientist — Python, SQL, Power BI & applied ML/DL
<!-- TODO: confirm current employer name/title before publishing — VoxKit and SdevaX both
     appear across different live sources (resume, portfolio, GitHub, LinkedIn). Replace the
     line below with the confirmed name once you've reconciled it everywhere else. -->
💼 AI Engineer in production voice/GenAI systems — building real-time voice agents, RAG pipelines & multi-tenant AI platforms
⭐ ML/Data Science Freelancer @ Fiverr — 100% Response Rate <!-- TODO: confirm current star rating (sources show 4.7 live vs 5.0 elsewhere) before adding a number back in -->
🎓 BS Computer Science @ Superior University, Lahore (2022–2026)
🏆 Kaggle Notebooks Expert | Google Data Analytics Certified
🚀 Currently building: Urdu-first voice AI for healthcare, multi-tenant LiveKit ordering pipelines, and RAG/agentic systems

## 🧭 My Journey

```
C++ games & Android apps  →  Web dev (Flask, React Native)  →  Data Science & EDA  →  Agentic AI & Voice AI
      (2023)                       (2023–2024)                    (2024)                (2025–2026)
```

Started with a bouncing-ball game and a chess engine in C++ during my first two semesters, moved into
web development, then spent a year deep in data science — EDA, Kaggle notebooks, classical ML. Since
2025 I've been building production agentic and voice AI systems: RAG chatbots, MCP servers, and
multi-tenant voice agents used in real hospital and restaurant workflows. Every stage is still up here —
I'd rather show the full arc than hide where I started.

## 🌐 Socials

<!-- TODO: replace the Portfolio href below — it currently points at this GitHub profile instead of
     the actual portfolio site. Grab the live deployment URL and swap it in. This was a live bug on
     the previous version of this README. -->
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/zeeshan--ahmad) [![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?logo=kaggle&logoColor=white)](https://kaggle.com/zeeshanahmad124586) [![Fiverr](https://img.shields.io/badge/Fiverr-1DBF73?logo=fiverr&logoColor=white)](https://fiverr.com/ds_ai_byzeeshan) [![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/zeeahmad0) [![Facebook](https://img.shields.io/badge/Facebook-%231877F2.svg?logo=Facebook&logoColor=white)](https://facebook.com/profile.php?id=100090239561697) [![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:zeeshan.ahmad124586@gmail.com) [![Portfolio](https://img.shields.io/badge/Portfolio-000000?logo=About.me&logoColor=white)](https://REPLACE-WITH-YOUR-PORTFOLIO-URL.com)

<!-- Optional add: LeetCode badge — he holds two 50-day badges, worth surfacing algorithmic-fundamentals signal.
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?logo=leetcode&logoColor=black)](https://leetcode.com/u/Zeeshan_Ahmed_)
-->

---

# 🚀 Featured Projects

### 🏥 Flagship: VoxCare — Urdu-First Voice AI Agent for Healthcare
Final Year Project (Superior University, supervised by Dr. Jawad Ahmad, built with a 2-person team).
A realtime, Urdu-first voice AI agent that lets patients book, reschedule, and cancel hospital
appointments over a live phone call — multi-tenant SaaS architecture with RBAC, call logging, and an
analytics dashboard.
**Tech:** Python · FastAPI · VAPI · GPT-4o (tool calling) · LangChain · LangGraph · Redis · Twilio · PostgreSQL
🔗 [Live demo](https://voxcare-ai.vercel.app) · [AI Agent repo](https://github.com/voxcare-ai/ai-agent) · [Frontend repo](https://github.com/voxcare-ai/front-end)

### 🏠 Capstone: Lahore Real Estate Intelligence System
End-to-end ML pipeline for Lahore property data: scraping → cleaning → feature engineering → 5
regression models compared (Linear, Ridge, Lasso, Random Forest, XGBoost) with cross-validation and
hyperparameter tuning, a TF-IDF + cosine-similarity content-based property recommender, and an
Explainable AI module, shipped as a multi-page Streamlit app.
**Tech:** Python · scikit-learn · XGBoost · Pandas · Streamlit
🔗 [Repo](https://github.com/zeeshanAhmed2798/real-estate-intelligence-sys) <!-- TODO: add live demo link -->

### 🤖 Agentic AI & GenAI
- **[YouTube RAG Chatbot](https://github.com/zeeshanAhmed2798/YouTube-Chatbot)** — Full RAG pipeline over YouTube transcripts: chunking, 384-dim sentence-transformer embeddings, Pinecone vector DB with custom namespaces, Groq LLM, LangChain orchestration, Streamlit UI with session memory. <!-- TODO: add live demo / walkthrough video link -->
- **[Cold Email Generator](https://github.com/zeeshanAhmed2798/COLD-EMAIL)** — LLaMA-orchestrated pipeline that scrapes a company's careers page, extracts role requirements, vector-matches them against portfolio projects, and drafts a personalized cold email.
- **[n8n Personal Assistant](https://github.com/zeeshanAhmed2798/n8n-personal-assistant)** — Natural-language agent orchestrating Google Calendar, Gmail, Tasks, Docs, and Sheets through n8n workflow automation.
- **VoxKit Voice Agent (LiveKit)** — Modular-monolith, multi-tenant voice ordering system for restaurants, built on LiveKit + FastAPI + GPT-4o. *(production work — link to the relevant repo once confirmed public/shareable.)*
- **Hybrid Voice Pipeline** — OpenAI STT+VAD → LangChain → ElevenLabs TTS over Twilio; ~15x cheaper than the OpenAI Realtime API while preserving barge-in and function calling. <!-- TODO: no repo in the current repo list obviously matches this project — verify which repo it is (may be private/unlisted) and link it here. -->

### 📊 Data Science, ML & BI
- **[PSL Analytics Platform](https://github.com/zeeshanAhmed2798/psl-stats-api)** — 73,785 rows of ball-by-ball PSL cricket data behind a public REST API (FastAPI, deployed on Vercel) plus a Streamlit dashboard; backed by two self-published Kaggle datasets.
- **[SMS Spam Classifier](https://github.com/zeeshanAhmed2798/sms-spam-classifier)** — TF-IDF + Naive Bayes + stacking ensembles on 5,572 SMS messages: 100% precision, 95–97% accuracy, deployed with Streamlit.
- **[Cats vs Dogs CNN](https://github.com/zeeshanAhmed2798/cat-vs-dog)** — TensorFlow/Keras CNN with a full optimization journey (baseline → dropout → batch norm → L2): 81.85% validation accuracy, 88.71% train accuracy.
- **[WhatsApp Chat Analyzer](https://github.com/zeeshanAhmed2798/whatsapp-chat-analyzer)** — Streamlit app for message stats, timelines, word clouds, activity heatmaps, and emoji analysis.
- **Interactive Power BI Dashboards** — HR attrition analytics, e-commerce sales, hotel-cancellation analysis, and a 10-year non-profit financial EDA across 3 charities.

### 🕷️ Web Scraping & Automation
- **[Stepstone Job Market Analyzer](https://github.com/zeeshanAhmed2798/stepstone-job-scraper)** — Selenium scraper covering 1,300+ Düsseldorf tech job listings, handling pagination, cookies, and dynamic scroll.
- **[Yahoo Finance Scraper](https://github.com/zeeshanAhmed2798/yahoo-finance-scraper)** — OOP-refactored Selenium scraper pulling real-time price, volume, market cap, and P/E data for 50+ stocks daily.

---

# 💻 Tech Stack

### Languages
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white) ![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white) ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

### AI/ML & Agentic AI
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white) ![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white) ![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)

### Voice AI & Realtime
![Twilio](https://img.shields.io/badge/Twilio-F22F46?style=for-the-badge&logo=Twilio&logoColor=white) <!-- LiveKit and VAPI don't have shields.io/simple-icons logo support as of writing — keep as plain badges or text if added -->

### Data Science & Analytics
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black) ![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white) ![Scipy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white) ![Power BI](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black) ![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

### Frameworks & Tools
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi) ![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white) ![Streamlit](https://img.shields.io/badge/Streamlit-%23FE4B4B.svg?style=for-the-badge&logo=streamlit&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

### Web Scraping & Automation
![Selenium](https://img.shields.io/badge/-selenium-%43B02A?style=for-the-badge&logo=selenium&logoColor=white) ![BeautifulSoup](https://img.shields.io/badge/Beautiful_Soup-3776AB?style=for-the-badge&logo=python&logoColor=white)

### Databases
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white) ![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white) ![Firebase](https://img.shields.io/badge/firebase-a08021?style=for-the-badge&logo=firebase&logoColor=ffcd34) ![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=for-the-badge&logo=pinecone&logoColor=white) ![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)

### Cloud & Deployment
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white) ![Render](https://img.shields.io/badge/Render-%46E3B7.svg?style=for-the-badge&logo=render&logoColor=white) ![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white)

### Other Tools
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white) ![Jupyter](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white) ![VS Code](https://img.shields.io/badge/VS_Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)

<!--
  Trimmed from the previous version: Heroku, Anaconda, Canva badges (least relevant to the current
  AI/ML positioning) and Web Scraping's own category folded net-new logos in. Added: PyTorch, Redis
  (both real, verified skills from the brief that weren't previously badged despite being used in
  production work). If you'd rather keep every original badge, that's a fine call too — see
  RECOMMENDATIONS.md Priority 3 on badge count, it's optional, not a fix.
-->

---

# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=zeeshanAhmed2798&theme=tokyonight&hide_border=false&include_all_commits=true&count_private=true)<br/>
![](https://github-readme-streak-stats.herokuapp.com/?user=zeeshanAhmed2798&theme=tokyonight&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=zeeshanAhmed2798&theme=tokyonight&hide_border=false&include_all_commits=true&count_private=true&layout=compact)

## 🏆 GitHub Trophies
![](https://github-profile-trophy.vercel.app/?username=zeeshanAhmed2798&theme=tokyonight&no-frame=false&no-bg=false&margin-w=4)

### ✍️ Dev Quote
![](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight)

---
[![](https://visitcount.itsvg.in/api?id=zeeshanAhmed2798&icon=2&color=6)](https://visitcount.itsvg.in)

<!-- Proudly created with passion for AI and data -->
