<document>

<metadata>
  <doc_id>sol-000-fact-check-log</doc_id>
  <title>The Spear of Lugh — Fact-Check Log (V16)</title>
  <category>Reference / Anti-Hallucination</category>
  <status>Active_Reference</status>
  <last_updated>2026-11-10</last_updated>
  <instruction_for_ai>
    Read this file together with sol-000-logic-ref before stating facts drawn from the corpus.
    Each article file carries its own fact_check block; this log consolidates every CORRECTION
    and UNVERIFIED item. Statuses: CHECKED (date + verbatim content verified against the Substack
    export), VERIFIED (real-world claim confirmed by web search), CORRECTION (error in the
    author's text or in earlier AI-generated metadata — the author's text itself is never altered),
    UNVERIFIED (could not be confirmed), NOTE (context or nuance). When a CORRECTION concerns the
    author's own text, quote the author faithfully but do not repeat the erroneous claim as fact.
  </instruction_for_ai>
</metadata>

<content>

# Fact-Check Log — V16 (2026-11-10)

## Method

1. **Source of truth for texts and dates**: the author's Substack export of 2026-11-06 (posts.csv + HTML posts).
   Every article's date field was replaced by its exact publication date and every content block by the
   verbatim post text (converted from HTML). Song lyrics and longer copyrighted literary quotations were
   replaced by bracketed placeholders.
2. **Content fidelity audit** (word-level alignment between V15 content blocks and the export): 36 of 105
   article files reproduced less than 90% of the original text (abridged or paraphrased), 14 less than 50%,
   and 9 were reconstructions with less than 15% of the real text (sol-000n, sol-000r, sol-000s,
   sol-010c to sol-010g, and sol-024, which was an empty placeholder). All were replaced by the verbatim text.
   Two files contained paragraphs **transplanted from later articles** (sol-000l, sol-000m).
3. **Real-world claims**: checked by web search on 2026-11-10, prioritising anti_hallucination warnings,
   context fields and every event mentioned in the 40 new articles (May–November 2026).

## Counts

- CHECKED: 142
- CORRECTION: 41
- NOTE: 35
- UNVERIFIED: 7
- VERIFIED: 105

## Most important corrections

1. **sol-032 (The Kirk Transform)** — V15 said the Charlie Kirk assassination was a *fictional scenario*
   and that "Charlie Kirk is alive". **False**: Kirk was killed on 10 September 2025 at Utah Valley
   University; the article was written five days later. Fixed in sol-032, sol-000-logic-ref (err-009) and here.
2. **sol-000l (Dawn of the Midwits, 2022)** — contained a paragraph from sol-024g (Bullet Time, 2024):
   the "Biden eigenvalue" concept is from 2024, not 2022. Lexicon, README and thematic map corrected.
3. **sol-000m (Topological Wars, Feb 2023)** — ended with two paragraphs from sol-015b (Nov 2023, mentions
   Milei's election): Möbius strip and Byzantine fault are NOT in sol-000m. Genealogy corrected.
4. **sol-000n (Facts by Fiat)** — not paywalled; metadata was reconstructed and misdescribed the
   "social Oracle problem" (it derives from the *blockchain* oracle problem). Rewritten.
5. **Dates** — 5 files had a wrong year (sol-026, sol-030, sol-031, sol-033, sol-034) and sol-000r was dated
   June 2020 instead of 30 March 2021 (Medium original: 21 June 2020). "Earliest article" claims for
   sol-000o and sol-000r were false (earliest in the repository: sol-000b, 13 April 2020).
6. **Invented or wrong references in metadata** — "Thornhill et al. 2009 PNAS" (sol-013c), "Rosset
   translation 1984" (sol-010g), "China mining ban May 2022" (sol-003b), "Nolan's Odyssey 2025"
   (sol-034), "NJ drones officially unexplained" (sol-036), "unattributed French lyric" (sol-013d — it is
   Lavilliers), "sol-046 Human2Vec" (sol-000j), "sol-013d Möbius" (sol-000m), Athestia/Flat Checking order
   (sol-045), Starlink episode dating (sol-054b), "Lyon/Villeurbanne" embellishment (sol-062).

## All CORRECTION items

- **sol-000l** — The previous content block contained a paragraph that is NOT in this article: the "eigenvalue that looks like Biden" / "averaging monster" passage was transplanted from "Bullet Time" (sol-024g, February 2024). The verbatim text has been restored and the metadata corrected: the eigenvalue-convergence concept is coined in sol-024g, not in this 2022 article; this article contributes "leaders mutating into followers", the Larsen-effect swarm and the Keynesian beauty contest.
- **sol-000m** — The previous content block ended with two paragraphs (Byzantine fault, Bitcoin/China, Milei, "The Möbius strip...") that belong to sol-015b (Nov 2023) — an anachronism in a February 2023 text (Milei was elected in November 2023). Verbatim text restored; the "Byzantine Fault and Political Resilience" concept and the Byzantine bridge were removed from this file. The article's real ending is about inventing "topological characteristics" that would make manipulation of the global conversation manifest (puncturing the surface).
- **sol-000n** — This article is NOT paywalled: the full text is in the Substack export and has been restored verbatim. The previous metadata was a reconstruction from a search snippet and described the "social Oracle problem" as a cousin of a philosophical oracle problem; the text actually says it is "a distant cousin of the legit blockchain oracle problem" (how a blockchain learns about real-world events). Metadata rewritten from the text.
- **sol-024** — The previous file contained no article text (placeholder "published after ZIP export date"). Full verbatim text restored from the Substack export.
- **sol-032** — Previous metadata and the logic-reference file (err-009) claimed the assassination was a fictional scenario and that "Charlie Kirk is alive". This was false: Kirk was assassinated on 10 September 2025. Corrected here, in the logic reference, and in the fact-check log. — <https://www.pbs.org/newshour/politics/live-updates-turning-point-usa-co-founder-charlie-kirk-shot-at-utah-college-event>
- **sol-000d** — Broken cross-reference "sol-009-jacobs-escalator" replaced by sol-000e (Jacob's Escalator).
- **sol-000j** — The previous metadata pointed to "sol-046 (Human2Vec)"; Human2Vec is sol-049 (sol-046 is The Sheep of Theseus). Fixed.
- **sol-000j** — Earlier README versions called this the "earliest article in the corpus after sol-000b". False: sol-000o, sol-000p, sol-000q, sol-001 (2020) and sol-000g, sol-000r, sol-000s (2021) are earlier. Fixed in README V16.
- **sol-000o** — Previous versions called LEG "the earliest article in the corpus". Dates from the Substack export: sol-000b (13 Apr 2020) and sol-001 (16 Apr 2020) are earlier; the earliest post of the archive is "Pancake Thinkers" (28 Mar 2020, not in this repository).
- **sol-000r** — The Substack publication date is 30 March 2021; the text states it was first published on Medium on 21 June 2020. It is not the earliest article.
- **sol-000r** — The previous content block reproduced only ~3% of the article (a reconstruction). Full verbatim text restored.
- **sol-000s** — The previous content block was a short reconstruction (~2% of the text). Full verbatim text restored.
- **sol-003b** — China's crackdown on Bitcoin mining took place in May–June 2021 (not May 2022 as previously stated in the metadata).
- **sol-010c** — Previous content was a reconstruction (~6% of the text). Full verbatim text restored.
- **sol-010d** — Previous content was a reconstruction (~11% of the text). Full verbatim text restored.
- **sol-010e** — Previous content was a reconstruction (~5% of the text). Full verbatim text restored.
- **sol-010f** — Previous content was a reconstruction (~12% of the text). Full verbatim text restored.
- **sol-010g** — Previous content was a reconstruction (~10% of the text). Full verbatim text restored.
- **sol-010g** — The English translation of Rosset's "Le réel et son double" was published by Seagull Books in 2012 (not 1984). — <https://seagullbooks.org/the-real-and-its-double>
- **sol-011c** — The previous warning muddled the etymology; the author's gloss matches Genesis 32:28.
- **sol-013c** — Removed an inaccurate citation ("Thornhill et al., 2009 PNAS"); replaced with a verifiable reference. — <https://hraf.yale.edu/ehc/hypotheses/2903>
- **sol-013d** — The French verses quoted at the end are from Bernard Lavilliers, "Noir et Blanc" (1986) — not unattributed. Lyrics and translation removed from the content (copyright).
- **sol-026** — Date was "2025"; the article was published on 6 December 2024.
- **sol-030** — Date was "2024"; the article was published on 29 May 2025.
- **sol-031** — Date was "2025"; the article was published on 13 February 2026.
- **sol-033** — Date was "2025"; the article was published on 23 February 2026.
- **sol-034** — Date was "2025"; the article was published on 18 February 2026.
- **sol-034** — Nolan's The Odyssey: release July 2026, not 2025.
- **sol-036** — The White House offered an official explanation of the NJ drones on 28 January 2025 (FAA-authorized flights). — <https://abc7ny.com/post/white-house-says-many-drones-spotted-new-jersey-east-coast-were-flown-faa-was-not-enemy/15844019/>
- **sol-042** — Vice filed for bankruptcy on 15 May 2023, after this post's publication date.
- **sol-045** — Flat Checking (24 Feb 2025) predates Athestia (14 Mar 2026); the earlier warning had the order reversed.
- **sol-054b** — The Starlink episode happened in September 2022 (revealed September 2023); Isaacson corrected his account (refusal to activate rather than a cut-off). — <https://www.mediaite.com/print/walter-isaacson-corrects-reporting-on-elon-musk-cutting-ukrainian-militarys-access-to-starlink>
- **sol-062** — The author writes that the trolley problem "was a thought experiment precisely set up to study ethical dilemmas of automated systems". Historically false: Philippa Foot introduced it in 1967 (doctrine of double effect) and Judith Jarvis Thomson named it (1976/1985); its application to autonomous vehicles dates from the 2010s.
- **sol-062** — The previous content block was abridged/paraphrased (≈63% of the text); verbatim text restored.
- **sol-074** — The text implies no positive French budget since Mitterrand; in fact the last balanced budget dates from 1974 (Giscard d'Estaing), so deficits predate Mitterrand.
- **sol-075** — "Operation Midnight Hammer was launched 12 months ago and was followed by the 12-day war": the US strikes (Midnight Hammer, 22 June 2025) took place during the 12-day war that Israel began on 13 June 2025, near its end — not before it.
- **sol-080** — "Kodak ... completely vanished": Eastman Kodak went through bankruptcy (2012–2013) but still exists; its consumer film-camera dominance vanished.
- **sol-081** — The French ban on social media for under-15s announced for 1 September 2026 was struck down by the Constitutional Council on 14 August 2026 (decision 2026-911, per Wikipedia), after this article.
- **sol-094** — "Yesterday" in a post dated 8 October refers to the 6 October release (the post was likely drafted on 7 October).
- **sol-095** — The sentence "Mathematicians did not ask for this work to be done" is, according to Wikipedia's account, a statement of the Association for Human Mathematics, not of Terence Tao (the text places it right after mentioning Tao). Tao's documented reactions contrasted "Math 1.0" and "Math 2.0". Calls for mathematicians to stop collaborating with OpenAI were reported. — <https://mezha.ua/en/news/mathematicians-urge-end-to-openai-collaboration-315962/>
- **sol-096** — See warning on Combs: acquitted of trafficking/RICO, convicted on Mann Act counts; projected release in 2028.

## All UNVERIFIED items

- **sol-039** — The attribution of "Omnicause" to Alysia Ames could not be confirmed.
- **sol-041** — "All of Europe put 2.1 metric tons into orbit" in 2025 — likely understated.
- **sol-072** — The Axios "half a trillion dollars" figure and the "King of England" podcast remark could not be confirmed.
- **sol-081** — The figure of "150 km of deep cuts" by local communities could not be confirmed.
- **sol-089** — The Gartner ($6.31 trillion, +13.5%), Cast AI (~23,000 clusters) and "54% of consumers" figures from the AI review were not independently verified.
- **sol-097** — The fire at the University of Rouen on the night of 16–17 October is reported by the author; not independently confirmed here.
- **sol-098** — The speech length (8 min 35 s) and the Lyon tourist office fire are reported by the author.

## Verified chronological index (all article files)

| Date | File | Title | Phase (by date) |
|------|------|-------|-----------------|
| 2020-04-13 | sol-000b-digitalized-portal | The Digitalized Portal | P1 Exploration |
| 2020-04-16 | sol-001-ergodicity | Ergodicity and Digital Culture | P1 Exploration |
| 2020-04-22 | sol-000o-leg-law-of-excluded-gap | LEG — Law of Excluded Gap | P1 Exploration |
| 2020-05-10 | sol-000p-politics-of-lightning-rod | The Politics of the Lightning Rod | P1 Exploration |
| 2020-07-06 | sol-000q-data-diet | Data Diet and the Sin of Radical Abstinence | P1 Exploration |
| 2021-03-20 | sol-000g-dorian-grays-selfie | Dorian Gray's Selfie | P1 Exploration |
| 2021-03-30 | sol-000r-old-and-new-normal | The Old and the New Normal | P1 Exploration |
| 2021-05-01 | sol-000s-on-digital-discussions | On Digital Discussions | P1 Exploration |
| 2021-09-17 | sol-000j-abc-authorization-based-citizenship | ABC — Authorization Based Citizenship | P1 Exploration |
| 2021-11-29 | sol-000c-dehumanizing | Dehumanizing One Fact at a Time | P1 Exploration |
| 2021-12-07 | sol-000d-scales-scopes | On Scales, Scopes and Ladders | P1 Exploration |
| 2022-01-10 | sol-007-unmasking | The Unmasking | P1 Exploration |
| 2022-01-27 | sol-008-wittgensteins-rulers | Wittgenstein's Rulers | P1 Exploration |
| 2022-02-13 | sol-004-disablers | The Disablers | P1 Exploration |
| 2022-03-07 | sol-000f-swarm-and-sword | The Swarm and the Sword | P1 Exploration |
| 2022-03-16 | sol-010c-clusion-wars | Clusion Wars | P1 Exploration |
| 2022-03-25 | sol-002-topological-revolution | The Topological Revolution | P1 Exploration |
| 2022-04-13 | sol-010e-surface-of-exchange | The Surface of Exchange | P1 Exploration |
| 2022-04-16 | sol-010d-social-media-wars | Social Media Wars | P1 Exploration |
| 2022-07-10 | sol-010f-first-will-be-last | The First will be Last | P1 Exploration |
| 2022-07-14 | sol-000l-dawn-of-the-midwits | Dawn of the Midwits | P1 Exploration |
| 2022-07-20 | sol-010g-yesterday-no-longer | Yesterday is No Longer What It Used to Be | P1 Exploration |
| 2022-08-10 | sol-003b-distributed-systems-catallaxia | On Distributed Systems and Catallaxia | P2 Crystallization |
| 2022-08-15 | sol-000n-facts-by-fiat | Facts by Fiat | P2 Crystallization |
| 2022-12-13 | sol-011d-web-and-rack | The Web and the Rack | P2 Crystallization |
| 2023-01-08 | sol-000e-jacobs-escalator | Jacob's Escalator | P2 Crystallization |
| 2023-02-02 | sol-013e-nada-que-perder | Nada que perder — Mirame Reir — Volvemeros a Salir | P2 Crystallization |
| 2023-02-28 | sol-000m-topological-wars | Topological Wars | P2 Crystallization |
| 2023-03-14 | sol-000i-dantes-show-business | Dante's Show Business | P2 Crystallization |
| 2023-03-20 | sol-000h-miranda-warning | Miranda Warning | P2 Crystallization |
| 2023-04-03 | sol-011-ai-risk-chess | AI Risk: An Historical Perspective Through Chess | P2 Crystallization |
| 2023-04-05 | sol-012-ai-incarnation | The Mystery of AI Incarnation | P2 Crystallization |
| 2023-04-13 | sol-010-social-media-topology | Social Media Topology | P2 Crystallization |
| 2023-04-19 | sol-000k-simulation-game | The Simulation Game | P2 Crystallization |
| 2023-05-07 | sol-042-dark-dorian | Dark Dorian | P2 Crystallization |
| 2023-05-10 | sol-010h-maps-and-meaning | Maps and Meaning — A Topological Perspective | P2 Crystallization |
| 2023-06-17 | sol-010b-social-media-landscape-continued | The Social Media Landscape — Continued | P2 Crystallization |
| 2023-08-03 | sol-011c-great-conflaxion | The Great Conflaxion | P2 Crystallization |
| 2023-08-09 | sol-005-on-evil | On Evil in a Digital Age | P2 Crystallization |
| 2023-09-01 | sol-013d-return-of-disablers | The Return of the Disablers | P2 Crystallization |
| 2023-09-21 | sol-003-distributed-gulag | The Distributed Gulag | P2 Crystallization |
| 2023-09-26 | sol-011b-version-of-the-law | The Version of the Law | P2 Crystallization |
| 2023-09-28 | sol-009-relativity-truth | Relativity, Truth and Social Media | P2 Crystallization |
| 2023-10-05 | sol-013c-dermatophobia | Dermatophobia | P2 Crystallization |
| 2023-10-25 | sol-013b-denycracy | Denycracy | P2 Crystallization |
| 2023-11-20 | sol-015b-mobius-strip | Progress on the Möbius Strip | P2 Crystallization |
| 2023-11-24 | sol-054b-powers-that-be-digital-society | The Powers that Be in a Digital Society | P2 Crystallization |
| 2024-01-16 | sol-024i-sophies-other-choice | Sophie's Other Choice | P3 Maturation |
| 2024-02-09 | sol-024g-bullet-time | Bullet Time | P3 Maturation |
| 2024-04-04 | sol-024d-close-but-no-cigar | Close, but no Cigar | P3 Maturation |
| 2024-04-27 | sol-024b-waiting-for-godot | Waiting for Godot | P3 Maturation |
| 2024-05-27 | sol-024c-harvey-make-a-dent | Harvey Make a Dent | P3 Maturation |
| 2024-08-04 | sol-013-homeopathogenesis | Homeopathogenesis | P3 Maturation |
| 2024-08-23 | sol-024h-topological-revolution-goes-mental | Topological Revolution Goes Mental | P3 Maturation |
| 2024-10-17 | sol-006-percolation | Percolation — A New Model for Disruption | P3 Maturation |
| 2024-10-22 | sol-052-separation-of-powers | On the Separation of Powers, Stability and All That | P3 Maturation |
| 2024-11-19 | sol-024e-dhl-and-social-media | DHL and Social Media | P3 Maturation |
| 2024-12-06 | sol-026-final-frontier | The Final Frontier | P3 Maturation |
| 2024-12-19 | sol-024f-airoscopes | AIroscopes | P3 Maturation |
| 2025-02-03 | sol-025-pale-glider | Pale Glider | P4 System-building |
| 2025-02-24 | sol-045-flat-checking | Flat Checking | P4 System-building |
| 2025-03-06 | sol-046-sheep-of-theseus | The Sheep of Theseus | P4 System-building |
| 2025-03-23 | sol-035-welfare-state-endgame | Welfare State Endgame | P4 System-building |
| 2025-04-10 | sol-050-imaginary-borders | Imaginary Borders | P4 System-building |
| 2025-04-16 | sol-027-orbital-strike-systems | Orbital Strike Systems | P4 System-building |
| 2025-05-06 | sol-028-news-from-frontlines | News from the Front Lines | P4 System-building |
| 2025-05-21 | sol-015-social-matryoshka | Social Matryoshka | P4 System-building |
| 2025-05-29 | sol-030-sesame-two-way-street | Sesame Two-Way Street | P4 System-building |
| 2025-06-06 | sol-022-adiabatic-politics | Adiabatic Politics | P4 System-building |
| 2025-06-17 | sol-014-quantization-of-war | The Quantization of War | P4 System-building |
| 2025-07-08 | sol-049-human2vec | Human2Vec | P4 System-building |
| 2025-08-20 | sol-029-brave1-rubikon | Brave1 Has Crossed the Rubicon | P4 System-building |
| 2025-08-30 | sol-017-onlyhumans | OnlyHumans | P4 System-building |
| 2025-09-15 | sol-032-kirk-transform | The Kirk Transform | P4 System-building |
| 2025-09-30 | sol-016-filth-element | The Filth Element | P4 System-building |
| 2025-10-15 | sol-048-choice-and-necessity | Choice and Necessity | P4 System-building |
| 2025-10-20 | sol-047-great-simulation | The Great Simulation | P4 System-building |
| 2025-11-06 | sol-020-ff0000-tape | The FF0000 Tape | P5 Chronicle |
| 2025-11-26 | sol-036-disposable-stories | Disposable Stories | P5 Chronicle |
| 2025-12-01 | sol-019-digital-vanishing-point | The Digital Vanishing Point | P5 Chronicle |
| 2025-12-09 | sol-018-winged-lion | Winged Lion, Slayed Dragon | P5 Chronicle |
| 2025-12-18 | sol-037-4-weeks-later | 4 Weeks Later | P5 Chronicle |
| 2025-12-20 | sol-021-nation-state-divorce | The Nation-State Divorce | P5 Chronicle |
| 2026-01-12 | sol-038-palasseuss-and-odymedes | Palasseuss and Odymedes | P5 Chronicle |
| 2026-01-22 | sol-039-hyperpresent-omnicause | Hyperpresent and the Omnicause | P5 Chronicle |
| 2026-01-28 | sol-040-discombobulator-media | Discombobulator Media | P5 Chronicle |
| 2026-02-04 | sol-041-orbital-telegraph-road | Orbital Telegraph Road | P5 Chronicle |
| 2026-02-13 | sol-031-patching-the-sacred | Patching the Sacred — from Hippocrates | P5 Chronicle |
| 2026-02-18 | sol-034-second-law-metaphysics | The Second Law of Metaphysics | P5 Chronicle |
| 2026-02-22 | sol-051-predictions-first-batch | Predictions — First Batch | P5 Chronicle |
| 2026-02-23 | sol-033-katechon | Katechon, Acceleration and All That | P5 Chronicle |
| 2026-03-09 | sol-043-babel-timeline | The Babel Timeline | P5 Chronicle |
| 2026-03-14 | sol-044-athestia | Athestia | P5 Chronicle |
| 2026-03-17 | sol-054-omniconvergence | Omniconvergence | P5 Chronicle |
| 2026-03-25 | sol-023-what-you-get | What You Get and What You See | P5 Chronicle |
| 2026-03-27 | sol-024-treadmill-to-heathens | The Treadmill to Heathens | P5 Chronicle |
| 2026-03-31 | sol-053-game-of-domes | Game of Domes | P5 Chronicle |
| 2026-04-04 | sol-055-all-quiet-on-the-moat-front | All Quiet on the Moat Front | P5 Chronicle |
| 2026-04-09 | sol-056-one-reality-legion-reasons | One Reality, Legion Reasons | P5 Chronicle |
| 2026-04-15 | sol-057-fantasia-covfefe | Fantasia Covfefe | P5 Chronicle |
| 2026-04-19 | sol-058-speaker-of-the-house | Speaker of the House | P5 Chronicle |
| 2026-04-21 | sol-059-peak-blinders | Peak Blinders | P5 Chronicle |
| 2026-04-23 | sol-060-discord-ravers | Discord Ravers | P5 Chronicle |
| 2026-04-24 | sol-061-a-maze-inc | A Maze Inc. | P5 Chronicle |
| 2026-04-29 | sol-062-butterfly-affect | The Butterfly Affect | P5 Chronicle |
| 2026-05-05 | sol-063-closure-and-leisure | Closure and Leisure | P6 Open Set |
| 2026-05-07 | sol-064-flattening-cones | Flattening Cones | P6 Open Set |
| 2026-05-09 | sol-065-it-story | IT Story | P6 Open Set |
| 2026-05-16 | sol-066-doppelganger | Doppelgänger | P6 Open Set |
| 2026-05-21 | sol-067-the-rummaging-area | The Rummaging Area | P6 Open Set |
| 2026-05-28 | sol-068-the-draft-for-the-drift | The Draft for the Drift | P6 Open Set |
| 2026-05-30 | sol-069-the-distributed-krakens-have-been | The Distributed Krakens have been released | P6 Open Set |
| 2026-06-02 | sol-070-e-mithridatism | e-Mithridatism | P6 Open Set |
| 2026-06-06 | sol-071-tell-homer | Tell Homer | P6 Open Set |
| 2026-06-09 | sol-072-predictions-second-batch-and-review | Predictions - Second Batch and Review | P6 Open Set |
| 2026-06-10 | sol-073-pandoras-parabox | Pandora's Parabox | P6 Open Set |
| 2026-06-15 | sol-074-the-dream-of-a-dream | The Dream of a Dream | P6 Open Set |
| 2026-06-20 | sol-075-stone-soup | Stone Soup | P6 Open Set |
| 2026-06-26 | sol-076-only-fans | Only Fans | P6 Open Set |
| 2026-07-12 | sol-077-aesops-reels | Aesop's Reels | P6 Open Set |
| 2026-07-14 | sol-078-bureaucrat-calculus-its-syntax-and | Bureaucrat Calculus: Its Syntax and Semantics | P6 Open Set |
| 2026-07-23 | sol-079-con-census | Con Census | P6 Open Set |
| 2026-07-26 | sol-080-the-way-after | The Way After | P6 Open Set |
| 2026-08-02 | sol-081-the-ongoing-polymorphic-coup | The Ongoing Polymorphic Coup | P6 Open Set |
| 2026-08-10 | sol-082-echoes | Echoes | P6 Open Set |
| 2026-08-21 | sol-083-hidden-ledger-crouching-lagrange | Hidden Ledger, Crouching Lagrange | P6 Open Set |
| 2026-08-28 | sol-084-jason-quixote | Jason Quixote | P6 Open Set |
| 2026-08-31 | sol-085-under-the-shadow-of-soros | Under the Shadow of Soros | P6 Open Set |
| 2026-09-12 | sol-086-ai-anima-and-intelligence | AI - Anima & Intelligence | P6 Open Set |
| 2026-09-18 | sol-087-super-intelligence-from-first-principles | Super Intelligence from First Principles | P6 Open Set |
| 2026-09-19 | sol-088-ardnassak | Ardnassak | P6 Open Set |
| 2026-09-21 | sol-089-predictions-third-batch-and-review | Predictions - Third Batch and Review | P6 Open Set |
| 2026-09-23 | sol-090-weapons-of-mass-production | Weapons of Mass Production | P6 Open Set |
| 2026-09-28 | sol-091-willkommen-strangers | Willkommen, Strangers | P6 Open Set |
| 2026-10-02 | sol-092-sad-meridians | Sad Meridians | P6 Open Set |
| 2026-10-05 | sol-093-the-battlenetwork-of-the-present | The Battlenetwork of the Present | P6 Open Set |
| 2026-10-08 | sol-094-377-reasons-why | 377 Reasons Why | P6 Open Set |
| 2026-10-09 | sol-095-broken-filters | Broken Filters | P6 Open Set |
| 2026-10-12 | sol-096-frogs-personal-stories | Frogs Personal Stories | P6 Open Set |
| 2026-10-17 | sol-097-angkor-was | Angkor Was | P6 Open Set |
| 2026-10-20 | sol-098-naming-animals | Naming Animals | P6 Open Set |
| 2026-10-22 | sol-099-the-social-kaleidoscope | The Social Kaleidoscope | P6 Open Set |

</content>
</document>
