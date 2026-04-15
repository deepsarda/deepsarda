<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=28&duration=3000&pause=1000&color=C9D1D9&center=true&vCenter=true&random=false&width=600&lines=building+cool+stuff;Deep+Sarda" alt="Typing SVG" />

<br/>

[![Nox](https://img.shields.io/badge/Nox-sandbox_runtime-181717?style=for-the-badge&logo=kotlin&logoColor=white)](https://github.com/deepsarda/Nox)
&nbsp;

</div>

<br/>

## `$ whoami`

A college student obsessed with building cool stuff. I build runtimes, research AI architectures, and occasionally ship things people use.

Previously built **[Aeona](https://github.com/deepsarda/aeona)** which is a Discord bot that scaled to **15,000 servers** and **10k monthly active users** before I deprecated it.

<br/>

## `$ cat flagship.md`

### [Nox](https://github.com/deepsarda/Nox)

A **zero-trust sandbox runtime** for executing untrusted scripts on the JVM. Built for AI agents that need to write their own tools without becoming autonomous code execution vulnerabilities.

**->** Static typing, resource guards, permission-gated I/O<br/>
**->** Compiles NSL to custom bytecode (not JVM bytecode)<br/>
**->** Incredible extensibility<br/>
**->** LSP + MCP integration in progress
```kotlin
val runtime = NoxRuntime.builder()
    .maxInstructions(100_000)
    .maxExecutionTime(Duration.ofSeconds(5))
    .permissionHandler { request ->
        PermissionResponse.Denied("Not allowed")
    }
    .build()

val result = runtime.execute(
    source = """
        @tool:name "greeter"
        main(string name) {
            return `Hello, ${name}!`;
        }
    """,
    args = mapOf("name" to "World")
)
```



<br/>

## `$ ls research-interests/`

```
agentic-systems/        linear-attention-architectures/    multimodal-diffusion-llm-hybrids/
capability-based-security/   efficient-training-pipelines/      procedural-generation/
```

<br/>

<div align="center">

## `$ git log --graph`

<img src="https://github-readme-activity-graph.vercel.app/graph?username=deepsarda&theme=github-compact&hide_border=true&area=true&bg_color=0d1117&color=c9d1d9&line=58a6ff&point=c9d1d9" width="95%" />

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=deepsarda&theme=github_dark" width="95%" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com?user=deepsarda&theme=github-dark-blue&hide_border=true&background=0d1117" width="49%" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=deepsarda&theme=github_dark&utcOffset=5.5" width="49%" />

</div>

<br/>

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/deepsarda/deepsarda/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/deepsarda/deepsarda/output/github-snake.svg" />
  <img alt="Snake animation" src="https://raw.githubusercontent.com/deepsarda/deepsarda/output/github-snake-dark.svg" />
</picture>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=deepsarda&style=for-the-badge&color=1f6feb&label=PROFILE+VIEWS" />

</div>
