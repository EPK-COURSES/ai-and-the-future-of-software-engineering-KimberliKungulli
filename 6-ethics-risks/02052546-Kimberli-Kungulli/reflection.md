# Personal Reflection

**Student:** Kimberli Kungulli  
**Student ID:** 02052546  
**Topic:** Topic 6 — Risks, Ethics, and Limitations of AI

---

## What surprised me most

Before starting this research, I thought the biggest risk of AI in software engineering was simply that it might generate wrong code that causes bugs. That concern is real, but it turned out to be only the surface level.

What genuinely surprised me was learning about slopsquatting — the idea that attackers are now actively registering package names that AI tools commonly hallucinate. This means the risk is not just accidental: there are people deliberately exploiting AI's weaknesses to inject malicious code into software supply chains. I had never considered that an AI's limitation could be weaponized so directly and systematically.

The 20% hallucinated package rate is striking. If I used an AI assistant 10 times to help with dependencies, statistically two of those recommendations might not exist — and someone may have already prepared a trap at that name.

---

## What concerns me about AI in software engineering

My biggest concern is what I think of as "invisible incompetence." It is possible for a developer today to build and ship working software without deeply understanding what the code does — simply by accepting AI suggestions. The system runs, tests pass, and everything seems fine. But the developer has not actually developed the skill to debug it, redesign it, or secure it under pressure.

This concerns me personally as a student. If I rely too heavily on AI during my education and early career, I might end up with a portfolio of projects I cannot actually explain or maintain. The short-term convenience could cost me the long-term capability.

The accountability gap also concerns me. When AI-generated code causes harm — a data breach, a failed system, an incorrect medical record — it is still not clear who is legally or professionally responsible. The developer who accepted the suggestion? The company that deployed the AI tool? The vendor who built it? This ambiguity creates a space where no one is properly accountable, and that worries me.

---

## What opportunities I see

Despite the risks, I do see genuine opportunity. The engineers who understand these risks and can work responsibly with AI will be in a much stronger position than those who either blindly trust AI or blindly reject it.

There is also a growing need for people who can audit, verify, and govern AI-generated code. Security engineering, ethical AI auditing, and software supply chain security are areas where human expertise becomes more valuable precisely because AI creates new attack surfaces and risks. These are fields I had not seriously considered before this research.

The EU AI Act and emerging U.S. legislation also suggest that compliance engineering and responsible AI implementation will become important specializations. Knowing both the technical side and the regulatory side of AI will be genuinely valuable.

---

## Which skills will remain important

This research made me more convinced that understanding fundamentals — not just frameworks — matters more than ever. If AI can generate code faster than I can type it, my value is not in typing. It is in knowing whether the generated code is correct, secure, maintainable, and appropriate for the context.

Critical thinking and verification skills are essential. The ability to read code I did not write, understand what it does, find what is wrong with it, and know when to reject it — these are skills AI cannot replace and that become more important as AI-generated code becomes more common.

I also think communication and ethical reasoning matter more now. Decisions about when to use AI, in what contexts, with what level of oversight — these are not purely technical decisions. They involve professional judgment and responsibility.

---

## How my opinion changed after research

I started this assignment with a fairly neutral view of AI tools — useful if used carefully, risky if overused. After the research, my view became more specific and more serious.

I now think the risk is not just about individual careless developers. The risk is systemic. When an industry shifts to AI-assisted development without fully understanding the security and legal implications, entire software ecosystems become vulnerable. The 84% adoption rate combined with a 29–45% vulnerability rate in AI-generated code is a combination that deserves serious attention from the profession.

I also changed my view on copyright. I previously assumed that code produced by an AI assistant was legally clean to use. The research showed that this is an open legal question — one that courts and legislators are still working through. Using AI-generated code in a commercial context without understanding the licensing implications is a risk I would not have recognized before.

---
## Final Thought: What I Will Do Differently

Coming back to update this reflection after finishing the full research, one thing stands out above everything else: the gap between how fast AI tools are being adopted and how slowly the profession is adapting its safety practices.

The statistic that hit me hardest was that 1 in 5 organizations has already suffered a breach linked to AI-generated code. That is not a future warning — it is happening now. And yet 58% of developers still trust AI output without proper testing (SQ Magazine, 2026).

The one concrete thing I will do differently because of this research is treat every piece of AI-generated code the way I would treat code written by someone I do not know — read it carefully, test it independently, and never assume it is correct just because it looks right. Trust has to be earned through verification, not assumed because the tool is sophisticated.

I also now understand that the engineers who will be most valuable going forward are not those who generate the most code with AI, but those who can catch what AI gets wrong. That is the skill I want to build.


## How I will personally adapt

Concretely, I plan to:

1. **Always review AI-generated code line by line** before accepting it, rather than trusting that it works because it looks correct.
2. **Verify every library or package** an AI recommends before including it in any project — checking that it exists, is actively maintained, and comes from a trustworthy source.
3. **Keep building fundamental skills** independently of AI — algorithms, data structures, system design, security concepts — so my knowledge does not depend on AI availability.
4. **Follow the legal and regulatory landscape** around AI and software, so I understand the compliance and intellectual property context in which I will be working.
5. **Treat AI as a collaborator that needs supervision**, not as an authority to defer to.

The engineers who will remain valuable in the AI era are not those who use AI the most — they are those who use it most responsibly.
