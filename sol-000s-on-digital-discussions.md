<document>

<metadata>
  <doc_id>sol-000s</doc_id>
  <title>On Digital Discussions</title>
  <date>2021-05-01</date>
  <cluster>Foundational Theory</cluster>
  <type>Pre_Foundational_Technical</type>
  <source_url>https://spearoflugh.substack.com/p/on-digital-discussions</source_url>
  <corpus>spear-of-lugh</corpus>
  <content_status>Verbatim text from the author's Substack export (2026-11-06). Song lyrics and longer copyrighted literary quotations are replaced by bracketed placeholders.</content_status>

  <relations>
    <related_to>sol-003</related_to>
    <related_to>sol-021</related_to>
    <related_to>sol-024e</related_to>
    <related_to>sol-036</related_to>
    <related_to>sol-052</related_to>
    <precursor_to>sol-052</precursor_to>
  </relations>

  <key_concepts>
    <concept name="Protocol vs Implementation — Applied to Discussion Architecture">
      The article applies the Program vs Protocol distinction (later formalized in sol-021)
      to the specific problem of digital discussion design. Written in the context of the
      Lamfada project (an attempt at a decentralized social media protocol), it asks whether
      discussion structure should be at the protocol level (like TCP/IP headers) or the
      implementation level (like an email client's "Re:" threading). Key observation:
      SMTP handles identity and message text but not conversation structure — threading
      emerged as a practice on top of the protocol, not inside it. The author's position:
      publication should be protocol-level; discussion structure and moderation should be
      implementation-level, left to communities rather than encoded into the base layer.
      This distinction prefigures the sol-021 (Program vs Protocol) argument and the
      sol-052 (Separation of Powers) proposal that protocols should replace laws precisely
      because laws are too rigid and moderation-like decisions require local adaptation.
    </concept>
    <concept name="The Asymmetric Fight — Good Faith vs Bad Faith Actors">
      A key structural observation: a few bad-faith actors (trolls) can derail conversations
      involving many more good-faith participants. The fight is asymmetric because the cost
      of destruction is far lower than the cost of construction. This asymmetry prefigures
      the Discombobulator (sol-040): the OODA loop destruction strategy works precisely
      because destruction is cheaper than coherent response. The proposed solution is
      shadow-banning (making bad-faith interventions invisible without removing them) rather
      than deletion (which creates martyrs and escalates). This is structurally equivalent
      to the corpus's later argument that deplatforming produces more noise than silence.
    </concept>
    <concept name="The Lamfada Project — Constructive Phase Before the Fibralist Corner">
      The article is written explicitly for the Lamfada project — an attempt at building
      a decentralized social media protocol in 2021, before the Fibralist Corner was
      formalized. This reveals that the diagnostic/constructive duality of the two
      repositories was present in embryo from the beginning: the author was simultaneously
      diagnosing digital culture (Spear of Lugh) and attempting to build alternatives
      (Lamfada). The Lamfada project appears to have been discontinued; its constructive
      impulse migrated into The Fibralist Corner. The article is therefore the earliest
      documented trace of the constructive thread that culminates in fib-002 through fib-009.
    </concept>
  </key_concepts>

  <quality_assessment>
    <rating>2/5 — Specialized Historical Document</rating>
    <justification>
      The article has limited standalone analytical value for a reader of the corpus.
      The Lamfada project context is opaque to anyone unfamiliar with it, and the technical
      protocol discussion is narrower than the corpus's usual scope. Its value is entirely
      archival: it documents that the author's constructive impulse (building alternatives)
      predates the Fibralist Corner by several years, and that the Program vs Protocol
      distinction was being thought through in 2021 before being formalized in sol-021.
    </justification>
    <limitation>
      The Lamfada project appears to have been discontinued with no follow-up in the corpus.
      The technical recommendations (backlinks, shadow-banning at protocol level vs
      implementation level) have not been developed further. This article is a historical
      dead-end in the corpus's trajectory rather than a live thread.
    </limitation>
  </quality_assessment>

  <corpus_impact>
    Modest analytical impact but significant autobiographical impact. Reveals the
    constructive intention co-existing with the diagnostic one from 2021 onward.
    The Lamfada project is the missing link between the Spear of Lugh diagnosis and
    the Fibralist Corner construction — they were not sequential but parallel from the start.
  </corpus_impact>

  <anti_hallucination>
    <warning>The Lamfada project (lamfada.com) was a real project of the author's, active circa 2021. Its current status is unclear — the forum link in the article may no longer be active. Do not present Lamfada as an ongoing project.</warning>
    <warning>The article references "the end has no end" — this is a link to another SoL article not in this corpus. It appears to discuss the open-endedness of digital conversations vs the natural endings of physical conversations.</warning>
    <warning>The Dreyfus Affair / J'Accuse reference is used as the historical pre-digital equivalent of public intellectual discourse — a debate conducted via newspaper that approximated what Twitter would later enable at scale.</warning>
  </anti_hallucination>

  <fibralist_connection>
    <bridge_to_fibralist>fib-004 (Fiber as protocol: the Lamfada question — should discussion structure be at the protocol or implementation level? — is answered in fib-004 where Fiber is designed as a human-scale protocol that includes community governance norms at the implementation layer, with only identity and publication at the protocol layer)</bridge_to_fibralist>
  </fibralist_connection>
  <fact_check version="V16" checked="2026-11-10">
    <item status="CHECKED">Date checked against the Substack export (published 2021-05-01); content block replaced by the verbatim post text.</item>
    <item status="CORRECTION">The previous content block was a short reconstruction (~2% of the text). Full verbatim text restored.</item>
    <item status="NOTE">"The End has no End" (9 March 2021) is revisited five years later in sol-063 (Closure and Leisure).</item>
  </fact_check>
</metadata>

<content>

# On digital discussions

The key features of social media communication are that, in addition to the message, it is paramount to know *who* published the message and *when* it was published. The “when” part is actually needed to provide context: your opinions may change as you are gathering more information.  The most direct way to address this is to put a timestamp on the publication. The timestamp is an “absolute” information, something like the number of seconds since 1970 or the “Unix Time”. But we all know that the context on which a statement is published can also be relative to a conversation: when you are discussing and idea with someone, or a group, the sheer succession of arguments is more important than the exact instant when it was made. It is especially true in our digital society: more and more discussions are held online asynchronously and not locally. The aim of this essay is to think out loud about some aspects of digital discussions.

[Image caption: The maieutic technology to discover truth]

I am writing this in the context of the Lamfada project. My concern is the following: are discussions an atomic part of social media? Shall there be something like a discussion, and if yes with what properties, at a protocol level? Or are discussions something that should be built on top of a publication protocol? If you take the raw SMTP protocol for instance there is nothing in it regarding how the conversation is conducted (what message is a reply to what message etc.). SMTP basically considers the identity of the sender, the identity of the recipient, and the text of the message.  Now, if you consider modern mail clients, they can organise messages as conversations using the “Re:” to sort out messages with relation to one another. It is a standard practice that emerged from the practice but that is not a part of the protocol itself.

---

When we think at the social media we do not only think at a set of publications but also at how those publications are related to one another. The links between publications can be person oriented (e.g. your friendship relations within the Facebook graph) or subject oriented (e.g. Twitter and the use of hashtags) or explicitly expressed within the publication itself (html links on a blog article for instance).  Those features are peculiar to digital conversations. Indeed, before the digital era, conversations were held live: the people participating to the conversation were present (and the conversation ended at some point). The closest thing approaching those kind of discussions were the very high level (in the sense that only a tiny elite was participating) discussions conducted through newspapers like the famous Dreyfus affair and “J’accuse” article of Emile Zola.

[Image caption: Social Media - XIX° edition]

Many solutions have been proposed in the digital era. From comments moderation of blog articles to retweet and muting/blocking of individuals. The scope of people allowed to intervene also: by default based on your friendship topology as in Facebook or wide open as in Twitter. A first problem appear because of the following clash of principles:

1. Every publication is eternal and not mutable.
2. You are the last ditch editor of your conversations.

At the end of the day, being the editor of your discussion means that you can delete publication which is in clear opposition to the principle that published content becomes like an idea. This editing is required because of bad faith actors that can make conversations impossible. It is actually a very asymmetrical fight: a few trolls may derail conversations involving many more good faith actors. The only solution seems to be something like “muting” those bad faith actors. You do not prevent them from posting (freedom of publication must prevail) but shadow ban them: make their interventions irrelevant. There are many ways to do this and it is not clear at the time of writing if there is a canonical one. That is why I think it should be left outside of the protocol layer.

I have roughly the same kind of arguments regarding how a conversation is structured: there are many ways to organize conversation and no way seem to be more fundamental than the other one. I am less convinced regarding this because reacting to a message is pretty clear and it is part of the social feedback that is paramount in social media. But it seems to be more at the level of best practice but it has to be facilitated at the protocol level. When you publish a content you should have tools to help you to know how it has been received, what are the reactions etc. Something like backlinks looks sensible. But how exactly (different kinds of backlinks? how do you indicate what reactions you think are not worthy etc.) will be the subject of further thinking.

Do not hesitate to join the Lamfada forum if you want to participate in the Lamfada project by  talking about this subject and others linked to the set up of a protocol for a decentralized social media.

</content>

</document>
