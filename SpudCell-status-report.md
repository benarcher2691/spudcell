# SpudCell — Development Status Report

*Prepared 2026-07-04 · Updated 2026-10-11 · Sources: primary preprint manuscript + Wikipedia, Science, and The Guardian coverage (all archived in `./papers/`)*

## TL;DR

SpudCell is the first **bottom-up synthetic (artificial) cell** shown to run a *complete cell cycle* — feeding, growth, genome replication, and genetically encoded division — built entirely from chemically defined, non-living components. It was unveiled on **1 July 2026** by **Kate Adamala's lab at the University of Minnesota Twin Cities**. The community reaction ranges from "stunning… biggest breakthrough in recent times" to firm caution that it is *not alive* and *not yet peer-reviewed*. The work is currently a **preprint** (190-page manuscript), released outside the normal journal pipeline after a rejection from *Cell*.

---

## 1. What SpudCell is

- A **synthetic minimal cell**: liposomes (water droplets ~a few µm wide, wrapped in a fatty membrane) containing a cell-free protein-expression system and a fully defined DNA genome.
- Built **from the bottom up** — every component is known and characterized — rather than by stripping down a natural organism (the approach Craig Venter used in 2010).
- Genome: **~90 kbp encoded across seven plasmids**, roughly **50× smaller than a typical bacterium**. News coverage summarizes this as **~36 genes**, drawn from *E. coli* and viral sources (notably the Phi29 replicase from a *Bacillus subtilis* phage).
- Runs on the **PURE system** (Protein synthesis Using Recombinant Elements) — a defined kit of the biomolecules needed to transcribe DNA→RNA and translate RNA→protein — encapsulated inside the liposomes.
- **Name:** coined by Adamala to evoke *Sputnik* and the dawn of a new era; she also jokes, "I'm Polish… I'm mostly made of potatoes."

## 2. Who is behind it

- **Lead:** Dr. Katarzyna (Kate) P. Adamala, University of Minnesota Twin Cities.
- **Manuscript authors:** Nathaniel J. Gaut, Christopher Deich, Brock Cash, Tanner Hoog, Aaron E. Engelhart, Katarzyna P. Adamala.
- **Manuscript:** *"A Chemically Defined Synthetic Cell Capable of Growth and Replication"* — 190 pages, ~5 researcher-years of effort.
- **New institution — Biotic:** a public-benefit research organization co-founded by Adamala, Stanford bioengineer **Drew Endy**, and two others, to coordinate synthetic-cell research globally. Seed funding **~$10M**; first grants expected **September 2026**. Endy frames the goal as building "an operating system for life."
- **Licensing:** Biotic will license the core SpudCell technology — **free for academics and nonprofits, fees for commercial use** (Adamala, via CNN). Though US-based, Biotic says it will soon support work in **Japan, the UK, France, Germany, and the Netherlands** (Hoover interview).

## 3. What has been demonstrated (the cell cycle)

| Function | Mechanism | Status |
|---|---|---|
| **Feeding / growth** | Genetically encoded liposome fusion: cell expresses modified α‑hemolysin (αHL) that displays a 6×His tag on the surface; "feeder" vesicles carrying Ni‑NTA lipids bind and fuse, delivering lipids, enzymes, ribosomes, small molecules | ✅ Demonstrated |
| **Genome replication** | Phi29 replicase (rolling-circle amplification); TTcDR — transcription–translation-coupled DNA replication | ✅ Demonstrated |
| **Division** | Genetically encoded: FLAG surface tag binds streptavidin, generating membrane repulsion that splits the droplet; also achieved mechanically by extrusion through a filter | ✅ Demonstrated (inefficient) |
| **Selection / competition** | An inserted mutation that raises growth-protein output let mutant cells grow faster and outcompete originals (~60% of genomes carried the mutation after 5 rounds) | ✅ Demonstrated (artificial, not spontaneous) |

## 4. What it cannot do (limitations)

- **Cannot make its own ribosomes** — ribosomes degrade over time with no way to replace or recycle them.
- **Cannot regulate its own metabolism** or **clear waste**.
- **Wholly dependent** on a nutrient-rich external medium (ATP and other chemicals) and on "feeder" vesicles.
- **Division is very inefficient** — multiple rounds required mechanical extrusion; only **~30% of cells carried the full genome after 5 division cycles** because replicated genomes don't partition cleanly.
- **"Conks out" after a few generations.**
- **Not true Darwinian evolution** — the beneficial mutation was inserted by researchers, and cells were divided mechanically.
- **No cytoskeleton** — robust, controllable division will likely eventually need a synthetic one.
- Adamala's own framing: *"It is not as robust, as fast, or as good at most of its functions as a natural cell, but it is proof of principle."*

## 5. Publication status & controversy

- **Not yet peer-reviewed.** Released as a **preprint** so other labs can scrutinize it without delay.
- The manuscript was **rejected by *Cell***, where one reviewer argued SpudCells "were not real biology."
- Adamala then **sent the 190-page manuscript to journalists under embargo**, in some cases before posting to bioRxiv — an unusual sequence that drew criticism (Kerstin Göpfrich: "an unusual way of doing things"). The group says it will submit to a new journal soon.
- Adamala's rationale: *"This is like the spark"* — getting the work out fast to jump-start a coordinated field.

## 6. How the field is reacting

**Supportive**
- **Roseanna Zia** (Univ. of Missouri): "a stunning scientific achievement."
- **Job Boekhoven** (TU Munich): incorporating all modules together is "the feat that the field has been waiting for" (but stresses peer review is needed).
- **Drew Endy** (Stanford): "a catalyzing moment" — likens it to the Wright brothers' first plane vs. being handed a Dreamliner without plans.
- **Tom Ellis** (Imperial College London): "probably the biggest breakthrough in recent times."

**Cautious / critical**
- **Seraphine Wegner** (Univ. of Münster): "a very cool paper, but I don't think it means we're close to creating a fully synthetic cell."
- **Kerstin Göpfrich** (Heidelberg): critical of the publicity-first rollout.
- **John Dupré** (Univ. of Exeter, philosopher of biology): questions the practical point vs. engineered bacteria, and notes it omits the "relational/symbiotic" aspect of real life.

## 7. Significance & where it's headed

- **Why it matters:** the first system to *couple growth and division to gene expression* in a fully defined, non-living-origin cell — a long-standing hurdle because each cellular function tends to need different conditions (magnesium, pH, etc.).
- **Two payoffs:** (1) a fully understood **chassis/"operating system"** for engineering biology to make drugs, foods, fuels, and materials; (2) insight into the **minimum requirements for life** and how life emerged from chemistry.
- **Next steps (from the manuscript & Biotic):** more robust, higher-yield, controllable division; a route toward a **synthetic cytoskeleton**; coupling growth + division + *spontaneous* mutation into genuine Darwinian evolution; and improving metabolic self-sufficiency (self-produced ribosomes).

## 8. Developments since July 2026

*Added 2026-08-28, extended 2026-10-11. Nothing below changes the science: as of 28 Aug the preprint was still v1 on bioRxiv (posted 2 Jul); no journal version or revision has been reported since (bioRxiv itself blocked automated checks on 11 Oct).*

**Since 28 Aug**

- **Bloomsday held as planned** (10 Sep, Philadelphia). The only write-up so far is Yelena Biberman's "Soon Enough to Matter" (*Bioinsecurity* Substack, 15 Sep). It names the safety & security panel: moderator **Kenneth Oye** (MIT), with **Tom Inglesby** (Johns Hopkins Center for Health Security), **John Glass** (J. Craig Venter Institute), **Sam Evans**, and Biberman. Biotic has posted no recap or recordings.
- **No Biotic grant announcement yet**, despite the September target. biotic.org's only dated post is still the 2 Jul launch essay.
- **Wikipedia** — the SpudCell article saw only cleanup in September (reference fixes, a maintenance tag, two reverted edits). No substantive change.

**July–August**

- **Peer review underway** — Biotic's FAQ states the work is "being released as a preprint, with peer review underway at a journal" — journal unnamed, no timeline given. It also notes the authors discussed the work with field experts and refined the paper in response ahead of release.
- **Biotic FAQ adds technical color** — one generation takes **~12 hours at 30 °C** with regular feeding (five generations run; *E. coli* divides every 20–30 min); Biotic names **five open engineering challenges** between SpudCell and a dependable engineering substrate: consolidating the genome into a single stably inherited form, strengthening protein/energy systems, making genetically-encoded division dependable, engineering the ribosome from defined components (**"ribogenesis"**), and integrating bottom-up safety and security. It also details why SpudCell can't survive outside the lab and argues misuse risk is remote.
- **Biotic launch essay** — "Out of One, Many," on biotic.org (Jul 2026). Names the next goal a **"Liberty Cell"** that makes its own parts and sustains itself; confirms **CellOS** as the flagship project; notes SpudCell's plasmids descend from DNA modules shared on **Addgene** almost a decade ago; and cites a **state-backed Shenzhen effort spanning 100+ labs** with a ten-year roadmap toward the same destination as a reason to build in the open. Names the four founders in full: **Adamala, Endy, Jedryszek, Raggio**.
- **Hoover Institution founders' interview** — "Building Cells, Building a Field" (1 Jul), with all four founders. Adamala first showed Endy the SpudCell result **in confidence at the Build-a-Cell workshop at Stanford in spring 2025**. Endy places SpudCell in a near-decade collaboration with Richard Murray (Caltech), John Glass (JCVI), Elizabeth Strychalski (NIST), and Lynn Rothschild (NASA). He also cites the **May 2026 roadmap from China's SynCell Asia Initiative**, which calls for a centralized, AI-driven biofoundry in Shenzhen.
- **Biotic kick-off event — "Bloomsday 2026"** — **10 Sep 2026**, Science History Institute, Philadelphia. Full programme published: Endy on "The Biotic Future," Adamala on "Why Synthetic Cells Matter," sessions on biosecurity, ethics, and governance, and a conversation with the four founders.
- **Provisional patent filed** — disclosed on the bioRxiv abstract page ("Provisional patent application has been filed"); the July sources didn't mention IP.
- **Open release** — SpudCell was released "openly, in full" at launch: preprint, manuscript, and protocols (biotic.org/protocols) rather than held behind journal publication.
- **Wikipedia article created** — <https://en.wikipedia.org/wiki/SpudCell>, last edited 21 Jul 2026 (English + Arabic). Carefully framed: describes claims as "claimed," notes no peer-reviewed publication.
- **Later coverage** — *Quanta*, "For the First Time, a Cell Built From Scratch Grows and Divides" (1 Jul); *New Scientist*, "What is 'SpudCell'?" (1 Jul, paywalled); STAT, "Synthetic biology researchers think they've made a cell. Is it alive?" (1 Jul, paywalled); CNN, "Scientists say they have made a cell from scratch for first time" (1 Jul; source of the licensing terms, plus ethicist Laurie Zoloth on Biotic's governance); SingularityHub (9 Jul); *The Scientist*, "Meet SpudCell" (12 Jul); *Science News*, "No, the 'first synthetic life' isn't alive" (17 Jul, updated 25 Aug); *Lab Manager* (22 Jul); Science in Poland, "Polish researcher's team first to build synthetic cell from scratch" (24 Jul) — profile, no new science.
- **Correction watch** — biotic.org's SpudCell overview says the 90 kbp genome is spread across "**nine** separate DNA molecules," contradicting its own architecture section and the manuscript (**seven plasmids**). Treat "nine" as their typo.

---

## Sources & downloaded files (`./papers/`)

- **`spudcell-manuscript.pdf`** — Gaut, Deich, Cash, Hoog, Engelhart, Adamala. *"A Chemically Defined Synthetic Cell Capable of Growth and Replication."* Preprint (190 pp.), via biotic.org. *(Extracted text: `spudcell-manuscript.txt`.)*
- **`science-spudcell.txt`** — Kai Kupferschmidt, "Lab-created 'SpudCell' marks 'stunning' step toward building life from scratch," *Science*, 1 Jul 2026.
- **`guardian-spudcell.html`** — Ian Sample, "'Beautiful blobs': synthetic life a step closer…," *The Guardian*, 1 Jul 2026.
- **`nyt-spudcell.html`** — Carl Zimmer & Marco Hernandez, "This Cell Feeds, Grows and Reproduces. And It's Manmade," *The New York Times*, 1 Jul 2026.
- Wikipedia: <https://en.wikipedia.org/wiki/SpudCell> *(archived: `wikipedia-spudcell.html`, snapshot 28 Aug 2026)*
- **`quanta-spudcell.html`** — "For the First Time, a Cell Built From Scratch Grows and Divides," *Quanta Magazine*, 1 Jul 2026.
- **`biotic-out-of-one-many.html`** — Biotic, "Out of One, Many," launch essay, biotic.org (Jul 2026).
- **`biotic-bloomsday-2026.html`** — Biotic kick-off event page, "Bloomsday 2026," Science History Institute, Philadelphia, 10 Sep 2026.
- **`biotic-faq.html`** — Biotic, "FAQ" (SpudCell + Biotic sections), biotic.org, snapshot 28 Aug 2026.
- **`hoover-building-cells.html`** — Endy et al., "Building Cells, Building a Field," Hoover Institution, 1 Jul 2026.
- **`cnn-spudcell.html`** — "Scientists say they have made a cell from scratch for first time," CNN, 1 Jul 2026.
- **`the-scientist-spudcell.html`** — "Meet SpudCell: The First Synthetic Cell Built from Non-Living Parts," *The Scientist*, 12 Jul 2026.
- **`sciencenews-spudcell.html`** — "No, the 'first synthetic life' isn't alive," *Science News*, 17 Jul 2026 (updated 25 Aug).
- **`labmanager-spudcell.html`** — "SpudCell Synthetic Cell Grows, Replicates DNA, and Divides," *Lab Manager*, 22 Jul 2026.
- **`bioinsecurity-soon-enough-to-matter.html`** — Yelena Biberman, "Soon Enough to Matter," *Bioinsecurity* (Substack), 15 Sep 2026.
- Not archived: UMN press release, "World's first synthetic cell with a complete life cycle could revolutionize biological engineering" (twin-cities.umn.edu; blocked by a Cloudflare bot check).
- Additional coverage: *The Economist*, "Scientists have built a cell from the ground up," 1 Jul 2026; *New Scientist* (1 Jul) and STAT (1 Jul), both paywalled; SingularityHub, 9 Jul 2026; Science in Poland, 24 Jul 2026.
