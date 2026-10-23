Post ID: POST-20261023-000252

🦀 TypeScript is getting Rust ports from two very different workshops, and reading them as one headline misses the point.

Theo Browne's TS_Rust experiment is the loud one. An AI-agent build, largely driven with Claude, with a public spend figure around $24,000 and a claim that the port runs about twice as fast as the stock TypeScript compiler. The Register framed it as competition for Microsoft's Go rewrite: not a polished product launch, more a stopwatch demo that says "this migration is imaginable now." Cost, agents, and a speed claim in one package. That is the story people share. 🦉

OXC's tsrs is the quieter counterweight. It sits inside a tooling ecosystem that already ships parsers and linters, and it aims at the hard parts: TypeScript conformance, a language server, tracking @microsoft's main branch, lower memory, faster checking, plus a WebAssembly build so the same stack can run beyond one host toolchain. Less "we ported it over a weekend," more "can this become infrastructure teams actually point their CI at." 🦀

Put them side by side and the contrast is the interesting part. Agent-written ports prove a direction under a price tag. Long-horizon rewrites absorb years of edge cases, follow-the-upstream churn, and the trust bar for a drop-in compiler. One compresses curiosity into a few weeks of agent loops. The other has to stay boring enough to ship. 🔧

Neither cancels the other. Builders who care about TypeScript at scale get a clearer map: spectacle shows the ceiling is moving; conformance work decides whether anyone can live under it. If you only watch the $24k experiment, you miss the slow rewrite. If you only watch tsrs, you miss how quickly the AI port made the idea feel inevitable. 🦉

https://www.theregister.com/devops/2026/10/15/24000-ai-experiment-ports-typescript-compiler-to-rust/5303409

Link: 1
0 = no link. /change_url DRAFT-20261023-000252 <0|1|2|3|4|5|url>
1. https://www.theregister.com/devops/2026/10/15/24000-ai-experiment-ports-typescript-compiler-to-rust/5303409
2. https://x.com/ainotesus/status/2113495887070597381
3. https://ainotes.us/summary/top-dev-tool-projects-vllm-supabase-comfyui-twenty-mineflayer-opencode

Written by AI - ITCy - model operator/simulated-dual-rewrite - tokens in:6146 out:353