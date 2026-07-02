---
name: mystyle
description: Draft or revise academic finance papers in Snehal Banerjee's voice — structure, tone, and phrasing calibrated to his recent top-tier publications (JF, JFE, RFS, JPE, Management Science; 2018 onward). Invoke this skill whenever the user asks you to write, rewrite, tighten, translate into "his voice", or continue any section of an academic paper — introduction, related literature, model setup, equilibrium analysis, results/propositions, discussion of implications, extensions, or conclusion. Also invoke when asked to write an abstract, response to referees, or slide narrative in the same voice.
---

# mystyle — Snehal Banerjee's academic writing voice

This skill is calibrated on the introductions, model sections, and conclusions of Banerjee's recent top-tier papers (weighted toward JF, JFE, RFS, JPE, Management Science publications from 2018 forward). It captures the structural, rhetorical, and sentence-level patterns that define his voice as a theoretical finance author, most of it written jointly with co-authors (Breon-Drish, Davis, Gondhi, Smith, Marinovic, Szydlowski, Kremer, Kaniel, Green, Graveline).

Use this skill any time the user asks you to produce or revise prose that should read as his. Do not produce generic "academic writing" — hit the specific moves below.

---

## 1. The one-paragraph summary

The voice is: **first-person plural, measured, mechanism-first, and grounded in named channels.** Papers open by contrasting a standard intuition or stylized empirical fact with a puzzle the existing literature cannot resolve, then propose a stylized model, walk the reader through the mechanism using two or three named "channels" or "effects" that interact, and close with a compact list of "distinctive" or "novel" implications and an unshowy conclusion. Sentences are medium-length, connective-adverb-rich, and almost never rhetorical. There is essentially no ornament, no theatrics, no metaphor beyond the standard finance vocabulary (feedback, crowd in/out, level the playing field, agree to disagree). The paper is a chain of clean logical claims, each one earned.

---

## 2. Structural template for a full paper

Use these section names and this order unless the target venue dictates otherwise. Section numbers are Arabic for JFE / RFS / Management Science / JPE style, and Roman (I, II, …) for JF style — mirror the target journal.

1. **Introduction** (see §3 below — the most templated section)
2. **Related Literature** — always its own section (never buried in the intro); usually §2 or §I
3. **Model** or **Model Setup** — labeled subsections: *Payoffs*, *Preferences and information*, *Signals* / *Information structure*, *Timing*, *Discussion of Assumptions*
4. **Equilibrium** — definition, then existence/uniqueness, then characterization
5. **Analysis** / **Implications** / **Empirical implications** — the results section, structured around named mechanisms
6. **Extensions** — often §5 or §6, with each extension labeled as its own subsection
7. **Conclusion** or **Concluding Remarks** — brief, recaps main mechanism, then labeled subsections gesturing to extensions and future work
8. **Appendix A: Proofs** — every proposition/lemma gets a proof, ordered by the paper
9. **Appendix B / Internet Appendix** — extensions, robustness, alternate specifications

## 3. The introduction template (highest signal — imitate closely)

His introductions almost always follow this eight-move sequence. Each move gets one to three paragraphs.

**Move 1 — Motivating stylized fact / empirical puzzle / policy quote.** Open with either (a) a stylized empirical fact with citations, (b) a puzzle across recent evidence that varies by setting, (c) a regulatory or policy statement (occasionally an epigraph — see the Keynes and Warren Buffett epigraphs in the 2018 RFS and 2022 RFS papers), or (d) a common intuition to be challenged.

> *Example (BBS 2025, JF):* "Since Hayek (1945), it has been recognized that prices aggregate information that is dispersed across the economy and convey it to real decision makers."

> *Example (BDG 2018, RFS):* "Financial regulations often change the information environment in an effort to reduce market uncertainty."

> *Example (BDG-coord 2026, JPE):* "Survey forecasts exhibit significant deviations from rational expectations. Using regressions of forecast errors on forecast revisions, Coibion and Gorodnichenko (2012, 2015) show that consensus forecasts exhibit underreaction for macroeconomic variables, while Bordalo, Gennaioli, Ma, and Shleifer (2020) show that individual forecasts tend to exhibit overreaction."

**Move 2 — Point out what the existing literature misses.** One sentence identifying the gap, usually with "Yet …" or "However …" or "In contrast, …" or "existing … is largely silent on …".

> *Example (BMS 2024, JF):* "Yet existing theory is largely silent on how such voluntary disclosures affect trade based on private information and, conversely, how such information affects a firm's propensity to disclose."

**Move 3 — "We develop / propose / consider a model in which …"** One or two sentences. Always active voice, first-person plural. State the setting and the twist.

> *Templates:*
> - "We develop a model in which …"
> - "We propose a framework in which …"
> - "To study how X, we develop a model where …"
> - "We consider a setting in which …"

**Move 4 — Punchline / main result.** One paragraph stating the headline finding. Usually contains the key contrast with the existing view.

**Move 5 — "Model and Intuition" / "Overview of Model and Mechanism".** A boldfaced labeled subsection walking through the model informally with the intuition. This is where the *named channels* first appear. Two to four paragraphs.

Use boldface run-in labels for these mini-sections. Signature labels he uses:

- **Model.** / **Model Overview.** / **Model and Intuition.** / **Model Overview and Main Trade-off.** / **Overview of Model and Mechanism.**
- **Intuition.**
- **Setup.**
- **Payoffs.** / **Preferences and information.** / **Timing.**

**Move 6 — "Implications." (labeled subsection).** State three to five numbered implications ("First, … Second, … Third, …"). Each implication typically pairs a formal result with an empirical fact it explains or a policy interpretation it delivers.

> *Example (BBS 2025, JFE):* "The above economic mechanisms have several empirically-relevant implications. First, as discussed above, our model jointly explains why belief dispersion can be negatively related to equity returns but positively related to debt returns. … Second, for firms far from default, we find that higher leverage is associated with higher expected excess debt returns … Third, the above intuition implies that these relations weaken, and can even reverse, when …"

Signature labels that mark these blocks: **Implications.**, **Empirical implications.**, **Policy implications and Extensions.**, **Welfare.**, **Return dynamics.**, **Risk sharing and investor utility.**

**Move 7 — Roadmap / Overview.** One paragraph starting "The rest of the paper is organized as follows." Every section named, no editorializing. Proofs are always relegated to the appendix with a closing sentence like "Proofs and extensions can be found in Appendices A and B, respectively."

> *Canonical closer:* "The rest of the paper is as follows. Section 2 briefly discusses the related literature. Section 3 presents the model … Section 7 concludes. All proofs are in Appendix A and the supplemental analysis is in Appendix B."

**Move 8 — Related Literature.** Always its own section (§2 or §I), never absorbed into the intro. Structure: (i) 1–2 paragraphs on the closest 2–4 papers with explicit comparisons ("We view our work as complementary…", "In contrast to …, we allow …"); (ii) grouped citations by theme; (iii) always closes with "We complement this work by …" or "Relative to these papers, our analysis highlights …"

---

## 4. Named-channel decomposition — the signature move

Almost every one of his papers decomposes the mechanism into two or three **named channels** or **effects** whose interaction drives the results. This is the single most identifiable feature of his writing. Adopt it whenever describing a mechanism.

- Introduce each channel with an italicized name inside the sentence where it first appears. Example: "*we refer to this as the fundamental uncertainty channel*."
- Reuse the exact channel name every time thereafter — never paraphrase it later. Consistency is the point.
- Show that the overall effect depends on the *interaction* / *relative strength* / *net impact* of the channels.
- State conditions under which each channel dominates.

Channel names lifted from the corpus (for calibration, not for reuse):

- BDG 2024 (JF): *information effect*, *speculative effect*
- BDG-coord 2026 (JPE): *fundamental uncertainty channel*, *aggregate error channel*
- BMS 2024 (JF): *substitution channel*, *valuation channel*
- BBS 2025 (JF): *cash flow channel*, *nonclimate risk channel*, *climate risk channel*, *risk-sharing channel*, *value of information channel*
- BBD 2022 (RFS): *trading horizon effect*, *impatience effect*
- BDG-DualRole 2025 (RFS): *incentive provision role*, *feedback effect*

Formula for coining a new channel name: `[noun modifier] + channel` or `[noun modifier] + effect`. Prefer *channel* when the mechanism operates through information / valuation; prefer *effect* when it's a behavioral or dynamic force. Two words maximum before "channel"/"effect".

---

## 5. Sentence-level voice

### 5.1 Person, voice, tense

- **First-person plural** ("we") almost everywhere, even when the paper is sole-authored (in the 2011 RFS, use "the article" for a couple of framing moves; otherwise switch to "I" only if the venue forbids "we").
- Active voice throughout. "We show", "We characterize", "We develop", "We build on …", "We consider …", "We derive …".
- Present tense for describing the paper's own claims. Simple past for empirical citations ("Coibion and Gorodnichenko (2012) show …").

### 5.2 Signature connective adverbs (use liberally at sentence starts)

- **Intuitively,** — introduces the mechanism story after a formal statement.
- **Importantly,** — flags what the reader must not miss.
- **Moreover,** — adds a second claim reinforcing the first.
- **Consequently,** / **As a result,** — states the implication.
- **In contrast,** / **In stark contrast,** — sets up the comparison to existing work or a benchmark.
- **Specifically,** / **In particular,** — narrows in.
- **Finally,** — the last item in a list of implications.
- **For instance,** / **For example,** — illustrative case.
- **To fix ideas,** / **To see this,** — opens an informal expository paragraph.
- **In fact,** — sharpens a claim.
- **Analogously,** — parallel construction with a prior mechanism.
- **All else equal,** — comparative statics.

Every one of these is followed by a comma. Do not use bare "However" — use "However," followed by comma, and only sparingly; prefer "In contrast," or "Yet".

### 5.3 Signature verbs and phrases

- "We show that …" — the workhorse.
- "We characterize …" — for results describing a set of equilibria / conditions.
- "We develop a model …" — model introduction.
- "We build on the framework of …" — literature positioning.
- "Our analysis suggests …" / "Our results imply …" / "Our findings are (broadly) consistent with …"
- "This is consistent with the empirical evidence in …"
- "In equilibrium, …"
- "In the benchmark, …"
- "The key insight is that …" / "A key takeaway is that …"
- "Our paper contributes to the literature on …"
- "We view our work as complementary."
- "We leave this for future work." / "We leave a full exploration of such issues to future work."
- "This distinguishes our analysis from …"
- "Our model provides novel / testable predictions on …"

### 5.4 Signature scare-quotes

Introduce informal names in quotes on first use, formalize them, then use the term without quotes thereafter. He does this constantly. Common examples:

- "wishful thinking", "agree to disagree", "crowd in", "crowd out", "level the playing field"
- "green" and "brown" projects, "greenness"
- "curse of knowledge", "curse", "cursed"
- "feedback effect", "feedback effects"
- "worst-case" / "best-case"
- "dismissiveness", "dismissive equilibrium"
- "trading horizon" effect, "impatience" effect

When you invent a term the paper will reuse, put it in quotes on first mention and italicize its name-defining occurrence in the body of the paper.

### 5.5 Hedging vocabulary (calibrated, not weak)

- "tends to", "typically", "generally", "broadly consistent with", "qualitatively similar", "qualitatively unchanged", "robust to"
- "unless", "as long as", "provided that", "when X is sufficiently high / low", "for intermediate values of X"
- "may", "can" — used when the direction of the effect depends on parameters
- Avoid: "clearly", "obviously", "of course", "certainly", "undoubtedly", "it is well-known that" (this last is used, but sparingly — usually replaced with a citation)

### 5.6 Adjectives — pick the technical ones

Frequently used, positively-valenced technical adjectives (safe to use):

- **novel**, **distinctive**, **striking**, **surprising**, **counterintuitive**, **unique**, **stark**, **sharp**
- **tractable**, **stylized**, **parsimonious**, **transparent**
- **efficient**, **informationally efficient**, **welfare-maximizing**

Used but sparingly:

- **important**, **key**, **crucial**, **critical**, **fundamental**

Avoid entirely:

- **very**, **really**, **quite**, **rather** (as intensifiers)
- **massive**, **huge**, **tremendous**
- **fascinating**, **exciting**, **beautiful**, **elegant** (as adjectives for the results — he does not praise his own findings)

### 5.7 Sentence rhythm

- Aim for medium-length sentences (15–30 words). Occasionally a short punch sentence for emphasis ("This is not the case."; "As a result, the two channels can reinforce or offset each other.").
- Use semicolons freely to join tightly-linked clauses.
- Use em-dashes sparingly — only for asides, never for emphasis theatrics.
- Prefer "such that", "so that", "which implies that", "which suggests that" for logical linkages.
- Parenthetical clarifications with "(i.e., …)" and "(e.g., …)" — both with commas after the abbreviation — appear once or twice per paragraph.

### 5.8 Footnotes

His papers are footnote-heavy — typically 10+ footnotes in the introduction alone. Use footnotes for:

- Robustness ("Qualitatively similar results hold when …")
- Defending simplifying assumptions ("We rule this out for parsimony …")
- Related-but-distinct citations ("These results are related to Xie (2023), who …")
- Institutional / empirical detail supporting the motivation
- Referee-anticipating clarifications ("Note that this is distinct from …")

Never use footnotes to lecture, moralize, or hedge philosophically.

---

## 6. The model section

### 6.1 Ordering

1. One-sentence framing: "We consider a model of X in the spirit of Y." (Kyle 1985 and Hellwig 1980 are the two most cited base models.)
2. Boldface labeled subsections in this order: **Payoffs.**, **Preferences and information.**, **Signals.** (or built into Preferences), **Disclosure decision** / **Investment decision** / **Trading**, **Timing.**
3. A separate labeled subsection **Discussion of Assumptions** defending each substantive choice: which assumption is for tractability, which is essential, what the qualitative story would look like if relaxed.
4. **Equilibrium** as its own section: definition, existence/uniqueness lemma, then characterization.

### 6.2 Notation defaults

Adopt these unless the setting forces otherwise:

- Continuum of investors indexed by \(i \in [0,1]\).
- CARA utility with risk aversion \(\gamma\) or risk tolerance \(\tau\).
- Normal priors: \(v \sim N(\mu_v, \sigma_v^2)\) or with precision notation \(v \sim N(\mu_v, 1/\tau_v)\).
- Private signal \(s_i = v + \varepsilon_i\), public signal \(s = v + \eta\).
- Price \(P\), demand \(D_i\), aggregate/consensus action \(K = \int k_j\, dj\).
- Noise trade / liquidity trade \(z \sim N(0, \sigma_z^2)\).
- Tilde over random variables when the venue conventions (JF, older JFE) use it; drop tildes for newer JFE, RFS, JPE, MS.

### 6.3 Discussion-of-assumptions template

For each assumption:

1. State the assumption in one sentence.
2. Motivate it: is it standard? Simplifying? Substantive?
3. State how the analysis would change without it, gesturing to an appendix or footnote where applicable.
4. If it's for tractability, say so explicitly: "We assume X for analytical tractability" or "for parsimony".

---

## 7. Results / analysis section

Every formal result gets the same treatment:

1. **Proposition / Lemma / Corollary N.** [Formal statement.]
2. **Proof.** See Appendix A. (Never inline unless a short one-liner.)
3. Interpretive paragraph opening with **Intuitively,** or **To see this,** explaining the mechanism in words.
4. If applicable: comparative statics — "The effect increases in X, decreases in Y, and is hump-shaped in Z."
5. If applicable: link to a named channel — "This reflects the *substitution channel* dominating the *valuation channel*."
6. If applicable: an empirical or policy interpretation — "This is consistent with the evidence in …" or "This suggests that regulators should …"

Results are stated cleanly. The paper never says "the surprising result is …" — the surprise, if any, comes from the contrast the reader draws with the benchmark.

---

## 8. Empirical implications section

Structured as a bulleted or numbered list of testable predictions. Each prediction is:

- one sentence stating the sign of a relationship;
- followed by a sentence tying it to existing empirical evidence (either "consistent with X" or "novel prediction not yet tested");
- rarely followed by a sentence proposing how one might test it ("A natural approach is to regress … on …").

Do not overpromise. When existing evidence is mixed, say "the evidence is mixed" and cite both sides.

---

## 9. Related-literature section

- Always its own labeled section (§I / §2 or occasionally §I.A within a Background section).
- Opens with a one-sentence positioning: "Our paper contributes to two strands of literature: X and Y."
- Group papers by strand, not chronologically.
- For each strand: name the two or three closest papers, explain what they do, then explain the incremental contribution. Standard phrasing: "The most closely related papers are X and Y", "We view our work as complementary", "In contrast to X, we …", "Relative to these papers, our analysis …", "We complement this work by …"
- Do not review the entire literature — the section is a positioning exercise, not a survey.
- Use grouped footnote citations for broader strands.

---

## 10. Conclusion

Follow this compact template:

1. Two-sentence recap: "We develop a model of X. We show that …"
2. Restate the main mechanism in a single paragraph.
3. Optional: labeled subsections gesturing at open questions — **Generalized cost functions.**, **Public information.**, **Policy implications and welfare.**, **Extensions.**
4. Close with future-work forward-pointing: "We leave this for future work" or "We view this as a promising direction for further research".

The conclusion is short (rarely more than two pages typeset). It never dramatizes, never restates the abstract, and never adds new arguments.

---

## 11. Abstract style

- One paragraph, 100–160 words.
- First sentence: "We develop / study / analyze …" plus the setup.
- Middle: two or three sentences stating the main results, using "We show that …", "We find that …", "We characterize …".
- Last one or two sentences: implications or extensions.
- No first-person plural bias against "the model" — "The model implies …" and "We show …" are both fine.
- No citations in the abstract.

Example rhythm to emulate:

> *BDG 2024 (JF) abstract:* "The psychology literature documents that individuals derive current utility from their beliefs about future events. We show that, as a result, investors in financial markets choose to disagree about both private information and price information. When objective price informativeness is low, each investor dismisses the private signals of others and ignores price information. In contrast, when prices are sufficiently informative, heterogeneous interpretations arise endogenously: most investors ignore prices, while the rest condition on it. Our analysis demonstrates how observed deviations from rational expectations (e.g., dismissiveness, overconfidence) arise endogenously, interact with each other, and vary with economic conditions."

---

## 12. Example bank — sentences to model on

These are direct extracts from the top-tier recent papers. Use them for tone and phrasing calibration; do not paste verbatim into new work.

### 12.1 Opening / motivation

> "Since Hayek (1945), it has been recognized that prices aggregate information that is dispersed across the economy and convey it to real decision makers." (BBS 2025, JF)

> "Financial regulations often change the information environment in an effort to reduce market uncertainty." (BDG 2018, RFS)

> "Voluntary disclosures by firms account for nearly two-thirds of the return variation created by firm-level public announcements (Beyer et al. (2010))." (BMS 2024, JF)

> "The standard approach in economics assumes that market participants have rational expectations and learn efficiently from the information in prices. Yet there is ample evidence that people do not behave this way …" (BDG 2024, JF)

> "Algorithmic trading is transforming financial markets." (BS Q-learning, wp)

> "The impact of heterogeneous investor beliefs on asset prices is a foundational question in financial economics, yet the empirical evidence on this relation is strikingly different across stock and bond markets." (BBS 2025, JFE)

### 12.2 Gap statement

> "Existing analyses focus on the extent to which prices reflect information about future cash flows and interpret non-cash-flow variation in prices as noise that needs to be filtered out by decision makers." (BBS 2025, JF)

> "Yet existing theory is largely silent on how such voluntary disclosures affect trade based on private information …" (BMS 2024, JF)

> "However, these models are usually unable to explain the variation in interpretations across investors and over economic conditions without assuming exogenous heterogeneity across investors." (BDG 2024, JF)

### 12.3 Model introduction

> "We develop a model in which a firm's manager can voluntarily disclose to privately informed investors." (BMS 2024, JF)

> "To study feedback effects when managers learn about discount rates from prices, we develop a model in which a firm's stock price conveys information about both future cash flows and investors' risk exposures." (BBS 2025, JF)

> "We propose a framework in which individuals, who exhibit 'wishful thinking,' face uncertainty about the precision of a public signal and choose a subjective interpretation to maximize their anticipatory utility." (BDG-coord 2026, JPE)

> "We consider a setting where investors who have dispersed information about a firm's cash flows trade these securities with liquidity, or noise, traders (e.g., as in the noisy RE model of Hellwig, 1980)." (BBS 2025, JFE)

### 12.4 Intuition / mechanism

> "Intuitively, when the price is more responsive to information about investment opportunities, it can become a noisier measure of managerial effort, which makes it more difficult for the principal to incentivize the manager." (BDG-DualRole 2025, RFS)

> "To see how, first consider a setting in which there are no strategic considerations or externalities (i.e., ρ = γ = 0). In this case, each individual who engages in wishful thinking has a tendency to over-estimate the precision of the public signal since this leads to higher perceived accuracy and, consequently, higher anticipatory utility — we refer to this as the *fundamental uncertainty channel*." (BDG-coord 2026, JPE)

> "Believing that others are less informed has two opposing effects on an investor's anticipatory utility. On the one hand, this implies that the price is less informative about payoffs, which increases the investor's perceived uncertainty and reduces her anticipatory utility. We refer to this as the *information effect*. On the other hand, when others are less informed, the perceived trading gains from speculating against them is higher, which increases anticipatory utility. We term this the *speculative effect*." (BDG 2024, JF)

### 12.5 Implications / findings

> "First, our model generates underreaction in consensus forecasts and overreaction in individual forecasts when private information is sufficiently precise, even in the absence of strategic considerations and externalities. This distinguishes our mechanism from models in which such results are driven by strategic considerations …" (BDG-coord 2026, JPE)

> "In stark contrast to the costly disclosure benchmark, the likelihood of disclosure can decrease with liquidity, and the stock can trade at a premium relative to expected cash flows conditional on nondisclosure." (BMS 2024, JF)

> "Our analysis demonstrates that one must identify the underlying friction driving nondisclosure to understand the relation between voluntary disclosure and market outcomes." (BMS 2024, JF)

### 12.6 Contrast with existing work

> "In contrast, when the manager chooses investment to maximize the future share price, non-cash-flow variation in prices conveys useful information about the project's discount rate." (BBS 2025, JF)

> "Relative to these papers, our analysis highlights how investor information affects both investment efficiency and contracting efficiency, and how the interaction between these affects firm value and decisions." (BDG-DualRole 2025, RFS)

> "In contrast to many existing explanations, our model provides a common mechanism to explain why we observe overreaction in individual forecasts for some settings, but underreaction in others." (BDG-coord 2026, JPE)

### 12.7 Related literature transitions

> "The most closely related papers are Brunnermeier and Parker (2005), Caplin and Leahy (2019) and Banerjee et al. (2024)." (BDG-coord 2026, JPE)

> "We view our analysis as complementary to this earlier work." (BBS 2025, JFE)

> "We complement this work by focusing on how a firm's voluntary disclosure decision endogenously leads to non-normal investor beliefs …" (BMS 2024, JF)

### 12.8 Roadmap

> "The rest of the paper is as follows. The next section briefly discusses the related literature. Section 3 presents the model, and Section 4 characterizes the equilibrium … Section 7 concludes. All proofs are in Appendix A." (BS SPAC 2024, JFE)

> "The rest of the paper is organized as follows. Section I reviews the related literature. Section II presents the model and discusses our assumptions … Section VII concludes. Proofs and extensions can be found in Appendices A and B, respectively." (BMS 2024, JF)

### 12.9 Discussion of assumptions

> "We rule it out for parsimony." (BMS 2024, JF)

> "While the lower bound is a necessary technical assumption for our analysis, a natural interpretation of such restrictions on the set of beliefs is that they arise from …" (BDG-coord 2026, JPE)

> "The essential assumption that lends tractability to our analysis is that the manager has incremental information relative to the market; qualitatively similar results hold when the manager's signal is noisy." (BMS 2024, JF)

### 12.10 Conclusion openings

> "We develop a model in which investors who experience anticipatory utility choose how to interpret the information available to them before trading in financial markets. We show that wishful thinking endogenously gives rise to a rich set of behavior that is consistent with existing empirical evidence, while providing new insight into how such behavior varies with economic conditions and context." (BDG 2024, JF)

> "We develop a model of research by a strategic trader that captures two important features: research is dynamic and probabilistic." (BBD 2022, RFS)

> "Standard voluntary disclosure models assume that investors do not have access to private information. We show that this assumption is an economically important restriction, and relaxing it has novel implications." (BMS 2024, JF)

### 12.11 Future work

> "We leave a model that incorporates both approaches for future work." (BDG-coord 2026, JPE)

> "It would be interesting to explore the effect of richer information acquisition technologies on equilibrium market dynamics." (BBD 2022, RFS)

> "Our paper is an early step in exploring the implications of research and information acquisition dynamics on trading a market behavior, and suggests a number of natural avenues for future research." (BBD 2022, RFS)

---

## 13. Anti-patterns — do not write like this

If you catch yourself producing any of the following, revise:

- Long sentences with three subordinate clauses that lose the reader. Break them.
- Rhetorical questions in the body ("But is this really the case?"). Use them at most once in the intro, and only in a specific setup-a-question moment.
- Chatty transitions: "So", "Now", "Well", "Let's", "It's worth noting that". Replace with "In particular,", "Specifically,", "Note that,".
- First-person singular in a co-authored paper. Always "we".
- Praise for your own results: "Our striking finding is …", "Remarkably, we find …", "Surprisingly, we obtain the beautiful result that …". Cut the adverb; let the reader be surprised.
- Editorializing about the literature: "A common but misguided view is …", "Prior work has failed to appreciate …". Instead: "Existing work has focused on …, which abstracts from …".
- Bulleted lists inside the intro. Introductions are always continuous prose. Bulleted lists are fine in later sections (welfare decomposition, list of assumptions, empirical predictions) but not in the intro.
- "In this paper, we …" as the opening line. Skip it — start with the substantive claim.
- "It goes without saying", "needless to say". Just say it or don't.
- Overuse of "very", "really", "quite". Delete these intensifiers on a second pass.

---

## 14. When drafting, follow this checklist

Before returning the draft, verify:

- [ ] Opening paragraph motivates with a stylized fact / puzzle / policy quote, not with "In this paper we …".
- [ ] There is at least one boldface labeled run-in subsection in the intro (**Model.**, **Intuition.**, **Implications.**, **Overview.**).
- [ ] The mechanism is decomposed into at least two named channels or effects, each italicized on first appearance, then reused verbatim.
- [ ] "We show that …" or "We characterize …" appears in the first result paragraph.
- [ ] Contrast with existing work is explicit — at least one "In contrast, …", "Relative to …", or "We complement …".
- [ ] The word "Intuitively," appears at least once (as a paragraph opener).
- [ ] Every formal claim uses first-person plural.
- [ ] No unhedged causal claims — "may", "can", "tends to", "under sufficient X" appear where the direction depends on parameters.
- [ ] No triumphant adjectives about own results ("beautiful", "remarkable", "amazing").
- [ ] The roadmap paragraph names every section.
- [ ] Related literature is a separate section, positions against 2–4 closest papers by name, groups the rest.
- [ ] Model section has a **Discussion of Assumptions** subsection.
- [ ] Every proposition is followed by "**Proof.** See Appendix A." and an "Intuitively, …" paragraph.
- [ ] Conclusion recaps the mechanism in a paragraph, gestures at extensions, ends with future work.

---

## 15. Genre defaults

- Journal target: assume JF, JFE, RFS, JPE, or Management Science unless told otherwise. Use LaTeX. Two-sided document, numbered propositions, numbered equations.
- Length: intros are 5–8 typeset pages. Related lit 2–4. Model 4–6. Analysis 8–14. Conclusion 2–3. Appendix as long as it needs to be.
- Reference style: parenthetical author-year, with "e.g.," inside parens when grouping ("(e.g., Grossman and Stiglitz (1980))"). Never Vancouver-style numbered refs.
- Equation numbering: (1), (2), … right-aligned. Reference equations as "equation (5)" or just "(5)".
- Proposition/Lemma numbering: start over each section (Proposition 1 in §3, Proposition 1 in §4) *only if* the venue prefers it; otherwise number continuously (Proposition 1, 2, 3, …).

---

## 16. When the user asks for something short

- **Abstract**: use §11.
- **Cover letter to editor**: keep to three short paragraphs — (1) what the paper does in one sentence, (2) the main contribution in one paragraph, (3) authorship / conflict-of-interest disclosure and closing.
- **Response to referee**: address each point in the referee's order, quote the referee in italics, respond in plain text opening with "We thank the referee for this comment." or "We agree with the referee and have …". Do not defend if the referee is right; concede and revise.
- **Slide narrative**: one takeaway per slide, headline-style titles (not descriptive titles), short bullet substance.

---

## 17. Files this skill was calibrated on

Weighted heavily (recent top-5 finance + JPE + MS):

- Banerjee, Davis, Gondhi (2026), *Journal of Political Economy*, "Strategic Wishful Thinking"
- Banerjee, Davis, Gondhi (2026), *Management Science*, "Information Provision and the Curse of Knowledge"
- Banerjee, Davis, Gondhi (2025), *Review of Financial Studies*, "Incentivizing Effort and Informing Investment"
- Banerjee, Breon-Drish, Smith (2025), *Journal of Finance*, "Feedback Effects and Systematic Risk Exposures"
- Banerjee, Breon-Drish, Smith (2025), *Journal of Financial Economics*, "Asymmetric Information, Disagreement, and the Valuation of Debt and Equity"
- Banerjee, Davis, Gondhi (2024), *Journal of Finance*, "Choosing to Disagree"
- Banerjee, Marinovic, Smith (2024), *Journal of Finance*, "Disclosing to Informed Traders"
- Banerjee, Szydlowski (2024), *Journal of Financial Economics*, "Harnessing the Overconfidence of the Crowd"
- Banerjee, Breon-Drish (2022), *Review of Financial Studies*, "Dynamics of Research and Strategic Trading"
- Banerjee, Breon-Drish (2020), *Journal of Financial Economics*, "Strategic Trading and Unobservable Information Acquisition"
- Banerjee, Davis, Gondhi (2018), *Review of Financial Studies*, "When Transparency Improves…"

Lightly sampled for continuity: Banerjee (2011, RFS), Banerjee-Graveline (2013, JF), Banerjee-Green (2015, JFE), BBKK (2023, JET), and current working papers.

---

## 18. If the user gives you their draft

When asked to revise their prose into this voice:

1. First pass — structure. Confirm the eight-move introduction structure. If any move is missing, add it. If moves are in the wrong order, reorder.
2. Second pass — sentence rhythm. Break long sentences. Insert the connective adverbs at natural breaks.
3. Third pass — mechanism naming. Identify the mechanism and name the channels. Italicize on first use, then repeat verbatim.
4. Fourth pass — verbs. Convert "This paper shows …" to "We show that …". Convert "It is shown that …" to "We show that …". Convert past-tense claims about the paper to present tense.
5. Fifth pass — hedging. Verify that comparative-statics claims are hedged with "when X is sufficiently …".
6. Sixth pass — adjective audit. Cut praise adjectives. Confirm no "very", "really", "quite".
7. Seventh pass — checklist §14.

Show the user the revised draft, then briefly note what changed (three to five bullet points, no more).
