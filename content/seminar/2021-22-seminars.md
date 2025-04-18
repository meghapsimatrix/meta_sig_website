---
description: 'Systematic Reviews and Meta-Analysis Methodology'
featured_image: ""
title: 2021-22 Seminars and Recordings
date: 2022-05-30
---

### October 22, 2021

***Missing Covariates in Meta-Regression: Considerations and Implications***

-   Speakers:

    -   [Jacob Schauer](https://www.jmschauer.com/), Northwestern University
    -   [Jihyun Lee](https://education.utexas.edu/student/jihyun_lee), University of Texas at Austin
    -   [Karina Diaz-Yanez](https://www.kgdiaz.com/), University of Pennsylvania
    -   [Terri Pigott](https://www.terripigott.com/), Georgia State University

-   Description: This talk will take a deep dive into methods for exploring and handling missing covariates in meta-regression analysis. The speakers will highlight examples of exploratory data analysis techniques and share results of on-going research on methods for handling missing covariate information in a meta-regression. The speakers will present for 30-45 minutes, followed by a Q&A and discussion period.

-   [Slides](../seminar_1_missing_data.pdf)

-   Video Recording

        {{< youtube 8asqqvYXuBs >}}

### November 19, 2021

***Modeling Statistical Artefacts in Meta-Analysis***

-   Speaker: [Brenton Wiernik](https://wiernik.org/), University of South Florida

-   Description: Most published meta-analyses address only artefactual variance due to sampling error and ignore the role of other statistical and psychometric artefacts, such as measurement error (due to factors including unreliability of measurements, group misclassification, and variable treatment strength) and selection effects (including range restriction/enhancement and collider biases). These artefacts can have severe biasing effects on the results of individual studies and meta-analyses. Failing to account for these artefacts can lead to inaccurate conclusions about the mean effect size and between-studies effect-size heterogeneity, and can influence the results of meta-regression, publication bias, and sensitivity analyses. In this talk, I will provide a brief introduction to the biasing effects of measurement error and selection effects and their relevance to a variety of research designs, including connecting to the broader literatures on measurement modeling and causal inference in statistical analysis. I will describe how to estimate the effects of several artefacts in different research designs and correct for their impacts in meta-analyses. This talk is based in part a paper available from <https://psyarxiv.com/9mpbn/>. Example code implementing methods in R will be provided. The speaker will present for 30-45 minutes, followed by a Q&A and discussion period.

-   [Slides](../seminar_2_stat_artefacts.pdf)

-   Video Recording

        {{< youtube YqUUEmhlDEE >}}

### December 17, 2021

***One-stage Meta-Analytic Structural Equation Modeling***

-   Speaker: [Suzanne Jak](http://www.suzannejak.nl/), University of Amsterdam

-   Description: Meta-analytic structural equation modeling (MASEM) refers to fitting structural equation models (such as path models or factor models) to meta-analytic data. The meta-analytic data generally consists of correlations across the variables in the path or factor model, obtained from multiple primary studies. In this talk, I will contrast univariate MASEM to multivariate MASEM. Univariate MASEM refers to performing multiple univariate meta-analyses in order to obtain a synthesized correlation matrix as input in a SEM program. Multivariate MASEM in contrast involves using multivariate meta-analysis to synthesize correlation matrices across studies (e.g., GLS, TSSEM, one-stage MASEM). I will show that although univariate MASEM is the default MASEM method in for example organizational psychology, results obtained from univariate MASEM cannot be trusted. The reason that univariate MASEM is still often used, may be that fitting MASEMs may be challenging for researchers that are not accustomed to working with R software and packages. Therefore, we developed webMASEM; a web application for MASEM. This app implements the one-stage MASEM approach, and allows users to apply multivariate MASEM in a user-friendly way.

-   [Slides](../seminar_3_MASEM.pdf)

-   Video Recording

        {{< youtube 0ykRk9WwHRA >}}

### January 21, 2022

***Implications of Open Science for Research Syntheses in Education***

-   Speaker: [Erika Patall](https://rossier.usc.edu/faculty/erika-patall/), University of Southern California

-   Description: Extensive debate about common, yet questionable research practices that lead to biased findings within social and health sciences has emerged over the last decade. Similar challenges likely apply to education research, though the field has been slow to address them. In this talk, I discuss current research norms, strategic solutions proposed under the broad rubric of "Open Science", and the implications of both for the way research syntheses in education are conducted and the quality of the information they produce. Strategies such as preregistration, transparent reporting, open materials and data, and registered reports stand to address significant threats to the validity of research syntheses. These include challenges associated with publication, dissemination, and selective reporting biases, comprehensive information retrieval, and opportunities to execute unique analytic approaches. Parallel solutions that address biases in the decision making and practices of researchers conducting and evaluating research syntheses will also be discussed, along with the challenges and tips associated with their implementation.

-   [Slides](../seminar_4_open_science.pdf)

-   Video Recording

        {{< youtube FF7AR65DAY0 >}}

### February 18, 2022

***Model-Building with Complex Meta-Regression: Strategies and Considerations***

-   Speaker: [Ryan Williams](https://www.air.org/experts/person/ryan-williams) is a Principal Researcher at American Institutes for Research (AIR) where he co-leads the Methods of Synthesis and Integration Center (MOSAIC). At AIR, his work focuses applied meta-analyses, methods for research synthesis, and applied impact evaluations. He spends his spare time with his family, avoiding communicable disease.

-   Description: In large scale meta-analyses, meta-regression model specification and determining variable (moderator) importance are increasingly common issues. This presentation will focus on some of those issues, using a recently completed synthesis ([Williams et al., 2022](https://doi.org/10.1080/19345747.2021.2009072)) as a working example. I will walk through how our team conceptualized an a priori meta-regression model to understand sources of heterogeneity using Cronbach's units, treatments, outcomes, and settings framework (UTOS; Cronbach, 1982). Then I will describe the results of our confirmatory modeling and the rationale for developing an exploratory study, using random forests, to evaluate the robustness of our conceptual model and its explanatory value. I will briefly walk through how we applied a random forest model to our data to identify unanticipated or complex relationships, and what we discovered. The remainder of the talk (and discussion) will focus on how modern, large-scale, meta-analyses, with a focus on heterogeneity, can benefit from machine learning applications to evaluate the quality of theoretically grounded modeling strategies.

-   [Slides](../seminar_5_exploring_heterogeneity.pdf)

-   Video Recording

        {{< youtube GPDZiRIYj_s >}}

### April 15, 2022

***Sensitivity Analyses for Unmeasured Confounding in Meta-Analyses***

-   Speaker: [Maya Mathur](https://www.mayamathur.com/), Stanford University

-   Description: Meta-analyses contribute critically to cumulative science, but they can produce misleading conclusions if their constituent primary studies are biased, for example by uncontrolled confounding in non-randomized studies. We provide practical guidance on how meta-analysts can address uncontrolled confounding, focusing primarily on sensitivity analyses that help quantify how biased the meta-analysis estimates might be. We discuss recently proposed sensitivity analyses that are straightforward to implement and interpret and that use somewhat less stringent statistical assumptions than earlier methods. We illustrate the methods' use by conducting sensitivity analyses for two prominent meta-analyses on the effect of being overweight on all-cause mortality. One meta-analysis reported a detrimental association, while the other reported a protective association, sparking ongoing debate. Our re-analyses suggest that given potential uncontrolled confounding, neither meta-analysis provides robust evidence for either detrimental or protective effects of being overweight.

-   [Slides](../seminar_6_causal.pdf)

-   Video Recording

          {{< youtube KRkmgN-Or5o >}}
