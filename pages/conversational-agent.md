---
layout: page
title: Conversational Agent
permalink: /research/conversational-agent/
---

<article class="research-case">
  <header class="research-case-header mb-5">
    <p class="small text-uppercase text-muted font-weight-bold mb-2">
      Academic Research · Journal Article
    </p>
    <h1 class="mb-3">
      Like My Aunt Dorothy: Effects of Conversational Styles on Perceptions,
      Acceptance and Metaphorical Descriptions of Voice Assistants during
      Later Adulthood
    </h1>
    <p class="lead mb-4">
      How does a voice assistant's conversational style shape the way
      middle-aged and older adults perceive it, describe it, and decide
      whether to keep using it?
    </p>

    <dl class="row research-meta mb-4">
      <dt class="col-sm-3">Publication</dt>
      <dd class="col-sm-9">Proceedings of the ACM on Human-Computer Interaction, CSCW 2024</dd>

      <dt class="col-sm-3">Study</dt>
      <dd class="col-sm-9">2 × 2 Wizard-of-Oz experiment · N = 58 · Ages 50–80</dd>

      <dt class="col-sm-3">My role</dt>
      <dd class="col-sm-9">Quantitative analysis and collaborative qualitative coding</dd>

      <dt class="col-sm-3">Methods</dt>
      <dd class="col-sm-9">Correlation, ANOVA, MANOVA, linear regression, and metaphor coding</dd>
    </dl>

    <a class="btn btn-outline-primary" href="https://doi.org/10.1145/3637365">
      View publication
    </a>
  </header>

  <section class="research-section">
    <h2>Research question and why it matters</h2>
    <p>
      Most voice assistants use a single conversational style, even though
      the people interacting with them differ in age, personality, and social
      expectations. Research on conversational style has also tended to focus
      on younger adults. This study asked whether a seemingly small design
      choice—formal versus informal language—changes how people in later
      adulthood perceive a voice assistant, whether they want to continue
      using it, and the metaphors they use to make sense of it.
    </p>
  </section>

  <section class="research-section">
    <h2>Study at a glance</h2>
    <p>
      The research team created RAVA, a Wizard-of-Oz voice assistant, and
      conducted the study in a simulated home environment. Thirty-four
      middle-aged adults (ages 50–64) and 24 older adults (ages 65–80)
      interacted with either a formal or informal version of the same script.
      The content, voice, and speech engine remained constant so the study
      could isolate conversational style.
    </p>
    <p>
      Participants completed measures of personality, perceived intelligence,
      trust, likeability, and technology acceptance. In a semi-structured
      interview, they also answered the prompt “RAVA is like a…?” to reveal
      the mental models they formed after the interaction.
    </p>
  </section>

  <section class="research-section research-contribution">
    <h2>My contribution</h2>
    <p>
      I joined the project after data collection was complete. My role focused
      on turning the survey and interview data into interpretable results.
    </p>
    <ul>
      <li>
        I conducted quantitative analyses in R—including correlation, ANOVA,
        MANOVA, and linear regression—to examine how age, personality, and
        conversational style shaped perceived intelligence, trust,
        likeability, and technology acceptance.
      </li>
      <li>
        I worked with a co-author to develop and apply a coding scheme for
        participants' metaphorical descriptions, classifying the agency,
        autonomy, and animacy they attributed to the assistant.
      </li>
    </ul>
    <p class="small text-muted mb-0">
      The original study design and the multilevel modeling used for the
      paper's metaphor findings were led by my co-authors.
    </p>
  </section>

  <section class="research-section">
    <h2>Key findings</h2>
    <div class="research-finding">
      <h3>Age and personality shaped perceived likeability</h3>
      <p>
        Older adults with higher agreeableness rated the assistant as more
        likeable than middle-aged adults did. Conversational style alone did
        not significantly change likeability.
      </p>
    </div>
    <div class="research-finding">
      <h3>Informality increased older adults' intention to continue use</h3>
      <p>
        Middle-aged adults responded similarly to the formal and informal
        assistants. Older adults—especially those lower in agreeableness—were
        more willing to continue using the informal assistant.
      </p>
    </div>
    <div class="research-finding">
      <h3>Tone changed the social role people assigned to the same system</h3>
      <p>
        Older adults described the formal assistant through professional roles,
        such as a librarian or teacher. The informal assistant prompted
        comparisons to close relationships—a sibling, spouse, friend, or, in
        one participant's words, “my aunt Dorothy.”
      </p>
    </div>
  </section>

  <section class="research-section">
    <h2>Design implications</h2>
    <p>
      “Older adults” should not be treated as a single user type. Their
      preferences varied with both conversational style and personality. For
      conversational UX, this points toward adaptable interaction styles rather
      than a universal voice persona. Metaphors can also give researchers a
      practical way to surface users' mental models, expectations, and concerns
      about an AI system—including intimacy, authority, autonomy, and privacy.
    </p>
  </section>

  <section class="research-section">
    <h2>What I carried forward</h2>
    <p>
      The technology-acceptance result I analyzed was important, but the
      metaphor finding stayed with me: a shift in tone could move the same AI,
      in someone's mind, from a tool to a member of the family. It sharpened
      the question that now guides my research—whether an AI feels genuinely
      understanding may depend not only on what it can do, but also on how it
      is designed to relate to people. This is especially consequential for
      people whose needs are often designed around rather than designed for,
      including children, older adults, and other cognitively vulnerable
      populations.
    </p>
  </section>

  <footer class="research-citation mt-5 pt-4 border-top">
    <h2 class="h5">Publication</h2>
    <p>
      Chin, J., Desai, S., Lin, S., &amp; Mejía, S. (2024). Like My Aunt
      Dorothy: Effects of Conversational Styles on Perceptions, Acceptance and
      Metaphorical Descriptions of Voice Assistants during Later Adulthood.
      <em>Proceedings of the ACM on Human-Computer Interaction, 8</em>(CSCW1),
      Article 88.
    </p>
  </footer>
</article>
