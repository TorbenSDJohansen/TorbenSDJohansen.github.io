---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

## Published papers

{% for post in site.publications reversed %}
  {% if post.path contains 'published' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Working papers

{% for post in site.publications reversed %}
  {% if post.path contains 'wp' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Selected work in progress

**Job Amenities and Old Age Labor Supply: Evidence from Danish Administrative Data**<br>
*With Alexander O. K. Marin, Nabanita D. Gupta, and Bent J. Christensen.* [Short description in Danish](https://www.seniorerpaaarbejdsmarkedet.dk/da/undersoegelser-i-gang/seniorers-praeferencer-for-jobkarakteristika-og-deltagelse-paa-arbejdsmarkedet-8opq84jl/).

<details>
<summary>Abstract</summary>
Aging societies increasingly rely on longer working lives, yet evidence on which job attributes keep older workers employed is limited outside the U.S. We study Danish seniors’ preferences for nonwage job characteristics using population-scale administrative registers and a revealed-preference framework based on observed job transitions. We combine individual employment histories, earnings, and demographics with occupational-level amenity profiles constructed from textual job descriptions. We use machine learning to map occupational-level attributes written in text from O*NET to interpretable amenities, such as degree of flexibility and autonomy, and link these measures to Danish occupations. We estimate random-utility models of job choice to recover compensating wage differentials and willingness-to-pay for each amenity. We also document heterogeneity in valuations by age and gender and use the estimated model to simulate how age-friendly job designs could affect late-career mobility and retirement timing.
</details>

**CHAOS: Converting Historical Accounts into Occupational Scores**<br>
*With Matthew Curtis, Julius Koschnick, and Christian Vedel.*

<details>
<summary>Abstract</summary>
History is rich in information about people’s occupations but far less forthcoming on outcomes such as income, wealth, or skills. For this reason, a widely used approach is to proxy these outcomes by averages or medians within each occupational category—so-called occupational scores—of which IPUMS’ occscore (Sobek, 1995) is the most prevalent. This strategy has enabled new insights into topics as varied as technological change, inequality, and institutions. But existing occscores are limited: they rely on fixed benchmarks such as 1950 U.S. wages, discard ambiguity in historical titles, and are difficult to adapt across time and space, generating downstream biases that are hard to correct (Inwood, Minns, &amp; Summerfield, 2019; Saavedra &amp; Twinam, 2020). A key problem is that researchers cannot feasibly construct a new occupational score by hand for every project. This paper introduces a way to automatically estimate occupational scores tailored to any project. CHAOS is a replicable, fully automatic, and interpretable framework for converting historical occupational descriptions into outcome estimates given a source. The key insight is that any occupational score is a weighted average of observed outcomes, where the weights reflect the relevance of each piece of source information. These relevance weights can be estimated automatically using a classification algorithm such as OccCANINE (Dahl, Johansen, &amp; Vedel, 2024) enabling entirely new scales of data collection in economic history. Beyond data construction, we provide a general econometric framework for occupational scores, characterizing the bias they entail relative to true outcomes and deriving a correction method based on recent advances in debiased machine learning. We demonstrate the utility of CHAOS through an application to historical U.S. wage reports covering 88,000 occupation–income pairs across U.S. states throughout the 19th century. From this source we recover decadal wage estimates by state and use them to estimate the evolution of skill bias across an entire century of the Industrial Revolution.
</details>

**Reducing pain and distress in pediatric blood sampling: A pre-post multicomponent intervention study**<br>
*With Louise Kjersgaard Jakobsen, Ina Mathilde Kjær, Bente Lindberg Callesen, Hanne Irene Jensen, Patricia Diana Sørensen, Rikke Møller Andersen, Randi Lehmann Boesen, Ulla List Tønnesen, Karin Bundgaard Nielsen, Thomas Houmann Petersen, and Jonna Skov Madsen.*

<details>
<summary>Abstract</summary>
Needle procedures are among the most feared health care experiences for children and may contribute to long-term anxiety, needle fear, and avoidance of medical care. This pre-post intervention study evaluated a multicomponent, child-centred intervention to reduce pain and distress during blood sampling among children aged 1 to 15 years at the paediatric phlebotomy facility at Lillebaelt Hospital, Denmark. The intervention targeted procedure-related routines, preparation of children and parents, the physical environment, staff competences, anaesthesia, distraction, and child-centred communication. Child-reported pain and distress were assessed using validated 6-point scales before and after implementation. The pre-intervention group included 282 children and the post-intervention group 284 children, with similar age, sex, and sample-type distributions. Mean pain scores decreased from 2.76 to 2.17, and mean distress scores decreased from 2.89 to 2.29; reductions were most pronounced among children aged 4 to 6 years. Parents also reported higher satisfaction and less use of physical restraint. These findings suggest that a multicomponent child-centred approach can reduce pain and distress during blood sampling, although further research is needed on long-term effects on needle fear and health care use.
</details>

**Biomarkers in Prediction of Fibromyalgia Severity and Response to Low-dose Naltrexone: An RCT Secondary Analysis**<br>
*With Freja M. Martinsen, Lotte M. Jensen, Grete Tarp, Louise Skovbjerg, Kirsten Bested, Dorte Aalund Olsen, Mads U. Werner, and Jonna S. Madsen.*

<details>
<summary>Abstract</summary>
Fibromyalgia is a nociplastic pain syndrome of unknown aetiology, and reliable biomarkers are needed to support predictive and therapeutic decisions. This study examined whether selected plasma biomarkers were associated with fibromyalgia severity and whether low-dose naltrexone affected biomarker concentrations compared with placebo. Blood samples were obtained from 51 participants in a randomised, double-blind, placebo-controlled crossover trial of oral low-dose naltrexone 4.5 mg. Plasma concentrations of IL-1β, IL-6, IL-8, TNF-α, BDNF, NfL, NGF, GFAP, and eotaxin were analysed. IL-6 was significantly associated with sleep interference in multivariable analysis, but not with other measures of fibromyalgia severity, and the remaining biomarkers showed only weak correlations with symptom severity. No clear treatment-related differences in biomarker concentrations were observed between low-dose naltrexone and placebo, except for GFAP, which increased after low-dose naltrexone and decreased after placebo. Overall, the findings did not indicate clinically relevant associations between the biomarker panel and fibromyalgia symptomatology or consistent biomarker changes following low-dose naltrexone treatment.
</details>