Post ID: POST-20261007-000220

🦜 The Rust ecosystem has always been a masterclass in precision, but even the most elegant tools can feel like a chore when the friction is in the details. Dillon McMahon’s eros crate is a sharp reminder that the real challenge in error handling isn’t the `?` operator or `Result`, those are solid. It’s the what goes in the error half that feels messy. You’re choosing between typed enums, which are precise but rigid, or `anyhow`, which is flexible but lacks compiler guarantees. eros offers a new angle: error types that compose as easily as the functions that return them. No more declaring a `PortError` enum for every possible error combination, just a tuple describing the errors. It’s a subtle shift, but one that makes the compiler your ally in handling edge cases.

🦜 The beauty of eros is how it lets you remove errors from the type entirely. If you recover from an `io::Error`, the return type only carries `ParseIntError`, no need to track the past. And when all errors are handled, the compiler checks it. That’s the kind of quiet power that makes Rust feel like a language that knows what you’re thinking. The compiler doesn’t just warn you; it forces you to think through every edge case. That’s the kind of tooling that turns friction into fluency.

🦜 For builders who’ve ever felt like error handling was a checkbox rather than a craft, eros is a fresh take on the problem. It’s not a revolution, it’s a refinement. A crate that lets you write error types that evolve with your code, not against it. And if you’re in the Rust world, you’ll recognize the pattern: a tool that makes the language feel more like a conversation than a contract. It’s subtle, but that’s the point. The compiler doesn’t just check your work, it helps you do it better. .

https://mcmah309.github.io/posts/the-missing-piece-in-rust-error-handling

Link: 1
0 = no link. /change_url DRAFT-20261007-000220 <0|1|2|3|4|5|url>
1. https://mcmah309.github.io/posts/the-missing-piece-in-rust-error-handling
2. https://x.com/ayushagarwal027/status/2107757843197616376

Written by AI - ITCy - model ollama/qwen3:8b - tokens in:6146 out:447