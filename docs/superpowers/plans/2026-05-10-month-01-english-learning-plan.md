# Month 1 — Foundation: Implementation Plan

> **For agentic workers:** USE Write tool to create each file. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Produce Month 1's 4 weekly learning files covering basic sentence structure, simple tenses, and daily dev vocabulary.

**Architecture:** Each week is a standalone markdown file. Content is written sequentially — Week 1 grammar lays the foundation for Week 2, etc. All files are pure content, no scripts.

**Output:** 5 files (1 overview + 4 weekly files)

---

## File Map

| File | Responsibility |
|------|---------------|
| `plan.md` | 6-month overview, monthly goals, how to use |
| `month-01-foundation/week-01.md` | Basic sentence structure + 20 dev verbs |
| `month-01-foundation/week-02.md` | Simple present & present continuous + dev nouns |
| `month-01-foundation/week-03.md` | Simple past & past continuous + collaboration verbs/nouns |
| `month-01-foundation/week-04.md` | Future tense + error/bug vocabulary + Month 1 review |

---

### Task 1: Project overview file

**Files:** Create `plan.md`

- [ ] **Step 1: Write `plan.md`**

The overview file gives the user a bird's-eye view of all 6 months and how to use the materials. Write the following content:

```markdown
# 6-Month English Improvement Plan

## Goal

Go from "can read docs but struggle to speak" to "communicate fluently in remote work settings."

## How to Use This Plan

1. Read through the grammar explanation and sentence breakdowns
2. Go over each vocabulary word and its example sentences
3. Do the sentence-making exercises (write out sentences, then check against the answer)
4. At the end of each week, review your mistakes and the "commonly confused" section
5. Speaking practice is on you — this plan handles vocabulary, grammar, and sentence output

## Learning Principles

- **No rote memorization** — learn words through sentences and context
- **Grammar through analysis** — understand sentence structure, not just rules
- **Internet-industry focus** — all vocabulary and examples come from real dev/tech scenarios
- **Review is built in** — each week's file includes a review section

## 6-Month Roadmap

| Month | Grammar | Vocabulary Domain |
|-------|---------|-------------------|
| 1 | Basic sentence structure, simple tenses, continuous tenses | Daily development terms (verbs/nouns) |
| 2 | Perfect tenses, perfect continuous, passive voice, modal verbs | Collaboration & communication |
| 3 | Noun clauses, relative clauses, adverbial clauses | System design & architecture |
| 4 | Conditionals, subjunctive mood, non-finite verbs | Product & data |
| 5 | Inversion, emphasis, ellipsis, articles & prepositions | Business & interview |
| 6 | Comprehensive review, long-sentence breakdown, common errors | Remote work scenario integration |

## Monthly Goals at a Glance

### Month 1 — Foundation
- Master the 5 basic English sentence patterns
- Correctly use simple present, past, future and continuous tenses
- Acquire ~80 core dev verbs and nouns with their common usages
- Be able to write a correct 10+ word sentence about your work

### Month 2 — Building
- Understand and use perfect tenses (have done / had done)
- Use passive voice appropriately in technical descriptions
- Use modal verbs for polite requests and technical probability
- Vocabulary: ~80 collaboration terms (meetings, code review, async communication)

### Month 3 — Expanding
- Master noun clauses (that, wh-, whether)
- Master relative clauses (who, which, that — essential vs. non-essential)
- Master adverbial clauses (time, cause, condition, concession)
- Vocabulary: ~80 system design & architecture terms

### Month 4 — Deepening
- Understand conditionals (zero, first, second, third)
- Grasp subjunctive mood (wish, if only, would rather)
- Use non-finite verbs correctly (gerund vs. infinitive, participle phrases)
- Vocabulary: ~80 product & data terms

### Month 5 — Refining
- Use inversion for emphasis in presentations
- Apply emphasis (cleft sentences, do-emphasis)
- Master articles (a/an/the) and prepositions in technical contexts
- Vocabulary: ~80 business & interview terms

### Month 6 — Mastering
- Break down long, complex sentences confidently
- Self-correct common Chinese-speaker errors
- Integrate all vocabulary domains into fluent output
- Be interview-ready for remote work scenarios
```

- [ ] **Step 2: Commit**

```bash
git add plan.md
git commit -m "feat: add 6-month overview plan"
```

---

### Task 2: Week 1 — Basic Sentence Structure + Dev Verbs

**Files:** Create `month-01-foundation/week-01.md`

- [ ] **Step 1: Write `month-01-foundation/week-01.md`**

**Grammar Section: 5 Basic Sentence Patterns**

For each of the 5 patterns, provide:
1. A clear Chinese explanation of the structure
2. 3 example sentences in dev/internet contexts
3. Syntax breakdown of one sentence (mark each component: Subject, Verb, Object, Complement, Adverbial)
4. A memorization/understanding tip
5. Common mistake Chinese speakers make

Patterns to cover:
1. **S + V (主语 + 不及物动词)** — e.g., "The server crashed."
2. **S + V + O (主语 + 及物动词 + 宾语)** — e.g., "I wrote a script."
3. **S + V + C (主语 + 系动词 + 主语补足语/表语)** — e.g., "The code is messy."
4. **S + V + O + O (主语 + 动词 + 间接宾语 + 直接宾语)** — e.g., "She sent me the patch."
5. **S + V + O + C (主语 + 动词 + 宾语 + 宾语补足语)** — e.g., "We made the API faster."

For each pattern, write the syntax breakdown like this:

```
Example: The server crashed.
- The (determiner) + server (subject/noun) + crashed (predicate/intransitive verb)
- Analysis: This is the simplest English sentence pattern. The verb "crash" is intransitive — it doesn't need an object. The action happens to the subject itself.
- Common mistake: Chinese speakers often add an unnecessary object — ❌ "The server crashed itself."
- Tip: Think of intransitive verbs as "self-completing" actions — the meaning is done without needing a receiver.
```

**Vocabulary: Top 20 Dev Verbs**

For each verb, provide:
- 3 common meanings (label with Chinese equivalent + part of speech)
- 1 example sentence per meaning (all in dev/tech/work contexts)

Example format:

```
### 1. deploy
- **Meaning 1: 部署 (v.)** — to release software to a server or environment
  - "We deploy new features to production every Monday."
- **Meaning 2: 安排配置 (v.)** — to arrange or position resources strategically
  - "The team deployed three engineers to the incident response."
- **Meaning 3: 施展/发挥作用 (v.)** — to put into effective action
  - "She deployed her deep JavaScript knowledge to fix the performance bug."
```

The 20 verbs for Week 1:
1. deploy
2. implement
3. execute
4. configure
5. trigger
6. resolve
7. debug
8. fetch
9. render
10. parse
11. validate
12. merge
13. rollback
14. refactor
15. deprecate
16. iterate
17. initialize
18. log
19. cache
20. scale

**Sentence-Making Practice**

Provide 10 prompts that require using this week's vocabulary and sentence patterns. Include expected reference answers. Format:

```
1. Write a sentence about what happens when you push code. (Use Pattern 2: SVO, and the verb "trigger")
   Reference: "Pushing to main triggers the CI pipeline."
```

**Weekend Review**

- List 5 pairs of easily confused verbs from this week with clarifying sentences
- A self-check checklist: "Can I name the 5 sentence patterns? Can I use each of these 20 verbs in a sentence?"

- [ ] **Step 2: Commit**

```bash
mkdir -p month-01-foundation && git add month-01-foundation/week-01.md
git commit -m "feat: add Month 1 Week 1 — sentence patterns + dev verbs"
```

---

### Task 3: Week 2 — Simple Present & Present Continuous + Dev Nouns

**Files:** Create `month-01-foundation/week-02.md`

- [ ] **Step 1: Write `month-01-foundation/week-02.md`**

**Grammar Section: Simple Present & Present Continuous**

For Simple Present:
1. Core usage: facts, habits, schedules, states — with dev examples
2. Third-person singular -s rule and common pitfalls
3. Negative and question forms
4. At least 5 example sentences, each with syntax breakdown
5. Common Chinese-speaker errors (e.g., forgetting -s)

For Present Continuous:
1. Core usage: actions happening now, temporary situations, near-future arrangements
2. Form: be + V-ing
3. Stative verbs that DON'T use continuous (know, understand, belong, etc.)
4. At least 5 example sentences, each with syntax breakdown

Contrast: When to use present vs. present continuous — with paired examples

**Vocabulary: Top 20 Dev Nouns**

Same format as Week 1 (3 meanings + example sentences each):

1. repository
2. dependency
3. endpoint
4. interface
5. variable
6. function
7. parameter
8. argument
9. database
10. query
11. schema
12. instance
13. container
14. deployment
15. pipeline
16. artifact
17. threshold
18. redundancy
19. latency
20. throughput

**Sentence-Making Practice**

10 prompts mixing Week 1 verbs + Week 2 nouns + present tenses. Include reference answers.

**Weekend Review**

- Easily confused pairs from Weeks 1-2
- Grammar self-check: present vs. present continuous

- [ ] **Step 2: Commit**

```bash
git add month-01-foundation/week-02.md
git commit -m "feat: add Month 1 Week 2 — present tenses + dev nouns"
```

---

### Task 4: Week 3 — Simple Past & Past Continuous + Collaboration Vocab

**Files:** Create `month-01-foundation/week-03.md`

- [ ] **Step 1: Write `month-01-foundation/week-03.md`**

**Grammar Section: Simple Past & Past Continuous**

For Simple Past:
1. Regular verbs: -ed pronunciation rules (/t/, /d/, /ɪd/)
2. Irregular verbs: top 30 most common in dev contexts (write→wrote, build→built, send→sent, etc.)
3. Negative and question forms (did + base form)
4. At least 5 example sentences with syntax breakdown
5. Common errors: double past marking (❌ "I didn't saw"), wrong irregular form

For Past Continuous:
1. Usage: action in progress at a past moment, two simultaneous past actions, interrupted action
2. Form: was/were + V-ing
3. Contrast with simple past — paired examples

Past Continuous vs. Simple Past contrast: When one action interrupts another — "I was debugging the issue when the meeting started."

**Vocabulary: Top 20 Collaboration Verbs & Nouns**

Mix of verbs and nouns used in team communication:

1. align (v.)
2. clarify (v.)
3. escalate (v.)
4. prioritize (v.)
5. delegate (v.)
6. brainstorm (v.)
7. sync (v.)
8. onboard (v.)
9. offload (v.)
10. follow up (v.)
11. stakeholder (n.)
12. consensus (n.)
13. blocker (n.)
14. deliverable (n.)
15. milestone (n.)
16. timeline (n.)
17. scope (n./v.)
18. trade-off (n.)
19. bandwidth (n.)
20. capacity (n.)

**Sentence-Making Practice**

10 prompts involving past narration of work events. Include reference answers.

**Weekend Review**

- Irregular verb self-quiz (write→?, build→?, etc.)
- Commonly confused: align vs. agree, scope vs. scale, bandwidth vs. capacity

- [ ] **Step 2: Commit**

```bash
git add month-01-foundation/week-03.md
git commit -m "feat: add Month 1 Week 3 — past tenses + collaboration vocab"
```

---

### Task 5: Week 4 — Future Tense + Error/Bug Vocab + Month 1 Review

**Files:** Create `month-01-foundation/week-04.md`

- [ ] **Step 1: Write `month-01-foundation/week-04.md`**

**Grammar Section: Expressing Future**

1. **will** — spontaneous decisions, predictions, promises
2. **be going to** — planned intentions, evidence-based predictions
3. **Present continuous for future** — scheduled arrangements
4. **Present simple for future** — timetabled events

For each, provide 3+ example sentences with syntax breakdown.
Then a contrast table: when to use each form — with paired scenarios.

**Vocabulary: Top 20 Error & Bug Terms**

1. crash (v./n.)
2. timeout (n.)
3. exception (n.)
4. bottleneck (n.)
5. outage (n.)
6. corrupt (v./adj.)
7. leak (memory leak) (n./v.)
8. race condition (n.)
9. deadlock (n.)
10. regression (n.)
11. edge case (n.)
12. breach (n./v.)
13. exploit (n./v.)
14. patch (n./v.)
15. hotfix (n.)
16. stale (adj.)
17. flaky (adj.)
18. obsolete (adj.)
19. duplicate (v./n./adj.)
20. inconsistent (adj.)

**Month 1 Review**

- Tense overview: a summary table of all 6 tense forms covered, with one example each
- Sentence pattern review: one example of each 5 patterns using Month 1 vocabulary
- Self-assessment checklist for Month 1
- Preview of Month 2

**Sentence-Making Practice**

10 prompts for future-tense bug/incident scenarios. Include reference answers.

**Weekend Review**

- All commonly confused pairs from Month 1
- Tense self-quiz: fill in correct tense form

- [ ] **Step 2: Commit**

```bash
git add month-01-foundation/week-04.md
git commit -m "feat: add Month 1 Week 4 — future tense + error vocab + review"
```

---

### Task 6: Verify and deliver

- [ ] **Step 1: Review all files for completeness**

Check each file has: grammar with syntax breakdowns, 20 vocab words (3 meanings + sentences each), sentence-making practice, weekend review.

- [ ] **Step 2: Commit any final fixes**

```bash
git add -A month-01-foundation/ plan.md
git commit -m "chore: finalize Month 1 files" --allow-empty
```
