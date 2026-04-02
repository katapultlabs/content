# The Value Loop

**TL;DR**: We went from prompting to context engineering. Now there's a next layer. OpenAI called their version "harness engineering": building constraints, feedback loops, and scaffolding around AI agents so they produce stable work. Good start, but it's scoped to software. The real question is bigger. How do humans and non-human intelligence structure collaboration to produce the specific kind of value a given output demands? That's what we're calling the value loop. This is the thinking-out-loud version of how we got there.

---

I've been uncomfortable with the term "artificial intelligence" for a while now.

It made sense when the thing was statistical pattern matching dressed up in a trenchcoat. But what's happening now doesn't feel artificial. It feels like a different kind of intelligence. One that processes differently, fails differently, sees patterns differently.

Calling it "artificial" carries an implicit hierarchy: it's the synthetic version of the real thing. I think "non-human intelligence" is more honest. It places this new capability alongside human intelligence rather than beneath it. Two different cognitive architectures, each with strengths the other lacks.

That reframe changes the question. We stop asking "how do I get the AI to do what I want?" and start asking something harder: how do we collaborate?

## The Collaboration Problem

Here's the thing about collaboration between humans and non-human intelligence: there's no single right answer for how to structure it.

A vibe-coded prototype and a litigation strategy are both valuable outputs. But they demand completely different collaboration architectures. The prototype might need 10 minutes of human direction and zero oversight. The litigation strategy might need a senior attorney reviewing every inference, every citation, every logical step.

The variable is always value. And value is subjective.

For the prototype, value means speed, feel, creative exploration. For the litigation strategy, value means precision, defensibility, zero tolerance for hallucination. For a hardware spec, value means structural integrity. For a brand campaign, value means resonance.

Same collaboration partners (human + non-human intelligence). Completely different value requirements. Completely different architectures to get there.

So the core question becomes: what does "valuable" mean for this specific output, and how do we structure the collaboration to match?

That's the value loop. Define what valuable means. Structure the collaboration to produce it. Evaluate whether you got there. Recalibrate. Repeat.

## The Evolution So Far

Prompting was the first paradigm. You talked to the model. You got better at talking to the model. The skill was in the asking.

Context engineering was the second. You stopped focusing on single prompts and started designing what the system sees: memory, retrieval, tool access, conversation structure. The skill moved from asking to architecting the information environment.

Both of those are about the interface between human and non-human intelligence. They answer the question: how does information flow?

The value loop asks a different question entirely: how does the *whole system* work? Who does what? Where do humans sit in the loop? What gets automated, what gets reviewed, what gets co-created? And how do those decisions change based on the value you're trying to produce?

## OpenAI Called Their Version "Harness Engineering"

In February 2026, OpenAI published a piece about building production software entirely with Codex agents. 7 engineers, ~1,500 pull requests, roughly a million lines of generated code, zero lines written by hand.

The discipline that emerged from that experiment: designing environments, specifying intent, and building feedback loops so AI agents can do stable, reliable work. They called it [harness engineering](https://openai.com/index/harness-engineering/).

The metaphor comes from horse tack. Reins, saddle, bit. Equipment for channeling a powerful but unpredictable animal.

Their findings are real. LangChain took the same model and jumped from 52.8% to 66.5% on a coding benchmark by changing nothing about the model, only the scaffolding around it. Same intelligence, different structure, dramatically better results.

But harness engineering is fundamentally about software. Linters, CI gates, telemetry pipelines. It answers the question "how do we keep code-writing agents from producing entropy?" That's valuable. It's also one instance of a much broader pattern.

## Zooming Out

We have a project right now that involves litigation. The collaboration patterns look nothing like a software build. But the underlying question is identical: how do we structure the loop between human expertise and non-human intelligence to produce the specific kind of value this output demands?

The same question applies to product design, financial modeling, education, hardware engineering. Every domain has its own definition of valuable. Every output within that domain has its own fidelity requirements.

Harness engineering is one value loop, optimized for one domain. What we're looking for is the general principle underneath it.

## Finding the Right Word (In Public)

I've been trying to find a term for this broader discipline and I want to show my work, because the process of naming something is part of understanding it.

The long version: "agentic collaboration with the right level of expert human in the loop to affect the desired value outcomes." That's accurate. It's also a mouthful that nobody will remember.

I tried "harness building" for a while. Take OpenAI's concept but apply it beyond engineering, to anything you're building: products, legal strategies, educational experiences, organizational processes. You're building something valuable, and the discipline is in knowing how to structure the collaboration to get there.

But I kept bumping into limitations. The word implies containment, control, direction. Those are sometimes the right moves. But sometimes the best collaboration means stepping back and letting non-human intelligence run in directions you didn't anticipate. The skill isn't always in holding the reins. Sometimes it's in knowing when to let go.

(Also, "harness" is literally on our internal banned words list because it's been beaten to death by tech marketing. "Harness the power of AI." The irony of needing to engage with it seriously is... noted.)

Other candidates that passed through:

**Centaur work.** The chess metaphor: human + machine beats either alone. It captures the collaboration angle but implies a fixed split that doesn't reflect reality. Sometimes it's 95% non-human intelligence and 5% expert review. Sometimes the reverse.

**Calibrated building.** The act of calibrating human involvement to the demands of the output. "Calibrated" implies precision and intentionality. The full phrase doesn't quite land.

**Agentic building.** Simple, but "agentic" already carries its own baggage and drops the human side of the equation entirely.

Then I kept coming back to the loop.

The actual discipline is cyclical. You define what valuable means for a given output. You structure the collaboration. You evaluate whether it produced that value. You recalibrate. The human's role shifts depending on where you are in the cycle and what the output demands. The non-human intelligence's role shifts too.

It's a loop. A value loop. And every domain, every output, every project has its own version of it spinning at its own speed with its own fidelity requirements.

## What This Means in Practice

For us at Katapult, this is operational. Every partnership we enter now requires answering a version of this question before a line of code gets written (or gets written for us).

What are we building? What does "valuable" mean for this specific output? Where does human expertise need to sit in the loop? What can non-human intelligence handle autonomously, and where does it need guardrails, review, or real-time collaboration?

The person who can answer those questions well is worth more than the person who can write the best code. Or the best legal brief. Or the best design. Because the raw output is increasingly abundant. The judgment about how to structure collaboration to produce the right kind of value? That's the scarce skill.

The lawyer who structures the right value loop for litigation. The product designer who knows when to let AI generate 50 variants and when to insist on hand-crafted specificity. The educator who understands which parts of the learning loop benefit from non-human intelligence and which parts demand a human presence.

That's the discipline. And now it has a name.

## The Uncomfortable Part

I want to end with something honest.

Part of the reason naming this took a while is because it forces a question about human relevance. If the answer to "who does what?" keeps shifting toward non-human intelligence, what's left for us?

I think what's left is the value judgment itself. Deciding what "valuable" means for a given output. Defining the quality bar. Knowing when the collaboration architecture needs to shift because the stakes changed.

Those are deeply human questions. They require understanding context, stakes, consequences, and human needs in ways that non-human intelligence can inform but (for now, and probably for a while) can't fully own.

The value loop is about humans owning the thing only humans can own: the definition of value, and the accountability for whether the system delivered it.
