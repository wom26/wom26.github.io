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
  font-size: 0.9em;
}

.abstract-panel {
  text-align: justify;
}
</style>



<base target="_blank">

### Working Papers
[**Screening Property Rights for Innovation**](img/ms_2026_01_20_main_text.pdf) [(SSRN)](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4519999), with [Mark Schankerman](https://personal.lse.ac.uk/schanker/) ([Online Appendices](img/ms_2026_01_20_online_appendices.pdf)) <br>
Conditionally Accepted, *Econometrica* <br>
Coverage: [C-IP2](https://cip2.gmu.edu/2023/10/04/using-economic-models-to-evaluate-the-efficacy-of-u-s-patent-examination/) <br> Recording of intro: [Spotify](https://open.spotify.com/episode/1n0MKTUkXJc1FbWsiAy5BQ?si=i805Z6Z-S4CFBWDGyA7RUw) [Acast](https://shows.acast.com/matchams-research-paper-introductions/episodes/screening-property-right-for-innovation) [Apple](https://podcasts.apple.com/us/podcast/screening-property-right-for-innovation/id1714279823?i=1000633111884) [Amazon Music](https://music.amazon.co.uk/podcasts/5db97e90-6542-4e6f-81dd-ef3ca637514b/episodes/dd492ecc-651b-4187-801d-1ccbb625119f/matcham's-research-paper-introductions-screening-property-right-for-innovation)  <br>
Presentations: [Zvi Conference 2024](https://www.youtube.com/watch?v=CRdLmHuQOwY&ab_channel=Sciencessociales-Coll%C3%A8gedeFrance)

<div class="paper-tools">
  <details class="paper-dropdown">
    <summary>Abstract</summary>
    <div class="paper-panel abstract-panel">
      We develop a dynamic structural model of patent screening incorporating incentives, intrinsic motivation, and multi-round negotiation. We use natural language processing to create a new measure of patent distance, which, together with detailed data on examiner decisions, enables us to estimate the model and study strategic decisions by applicants and examiners. Using the estimated model, we quantify the effectiveness of the U.S. Patent Office and evaluate counterfactual policy reforms. We find that patent screening is moderately effective, given the existing standards for patentability. Examiners exhibit substantial intrinsic motivation that strongly improves screening quality. We quantify the annual social costs of patent screening at $15.38bn, equivalent to 5% of total private sector R&D in the U.S. and show that reforms limiting the number of negotiation rounds significantly reduce social costs.
    </div>
  </details>
</div>



<details class="paper-dropdown">
  <summary>Abstract</summary>
  <div class="paper-panel abstract-panel">
    We develop a dynamic structural model of patent screening incorporating incentives, intrinsic motivation, and multi-round negotiation. We use natural language processing to create a new measure of patent distance, which, together with detailed data on examiner decisions, enables us to estimate the model and study strategic decisions by applicants and examiners. Using the estimated model, we quantify the effectiveness of the U.S. Patent Office and evaluate counterfactual policy reforms. We find that patent screening is moderately effective, given the existing standards for patentability. Examiners exhibit substantial intrinsic motivation that strongly improves screening quality. We quantify the annual social costs of patent screening at $15.38bn, equivalent to 5% of total private sector R&D in the U.S. and show that reforms limiting the number of negotiation rounds significantly reduce social costs.
  </div>
</details>

[**Risk-Based Borrowing Limits in Credit Card Markets**](img/rbbl_main_03_07_website_2025_03_10.pdf) [(SSRN)](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4926974) ([Online Appendices](img/rbbl_online_03_07_website_2025_03_10.pdf)) [[Extra Note](img/rbbl_note_03_07_website_2025_03_10.pdf)] <br>
Revise and Resubmit (1st round), *Journal of Financial Economics* <br> <br>
Coverage: [FCA](https://www.fca.org.uk/publications/research/interest-rates-risk-based-credit-limits-uk-credit-card-market) <br> Recording of intro: [Spotify](https://open.spotify.com/episode/3ngwvtfcbdiufCsbtmFuQx?si=Eu0MGm5IS5emRpQ2S7trSA) [Acast](https://shows.acast.com/matchams-research-paper-introductions/episodes/risk-based-borrowing-limits) [Apple](https://podcasts.apple.com/us/podcast/risk-based-borrowing-limits-in-credit-card-markets/id1714279823?i=1000666018648) [Amazon Music](https://music.amazon.co.uk/podcasts/5db97e90-6542-4e6f-81dd-ef3ca637514b/episodes/4610a634-3b96-46fe-8178-807c2c192777/matcham's-research-paper-introductions-risk-based-borrowing-limits-in-credit-card-markets) <br>

<p style='text-align: justify;'> <span style="font-size:1em;"> I use novel statement-level data on the 2010—2015 UK credit card market to show that lenders individualize contracts through risk-based credit limits. Though shared with other European credit markets, this feature contrasts with the US counterpart, where interest rates are also individualized. To quantify the implications of this distinction, I estimate a structural model relating individualized interest rates and credit limits to lender-specific credit scores. I evaluate a counterfactual where lenders can freely tailor prices and credit limits, which the UK environment precludes. Lenders control default risk with credit limits and use prices to extract surplus from inelastic borrowers. </span> </p>

[**Multivariate Ordered Discrete Response Models with Two Layers of Dependence**](img/KM20251105_nonlattice.pdf) [(SSRN)](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4103429), with [Tatiana Komarova](https://personalpages.manchester.ac.uk/staff/tatiana.komarova/) <br> *Submitted*

<p style='text-align: justify;'> <span style="font-size:1em;"> We develop a class of multivariate ordered discrete response models featuring general rectangular structures, which allow for functionally interdependent thresholds across dimensions, extending beyond traditional (lattice) models that assume threshold independence. The new models incorporate two layers of dependence: one arising from the interdependence of decision rules (capturing broad bracketing behaviors) and another from the correlation of latent utilities conditional on observables. We provide microfoundations, explore semiparametric and parametric specifications, and establish identification conditions under logical consistency in decision-making. An empirical application to health insurance markets demonstrates the advantages of this new framework, showing how it disentangles moral hazard (captured via threshold dependence) from adverse selection (isolated in unobservable correlations), offering insights into behavioral responses obscured by lattice models. </span> </p>

[**Multivariate Ordered Discrete Response Models with Lattice Structures**](img/KM20251108_lattice.pdf) [(SSRN)](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5702682) (with [Tatiana Komarova](https://personalpages.manchester.ac.uk/staff/tatiana.komarova/)) <br>

<p style='text-align: justify;'> <span style="font-size:1em;"> We analyze multivariate ordered discrete response models with a lattice structure, modeling decision makers who narrowly bracket choices across multiple dimensions. These models map latent continuous processes into discrete responses using functionally independent decision thresholds. In a semiparametric framework, we model latent processes as sums of covariate indices and unobserved errors, deriving conditions for identifying parameters, thresholds, and the joint cumulative distribution function of errors. For the parametric bivariate probit case, we separately derive identification of regression parameters and thresholds, and the correlation parameter, with the latter requiring additional covariate conditions. We outline estimation approaches for semiparametric and parametric models and present simulations illustrating the performance of estimators for lattice models.  </span> </p>


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
*The Design of Misconduct Redress: Evidence from the UK Financial Ombudsman*

**On Innovation (Joint work, funded by ERC Advanced Grant of [Mark Schankerman](https://personal.lse.ac.uk/schanker/)):** <br>
*Patent Trial and Appeal Board: Killing Property Rights?* <br>
*Evaluating Screening in the European Patent Office* <br>
*Micro-Dynamics of Creative Destruction: Causal Evidence from Patent Renewals* <br>
*Assessing the Patentability Standard* <br>
*Patent Screening in Diverse Technology Fields* <br>
<!---
-->
