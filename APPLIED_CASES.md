# Opioid-sparing anesthesia: applied cases

> **Educational work by a pre-medical student — not medical advice.** Not a clinical protocol, prescription, or patient handout, and not for patient care. See [DISCLAIMER](DISCLAIMER.md).

28 October 2026. Educational source application only. This supplement does not restore the earlier manuscript or publish another Zenodo version.

All examples are entirely synthetic, independent of real encounters, charts or shadowing observations. They illustrate source-informed reasoning, not observed administrations, validated treatment plans, standardized drug regimens or clinical competence. Male/female labels are descriptive; any difference in the discussion follows history, procedure and evidence applicability rather than sex alone. Female cases are nonpregnant unless explicitly stated otherwise.

## Shared example set and method

Read [the local anesthesia-options case set](ANESTHESIA_OPTIONS_AND_CASES.md) for the same four-modality comparison, 12 general teaching cases, medication roles/routes, monitoring distinctions and decision flows used throughout this portfolio. The topic-specific pairs below apply that format to this repository.

Standardize the reasoning: identify the clinical question → verify source/version and population → distinguish published recommendation from fictional inference → assess patient-specific alternatives and monitoring → reassess effects and harms. A DOI establishes an identifier, not the truth or clinical suitability of every inferred decision. Source verification here covers identities and available abstracts/selected passages; it is not an exhaustive full-text systematic appraisal.

```mermaid
flowchart TD
 A[Define procedure, patient goals and question] --> B[Verify source population, version and claim]
 B --> C[Assess patient factors and feasible options]
 C --> D[Clinical team chooses and explains the individualized plan]
 D --> E[Observe intended effects and unwanted effects]
 E --> F[Reassess evidence, response and applicability]
 F --> C
```


<a id="noa-01"></a>
## NOA-01 — Define opioid-free phase versus multimodal care

- **Synthetic male example:** 48-year-old male, 180 cm, 82 kg, elective abdominal surgery with no stated organ dysfunction.
- **Synthetic female example:** 48-year-old female, 164 cm, 64 kg, same procedure with prior unpleasant opioid effects.

**Worked application:** Agree which phase is being discussed and what outcomes matter. Prior adverse effects inform choice but do not prove that every opioid-free strategy is safer.

**Options / medication and administration context:** IV or inhaled general anesthesia, suitable local/regional analgesia and selected systemic agents may be considered; rescue analgesia remains a clinical option.

**Decision flow:** Define goals and phase → compare evidence/population → select suitable components → assess harms and recovery.

**Source map:** [P](#source-registry), [B](#source-registry), [T](#source-registry). The sources support the named concepts, not the existence or validation of these fictional administrations.

<a id="noa-02"></a>
## NOA-02 — Dexmedetomidine and patient risk

- **Synthetic male example:** 77-year-old male, 179 cm, 80 kg, bradycardia and conduction history.
- **Synthetic female example:** 77-year-old female, 163 cm, 63 kg, hypotension risk and impaired hepatic function.

**Worked application:** The US prescribing information advises considering a dose reduction in patients over 65 years and in hepatic impairment (dexmedetomidine is hepatically metabolized), and notes that hypotension and bradycardia may be more pronounced in older adults. That labeling does not by itself make an alpha-2 agonist suitable: the fictional man's bradycardia and conduction history and the fictional woman's hypotension risk and hepatic impairment each warrant reassessment of whether dexmedetomidine is appropriate at all, before any plan.

**Options / medication and administration context:** A dexmedetomidine adjunct is not necessary for every multimodal anesthetic; other suitable approaches depend on the clinical goals.

**Decision flow:** Identify risk and indication → assess alternatives → determine monitoring → reassess.

**Source map:** [DEX](#source-registry), [LBL](#source-registry), [P](#source-registry). The sources support the named concepts, not the existence or validation of these fictional administrations.

<a id="noa-03"></a>
## NOA-03 — Lidocaine route and exposure

- **Synthetic male example:** 51-year-old male, 180 cm, 81 kg, an IV lidocaine option is being discussed.
- **Synthetic female example:** 51-year-old female, 164 cm, 65 kg, a peripheral block and infiltration are already planned.

**Worked application:** Review exact routes, preparations and timing; the lidocaine consensus does not support assuming concurrent local-anesthetic exposure is safe merely after arithmetic.

**Options / medication and administration context:** Consider the IV option separately from a regional/local plan; the examples do not choose a loading dose or pump setting.

**Decision flow:** Inventory exposures → check overlap limits → select compatible approach → monitor.

**Source map:** [LIDO](#source-registry), [X](#source-registry). The sources support the named concepts, not the existence or validation of these fictional administrations.

<a id="noa-04"></a>
## NOA-04 — Ketamine purpose and clinical assessment

- **Synthetic male example:** 44-year-old male, 181 cm, 84 kg, persistent procedural pain is the discussion topic.
- **Synthetic female example:** 44-year-old female, 165 cm, 65 kg, anxiety is the main concern and analgesia appears adequate.

**Worked application:** Analgesic-adjunct, anxiolytic and hypnotic goals are different. A ketamine acute-pain source cannot by itself justify sedation or induction decisions.

**Options / medication and administration context:** Selected acute-pain adjuncts require indication and adverse-effect review; anxiety does not automatically call for an analgesic infusion.

**Decision flow:** Identify the unmet goal → assess relevant evidence → compare options → monitor response.

**Source map:** [KET](#source-registry), [S](#source-registry). The sources support the named concepts, not the existence or validation of these fictional administrations.

<a id="noa-05"></a>
## NOA-05 — Recovery benefits and evidence claims

- **Synthetic male example:** 62-year-old male, 178 cm, 79 kg, lower opioid use with more drowsiness.
- **Synthetic female example:** 62-year-old female, 162 cm, 62 kg, some rescue opioid use with better perceived comfort.

**Worked application:** Reduced opioid exposure is not identical to improved overall recovery. A fictional pair cannot estimate an effect size, prove superiority or validate the manuscript.

**Options / medication and administration context:** Discuss pain/function/adverse effects together; rescue administration need not mean the initial strategy failed.

**Decision flow:** Specify outcomes and time → compare benefits/harms → reassess priorities → document uncertainty.

**Source map:** [P](#source-registry), [QOR](#source-registry). The sources support the named concepts, not the existence or validation of these fictional administrations.

<a id="source-registry"></a>
## Source registry and applicability

| ID | Source | Scope / limitation |
|---|---|---|
| P | Beloeil H et al. Balanced Opioid-free Anesthesia with Dexmedetomidine versus Balanced Anesthesia with Remifentanil for Major or Intermediate Noncardiac Surgery: The Postoperative and Opioid-free Anesthesia (POFA) Randomized Clinical Trial. *Anesthesiology*. 2021;134(4):541-551. [doi:10.1097/ALN.0000000000003725](https://doi.org/10.1097/ALN.0000000000003725) | Randomized trial: primary composite (hypoxemia, ileus or cognitive dysfunction) more frequent with the dexmedetomidine opioid-free regimen; stopped early after five cases of severe bradycardia. Evidence against assuming a universal safety benefit from avoiding intraoperative opioids |
| B | Joshi GP et al. 2026 American Society of Anesthesiologists Practice Guideline on Perioperative Pain Management Using Local and Regional Analgesia for Cardiothoracic Surgeries, Mastectomy, and Abdominal Surgeries. *Anesthesiology*. 2026;144(1):19-43. [doi:10.1097/ALN.0000000000005790](https://doi.org/10.1097/ALN.0000000000005790) | Procedure-specific local/regional adjunct recommendations; not sole-anesthetic selection |
| T | Nimmo AF et al. Guidelines for the safe practice of total intravenous anaesthesia (TIVA): joint guidelines from the Association of Anaesthetists and the Society for Intravenous Anaesthesia. *Anaesthesia*. 2019;74(2):211-224. [doi:10.1111/anae.14428](https://doi.org/10.1111/anae.14428) | IV delivery and monitoring principles |
| DEX | Weerink MAS et al. Clinical Pharmacokinetics and Pharmacodynamics of Dexmedetomidine. *Clinical Pharmacokinetics*. 2017;56(8):893-913. [doi:10.1007/s40262-017-0507-7](https://doi.org/10.1007/s40262-017-0507-7) | Pharmacokinetic covariates (including hepatic impairment) and hemodynamic effects; dose contexts differ by indication. |
| LBL | PRECEDEX (dexmedetomidine hydrochloride) injection, US prescribing information (Hospira/Pfizer), current label on [DailyMed](https://dailymed.nlm.nih.gov/dailymed/drugInfo.cfm?setid=4419162d-81d4-49bd-96de-1729440bdb74) | Official labeling (no DOI): consider dose reduction in patients over 65 years and in hepatic impairment. Not a dose selection for these fictional profiles. |
| LIDO | Foo I et al. The use of intravenous lidocaine for postoperative pain and recovery: international consensus statement on efficacy and safety. *Anaesthesia*. 2021;76(2):238-250. [doi:10.1111/anae.15270](https://doi.org/10.1111/anae.15270) | High-risk IV use, ideal-body-weight context and avoidance of overlapping local-anesthetic interventions; not a complete regimen. |
| X | Neal JM, Neal EJ, Weinberg GL. American Society of Regional Anesthesia and Pain Medicine Local Anesthetic Systemic Toxicity checklist: 2020 version. *Regional Anesthesia and Pain Medicine*. 2021;46(1):81-82. [doi:10.1136/rapm-2020-101986](https://doi.org/10.1136/rapm-2020-101986) | Published toxicity response resource, not reproduced or replaced by this guide |
| KET | Schwenk ES et al. Consensus Guidelines on the Use of Intravenous Ketamine Infusions for Acute Pain Management From the American Society of Regional Anesthesia and Pain Medicine, the American Academy of Pain Medicine, and the American Society of Anesthesiologists. *Regional Anesthesia and Pain Medicine*. 2018;43(5):456-466. [doi:10.1097/AAP.0000000000000806](https://doi.org/10.1097/AAP.0000000000000806) | Acute-pain adjunct context, not hypnosis or universal induction guidance. |
| S | Practice Guidelines for Moderate Procedural Sedation and Analgesia 2018: A Report by the American Society of Anesthesiologists Task Force on Moderate Procedural Sedation and Analgesia and collaborating societies. *Anesthesiology*. 2018;128(3):437-479. [doi:10.1097/ALN.0000000000002043](https://doi.org/10.1097/ALN.0000000000002043) | Moderate-sedation assessment, monitoring and rescue context; not a deep-sedation recipe |
| QOR | Stark PA, Myles PS, Burke JA. Development and psychometric evaluation of a postoperative quality of recovery score: the QoR-15. *Anesthesiology*. 2013;118(6):1332-1340. [doi:10.1097/ALN.0b013e318289b84b](https://doi.org/10.1097/ALN.0b013e318289b84b) | Recovery is multidimensional; do not reproduce the questionnaire or interpret a synthetic score as validation. |

[Machine-readable source and case map](EXAMPLE_SOURCE_AUDIT.json). Journal sources have DOI identities checked against publisher/PubMed records or the existing verified portfolio audit. Consensus, narrative reviews, guidelines and trials are different evidence types. Official standards and prescribing information in the shared guide are separately labeled and are not assigned invented DOIs. No questionnaire, society algorithm or proprietary figure is reproduced.

## Administration and dosing boundary

These incomplete profiles do not select an individual dose, block injection, reversal dose or pump setting. Source dose context and arithmetic for the separate [Smart NOA educational software project](https://github.com/collingeorge/Smart-NOA-Controller/blob/main/GUIDELINE_INFORMED_EXAMPLES.md) (linked from the shared guide; not part of this repository and not used by these cases) are outside this repository's scope; clinical route, preparation, weight metric, organ function and monitoring determine applicability. The absence of a contraindication in a short case is not clinical clearance. A lower opioid amount or one improved measurement is not a complete recovery benefit.
