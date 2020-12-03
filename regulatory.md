**Concept note to develop COVID vaccine side effect chatbot**<br>

![COVID Vaccine Rumor Control](/docs/RumorControl_masks_chiron2.png)
<br>
<br>
# Regulatory Considerations
Similar to the American Association of Poison Control Centers [web app PoisonHelp.org](https://www.poisonhelp.org), the chatbot does not make a medical diagnosis, but rather serves as a triage tool aimed at reducing the burden of minor cases on healthcare systems, while providing vaccine-specific side effect information based on existing public data from US FDA, CDC, EMA, MHRA, Lareb, and other government agencies. The current medial software [guidance (Section V.B. on page 12)](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/policy-device-software-functions-and-mobile-medical-applications) suggests that this type of web app does not fall into high risk software that is the focus of regulation, but that regulatory discretion will be exercised.<br>
<br>

# Legal Considerations
For the proposed project, the [PoisonHelp.org web app](https://www.poisonhelp.org) sets precedent. It has been operational since 2016, and allows users to identify circumstances of poisoning exposures (broadly construed). It provides basic comfort suggestions and triages whether they should seek help. Basic demographic and circumstantial information is used to determine severity and circumstance. It is carefully calibrated to limit liability while allowing the healthcare system to focus on cases that most need professional intervention. We build upon this framework. Dr. Dasgupta led the development of PoisonHelp.org and has a working understanding of the considerations. What we are proposing here is of a much narrower scope. Only the most common minor side effects (chills, headache, etc.) will be offered comfort suggestions. We will consult [FDA Serious Adverse Event](https://www.fda.gov/safety/reporting-serious-problems-fda/what-serious-adverse-event) and [EMA Important Medical Events](https://www.ema.europa.eu/documents/other/important-medical-event-terms-list-version-meddra-version-231_en.xlsx) standards to identify severity, but in practice only patient-entered phrases that clearly state a minor problem will be provided comfort advice (e.g., "I had the chills").<br>
<br>
![poisonhelp.org](/docs/poisonhelp.png)
<br>
We will not be providing "treatment recommendations" to users. Instead, we will deliver vetted side effect information in a format that is meaningful, for example augmenting with how long symptoms might last or age-specific profiles. For the most common, easily managed, minor side effects like chills and soreness, providing general comfort suggestions (ice, arm movement exercises, standard OTC pain relievers, etc.) poses marginal risk. We may not have to create this content ourselves, since news media are already making these suggestions. Providing useful information that patients expect is inherent to the value proposition. The general posture is to refer anything ambiguous or complicated to clinicians/pharmacists, as with PoisonHelp.org. For example, the decision rules default to seeking medical advice for all pediatric cases and if pregnant or breastfeeding, and we could follow a similar framework. Since the vaccine is not expected to be approved in children, any minors who are described will be referred to clinicians. To mitigate risks we can focus on non-therapeutic comfort suggestions at launch.<br>
<br>
As a practical example, PoisonHelp.org provides the following comfort suggestions for Krazy Glue (ethyl cyanoacrylate):<br>
<br>

![krazy glue](/docs/krazyglue.png)

<br><br><br>
[Return to Concept Note](https://nabarundg.github.io/vaccinerumorcontrol/index)

