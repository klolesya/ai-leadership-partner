# Testing notes

**Published package: v0.11.0-rc3 · Russian and English**

## Personal use by the creator

On 9 October 2026, the creator reported personally trying the skill in 15 management situations. This is hands-on use reported by the creator, separate from automated scenario testing. The exact revisions, dates and outcomes of the 15 trials have not been documented here. They are not represented as 15 tests of the final rc3 build or as an independent user study.

## Automated scenario testing

The retained development record contains 254 model responses across three revisions, with 84 case identifiers:

| Revision | Recorded responses | Coverage |
|---|---:|---|
| rc1 | 166 | All 19 leadership areas in Russian and English over three turns, plus targeted language, ethics, practice, factual-grounding and research scenarios. |
| rc2 | 76 | Repeated second and third turns for all 19 areas in both languages after an investigation-threshold fix. |
| rc3 | 12 | Targeted checks following further wording and reasoning fixes. |
| **Total** | **254** | **Across three revisions, not 254 complete tests of the final revision.** |

Five findings were accepted: one of medium significance and four of low significance. They concerned premature causal focus before understanding the manager’s reasoning, ambiguous action ownership, the direction of a resource trade-off, interacting causes, and assigning an observation to an unsupported option. Rules were refined and the accepted issues did not recur in the targeted follow-up checks. This does not establish that future errors are absent.

The final core passed 15 recorded static checks covering structure, references, consistency and package integrity. The standard validator did not run because PyYAML was unavailable; YAML was checked using Ruby and the remaining checks used a custom script. This is not a claim that the standard validator passed.

## What these checks do not establish

The conversations used synthetic scenarios and shared executor contexts within batches. They are not statistically independent trials or independent human evaluation. The full suite was not rerun on final rc3. Historical checks of earlier English-only editions are not included in the 254 responses.

Real-world effectiveness, learning transfer and equivalence to a human coach have not been established. Other conversation languages, long-term memory and automatic installation in a different environment were not tested in this record.

This page summarizes the retained development record; it is not a new test run or a publication of the full raw conversation corpus. No private workplace stories from the creator’s trials are included.
