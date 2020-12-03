![COVID Vaccine Rumor Control](/docs/RumorControl_masks_chiron2.png)<br>
*We want COVID vaccines to succeed and get on with our lives. And, reports of “90%+ effective” have primed the public to expect miracles. But, vaccine acceptability will be contingent on a yet nebulous profile of safety. Therefore, we must proactively evaluate side effect reports and optimize vetted information for dissemination. We are not throwin’ away our shot.*
<br>

---

# Mission
To factcheck vaccine side effect rumors and results in real-time. To deliver vetted information to the public effectively.<br>
<br>

```We are soliciting interest and funding to rapidly build (January deployment) a lightweight science-as-a-service tool. The rumor control website will require scientific expertise, and the chatbot will require software developers. Please WhatsApp (+1-919-260-3808) or email nab@unc.edu if interested.```
<br><br>
![message examples](/docs/messageexamples4.png)
<br>
<br>
Jump to [funding options](https://nabarundg.github.io/vaccinerumorcontrol/#funding) and [project team](https://nabarundg.github.io/vaccinerumorcontrol/team)
<br><br>

# Watch the Demo
Mass vaccinations, common side effects, and ubiquitous mobile phones mean millions will be searching for reliable information on handhelds. The envisioned platform focuses on SMS because it is the lowest threshold and most widespread. An embeddable web chatbot API is also envisioned. The platform will not diagnose or deliver treatment advice, but instead provide comfort suggestions to cope with common side effects. In this [1 minute demo video](https://vimeo.com/486023188) we show how to answer the three questions regarding vaccine side effects that patients find most important. 
1. Is it vaccine-related?
2. How long will it last?
3. What should I do now?

<br><br>
<a href="https://vimeo.com/486023188" rel="demo video">![](https://nabarundg.github.io/vaccinerumorcontrol/docs/vimeo_demo4.png)</a>
<br><br>

# Generated Data
User-generated text can be mined for shifts in public sentiment and provide specific real-time targets for countering misinformation. Private text exchanges with a bot may provide different insight than other data sources. Unlike search engine trends and social media monitoring, we will be able to query the time between vaccination and onset of symptoms. Time-to-onset is the [single most important](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6447519/) element to determining if a side effect was caused by the vaccine.
<br><br>

# Insights
From years of deploying patient-centric health apps, we proceed with 4 central insights.

**1. The "worried well" need encouragement to get second doses**<br>
Offering encouragement to those with minor expected side effects will be essential to overcome hesitancy for regimen completion.<br>
<br>
**2. Syndication speeds uptake**<br>
To rise above pandemic media saturation, a data tool must be easily propogated while fulfilling a fundamental public need, as the success of COVID tracker APIs demonstrates.<br>
<br>
**3. Patients expect instant feedback**<br>
As described in this [video](https://nabarundg.github.io/vaccinerumorcontrol/docs/patients.md), patients with side effects expect instant and compassionate feedback. <br>
<br>
**4. Patients are reluctant to download single-use reporting apps**<br>
[Based on our experience in 4 countries](https://link.springer.com/article/10.1007/s40264-019-00813-6), mobile apps for side effect reporting have limited uptake. The yet-unlaunched [CDC mobile app (V-SAFE)](https://www.cdc.gov/coronavirus/2019-ncov/vaccines/safety.html) focuses on *collecting* information, while [patients](https://nabarundg.github.io/vaccinerumorcontrol/docs/patients.md) expect to *receive* information.
<br><br>

# Scientific Strategy
The goal is to evaluate side effect rumors and study results in real-time. We will monitor social and news media, scientific literature, pharmaceutical industry filings, and government reports to identify emerging concerns about vaccine side effects. We will scientifically assess each new side effect ("adverse event") using data and medical knowledge to determine causality. The team will consist of experts in pharmacovigilance, pharmacoepidemiology, pharmacology, and related disciplines.
<br><br>
> Notably, exposure to misinformation cannot simply be undone through fact checking, correcting, or debunking efforts: a large body of research has shown that retractions are rarely successful at eliminating reliance on misinformation, a phenomenon known as the “continued influence” effect. Mitigating the effects of exposure to vaccine misinformation requires the development and testing of novel strategies beyond traditional vaccine education efforts.<br>
> <br>
> Robin C. Vanderpool, Anna Gaysynsky, and Wen-Ying Sylvia Chou [writing](https://ajph.aphapublications.org/doi/10.2105/AJPH.2020.305906) in the October *American Journal of Public Health* [supplement on tackling misinformation online](https://ajph.aphapublications.org/toc/ajph/110/S3)
<br>

# Tech Strategy
We will develop a chatbot to allowing users to describe symptoms and learn if they could be vaccine-related. Serious side effects will be referred for medical attention. Basic management information will be provided for common known minor side effects, including how long symptoms are expected to last. Using services like [Twilio](https://www.twilio.com/messaging), the chatbot can be embedded in other websites for mass syndication, and will be accessible via SMS text and WhatsApp. Python-based chatbots will be developed to pilot message test. As we have done in previous projects, a dictionary will be developed to translate vernacular symptoms to a medical ontology to assist with natural language processing. + [Details here](https://nabarundg.github.io/vaccinerumorcontrol/softwaredev)
<br><br>

# Comfort Suggestions for Patients
We will not be providing treatment advice to users. We are delivering vetted side effect information in a format that is meaningful, for example augmenting with how long it might last. For the most common, easily managed, minor side effects like chills and soreness, providing general comfort suggestions (ice, arm movement exercise, standard OTC pain relievers, etc.) is entirely reasonable and in line with is already said in news media. The general posture is to refer anything ambiguous or complicated to clinicians/pharmacists.
<br><br>

# Funding
Thus far this is a collaboration between the University of North Carolina at Chapel Hill and Rhizomik Tech, LLC. We are open to other collaborators. Funding could be directed at the university (scientific strategy) or the small business (tech strategy).
<br><br>
*Traditional Development*<br>
We are soliciting funding and suggestions to make this vision a reality. We would like to develop a rapid MVP by January 2021. Using standard development process we will need a software developer ($25-$43k), purchased computing resources ($30k), and a scientific project manager ($40k). Ideally, 2 research assistants ($21k each) and more programmer resources would be available, either funded, crowdsourced, or in-kind. These resources are anticipated to cover the initial build and 6 months of moderate uptake.
<br><br>
*Crowdsourced Development*<br>
Capitalizing on boredom during a socially distanced holiday and altruistic impulse, an alternate approach is to rely on crowdsourcing for much of the devleopment as an open source project. For example, scientific tasks could be distributed to separate teams: searching for rumors on TikTok, monitoring and extracting results from scientific reports, message testing, creating the vernacular-to-medical language dictionary, assesing causality and writing blog posts, analyzing user-generated text. Similarly, once an architecture has been established, tech development tasks could be crowdsourced too. However, for this model to be successful, we still need a lead software designer and a lead scientific project manager to oversee task deployment. And, we would need to excite and motivate hundreds to yield a core dozen who would do most of the work. Crowdfunding could also be envisioned. Both crowdsorucing and crowdfunding would be heavily reliant on institutional support for promotion. 
<br><br>
*Scaling Costs*<br>
In the event of high volume uptake (more than 100,000 sessions), text messaging via [Twilio](https://www.twilio.com/pricing) can be scaled with volume discounts, but would require additional funding. Each chatbot session costs about $0.12 (assuming 16 send/receive messages) in the United States, and is available for paralell deployment in dozens of other countries.
<br><br>

# Why This Is Needed Now
<a href="https://science.sciencemag.org/content/370/6520/1022" rel="demo video">![](https://nabarundg.github.io/vaccinerumorcontrol/docs/scienceheadline2.png)</a>
<br>
A [recent headline in *Science*](https://science.sciencemag.org/content/370/6520/1022?fbclid=IwAR1glSi-0GalPGx1ASJDzDPfyu91Wk-ODA_NbIYGlz2xrpjCRtceIdrcsPQ) summarizes the need.<br>
[Professional societies](https://link.springer.com/article/10.1007/s40264-020-00941-4) and [industry experts](https://www.mymedsandme.com/resources/whitepapers/impact-covid-19-vaccination-on-safety-reporting-and-liability) have warned of this challege for months.
+ [USA Today](https://www.usatoday.com/story/news/health/2020/12/02/covid-vaccine-pfizer-moderna-astrazeneca-what-to-know/6476436002/), Dec 2, 2020: Will there be side effects from a COVID-19 vaccine? When can you get it? We answer your vaccine questions
+ [CNN](https://www.cnn.com/2020/12/02/health/coronavirus-vaccine-volunteer-side-effects/index.html), Dec 2, 2020: What it feels like to get an mRNA coronavirus vaccine
+ [Washington Post](https://www.washingtonpost.com/politics/2020/11/17/cybersecurity-202-next-big-disinformation-fight-is-coming-over-coronavirus-vaccines/), Nov 17, 2020: The next big disinformation fight is coming – over coronavirus vaccines
+ [WebMD](https://www.webmd.com/lung/news/20201124/people-should-know-that-covid-vaccine-might-spur-transient-sickness-cdc-experts#1), Nov 24, 2020: Experts: COVID Vaccine May Cause Side Effects
+ [BBC News](https://www.bbc.com/news/54893437), Nov 15, 2020: Vaccine rumours debunked: Microchips, 'altered DNA' and more
+ [NBC News](https://www.nbcnews.com/health/health-news/covid-19-vaccines-may-have-potentially-unpleasant-side-effects-n1247485), Nov 12, 2020: Covid-19 vaccines may have potentially unpleasant side effects

### Revealing RCT patient experiences reported publicly
> "The actual injection felt, at first, just like a flu shot, which is basically just a little pinch in the side of your arm," Batalvi said. "Once I left the hospital, that evening, the stiffness got a little bit worse. It was definitely manageable, but you kind of don't really feel like moving your arm too far above your shoulder. But the side effects are pretty localized. I mean, it's just in the muscle in your arm. And that's about it. It doesn't really affect anything else and you feel fine."
> That was after the first dose. But the second dose was different.
> "I actually had some pretty significant symptoms after I got the second dose. Once I got the second dose, I was fine while I was in the hospital. But that evening was rough. I mean, I developed a low-grade fever, and fatigue and chills," Batalvi said. He said he was out for that day and evening, but he "felt ready to go by the next morning."
> He said he called the study doctors to let them know about his symptoms. They weren't alarmed and told him he shouldn't be either.<br>
> [CNN - Dec 2, 2020](https://www.cnn.com/2020/12/02/health/coronavirus-vaccine-volunteer-side-effects/index.html)
<br>

> This summer, computational biologist Luke Hutchison volunteered for a trial of Moderna's COVID-19 vaccine. But after the second injection, his arm swelled up to the size of a “goose egg,” Hutchison says. He can't be sure he got the vaccine and not a placebo, but within a few hours, Hutchison, who was healthy and 43, was beset by bone and muscle aches and a 38.9°C fever. “I started shaking. I had cold and hot rushes,” he says. “I was sitting by the phone all night long thinking: ‘Should I call 911?’” Hutchison's symptoms resolved after 12 hours. But, he says, “Nobody prepared me for the severity of this.”<br>
> [*Science* - Nov 27, 2020](https://science.sciencemag.org/content/370/6520/1022?fbclid=IwAR1glSi-0GalPGx1ASJDzDPfyu91Wk-ODA_NbIYGlz2xrpjCRtceIdrcsPQ)

<br><br>

# Existing Example
[PoisonHelp.org is a similar web app](https://www.poisonhelp.org) that allows users to identify circumstances of poisoning exposures (broadly construed) and provides first pass information, depending on severity and circumstance, to triage whether they should seek help. It is carefully calibrated to limit liability while allowing the healthcare system to focus on cases that most need professional intervention. 
<br>
Leveraging the opportunity presented by COVID mass vaccination, the proposed project could serve as a model for future public health messaging.
<br><br>

# Read more...
+ [Patient perspective video](https://nabarundg.github.io/vaccinerumorcontrol/patients) we compiled on from advocates discussing COVID vaccine adverse event reporting
+ [Misinformation and humor](https://nabarundg.github.io/vaccinerumorcontrol/misinformation) already spreading on TikTok about COVID vaccines
+ [Project team](https://nabarundg.github.io/vaccinerumorcontrol/team)
+ [Software development process](https://nabarundg.github.io/vaccinerumorcontrol/softwaredev)
+ [Regulatory considerations](https://nabarundg.github.io/vaccinerumorcontrol/regulatory)
+ [Example rumor dispelling](https://tarheels.live/vaccine/rumors-and-results/)
