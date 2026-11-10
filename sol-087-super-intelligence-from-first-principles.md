<document>

<metadata>
  <doc_id>sol-087</doc_id>
  <title>Super Intelligence from First Principles</title>
  <date>2026-09-18</date>
  <cluster>Phase 6 — AI &amp; Mathematics Shock</cluster>
  <type>Essay (technical argument)</type>
  <source_url>https://spearoflugh.substack.com/p/super-intelligence-from-first-principles</source_url>
  <corpus>spear-of-lugh</corpus>
  <content_status>Verbatim text from the author's Substack export (2026-11-06). Song lyrics and longer copyrighted literary quotations are replaced by bracketed placeholders.</content_status>
  <added_in>V16</added_in>

  <relations>
    <prerequisite>sol-011</prerequisite>
    <prerequisite>sol-086</prerequisite>
    <related_to>sol-000o</related_to>
    <related_to>sol-003</related_to>
    <related_to>sol-012</related_to>
    <related_to>sol-088</related_to>
  </relations>

  <key_concepts>
    <concept name="ASI as a Conversation-Stopper">
      "With ASI, whatever you say is invalid" functions as a magic card while the term stays vague. The author (whose hunch is that ASI is impossible, without proof) explores what superintelligence could mean from first principles.
    </concept>
    <concept name="Definition With a Caveat">
      Bostrom-style definition — above-human ability to solve general, new, complex problems — plus a caveat absent from Bostrom: "suppose the problem is solvable" (Gödel). An ASI is a Turing machine subject to computability limits: it cannot make 2+2=5.
    </concept>
    <concept name="Problem 1 — Two ASIs Beat One">
      Two distant superintelligences coordinating (e.g., via shared randomness) can act instantaneously on local knowledge where a single one would wait for light-speed signals; hence communication is constitutive of any worthwhile ASI.
    </concept>
    <concept name="Problem 2 — Chaos Cannot Be Tamed">
      The super-chess-player image assumes complete state knowledge; the world is chaotic (butterfly effect) and unmeasurable to arbitrary precision — no ASI can forecast weather weeks ahead (the author also invokes Heisenberg).
    </concept>
    <concept name="Problem 3 — Complexity Classes Don't Collapse">
      Bin packing (NP-complete), generalized chess (EXPTIME-complete): even if P = NP, intrinsically intractable problems remain. Combined, the three limits debunk most doomer talking points before energy and infrastructure issues; fear plays in AI risk the role greed plays in economics; the debate looks like a power grab, not good faith.
    </concept>
  </key_concepts>

  <new_terms>
    <term name="First-Principles ASI Limits" status="coined_here">
      [SoL] Three independent constraints on superintelligence — distribution/communication (light speed), chaos (measurement), computational complexity.
    </term>
  </new_terms>

  <anti_hallucination>
    <warning>These arguments update the corpus's 2023 anti-doomer case (sol-011 AI Risk Chess; sol-012 AI Incarnation).</warning>
  </anti_hallucination>

  <context>
    Published 18 September 2026. Technical core of the AI &amp; Mathematics Shock arc.
  </context>

  <fact_check version="V16" checked="2026-11-10">
    <item status="CHECKED">Published 2026-09-18 (Substack export); real-world claims checked by web search on 2026-11-10. Statuses: VERIFIED / CORRECTION (author or metadata error) / UNVERIFIED / NOTE.</item>
    <item status="VERIFIED">Generalized chess on an n×n board is EXPTIME-complete (Fraenkel &amp; Lichtenstein, 1981); bin packing (decision version) is NP-complete.</item>
    <item status="VERIFIED">Deterministic weather predictability is limited to roughly two weeks (Lorenz); quantum uncertainty is not the usual reason invoked, but the measurement-limit point stands.</item>
  </fact_check>
</metadata>

<content>

# Super Intelligence from First Principles

The new round of discussion around AI risks is boring and interesting. The interesting part is to see how the deep tech vs deep state war is unfolding. Clearly there are many moves made in order to grab power (or dually to forbid others from acquiring power). But in this piece, I am going to focus on the boring part. This is the stupid part of the conversation in which words are nonsensically used. Things like  “but you don’t understand, with Artificial SuperIntelligence (ASI) whatever you tell me is invalid because you are too stupid”. You have certainly seen thousands of exchanges of this nature. It is boring because A)lSI is used as a magic card shutting down the conversation. Yet what ASI means always remains vague.

Hence I am going to tackle here *what this concept could mean*. Note that I am not even discussing whether or not ASI is possible (I think it is not,  but I have no proof, this is just a hunch). I would like to explore here what SI could mean starting from first principles.

### Intelligences

​There is no definitive definition of intelligence. Just look at the fights around the relevance of the concept of IQ. Likewise, world chess champions were heralded as being representative of superintelligence... before computers routinely crushed them. So the very idea of what intelligence is is not really clear. Maybe the best definition would be akin to the definition of pornography: you know it when you see it. Now imagine that on top of this unclear definition you add a superlative  “Super”.

​In order to continue the investigation into this term, let’s settle on this definitional issue. Superintelligence would be an above-human-level intellectual capacity to solve complex (general meaning not limited to a specific domain, and new) problems. Something like: “consider a math problem that has remained unsolved for decades, and suppose the problem is solvable, then SI can solve it”. This is basically Bostrom’s definition, but note that I have put the caveat “and suppose that the problem is solvable”. This caveat is not in Bostrom’s definition. It is because there are unsolvable problems in math (see Gödel ‘s incompleteness theorem). This is important and shows that ASI is not magic. You can’t just wish reality, or provability, into existence. There are things that are impossibe. Be it for an SI or anything. Likewise, an ASI is a Turing machine. As such, it is subjected to the limits of computation and the established results of computability theory. This is not an opinion but an observation. Just like any object is subjected to gravity, an ASI, no matter how large the S, can’t make 2+2 equals 5.

### Problems

​As it is hard to conceptually define SI out of the blue, let’s get a picture of it by considering how it should behave (even if only in a thought experiment). I will ask questions and try to answer them

[Image caption: Cover of “Distributed Systems” by Van Steen]

> **​Problem 1:** *Are two ASIs stronger than a single ASI?*

The question is interesting because an ASI, if it is seen as a godlike capability, should not depend on other intelligences at first glance. If it is so strong, then it should foresaw every move of other entities like it is entertained in doomer’s speech where the ASI can fool humans on demand in order to dominate them.

The answer is clear though: two SIs are strictly stronger than a single one. Indeed, the two SIs could be situated in very far away parts of the universe. But they could coordinate, through standard distributed system’s techniques (for instance shared randomness so that they don't need to communicate and can rely on a pre-established plan). They could use their local knowledge to do things instantaneously that a single SI could not. Indeed, the single SI would have to wait for the information to reach it to simulate the two ASIs. To the best of our knowledge, the speed of light is a hard limit.

A direct consequence is that communication is part of an ASI. Indeed one may argue that ASI, unlike human intelligence which resides inside each person, is not necessarily linked to a single physical place.  Even though, what is established is that without communications you won’t have the best ASI that you could. Said differently the capacity to communicate between remote parts of the universe is a necessary part of any ASI that is worth of this acception.

[Image caption: Lorenz atractor looking butterfly shaped]

> **Problem 2**: can ASI tame chaos?

Another way that ASI is understood by the public is to imagine a super chess player. The ASI would be able to guess all the moves of the adversary and outplay all of its opponents using its practically infinite wit. There is a fallacy at the root of this conception of ASI. It is the illusion that an ASI could see the world as a chess player sees the chessboard: with complete and exact access to the state of the world. It turns out that the world is messy. This is more than a hand-waving remark. Many real-life phenomena are chaotic. The most obvious one is the weather. This is the well-known idea of the butterfly effect. An infinitesimally small variation can lead to completely different outcomes in chaotic systems. That is why even an ASI could not accurately forecast the weather two or three weeks from now, let alone for a whole season. This is because, whatever the tools used to sense the atmosphere, it is impossible to have a perfect representation of it. Note that, due to Heisenberg uncertainty principle, this is true even if you imagine an unbound ASI, because at the end of the day, it remains a machine and as such has to follow the laws of physics.

[Image caption: Complexity Zoo]

> **Problem 3**: can an ASI collapses complexity classes?

I am sorry to have to make this problem explicit for the computability-literate reader. The answer is of course: “**no it can’t”**. Indeed, an ASI remains a Turing machine. Note that this is a stronger limitation than the ones outlined by Problems 1 and 2. One could even change the value of c and make it infinite, and problem 3 would remain. That would also be the case even if the Heisenberg incertitude is in fact wrong (but before being afraid of ASI, one would first have to invent a new standard theory of physics).

Now, this problem is important because even simple optimization problems, like bin-packing, that is NP-Complete, are intractable. A critic could say that approximate solutions might be enough but problem 2 suggests otherwise. Likewise, even if P=NP —which is unlikely but let's assume for the moment— other problems are inherently intractable and out of reach of any conceivable ASI. For instance, chess is EXPTIME-complete. This problem is interesting because it is directly linked to the conversation: if you extend the chessboard, to keep the analogy of the ASI being an extraordinary chess player, then perfect play remains intractable.

### Temporary Conclusion

This brief, and preliminary, exploration of the concept of ASI is already enough to debunk most of the senseless talking points of doomers,  or at least recenter the conversation on things that are not total fantasies. I have presented three independent categories of problems that would limit the magical ability of an ASI to wipe out humanity. Those points are interact with one another in a way that their combination makes the ASI ‘s task harder: the ASI would have to solve computationally intractable problems for which inputs cannot be known through simulations because of the chaotic nature of the world. Moreover, the ASI would have to be physically widespread in order to circumvent the finite speed at which information moves around. There are certainly many more issues, but only these three should be answered by a doomer before moving on further in the discussion of regulating the world against the threat of AI under the guise of unsubstantiated fear (even in principle, as I have done here, without even touching on practical issues linked to energy, the whole infrastructure that would be required, etc.) fear.

But fear is its own collateral. As a realist, I know that my piece won’t be seriously discussed. Just take another body of knowledge:  economics. It has been very common to see people in mainstream media explaining very seriously that 2+2=5 for decades. They appear to be impermeable to reality checks. It seems that fear, in the AI risk discussion, plays the role of greed in the realm of economics.

The conclusion is that the current discussion is essentially a mirage. It seems rather to be a power grab, but this subject — who does what to what end— is complex and slippery. The only thing that is clear beyond reasonable doubt is that this conversation is not being held in good faith.

</content>

</document>
