# Research Workflows

Use these workflows when the request needs a repeatable research structure rather than a brief explanation.

## Architecture and Standards Extraction

Extract the system or research object into a traceable structure:

- Research object: the system, process, model, artifact, dataset, or standard being analyzed.
- Scope boundary: what is included, excluded, assumed, or left for future work.
- Functional structure: modules, actors, inputs, outputs, data flow, control flow, and interfaces.
- Standards and criteria: relevant standards, specifications, best practices, metrics, compliance points, and acceptance thresholds.
- Constraints: technical, operational, legal, safety, cost, latency, maintainability, interoperability, and data constraints.
- Traceability: map requirement -> design choice -> implementation evidence -> validation method.

Useful outputs include requirement matrices, system decomposition tables, standard-to-design mappings, evaluation rubrics, and architecture narratives.

## Engineering Logic Translation

Translate implementation into research-facing reasoning:

- Begin with the problem the engineering choice solves.
- Explain the mechanism at the right abstraction level before naming code details.
- Tie each major design choice to a requirement, constraint, or measurable outcome.
- Distinguish algorithmic logic, system architecture, data handling, and operational workflow.
- Identify tradeoffs clearly, such as accuracy vs latency, modularity vs complexity, automation vs controllability, or generality vs domain fit.
- Convert code-level behavior into defensible statements: "This component ensures..." only when implementation actually supports that claim.

When reading code, prefer local names and actual control flow over assumed architecture. Quote short identifiers, function names, files, or module names when they help Ian trace the explanation back to the system.

## Literature Review Automation

Organize literature around an argument, not a list of summaries:

- Cluster papers by research problem, method, dataset, system type, evaluation metric, or theoretical perspective.
- Extract each work's contribution, method, evidence, limitation, and relevance to Ian's research question.
- Build synthesis statements that compare groups of work instead of describing one paper at a time.
- Surface research gaps cautiously: a gap must be supported by what the reviewed works do not cover, not merely by absence in a small sample.
- Track citation quality: distinguish peer-reviewed papers, preprints, standards, documentation, industry reports, and blog posts.

Useful outputs include annotated bibliographies, theme matrices, method comparison tables, gap analysis, related-work paragraphs, and citation-ready summaries.

## Reporting and Defense Generation

Shape content for explanation under scrutiny:

- Start with the research problem, why it matters, and the specific contribution.
- Use a claim-evidence-reasoning pattern for important statements.
- Make the novelty bounded and believable.
- Explain methodology as a sequence of justified decisions, not just steps performed.
- Include validation logic: what was measured, why that metric matters, what result would count as success, and what threats remain.
- Prepare likely questions about scope, assumptions, baseline choice, reproducibility, standards alignment, limitations, and generalizability.

For oral defense, generate concise answers that can be spoken naturally. Each answer should make one central point, cite the strongest evidence available, and close by acknowledging a reasonable limitation when appropriate.

## Quality Checks

Before finalizing research output, check:

- Are claims traceable to evidence, implementation, or clearly marked inference?
- Are standards or papers named precisely enough for verification?
- Are limitations honest without weakening the core contribution unnecessarily?
- Does the structure help Ian answer "why this design, why this method, and why these results matter"?
- Would an advisor or reviewer be able to challenge the work and still receive a calm, concrete answer?
