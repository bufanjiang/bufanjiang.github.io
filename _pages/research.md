---
layout: page
title: research
permalink: /research/
nav: true
nav_order: 2
---

## Working Papers

<div class="research-item">
  <h3>What Economists Say They Study: Field Labels, JEL Codes, and the Measurement of Research</h3>
  <p class="research-meta">Bufan Jiang</p>
  <details>
    <summary>Show abstract</summary>
    <div class="research-abstract">
      <p>Field labels are ubiquitous in economics: they appear on CVs, in JEL codes, in hiring and promotion files, and in the classifications that meta-analyses use to select studies. Yet the two main records of a scholar's field—the labels she declares and the codes attached to her articles—are rarely validated against each other. I assemble a hand-checked dataset of 273 tenured faculty in the top 20 US economics departments and compare CV-declared fields with the JEL codes recorded on their journal articles. Among the 181 professors who declare more than one field, 24.3% are full matches, 72.4% partial, and 3.3% no match; single-field professors are 90.3% full matches. The raw match rate falls from 71.0% at one JEL digit to 38.6% at three, but at three digits it is close to a uniform benchmark (36.8%). A within-professor benchmark, a permutation test, a mapping audit, and selection reweighting show that labels are informative but not a faithful summary of the portfolio. Field-label sampling and JEL-code sampling identify different populations, and the difference is largest for cross-cutting fields.</p>
    </div>
  </details>
  <a class="paper-download" href="/assets/pdf/Jiang_Field_Labels.pdf" download>Download paper</a>
</div>

<style>
  .post-header { display: none !important; }
  .research-item { border-bottom: 1px solid rgba(128,128,128,0.3); padding: 0 0 1.5rem; margin-bottom: 1.5rem; }
  .research-item h3 { font-size: 1.3rem; margin: 0 0 0.4rem; }
  .research-meta { color: inherit; opacity: 0.75; font-size: 0.95rem; margin-bottom: 0.8rem; }
  .research-item details { margin-bottom: 1rem; }
  .research-item summary { cursor: pointer; font-weight: 600; color: var(--global-theme-color, #0b6e99); }
  .research-abstract p { line-height: 1.65; margin: 0.75rem 0 0; }
  .paper-download { display: inline-block; padding: 0.35rem 0.9rem; border: 1px solid var(--global-theme-color, #0b6e99); border-radius: 4px; color: var(--global-theme-color, #0b6e99); text-decoration: none; }
  .paper-download:hover { background: var(--global-theme-color, #0b6e99); color: #fff; text-decoration: none; }
</style>

<script>
  document.querySelectorAll(".research-item details").forEach(function (box) {
    if (box.querySelector("summary")) return;
    var head = document.createElement("summary");
    head.textContent = "Show abstract";
    var first = box.firstChild;
    if (first && first.nodeType === 3 && first.textContent.trim() === "Show abstract") box.removeChild(first);
    box.insertBefore(head, box.firstChild);
  });
</script>
