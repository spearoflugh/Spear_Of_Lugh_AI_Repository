<document>

<metadata>
  <doc_id>sol-086</doc_id>
  <title>AI - Anima &amp; Intelligence</title>
  <date>2026-09-12</date>
  <cluster>Phase 6 — AI &amp; Mathematics Shock</cluster>
  <type>Essay</type>
  <source_url>https://spearoflugh.substack.com/p/ai-anima-and-intelligence</source_url>
  <corpus>spear-of-lugh</corpus>
  <content_status>Verbatim text from the author's Substack export (2026-11-06). Song lyrics and longer copyrighted literary quotations are replaced by bracketed placeholders.</content_status>
  <added_in>V16</added_in>

  <relations>
    <prerequisite>sol-011</prerequisite>
    <prerequisite>sol-012</prerequisite>
    <related_to>sol-047</related_to>
    <related_to>sol-053</related_to>
    <related_to>sol-061</related_to>
    <related_to>sol-087</related_to>
    <related_to>sol-088</related_to>
  </relations>

  <key_concepts>
    <concept name="New AI Moral Panic">
      Triggered within hours by OpenAI's claim to have solved a Millennium Prize problem (Navier–Stokes) and an ex-Anthropic employee's public "this time it's real, AI is going to kill us all" declaration (described by the author as astroturfed).
    </concept>
    <concept name="Artificial Anima vs Artificial Intelligence">
      Thesis: what people fear is not artificial intelligence but artificial anima (AA) — animation, life, drive. Presenting AI progress as progress in AA is a category error.
    </concept>
    <concept name="Agentic AI = LLM + 1990s Multi-Agent Systems">
      Agent-oriented programming (formalized in the 1990s: BDI model, autonomy/proactiveness, FIPA-ACL/KQML) lacked computing power and intelligence; LLMs added both plus a natural-language interface. Agents may look alive but "are as alive as an LLM alone is intelligent".
    </concept>
    <concept name="Pet Sematary — Life Simulated">
      Like the returning cat in Stephen King's novel, agents simulate life: no autopoiesis (they repair nothing), goals as synthetic shells (a hyperparameter can be edited; an ant's hunger cannot), and simulation is not reality ("a simulation of a hurricane isn't wet").
    </concept>
    <concept name="The Uncanny Shadow and the Rabbit in the Headlights">
      Conflating intelligence with anima disarms the public; there is no ghost in the machine, only responsible designers. AI companies talk about doom while driving the car; fear (as with COVID) is used to bend legislation — deep state vs deep tech.
    </concept>
  </key_concepts>

  <new_terms>
    <term name="Artificial Anima (AA)" status="coined_here">
      [SoL] The illusion of life, drive or soul attributed to AI systems, distinct from (and wrongly inferred from) intelligence.
    </term>
  </new_terms>

  <anti_hallucination>
    <warning>The author's claim that "an LLM's response time scales with the length of its prompt, not with the depth of the problem" is technically imprecise: generation time scales mainly with the number of output tokens, and reasoning models vary their compute with problem difficulty.</warning>
    <warning>"Astroturfed" is the author's characterization of the ex-Anthropic employee's statement.</warning>
  </anti_hallucination>

  <context>
    Published 12 September 2026. Opens the "AI &amp; Mathematics Shock" arc (sol-086 → sol-097). Consistent with the corpus's long-standing anti-doomer position (sol-011, sol-012).
  </context>

  <fact_check version="V16" checked="2026-11-10">
    <item status="CHECKED">Published 2026-09-12 (Substack export); real-world claims checked by web search on 2026-11-10. Statuses: VERIFIED / CORRECTION (author or metadata error) / UNVERIFIED / NOTE.</item>
    <item status="VERIFIED">OpenAI announced on 8 September 2026 a claimed solution of the Navier–Stokes existence-and-smoothness problem; the claim was disputed (credit dispute; not validated by the Clay Institute at time of writing).<source>https://www.datacamp.com/blog/openai-navier-stokes-math-problem</source></item>
    <item status="VERIFIED">BDI agents (Bratman 1987; Rao &amp; Georgeff 1990s), agent-oriented programming (Shoham, early 1990s), KQML and FIPA-ACL are accurate references.</item>
  </fact_check>
</metadata>

<content>

# AI - Anima & Intelligence

We just entered a new phase of the AI moral panic. This was sparked by a couple of events that unfolded in a matter of hours. The first one was the claim by OpenAI of the resolution of a Millennium Prize Problem, a list of very high end mathematical problems that stayed unsolved for decades or even centuries.

[Embedded X post]

It was shortly followed by an astroturfed social media declaration from an ex-Anthropic employee along the lines of “you don’t understand, this time it’s real, AI is going to kill us all”.

[Embedded X post]

I am not going to tackle the intricacies of both statements here, but there is a lot to say about them. In this piece, I am making a step back to clarify the discussion. My thesis is simple: what people are afraid of is not artificial intelligence, but artificial anima (AA). Moreover, progress in AI is presented as progress in AA, which is a category error.

### Agentic Animation

Agentic AI is all the rage right now. The idea is simple: LLMs are limited in a number of ways. The most glaring one is that an LLM doesn’t think. An LLM’s response time scales with the length of its prompt, not with the depth of the problem — a short question and a Millennium Prize Problem take the same time if both call for a one-paragraph answer.  A natural idea to circumvent this limitation is to use standard programs that can use LLMs as oracles. Those standard programs might inspect the solution and launch further investigations or use other resources, like data found on the internet, in order to know what to do next.

​Agent-oriented programming is not new, though. It was an idea formalized in the nineties that has sparked a lot of interest since the early 2000s. Multi-agent systems of that era lacked computing power and intelligence. LLMs brought intelligence and a natural language interface, which explains the success that we are witnessing today.

The key point of agentic programming were already defined more than a quarter of century ago. Namely:

- **BDI (Belief-Desire-Intention) Model**: Structuring agents based on their Beliefs (state of the world), Desires (goals to achieve), and Intentions (chosen action plans).
- **Autonomy and Proactiveness**: Unlike a simple OOP object that merely receives method calls, an agent reacts to its environment and takes initiatives to accomplish its goals.
- **Standardized Communication**: Development of FIPA-ACL and KQML languages, enabling agents to exchange structured messages (”request”, “inform”, “propose”).

When you hear about agentic AI, this is simply the cross over of both LLMs and multi agent-oriented programing. Superficially those system might give the impression of anima. Indeed agents may cooperate with one another giving rise to unexpected results and behavior. In facts agents are as alive as a LLM alone is intelligent. They might appear so at a first glance but a quick inspection reveals the fraud quite easily.

### Pet Sematary

One of the most disturbing S. King’s novel, which is saying something, is *Pet Sematary*. The plot is straightforward: a guy and his son move to a new house. Monday their cat dies. They burry it in an ancient Indian cemetery. Few days pass and the cat gets back home. It behaves a bit weird but it is alive. Then the son is killed by a truck while he was crossing the road. Of course the father goes to bury the child in the indian’s cemetery. The S. King’s readers may infer how things unfold from there.

Software agents that appears to simulate life because they are pieces of code that don’t primarily interact with the user. They interact with the environment: the network and other agents. While multi-agent systems capture the structural patterns of life, they lack its fundamental ontology. Let’s go through step by step and category by category.

- ​**Lack of Autopoiesis** : Biological entities continuously repair, maintain, and recreate their own physical boundaries using energy from their environment. A multi-agent network is an abstract graph of algorithms running on server hardware. Agents don’t repair anything.
- “**Goals” of agents Are Synthetic Shells**: An ant colony searches for food because individual ants die without calories. Agents in a MAS pursue goals solely because a hyperparameter or system prompt evaluates that state as optimal. Remove the loss function, and the agents have no intrinsic drive to do anything. You can change an hyper parameter by editing a file. It won’t work for the ant.
- **Simulation**: Multi-agent systems compute the math of interaction. A simulation of a hurricane isn’t wet, and a simulation of social swarm dynamics isn’t conscious.

I am stressing the last point. Reality is never completely understood. Models of the world are at best faithful but one can never be sure that they are complete. Believing that a simulation could replace real life is at best a leap of faith, but one that can be disproved very easily. And agents only have access to simulations. They know what they have been symbolically fed with.

### The uncanny shadow of the valley of death

The uncanny valley effect is that weird feeling you experience when looking at an AI product. It’s like the pet coming back from the cemetery: everything looks okay on the surface.

​Agents might actually prove dangerous and there may be something behind the current moral panic, but what is feared is missing the mark. Conflating intelligence with anima creates a primary risk: acting like a rabbit frozen in the headlights of an oncoming car. The mere belief that there is a ghost in the machine is disarming. There is no ghost, and there are clear responsible parties: the ones who designed the system. It is quite ironic to see OpenAI, Anthropic, Musk and co. talking about doom probabilities while they are driving the car. Their talk is to the public what the car’s headlights are to the rabbit. The difference being that in the case of the car, the aim of the headlights is not to hypnotize rabbits.

Most of the public has no deep knowledge of computer science, mathematics, or computability. The growing cargo cult behavior displayed around new information technologies—where no one knows how they really work—reaches a pinnacle with the fear of these latest technological advances. By playing on this lack of understanding, AI companies try to impose a narrative. Fear, as the COVID crisis showed, is the most powerful tool to manipulate crowds. To what end is the question. The first idea that comes to mind is to bend the legislative process to their liking. This is only the beginning. Deep state vs. deep tech is just getting started.

</content>

</document>
