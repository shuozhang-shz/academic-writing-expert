# Composition decisions for scientific prose

Use the relevant section when a sentence or paragraph needs diagnosis beyond the overview in [language and style](language-and-style.md). These are operational additions from the second writing deck, not a mandatory editing sequence. Preserve the editing scope and scientific invariants in [SKILL.md](../SKILL.md). All examples below are invented teaching material; their numbers and assertions are not research evidence.

Contents: paragraph purpose and bridges; voice and accountability; affirmative wording; compression; sentence hierarchy; parallelism; attachment; tense and emphasis.

## 1. Paragraph purpose, development, and bridges — rules 9–10

For an unfocused paragraph, write a private one-sentence account of the question it answers or the judgment it supports. A topic label such as “sensor performance” does not yet state the point. If the account needs unrelated claims, inspect whether the paragraph should split; if it cannot be written, inspect the reasoning before polishing the opening.

Assign each sentence a role relative to that point: evidence, explanation, example, contrast, qualification, or consequence. Relocate a sentence that answers a different question; retain an apparently digressive limitation if it changes the interpretation. Develop a thin argument with supplied support, not invented evidence. Paragraph breaks should mark changes in the reasoning, not a fixed sentence count. Use consistent paragraph formatting appropriate to the document rather than manual spaces.

Compare the first and last sentences. The opening should orient the reader; the ending should leave the supported point, consequence, boundary, or next question clear. It need not restate the opening. Remove an unrelated last-minute topic or relocate a minor procedural detail when it distracts from the paragraph's purpose. Do not require explicit topic and conclusion sentences when the context already supplies them.

For a broken bridge between paragraphs, identify the actual relationship first, then choose the lightest repair:

- Repeat the same technical term when the entity continues; do not introduce a synonym that looks like a second entity.
- Use a specific referring phrase, such as “This calibration error,” when the previous finding becomes the next topic.
- Add a short bridge that names the shift, for example from measured performance to a limitation, if the connection would otherwise be missing.
- Use furthermore for addition, however for contrast, for example for illustration, similarly for an actual parallel, and therefore only for a supported inference. A connector cannot supply absent reasoning.

Read the paragraph purposes consecutively to check the argument; read neighboring endings and openings to check the handoff. Use this diagnosis only within the requested scope.

## 2. Voice, subjects, and accountable decisions — rule 11

Choose the subject by what this sentence contributes to the paragraph. Consider the intended focus, whether the actor matters, the previous sentence's topic, the location of new information, and any explicit journal requirement. When no competing focus favors a passive construction, try a direct active sentence.

| Intended focus | A possible form | Decision boundary |
|---|---|---|
| Researchers' action | “We fitted the recovery curve.” | Use we only for the actual authors' action |
| A model, measurement, or physical process | “The model predicts the recovery time.” | Nonhuman subjects are legitimate; the verb must describe an actual capability or supported relationship |
| An already introduced object or procedure | “The recovery curve was fitted with a biexponential function.” | Passive voice can preserve topic continuity and keep the method prominent |
| An accountable analytical decision | “We excluded the trace because the detector saturated.” | The decision maker and reason must be supplied, never inferred from a stylistic rewrite |

Do not erase the basis of exclusions, model selection, or interpretation behind “it was decided.” An omitted routine operator may be harmless; an unexplained research decision may be consequential. Query a missing rationale locally. A passive statement with a clear reason can also be adequate; active voice is not a substitute for transparency.

Separate three diagnoses: passive voice, an empty action noun, and an existential construction. “An assessment of drift was performed” can become “Drift was assessed” while remaining passive. “There were three peaks in the spectrum” is existential, not passive. Retain it if introducing the peaks is useful. A more vivid verb must not add coverage, causality, or certainty absent from the original.

Models can predict, curves can show a feature, and data can support an inference. They do not need fictional human intentions. Simplify stacked passives if their relationship is clear, but preserve attribution and modality: “The specimens were required to be sealed” can become “The protocol required sealed specimens” only when the protocol is the stated source of the requirement.

## 3. Direct statements without changing the proposition — rule 12

Before replacing a negative with an affirmative, state what the original rules out and what possibilities remain. A direct positive formulation is useful only if the supplied context selects that possibility.

- “Did not increase” leaves both no change and a decrease possible. Report a decrease and its magnitude only when the data establish it.
- “Did not examine late-stage behavior” does not by itself establish an exclusive early-stage focus. State the actual studied interval if known, or retain the explicit limitation.
- Weak support, contradiction, and no evidence are different evidential states. Do not change “limited support” to “challenges” merely for force.
- A double negative may express deliberate understatement. Remove it only when the intended degree survives; partial usefulness is not uselessness.

Purposeful negation can delimit a contribution or contrast competing interpretations. Keep both sides grammatically parallel and supported. In a mechanism contrast, evidence favoring one explanation does not automatically eliminate the other. Avoid inserting a stock contrast where the author has made no such distinction. Preserve necessary hedges; clarity comes from locating uncertainty precisely, not from sounding confident.

## 4. Compression with attachment and chronology intact — rule 13

After the argument is stable, inspect removable framing and compressible syntax. Do not run global phrase replacements. For example, “the fact that” may disappear after a reporting verb; a reason can often use because; a concession can use although; a vague manner phrase can use a precise adverb. Check that the shorter construction retains the same attribution and logical relationship. Deleting “there is no doubt” may be better than retaining a shorter unsupported certainty marker.

Reduce a relative clause to an appositive or participial phrase only when its referent, restriction, time, and modality remain clear:

- “The detector, which was mounted above the chamber, recorded the emission” can become “The detector, mounted above the chamber, recorded the emission.”
- “The detector, which will be mounted above the chamber, …” cannot safely lose will through the same edit: planned installation is not completed installation.
- A restrictive clause can sometimes be reduced too, but keep the subset-defining information and punctuation. Reduction is not permission to delete a condition.

Combine short sentences that repeat the same subject or distribute one relationship across fragments of thought. Preserve each action's object and chronological order. If a model was calibrated and predictions were validated, do not compress this to a sentence claiming the model itself was validated. Do not imply that calibration and validation used the same data unless that is stated. Retain separate sentences when a shift of actor, evidence, or qualification is easier to follow that way.

## 5. Sentence hierarchy and rhythm — rule 14

Inspect a run of sentences, not a single and or which. Repeated main-statement-plus-added-clause patterns may flatten reasons, qualifications, and findings into equal-weight assertions. The repair is to recover their relationship, not merely exchange conjunctions or impose varied sentence lengths.

| Relationship to communicate | Useful structure | Limit |
|---|---|---|
| One decisive observation or a change of topic | A direct independent sentence | Brevity does not justify dropping a qualifier |
| Two closely related assertions of similar weight | Coordinated clauses or a semicolon | A semicolon is not inherently more scholarly than but |
| A condition, reason, or concession governing a finding | A subordinate clause plus a main clause | Do not turn coexistence into causality |
| A condition that readers need before the main point | A short introductory condition followed by the finding | Avoid long delayed-main-point openings that overload memory |
| Supporting detail within one proposition | A relative clause, participial phrase, or appositive | Check its grammatical attachment and semantic scope |

“Although the reference signal remained stable, the sample signal declined” makes the contrast explicit only if it is intended. “After normalization, the sample signal declined” gives an order of analysis; it does not say normalization caused a physical decline. Read the passage aloud or simulate its pacing if monotony remains, but change structure only where meaning or readability benefits.

Do not count relative clauses as coordinate clauses, classify every long sentence as complex, or require three clauses for complexity. Clause function matters more than the label. See [grammar and punctuation §4](grammar-and-punctuation.md#4-clause-boundaries-diagnose-before-choosing-a-repair) for boundaries. Rearranging a claim does not validate it: a p-value alone cannot establish the truth of a scientific hypothesis.

## 6. Parallelism: test each member against its shared frame — rule 15

Find the common stem and attach each coordinated item to it separately. Choose matching grammatical functions at the same logical level: nouns, gerund phrases, infinitives, or clauses. An action and its explanation need not be falsely promoted to equal list items.

“The protocol involves filtering the signal, estimating drift, and removal of outliers” is clearer as “The protocol involves filtering the signal, estimating drift, and removing outliers.” Alternatively use parallel action nouns if that better fits the surrounding prose. Do not call every noun ending in -tion a gerund or treat gerund subjects as inherently informal.

Place paired markers immediately before the units they coordinate: both…and, either…or, neither…nor, not…but, and not only…but also. Compare “The assay both detects the target and estimates its concentration” with a malformed pairing of a verb phrase and a full clause. Moving the markers or recasting both branches can repair the structure. Preserve which actor performs each action; do not assign both to we merely to make them parallel.

For a shared article, preposition, or infinitive to, test whether it works for every item. “At low, intermediate, and high pressure” shares at; repeating at for each item is also possible. Repeat the word when it clarifies grouping or when a different complement requires it. Partial repetition is not automatically ungrammatical, but unexplained asymmetry may confuse the list's boundaries. Preserve required differences such as “between groups and within each group.”

Check semantic comparisons separately from grammatical symmetry: compare quantities with quantities under the intended conditions. A gerund-led comparison is not necessarily faulty; a direct comparison may simply be clearer. Do not delete the observation or attribution boundary while making it more direct. Keep genuinely parallel terminology stable across sentences, lists, and headings; meaningful parallelism need not be varied for rhythm.

## 7. Attachment: locate the intended scope before moving words — rule 16

For only, almost, nearly, negation, and condition phrases, identify exactly what they limit. “Only two sensors detected the pulse” limits the sensors; “The sensors detected only two pulses” limits the pulses. Similar-looking rearrangements can change the result. Ask when context cannot settle the scope.

For a relative clause, identify the intended noun phrase or proposition and any competing plausible antecedent. Moving the clause next to its referent or repeating that referent can resolve ambiguity. Nearest-noun attachment is a diagnostic, not an absolute rule: which can refer to the preceding clause as a whole. In “The detector saturated, which prevented peak estimation,” the consequence concerns saturation, not a property of the detector. Recast as two sentences if the relationship is unclear; do not mechanically attach which to the nearest noun.

Locate the subject and main predicate around a long interruption. A movable time or condition phrase can often go before the subject or after the predicate. Keep a restrictive modifier attached to the entity it identifies. Short parenthetical remarks may remain between subject and verb when they are easy to process. After shortening a long subject or moving a phrase, recheck agreement, population, temporal order, and which claims inherit the condition. Also recheck [opening modifiers](grammar-and-punctuation.md#6-opening-modifiers-find-the-actor-or-recipient-again-after-editing).

When moving a modifier out of a reporting phrase, also preserve who vouches for the description. For example, “The report described the specimen as porous” attributes porosity to the report. “The porous specimen was described in the report” presents porosity as the writer's own premise. Keep the attribution boundary unless the manuscript supplies independent support for that change.

## 8. Tense and information emphasis — rules 17–18

Choose tense by the sentence's job, then check consistency within that job. In an abstract, background may use present, completed work past, and the present interpretation present with calibrated modality. A paper can present an approach now although the authors developed it earlier. Discussion can move legitimately between past observations and present interpretation; changing to present does not make a finding universal.

In a literature review, distinguish a past research event (“The earlier study measured …”), the argument currently available in a publication (“That article argues …”), established knowledge, and a continuing body of work (often present perfect). A dated research event usually takes past tense; a citation's date alone does not require every verb to be past. Preserve the source's claim strength, attribution, and chronology. Avoid empty “well known” assertions as substitutes for evidence.

For information order, identify what readers already have and what they should retain. A familiar topic often provides the opening; a result, gap, or consequential qualification can take the ending. The opening can also foreground a crucial result or establish a contrast or condition. Neither position has automatic priority over clarity.

Teaching alternatives, assuming all conditions have already been established:

- Continuing a discussion of sensor R: “Sensor R reduced the median timing error by 8 ms.”
- Opening a result-focused summary: “An 8 ms reduction in median timing error was obtained with sensor R.”

Choose using the preceding and following sentences, not a universal active-voice or end-focus rule. Restore the comparator and test conditions if they are not recoverable from context. Avoid tacking an unrelated detail onto the ending, but keep an essential qualifier close enough to prevent overreading. Move a figure citation only with the result it supports.

Apply the same question at paragraph and section scale: does the ending leave the reader with the supported point? An Introduction may end with its research question; a Discussion or Conclusion may end with a bounded contribution or justified next step. This is a placement option, not a demand for a grand claim, a future-work promise, or identical paragraph endings. Recheck meaning after all reordering, using [review and delivery](review-and-delivery.md) only to the extent the task calls for it.
