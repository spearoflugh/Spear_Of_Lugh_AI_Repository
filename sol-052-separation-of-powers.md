<document>

<metadata>
  <doc_id>sol-052</doc_id>
  <title>On the Separation of Powers, Stability and All That</title>
  <date>2024-10-22</date>
  <cluster>Institutional Diagnosis</cluster>
  <type>Synthetic_Framework</type>
  <source_url>https://spearoflugh.substack.com/p/on-the-separation-of-powers-stability</source_url>
  <corpus>spear-of-lugh</corpus>
  <content_status>Verbatim text from the author's Substack export (2026-11-06). Song lyrics and longer copyrighted literary quotations are replaced by bracketed placeholders.</content_status>

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
  <fact_check version="V16" checked="2026-11-10">
    <item status="CHECKED">Date checked against the Substack export (published 2024-10-22); content block replaced by the verbatim post text.</item>
  </fact_check>
</metadata>

<content>

# On the Separation of Powers, Stability and All That

The focus of this Substack experiment is to study the implications of the new information technologies on  culture and society. After a few years a sort of vision has started to crystalize in my mind. It is kind of weird/unexpected. Also it is clearly not finished, and writing about it is a part of organizing those thoughts.  For the moment they appear to look more like dreams than a formal system/philosophy.

My initial investigating directions were: “What could be the kind of institutions fit for a digital culture?” And more broadly “What would ‘living’ might look like in such a society?”

As it is a pretty large subject, I am going to start with a synthetic description of the most fundamental points. “Why those points?”, “How those points articulate with one another?”, and “What does it mean in practical terms” will be addressed subsequently. I will also make a lot of self citation in this post to show where all this comes from: a many years long meditation on how the world is transforming under the impact of information technologies.

This post is full of self citations, they are used to show how I gradually came to the conclusions that I am discussing here. One of my underlying thesis being that we are in the midst of a shift akin to the one of moving from oral culture to written culture.

### Fundamentals

Here follows four fundamental points that I have identified. In my opinion they will be major inflexion points in the transformation from a written culture into a digital culture.

1. **The three orders**. New information technologies have blurred the distinction between ideas and objective reality. What was a theological controversy, the Trinity doctrine, has become an every day issue for laymen. This is why I think that there is a case to be made to reorganize society along three orders: 1. *Warriors*. Warriors have a direct impact on the world: they are the ones that turn ideas into reality. Ultimately war is a clash of wills. There is no war without will. Wars do not flow from the physical world. They are initiated in the domain of ideas and have an incarnation in the physical world. From a standard political point of view this is the executive branch of the government: how do you turn laws and regulations into a tangible reality? Police is used to enforce social peace and implement judiciary decisions. The sentences pronounced by  judges are just words. They have to be fleshed out (the mystery of incarnation). It is done through warriors. Elon Musk belongs to this category: his purpose in life is to transform ideas and aspirations into concrete technologies. In the Ancient Régime it was : “Le Rouge” -the Red- as the symbolic color of the army, the aristocracy. Think Alexandre the Great, Napoleon.
2. *Priests*. The Priests are the one who build ideas from what happens in the objective world. They are the ones that interpret reality and turn physical manifestations into ideas. They assign significance to material phenomenons (death, birth, wedding). The judiciary branch of the government is the political manifestation of this tier. The job of the judge is to build “judicial truth” from events. Priests, Rabbis or Muftis are religious expressions: they are interpreting life within a moral/religious framework. In the Ancien Régime it was: “Le Noir” -the Black- as the dress of catholic priests. Many podcasters belong to this tier. Think Joe Rogan, the Weinsteins brothers, Jordan Peterson: something like the intellectual dark web. They are very much included into the society and are talking about what is happening and what it means.
3. *Merchants*.  The Merchants make the world go round. From peasants to plumbers, mechanics, delivery guys passing by cable technicians, they are the ones literally bringing food on the table, and the table itself. This is the tier that never stopped to work during the COVID crisis. They are the ones acting in the physical world. In the Ancien Régime it was: “le Tiers état” -literally *what’s left-*Meaning what’s left after having removed the two previous tiers (called orders). They were not identified as tier traditionally because they had no way to express themselves, they were busy working. Maybe the Marxist lumpenproletariat. New information technologies change this tier a lot: it has access to communication and coordination without having to go by middle men. Just like buyers/sellers through Amazon. Think “Gilets Jaunes” riots in France.Messages
2. **Stability**. Until very recently a lot of political issues were constrained by the real world. It meant also that many political problems were solved “by default”. Words and swords were syncrhonized. A striking example is how french “départements” (administrative subdivision of the french state) were defined under Napoleon's ruling: it is the set of places that can be reached from the “chef-lieu” (main city) with less than a  1-day horse ride. Now that a tweet can be read instantaneously at the other part of the globe, we see that the “horse ride” condition makes little sense. The decorrelation between speech and locality has tremendous influences on the political landascape: an event that occurs on the other side of the earth has immediate implications hic et nunc. On the reality front the same thing is happening: it has become very easy to move from one point of the globe to the other one. “Around the world in eighty days” has turned into being able to reach almost any area in less than 24 hour using economy flight. The migration crisis is a reflect of that. Moving from Europe to America took weeks. When europeans moved towards America there was no going back in sight.  They were all-in. Today’s migrants can change their mind, go back home for hollidays etc.  Those have deep implications on social life: the Free-rider problem has taken a new dimension. A third dimension in which new information technologies have a destabilizing role in society: legacy.
3. **Distributed system of powers that be**. “The powers that be” emerge from the collaboration of different entities. For instance, is not true that the three letters agencies directly give an order to social media platforms: they rather suggest or give hints on what to do. The relation is less asymmetric. Big corp provides new services and are granted special rights (or rather no one is going to bother them on some points in exchange of the collaboration) in exchange. In this sense the powers that be act more and more like a distributed systems. Distributed systems work with protocols : those are rules that have to be observed for the system to work correctly. It departs from a software/computer view in which the program is explicit and has to obey a specific syntax. Protocols are open and closer to voluntary participation. Think at the http (hyper text transfrer protocol) over which the whole internet has been developped. My claim is that protocols will replace the editorial function of written culture.
4. **Material world has to catch up**. At a quick glance, making everything virtual only presents upside. You are no longer limited by geographical constraints and the use of ideas is marginally free. You can reuse the same idea (copying a file doesn't destroy it) as much as required without having to face new costs (e.g. unlike printing a new copy of a book that is a very materialist enterprise). Moreover, copies are perfect (there is no notion of original version anymore), the copies don't age etc. Even the limits of the physical world seems to vanish: if I record my voice and post it on Tik Tok, it becomes instantly available around the globe. I could go on like this for screens but I think that you get the idea. The flip side is that we are still humans and humans are not just ideas. We are our ideas, but we are also our bodies. Science made huge progresses on the virtual front during the last 4 decades, much less progresses have been made in the material front. We seem to have reach a point where this unbalance is starting to show: recent AI progresses are so dependant on energy that you can feel this push towards more material oriented progress. Recent news that Three Miles Island reactors are going to be restarted for powering data center is just the start of a very heavy trend. The material world is about to strike back.

### And now what ?

A legitimate question would be: suppose that the preceeding points are directionally correct, in what are they helpful? My further claim is that having those points in mind is important in order to have clear directions in our heads while we are on the brink of radical change. The first section was about the first O of the OODA loop: Observe. Here I am tackling with the second O: Orient.  I am going to explore here some implications that can be drawn from the perspective presented in the previous section.

1. **Separation of powers becoming balancing of orders**. A direct implication of the fact that powers that be now work as a distributed is that the traditionnal checks and balances between the legislative, excutive and judicial branches, as well as traditional constitutional protections are no longer effective. The most basic scheme is the one of 5-eyes  : basically three letters agencies can get around consitutional limitations by exchanging favors. Something like: we have no rights to spy on our own citizens, but we will spy on citizen of other countries and exchange those records with partners (excerpt from wikipedia): ```
However, in recent years, FVEY documents have shown that member agencies are intentionally spying on one another's private citizens and sharing the collected information with each other.[11][91] Shami Chakrabarti, director of the advocacy group Liberty, claimed that the FVEY alliance increases the ability of member states to "subcontract their dirty work" to each other.[92]
``` The issue underlined here is the gradual irrelevance of a fundamental concept in law. The idea that geographical constraints are primary in the choice of law to apply. On the internet there are no frontiers and the distinction between a citizen and a foreigner are not fundamental. This is why constitutional constraints might rather have to do with the structure of society, the orders, rather than its geographical extension. In other words the concept of Nation-State based on who control the land has to be rethought, because the world of ideas has no clear borders and has gained into significance.
2. **Citizenship rethought: vertical vs horizontal.**Citizenship has always been a function of space: where you were born, and maybe from which family, was the main parameter. Moving around was the exception. It has become the rule. It means that citizenship must integrate the time parameter. Just being born somewhere, or acquiring *legal* citizenship does not entail that you are going to invest in an area on a multi generational scale. But cities, countries develop over long period of times. Much longer than human lives. Sorry you cannot be “citizen of the world”. It doesn’t mean that the world has to close down and to forbid the physical mobility of humans. Quite the contrary. But you can only be a political actor in a place where you have more than skin in the game: lineage in the game. Of course it seems impossible to predict what your desdence is going to do. They may move to places where life is better. It must not be encouraged and made easy. You have to be all-in. The point is to mitigate the free rider issue. It can be done positively by rewarding the ones who commit to a particular area. Property laws, voting laws (who has the right to vote for what questions) are levers that can be used. It is a tricky issue because human rights and civic rights were bond together at the inception. They are related but distinct in my opinion. Subsidiarity cannot function properly without a stable foundation. As always a balance has to be found to avoid the calcification of society. At the moment of writing we are way too open to mobility, in every acception of the term: intellectual, geographical, societal. Things change too fast to adapt.
3. **Protocols rather than laws and regulations.**There is a fundamental difference between programs and protocols. Programs are explicit as well as the machines over which they are executed. On the other hand protocols are implitict in the sense that they are not written in a single program. The protocol is how the programs are going to react to one another when run in parallel. Most of the time you even have no idea of how many programs are running: think at the http protocol that is used to exchange informations. The overall result is what we call “the internet”. There is not a clear picture of what “the internet” is because it changes at every second: new servers are set up, others go down or become unreachable etc. Yet “the internet” is a thing, it exists even if it is impossible to pin down what (in material terms) it is. You can’t isolate the servers of Google and say that it is the internet, even if they were going down the internet would still be here. In societal term it translates into the following: more and more activities are now distributed systems. In pre-digital era the state apparatus was organized as a computer running a program: it was able to internally achieve its proclaimed goals (exerting power on a given piece of land). Nowadays the state aparatus can no longer do it alone: it has to rely on FAANG to just know what is going on, let alone have a say on how things are done on the virtual reality front. So governmental agencies are setting up distributed system of powers. In order to limit their reach static rules are not going to work. Indeed, one particularity of distributed system is their robustness and adptability. Think again at the use of 5-eyes alliance. The question becomes : how can limits be imposed to such distributed public/private partnerships ? I have no definitive answers, my intuition would be that static negative rules shall be replaced by positive open protocols (setting up standards). The general idea is to promote ways for people for being able to cooperate rather than focusing forbidding people from doing bad things. By this I don’t mean that laws like “murder is forbidden” should be erased. I am rather thinking at the ever expanding body of regulations about anything and everyhting in particular.
4. **Robustness rather than consistency**. One of the few theoretical results in distributed is the famous CAP theorem. The idea is that you can have at best two but not three of the following properties for a distributed data store : 1. Consitency (every part of the system sees the same value for each variable) 2. Availability (every request must result into a response) and 3. Partition tolerance (the system continues to work even experiencing network disruptions). The problem of consitency is called “misinformation”. The calls to deal with misinformation relies on the idea that there would be a mechanism allowing the truth to be known, or to be revealed (from where ?), without any error. It is a false belief of course, but focusing on dealing with this issue means that you are going to loose either A or P. Which is a shame because we already have a protocol to deal with the progressive discovery of truth: free speech. It is another instance that shows that the editorial function that was paramount in a written culture has to give way to cooperation. The objective of institutions has to shift towards cooperation and move away from censoreship. This is particularly well illustrated but the 2024 US presidential campaing. A picture is worth thousand words, look how complacency media is dying by focusing on being the editors of “the truth”:

I am wrapping it up here, but will follow to post on this heavily in the months to come. Please react if you have comments, thoughts about the subject.

</content>

</document>
