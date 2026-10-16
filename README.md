# The Capability Question: AI Enablement Measurement Tool

A research design assistant that helps practitioners measure what AI enablement actually does to the people using it.

Most organizations deploying AI tools to their workforce measure adoption through utilization rates, completion data, and satisfaction scores. None of that tells you whether your people are getting better at their jobs.

This tool asks you 19 questions about your AI tool, your employee population, and your organizational context. Then it generates a tailored study design, honest about what is feasible and specific about what the findings can and cannot claim.

**Try it:** [shannonlcoleman.com/capability-measurement-tool](https://shannonlcoleman.com/capability-measurement-tool)

Free to use for non-commercial purposes with attribution.

---

## What This Tool Produces

A structured eight-section study design report covering:

1. **Assessment Parameters:** a summary of your deployment context
2. **The Capability Question for This Context:** the specific question your study is designed to answer
3. **Before You Can Run This Study:** preconditions that need to be in place, or an honest assessment of feasibility constraints
4. **Recommended Study Design:** methods, measurement timepoints, and sample size guidance with transparent reasoning
5. **Honest Limitations:** what the design cannot claim and the specific language to use when presenting findings
6. **What Your Findings Might Look Like:** how each of the three possible outcome patterns would show up in your data
7. **Communicating Your Findings:** framing for the people who will see the findings
8. **Suggested Next Steps:** what to do first, second, and third in your situation

---

## The Framework

This tool applies a framework developed by Shannon L. Coleman, PhD:

**Capability is not the same as completion.** An employee who finishes tasks is not necessarily an employee who is developing judgment.

**Confidence and capability diverge in predictable ways when AI tools are involved.** AI systems produce fluent, authoritative outputs that reliably increase user confidence regardless of accuracy. A well-designed study has to disaggregate confidence from capability rather than treating self-reported confidence as a proxy for either.

**Substitution and development look identical in the short term.** A tool that does the thinking for employees and a tool that develops their thinking produce similar short-term metrics. Longitudinal measurement is the only way to tell the difference.

The full theoretical foundation is documented in the Ground Truth Substack series [The Capability Question: What AI Enablement Actually Does to People](https://byshannoncoleman.substack.com).

---

## How It Works

The tool uses Claude Sonnet 4.6 via the Anthropic API. The system prompt encodes the full capability measurement framework including methods guidance, reasoning principles, report structure, and the branching logic that tailors recommendations to each situation.

**The code is open.** The full source, including the system prompt, is in this repository. The methodology is the point, so you can see exactly how the tool reaches its recommendations.

---

## License

Creative Commons Attribution-NonCommercial 4.0 International. Free to use, adapt, and share for non-commercial purposes with attribution. Commercial use requires explicit permission.

For licensing inquiries: shannon@shannonlcoleman.com

---

## About

Built by [Shannon L. Coleman, PhD](https://shannonlcoleman.com), Principal Mixed Methods Researcher and Strategist.

Portfolio: [shannonlcoleman.com](https://shannonlcoleman.com)  
Ground Truth: [byshannoncoleman.substack.com](https://byshannoncoleman.substack.com)
