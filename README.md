<img src="https://huzaifah-dev.vercel.app/github-banner.png?v=2" alt="Huzaifah. AI engineer: I build AI agents, LLM systems and the backends that run them in production. Specialty: voice agents." width="100%" />

I build AI agents, LLM systems and the backends that run them in production. My specialty is voice agents, AI that holds real phone conversations at scale. Based in Hyderabad, India, working remotely.

You can find more on my [portfolio](https://huzaifah-dev.vercel.app), [LinkedIn](https://www.linkedin.com/in/huzaifah27) and [Medium](https://medium.com/@huzaif027), or reach me by [email](mailto:huzaif027@gmail.com).

<br />

<img src="https://huzaifah-dev.vercel.app/github-capabilities.png?v=2" alt="What I build. AI agents and LLM systems: agents that use tools and act on real systems, tool calling, MCP, multi-agent workflows, RAG over your own data, and ML models from training to deployment. Voice agents, my specialty: agents that hold real phone and web conversations, with telephony, real-time speech, turn-taking and detection of voicemail, IVRs and call screeners. Production AI infrastructure: backends and agent fleets that scale with load, with async APIs, autoscaling on custom metrics, concurrency limits, CI/CD and monitoring on AWS." width="100%" />

## Experience

### AI Engineer, Crypto Association Georgia
Remote, Jan 2026 to now

Built the voice agents and backend for [Callixo](https://www.callixo.ai), the company's outbound AI calling platform: 50,000+ leads dialed a day, 100+ concurrent live calls, sub-second turns.

- Designed it provider-agnostic: one CRM, several voice engines. Built and ran it on LiveKit, Retell AI, FreeSWITCH with a custom PJSIP media bot, and SignalWire, then kept what worked best.
- Built the scaling: an EC2 Auto Scaling Group that grows and shrinks the agent fleet on a custom load metric, a warm pool for fast scale-out, and a drain hook so scaling down never drops a live call.
- Machine detection for voicemail, IVRs and call screeners that runs alongside the call and leans toward keeping real people on the line.
- FastAPI and PostgreSQL backend and Next.js dashboards, shipped with Docker and GitHub Actions to AWS and monitored with Prometheus and Grafana.

### AI Developer Intern, Lanciere Technologies
Hyderabad, Feb to Aug 2025

- Took an AI interview platform to voice-to-voice interviews on OpenAI, Llama and Whisper, cutting hiring cycles by 30%.
- Cheat detection with YOLOv11, OpenCV and voice analytics inside the live interview pipeline.
- Agentic interviewer on LangGraph and CrewAI with persistent memory across a full interview.
- Cut live interview latency with batching and caching, serving 100+ assessments a day on AWS.

## Selected projects

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://www.callixo.ai"><img src="https://huzaifah-dev.vercel.app/projects/callixo-landing.webp" alt="Callixo screenshot" width="100%" /></a>
      <h3><a href="https://www.callixo.ai">Callixo</a></h3>
      Production voice agents and backend I built at Crypto Association Georgia for its AI calling platform: LiveKit and FreeSWITCH agents, answering machine detection and autoscaling on AWS. 100+ concurrent calls with sub-second turns. The codebase is private.
      <br /><br />
      <code>LiveKit</code> <code>Retell AI</code> <code>FreeSWITCH</code> <code>FastAPI</code> <code>AWS</code>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/Sa1f27/MindCanvas"><img src="https://huzaifah-dev.vercel.app/projects/mindcanvas-map.webp?v=4" alt="MindCanvas: a 3D knowledge map of pages in glowing clusters" width="100%" /></a>
      <h3><a href="https://github.com/Sa1f27/MindCanvas">MindCanvas</a></h3>
      RAG over the pages you read: each page is embedded, clustered and linked into a 3D knowledge graph, and every answer cites its source pages. Published as a <a href="https://ijesr.org/index.php/ijesr/article/view/1635">first-author paper</a>.
      <br /><br />
      <code>FastAPI</code> <code>pgvector</code> <code>RAG</code> <code>TypeScript</code> <code>three.js</code>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/Sa1f27/Live-Agent"><img src="https://huzaifah-dev.vercel.app/projects/live-agent-call.webp" alt="Live Agent: a voice conversation, with the project it is talking about on screen and its reply time" width="100%" /></a>
      <h3><a href="https://github.com/Sa1f27/Live-Agent">Live Agent</a></h3>
      A real-time voice agent on LiveKit Agents and Gemini Live that answers as me. Tool calls open the project under discussion, every reply is timed, and an LLM judge tests its answers in CI. <a href="https://huzaifah-dev.vercel.app/voice">Try it live</a>.
      <br /><br />
      <code>LiveKit Agents</code> <code>WebRTC</code> <code>Gemini Live</code> <code>React</code>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/Sa1f27/predictive-maintenance-mlops"><img src="https://huzaifah-dev.vercel.app/projects/predmaint-models.webp" alt="Predictive Maintenance: the champion and challenger models, the promotion gate and drift monitoring" width="100%" /></a>
      <h3><a href="https://github.com/Sa1f27/predictive-maintenance-mlops">Predictive Maintenance</a></h3>
      End-to-end MLOps on real fleet sensor data: survival models predict component failure, with an MLflow registry, a gated champion and challenger, drift-triggered retraining and Dagster pipelines. Cuts maintenance cost 26% on held-out data.
      <br /><br />
      <code>LightGBM</code> <code>Survival analysis</code> <code>MLflow</code> <code>Dagster</code> <code>FastAPI</code> <code>Docker</code>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/Sa1f27/HireSense-Final"><img src="https://huzaifah-dev.vercel.app/projects/hiresense.jpg" alt="HireSense screenshot" width="100%" /></a>
      <h3><a href="https://github.com/Sa1f27/HireSense-Final">HireSense</a></h3>
      AI voice agents that interview candidates and call their references, with LLM scoring of the transcripts and cross-checks of CV, LinkedIn and GitHub.
      <br /><br />
      <code>Next.js</code> <code>Supabase</code> <code>Whisper</code> <code>ElevenLabs</code>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/Sa1f27/GraphRAG"><img src="https://huzaifah-dev.vercel.app/projects/graph-rag.jpg" alt="Graph RAG screenshot" width="100%" /></a>
      <h3><a href="https://github.com/Sa1f27/GraphRAG">Graph RAG</a></h3>
      Hybrid retrieval for medical question answering: vector search refined by a MeSH knowledge graph, so every answer traces back to its sources.
      <br /><br />
      <code>Weaviate</code> <code>RDFLib</code> <code>Databricks</code> <code>OpenAI</code>
    </td>
  </tr>
</table>

More in the [full project list](https://huzaifah-dev.vercel.app/projects), and the voice work in depth on [voice agents](https://huzaifah-dev.vercel.app/voice).

## Stack

| | |
| --- | --- |
| **AI** | LLMs, AI agents, tool calling, MCP, RAG, LangGraph, LangChain, CrewAI, Qdrant, Transformers, OpenCV |
| **Voice** | LiveKit, Retell AI, SIP/RTP, FreeSWITCH, PJSIP, SignalWire, Twilio, STT/TTS, speech-to-speech models |
| **Backend** | Python, asyncio, FastAPI, PostgreSQL, Redis, WebSockets, REST |
| **Infra** | AWS (EC2, RDS, S3, Auto Scaling), Docker, Nginx, GitHub Actions, Prometheus, Grafana |
| **Frontend** | TypeScript, React, Next.js, Tailwind |

## Highlights

- **First-author paper:** *An AI system for transforming scattered web data into an interactive, queryable knowledge graph*, International Journal of Engineering & Science Research, 2026.
- **Hackathons:** seven, including the OpenAI Buildathon and Google's Agentic AI Hackathon, with two podium finishes.
- **Practice:** 291 LeetCode problems solved and six technical articles on [Medium](https://medium.com/@huzaif027).
- **Education:** B.E. Computer Science (AI & ML), First Division with Distinction, CGPA 8.48.

<br />

The fastest way to reach me is [email](mailto:huzaif027@gmail.com). I reply within a day.
