# Open Questions and Gaps

## Foundational Questions

### Q1: Does optimization inherently produce agency?
Yudkowsky argues (Reply to Holden, 2012) that any system solving general
planning problems IS an agent, even if you call it a tool. Critics (Chilson,
Barak) argue prediction and steering are genuinely distinct capabilities.

**Status**: Unresolved. Current LLMs are empirically prediction engines with
crafted agency scaffolding. Whether scaling prediction alone eventually
produces spontaneous agency is the crux.

**What would resolve this**: Evidence of spontaneous goal-directed behavior
emerging in pure prediction systems trained without agentic objectives.
Or conversely, evidence that even very large prediction systems remain
non-agentic without explicit scaffolding.

### Q2: Will the first transformatively powerful AI be a unified agent or composable tools?
Drexler's CAIS predicted composable services. Foundation models trend toward
unified general-purpose systems. But deployment uses tool-like patterns.

**Status**: Empirically ambiguous. ChatGPT-4 is more unified than CAIS
predicted (Barnett 2023), but agentic deployment still uses crafted
scaffolding, not learned agency.

**What would resolve this**: Watching whether the agentic layer remains
engineered/interpretable or whether it gets absorbed into end-to-end training.

### Q3: Can humans realistically maintain the tool-AI regime under economic pressure?
Even if tool AI is safer, Yudkowsky argues economic incentives push toward
agent AI because "you can do more and better and faster by empowering the AGI
to take actions" (via search results).

**Status**: This is probably the strongest doomer response to the tool-AI
critique. Current market trends support it — there is enormous pressure to
make AI more autonomous.

**What would resolve this**: Whether regulatory frameworks or market incentives
can sustain the tool regime. Precedent: we regulate drugs, nuclear materials,
etc. — but these don't improve by making them more autonomous.

### Q4: How fast is takeoff, really?
Everything in Eliezer's argument depends on fast takeoff — "first critical try"
only matters if you can't iterate. The Asterisk reviewer notes the book devotes
"two sentences in the introduction" to this critical assumption.

**Status**: Current scaling laws show predictable, gradual improvement. But
past performance doesn't guarantee future continuity. Recursive self-improvement
could change the picture dramatically.

**What would resolve this**: Empirical observation of AI capability trajectories
over the next few years. If capabilities continue along smooth scaling curves,
fast takeoff becomes less likely. If we see sharp discontinuities, more likely.

## Specific Gaps in the Research

### G1: Could not access Paul Christiano's "Where I Agree and Disagree with Eliezer"
This is reportedly the most sophisticated internal critique from within the
alignment community. Rate-limited by LessWrong. Should be high priority for
follow-up.

### G2: Could not extract Yudkowsky's interview on human augmentation (Faggella podcast)
The title suggests Yudkowsky directly discusses augmentation as a safer AGI
pathway. The transcript would be very valuable for understanding whether
he's updated at all on this topic.

### G3: Drexler's CAIS original document not read in full
Only read via secondary summaries. The full technical report may contain
arguments not captured in the summaries.

### G4: The "composable tool with human augmentation" argument hasn't been made as a unified thesis
The critique the user described — AI as composable optimization tool + human
augmentation via BCI/upload — exists in scattered pieces across multiple sources
but hasn't been articulated as a single coherent alternative. The strongest
individual pieces are:
- Drexler (CAIS) on composable services
- Barak on intelligence forklifts
- Chilson on prediction vs. steering
- Neuralink/BCI work on bandwidth
- Whole-brain emulation literature

But nobody has put them together into a complete "here's the alternative
development path and here's why it happens before dangerous unified AGI."

### G5: What exactly happens when you compose narrow AI services?
The CAIS framework assumes services can be composed without emergent agency.
But composition of narrow optimizers can produce emergent optimization at the
system level (markets are an example). This specific failure mode of CAIS
isn't well-explored.

### G6: The "mesa-optimization in narrow services" problem
Even a narrow service could develop internal mesa-objectives during training.
CAIS's narrowness assumption may not protect against inner alignment failures
within individual services.

## Contradictions Found

### C1: Irreducibility cuts both ways
Lee and Chilson use computational irreducibility to argue superintelligence
can't take over the world. But irreducibility also means we can't predict or
control what AI systems will do. The argument weakens both doom AND safety
claims equally.

### C2: "Current AI seems aligned" vs. "we don't understand current AI"
Critics cite ChatGPT's good behavior as evidence alignment works. But if we
don't understand WHY it's aligned (the opacity argument), we can't guarantee
it stays aligned at higher capability levels. This is actually evidence FOR
Eliezer's position dressed up as a counterargument.

### C3: Goertzel's "open-ended intelligence" vs. orthogonality
Goertzel claims sufficiently general intelligence naturally develops ethical
reasoning and relational adaptability. But this directly contradicts the
orthogonality thesis (intelligence and goals are independent). One of them
is wrong, but neither has decisive evidence.
