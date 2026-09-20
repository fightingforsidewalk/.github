## Fighting For Sidewalk

Venture studio and technology lab. We develop new business concepts, build the sites
and tools they need, and share what we learn along the way.

Most of the work is for ventures in development and none of it is here. What is here is
our community contribution: tools that came out of our own learnings and practice,
published because they were useful to us and might save someone else the trouble. Our
attention sits where IT infrastructure, AI, and blockchain overlap, which is where most
of the interesting problems have been lately.

Everything we publish will generally be released under CC0 or MIT, where the license is ours to
choose. CC0 asks nothing in return at all; MIT asks only that the notice travels with the code.
Take what is useful to your projects.

### Working with AI agents

Three repositories from the same work, each doing a different job:

- **Coordination** — [claude-relay](https://github.com/fightingforsidewalk/skill-claude-relay):
  how several chats on one project reach each other without a person carrying the messages.
- **The record** — [canonical-tracker](https://github.com/fightingforsidewalk/skill-canonical-tracker):
  one record as the truth, every derived view patched from it, and a check that fails when
  they disagree.
- **Execution** — [claude-code-discipline](https://github.com/fightingforsidewalk/claude-code-discipline):
  how a coding agent works on its own and reports back in a form a person can check without
  reading the diff.

Each one works alone. Together they cover a project from the first instruction to the last
commit.

### Application security

- [cloudflare-turnstile-form-hardening](https://github.com/fightingforsidewalk/cloudflare-turnstile-form-hardening):
  hardening a public form on Cloudflare — the bot challenge, the proxy hop that carries the
  real client IP, rate limiting, validation, and getting the message safely into an inbox.
  Field notes from one implementation, including the controls that looked correct and were
  not. A companion covers stored content that gets rendered later.

Different from the three above: not part of an operating model, just what one surface took
to harden and why each part is there.

[fightingforsidewalk.com](https://fightingforsidewalk.com)
