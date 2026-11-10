<document>

<metadata>
  <doc_id>sol-102</doc_id>
  <title>Baryonic Trust</title>
  <date>2026-11-04</date>
  <cluster>Phase 6 — Trust Architecture / Constructive</cluster>
  <type>Essay (proposal)</type>
  <source_url>https://spearoflugh.substack.com/p/baryonic-trust</source_url>
  <corpus>spear-of-lugh</corpus>
  <content_status>Verbatim text from the author's Substack export (2026-11-06). Song lyrics and longer copyrighted literary quotations are replaced by bracketed placeholders.</content_status>
  <added_in>V16</added_in>

  <relations>
    <prerequisite>sol-101</prerequisite>
    <prerequisite>sol-000n</prerequisite>
    <related_to>sol-000j</related_to>
    <related_to>sol-023</related_to>
    <related_to>sol-031</related_to>
    <related_to>sol-049</related_to>
    <related_to>sol-083</related_to>
  </relations>

  <key_concepts>
    <concept name="The Signature in a Digital Society">
      Pasting a picture of a handwritten signature is absurd (copy/paste is anonymous), yet signing remains a cornerstone of trust. Writing leaves a material imprint; digital permanence differs (RAM, discs lasting decades vs the Code of Hammurabi lasting millennia; format obsolescence). The pixel-signature "cannot last because it makes no real sense".
    </concept>
    <concept name="Public Commitment and Inverted Permanence">
      Signing is a public, social commitment (even on a desert island one signs for future readers). Click-through licence/cookie boxes are better than pseudo-signatures but unsatisfactory. With AI able to fake any recording, everything is recorded yet nothing digital can be trusted at face value — the inverse of a signature (unforgeable and deliberate). Unforgeability came from social friction (Trump's Oval Office signing staging as cartoon version).
    </concept>
    <concept name="Three Requirements for a Digital Signature">
      (1) Proof of reality — an extended blockchain oracle problem (cf. sol-000n's social oracle problem); (2) Proof of intentionality — an unambiguous protocol proving intent; (3) Friction — signing must interrupt the normal course of events (clicking boxes is not acceptable).
    </concept>
    <concept name="Baryonic Keys">
      Purely digital solutions will fail because digital data behaves like ideas (perfect copies, no ageing; you cannot see a stolen copy). Trust must be made material again: "baryons" (protons, neutrons — the objective world) vs "leptons" (electrons in computers). A baryonic key (BK) is a physical object that cannot be simulated or digitally represented (Physically Unclonable Functions), gives repeatable results and reveals nothing about its structure — the digital equivalent of a royal seal on a ring that never leaves the monarch's hand. It provides proof of reality, intentionality and friction; it is not meant to live inside a smartphone. Paths exist at conceptual, societal and technical levels.
    </concept>
  </key_concepts>

  <new_terms>
    <term name="Baryonic Trust / Baryonic Key (BK)" status="coined_here">
      [SoL] Trust anchored in unclonable physical objects used in cryptographic protocols, providing proof of reality, proof of intentionality and friction. Developed from "The Baryons Strike Back" (Aug 2023, not in this repository).
    </term>
    <term name="Proof of Reality / Proof of Intentionality" status="coined_here">
      [SoL] Two of the three requirements (with friction) for any digital successor to the signature.
    </term>
  </new_terms>

  <anti_hallucination>
    <warning>"Baryon" is used loosely to denote the material world; the physics distinction (baryons vs leptons) is correct but the usage is metaphorical.</warning>
  </anti_hallucination>

  <fibralist_connection>
    <bridge_to_fibralist>fib-006 (Keel — material anchor of identity)</bridge_to_fibralist>
    <bridge_to_fibralist>fib-008 (Pax Fibris — protocol-level trust)</bridge_to_fibralist>
  </fibralist_connection>

  <context>
    Published 4 November 2026 — the most recent article in the corpus as of V16. Constructive conclusion of the trust trilogy (sol-083 → sol-101 → sol-102) and a direct echo of the corpus's earliest oracle-problem article (sol-000n).
  </context>

  <fact_check version="V16" checked="2026-11-10">
    <item status="CHECKED">Published 2026-11-04 (Substack export); real-world claims checked by web search on 2026-11-10. Statuses: VERIFIED / CORRECTION (author or metadata error) / UNVERIFIED / NOTE.</item>
    <item status="VERIFIED">Physically Unclonable Functions (PUFs) / physical one-way functions are an established research field (Pappu et al., 2002).</item>
    <item status="VERIFIED">The Code of Hammurabi stele dates to c. 1754 BCE (over 3,700 years).</item>
  </fact_check>
</metadata>

<content>

# Baryonic Trust

If there is one activity typical of written culture that looks strange in a digital culture, it is the signature. I have used pictures of my handwritten signature on God only knows how many documents. There is something ridiculous about that, since copy/paste is as anonymous as an activity could be. Yet signing remains a cornerstone of trust in our society. In this piece, I am interested in exploring the function of the signature in a digital society. I am not interested in technical implementations, and I am aware of cryptographic signature schemes, distributed ledgers, blockchains, etc. That is not my angle here. The raw question is: what function does the signature fulfill in society, and how could it be adapted?

### Public commitment

The fundamental feature of writing is that, unlike spoken words, it leaves a material imprint. The permanence of objects is contrasted with the volatility of vibrations. When a society digitizes, more and more aspects become virtual. It is true that computer memory is a material imprint, but functionally it differs from a sheet of paper in many ways. RAM is only active while the power is on. Even when recorded in a more permanent storage medium, digital permanence is not the same as that of paper. Take, for instance, the limited life expectancy of various kinds of discs, typically around a few decades, and compare it to the Code of Hammurabi, carved in stone, which has lasted more than three millennia. On top of that, the format of the content and the technological means to access it are issues that were non-existent for written documents. This means that a file containing the definition of the pixels representing my handwritten signature has almost nothing to do with what a signature actually is. Yet, because it looks like a signature, it is deemed satisfactory in many instances. This is a transitory situation that cannot last because it makes no real sense.

The act of signing is a public commitment: you commit to the fact that you are aware of and agree to certain terms. One can find a digital equivalent to this in the numerous clicks you have to perform regarding license agreements or cookie policies. Those invasive procedures are better than a pseudo-signature. At least one doesn’t role-play the “signature-that-looks-like-it-was-done-by-hand.” Yet, they clearly remain unsatisfactory. It is not a personal thing. Signing only makes sense in a social context. Indeed, even on a desert island, one would only sign a declaration in the hope that someone in the future would find the text and read it.

Now, add to the mix the fact that an AI can manipulate any video or audio record at will. You end up in a strange situation: on the one hand, everything that you do is recorded, and on the other hand, nothing that is digitally recorded can be trusted just by looking at it. As I have said, there are loads of cryptographic solutions, but that is not really my angle here. It is as if things have been turned upside down: your words have permanence (because someone recorded you with a smartphone and posted it on social media) and everything about you on the network could be a fake. This is the complete inverse of what a signature used to be: unforgeable and deliberate. Note that unforgeability does not stem from the impossibility of replicating the drawing, but rather from the social friction associated with signing. The whole staging around Trump’s signature of executive orders in the Oval Office is a cartoonish version—as is often the case with Trump—of this very point.

This discussion gives us three hints **as to** what a digital equivalent of **a** signature has to solve:

1. **Proof of reality.** This is an extended version of the blockchain oracle problem. Basically, one has to ensure that some parts of the virtual world are a sound representation of the objective world. In the case of blockchains, it amounts to the challenge of injecting reliable external data into decentralized systems without losing the property of decentralization.
2. **Proof of intentionality.** A signature is the materialization of an intent. As mentioned, many things are recorded or virtualized without consent or even knowledge. Yet once **it is** done, how can you tell? So the problem to solve is to have **an** unambiguous protocol allowing a proof of intent.
3. **Friction.** The act of signing is in itself a friction. The normal course of **events** is stopped to perform it. Therefore**,** clicking boxes is not an acceptable digital adaptation.

### Baryonic Trust

I don’t think a purely digital solution is ever going to work. In fact, what makes digital technology strong is also what makes it less trustworthy. Digital data behaves like an idea: it can be copied perfectly, doesn’t age, and so on. These properties are great because they allow you to scale (the marginal cost is zero), but on the other hand, you have no way of knowing when a secret has been stolen or used. It is not like a physical object: if someone steals your gold coin, you can see that it is no longer in the vault. But what if someone makes a copy of one of your files? Likewise, if a 0 in computer memory is identical to another 0 in another computer memory, how can you identify a specific 0? The original Mona Lisa is not the same as a copy, but it doesn’t work that way in the virtual world—any copy of Star Trek will do.

Thus we have to make trust material again. I already discussed some ideas around that in the following post:

[Linked post: The Baryons Strike Back]

I use the word baryon loosely as a root to denote the objective world (because protons and neutrons are baryons) by opposition to leptons (electrons that are circulating in computers are leptons). Incorporating material aspects into digital trust operations effectively addresses the three aforementioned points. Supposing that suitable baryonic key technologies are developed—refer to the post “The Baryon Strikes Back” for a definition and discussion of this concept—a helpful analogy for baryonic keys is to consider a key possessing the following property: a baryonic key (BK) can neither be simulated nor digitally represented due to its complexity. This is a field of research known as Physically Unclonable Functions (PUF) or Physically One-Way Functions. A BK allows for repeatable experimentation, where a given experiment consistently produces the same result. The object also demonstrates robust randomness properties; knowing the outcome of an experiment provides no advantage in revealing the object’s underlying structure or predicting the results of other experiments.

A BK can be conceptualized as the digital equivalent of a royal seal. Royal seals were historical mechanisms for authenticating letters, acting as a physical signature and an embodiment of royal authority. The seal was affixed to a ring that never left the monarch’s hand. Furthermore, applying the seal was inherently deliberate: sealing a document inadvertently was impossible. This concept encompasses three core principles: proof of reality (the BK must be physically engaged to generate a result), proof of intentionality (conducting the experiment cannot occur accidentally), and physical friction (executing the physical experiment inherently introduces friction). Ultimately, the BK is not intended to reside within a smartphone or any digital equipment; rather, it should be viewed as a unique, physical object used to execute a cryptographic protocol.

The point here is not to discuss the intricacies of specific cryptographic protocols based on shared randomness,  but rather to show that paths exist to renew the trust architecture in a digital society. It requires work at the conceptual level, at the societal level (building systems actually usable by everyone) and at the technical level (having working systems).

</content>

</document>
