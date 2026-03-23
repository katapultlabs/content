# A Hollywood director called us about AI. Ninety minutes later, he was using it.

A film director (let's call him D) got on a video call with Katapult. He'd been referred by a mutual connection who'd worked with us on a complex product build, and the intro came with high praise.

D wasn't looking for software development. He had something more ambitious.

He wanted to figure out how to build a dream he'd been carrying for years: the first professional-grade, fully AI-generated feature film. Real production. Real composer. Real post. A name actor doing voice work. Theatrical or streaming release.

He had the producing partner, someone whose credits include billion-dollar franchises. He had the creative vision. What he was missing was the technical on-ramp to actually pull it off.

"I don't even know how to program my phone," he told us. "My editor comes to my house and I'm a total moron when it comes to tech stuff. But what I do understand really well is filmmaking."

## The gap that actually matters

The film industry is sitting on a fault line. AI video generation is advancing on a weekly cadence. Models out of China are pushing past what anyone expected on duration and consistency. Tools like Runway ML are approaching photorealism.

One of the most prominent directors in history recently estimated 5 to 7 years until a full AI feature film at blockbuster scale. We think he's wrong. We think it's closer to 2 for a human-directed, scene-by-scene AI production, and possibly 6 to 12 months for something that's rough but recognizably a feature.

(The distinction matters. "Fully autonomous AI generates an Avengers-scale blockbuster" is one claim. "A skilled director uses AI tools to produce a cohesive 90-minute film, shot by shot, with human judgment driving every creative decision" is a very different one. We're talking about the second.)

Here's the structural problem: the people with the deepest filmmaking expertise are watching from the sidelines. The Spielbergs and Camerons have unlimited budgets. They don't need to investigate AI yet. They'll adopt it once it's proven.

On the other end, technically gifted creators are producing beautiful AI-generated shorts on Instagram and YouTube. But they don't have the storytelling depth, production experience, or industry relationships to make something that actually moves an audience over 90 minutes and gets a theatrical release.

D sits in the middle. Decades of directing experience. Festival selections. Streaming hits. Relationships with A-list talent. A producing partner with franchise-level credits. He has taste, which is the one thing AI can't generate.

What he lacked was a bridge between how he thinks and what the tools require.

## What happened on the call

We didn't pitch anything. The conversation started as a brainstorm and turned into something more useful.

**D described what he actually wanted.** He didn't say "AI-generated movie" in the abstract. He described something specific: a virtual volume stage.

If you've watched The Mandalorian, you've seen the concept. Actors perform inside an LED dome where every background, prop, and environment is rendered digitally in real-time. D wanted that concept, but powered by AI generation instead of pre-built CG assets.

He would still place every camera. Still call for close-ups. Still direct the performance. AI would generate the world around his decisions.

**We asked a question that reframed things.** Instead of jumping to "let's build an Unreal Engine setup," we went somewhere different: how much of the physical production workflow should carry into a digital world? And what should we strip back and rebuild?

There's a concept called skeuomorphism, building digital things to look like physical things. The first smartphone keyboards looked like typewriters. Sometimes that's useful. Sometimes it's a cage.

If the actors are synthetic and the sets are generated, what's the point of simulating a volume stage? Maybe the whole idea of "placing a camera" gets rethought entirely.

D didn't have an answer. Neither did we. But the question cracked open space that wasn't there 5 minutes earlier.

**A technical explanation did more than a demo ever could.** D had been frustrated with ChatGPT losing track of his screenplay. He'd feed it scenes, collaborate for a while, and then it would start inventing things that contradicted what they'd already written.

We explained why: language models have a context window, essentially short-term memory. Once it fills up, the model starts making things up to keep you happy. It loses the thread.

D's reaction was immediate: "That's exactly what I experience. Somewhere into it, I'm like, you asshole, you know this isn't true."

That explanation landed because it matched something he'd already felt. And it gave him a framework: if context management is the constraint, then you manage context the way you manage a production. Scene by scene. Shot by shot. Deliberate setup at the top of each segment.

A similar (but technically different) problem exists in video generation. Current models can produce 10 to 60 seconds of coherent video per generation. The coherence breaks down over longer durations because the model loses track of temporal position, essentially forgetting where it is in the sequence. The bottleneck isn't identical to a text model's context window, but the creative workaround is the same: break the work into discrete, well-seeded segments and maintain consistency through deliberate inputs at the start of each one.

D started reasoning about this like a filmmaker, which is exactly what he should've been doing all along.

**Then the call went somewhere we didn't plan.** Normally this is where you say "great chat, let's schedule a follow-up."

Instead, we pulled up the transcript of the conversation (live, from a note-taking tool) and pasted it into Claude. We told it: build a plugin for this director. Use the transcript. Go research his public work. Create a writing collaborator that knows his voice.

(We should note: we're not sponsored by Claude, though we'd happily take that call. Or any of the other major labs. We're tool-agnostic. We'll use whatever is best aligned with creating value and bringing the future we're working toward, one where we maximize abundance, meaning, and value for as many people as possible. Right now, for this type of collaborative work, Claude's cowork mode happened to be the sharpest tool available.)

Claude found his interviews, his filmography, his public statements about storytelling. It assembled a profile: writes from deep personal pain, wants audiences to leave so angry they have no choice but to act, prioritizes emotional authenticity over cleverness.

D watched it happen and kept saying "how does it know that?"

Because he'd spent years saying it publicly. Nobody had organized it for him before.

By the end of the call, D had a custom AI plugin that understood his creative voice and working style. He had voice-to-text tooling that solved his core friction (his own words: "I'm much better at talking").

His in-progress screenplay was loaded into a working session alongside all supporting materials, ready for scene-by-scene collaboration. And he had a mental model for how context and coherence work, giving him a framework to think about AI production on his own terms.

His reaction: "You got me into this. That's crazy."

He went from "I just don't give a fuck about AI" to collaborating with a personalized writing partner. Under 90 minutes. No contract. No SOW. No pitch deck.

## The bigger insight

D isn't a Katapult client. At least, not in the traditional sense. No contract got signed on that call. No SOW got drafted.

What happened was more interesting: a creative professional with deep domain expertise went from dismissing AI to actively collaborating with it, in a single sitting.

That transformation didn't happen because someone explained the technology. It happened because someone understood his world first. The economics of production. The politics of actors' unions and industry adoption. The difference between a volume stage and a green screen. The specific frustrations of a director who's been on set with difficult talent.

The bridge got built from his side, not ours.

We keep seeing this pattern across industries.

D knows what makes a scene work. He knows when dialogue is "on the nose" versus subtextual. He knows how to light a face, stage a fight, build tension through pacing. No model can do that. The real value shows up when someone with 30 years of taste gets to iterate at the speed of thought instead of the speed of production budgets.

The technology gap is temporary. What requires custom engineering today will be turnkey in months. The professionals who engage now, even clumsily, will be the ones who know how to wield these tools when they mature. Everyone else will be starting from zero.

And taste is the competitive advantage. The most technically polished AI shorts being produced today are impressive but hollow. They lack the emotional architecture that makes a story land. The storytellers who learn to direct AI are going to eat the engineers who learn to tell stories.

The best technology partner understands your world well enough to translate between your instincts and the available tooling, then gets out of the way.

## Where this goes

The North Star that came out of the conversation: build the first professional-grade, fully AI-produced feature film. Give filmmakers a new kind of studio.

The work ahead is R&D at the frontier. Understanding the current state of the art. Testing limitations that'll disappear as models improve. Building workflows that evolve alongside the technology.

As we put it on the call: the ones riding the wave right now, crashing and trying to surf it, are the ones who'll catch it at the right time with the right skill set.

Was Pixar too early when it was flopping and burning cash before Jobs bought it? Someone has to go first.

D has the vision, the taste, and the industry relationships. The technology is on a steep curve. This is going to happen. The only question is who's in the room when it does.

We build the bridge between domain experts and AI tooling. We've done it in fintech, healthcare, logistics, and education. The pattern holds everywhere: the professionals with the deepest expertise benefit the most from AI, if someone bothers to build the on-ramp.

That's how we work.
