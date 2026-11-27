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
      Voice agents and backend I built at Crypto Association Georgia for its AI calling platform. Provider-agnostic, with machine detection and autoscaling. The codebase is private.
      <br /><br />
      <code>LiveKit</code> <code>Retell AI</code> <code>FreeSWITCH</code> <code>FastAPI</code> <code>AWS</code>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/Sa1f27/MindCanvas"><img src="https://huzaifah-dev.vercel.app/projects/mindcanvas-map.webp?v=4" alt="MindCanvas: a 3D knowledge map of pages in glowing clusters" width="100%" /></a>
      <h3><a href="https://github.com/Sa1f27/MindCanvas">MindCanvas</a></h3>
      Turns what you read on the web into a 3D knowledge map. Pages cluster into areas, and answers cite your own pages and light them up on the map. Published as a <a href="https://ijesr.org/index.php/ijesr/article/view/1635">first-author paper</a>.
      <br /><br />
      <code>FastAPI</code> <code>pgvector</code> <code>RAG</code> <code>TypeScript</code> <code>three.js</code>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/Sa1f27/Live-Agent"><img src="https://huzaifah-dev.vercel.app/projects/live-agent.webp" alt="Live Agent: talk to my voice agent in the browser" width="100%" /></a>
      <h3><a href="https://github.com/Sa1f27/Live-Agent">Live Agent</a></h3>
      Speech-to-speech agent that holds unscripted voice conversations in the browser, streaming PCM over WebSockets. <a href="https://live-agent-eoj3.onrender.com">Try it live</a>.
      <br /><br />
      <code>AudioWorklet</code> <code>Gemini ADK</code> <code>WebSockets</code> <code>FastAPI</code>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/Sa1f27/predictive-maintenance-mlops"><img src="https://huzaifah-dev.vercel.app/projects/predmaint-fleet.webp?v=3" alt="Predictive Maintenance: a live fleet view of each truck's failure risk and recommended workshop action" width="100%" /></a>
      <h3><a href="https://github.com/Sa1f27/predictive-maintenance-mlops">Predictive Maintenance</a></h3>
      Predicts engine failures across a SCANIA truck fleet from real sensor data and picks workshop alerts by maintenance cost, saving 26%. A live plant on industrial standards, gated retraining and an AI copilot.
      <br /><br />
      <code>Survival models</code> <code>MLflow</code> <code>Dagster</code> <code>OPC UA</code> <code>TimescaleDB</code> <code>React</code>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/Sa1f27/HireSense-Final"><img src="https://huzaifah-dev.vercel.app/projects/hiresense.jpg" alt="HireSense screenshot" width="100%" /></a>
      <h3><a href="https://github.com/Sa1f27/HireSense-Final">HireSense</a></h3>
      Candidate verification and voice interviews: cross-platform profile checks, automated reference calls, scored transcripts.
      <br /><br />
      <code>Next.js</code> <code>Supabase</code> <code>Whisper</code> <code>ElevenLabs</code>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/Sa1f27/GraphRAG"><img src="https://huzaifah-dev.vercel.app/projects/graph-rag.jpg" alt="Graph RAG screenshot" width="100%" /></a>
      <h3><a href="https://github.com/Sa1f27/GraphRAG">Graph RAG</a></h3>
      Retrieval over medical literature combining vector search with a MeSH knowledge graph for explainable answers.
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
