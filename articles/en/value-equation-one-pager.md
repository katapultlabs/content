# The Value Equation

### A framework for maximizing human-AI collaboration

**TL;DR:** Value = (Impact × Reach × Sustainability) / (AI Cost + Human Cost + Friction). You create value when you solve real problems for real people in a way that sustains itself. You destroy it when you generate output nobody uses, babysit AI through review loops, or burn compute on vague prompts. The most important variable is S: if what you build can't fund its own continuation, you have a project. If it can, you have a venture.

**ELI5:** Two helpers, a robot and a person. Value is how much good stuff they make for how many people, divided by how much it costs to run the robot and how much of the person's time it eats. Best setup: robot does the grunt work, person focuses on hard decisions, and what they build keeps working without constant babysitting.

-----

## The Core Equation

$$V = \frac{I \cdot R \cdot S}{T \cdot c + H \cdot w}$$

**Maximize value by generating real impact for real people, sustainably, while minimizing wasted tokens and human attention.**

-----

## The Numerator: What Is Value?

Value isn't output. You can generate a mountain of content, code, or analysis that nobody touches. Value only exists when someone receives it and it matters to them.

**I (Impact):** How much the output solves a real problem or improves someone's situation. *Does this actually help someone?*

**R (Reach):** How many people or entities benefit. *How many people does this touch?*

**S (Sustainability):** Whether the output generates enough captured value to reinvest and compound over time. *Does this sustain itself or decay?*

**S is the multiplier that separates projects from ventures.** When S < 1, you're extracting value. When S > 1, you've built a virtuous cycle: you capture enough value to reinvest, which grows I and R over time.

In the core equation, S is a snapshot. Appendix A1 extends it into a time series (V_{t+1} = S·V_t), showing how value compounds or erodes across iterations.

-----

## The Denominator: What Does It Cost?

**T (Tokens):** AI compute consumed (tokens, API calls, cycles). *How much AI resource did this take?*

**c (Cost per token):** Unit cost of AI compute (dollars, energy, time). *What's the price of each unit of AI work?*

**H (Human time):** Hours of human attention, review, direction, and correction. *How much human time did this require?*

**w (Weight of human time):** The cost of the specific human's attention. *Whose time is being spent?*

**The weight (w) matters enormously.** An hour of a CEO's strategic attention costs more than an hour of routine review. The equation rewards putting expensive human attention on high-leverage work and routing the rest to tokens.

-----

## What The Equation Kills

- **Bullshit output.** If nobody uses it, I ≈ 0 and R ≈ 0. V collapses no matter how efficiently you produced it.
- **Babysitting AI.** If a human has to review every line, H stays high and V barely improves over doing it manually.
- **Token waste.** Throwing compute at vague prompts without clear intent inflates T without growing the numerator.
- **Unsustainable projects.** If S < 1, the numerator decays over time. No amount of efficiency in the denominator saves you.

-----

## The Philosophy Behind It

This equation encodes 3 principles:

**Help as many people or entities as we can.** That's R. Reach is how impact scales beyond the individual.

**Leave the place better than we found it.** That's I × S. Impact that sustains and compounds means the world is better off because you showed up.

**Enjoy the work.** High V tends to correlate with flow: you're generating real impact without grinding through waste. When the denominator is bloated (endless review, vague prompting, organizational friction), the work feels like a slog. When it's tight, you move fast and the results speak for themselves.

-----

## The KPI

**Maximize V.**

-----

## Practical Implications

**For teams building with AI:**

- Before generating anything, ask: who benefits and how? (I and R)
- Design workflows that strip out human review loops (reduce H)
- Use tokens with intent: clear prompts, structured outputs, purposeful iteration (reduce T)
- Build for sustainability. Can this generate enough value to fund its own continuation? (grow S)

**For evaluating AI initiatives:**

- Don't measure output volume. Measure impact delivered per unit of combined resource.
- The best human-AI collaborations have high I, growing R, S > 1, and shrinking denominators over time.

-----

# Appendix: Mathematical Refinements & Extensions

For teams that want more rigor. These don't change the core philosophy; they make the structure more explicit.

-----

## A1. Sustainability as a Time Multiplier

In the core equation, S is a snapshot multiplier. More precisely, S represents how value evolves over time:

$$V_{t+1} = S \cdot V_t$$

If S < 1, value decays. If S = 1, value sustains. If S > 1, value compounds.

S determines whether the impact you create today accumulates or erodes tomorrow. A product with high I and R but S < 1 is a project. A product with S > 1 is a venture.

-----

## A2. Friction Term (Organizational Overhead)

Early AI systems often introduce hidden coordination costs: context switching, review loops, integration overhead, cognitive fatigue. These don't fit neatly into T or H. They're the glue tax between them.

Model this as a friction term F:

$$V = \frac{I \cdot R \cdot S}{T \cdot c + H \cdot w + F}$$

In immature systems, F is large. In AI-native systems, F approaches zero.

This explains a common paradox: why some teams invest heavily in AI and see limited gains. The tokens are flowing, the humans are engaged, but the friction between them (unclear handoffs, redundant reviews, poor context transfer) eats the value. Reducing F is often the highest-leverage move an organization can make.

-----

## A3. Interpretation as Capital Allocation

Tokens and human attention are both forms of capital: one computational, one cognitive. The equation reframes AI usage as a capital allocation problem:

- Where should scarce human attention go?
- Where should compute be deployed?
- How do you compound instead of extract?

This is structurally similar to capital efficiency models in economics and investing. The numerator is your return (impact × reach × sustainability). The denominator is your investment (compute capital + cognitive capital + friction). The goal isn't more output. It's superior return on combined cognitive and compute capital.

-----

## A4. Marginal Optimization

For teams optimizing iteratively, the practical question is: **increase impact faster than resource consumption grows.**

The best human-AI systems achieve this by growing I and R nonlinearly (one well-designed system can serve thousands), improving S over time (learning loops, network effects), reducing H through better prompts and workflows, and using tokens intentionally to avoid waste.

When marginal value exceeds marginal cost, you scale. When it doesn't, you optimize or pivot.

-----

*The Value Equation, a framework by Katapult*
