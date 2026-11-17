---
layout: default
permalink: /research/economy-measurement/
title: "Measuring the economy independently"
status: "Proposed design; examples not yet verified to primary sources"
source_url: "https://github.com/irvan-putra/kaji/blob/main/docs/mengukur-ekonomi-independen.md"
---

# Measuring the economy independently ("testing the numbers from below")

Research note. Sources accessed 17 November 2026; verification status is stated per section.

## The three-check framework

1. **Direct activity.** Form a fixed sample across regions and sectors; record businesses opening/closing, visitors, transactions, sales volume, and prices of the same goods; repeat monthly; separate price increases from volume increases. This is a measurement design, not yet run, and does not claim to represent all of Indonesia.
2. **Non-bank corporate earnings quality.** Read financial statements and their notes over five years; reconcile profit with operating cash flow (IAS 7 as the basis for reading cash flow); trace receivables, inventory, related-party transactions, and one-off gains; compute a value range with conservative assumptions rather than following the market price.
3. **Trade mirror.** Match Indonesia's exports against partner countries' imports per commodity, volume, value, and period; adjust for valuation differences (CIF vs FOB), recording lags, and goods routing before concluding manipulation exists. **Verified:** the official UN Comtrade page explains common causes of bilateral asymmetry: country attribution (origin vs last known destination), CIF vs FOB valuation, time lags, third countries, customs warehouses, classification differences, and trade-system differences. Source: <https://uncomtrade.org/docs/bilateral-asymmetries/>

Verification note: the IAS 7 link on ifrs.org was behind the IFRS Digital subscription when checked, so the document content at that link is unverified.

## Applied examples (not yet verified to primary sources)

### MDIY (PT Daya Intiguna Yasa Tbk, per KSEI), H1 2026 vs H1 2025

- Issuer identity verified: ticker MDIY is PT Daya Intiguna Yasa Tbk according to the KSEI share list. Source: <https://web.ksei.co.id/services/registered-securities/shares/lc/MDIY>
- Revenue +24.5%; transactions +23.3%; average transaction +0.92%; same-store sales -1.2%. Claimed source: H1 2026 financial statements, semester figures unaudited.
- Cash after capex and lease payments: -Rp168.9 billion (H1 2025); +Rp654.3 billion (H1 2026); +Rp681.6 billion (12 months to June 2026, calculated as FY2025 + H1 2026 - H1 2025). The first two lines cover six months, the third twelve months; they are not compared as growth. Claimed source: H1 2026 financial statements and Public Expose 2026.

### Indonesia-US trade, HS85 (electrical machinery and equipment), 2025

- Indonesia's exports (FOB): US$6.035 billion; US imports from Indonesia (FOB): US$7.848 billion; US imports (CIF): US$8.100 billion. The chart states the FOB-to-FOB difference as US$1.814 billion (30.1% of Indonesia's export record); subtracting the printed figures gives 1.813. Rounding of more precise source figures could be one explanation for this difference, but that is unverified. Claimed source: UN Comtrade API, reporter Indonesia (360) / US (842), HS85, 2025; US weights marked as estimates and not used.
- Methodological note on the chart: the difference requires examination of country attribution, recording time, and goods detail; a difference is not evidence of fraud by itself. Consistent with the UN Comtrade explanation above. The figures are *unverified* against UN Comtrade.

### Motor vehicles

- Domestic motorcycle distribution, Jan-Sep 2026 vs 2025 (units): monthly tracks move in opposite directions in March-April; Sep 2026: 654,343 vs Sep 2025: 567,173. Claimed source: AISI, Statistic Distribution, read 26 Oct 2026. Note: distribution to dealers is not end-consumer purchases. *Unverified.*
- Cars, Aug vs Sep 2026 (units): wholesale 81,757 to 79,540; retail 83,421 to 81,243. Claimed source: GAIKINDO via Tempo, 12 Oct 2026. *Unverified.*

### Bank Indonesia Consumer Survey

- Expectations index: Aug 127.6 to Sep 128.7; current conditions index: 109.4 to 107.5. The 0-140 range on the chart is the bar-axis scale, not the definition of the index scale. Claimed source: BI, Consumer Survey September 2026, released 8 Oct 2026. *Unverified* against the BI release.

### Scenario map and prediction

- Conceptual volume x price map: volume up-price contained (healthier recovery), volume up-price up (demand strengthening or supply constrained), volume down-price contained (weak demand), volume down-price up (cost and purchasing-power pressure). A conceptual framework, not a plot of observations.
- The prediction stated for Nov-Dec 2026: recovery is more likely to differ across categories than for all indicators to strengthen together; a provisional assessment, not a calibrated model. The conditions that would invalidate the prediction are not specified.

## Independent research protocol and the role of citizens (plan dated 27 Oct 2026)

The plan dated 27 Oct 2026 elaborates the framework above into a field protocol. This is a research proposal; no field survey results exist yet. The references it lists (World Bank DIME, Bank Indonesia PIHPS, UNSD SNA, the SP4N-LAPOR! page) have not been re-verified.

- Question that can be wrong: whether increased spending adds to local economic activity and who benefits, broken into falsifiable hypotheses (demand increases, spending shifts location, supply pressure, welfare improves). Pre-register the question, primary indicators, sample, period, and analysis rules; date and explain any changes.
- Sample: build a population list before selecting respondents (the "always sample from a master dataset" principle); map street segments; select areas and respondents by stratified random sampling; follow the same respondents (panel) with fixed codes; record refusals and dropouts; start with a pilot.
- Measurement tracks: consumption and purchasing power (units sold, working hours, actual prices); prices and supply pressure (transaction-price principle, fixed specifications, price per unit); jobs and income (separate worker counts from total hours worked, nominal from purchasing power); cross-checks across tracks (logistics costs vs inter-regional price gaps; sales vs cash receipts and payment delays).
- Data quality: standard forms; separation of measurement from respondent explanations; cross-checking between observers; correction trails; visibility of missing data and uncertainty; disclosure of funding and conflicts of interest; respondent privacy.
- Citizens' role toward government: standardized observation that can be acted on; helping find causes; testing fixes and re-measuring results; using official complaint channels (the plan notes the SP4N-LAPOR! main page was under maintenance on 27 Oct 2026 and points to prod.lapor.go.id; current status not re-checked).
- Stated limits: sample business turnover cannot be directly summed as a measure of the national economy (referring to the SNA framework); claims beyond the sample population must wait for a design that supports them.

## Concept diagrams and research plan

- **Factor diagram:** households (income, interest), with additional multifactor hypotheses to be tested: credit to spending and working capital; exchange rate to input costs and exports; sales to cash to investment to production; production back to jobs and spending. These arrows are stated as hypotheses, not findings.
- **Research flow diagram:** design the research (testable hypotheses, random sample, fixed panel); citizens gather evidence (real activity, purchasing power and cash, researcher verification); test hypotheses (compare before-after, check controls, assess evidence strength); help government improve (operational findings, test fixes, re-measure results, publish aggregate results).
- **Research plan (15 slides, dated 29 Oct 2026):** 15 slides titled "Rencana Riset - Mengukur Ekonomi dari Bawah" covering design questions, a multifactor map with feedback loops, panel sample design, core recording, separating nominal and real, control-group test design, pilot stages, re-checkable data standards, and the division of roles among citizens, researchers, and government. The plan is a proposal and includes no field results figures. Its content is consistent with the protocol above; it is not fully re-summarized here.

## Proposed test: PortWatch

Proposed test: compare PortWatch cargo-volume estimates with export values at the same ports and periods; if value rises while volume is flat, check commodity prices, goods composition, and the accuracy of the cargo estimate before concluding. Status: proposal, not yet run.

- **Verified:** PortWatch is an IMF/University of Oxford platform with daily satellite-data-based trade volume estimates. An IMF blog (15 Nov 2023) states coverage of 1,400 ports; the PortWatch data page when checked states 1,666 ports. Sources: <https://www.imf.org/en/blogs/articles/2023/11/15/climate-change-is-disrupting-global-trade> and <https://portwatch.imf.org/pages/data-and-methodology>

### Recording PortWatch data revisions

For the proposed test, keep the time of each snapshot, the initial estimate, subsequent revisions, and the data version used in each analysis. Comparing past official figures with later-revised estimates can introduce look-ahead bias.

An unverified example is the China seaborne export estimate for 14 October changing from 7.10 million to 8.03 million tons, with revisions of 7-13% over 12-16 October. These figures and the 11 November PortWatch update have not been matched against their source.

**Verified:** IMF Working Paper WP/26/99 (May 2026), "Nowcasting Country-level Trade Estimates using IMF PortWatch" (Arslanalp et al.), states the method can produce and release monthly trade estimates after seven working days, ahead of many countries' official statistics. Source: <https://www.imf.org/-/media/files/publications/wp/2026/english/wpiea2026099-source-pdf.pdf>

## Open items

- All applied-example figures above have not been verified to primary sources (MDIY reports and Public Expose, UN Comtrade API, AISI, GAIKINDO/Tempo, the BI release).
- The fixed-sample design for measuring direct activity has not been run; it needs a sample design and field data sources.

## Sources

- UN Comtrade Help Center, Bilateral asymmetries: <https://uncomtrade.org/docs/bilateral-asymmetries/>
- Referenced IAS 7 PDF link (behind subscription, content unverified): <https://www.ifrs.org/content/dam/ifrs/publications/pdf-standards/english/2022/issued/part-a/ias-7-statement-of-cash-flows.pdf>


## Visuals from the forwarded Rapi research

The figures below preserve the supplied Rapi research graphics and their visible branding. The two historical charts with a personal header removed are identified in their captions; no chart content or source note was changed. Figures not specifically marked verified remain unverified, historical, or conceptual as stated. No reuse license or public-domain status was provided or verified; this page makes no license claim. Select an image to open its full-size file.

<figure class="research-figure">
  <a href="{{ '/assets/rapi/economy-factor-funnel.png' | relative_url }}"><img src="{{ '/assets/rapi/economy-factor-funnel.png' | relative_url }}" alt="Rapi diagram showing household, business and government, and global factors feeding into demand and supply, then production, transactions, jobs, income, prices, and purchasing power"></a>
  <figcaption><strong>Factor diagram.</strong> Original Rapi image; a simplified set of conceptual paths, not an estimated causal model or a comprehensive feedback network.</figcaption>
</figure>

<figure class="research-figure">
  <a href="{{ '/assets/rapi/economy-research-workflow.png' | relative_url }}"><img src="{{ '/assets/rapi/economy-research-workflow.png' | relative_url }}" alt="Tall Rapi proposed research workflow from hypothesis and panel sampling through citizen evidence, researcher verification, hypothesis tests, government improvements, and aggregate publication"></a>
  <figcaption><strong>Proposed research workflow.</strong> Original Rapi image. This is a proposed design, not an executed study or a government commitment. Open the full-size image for legible text.</figcaption>
</figure>

<figure class="research-figure">
  <a href="{{ '/assets/rapi/vehicle-sales-research.png' | relative_url }}"><img src="{{ '/assets/rapi/vehicle-sales-research.png' | relative_url }}" alt="Historical Rapi charts comparing Indonesian motorcycle distribution and car wholesale versus retail figures through September 2026"></a>
  <figcaption><strong>Vehicle-sales research graphic.</strong> Historical October 2026 Rapi graphic. Figures were not independently reverified here. Domestic motorcycle distribution, car wholesale, and retail are different measures; their directions do not establish a cause. The personal header was removed; chart and source notes are otherwise unchanged.</figcaption>
</figure>

<figure class="research-figure">
  <a href="{{ '/assets/rapi/expectations-and-scenarios.png' | relative_url }}"><img src="{{ '/assets/rapi/expectations-and-scenarios.png' | relative_url }}" alt="Historical Rapi graphic comparing Bank Indonesia consumer expectations and current-conditions indices and showing a conceptual volume-and-price scenario matrix"></a>
  <figcaption><strong>Expectations and scenario graphic.</strong> Historical Rapi graphic. The 0–140 range is the chart's axis, not the index definition. The Nov–Dec 2026 predictions are historical and unvalidated, not a current forecast; the scenario matrix is conceptual, not observed data or probability. The personal header was removed; chart and source notes are otherwise unchanged.</figcaption>
</figure>

<figure class="research-figure">
  <a href="{{ '/assets/rapi/mdiy-and-trade-research.png' | relative_url }}"><img src="{{ '/assets/rapi/mdiy-and-trade-research.png' | relative_url }}" alt="Historical Rapi research graphic on MDIY sales and cash flow and Indonesia–US HS85 trade differences"></a>
  <figcaption><strong>MDIY and trade research graphic.</strong> Historical Rapi graphic. Figures were not independently reverified here. The cash-flow comparison mixes six- and twelve-month periods and is not a growth comparison. The trade discrepancy needs attribution, timing, and goods-detail checks; it is not evidence of misconduct.</figcaption>
</figure>

<figure class="research-figure">
  <a href="{{ '/assets/rapi/credit-and-inflation-slide-sample.png' | relative_url }}"><img src="{{ '/assets/rapi/credit-and-inflation-slide-sample.png' | relative_url }}" alt="Two original Rapi presentation slides comparing credit growth with deposits and showing inflation series"></a>
  <figcaption><strong>Historical presentation sample.</strong> Two Rapi slides from October 2026 about credit/deposits and inflation. This is a separate presentation artifact, not a new measurement; the figures have not been independently reverified here.</figcaption>
</figure>
