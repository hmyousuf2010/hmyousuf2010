# yousuf

self-taught developer from bangladesh. 10th grader. the education system here runs on memorization — i run on curiosity.

i picked up programming because i wanted to understand how things actually work. i stayed because it turns out you can build *real* things with a laptop and enough stubbornness. no courses, no bootcamps — just docs, source code, and problems worth solving.

my goal has never been a job. it's building things that are deeply useful and earning a halal living from it.

---

### right now

**[bodh (বোধ)](https://github.com/hmyousuf2010/bodh)** — a morphology-aware Bengali tokenizer for LLMs.

current tokenizers (tiktoken, SentencePiece, Llama-3) fragment Bengali into 3-4x more tokens than English. bengali speakers pay more, get less context, and wait longer — for the same meaning. bodh aims to fix this: a Rust core engine with 3-stage constrained BPE, Daachorse automaton inference, and morpheme-boundary awareness baked into the training pipeline. target is ≤1.5 tokens per word, down from ~4.0. the [full roadmap](https://github.com/hmyousuf2010/bodh/blob/main/ROADMAP.md) is built on top of MorphTok (ICML 2025), SuperBPE (COLM 2025), rs-bpe, and more.

this is what i think about most of the day.

---

### what i work with

**react native** — not the tutorial kind. i've written custom native modules for professional drone ground control stations — bridging JS to platform APIs, handling real telemetry, the kind of work where a dropped frame isn't a UX issue, it's a crash.

**rust** — studying it seriously. bodh is how i learn: through a problem that demands it, not through exercises. memory layout, zero-cost abstractions, the compiler as a teacher.

**cryptography & web3** — the math underneath, not the hype on top. bip39 mnemonic generation, key derivation, protocol-level thinking. going deeper.

**hardware** — ESP32, custom flight controllers, RC aircraft, sensor fusion. this is the stuff that makes my brain light up. parts cost money i don't have yet, so i channel the same obsession into low-level software instead. same curiosity, different medium.

---

### if you're wondering

i'm an introvert until you get me around people i trust — then i won't shut up.

i have a bad habit of wanting to understand every layer of the stack, all the way down to the metal. it's inefficient. i love it.

---

open to collaborating on systems-level work, bengali NLP, or anything at the intersection of low-level engineering and real-world impact.

**hmyousuf2010@gmail.com**
