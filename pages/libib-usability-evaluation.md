---
layout: page
title: Library App Usability Evaluation
permalink: /research/libib-usability-evaluation/
---

<article class="research-case">
  <header class="research-case-header mb-5">
    <p class="small text-uppercase text-muted font-weight-bold mb-2">Applied Research · Usability Evaluation</p>
    <h1 class="mb-3">Library App Usability Evaluation</h1>
    <p class="lead mb-4">An expert cognitive walkthrough of Libib designed to uncover usability problems that routine cataloging tasks might miss.</p>
    <dl class="row research-meta mb-4">
      <dt class="col-sm-3">Product</dt><dd class="col-sm-9">Libib mobile app</dd>
      <dt class="col-sm-3">Project</dt><dd class="col-sm-9">Graduate usability research project</dd>
      <dt class="col-sm-3">Role</dt><dd class="col-sm-9">Sole evaluator</dd>
      <dt class="col-sm-3">Methods</dt><dd class="col-sm-9">Expert cognitive walkthrough, task analysis, and Nielsen's usability heuristics</dd>
    </dl>
  </header>

  <section class="research-section">
    <h2>Context and challenge</h2>
    <p>Libib is a cataloging app for building personal collections of books, movies, music, and video games, primarily by scanning barcodes. At the time of this study, the app was generally well reviewed, but a series of recent one-star reviews described severe login friction after a software update. As a Libib user cataloging my own mixed-media collection, I had encountered several of the same problems.</p>
  </section>

  <section class="research-section research-contribution">
    <h2>My contribution</h2>
    <p>For a graduate usability research project supervised by Christopher Lueg, I independently designed and conducted a complete expert cognitive walkthrough of the mobile app.</p>
    <ul>
      <li>I selected 16 deliberately difficult catalog items to expose edge cases.</li>
      <li>I designed eight realistic tasks covering collection creation, scanning, search, editing, and duplicate management.</li>
      <li>I completed each task as an expert user and documented every interaction breakdown.</li>
      <li>I evaluated the breakdowns using Nielsen's ten usability heuristics.</li>
      <li>I translated the findings into a specific design recommendation for each problem.</li>
    </ul>
  </section>

  <section class="research-section">
    <h2>Evaluation approach</h2>
    <p>Straightforward items can make a cataloging workflow appear more usable than it is. I therefore built the walkthrough around books in foreign languages, films with multiple released versions, and duplicate books in different physical conditions. These cases tested whether the app could support the ambiguity and variation found in a real personal library.</p>
    <p>I organized those items into eight tasks: creating libraries, scanning items, searching, updating records, and managing duplicate copies. For every breakdown, I recorded where the interaction failed and connected the problem to a specific usability principle rather than relying on an unsupported impression.</p>
  </section>

  <section class="research-section">
    <h2>Four critical usability breakdowns</h2>
    <div class="research-finding"><h3>New items were difficult to locate</h3><p>The default alphabetical sort buried recently added items instead of surfacing them by recency. The interface had also removed the back-arrow pattern used elsewhere in the app, creating consistency problems.</p></div>
    <div class="research-finding"><h3>The primary action required unnecessary effort</h3><p>Adding an item—the more frequent action—required more taps than creating an entirely new collection, even though collection creation occupied the most prominent position on the home screen.</p></div>
    <div class="research-finding"><h3>A removed setting made repeated entry slower</h3><p>An update had removed the ability to lock a collection to one media type. Users now had to choose the media type for every item, turning a previously one-tap workflow into repeated work.</p></div>
    <div class="research-finding"><h3>Duplicate copies could not be distinguished</h3><p>The app recorded a quantity but offered no way to distinguish a hardcover from a softcover copy—and did not explain that this editing capability was available only on the desktop website.</p></div>
  </section>

  <section class="research-section">
    <h2>Recommendations</h2>
    <p>I recommended defaulting to a recency-based view or visually flagging new items, moving the add-item action to the primary button, restoring per-collection media-type locking, and adding an in-app path to the web-based copy editor until equivalent editing became available natively.</p>
  </section>

  <section class="research-section">
    <h2>Methodological limitation</h2>
    <p>This evaluation involved one expert rather than several independent evaluators. A single evaluator inevitably has blind spots, so the findings should be understood as a focused expert assessment rather than a comprehensive inventory of every usability problem. Making that boundary explicit was important: the method supported actionable diagnosis, but it did not justify overstating what one walkthrough could prove.</p>
  </section>

  <section class="research-section">
    <h2>What I carried forward</h2>
    <p>This was where I first learned to conduct a usability evaluation end to end: designing tasks difficult enough to uncover meaningful problems, walking through them systematically as an expert, and grounding every recommendation in a clear, citable usability principle rather than a gut feeling.</p>
  </section>
</article>
