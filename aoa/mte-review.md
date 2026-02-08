# Mutual Trading Exemption Review: Articles of Association — BVMA Limited

**Document reviewed:** `aoa/aoa.md` (as amended)
**Date of review:** 8 February 2026
**Purpose:** Assess the Articles of Association against HMRC mutual trading exemption (MTE) requirements, best practice, and leading case law

---

## 1. Legal Framework for the MTE

There is no statutory definition of "mutual trading." The exemption is entirely judge-made, resting on the principle that **a person cannot trade with themselves** and therefore cannot generate taxable profit from transactions with themselves. When individuals form an association to provide services collectively, any surplus from their contributions is not profit — it is merely over-contribution.

### 1.1 The Four Essential Tests

HMRC's guidance (BIM24100–BIM24120) identifies four tests derived from Lord Macmillan's judgment in *Municipal Mutual Insurance v Hills* [1932] 16 TC 430:

| Test | HMRC Reference | Requirement |
|------|---------------|-------------|
| **1. Identity** | BIM24105 | Complete identity between the class of contributors to the common fund and the class of participators in the surplus |
| **2. Return** | BIM24110 | Surplus must return to contributors and **no one else** — no arrangements for it to go to any other person or body |
| **3. Proportionality** | BIM24115 | A reasonable relationship between what each person contributes and what they receive on winding up |
| **4. Control** | BIM24120 | For incorporated bodies, the contributors must **control** the common fund |

All four must be satisfied simultaneously. Failure on any one test is fatal to MTE status.

### 1.2 Key Cases

| Case | Citation | Principle |
|------|----------|-----------|
| *New York Life Insurance v Styles* | [1889] 2 TC 460 (HL) | Foundation: a man cannot trade with himself |
| *Carlisle & Silloth Golf Club v Smith* | [1913] 6 TC 48 | Extended MTE to members' clubs; non-member income (visitors) is taxable |
| *Jones v SW Lancashire Coal Owners* | [1927] 11 TC 790 | Incorporation does not by itself negate mutuality |
| *Municipal Mutual Insurance v Hills* | [1932] 16 TC 430 (HL) | Established the four essential tests; mutual and non-mutual income can be severed |
| *NALGO v Watkins* | [1934] 18 TC 499 | Members' social/recreational clubs not taxable on member surpluses |
| *Ayrshire Employers v CIR* | [1946] 27 TC 331 (HL) | Definitive modern authority confirming MTE |
| *English & Scottish Co-op v CAIT* | [1948] AC 405 (PC) | Three conditions: identity, disposal right, contributor mandate |

### 1.3 Incorporation — Special Considerations (BIM24250)

For a **company limited by guarantee without share capital**, MTE is achievable but the articles must **expressly** provide for return of surplus to members on winding up. Unlike an unincorporated association, general law does not automatically give CLG members a right to surplus. Standard Model Articles are insufficient — custom drafting is essential.

---

## 2. Article-by-Article Assessment Against the Four Tests

### TEST 1: Identity Between Contributors and Participators

**Requirement:** The class of persons who contribute to the common fund must be identical to the class entitled to participate in the surplus.

**Assessment of Articles:**

| Article | Provision | MTE Impact | Rating |
|---------|-----------|------------|--------|
| Art 4 | Objects: "mutual association for the exclusive benefit of its Members" | Expressly mutual purpose — strong | PASS |
| Art 5(a) | Income from "subscriptions, levies, and contributions from Members" | Contributors are Members — correct | PASS |
| Art 9(1) | Full Members: pay subscriptions, full voting rights | Contributors and participators — aligned | PASS |
| Art 9(2) | Honorary Members: no subscriptions, full voting rights | **Do not contribute financially** | RISK |
| Art 9(3) | Associate Members: pay subscriptions, no voting rights | Contributors but limited participators | PASS (marginal) |
| Art 18(3) | Distribution to "Full Members or Associate Members" | Honorary Members excluded from distribution | MITIGATES Art 9(2) risk |

**Honorary Members — The Key Risk (Art 9(2)):**

Honorary Members pay no subscriptions. Under Art 18(3), they receive nothing on winding up (zero subscriptions = zero share). This is internally consistent — they don't contribute, they don't participate in surplus. However, they are defined as "Members" (Art 1) and hold full voting rights over the common fund. HMRC could argue this creates a class of non-contributing participators who control the fund without contributing to it, potentially breaking identity.

**Practical mitigation:** Honorary Members are typically few in number (honorary status is by invitation only). If their numbers remain small relative to the subscribing membership, this is unlikely to attract HMRC challenge. The risk would increase if Honorary Members became a significant proportion of voting members.

**Recommendation:** The current position is defensible but not watertight. Consider adding a provision that Honorary Members shall not exceed [X]% of total membership, or that Honorary Member status is reviewed periodically. Alternatively, remove their voting rights on financial matters (subscriptions, borrowing, dissolution) — though this adds complexity.

**Risk level: LOW-MEDIUM** (defensible given small numbers, but a theoretical vulnerability)

---

### TEST 2: Surplus Must Return to Contributors and No One Else

**Requirement:** On winding up, the surplus must go back to contributors. It must **not** be directed to charities, successor bodies, or any other entity. HMRC is explicit: "if the rules, constitution, articles, or memorandum of a body require that, on a winding up, any surplus is to be transferred to an entity with similar aims, the body cannot be carrying on a mutual trade" (BIM24110).

**Assessment of Articles:**

| Article | Provision | MTE Impact | Rating |
|---------|-----------|------------|--------|
| Art 18(1) | Distinguishes Mutual Funds from Non-Mutual Funds | Correct separation | PASS |
| Art 18(2) | Non-Mutual Funds → returned to funder or transferred to similar body | Only applies to non-mutual funds — correct | PASS |
| Art 18(3) | Mutual Funds → distributed to subscribing Members | Surplus returns to contributors | PASS |

**This is the single most important provision for MTE.** Article 18 gets it right by:

1. **Separating** mutual funds (member subscriptions) from non-mutual funds (grants)
2. **Directing mutual surplus only to members** — not to charities, not to successor bodies
3. **Directing non-mutual surplus away from members** — to funders or similar bodies (which is correct, because non-mutual funds were never part of the mutual common fund)

**The "or as the Members may otherwise determine" override (Art 18(3)):**

This discretion clause allows members to vote on an alternative distribution method at or before dissolution. While flexible, it creates a theoretical risk: members could vote to send mutual surplus to a non-member body, which would retrospectively break Test 2 for all prior years.

**Recommendation:** Consider constraining this override: "...or in such other proportions as the Members may determine by ordinary resolution, provided always that the Mutual Funds shall be distributed only among persons who are or were Members of the Company."

**Risk level: LOW** (the architecture is correct; the override is a minor theoretical risk)

---

### TEST 3: Reasonable Proportionality

**Requirement:** The amount distributed to each member on winding up must bear a reasonable relationship to their contribution to the surplus. HMRC accepts the five-year lookback period (BIM24115).

**Assessment of Articles:**

| Article | Provision | MTE Impact | Rating |
|---------|-----------|------------|--------|
| Art 18(3) | "in proportion to the total subscriptions paid by each such person during the five years preceding dissolution" | Directly aligned with HMRC's accepted approach | PASS |

**This precisely mirrors HMRC's guidance at BIM24115**, which states:

> "You may accept that an entity satisfies this condition if the return of contributions only takes into account current contributors and those who ceased to be contributors within the last five years."

**One gap — former members:** Article 18(3) distributes to persons who "are Full Members or Associate Members **at the time of dissolution**." HMRC's guidance contemplates including **former members who left within the previous five years**. Excluding them strengthens the "last man standing" effect but could theoretically weaken proportionality if a large cohort of members left shortly before dissolution.

**Recommendation:** Consider adding "and any person who ceased to be a Full Member or Associate Member within the five years preceding dissolution" to the distribution class. This would more closely align with HMRC's expectation and strengthen the proportionality argument. However, it adds administrative complexity and the current wording is unlikely to be challenged on this point alone.

**Risk level: LOW** (HMRC-compliant formula; former member gap is minor)

---

### TEST 4: Members Must Control the Common Fund

**Requirement:** For an incorporated body, contributors must **control** the common fund. The fund must have been created for the common purpose and controlled wholly by the contributors (BIM24120).

**Assessment of Articles:**

| Article | Provision | MTE Impact | Rating |
|---------|-----------|------------|--------|
| Art 8(2) | MC elected by Members at AGM | Member control over governance — correct | PASS |
| Art 7(1) | Directors appointed by MC (from elected members) | Indirect member control over Board | PASS |
| Art 10(1) | Subscriptions approved by AGM | Members control contribution levels | PASS |
| Art 14 | Resolutions by vote of Members | Democratic member control | PASS |
| Art 6(5)(c) | Deadlock resolved by member vote | Ultimate control rests with Members | PASS |
| Art 21 | Borrowing requires member-approved limit | Members control fund exposure | PASS |
| Art 16(2) | Withdrawals need Treasurer + one other Member | Member oversight of expenditure | PASS |

**This test is strongly satisfied.** The governance structure ensures that:
- Members elect the MC → MC appoints Directors → Directors implement MC policy
- Major financial decisions (subscriptions, borrowing, dissolution) require member vote
- Deadlocks between Board and MC are resolved by member vote
- No external party controls any part of the common fund

**Risk level: VERY LOW**

---

## 3. Treatment of Specific Income Types

### 3.1 Member Subscriptions (Art 5(a), Art 10(1))

Member subscriptions are the core mutual trading income. Surpluses from member subscriptions applied to member services are **exempt** under MTE. The articles correctly identify these as the primary revenue source.

**Status: COMPLIANT**

### 3.2 Grant Income (Art 5(b))

Grant income from statutory bodies or charitable trusts is **not** mutual trading income. It must be:
- Accounted for separately (Art 5(b)(i) — **correct**)
- Applied per grant terms (Art 5(b)(ii) — **correct**)
- Excluded from member distributions on winding up (Art 18(2) — **correct**)

**Critical point:** If grant income is used to **subsidise** activities that would otherwise be funded by member subscriptions, HMRC may argue the whole operation is a single taxable trade rather than a mutual trade with separate non-trade income. The articles require separate accounting, which is the right approach, but operational practice must follow through.

**Status: COMPLIANT (subject to proper accounting in practice)**

### 3.3 Sponsorship and Donations from Non-Members (Art 5(c))

Article 5(c) prohibits soliciting or accepting "voluntary contributions, sponsorships, or donations from non-members." This is **more restrictive than MTE requires** — the exemption does not demand a blanket ban on non-member income, only that non-member income is separately accounted for and taxed. However, since the BVMA operates a separate company for non-member business, this strict approach is prudent and eliminates any risk of commingling.

HMRC guidance at BIM24505 confirms that sponsorship income is always non-mutual. By prohibiting it entirely, Art 5(c) removes this category of income from the equation.

**Status: OVER-COMPLIANT (conservative but effective)**

### 3.4 Investment Income (Not Addressed)

The MTE is purely a **trading income** concept. It does not extend to:
- Bank interest
- Dividends
- Property/rental income
- Capital gains

These remain fully taxable regardless of MTE status. The articles do not address this explicitly — this is an operational/accounting matter rather than a constitutional one. The Company will need to include any investment income in its corporation tax return even if all trading income is exempt.

**Status: N/A (operational matter, not articles issue)**

---

## 4. Structural Risks and Recommendations

### 4.1 Risk Summary

| Risk | Test Affected | Severity | Current Mitigation |
|------|--------------|----------|-------------------|
| Honorary Members: non-contributing voters | Test 1 (Identity) | LOW-MEDIUM | Art 18(3) excludes them from distribution |
| Art 18(3) override: members could redirect surplus | Test 2 (Return) | LOW | Override requires member vote |
| Former members excluded from distribution | Test 3 (Proportionality) | LOW | Five-year formula otherwise correct |
| Grant income subsidising mutual activities | Tests 1 & 2 | MEDIUM | Art 5(b) requires separate accounting |
| Associate Members: contribute but cannot vote | Test 1 (Identity) | LOW | They are statutory members; subscriptions count |

### 4.2 Recommended Amendments (Optional — For Enhanced Protection)

These are not essential but would strengthen the MTE position:

**1. Constrain the Art 18(3) override:**

Current: "...or as the Members may otherwise determine by ordinary resolution at or before the time of dissolution."

Suggested: "...or in such other proportions as the Members may determine by ordinary resolution at or before the time of dissolution, provided always that the Mutual Funds shall be distributed only among eligible Members and former Members as described in this Article."

**2. Include former members in Art 18(3) distribution class:**

Add after "at the time of dissolution": "and any person who was a Full Member or Associate Member at any time during the five years preceding dissolution"

**3. Add an express MTE preservation clause to Art 17:**

After Art 17(4), add:

> "(5) The Company is established as a mutual trading entity. The Directors and the Management Committee shall ensure that the Company's activities are conducted so as to preserve its mutual trading status for the purposes of corporation tax, including by maintaining proper separation between mutual trading income and any other income."

This would be the first articles provision I've seen that expressly names the MTE as a constitutional objective. It would give Directors a clear mandate (and duty) to protect MTE status.

---

## 5. Overall Assessment

### What the Articles Get Right

- **Objects clause (Art 4):** Expressly mutual — "for the exclusive benefit of its Members"
- **Income restriction (Art 5(a)–(c)):** Member subscriptions as primary income; grants ring-fenced; non-member contributions prohibited
- **Separate accounting for grants (Art 5(b)):** Required by the articles, not just by practice
- **Income application (Art 17):** Applied solely for member benefit
- **Dissolution clause (Art 18):** Correctly separates mutual from non-mutual funds; mutual surplus returns to subscribing members only; five-year proportionality formula matches HMRC guidance
- **Member control:** Unbroken chain from Members → MC → Board; major decisions require member vote

### What Could Be Improved (Not Fatal, But Advisable)

| Item | Current Position | Risk | Recommendation |
|------|-----------------|------|----------------|
| Honorary Members | No subscriptions, full voting rights, excluded from distribution by formula | Low-medium | Monitor numbers; consider limiting voting rights on financial matters |
| Art 18(3) override | Unrestricted discretion | Low | Constrain to distribution among Members only |
| Former members | Excluded from winding-up distribution | Low | Consider including leavers within 5 years |
| Art 17 tension | 17(1) says "benefit of Members" / 17(3) says no profit to Members | Low | Add clarifying sub-article |
| Express MTE clause | None | N/A | Consider adding to Art 17 as a constitutional objective |

### Conclusion

**The Articles of Association are substantially compliant with HMRC's mutual trading exemption requirements.** The dissolution clause (Art 18) — which is the single most critical provision — correctly returns mutual surplus to subscribing members in proportion to their contributions over five years. The four essential tests are all satisfied, with the Honorary Members position being the only area of theoretical vulnerability.

The BVMA's decision to operate non-member business through a separate company further strengthens the MTE position by eliminating the risk of commingled non-member income.

No fundamental restructuring is needed. The optional amendments above would harden the position further but the articles as drafted would withstand HMRC scrutiny.

---

*This review is for discussion purposes and does not constitute formal tax advice. Specialist tax advice from a chartered tax adviser experienced in mutual trading should be obtained before relying on MTE status in corporation tax returns.*

**Key HMRC references:** BIM24000–BIM24995 (Business Income Manual); CTM40950–CTM40985 (Company Taxation Manual)
