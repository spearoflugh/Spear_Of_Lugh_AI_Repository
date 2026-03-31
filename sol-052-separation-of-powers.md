<document>

<metadata>
  <doc_id>sol-052</doc_id>
  <title>On the Separation of Powers, Stability and All That</title>
  <date>2024-10</date>
  <cluster>Institutional Diagnosis</cluster>
  <type>Synthetic_Framework</type>
  <source_url>https://spearoflugh.substack.com/p/on-the-separation-of-powers-stability</source_url>
  <corpus>spear-of-lugh</corpus>

  <relations>
    <prerequisite>sol-002</prerequisite>
    <prerequisite>sol-003</prerequisite>
    <prerequisite>sol-004</prerequisite>
    <prerequisite>sol-021</prerequisite>
    <prerequisite>sol-000l</prerequisite>
    <prerequisite>sol-024g</prerequisite>
    <related_to>sol-008</related_to>
    <related_to>sol-025</related_to>
    <related_to>sol-026</related_to>
    <related_to>sol-035</related_to>
    <related_to>sol-049</related_to>
    <related_to>sol-051</related_to>
  </relations>

  <key_concepts>
    <concept name="Three Orders — Warriors, Priests, Merchants">
      A reorganization of society around three functional orders derived from the
      pre-digital Ancien Régime but reinterpreted for digital culture:
      (1) Warriors — those who incarnate ideas into physical reality (executive function,
      force application, Elon Musk transforming vision into technology; red = Ancien Régime
      aristocracy);
      (2) Priests — those who build ideas from physical reality, assign significance,
      interpret (judicial function, podcasters, intellectual dark web, Jordan Peterson;
      black = catholic clergy);
      (3) Merchants — those who make the world go round in the material layer (Tiers État,
      delivery workers, plumbers, gilets jaunes; historically voiceless, now able to
      coordinate via social media without middlemen).
      The thesis: the three-way separation of executive/legislative/judicial (Montesquieu)
      maps poorly onto digital culture; the Orders framework maps more faithfully to actual
      power distribution. The incarnation mystery: words (Warrior) must be made flesh — this
      is why force is always ultimately necessary (sentences without execution = words without
      reality).
    </concept>
    <concept name="CAP Theorem Applied to Governance — Robustness over Consistency">
      The CAP theorem (you cannot have simultaneously Consistency + Availability +
      Partition tolerance in a distributed data store) applied to information governance.
      The "misinformation" problem is a Consistency demand: the belief that a central
      mechanism can ensure all nodes see the same truth. This is a false belief — focusing
      on Consistency means sacrificing A or P. We already have the right protocol for
      progressive truth-discovery: free speech. The editorial function of written culture
      (Consistency enforcement) must give way to cooperation (Availability + Partition
      tolerance). Institutions should shift from censorship to enabling cooperation.
    </concept>
    <concept name="Protocols Replacing Laws and Regulations">
      The distinction from sol-021 (Program vs Protocol) applied to governance:
      programs (laws, regulations) require precise syntax and centralized enforcement;
      protocols (http, Bitcoin, email) work because nodes voluntarily follow shared
      conventions. The state apparatus can no longer operate as a program alone — it must
      rely on FAANG to know what is happening. So government agencies are setting up
      distributed public/private partnerships. Static negative rules (blacklists) cannot
      govern these; positive open protocols (standards) can. The goal: enable cooperation
      rather than forbid wrongdoing across an ever-expanding regulatory surface.
    </concept>
    <concept name="Citizenship Rethought — Vertical (Lineage) vs Horizontal (Mobility)">
      The free-rider problem in citizenship: modern mobility means you can extract value
      from a place without committing to it multi-generationally. "You cannot be citizen
      of the world." Citizenship requires lineage in the game, not just skin in the game —
      the willingness to have descendants in a place. Human rights and civic rights are
      related but distinct: universal human rights attach to persons; civic rights (voting,
      property) require demonstrated long-term commitment. The Fibralist bridge: subsidiarity
      cannot function without stable foundations; current moment is too open to mobility
      "in every sense: intellectual, geographical, societal."
    </concept>
  </key_concepts>

  <anti_hallucination>
    <warning>This article (October 2024) is the corpus's most systematic attempt at a constructive framework — it is the bridge between the diagnostic corpus and the Fibralist Corner. The author explicitly states "it is clearly not finished, and writing about it is a part of organizing those thoughts."</warning>
    <warning>The Three Orders (Warriors/Priests/Merchants) is the author's own adaptation of the Ancien Régime's three estates (Clergy/Nobility/Tiers État) combined with the modern executive/judicial/commercial structure. It is not a reference to any existing sociological typology.</warning>
    <warning>The CAP theorem (Consistency-Availability-Partition tolerance) is a real theorem in distributed computing (Brewer, 2000). The application to political governance is the author's own framework.</warning>
    <warning>The Three Mile Island / Microsoft data center reference is a real announcement (September 2024). It is used to illustrate the "material world striking back" — energy demand forcing return to physical infrastructure.</warning>
    <warning>The Five Eyes observation (spy on allies' citizens and exchange) is accurately described and sourced from Wikipedia's Five Eyes article. It is used as an illustration of distributed governance bypassing constitutional constraints, not as a novel revelation.</warning>
  </anti_hallucination>

  <fibralist_connection>
    <bridge_to_fibralist>
      This article is the most direct bridge to The Fibralist Corner in the entire corpus:
      fib-002 (Warriors/Priests/Merchants as the Three Orders of a Fiber society);
      fib-004 (topological citizenship with lineage-in-the-game);
      fib-008 (Pax Fibris as the protocol layer replacing interstate law);
      fib-009 (covenant as the positive protocol that replaces negative regulation).
      sol-052 is where the SoL diagnostic corpus explicitly reaches toward the Fibralist
      constructive response.
    </bridge_to_fibralist>
  </fibralist_connection>
</metadata>

<content>
The focus of this Substack experiment is to study the implications of the new information technologies on culture and society. After a few years a sort of vision has started to crystallize in my mind. It is kind of weird/unexpected. Also it is clearly not finished, and writing about it is a part of organizing those thoughts. For the moment they appear to look more like dreams than a formal system/philosophy.

My initial investigating directions were: "What could be the kind of institutions fit for a digital culture?" And more broadly "What would 'living' look like in such a society?"

This post is full of self-citations, used to show how I gradually came to the conclusions that I am discussing here. One of my underlying theses being that we are in the midst of a shift akin to the one of moving from oral culture to written culture.

## Fundamentals

Here follows four fundamental points that I have identified. In my opinion they will be major inflection points in the transformation from a written culture into a digital culture.

**1. The three orders.** New information technologies have blurred the distinction between ideas and objective reality. This is why I think that there is a case to be made to reorganize society along three orders:

*Warriors.* Warriors have a direct impact on the world: they are the ones that turn ideas into reality. Ultimately war is a clash of wills. There is no war without will. Wars do not flow from the physical world. They are initiated in the domain of ideas and have an incarnation in the physical world. From a standard political point of view this is the executive branch: how do you turn laws and regulations into a tangible reality? Police enforce social peace and implement judiciary decisions. The sentences pronounced by judges are just words. They have to be fleshed out — the mystery of incarnation. It is done through warriors. Elon Musk belongs to this category: his purpose in life is to transform ideas and aspirations into concrete technologies. In the Ancien Régime it was: "Le Rouge" — the symbolic color of the army, the aristocracy.

*Priests.* The Priests are the ones who build ideas from what happens in the objective world. They interpret reality and turn physical manifestations into ideas. They assign significance to material phenomena (death, birth, wedding). The judiciary branch of the government is the political manifestation of this tier. Priests, Rabbis or Muftis are religious expressions: they interpret life within a moral/religious framework. In the Ancien Régime it was: "Le Noir" — the dress of Catholic priests. Many podcasters belong to this tier: Joe Rogan, the Weinstein brothers, Jordan Peterson — something like the intellectual dark web.

*Merchants.* The Merchants make the world go round. From peasants to plumbers, mechanics, delivery workers, they are literally bringing food on the table, and the table itself. This is the tier that never stopped to work during the COVID crisis. In the Ancien Régime it was: "le Tiers état" — literally *what's left* after having removed the two previous tiers. New information technologies change this tier a lot: it has access to communication and coordination without having to go by middlemen. Think "Gilets Jaunes" riots in France.

**2. Stability.** Until very recently a lot of political issues were constrained by the real world. Words and swords were synchronized. A striking example is how French "départements" were defined under Napoleon: the set of places that can be reached from the main city with less than a 1-day horse ride. Now that a tweet can be read instantaneously across the globe, the "horse ride" condition makes little sense. The decorrelation between speech and locality has tremendous influences on the political landscape. Moving from Europe to America took weeks — when Europeans moved there was no going back. Today's migrants can change their mind, go back home for holidays. The free-rider problem has taken a new dimension.

**3. Distributed system of powers that be.** "The powers that be" emerge from the collaboration of different entities. It is not true that three-letter agencies directly give orders to social media platforms: they rather suggest or give hints on what to do. The relation is less asymmetric. Big tech provides new services and is granted special rights in exchange for collaboration. In this sense the powers that be act more and more like a distributed system. Distributed systems work with protocols: rules that have to be observed for the system to work correctly. It departs from a software view in which the program is explicit. Protocols are open and closer to voluntary participation. Think at http over which the whole internet has been developed. My claim is that protocols will replace the editorial function of written culture.

**4. Material world has to catch up.** Making everything virtual presents many upsides. You are no longer limited by geographical constraints and the use of ideas is marginally free. But we are still humans and humans are not just ideas. We are also our bodies. Science made huge progresses on the virtual front during the last 4 decades, much less on the material front. Recent AI progresses are so dependent on energy that you can feel this push towards more material-oriented progress — Three Mile Island reactors restarted to power data centers is just the start of a very heavy trend.

## And now what?

**1. Separation of powers becoming balancing of orders.** A direct implication of the distributed powers that be is that traditional checks and balances between legislative, executive and judicial branches are no longer effective. The most basic scheme is the Five Eyes: agencies can get around constitutional limitations by exchanging favors across borders — "subcontracting dirty work." The concept of Nation-State based on who controls the land has to be rethought, because the world of ideas has no clear borders.

**2. Citizenship rethought: vertical vs horizontal.** Citizenship has always been a function of space: where you were born. Moving around was the exception; it has become the rule. It means that citizenship must integrate the time parameter. You can only be a political actor in a place where you have more than skin in the game: lineage in the game. You cannot be "citizen of the world." It doesn't mean the world has to close down. But you have to be all-in. The point is to mitigate the free-rider issue. Property laws and voting laws are levers that can be used. Subsidiarity cannot function properly without a stable foundation.

**3. Protocols rather than laws and regulations.** There is a fundamental difference between programs and protocols. Programs are explicit and require precise syntax. Protocols are implicit — they are how programs react to one another when run in parallel. The overall result of http is "the internet" — you can't pin down what it is in material terms. In societal terms: more and more activities are distributed systems. The state apparatus can no longer operate as a program alone — it has to rely on FAANG to know what is going on. Governmental agencies are setting up distributed systems of power. Static negative rules will not work to govern these. Positive open protocols (setting standards) should replace them. The general idea: promote ways for people to cooperate rather than forbid bad things.

**4. Robustness rather than consistency.** The CAP theorem: you can have at best two of the three — Consistency (every part of the system sees the same value), Availability (every request results in a response), Partition tolerance (system works despite network disruptions). The "misinformation" problem is a false demand for Consistency. Focusing on it means losing A or P. We already have a protocol to deal with progressive discovery of truth: free speech. The objective of institutions must shift towards cooperation and away from censorship.
</content>

</document>
