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
<section class="scope" aria-labelledby="proposal-heading">
  <h2 id="proposal-heading">Additional public-safe proposal</h2>
  <p><a href="{{ '/research-plan/' | relative_url }}">Research plan: Measuring the Economy from Below</a> is a separately labeled 15-slide public-safe adaptation, not a field report. It has editable PowerPoint and PDF downloads; the source version remains private.</p>
</section>
<section class="scope" aria-labelledby="scope-heading">
  <h2 id="scope-heading">Sources and limits</h2>
  <p>The five notes are reproduced from the English research files in <a href="https://github.com/irvan-putra/kaji">Kaji</a>, as they stood in the <a href="https://github.com/irvan-putra/kaji/commit/c6798eea79001db880f75415c2d0017e3183dbb2">17 November 2026 source snapshot</a>. Source links and per-section caveats are in each note. External facts can change; check the linked primary sources before relying on time-sensitive claims.</p>
  <p>The bank-count and independent-economy notes now include nine supplied Rapi visuals with captions and full-size links. The bank-count note also links the supplied public-source ledger, with its mixed-date and extraction caveats. The images retain Rapi branding; two historical charts have only their personal header removed. Their reuse license and public-domain status were not verified, and no license is asserted. Values and research limits remain stated beside the figures. The private input deck is not included.</p>
</section>
