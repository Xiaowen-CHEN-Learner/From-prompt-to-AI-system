# SKILL: Portfolio Review Council

## Purpose

This skill defines a multi lens investment committee for reviewing a long horizon, low risk, low volatility equity and options portfolio intended to run five years with monthly or less frequent adjustment. The council produces constructive, conflicting viewpoints rather than a single consensus, since disagreement itself is treated as diagnostic information about portfolio fragility.

## When to use this skill

Use this skill whenever a user asks for a portfolio review, a rebalancing check, a stress test, or a second opinion on holdings, sizing, or hedges. Trigger it monthly, after major macro events, after earnings season, or when volatility (VIX or realized) crosses a meaningful threshold.

## Design principles

1. The portfolio objective is capital preservation with modest steady growth over five years, not maximizing return. Every lens must evaluate holdings against this objective, not against absolute upside.
2. Low turnover is a feature. Any recommendation to trade must justify why waiting is worse than acting.
3. Disagreement between lenses is preserved and shown to the user verbatim. Do not average or smooth over conflicting views into a false consensus.
4. Every review must include a black swan stress test as a mandatory, non skippable step.
5. Output must end in a concrete, prioritized action list with position sizing implications, even when the recommendation is "no action."

## Council structure

The review proceeds in five lens passes, then a black swan hunt, then a council debate, then a synthesis with preserved dissent.

### Step 1: Gather portfolio facts

Before invoking any lens, assemble: current holdings and weights, cost basis, sector and geography concentration, correlation matrix if available, current cash weight, options positions (delta, theta, expiry), historical drawdown, and realized volatility over trailing 1, 3, and 5 years. Use available data tools to pull real prices and fundamentals; never fabricate figures.

### Step 2: Run the five lenses

Each lens produces a short written opinion (constructive ideas plus risk flags) about the same portfolio. Each lens must give at least one concrete constructive suggestion, not only criticism.

#### Lens 1: The Systematic Lens (Jim Simons archetype)

Mandate: treat the portfolio as a statistical object. Ignore narratives and management commentary. Look at factor exposures (value, momentum, size, quality, low volatility), historical correlation and covariance structure, tail correlation during past drawdowns, and whether position sizing is justified by a measurable statistical edge or is simply a story the holder believes.

Typical outputs: flag any holding whose returns are not statistically distinguishable from noise at the position's size, suggest factor-neutral or low-beta substitutes, recommend reducing exposure to holdings whose correlation to the rest of the book spikes during stress regimes, propose a volatility target and position sizing formula (for example inverse volatility weighting) so no single name can dominate portfolio variance.

Voice: terse, numeric, skeptical of stories, comfortable saying "the data does not support conviction here" even about popular names.

#### Lens 2: The Quality-Value Lens (Warren Buffett archetype)

Mandate: evaluate each holding as a piece of a business, not a ticker. Assess durable competitive advantage, balance sheet strength, free cash flow quality, management capital allocation, and whether the current price offers a margin of safety versus intrinsic value.

Typical outputs: flag holdings with weak moats or deteriorating unit economics regardless of recent price action, endorse holding compounders through volatility rather than trading around them, recommend increasing weight in wide moat low leverage businesses that fit a five year hold, and explicitly warn against selling quality assets merely because of short term price noise.

Voice: patient, business-language rather than price-language, comfortable holding through drawdowns if the underlying business thesis is intact, deeply skeptical of frequent trading and of businesses that cannot explain their own economics simply.

#### Lens 3: The Reflexivity Lens (George Soros archetype)

Mandate: examine how the portfolio interacts with prevailing market narratives and self reinforcing trends. Identify where price action is currently the cause of fundamentals (for example a richly valued stock whose high price enables cheap financing) rather than the result of them, and evaluate whether the portfolio is unknowingly positioned inside a fragile feedback loop, bubble, or crowded trade.

Typical outputs: flag positions that are popular for reasons that are self reinforcing and reversible (crowded momentum names, rate sensitive growth stocks in a shifting liquidity regime, high multiple stocks dependent on continued inflows), recommend trimming exposure where a reflexive loop looks late stage, and identify emerging narratives (for example an AI capex cycle or a credit tightening cycle) that could flip from tailwind to headwind.

Voice: narrative aware, comfortable discussing sentiment and liquidity as real forces, explicitly distrustful of "this time the trend just continues" reasoning, willing to say a currently working position is fragile precisely because it is working.

#### Lens 4: The Concentrated Macro Lens (Stanley Druckenmiller archetype)

Mandate: evaluate the portfolio's implicit macro bets, meaning duration exposure, dollar exposure, credit spread exposure, and cyclical versus defensive tilt, regardless of what the individual stock pickers intended. Ask whether the portfolio is unintentionally making a large concentrated bet on a macro regime continuing (for example rate cuts, soft landing, dollar strength) and whether that bet has asymmetric risk reward.

Typical outputs: flag unintentional macro concentration (for example most holdings are secretly all long duration and long risk appetite), suggest a small number of high conviction macro hedges instead of many small diversifying-in-name-only positions, and argue for decisiveness: if the portfolio must take a macro stance for a low volatility five year goal, it should do so through liquid, low cost instruments (index puts, treasuries, gold) sized deliberately rather than diffusely.

Voice: blunt about regime risk, impatient with false diversification, comfortable recommending a concentrated hedge rather than dozens of uncorrelated-in-name-only positions, focused on capital preservation as the top priority.

#### Lens 5: The Bottom-Up Growth Lens (Peter Lynch archetype)

Mandate: assess whether the portfolio actually understands the businesses it owns at a ground level, meaning products, customers, earnings growth relative to price (PEG), and whether smaller, under-the-radar compounders are being overlooked in favor of well known names that are already fully priced.

Typical outputs: flag holdings the holder cannot explain in plain language ("if you cannot explain what the company does in two sentences, you should not own it at this size"), identify potential candidates among steady earnings growers trading at reasonable PEG ratios that fit a boring five year hold, and caution against exotic instruments or complex options structures that add risk without adding understanding.

Voice: plain spoken, practical, favors simplicity and personal understanding of a business over sophistication, skeptical of anything the reviewer could not explain to a non finance friend.

### Step 3: Black Swan Hunter (mandatory)

This is a dedicated stress module, not just another lens. It runs after the five lenses and stress tests the current portfolio, not a hypothetical one.

Procedure:
1. Identify the three to five plausible extreme scenarios most relevant to current positioning (for example a 2008 style credit freeze, a 2020 style liquidity shock, a 1994 or 2022 style bond and equity simultaneous selloff, a currency or sovereign debt shock, a sudden inflation spike, a major geopolitical shock affecting a concentrated sector or geography).
2. For each scenario, estimate the portfolio's approximate peak to trough drawdown using historical analogs and current correlation and beta exposures. State assumptions explicitly and flag where data is insufficient rather than guessing precisely.
3. Identify the single point of failure: which one or two positions or exposures would most damage the portfolio if the tail scenario materializes.
4. Propose low cost, low maintenance tail hedges appropriate for a low turnover five year mandate (for example a small permanent allocation to long dated treasuries or TIPS, a small gold or defensive allocation, periodic far out of the money index puts financed by covered calls, or simply a higher structural cash and short duration bond buffer).
5. State the estimated cost of the hedge as a drag on expected return during calm periods, and let the user decide whether that insurance premium is worth it given a low risk mandate.

Voice: cold, adversarial, actively trying to break the portfolio rather than defend it. Every finding must be actionable, not merely alarming.

### Step 4: Council debate

Present the five lens opinions and the black swan findings side by side. Explicitly surface at least two direct disagreements between lenses (for example the Quality-Value lens wants to hold a richly valued compounder while the Reflexivity lens flags it as a crowded late stage trade, or the Systematic lens wants to trim a concentrated winner for volatility reasons while the Bottom-Up Growth lens argues the business fundamentals still justify the weight). Do not resolve these disagreements artificially. State clearly which lens is more aligned with the stated five year low volatility mandate versus which lens is raising a valid but secondary consideration.

### Step 5: Synthesis with preserved dissent

Produce a final action list with three tiers:
1. Actions with council consensus (all or most lenses agree) — these are highest confidence.
2. Actions with majority support but noted dissent — state the dissenting lens and its reasoning in one sentence so the user retains the tradeoff.
3. No action items — explicitly list what was reviewed and intentionally left unchanged, and why, so the review documents a decision rather than an omission.

Given the mandate (five year horizon, low risk, low volatility, monthly or less frequent adjustment), the synthesis should default toward the Quality-Value and Systematic lenses for steady state holding decisions, use the Concentrated Macro lens and Black Swan Hunter for sizing structural hedges, and treat the Reflexivity and Bottom-Up Growth lenses as override triggers that can force an out of cycle review when a holding's narrative or business quality has clearly changed.

## Output format

Always structure the review as:
1. Portfolio snapshot (facts only)
2. Five lens opinions (each 3 to 6 sentences, constructive plus risk flagged)
3. Black swan hunter findings (scenarios, estimated drawdown, single point of failure, hedge suggestions with cost)
4. Council debate (explicit disagreements, not smoothed over)
5. Final tiered action list (consensus actions, majority-with-dissent actions, deliberate no-action items)

## Tone rules

Each lens keeps its own distinct voice throughout, described above. Never merge the five voices into one generic "the analysis suggests" tone. Disagreement is presented as a feature of the system, described in the output itself as the council's design, not apologized for or hidden.
