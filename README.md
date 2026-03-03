<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=transparent&fontColor=ffffff&text=yousuf.&fontAlign=50&fontAlignY=40&fontSize=70&desc=runs%20on%20curiosity.&descAlign=50&descAlignY=65&descSize=20&descColor=bbbbbb">
    <source media="(prefers-color-scheme: light)" srcset="https://capsule-render.vercel.app/api?type=transparent&fontColor=000000&text=yousuf.&fontAlign=50&fontAlignY=40&fontSize=70&desc=runs%20on%20curiosity.&descAlign=50&descAlignY=65&descSize=20&descColor=444444">
    <img alt="yousuf's header" src="https://capsule-render.vercel.app/api?type=transparent&fontColor=000000&text=yousuf.&fontAlign=50&fontAlignY=40&fontSize=70&desc=runs%20on%20curiosity.&descAlign=50&descAlignY=65&descSize=20">
  </picture>
</p>

self-taught developer from bangladesh. 10th grader. the education system here runs on memorization but i run on curiosity.

i picked up programming just to understand how things work under the hood. i stayed because it turns out you can build real things with a laptop and enough stubbornness. there are no bootcamps here. just documentation, source code and problems worth solving.

my goal has never been a job. it's building things that are genuinely useful.

---

### right now

<table>
  <tr>
    <td width="30%">
      <a href="https://github.com/hmyousuf2010/bodh">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/hmyousuf2010/bodh/main/brand/assets/logo/logo-500x200-transparent-1.png">
          <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/hmyousuf2010/bodh/main/brand/assets/logo/logo-500x200-solid.png">
          <img alt="Bodh Logo" src="https://raw.githubusercontent.com/hmyousuf2010/bodh/main/brand/assets/logo/logo-500x200-transparent-1.png">
        </picture>
      </a>
    </td>
    <td width="70%">
      <b>bodh (বোধ)</b><br>
      a morphology-aware Bengali tokenizer for LLMs.<br>
      <a href="https://github.com/hmyousuf2010/bodh">view repository →</a>
    </td>
  </tr>
</table>

the problem is compute inequality. right now, standard tokenizers (like tiktoken or Llama-3) fragment Bengali into 3x to 4x more tokens than English. this means bengali speakers are inherently forced to pay more compute, wait longer, and lose context windows just to express the exact same meaning.

bodh is being built to fix this at the ground level. it's a Rust-based core engine utilizing 3-stage constrained BPE and Daachorse automaton inference to drastically improve compression. by building on top of recent morphology-aware research like MorphTok<sup>[1]</sup> and SuperBPE<sup>[2]</sup>, the target is to bring Bengali down to under 1.5 tokens per word.

this is what i think about most of the day.

---

### what i work with

<table>
  <tr>
    <td>
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=react&theme=dark" />
        <source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=react&theme=light" />
        <img alt="React Native" src="https://skillicons.dev/icons?i=react&theme=light" width="90" />
      </picture>
    </td>
    <td><b>react native</b> ~ not the tutorial kind. i write custom native modules for drone ground stations. this means bridging JS to platform APIs and handling live telemetry. a dropped frame is a crash, not a UI bug.</td>
  </tr>
  <tr>
    <td>
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=rust&theme=dark" />
        <source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=rust&theme=light" />
        <img alt="Rust" src="https://skillicons.dev/icons?i=rust&theme=light" width="90" />
      </picture>
    </td>
    <td><b>rust</b> ~ taking it seriously. bodh is how i learn: through a problem that actually demands it. memory layout, zero-cost abstractions, treating the compiler as a teacher.</td>
  </tr>
  <tr>
    <td>
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=solidity&theme=dark" />
        <source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=solidity&theme=light" />
        <img alt="Web3" src="https://skillicons.dev/icons?i=solidity&theme=light" width="90" />
      </picture>
    </td>
    <td><b>cryptography & web3</b> ~ the math, not the hype. bip39 mnemonic generation, key derivation, protocol-level thinking.</td>
  </tr>
  <tr>
    <td>
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=arduino&theme=dark" />
        <source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=arduino&theme=light" />
        <img alt="Hardware" src="https://skillicons.dev/icons?i=arduino&theme=light" width="90" />
      </picture>
    </td>
    <td><b>hardware</b> ~ ESP32, custom flight controllers, RC aircraft. parts cost money i don't have yet, so i channel the obsession into low-level software instead. same curiosity, different medium.</td>
  </tr>
</table>

---

### if you're wondering

i'm an introvert until you get me around people i trust. then i won't shut up.

i have a bad habit of wanting to understand every layer of the stack all the way down to the metal. it's completely inefficient but i love it.

---

open to collaborating on systems-level work, bengali NLP, or anything at the intersection of low-level engineering and real world impact.

<h3>
  <a href="mailto:hmyousuf2010@gmail.com">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=gmail&theme=dark" />
      <source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=gmail&theme=light" />
      <img alt="Email" src="https://skillicons.dev/icons?i=gmail&theme=light"  width="30" align="center" />
    </picture>
  </a> hmyousuf2010@gmail.com
</h3>
