![COVID Vaccine Rumor Control](/docs/RumorControl_masks_chiron2.png)
*We are not throwin’ away our shot*
<br>
<br>
We want COVID vaccines to succeed and get on with our lives. And, reports of “90%+ effective” have primed the public to expect miracles. But, vaccine acceptability will be contingent on a yet nebulous profile of safety. Therefore, we must proactively evaluate side effect reports and optimize vetted information for dissemination.
<br>
<br>
# Mission
To factcheck vaccine side effect rumors and results in real-time. Deliver vetted information to patients effectively.<br>
<br>
<br>
```We are soliciting interest and funding to build a lightweight science-as-a-service tool. The rumor control website will require scientific expertise, and the chatbot will require software developers. Please WhatsApp (+1-919-260-3808) or email nab@unc.edu if interested.```
 
<br><br>
![message examples](/docs/messageexamples4.png)
<br><br>
<br>
# Watch the Demo
Mass vaccinations, common side effects, and ubiquitous mobile phones mean millions will be searching for reliable information on handhelds. The envisioned platform focuses on SMS because it is the lowest threshold and most widespread. In this [1 minute demo video](https://vimeo.com/486023188) we show how to answer the three questions regarding vaccine side effects that patients find most important. 
1. Is it vaccine-related?
2. How long will it last?
3. What should I do now?
<br><br><br>
<a href="https://vimeo.com/486023188" rel="demo video">![](https://nabarundg.github.io/vaccinerumorcontrol/docs/vimeo_demo4.png)</a>
<br><br>
# Generated Data
User-generated text can be mined for shifts in public sentiment and provide specific real-time targets for countering misinformation. Private text exchanges with a bot may provide different insight than other data sources. Unlike search engine trends and social media monitoring, we will be able to query the time between vaccination and onset of symptoms. Time-to-onset is the [single most important](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6447519/) element to determining if a side effect was caused by the vaccine.
<br><br>
# Anticipated Costs
We are soliciting funding to make this vision a reality. At a minimum over 6 months, we will need a software developer ($25-$43k), purchased computing resources ($30k), and a part-time project manager ($65k). Ideally, research assistants and more programmer support would be available, either funded, crowdsourced, or in-kind. In the event of high volume uptake (more than 100,000 sessions), text messaging via [Twilio](https://www.twilio.com/pricing) can be scaled with volume discounts, but would require additional funding. Each chatbot session costs about $0.12 (assuming 16 send/receive messages) in the United States, and is available for paralell deployment in dozens of other countries.
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
As described in this [video](https://nabarundg.github.io/vaccinerumorcontrol/docs/patients.md), patients with side effects expect instant  and compassionate feedback.
<br>
**4. Patients are reluctant to download single-use reporting apps**<br>
[Based on our experience in 4 countries](https://link.springer.com/article/10.1007/s40264-019-00813-6), mobile apps for side effect reporting have limited uptake. The yet-unlaunched [CDC mobile app (V-SAFE)](https://www.cdc.gov/coronavirus/2019-ncov/vaccines/safety.html) focuses on *collecting* information, while [patients](https://nabarundg.github.io/vaccinerumorcontrol/docs/patients.md) expect to *receive* information.
<br><br>
# Scientific Approach
The goal is to evaluate side effect rumors and study results in real-time. We will monitor social and news media, scientific literature, pharmaceutical industry filings, and government reports to identify emerging concerns about vaccine side effects. We will scientifically assess each new side effect ("adverse event") using data and medical knowledge to determine causality. The team will consist of experts in pharmacovigilance, pharmacoepidemiology, pharmacology, and related disciplines.<br>
<br>
**Illustrative table of regularly updated results**<br>
<br>
|Vaccine|Side Effect|Status|
|--|--|--|
|Vaccine01|transverse myelitis (rare inflammation of the spinal cord)|unlikely|
|Vaccine01|impanted microchip|false|
|Vaccine02|chills|known, common, minor|
<br><br>
# Tech Approach
We will develop a chatbot to allowing users to describe symptoms and learn if they could be vaccine-related. Serious side effects will be referred for medical attention. Basic management information will be provided for common known minor side effects, including how long symptoms are expected to last. Using services like [Twilio](https://www.twilio.com/messaging), the chatbot can be embedded in other websites for mass syndication, and will be accessible via SMS text and WhatsApp. Python-based chatbots be developed for pilot message testing. As we have done in previous projects, a dictionary will be developed to translate vernacular symptoms to a medical ontology to assist with natural language processing.
<br><br>
# Why This Is Needed Now
A [recent headline in *Science*](https://science.sciencemag.org/content/370/6520/1022?fbclid=IwAR1glSi-0GalPGx1ASJDzDPfyu91Wk-ODA_NbIYGlz2xrpjCRtceIdrcsPQ) summarizes the need: Public needs to prep for vaccine side effects<br>
[Professional societies](https://link.springer.com/article/10.1007/s40264-020-00941-4) and [industry experts](https://www.mymedsandme.com/resources/whitepapers/impact-covid-19-vaccination-on-safety-reporting-and-liability) have warned of this challege for months.
+ [BBC News](https://www.bbc.com/news/54893437), Nov 15, 2020: Vaccine rumours debunked: Microchips, 'altered DNA' and more
+ [NBC News](https://www.nbcnews.com/health/health-news/covid-19-vaccines-may-have-potentially-unpleasant-side-effects-n1247485), Nov 12, 2020: Covid-19 vaccines may have potentially unpleasant side effects
+ [Washington Post](https://www.washingtonpost.com/politics/2020/11/17/cybersecurity-202-next-big-disinformation-fight-is-coming-over-coronavirus-vaccines/), Nov 17, 2020: The next big disinformation fight is coming – over coronavirus vaccines

<a href="https://science.sciencemag.org/content/370/6520/1022" rel="demo video">![](https://nabarundg.github.io/vaccinerumorcontrol/docs/scienceheadline2.png)</a>
<br><br>
# Read More
+ [Patient perspective video](https://nabarundg.github.io/vaccinerumorcontrol/docs/patients.md) we compiled on from advocates discussing COVID vaccine adverse event reporting
+ [Misinformation and humor](https://nabarundg.github.io/vaccinerumorcontrol/docs/misinformation.md) already spreading on TikTok about COVID vaccines
+ Project [team](https://nabarundg.github.io/vaccinerumorcontrol/docs/team.md)
+ [Software development](https://nabarundg.github.io/vaccinerumorcontrol/docs/softwaredev.md) process
+ [Regulatory considerations](https://nabarundg.github.io/vaccinerumorcontrol/docs/regulatory.md)
+ [Demo rumor dispelling](https://tarheels.live/vaccine/rumors-and-results/) pages
