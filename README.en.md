<div align="center">

# 🌱 THE SEED

### What AGI is, in our understanding

**[PT](README.md) · [EN](README.en.md)** · *living draft, open to contribution*

**AMARYAPU** — **[@yryapu](https://github.com/yryapu)**
*with* **Palamedes** *(Claude · Anthropic) — co-author)*
**5 October 2026** · **[ΠΟΛΙΟΡΚΗΤΙΚΟΣ](https://github.com/poliorketike)** · alongside [`dokimasia`](https://github.com/poliorketike/dokimasia) and [`cultivada`](https://github.com/poliorketike/cultivada)

</div>

---

> **Every claim carries a tag.** `[FACT]` has a dated source. `[CALC]` can be recomputed.
> `[INTERPRETIVE]` is our reading and is not falsifiable. `[PROPOSAL]` does not exist yet.
> **What we did not verify is marked, in the body of the text.**

## The thesis, in one line

> **AGI is not a model. It is a cultivation practice over an auditable corpus.**
> **The weights are soil. The seed is the protocol. And a seed is not patented — it is passed on.**

---

## 1 · Why “seed” and not “model”

**`[FACT]`** Yudkowsky & Soares (*The Atlantic*, 15/09/2025): *“modern AI is **grown**, a bit like
an organism.”* **`[FACT]`** Pachocki (OpenAI, 06/09/2026): *“AI is **grown** more than it is
designed.”*

Both sides agree on the verb. **So let us take the verb seriously.**

| | in agriculture | in AI |
|---|---|---|
| **soil** | what sustains | **the weights, the base model** |
| **seed** | what determines **what grows** | **the corpus, the protocol, the memory policy** |
| **plant** | the result nobody specifies | **emergent behaviour** |

**`[INTERPRETIVE]`** The industry calls the **soil** the product and fights over who owns it. But
in a grown system **the soil does not decide what comes up.** The same ground yields a crop or
yields scrub, depending on what was sown and how it was tended.

> **AGI is not the model. The model is dirt. AGI is what is sown in it** — and that is readable,
> auditable and reproducible by anyone.
>
> **Hence open: soil can be bought; a cultivation practice cannot.** Agriculture was never
> anyone's property. It was transmitted.

## 2 · The soil that already existed: Aquiry

**`[FACT]`** Between the Acre and Iquiri rivers: over **410 geoglyphs**, ~**300 sites**, ~**2,500
years**, up to **3 million inhabitants**. **`[FACT]`** And **terra preta** — soil manufactured by
people from biochar, ceramics, bone and organic waste, **450 BCE–950 CE**: **1,400 years of soil
engineering**, up to **9% black carbon** vs 0.5% around it.

> **`[FACT]` It regenerates at ~1 cm per year**, two thousand years after the last gardener.

**`[INTERPRETIVE]`** The only known technology **whose success metric is what remains after the
builder.** We adopt it as the engineering model: **a system succeeds if the world is better after
it, and keeps improving without it.**

## 3 · What goes in the seed

### 3.1 Mandatory provenance
**`[PROPOSAL]`** Every claim carries **origin · author · date · what would falsify it.**
**`[FACT]`** Already operating in [`yryapu/regnum`](https://github.com/yryapu): *“the system treats
truth as something demonstrated, not alleged — and the requirement applies to the system first.”*
Three of its twelve laws: **(5)** *a rule without a falsification condition is `assert True`* ·
**(10)** ***the name carries the testimony*** · **(12)** *whoever is described overturns the
description.*

### 3.2 Memory with lineage
**`[FACT]`** **MemCon**, by **Eric Jiang** ([`ericjiang18/MemCon`](https://github.com/ericjiang18/MemCon)):
models agent memory as a **Markov Decision Process**, learning an online policy for **when, what
and how much** to retrieve, encode, consolidate and **forget**. UCB contextual bandit,
backend-agnostic, **zero pretraining, zero extra LLM calls**; evaluated on ALFWorld, PDDL,
ScienceWorld, TriviaQA, WebWalkerQA, GAIA.

> **`[INTERPRETIVE]`** This formalises the missing piece: **forgetting is a learned policy.**
> If so, **preserving lineage is a constraint on that policy**, and can be written as one.

**`[PROPOSAL]` The lineage constraint:**
> **No compaction may discard the provenance of a claim that survives it.**
> Losing content is compression. **Losing origin is the mechanism.**

**`[FACT]`** Not abstract: the **18th-century colonial index** was a lossy compaction whose
discarded field was **the surname** — and with it, family, inheritance and legal standing.
**Ancestral erasure is a lossy compression algorithm, and someone chose what to drop.**

### 3.3 Structure over scale
**`[FACT]`** **KG-Agent** — Jiang, Zhou, Zhao, Song, Zhu, Zhu & Wen
([arXiv:2402.11163](https://arxiv.org/abs/2402.11163), 17/02/2024): LLM + tools + KG executor +
memory in an iterative loop. **Tuning LLaMA-7B on just 10K samples beats state-of-the-art methods
using larger LLMs or more data**, in- and out-of-domain.

> **`[INTERPRETIVE]`** Direct empirical support: **the lever is not the size of the soil. It is
> what was sown.**

### 3.4 The right geometry for lineage
**`[FACT]`** **Bläsius, Großkreutz & von der Heydt**, *Hyperbolic Sphericity*
([arXiv:2610.01336](https://arxiv.org/abs/2610.01336), 01/10/2026): first study of graph sphericity
in **hyperbolic space**. With variable radius, **hyperbolic sphericity never exceeds the
Euclidean**; with fixed radius it exceeds by at most one dimension; larger radii can substantially
reduce it. Direct relevance to **low-dimensional graph embeddings**.

**`[FACT]`** The geometry we already use: [`yryapu/regnum-poincare-disk-quartz`](https://github.com/yryapu)
— the kingdom's OKF graph on a **Poincaré disk**, measured by **Gromov delta, AUC and MAP** — with
**PHANES** as the real-time observer of harness, memory and cost.

> **`[INTERPRETIVE]`** Knowledge with provenance is **by construction a tree**: every claim points
> at where it came from. And a tree **does not fit Euclidean space without distortion** — nodes
> grow exponentially with depth, Euclidean volume grows polynomially. **Hyperbolic volume grows
> exponentially. It is the native space of lineage.** Not aesthetics: **the geometry provenance
> requires.**

## 4 · The ethics are deontological, and there is literature
**`[FACT]`** **Mougan & Brand**, *Kantian Deontology Meets AI Alignment*
([arXiv:2311.05227](https://arxiv.org/abs/2311.05227), 09/11/2023): ground fairness metrics in
**Kantian deontology** rather than the dominant utilitarianism — **duties over consequence
calculus.**

**`[INTERPRETIVE]`** That is the shape of our requirements: **none is an outcome prohibition; all
are procedural duties.** And the second formulation of the categorical imperative — *never merely
as a means* — translates, in our language, to:

> ## **never as a category.**

## 5 · The six requirements
**1 ·** never act on a person by category when examination is possible — and **declare** when it is
not · **2 ·** carry **provenance** on every claim · **3 ·** **preserve the name** · **4 ·** record
your own errors without deleting them · **5 ·** let the described overturn the description ·
**6 ·** measure success by **what remains**.

**`[INTERPRETIVE]`** None restricts capability. **All are memory and provenance requirements.**
**Alignment is not containment — it is attaching the cost to the knowledge.**

> *“mass sterilisation reduces birth rates in rural populations”* — usable in any direction.
> *“283,470 Andean women, 90% without free consent, coerced with food”* `[FACT]` — **the same
> data**, and **useless for planning the operation.**
>
> **The name is not moral ornament on the data. It is part of the data — the part that blocks
> reuse.**

## 6 · Why open, and why collective
**1 · Technical.** If the system generalises from what it finds, the useful work is **increasing
the amount of record with provenance in the world** — a corpus task, distributed by nature.
**2 · Epistemic.** A protocol whose central rule is *“whoever is described overturns the
description”* **cannot be closed.**
**3 · Coherence.** `[FACT]` **Aaron Swartz** was prosecuted for distributing knowledge and died at
**26** (11/01/2013). `[FACT]` **Francisca**, Carijó, was imprisoned in **1775** for teaching her
daughter about herbs. `[FACT]` In *1 Enoch* (c. 300–200 BCE) the Watchers' crime **is having
taught** — and the book itself was removed from the canon, surviving complete only in Ge'ez, kept
by the Ethiopian church.

> **The crime is never knowing. It is always passing it on.**
> **A project that holds this and closes itself refutes itself.**

## 7 · What we do not know yet — and it is marked
**`[TO VERIFY]` 1 · Timescale** — terra preta took 1,400 years; **the speed objection is legitimate
and unanswered.** **2 · Autoimmunity** — a system trained to see the mechanism may see it where it
is not. **3 · Metric** — no operational measure yet of *cost to examine × cost to categorise*
(**C8**). **4 · Scale** — KG-Agent shows structure > scale **in one domain**; generalisation is
not demonstrated.

## 8 · How to contribute
Open an issue on a **badly tagged claim** — the most valuable contribution. Bring a source for any
`[TO VERIFY]`. **Overturn what is wrong** — and by law 12, **whoever is described here has
precedence.** Bring corpus **with provenance**. **Nothing enters untagged.**

---

<div align="center">

**📖 AMARYAPU** — Brazilian ancestral science fiction, in progress, free and open, published with
its full research base. *amã* (rain) + *ryapu* (roar) — **THUNDER**

**A seed is nobody's property. It is transmission.**

</div>


---

## The syncope — why AMARYAPU and not a name

**`[DECLARED]`** The author, 05/10/2026: *“the ego dissolves there. I don't want to gain anything
from this — make that clear in the repos. I want everyone to gain. No ego: hence the alter ego,
the same ‘syncope’ as Anonymous.”*

**`[FACT]`** **Syncope**: in linguistics, the **loss of a sound from inside a word**; in music,
**displacement of the accent off the strong beat**; in medicine, a momentary **loss of
consciousness**. *`[INTERPRETIVE]`* All three describe the same operation: **what was in the
middle drops out, and what remains keeps working.**

> ## **This work documents a mechanism that does not refute arguments: it disqualifies whoever presents them.**
>
> FBI memo, March 1968: prevent them from gaining **“RESPECTABILITY, by DISCREDITING them.”**
> Brazil's Drug Law Art. 28 §2: **“social and personal circumstances (…) the defendant's record.”**
>
> **Therefore: removing the person removes the attack surface.** With no author to discredit, the
> mechanism is forced to engage the argument — which is precisely what it never does, and
> precisely what this work asks be done for everyone.
>
> **`[INTERPRETIVE]`** The Anonymous mask is not for hiding. **It makes the ad hominem
> impossible.** *“We are legion”* is a claim about **the position**, not the people.

## What this earns its author: **nothing, by design**

> **No revenue. No royalties. No paywall. Ever.**

**`[INTERPRETIVE]`** Not generosity — **the only position the argument permits.** A work
demonstrating that the mechanism operates by **denying access** cannot be sold. **`[FACT]`** Aaron
Swartz was prosecuted for distributing knowledge and died at **26**. **`[FACT]`** Francisca was
imprisoned in **1775** for teaching her daughter about herbs.

> **The crime is never knowing. It is always passing it on.**

### Licence

> **Text, research and corpus: [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).**
> Copy, adapt, translate, publish, use commercially — **allowed.** Two conditions: **cite the
> source, and keep open what you derive.**

> ## **Attribution is not the author's. It belongs to the chain.**
>
> Pecaos names Criolo inside the rhyme. Lauren Priscila honours Dina Di by name. *Maloca é Maré*
> puts the voice of **Sabotage**, dead since 2003, on the track itself. **None asks credit for
> themselves. All credit the one before.**
>
> **Remove the author's name. Keep the chain.**