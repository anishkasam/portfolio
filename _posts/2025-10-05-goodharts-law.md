---
title: Goodhart's Law
---

"When a measure becomes a target, it ceases to be a good measure." 

In layman's terms, most objectives can't directly be measured, so we use a metric (as a proxy) in an attempt to measure the objective. However, once people start optimizing for the metric, it loses its value as a metric and no longer reflects the underlying objective it was meant to measure.

This idea has recently surfaced in the context of AI benchmarks, where [Meta built a model tuned specifically to perform well on benchmarks](https://techcrunch.com/2025/04/06/metas-benchmarks-for-its-new-ai-models-are-a-bit-misleading/?utm_source=chatgpt.com). These benchmarks were supposed to measure intelligence, but once labs started optimizing for the test instead of real intelligence, the scores lost their meaning.

I think this phenomenon is evident throughout society. We’ve undergone a fundamental shift in thinking, quantitative metrics are now treated as objective truth. But, the issue with this approach is that we lose so much context when we reduce complex observations into digestible numbers.

Now, this is obvious in some contexts. Take football for example, we know that simply comparing quarterbacks based on their passing statistics (yards, touchdowns, interceptions) is incomplete. It doesn't take into context the offensive scheme, receiver quality, game scripts, etc. We all know that a quarterback's talent/ability can’t be captured by a few numbers, and that’s why we call players who chase stats stat padders.

However, in other areas, this is less obvious. Take college admissions, for example. Intelligence can’t really be measured, so colleges use GPA and standardized test scores as proxies. This pushes students to take as many AP courses as possible and grind SAT/ACT prep instead of organically pursuing passions or exploring interests (which in my opinion, should be the only priority at that age).

Similarly, in software engineering interviews, companies have to evaluate candidates in a short period of time, so they resort to LeetCode style questions. But these interviews don't actually measure whether someone is an effective engineer.

The problem is that these systems create negative feedback loops. Institutions depend on these metrics, so applicants spend their time to mastering them. In response, institutions raise the bar even higher, pushing candidates to grind harder. The cycle keeps repeating, and eventually, both sides lose sight of the original goal. Institutions start selecting for stat padders, and candidates learn to pad stats.