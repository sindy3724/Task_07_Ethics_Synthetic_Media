# Limitations: Stress-Testing the Riverbend Ledger Policy

This section describes where the policy would fail. It is not an apology; the point is to say what the policy does and does not guarantee.

## 1. Where a well-intentioned employee would go wrong

- **Misreading "evokes a real person."** Section 7 asks whether a clip "imitates or evokes" a real person. A synthetic voice that happens to sound like a well-known local radio host, or a stock "generic" voice that resembles a staffer, falls into a gray zone. The policy has no objective test for "resembles."
- **The "minor" tools problem.** A reporter might use a built-in AI feature in an editing app (auto-dubbing, voice "cleanup," generative fill) without realizing it counts as synthetic media. The definition excludes "ordinary editing," but the boundary between *noise reduction* and *generative repair* is blurry and changing as tools update.
- **Deadline erosion.** The policy says review cannot be skipped under deadline pressure. In practice, a two-person desk on a breaking story will be tempted to interpret "emergency" loosely, or label something "internal mockup" and quietly publish it.
- **Over-refusal.** Because disagreement defaults to refusal, a cautious editor can block legitimate accessibility or translation uses, leaving readers worse served.
- **Label compliance without comprehension.** Staff can follow the disclosure wording exactly while the audience still skims past it.

## 2. What a bad-faith actor would do that the policy cannot stop

- **An insider acting deliberately** can generate content on a personal device, outside the registry, and publish it under a pseudonym. The policy governs sanctioned activity only.
- **An outsider** can create a fake Ledger-branded clip, or a fake clip of a Ledger reporter. The policy offers *incident response* and a public reporting page, but it cannot prevent creation or guarantee removal.
- **Strip-and-reframe attacks.** Anyone can take our honestly labeled clip, remove the label, and recaption it (the context axis). Our design preferences (in-audio disclosure, self-contained meaning) reduce but do not remove this risk.
- **Provenance laundering.** A bad actor could attach plausible-looking but false provenance claims, or exploit the absence of credentials to cast doubt on a real Ledger recording (the "liar's dividend"). Our own publication of credentials may make the *absence* of them on a genuine clip look suspicious.
- **Consent fraud.** A forged consent form or impersonated staff email could pass a check that relies on documents.

## 3. Where the policy relies on good faith

The policy leans on honesty at four points: the Requester's description of the use, the Approving Editor's written answers to the Section 7 questions, voluntary incident reporting, and staff recognizing tools as "synthetic." There is **no automated enforcement**, no technical block, and no audit mechanism in v1.

Is that a fatal weakness? I think it is an **honest one, but a real one.** Any internal policy governing human behavior relies on good faith; the question is whether the design makes good faith *easier* and bad faith *costlier*. Here it does so modestly: by requiring a named second reviewer, a registry that creates a paper trail, and a no-penalty reporting culture. It does not make violation impossible. A sufficiently motivated insider defeats it.

## 4. Structural weaknesses

- **Small-organization capacity.** A 22-person newsroom may not have a Managing Editor with time to maintain the registry, log consent, and run incident response. The policy could degrade into paperwork that nobody keeps up.
- **Tool churn.** The policy names categories, not products, which helps, but tools and platform behaviors change faster than a 12-month review cycle.
- **The prohibition on satire.** Banning all depictions of real people, including clear parody, protects against abuse but sacrifices a legitimate journalistic and editorial form. I am not confident this is the right trade-off for every newsroom; it is the right one for a trust-dependent local outlet with no legal department.
- **Peripheral dependence on the platforms.** Takedown speed and scope depend on platform responsiveness we do not control.
- **No empirical testing.** The policy has not been tested against an actual newsroom's workflow. Real operational friction (freelancers, remote work, CMS integration) would surface problems I have not anticipated.

## 5. Residual risk after adoption

If the policy were followed perfectly, the Ledger would still face:

1. **Third-party fakes using the Ledger's name or staff's likenesses**: moderately likely, hard to prevent, and damaging to trust.
2. **Stripped or recontextualized copies** of honest clips: likely over time, low-to-moderate harm if designed carefully.
3. **Erosion of audience trust in all audio/video**, including our own genuine recordings, regardless of what we do. This is an environmental risk the policy cannot address.
4. **Slow drift** between the policy's categories and what tools can do.

## 6. What I would change or add next

- An **audit mechanism**: quarterly spot-check of the registry against published output, plus a confidential reporting channel.
- A **sunset clause** requiring the policy to be re-ratified, not just reviewed.
- **Testing with a working journalist** to find friction points before adoption.
- A clearer **operational definition of "resembles a real person."**
- A decision on whether satire should remain flatly prohibited.

## 7. Portability note

I would have written a materially different policy for a political campaign or a marketing team. A campaign's incentives push toward persuasion, so the central problem would be *restraint* rather than process; a marketing team would prioritize talent licensing and brand control over audience trust. What carries over: the principle that disclosure alone is not enough, the need for a named reviewer, the importance of a refusal clause, and incident response. What does not carry over: the specific prohibitions, the consent exception, and the refusal conditions, which depend on the organization's incentives and constraints. Governance in this space is more context-specific than portable.
