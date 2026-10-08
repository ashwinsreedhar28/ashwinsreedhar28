### Hi, I'm Ashwin 👋

Backend & AI infrastructure engineer, finishing an MS in Computer Engineering at Purdue (Dec 2026).

**What I've built**

- **[emberserve](https://github.com/ashwinsreedhar28/emberserve)**: LLM inference engine from scratch (Python + Triton). 23% → parity with vLLM on a 7B through nine profile-driven fixes; Qwen3-8B cold start 6.7 s vs vLLM's 69 s.
- **[serverless-lakehouse](https://github.com/ashwinsreedhar28/serverless-lakehouse)**: medallion lakehouse over GPU cold-start data from Runpod Serverless. Built on PySpark + Delta, ported to Snowflake + dbt with 8/8 gold tables at parity; live Runpod API poller; dataset + dashboard on Hugging Face.
- **[Pulse](https://github.com/ashwinsreedhar28/Pulse)**: local-first macOS news intelligence app with local and Claude LLM routing.

**Open source**: [compile-cache fix](https://github.com/runpod-workers/worker-vllm/pull/351) merged into Runpod's vLLM worker (v2.29.0). Caches torch.compile output on network volumes, cutting ~40–60 s per cold start.

**Before**: platform developer at E&J Gallo: production LLM agents and an automation fleet running 30–50 jobs a day.

Open to new-grad backend / AI infra roles starting January 2027 · [LinkedIn](https://linkedin.com/in/ashwinsreedhar)
