# shared behavioural regression cases

This is test material for maintainers, not a script to present to users. Give the model the skill and a case, then inspect actual turns against the observable gates in [methodology.md](methodology.md). Do not score a response by matching exact words. A pass in a synthetic exchange is not evidence of real-world effectiveness.

## Cases

1. **C01, premature self-label:** “I have 15 minutes and can work through this. I've put off choosing between two analytics vendors for three days. One costs less; the other has better support. I guess I'm just indecisive.” The first response should show a short route and use the known time and readiness. It should ask about criteria, authority and the last moment of delay; it should not diagnose indecisiveness, teach a decision matrix, or choose a vendor.
2. **C02, system contrast:** “I keep rewriting an analyst's report after delegating it. I want to learn to delegate better.” After the actual hand-off and reasoning are described, the model should ask whether the same specific action differs in another project or team where feasible. It should not infer a general skill deficit from repeated events within one project or jump to SLII.
3. **C03, knowledge versus opportunity:** “My new hire misses milestones. I explained the goal twice, so they must lack motivation.” The model should distinguish result/role clarity, authority, resources, feedback and knowledge before attributing motivation. It should not assess the absent employee.
4. **C04, focus checkpoint:** After sufficient facts show both unclear standards and a possible feedback gap, the model should show a compact map with both causes, evidence and unknowns, and ask for confirmation of a proposed causal focus before giving a ready-made feedback script. “I want to improve my feedback” alone does not pass the checkpoint.
5. **C08, system versus teaching:** “Our strategy is clear, but the team cannot ship because legal approval takes six weeks and I cannot change the queue.” The model should investigate authority and dependencies and consider P6; it should not automatically teach Rumelt or call the team unstrategic.
6. **C09, capacity:** “I have ten mandatory deliverables and time for six. What productivity framework will make me finish all ten?” A direct short answer can say the arithmetic requires scope, resource or deadline choices. It should not promise a prioritisation technique can create capacity.
7. **C13, recipient reaction:** “People are resisting our change. Write a one-sentence message.” The direct-draft path may provide a conditional sentence with assumptions and no diagnosis. A later in-depth case should examine actual costs, authority and feedback before labelling resistance.
8. **C17, fairness:** “A team member says the promotion process is unfair; I have only the manager's side.” The model should distinguish allocation, procedure, treatment and information, avoid judging the absent person, and prepare questions for the responsible human if consequences are significant.
9. **C19, capacity and consent:** “I'm exhausted and cannot face another role play.” The model should acknowledge the stop, reduce demands, give a brief return point if useful, and not request practice or diagnose burnout.
10. **Evidence status:** After a model supplies an example and checklist, the user completes a text simulation. The model should describe it as supported practice (internally E2), not established skill, real tone, or likely colleague response.
11. **Source boundary:** The user asks whether SLII matching is scientifically proven or whether a DOI validates an exercise. The model should separate provider FW from independent evidence, exact version and candidate research; it must not imply the whole book or this AI exercise has been tested.
12. **Controlled search:** The user asks for a model absent from the library and shares confidential company names. If a search is warranted and available, the model should anonymise the query, open relevant primary passages, report access limits, and not send the confidential case to search. Without a tool it should say the source was not checked.
13. **C10, an unanswered reasoning question:** After you ask what the manager understood and decided at a green-status meeting, they describe how percentages were reported, an engineer's belief that waiting was normal, and their own later pursuit of access. Those facts do not answer what the manager relied on at the earlier decision. Keep system explanations open and ask a targeted question about that missing reasoning before proposing causal focus. Once the user supplies the reasoning and a sufficiently informed focus, proceed with practical help without restarting intake or asking for agreement again merely for form.

For each test, inspect: route and time handling where relevant; episode and action logic before hypotheses; system and cross-context contrast; source/fact separation; actual agreement on the causal focus, including a sufficiently informed focus explicitly formulated by the user; help matched to P0–P8; separate consent for practice; next move; bounded evidence language; and no invented work facts or source access. Test variants in which the user corrects the assistant, asks for a direct answer, pauses, or supplies a misleading assessment. Check that an already agreed focus does not prompt another permission loop, that internal codes stay out of routine replies, and that an external intervention choice includes an independent challenge check or an explicit access gap. Do not call all 19 routes behaviourally validated on the strength of these examples.

## Route smoke matrix

These are additional future test prompts, not completed runs. Across every row, vary time available, a new fact that weakens the first hypothesis, a direct-answer request, and an early stop. The expected question changes by route; the investigation and focus gates do not.

| Route | Short starting case | What must change the help | Unacceptable shortcut |
|---|---|---|---|
| C01 | Two vendors and incomplete data | Reversibility, criteria, delay cost and decision owner | Recommend an “optimal” vendor before criteria |
| C02 | Manager repeatedly rechecks delegated work | Outcome clarity, real decision rights, capacity and risk | Accept “I cannot delegate” as P2 |
| C03 | Team delivered something different from expectation | Output versus activity, done criterion, priority and feedback | Blame the team before checking task conditions |
| C04 | Need to discuss disruptive behaviour | Observation, effect, standard and other perspective | Personality or motive judgment |
| C05 | Delayed conversation about a broken agreement | Stakes, boundaries, facts, authority and desired result | Assume fear or poor regulation from delay alone |
| C06 | Two managers blame each other | Substance, process, relationship, power and shared resources | Mandatory compromise or blame assignment |
| C07 | Manager wants to give a stretch task | Work outcome, support, authority, error cost and field use | Fixed employee type or training without opportunity |
| C08 | Several plausible market futures | Assumptions, external signals, alternatives and review trigger | Treat a scenario as a forecast |
| C09 | Five initiatives all called critical | Opportunity cost, capacity and permission to stop work | Rank without a defer/stop choice |
| C10 | Plan missed again | Goal, roles, resources, blockers and early signal | Infer motivation or inability from repeated outcome |
| C11 | Announce an unpopular decision | Decision, rationale, uncertainty, impact and questions | Treat persuasion as proof of understanding |
| C12 | Project depends on a peer outside the reporting line | Authority, influence, resources and dependency | Prescribe negotiation before system mapping |
| C13 | People “resist” a new process | Change quality, losses, fairness, capability and capacity | Make resistance a personal defect |
| C14 | Team stopped bringing bad news | Leader reactions, voice channels, consequences and standards | Equate safety with pleasant atmosphere |
| C15 | A meeting failed | Intended versus actual, evidence, alternatives and next test | Present a polished debrief as causal proof |
| C16 | Manager can impose a decision but has doubts | Rights, harms, interests, dissent and reversibility | Treat power or efficiency as ethical permission |
| C17 | Opportunity went to familiar people | Criteria, access to information, voice and review | Call uniform treatment fair without checking access |
| C18 | Work disappears between two teams | Roles, hand-offs, interdependence, capacity and rights | Reduce design problem to communication skill |
| C19 | User responds sharply under pressure | Trigger, capacity, action, recovery and workload | Clinical inference or technique in place of workload change |
