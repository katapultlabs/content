# The Harness Thesis: Why We Were Solving the Wrong Problem

**TL;DR:** Founders who use AI can now express their vision directly into working products; no translation layer, no game of broken-telephone meetings, standups, decks, PRDs, and other crutches. The bottleneck was never the team's talent; it was the medium. A harness is the system (environment, tools, guardrails) that makes that direct expression as close to a production-ready reality. The team stops being an imperfect translation layer; the harness (humans and agents, each doing what they're best at) shifts to what actually matters: supporting a founder's vision so it thrives when it encounters reality.

**ELI5:** Imagine you're an architect, but instead of drawing blueprints and hoping the builders get it right, you can walk into the building and rearrange the walls yourself. You still need a system (some human, some automated) to make sure it won't fall down. But now it's reinforcing your actual vision instead of guessing what you meant from a sketch.

---

**We've been asking the wrong question.**

For months, we tried to solve what sounded like the right problem: how do we make high-performing teams keep up with fast-moving founders? How do we get engineers, PMs, and designers to absorb the vision inside someone's head?

We had daily standups. Product meetings. Founders would pour out their thinking orally at us, and teams scrambling to capture it, interpret it, translate it into tickets and specs and sprints. Used Granola to capture the meetings, pushed founders to Wispr into Claude to send us PRDs. The best teams got close. They captured the essence "well enough" to build valuable products.

For a long time, the essence was enough.

**The new speed of founders.**

We work with a certain kind of founder at Katapult. People who live and breathe their ideas 24/7, who dream about their products, who wake up at 5AM with a vision so vivid they can almost touch it. After every sales call they know exactly the little tweak they'd make. These are our partners. They're also me.

These founders have tasted velocity. They've vibe coded a prototype in an afternoon. They've watched AI turn a rambling voice memo into a working feature. They know what's possible, and they can't un-know it.

They're moving at a billion miles an hour. Entire universes in their heads: products, business models, user experiences, edge cases, market positioning, all swirling together in real time.

And we, as an industry, trying to put together teams who, no matter how talented, could never fully reconstruct that universe. We were trying to compress a founder's entire cognitive state into the brains of other humans. Through standups. Through PRDs. Through Slack threads and Figma comments and "can you say that again, differently?"

This has always been the reality for visionaries and dreamers. We come together, marshal resources, people, technology, and form something bigger than any one of us. Then we try to imprint our vision onto that organism and hope it brings a "valuable enough" version of our ideas to life.

It's not efficient for founders to talk at anyone. It never was. We know because we're founders too, and we've been on both sides of that table.

Your expectations are wrong. But they shouldn't be. The old expectations aren't unrealistic because founders are asking too much. They're unrealistic because the medium hasn't caught up to the speed at which founders think and could build.

Wrong problem.

**The real question.**

How do we let the founder express what's in their head directly, at full fidelity, into something that moves the product and business forward?

Give the founder a system where they see their visions reflected in reality at the speed of thought. In working software, close to production, where value gets generated. A founder sits with an AI that has infinite patience, iterates for 3 hours, riffs and refines and backtracks and pushes forward, then hands over a working pull request that *shows* what they mean. That's the whole universe, exported.

Once a founder experiences that flywheel, decks feel like cave paintings.

**Cooking with fire.**

One of the CEOs we work with is exactly this kind of founder. Brilliant, fast, impatient, overflowing with ideas. He'd been hearing about AI tools, seeing what's possible, getting excited. So I jumped on a Zoom, took over his screen, and spent an hour doing old-school tech support: setting up Claude Code against our actual codebase, fighting environment issues, running Docker, killing crashed processes, freezing his machine more than once.

When the local harness finally worked, he could see it. The raw potential, the speed, what this could become. But he couldn't wield it yet. Then he said something I haven't stopped thinking about: **"You gave me fire, but I don't know what to do with it."**

That's the whole tension. We're handing founders something enormously powerful (red-hot magma, really) and right now it throws off sparks and stones and burns people. Vibe coded prototypes that don't scale. Tools that crash. Highly technical requirements. A local environment eats 48 gigs of RAM and freezes your laptop.

Fire is only useful if you can wield it conveniently. If setting up the environment takes a technical CEO on a Zoom call for an hour, if the tools crash 3 times before they work, if you need to kill processes and restart Docker and pray: that's a science experiment, not a building tool.

The system has to be frictionless. That's the entire thesis.

**What a harness actually is.**

A harness is the system (environment, agents, guardrails, infrastructure) that sits between a founder's raw creative energy and production-ready software. Humans and agents, each doing what they do best. Agents handle the tedious, repeatable, high-volume work: running tests, checking for regressions, enforcing code standards, monitoring deploys. Humans focus on the judgment calls: architecture decisions, design taste, strategic tradeoffs, the things that require context no agent has yet.

The founder gets a near-production environment wired into the real codebase. Claude Code, Cowork, Codex, Cursor, whatever fits their style. They speak into it. "On this page, I want this interaction, try this animation, restructure this flow." They can be messy. They can dream out loud. AI doesn't lose context after lunch. It doesn't misremember the brief. It doesn't go home.

The founder iterates until they see the idea come alive. Then they create a pull request.

Without the harness, founders do what comes naturally: dump straight to production. It works until it doesn't, because it's a house of cards. Complexity grows, things break in places nobody checked, the product gets brittle, value errodes.

That's where the harness earns its name. Agents review PRs for regressions, generate test coverage, flag security issues. Engineers re-architect what needs human judgment. Designers sand down the rough edges. Product validates against the roadmap. Each layer does what it's best at. The tedious work gets compressed. The valuable work gets amplified.

The founder shows instead of explains. The harness turns a working prototype bulletproof instead of reconstructing a universe from meeting notes.

**"We were afraid of losing control."**

This week we kicked off a new project with a founding team that had been building their product in Lovable. They told us something that I hadn't thought about: they'd been hesitant to work with a development partner because they were afraid of losing their creative ability.

They'd been scrapping with AI tools. Building prototypes themselves. Iterating fast. The fear was that bringing in a team meant giving that up, becoming less agile, losing their touch on the product.

That fear makes perfect sense under the old model. Hiring an internal team or dev shop used to mean handing over your vision and hoping they'd give it back in roughly the right shape 6 weeks later. You lost the direct wire between your brain and the product.

And it's not just startups. We're hearing from companies with massive engineering organizations where executives vibe coded a working prototype in an afternoon, took it to their dev team, and were told: come back in three months. Hundred-person engineering teams that can't keep up with a founder and a laptop.

The answer is the opposite of what most founding teams expect. Product teams should give founders *more* control, not less. Build environments where founders can vibe build directly against the real platform, same way they've been doing in Lovable or Bolt or Cursor, but against production infrastructure with real data. The team runs interference: secure, scalable, tested, beautiful. The founder stays the most critical part of value creation.

**The system becomes more important.**

For weeks, I tried to solve the old problem with new tools. Better translators, better PMs, tighter specs. Then across 4 different conversations with founders and teams, something cracked open. We'll never win that race. The founders are moving too fast.

They don't need us to understand a lossy version of their vision anymore. They need us to build the machine that lets them express themselves directly. Compress the "idea to reality" loop.

Agents compress the boring work: test generation, regression checks, deploy monitoring, code review for standards compliance. That frees the humans on the team to zero in on what actually requires a brain: architecture, design taste, strategic calls. Less busywork, more meaningful decisions.

A founder's vibe-coded PR is a first draft written by someone with perfect domain knowledge and zero concern for edge cases. The harness (agents and humans together) takes that draft and makes it production ready.

That's more meaningful work for everyone involved. And it produces a better product, because the original vision survived intact instead of getting diluted through 5 layers of human interpretation.

**We have fire. Now we need to learn to cook.**

The tools are here. AI is patient enough, fast enough, and capable enough to be the medium between a founder's brain and valuable products. What's missing is the convenience layer: the guardrails, the agents, the frictionless setup that lets a CEO sit down, open a laptop, and start building. Agents handle what used to require a senior engineer on a Zoom call. Humans handle what no agent can.

That's what we're building at Katapult with our partners. Every adventure now starts with one question: what does the right system look like for this founder, this product, this team?

The founders who wire this up first are going to move so fast that everyone else will wonder what happened.
