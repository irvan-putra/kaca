---
layout: default
permalink: /
title: Kaca
---
<section class="hero">
  <p class="eyebrow">Rapi · research notes</p>
  <h1>See the evidence clearly.</h1>
  <p class="lede">Kaca is a reading site for five research notes on Indonesian banking, economic measurement, and research design. Each note keeps its sources, verification labels, and open questions visible.</p>
  <p class="callout">These are research notes, not a live data service or investment advice. Some sections are proposals or include figures that remain unverified. Read each note's status and scope before relying on its claims.</p>
</section>
<section id="notes" aria-labelledby="notes-heading">
  <h2 id="notes-heading">Five research notes</h2>
  <ul class="note-list">
  {% for note in site.data.notes %}
    <li class="note-card">
      <span class="pill">Research note</span>
      <h3><a href="{{ note.path | relative_url }}">{{ note.title | escape }}</a></h3>
      <p>{{ note.summary | escape }}</p>
      <p class="card-status"><strong>Status:</strong> {{ note.status | escape }}</p>
    </li>
  {% endfor %}
  </ul>
</section>
<section class="scope" aria-labelledby="scope-heading">
  <h2 id="scope-heading">Sources and limits</h2>
  <p>The five notes are reproduced from the English research files in <a href="https://github.com/irvan-putra/kaji">Kaji</a>, as they stood in the <a href="https://github.com/irvan-putra/kaji/commit/c6798eea79001db880f75415c2d0017e3183dbb2">17 November 2026 source snapshot</a>. Source links and per-section caveats are in each note. External facts can change; check the linked primary sources before relying on time-sensitive claims.</p>
  <p>No underlying spreadsheet, chart image, private inputs, or unreproduced data are added here. The notes say what was and was not checked.</p>
</section>
