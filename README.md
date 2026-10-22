# Who Writes the Answer Key?

**Lessons from Forty-Eight Rounds of Trying to Benchmark Autonomous Physics Research**

[Erin Krasniqi](https://orcid.org/0009-0008-0051-4163) · Working paper, version 1 · October 2026

**[Read the paper (PDF, 55 pages)](Krasniqi_2026_Who_Writes_the_Answer_Key_v1.pdf)** · Permanent record: [doi.org/10.5281/zenodo.23579090](https://doi.org/10.5281/zenodo.23579090)

From 23 September to 21 October 2026, one person and three AI systems tried to build an automatically scored benchmark of autonomous physics research that models could not saturate without genuinely improving. The team built and tested designs over about 48 rounds, and every design was eventually rejected. The paper is the record of why.

## Main findings

- The tested model, gpt-6.1-sol, solved nearly every single-principle discovery world we scored (23 of the 49 scored cells supplied the law or a hint, or were controls).
- Producing answer keys was easy. We did not establish an in-house task family that combined validated scoring, attainability from the supplied evidence, resistance to the declared shortcuts, and useful headroom for the tested model.
- Many rejections fall into four overlapping groups by how the answer key was built (some had more local causes):
  - keys from the designers' knowledge were reached by the solver;
  - authored laws were found by the model, or generic programs learned their scored behavior;
  - computed truths could support only a small separation on one machine;
  - in the verifier families, standard methods reached certified optima at small sizes.
- Three rules for benchmark builders: programs reject and models certify; a speed gap is not research headroom; measure the gap at the scored precision.
- The paper also documents the AI designers' own failures, several of which resemble capabilities the benchmark sought to measure, and sketches a protocol for answer keys from outside sources.

## How it was made

Erin Krasniqi set the goal, approved every model run and made the scope decisions. ChatGPT Pro designed, Codex built and ran the experiments, and Claude directed and verified. Claude drafted the paper from the project record, and ChatGPT Pro reviewed the full draft twice. Appendix F gives the details.

## Cite

Krasniqi, E. (2026). *Who Writes the Answer Key? Lessons from Forty-Eight Rounds of Trying to Benchmark Autonomous Physics Research.* Working paper, version 1. Zenodo. https://doi.org/10.5281/zenodo.23579090

## License

[CC BY 4.0](LICENSE.md)
