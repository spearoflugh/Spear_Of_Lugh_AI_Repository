<document>

<metadata>
  <doc_id>sol-024h</doc_id>
  <title>Topological Revolution Goes Mental</title>
  <date>2024-08</date>
  <cluster>AI and Technology</cluster>
  <type>Theoretical_Extension</type>
  <source_url>https://spearoflugh.substack.com/p/topological-revolution-goes-mental</source_url>
  <corpus>spear-of-lugh</corpus>

  <relations>
    <prerequisite>sol-002</prerequisite>
    <prerequisite>sol-000h</prerequisite>
    <related_to>sol-010</related_to>
    <related_to>sol-019</related_to>
    <related_to>sol-039</related_to>
    <related_to>sol-042</related_to>
    <related_to>sol-049</related_to>
  </relations>

  <key_concepts>
    <concept name="Second Topological Revolution — Mental Space">
      The first Topological Revolution (sol-002) changed what is "near" in social space —
      geographical proximity replaced by informational/narrative proximity. Generative AI
      produces a second topological revolution: in mental/semantic space. Word embedding
      (Word2Vec, transformers) represents words and concepts as vectors in high-dimensional
      space where semantic neighbors are geometrically near. "Coke" and "Pepsi" are close
      vectors; questions in English or French about sodas land in the same neighborhood.
      This second topology is potentially more destabilizing than the first: the first
      changed how we relate to each other; the second changes how concepts relate to each
      other — the internal topology of thought itself.
    </concept>
    <concept name="Morphing as Statistical Average — MJ to GPT">
      The Michael Jackson "Black or White" morphing effect (1991) is the technical seed of
      generative AI image production: both are computed averages (interpolations) between
      vectors. The MJ morphing interpolates between pixel arrays; GPT interpolates between
      word/concept vectors. The insight: what appeared as magical creative production is,
      at the mathematical level, the computation of many averages. "An average fourth-grader
      with a calculator and enough time can do it." This demystification has a direct
      consequence: AI outputs are, by construction, average — they cannot produce what is
      outside the distribution of their training data (the outlier, the genius, the Schindler).
    </concept>
    <concept name="AI as Zeitgeist Explorer — Archetypes of the Time">
      When a generative AI trained on social media (Grok on X) produces output in response
      to a prompt, it produces the archetypes of the current moment — "a visual representation
      of the zeitgeist." This is not a bug but a feature of the architecture: the model is
      a high-dimensional map of the training corpus's conceptual space. Prompting it is like
      taking a random walk through that map. "It is not surprising that it gets the temperature
      of the air, it is built this way." AI is not conscious, not creative in the strong sense,
      but it is an extraordinary new "scope" (sol-000d Scopes Taxonomy) — a new instrument
      through which society can observe its own collective conceptual space in real time.
    </concept>
  </key_concepts>

  <anti_hallucination>
    <warning>This article (August 2024) provides the most technically accurate description of word embedding in the corpus. Word2Vec (2013, Mikolov et al.) and transformers (2017, "Attention Is All You Need") are real technical architectures correctly described at a conceptual level.</warning>
    <warning>"Second Topological Revolution" in mental space is the author's own coinage — it extends the Topological Revolution (sol-002) framework to semantic space. It is not a reference to any existing academic term.</warning>
    <warning>The MJ "Black or White" morphing example is historically accurate: the 1991 music video was among the first high-profile uses of morphing technology in popular media. The technical description (interpolation between pixel arrays) is approximately correct.</warning>
    <warning>The Grok "Darkhorse podcast" image example references a real generative AI experiment the author conducted. The specific image described is real output from Grok; the interpretation is the author's.</warning>
    <warning>The claim that AI is "not conscious" is the author's position consistently held throughout the corpus (sol-011, sol-012, sol-047) — not a claim to established scientific consensus.</warning>
  </anti_hallucination>

  <fibralist_connection>
    <bridge_to_fibralist>fib-006 (Keel as non-average identity: the Fiber's cultural identity is precisely what cannot be represented as a vector average — it is the outlier that the semantic topology cannot capture because it is not in the training distribution of the current era)</bridge_to_fibralist>
  </fibralist_connection>
</metadata>

<content>
New information technologies are generating a cultural revolution. As we are living through it, it is hard to discern its features. One of them is the change in what we consider *close to us*. This transformation of the notion of neighborhood comes from the fact that instantaneous global communication abilities have more or less erased natural obstacles. Anyone can directly talk, even have a video call, to anyone on earth. I called this the *Topological Revolution*.

Generative AIs are at the origin of another topological revolution: in the mental space. This other topological revolution might be even more destabilizing than the topological revolution in the acquaintance space.

## Morphing

When the clip of M. Jackson — *Black or White* — was published, it was at the pinnacle of what technology could deliver. The morphing between images, changing characters between sexes and races, was using top ranked computers to be produced. At the time I was just starting to study computer science. I remember having been shocked to see how simple it was in my first courses on image processing. A friend of mine even wrote a morphing program in an afternoon. It was not as smooth as in the M. Jackson clip but you could see that it was just an issue of raw computing power.

For your computer an image is just a large array of integers. Each pixel is colored using three integers that give the values in red/green/blue. The morphing displayed in M. Jackson's video clip is obtained by computing intermediate images in which you compute the interpolation — a kind of average — between the values for each pixel in the original image and the corresponding pixel in the target image. The more intermediate images you can compute the smoother the morphing. There are a lot of pixels in an image, so it requires a lot of computing power. But conceptually it doesn't go much further than computing *a lot* of averages. An average fourth grader with a calculator and enough time can do it.

Believe it or not, it is more or less the same thing that generative AIs are doing. The engine that makes GPTs work is called "word embedding." The idea is to represent words and sentences as vectors in a very large dimensional space. If you craft a *good* embedding then the words "Coke" and "Pepsi" will be very close to one another in this space. A program looking for something to drink can easily search in the *neighborhood* of those vectors. Likewise the fact that you ask the question in English or French is not relevant: the embedding is about semantics not syntax. All sodas rest in the same area of the semantic space. The secret is to build this embedding correctly and to have enough computing power to do it. You can move from one idea (one vector) to another idea (another vector) by interpolating between the vectors. The result will be a morphing between the two ideas. Just like in the M. Jackson clip, but at the semantic level.

## Archetypes

There is another dimension on which AIs operate: they learn by ingesting material created by humans. Grok feeds on Twitter — it is closer to "what people think" than models built on news articles which go through the editorial filter. What does it mean in concrete terms?

When you send a prompt to generate a text, a picture or a video, the generative AI uses its learning material and its vector representation to produce the result. You can see AI-generated images moving from one another — just like in the M. Jackson clip, but the evolution is a random walk through the model's representation space. Now when you send a prompt to an AI that is sensing the pulse of the conversation, what you get are the archetypes of our times. A visual representation of the zeitgeist.

This is my answer to the question "is AI conscious?": no it is not, but it is a very good explorer of the spirit of our times. It is not surprising that it gets the temperature of the air — it is built this way. It doesn't stop me from admiring the results. Moreover it adds a new "scope" for society to observe itself. What is going to emerge from the use of this new introspective tool is anyone's guess at this point. The only thing we can be sure of is that it is going to be both impossible to forecast and impossible to dodge.
</content>

</document>
