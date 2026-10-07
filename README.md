<img src="https://huzaifah-dev.vercel.app/github-banner.png" alt="Huzaifah, AI engineer specializing in voice agents" width="100%" />

I design and ship production AI systems, from LLM and RAG applications to the backends that run them at scale. I'm currently building the voice agents and backend for an AI calling platform that dials 50,000+ leads a day.

[Portfolio](https://huzaifah-dev.vercel.app) · [LinkedIn](https://www.linkedin.com/in/huzaifah27) · [Email](mailto:huzaif027@gmail.com) · [Medium](https://medium.com/@huzaif027)

<br />

<img src="https://huzaifah-dev.vercel.app/github-capabilities.png" alt="What I build. Voice agents, my specialty: AI agents that hold real phone and web conversations, from telephony and real-time speech to turn-taking, machine detection and scale (50,000+ leads a day, 100+ concurrent calls). LLM, RAG and ML: assistants and agents grounded in your own data, retrieval and knowledge graphs, and ML from training to deployment. Production systems: backends built for scale and low latency, with async APIs, autoscaling, concurrency control, CI/CD and monitoring on AWS." width="100%" />

## Experience

### Crypto Association Georgia
**AI Engineer** · Remote, Georgia · Jan 2026 to now

Voice agents and backend for [Callixo](https://www.callixo.ai), an AI calling platform dialing 50,000+ leads a day.

- Designed it provider-agnostic: one CRM, several voice engines. Built and ran it on LiveKit, Retell AI, FreeSWITCH with a custom PJSIP media bot, and SignalWire, then kept what won on cost and conversion.
- Built the scaling: an EC2 Auto Scaling Group that grows and shrinks the agent fleet on a custom load metric, a warm pool for fast scale-out, and a drain hook so scaling down never drops a live call.
- Machine detection for voicemail, IVRs and call screeners that runs alongside the call and leans toward keeping real people on the line.
- FastAPI and PostgreSQL backend, Next.js dashboards, shipped with Docker and GitHub Actions to AWS and monitored with Prometheus and Grafana.

### Lanciere Technologies
**AI Developer Intern** · Hyderabad · Feb to Aug 2025

- Took an AI interview platform to voice-to-voice interviews on OpenAI, Llama and Whisper, cutting hiring cycles by 30%.
- Cheat detection with YOLOv11, OpenCV and voice analytics inside the live interview pipeline.
- Agentic interviewer on LangGraph and CrewAI with persistent memory across a full interview.
- Cut live interview latency with batching and caching, serving 100+ assessments a day on AWS.

## Selected projects

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/Sa1f27/MindCanvas"><img src="https://huzaifah-dev.vercel.app/projects/mindcanvas-ss-2.png" alt="MindCanvas screenshot" width="100%" /></a>
      <h3><a href="https://github.com/Sa1f27/MindCanvas">MindCanvas</a></h3>
      Turns scattered web data into a queryable knowledge graph with a RAG assistant on top. Published as a <a href="https://ijesr.org/index.php/ijesr/article/view/1635">first-author paper</a>.
      <br /><br />
      <code>FastAPI</code> <code>LangChain</code> <code>Supabase</code> <code>React</code>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/Sa1f27/Live-Agent"><img src="https://huzaifah-dev.vercel.app/projects/ai-conversational-agent.jpg" alt="Live Agent screenshot" width="100%" /></a>
      <h3><a href="https://github.com/Sa1f27/Live-Agent">Live Agent</a></h3>
      Speech-to-speech agent that holds unscripted voice conversations in the browser, streaming PCM over WebSockets. <a href="https://live-agent-eoj3.onrender.com">Try it live</a>.
      <br /><br />
      <code>AudioWorklet</code> <code>Gemini ADK</code> <code>WebSockets</code> <code>FastAPI</code>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/Sa1f27/predictive-maintenance-mlops"><img src="https://huzaifah-dev.vercel.app/projects/predictive-ss-2.png" alt="Predictive Maintenance screenshot" width="100%" /></a>
      <h3><a href="https://github.com/Sa1f27/predictive-maintenance-mlops">Predictive Maintenance</a></h3>
      End-to-end MLOps pipeline predicting equipment failure from sensor data. 91.2% accuracy, automated retraining and CI/CD.
      <br /><br />
      <code>MLflow</code> <code>scikit-learn</code> <code>Docker</code> <code>AWS ECS</code>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/Sa1f27/HireSense-Final"><img src="https://huzaifah-dev.vercel.app/projects/hiresense.jpg" alt="HireSense screenshot" width="100%" /></a>
      <h3><a href="https://github.com/Sa1f27/HireSense-Final">HireSense</a></h3>
      Candidate verification and voice interviews: cross-platform profile checks, automated reference calls, scored transcripts.
      <br /><br />
      <code>Next.js</code> <code>Supabase</code> <code>Whisper</code> <code>ElevenLabs</code>
    </td>
  </tr>
</table>

More in the [full project list](https://huzaifah-dev.vercel.app/projects).

## Stack

| | |
| --- | --- |
| **Voice** | LiveKit, Retell AI, SIP/RTP, FreeSWITCH, PJSIP, SignalWire, Twilio, STT/TTS, AMD |
| **Backend** | Python, asyncio, FastAPI, PostgreSQL, Redis, WebSockets, REST |
| **AI** | LLMs, RAG, LangGraph, LangChain, CrewAI, Qdrant, Transformers, OpenCV |
| **Infra** | AWS (EC2, RDS, S3, Auto Scaling, Elastic IP), Docker, Nginx, GitHub Actions, Prometheus, Grafana |
| **Production** | EC2 Auto Scaling on custom metrics, warm pools, drain hooks, concurrency limits, connection pooling, Redis caching and queues |
| **Frontend** | TypeScript, React, Next.js, Tailwind |

## Highlights

- **First-author paper:** *An AI system for transforming scattered web data into an interactive, queryable knowledge graph*, International Journal of Engineering & Science Research, 2026.
- **Hackathons:** seven, including the OpenAI Buildathon and Google's Agentic AI Hackathon, with two podium finishes.
- **Practice:** 291 LeetCode problems solved and six technical articles on [Medium](https://medium.com/@huzaif027).
- **Education:** B.E. Computer Science (AI & ML), First Division with Distinction.

<br />

Open to full-time AI engineering roles and freelance projects. The fastest way to reach me is [email](mailto:huzaif027@gmail.com).
