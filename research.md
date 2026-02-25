---
layout: page
title: Research

---

<style>
.paper-tools {
  display: grid;
  grid-template-columns: max-content max-content;
  column-gap: 0.35em;
  row-gap: 0.45em;
  align-items: start;
  margin: 0.4em 0 1em 0;
}

/* key trick: let summary + panel participate directly in the grid */
.paper-tools > .paper-dropdown {
  display: contents;
}

.paper-tools > .paper-dropdown > summary {
  display: inline-block;
  cursor: pointer;
  padding: 0.15em 0.4em;   /* smaller padding */
  border: 1px solid #ccc;
  border-radius: 6px;
  background: #f7f7f7;
  font-weight: 600;
  font-size: 0.8em;       /* smaller font */
  list-style: none;
  white-space: nowrap;
}

.paper-tools > .paper-dropdown > summary::-webkit-details-marker {
  display: none;
}

.paper-tools > .paper-dropdown > summary::before {
  content: "▸ ";
  font-size: 0.9em;
}

.paper-tools > .paper-dropdown[open] > summary::before {
  content: "▾ ";
}

/* panel appears below BOTH buttons and pushes content down */
.paper-tools > .paper-dropdown > .paper-panel {
  grid-column: 1 / -1;
  display: none;
  justify-self: start;

  width: min(900px, 95vw);
  box-sizing: border-box;
  padding: 0.6em 0.8em;
  border: 1px solid #e3e3e3;
  border-radius: 6px;
  background: #fafafa;
}

.paper-tools > .paper-dropdown[open] > .paper-panel {
  display: block;
}

.paper-panel pre {
  margin: 0;
  white-space: pre-wrap;
  word-break: break-word;
  font-size: 0.8em;
}

.abstract-panel {
  text-align: justify;
}
</style>



<base target="_blank">

### Working Papers
[**Screening Property Rights for Innovation**](img/ms_2026_01_20_main_text.pdf) [(SSRN)](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4519999), with [Mark Schankerman](https://personal.lse.ac.uk/schanker/) ([Online Appendices](img/ms_2026_01_20_online_appendices.pdf)) [BibTeX]()  <br>
Conditionally Accepted, *Econometrica* <br>
Coverage: [C-IP2](https://cip2.gmu.edu/2023/10/04/using-economic-models-to-evaluate-the-efficacy-of-u-s-patent-examination/) <br> 
Presentations: [Zvi Conference 2024](https://www.youtube.com/watch?v=CRdLmHuQOwY&ab_channel=Sciencessociales-Coll%C3%A8gedeFrance) <br>

[**Risk-Based Borrowing Limits in Credit Card Markets**](img/rbbl_main_03_07_website_2025_03_10.pdf) [(SSRN)](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4926974) ([Online Appendices](img/rbbl_online_03_07_website_2025_03_10.pdf)) [[Extra Note](img/rbbl_note_03_07_website_2025_03_10.pdf)] [BibTeX]()  <br>
Revise and Resubmit (1st round), *Journal of Financial Economics* <br> 
Coverage: [FCA](https://www.fca.org.uk/publications/research/interest-rates-risk-based-credit-limits-uk-credit-card-market) <br>
[**Institutional Design of Misconduct Redress: Evidence from the Financial Ombudsman**](img/fos_15.pdf) [(SSRN)](https://papers.ssrn.com/) ([Online Appendices](img/fos_15_online.pdf)) [BibTeX]()  <br>

[**Multivariate Ordered Discrete Response Models with Two Layers of Dependence**](img/KM20251105_nonlattice.pdf) [(SSRN)](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4103429), with [Tatiana Komarova](https://personalpages.manchester.ac.uk/staff/tatiana.komarova/) [BibTeX]()  <br> *Submitted* <br>
[**Multivariate Ordered Discrete Response Models with Lattice Structures**](img/KM20251108_lattice.pdf) [(SSRN)](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5702682) (with [Tatiana Komarova](https://personalpages.manchester.ac.uk/staff/tatiana.komarova/)) [BibTeX]() <br>


### Policy Reports

[**Patent Quality Policy Brief**](img/pat_qual_pol_brief_matcham.pdf), with Ani Harutyunyan <br>
[**Patent Quality Fact Sheet**](img/pat_qual_fact_sheet_matcham.pdf), with Ani Harutyunyan

[**Patent Quality in the United States: Findings and Suggestions for Policymakers**](https://sunwater.org/wp-content/uploads/2024/09/SWI-Policy-Report-Patent-9-23-2024.pdf), with Matthew Chervenak, Ani Harutyunyan, Mark Schankerman, and Nishant Shrestha <br>

Coverage: [IP Watchdog](https://ipwatchdog.com/2024/10/02/patent-quality-report-finds-improper-patent-abandonment-greater-issue-improper-grants/id=181705/#)   [Law360](https://www.law360.com/ip/articles/1882769/nonprofit-finds-bad-patent-epidemic-is-just-a-myth)   [MarketWatch](https://www.marketwatch.com/press-release/council-for-innovation-promotion-celebrates-groundbreaking-sunwater-institute-study-combatting-harmful-patent-disinformation-b8ca0dbf) [ClaimWise](https://www.linkedin.com/pulse/sunwater-institute-urges-critical-reforms-us-patent-system-l3j3e/?trackingId=wQh9%2FFbXwq7OifrCqnrOIQ%3D%3D) [TheWellNews](https://www.thewellnews.com/opinions/a-reality-check-for-patent-quality-critics/) <br> 

Council For Innovation Promotion (C4IP) Panel Discussion (2nd October 2024):
<div style="text-align: center;">
<iframe width="560" height="315" src="https://www.youtube.com/embed/PqsauSsg70c?si=zzTeGUjL_5YaR4ux" frameborder="0" allowfullscreen></iframe>
</div>



### Work in Progress

**On Finance:** <br>
*The Effects of Income Shocks on Asset Allocation and Wealth Inequality* (with [Akash Raja](https://www.akashraja.com/home) and [Nuno Clara](https://www.nunoclara.com/)) <br>

**On Innovation (Joint work, funded by ERC Advanced Grant of [Mark Schankerman](https://personal.lse.ac.uk/schanker/)):** <br>
*Patent Trial and Appeal Board: Killing Property Rights?* <br>
*Evaluating Screening in the European Patent Office* <br>
*Micro-Dynamics of Creative Destruction: Causal Evidence from Patent Renewals* <br>
*Assessing the Patentability Standard* <br>
*Patent Screening in Diverse Technology Fields* <br>
<!---
-->
