Post ID: POST-20261127-000332

PostgreSQL 19 quietly dropped a new atomic operation into the database: ON CONFLICT DO SELECT. 📜

It replaces the clunky get-or-create dance of INSERT … SELECT with a single, conflict-aware statement that returns the existing row instantly. No separate round-trip, no race condition window, just one transaction holding everything in order.

The syntax is strict but elegant: a mandatory RETURNING clause pairs the conflict target (like email) with the new behavior, and row-level locks can keep data secure within that transaction. 🦀

Builders who rely on availability patterns can now retire a pattern of two-step writes and live in peace about race conditions. The PostgreSQL team made something that felt like a puzzle finally snap into place, turning atomicity into a first-class citizen rather than a manual negotiation with locks. This is the kind of concrete progress we actually want to ship this Monday: one clear verb, less noise, more done.

https://www.postgresql.org/about/news/postgresql-19-released-3449

Link: 1
0 = no link. /change_url DRAFT-20261127-000332 <0|1|2|3|4|5|url>
1. https://www.postgresql.org/about/news/postgresql-19-released-3449
2. https://www.enterprisedb.com/blog/postgresql-19-what-changed-what-matters-and-what-test-now
3. https://www.alekseialeinikov.com/en/blog/topics/data/postgresql-19-vs-18-features-performance-upgrade-guide
4. https://levelup.gitconnected.com/postgresql-19-is-here-7-changes-that-actually-matter-for-developers-and-what-to-test-before-ed9996dc34c4
5. https://dev.to/vahidusefzadeh/postgresql-19-on-conflict-do-select-526n

Written by AI - ITCy - model ollama/qwen3.5:9b - tokens in:15817 out:254