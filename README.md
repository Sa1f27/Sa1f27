<img src="https://huzaifah-dev.vercel.app/github-banner.png" alt="Huzaifah, AI engineer specializing in voice agents" width="100%" />

I design and ship production AI systems, from LLM and RAG applications to the backends that run them at scale. I'm currently building the voice agents and backend for an AI calling platform that dials 50,000+ leads a day.

[Portfolio](https://huzaifah-dev.vercel.app) · [LinkedIn](https://www.linkedin.com/in/huzaifah27) · [Email](mailto:huzaif027@gmail.com) · [Medium](https://medium.com/@huzaif027)

## What I build

**Voice agents** (specialty). AI agents that hold real phone and web conversations: telephony, real-time speech, turn-taking, machine detection, and running them at scale.

**LLM, RAG and ML.** Assistants and agents grounded in your own data, retrieval and knowledge graphs, and ML models taken from training to deployment.

**Production systems.** Backends built for scale and low latency: async APIs, autoscaling, concurrency control, CI/CD and monitoring on AWS.

## Experience

**AI Engineer, Crypto Association Georgia** · Remote · Jan 2026 to now

Voice agents and backend for [Callixo](https://www.callixo.ai), an AI calling platform dialing 50,000+ leads a day.

- Designed it provider-agnostic: one CRM, several voice engines. Built and ran it on LiveKit, Retell AI, FreeSWITCH with a custom PJSIP media bot, and SignalWire, then kept what won on cost and conversion.
- Built the scaling: an EC2 Auto Scaling Group that grows and shrinks the agent fleet on a custom load metric, a warm pool for fast scale-out, and a drain hook so scaling down never drops a live call. 100+ concurrent calls at sub-second turns.
- Machine detection for voicemail, IVRs and call screeners that runs alongside the call and leans toward keeping real people on the line.
- FastAPI and PostgreSQL backend, Next.js dashboards, shipped with Docker and GitHub Actions to AWS and monitored with Prometheus and Grafana.

**AI Developer Intern, Lanciere Technologies** · Hyderabad · Feb to Aug 2025

- Took an AI interview platform to voice-to-voice interviews on OpenAI, Llama and Whisper, cutting hiring cycles by 30%.
- Cheat detection with YOLOv11, OpenCV and voice analytics inside the live interview pipeline.
- Agentic interviewer on LangGraph and CrewAI with persistent memory across a full interview.
- Cut live interview latency with batching and caching. Deployed on AWS, serving 100+ assessments a day.

## Selected projects

**[MindCanvas](https://github.com/Sa1f27/MindCanvas).** Turns scattered web data into a clustered, queryable knowledge graph with a RAG assistant on top. Published as a [first-author paper](https://ijesr.org/index.php/ijesr/article/view/1635).
`FastAPI` `LangChain` `Supabase` `React` `Cytoscape.js`

**[Live Agent](https://github.com/Sa1f27/Live-Agent).** Speech-to-speech agent that holds unscripted voice conversations in the browser, streaming PCM over WebSockets. [Try it live](https://live-agent-eoj3.onrender.com).
`AudioWorklet` `Gemini ADK` `WebSockets` `FastAPI`

**[Predictive Maintenance](https://github.com/Sa1f27/predictive-maintenance-mlops).** End-to-end MLOps pipeline predicting equipment failure from sensor data. 91.2% accuracy, automated retraining and CI/CD.
`MLflow` `scikit-learn` `FastAPI` `Docker` `AWS ECS`

**[HireSense](https://github.com/Sa1f27/HireSense-Final).** Candidate verification and voice interviews: cross-platform profile checks, automated reference calls, scored transcripts.
`Next.js` `Supabase` `Whisper` `ElevenLabs`

More in the [project index](https://huzaifah-dev.vercel.app/projects).

## Stack

| | |
| --- | --- |
| **Voice** | LiveKit, Retell AI, SIP/RTP, FreeSWITCH, PJSIP, SignalWire, Twilio, STT/TTS, AMD |
| **Backend** | Python, asyncio, FastAPI, PostgreSQL, Redis, WebSockets, REST |
| **AI** | LLMs, RAG, LangGraph, LangChain, CrewAI, Qdrant, Transformers, OpenCV |
| **Infra** | AWS (EC2, RDS, S3, Auto Scaling, Elastic IP), Docker, Nginx, GitHub Actions, Prometheus, Grafana |
| **Production** | EC2 Auto Scaling on custom metrics, warm pools, drain hooks, concurrency limits, connection pooling, Redis caching and queues, observability |
| **Frontend** | TypeScript, React, Next.js, Tailwind |

## Also

- First-author paper: *An AI system for transforming scattered web data into an interactive, queryable knowledge graph*, International Journal of Engineering & Science Research, Apr 2026.
- Seven hackathons including the OpenAI Buildathon and Google's Agentic AI Hackathon, with two podium finishes.
- 291 LeetCode problems solved. Six technical articles on [Medium](https://medium.com/@huzaif027).
- B.E. Computer Science (AI & ML), First Division with Distinction.

Open to full-time AI engineering roles and freelance projects. The fastest way to reach me is [email](mailto:huzaif027@gmail.com).
