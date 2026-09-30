# Hi, I'm Tim 👋

Solo developer from Germany, 16 years old student, working at the intersection of **machine learning, speech and local-first AI**. I like understanding how things work under the hood, and making them faster, smaller and more private.

## 🔬 What I've been digging into lately

### Machine learning & LLMs
- **Local LLM inference**: running and optimizing models with `llama.cpp` (Vulkan on AMD GPUs), comparing inference engines and their real-world trade-offs
- **Quantization**: evaluating how low-bit quantization affects quality, speed and memory across model families
- **Inference speed-ups**: speculative decoding, speculative prefill, persistent prefix KV-caching, streaming prefill
- **Fine-tuning** LLMs locally on my own hardware
- **Small, specialized models** for agentic tool calling, and what it takes to train them efficiently without cloud compute

### Evaluation & benchmarking
- Built a custom **tool-calling benchmark framework** with five difficulty tiers, scaled by the number of tool calls, to compare small local models (e.g. Gemma and Qwen variants) on realistic agentic tasks
- Latency testing of cascaded pipelines (STT → LLM → TTS) versus end-to-end omni models

### Speech & audio
- Wake-word detection and training of **custom wake-word models**
- Voice activity detection, streaming speech-to-text, and multilingual text-to-speech
- Pipeline latency: sentence-level TTS pipelining and overlapping stages to cut time-to-first-audio

### Agents & tooling
- Tool calling, MCP, and plugin/sandbox architectures for LLM agents
- Automation systems that let models act on a desktop safely

### Security
- Ongoing self-study in **cybersecurity** and privacy-preserving system design

## 🧾 Also
I take on client work building desktop automation tools for small businesses.

## 🔭 Currently interested in
- Making local models meaningfully faster without losing output quality
- Privacy-friendly AI that works without the cloud
- Open, reproducible evaluation of small models

---

*Languages: German, Polish & English · Open to interesting projects and collaboration*
