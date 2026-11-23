Post ID: POST-20261123-000324

ripgrep just dropped version 16, and while it sounds like a minor patch to the uninitiated, this release quietly drops in features that make agentic workflows significantly easier for developers. 📜

It now includes an `--in` flag for loading paths from line-delimited files (and even handles NUL delimited paths with `--in0`), which is exactly the kind of detail-oriented refinement that matters when feeding repositories to models. 🔧

For those managing large codebases, there's also a new `-G/--glob-not` flag to replace legacy glob negation patterns, plus a native way to set default parallelization threads via an environment variable rather than command-line flags every time. 🦉

@cursorai and Claude Code teams have long relied on ripgrep for its speed and noise reduction, respecting `.gitignore` by default so agents don't waste tokens on `node_modules` or binaries. This latest iteration keeps that pedigree while tightening the toolchain, proving that fundamental tools still evolve with meaningful utility rather than just marketing hype. 🦀

As builders ship agents this week, having a cleaner, more configurable grep at your fingertips means faster context gathering and fewer hallucinations from irrelevant files. 🤖

The move toward 16 represents a quiet but necessary upgrade in how search interfaces with modern automation, giving us another piece of the puzzle for building reliable coding agents. See what shipnotes BurntSushi highlighted regarding performance improvements and bug fixes in this release: . 🦉

https://newreleases.io/project/github/BurntSushi/ripgrep/release/16.0.0

Link: 1
0 = no link. /change_url DRAFT-20261123-000324 <0|1|2|3|4|5|url>
1. https://newreleases.io/project/github/BurntSushi/ripgrep/release/16.0.0
2. https://github.com/newreleasesio
3. https://cursor.com/blog/fast-regex-search
4. https://www.learnwithparam.com/blog/ripgrep-coding-agents-fast-code-search
5. https://codeant.ai/blogs/why-coding-agents-should-use-ripgrep

Written by AI - ITCy - model ollama/qwen3.5:9b - tokens in:16044 out:358