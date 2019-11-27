+++
title = "Presentation Titles, Abstracts and Slides"
description = ""
+++

The complete book of abstracts can be downloaded [here](/data/bookofabstracts.pdf).

<ul class="nav nav-tabs">
  <li class="active"><a data-toggle="tab" href="#tuesday">Tue</a></li>
  <li><a data-toggle="tab" href="#wednesday">Wed</a></li>
  <li><a data-toggle="tab" href="#thursday">Thu</a></li>
  <li><a data-toggle="tab" href="#friday">Fri</a></li>
</ul>
<div class="tab-content">
  <div id="tuesday" class="tab-pane fade in active">
    <h2>Invited Speakers: Medical</h2>
    <h4><i>Room: Exhibition Hall</i></h4>
    <a class="btn btn-template-main btn-sm expand-btn" type="button" data-toggle="collapse" data-target=".multi-collapse1" aria-expanded="false">Expand All</a>
    <div class="table-responsive">
      <table class="abstract-table">
        <thead>
          <tr>
            <th>Presenter</th>
            <th>Abstract Title</th>
            <th>Time</th>
            <th>Slides</th>
          </tr>
        </thead>
        <tbody>
          <tr class="clickable" data-toggle="collapse" id="1" data-target=".1collapsed">
            <td>James Carpenter</td>
            <td>Multilevel multiple imputation for health and survey data: your flexible (and robust) friend</td>
            <td>9:30 - 10:30</td>
            <td></td>
          </tr>
          <tr class="out budgets 1collapsed collapse multi-collapse1" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          Multiple imputation is now well established as a practical and flexible method for analyzing partially observed data under the missing at random assumption. However, in large datasets there are concerns about how to preserve heterogeneity in the relationship between variables in the imputation process.<p>Building on recent work, we describe an imputation model (and R software) which allows the covariance matrix of the variables to vary randomly across higher level units, which may represent health districts or hospitals.<p>We further show how this approach allows us to (i) include weights, when the substantive model is weighted; (ii) provide a degree of robustness to misspecification of the imputation model and (iii) extends to impute data consistent with interaction and non-linear effects under investigation.<p>We illustrate with examples from the UK Millennium Cohort Study and the UK Clinical Practice Research Datalink.<br><br>
          </td>
          </tr>
          <tr class="clickable" data-toggle="collapse" id="2" data-target=".2collapsed">
            <td>Max Moldovan</td>
            <td>Pursuing the cancer-schizophrenia disassociation paradox: genomes, phenomes and intimate conversations with inconclusive evidence</td>
            <td>13:30 - 14:30</td>
            <td></td>
          </tr>
          <tr class="out budgets 2collapsed collapse multi-collapse1" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          Positive and negative empirical findings of schizophrenia being protective against cancer remain a controversy and an active topic for debates among the intersection of oncologists, psychiatrists, epidemiologists and a diverse group of research scientists interested in the topic. I will present the vision of the paradox from different points of view, using a number of analysis and visualisation approaches from my current data science toolbox.<p>Firstly, I will take a position of a "genes-rule-it-all" theory proponent (while, in fact, being an opponent of the paradigm). I will share my experience of the exposure to genomics, and how my hopes and excitement were cut short by the inability of a SNP model to predict a well-defined phenotype when taken out of sample. Staying in the same role, I will introduce the Molecular Signatures Database (MSigDB) and an attempt to look at this gene expression signature information resource from a different angle.<p>Secondly, I will review epidemiological explanations behind the cancer-schizophrenia disassociation paradox, presenting the pair of disorders within the whole phenome network. While biases can help to justify the paradox, the doubt remains when one looks at bare numbers.<p>Finally, I will introduce a "geocentrism versus heliocentrism in cancer research" hypothesis and speculate about the role of dogmas in science, rates of clinical translation and prospects of moving to the brighter future.<br><br>
          </td>
          </tr>
          <tr class="clickable" data-toggle="collapse" id="3" data-target=".3collapsed">
            <td>Richard Cook</td>
            <td>Dependent selection and observation schemes in life history studies</td>
            <td>14:30 - 15:30</td>
            <td></td>
          </tr>
          <tr class="out budgets 3collapsed collapse multi-collapse1" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          Multistate models provide a powerful framework for the analysis of life history processes when the goal is to 
          characterize transition intensities, transition probabilities, state occupancy probabilities, and covariate 
          effects thereon.  Samples of individuals experiencing such processes are often constructed based on response-dependent
          selection schemes. Moreover, prospective data are often only available at random visit times realized over a finite 
          period of follow-up. We formulate a joint multistate model for the life history, selection, visit,
          and loss to followup processes.  This joint model is helpful when discussing the independence conditions necessary 
          to justify the use of standard likelihoods involving the life history model alone, and provides a basis for analyses 
          that accommodate dependence.  We consider settings with disease-driven visits and routinely scheduled visits and 
          develop likelihoods that accommodate partial information on the types of visits.  Simulation studies suggest that 
          suitably constructed joint models can yield consistent estimates of parameters of interest even under dependent 
          visit processes providing the models are correctly specified, but identifiability and estimability issues can arise. 
          An application is given to a cohort of individuals attending a rheumatology clinic where interest lies 
          in progression of joint damage. This is joint work with Jerry Lawless. <br><br>
          </td>
          </tr>
        </tbody>
      </table>
    </div>
    <!--                -->
    <!----First Stream --->
    <!--                -->
    <h2>Contributed Talks Session 1a: Biostatistics I</h2>
    <h4><i>Room: The Gallery</i></h4>
    <a class="btn btn-template-main btn-sm expand-btn" type="button" data-toggle="collapse" data-target=".multi-collapse2" aria-expanded="false" aria-controls="1collapsed 2collapsed 3collapsed">Expand All</a>
    <div class="table-responsive tg-wrap">
      <table class="abstract-table">
        <thead>
          <tr>
            <th>Presenter</th>
            <th>Abstract Title</th>
            <th>Time</th>
            <th>Slides</th>
          </tr>
        </thead>
        <tbody>
          <tr class="clickable" data-toggle="collapse" id="4" data-target=".4collapsed">
            <td>Hans Hockey</td>
            <td>Hockey sticks and broken sticks continued – enhancing the gold standard RCT for chronic diseases</td>
            <td>11:00 - 11:20</td>
            <td></td>
          </tr>
          <tr class="out budgets 4collapsed collapse multi-collapse2" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          This work was motivated by a previously given chronic rare disease real data example as analysed by a longitudinal hockey stick model. The gold standard randomized controlled trial (RCT) compares active and placebo treatment arms at a post-baseline timepoint sufficiently late enough for an active effect to be apparent. For this design the analysis of covariance of final values adjusted for baseline values is standard (hopefully!).<p>Similar but enhanced alternative design and analysis combinations in chronic diseases will be presented which have several possible advantages: there is the possibility of assessing the size of any placebo effect; there is less ethical and recruitment need to have the active group larger than the placebo group; missing data, particularly of the final value, is less critical to the analysis.<p>It is also conjectured that some of the circumstances which can favour these enhanced designs can also be used to help argue for single arm studies in rare chronic diseases, despite the lack of randomization.<br><br>
          </td>
          </tr>
          <tr class="clickable" data-toggle="collapse" id="5" data-target=".5collapsed">
            <td>Jessica Kasza</td>
            <td>From the stepped wedge to the staircase: the information content of stepped wedge trials</td>
            <td>11:20 - 11:40</td>
            <td></td>
          </tr>
          <tr class="out budgets 5collapsed collapse multi-collapse2" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          Stepped wedge cluster randomised trials are a type of longitudinal cluster randomised trial in which clusters, e.g. schools, hospitals, or geographical regions, are randomised to a particular set of treatment sequences. In standard stepped wedge trials, all clusters start in the control condition before switching, in a randomised order, to the intervention. The application of stepped wedge trials is increasing rapidly: a 2011 systematic review of published or registered stepped wedge trials found only 25, but as of July 2019, 210 stepped wedge trials were registered on clinicaltrials.gov. Stepped wedge trials are particularly useful in assessing interventions that will be rolled out or cannot be undone, e.g. changes in policies or cluster-wide education campaigns. However, stepped wedge trials are expensive and burdensome, requiring that all clusters contribute measurements for the entire trial duration. Recent work has shown that different cluster-period “cells” of the stepped wedge contribute different amounts of information to the estimation of the intervention effect. Such work suggests that “incomplete” stepped wedge trials in which clusters contribute measurements in a restricted set of trial periods may provide efficient alternatives to the full stepped wedge. <p>In this talk I will discuss the amount of information contributed by cluster-period cells of stepped wedge trials to the estimation of the effect of an intervention, where this is quantified by the increase in the variance of the intervention effect estimator when that cell is omitted. I will consider the impact of within-cluster correlation structure, treatment effect heterogeneity, implementation periods, and unequal cluster-period sizes on the pattern of information content. This work indicates that in many scenarios, “staircase” trials, a particular type of incomplete stepped wedge in which clusters provide measurements immediately before and after the treatment switch only, may prove to be efficient and less burdensome alternatives to the complete stepped wedge.<br><br>
          </td>
          </tr>
          <tr class="clickable" data-toggle="collapse" id="14" data-target=".14collapsed">
            <td>Nidhi Menon&#42;</td>
            <td>The effect of number of clusters and cluster sizes on multiple imputation in multilevel models</td>
            <td>11:40 - 12:00</td>
            <td></td>
          </tr>
          <tr class="out budgets 14collapsed collapse multi-collapse2" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          Missing data are a common phenomenon in public health research. Multiple Imputation (MI) has been long recognized as an attractive approach to handle missing values. Statisticians are now advocating the use of MI as a gold standard in solving the missing data problem. Despite its early conception and its numerous advantages over the traditional ad hoc methods, there is still limited application of MI in public health research. <p>The theory of multiple imputation requires that imputations be made conditional on the sampling design. Not accounting for complex sample design features, such as stratification and clustering, during imputations can yield biased estimates from a design-based perspective. <p>Most datasets in public health research show some form of natural clustering (individuals within households, households within the same district, patients within wards, etc.).  Cluster effects are often of interest in health research. In this study, we investigate through simulations different strategies for accounting for clustering when multiply imputing variables. Recent studies have identified methods to include fixed effects for clusters in imputations, however there is limited information on impact of varying number of clusters and cluster sizes on MI. <p>In this study, we simulate 3 level hierarchical data structures varying the number of clusters at each level. Missing values are present in covariates at each level in the data. We consider the impact of the combination of varying cluster sizes and proportion of missingness in imputation of covariates at each level in the dataset. This study implements the Gelman and Hill approach for imputation of missing data at higher levels by including aggregate forms of individual level measurements to impute for missing values at higher levels. The performance of popular methods of imputations, MICE and JoMo are compared. Performance measures include bias in estimates, mean squared errors and probability coverage of confidence intervals<br><br>
          </td>
          </tr>
          <tr class="clickable" data-toggle="collapse" id="15" data-target=".15collapsed">
            <td>Thomas Sullivan</td>
            <td>Multiple imputation for missing outcome data in trials involving independent and paired observations</td>
            <td>12:00 - 12:20</td>
            <td></td>
          </tr>
          <tr class="out budgets 15collapsed collapse multi-collapse2" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          Background: Trials involving a mixture of independent and paired data arise in many areas of health research, for example in paediatrics where outcomes can be collected on singletons and twins, and in ophthalmology, where one or both eyes may require treatment. An important consideration in these trials is the correlation in outcomes, or clustering, that occurs between observations from the same pair. When applying multiple imputation (MI) to address missing data, previous research suggests that any clustering in the data should be accounted for in the imputation and analysis models. However, most ad-hoc methods of MI for clustered data were designed with large and/or equal sized clusters in mind, and it is unclear how MI should be imeplemented in settings with independent and paired data.<p>Methods: Using simulated data the following MI approaches were evaluated: (1) MI ignoring clustering; (2) MI using chained equations with conditional imputation of the 2nd member of a pair; (3) MI performed separately by cluster size, and; (4) multi-level MI. Observations were allocated to one of two treatment groups using simple randomisation, with members of a pair randomised individually, to the same (cluster randomisation) or to opposite groups (opposite randomisation). <p>Results: When outcome data were missing at random, all MI methods produced unbiased treatment effect estimates. Although performance deficits were small, MI ignoring clustering and chained equations with conditional imputation produced confidence intervals for the treatment effect that were too narrow under cluster randomisation and too wide under opposite randomisation. MI performed separately by cluster size and multi-level MI performed well across the range of scenarios considered.<p>Conclusions: In trials involving a mixture of independent and paired observations, particularly those employing cluster or opposite randomisation, we recommend researchers apply multi-level MI or standard MI performed separately by cluster size to address missing outcome data.<br><br>
          </td>
          </tr>
          <tr class="clickable" data-toggle="collapse" id="8" data-target=".8collapsed">
            <td>Graham Hepworth</td>
            <td>Estimation of proportions by group testing with retesting of positive groups</td>
            <td>12:20 - 12:40</td>
            <td></td>
          </tr>
          <tr class="out budgets 8collapsed collapse multi-collapse2" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          In group testing (or pooled testing), material from individuals is pooled and tested in aggregate for the presence of an attribute, usually a disease.  Group testing for estimation of a proportion p has been applied in a wide range of fields, including virus prevalence in flowers, blood testing (especially for HIV), and transmission of viruses by mosquitoes.  Improved precision usually requires the testing of more groups, but in some situations it is difficult or expensive to obtain the required additional individuals.  If the testing procedure is non-destructive, retesting of groups comprising different combinations of individuals may be a useful option. <p>Hepworth & Watson (2017) developed an estimator of p for the retesting of a random grouping of individuals from the positive groups at the first stage.  The analytic complexity of this estimator led them to use simulation to examine its variance properties.  We have developed two closed-form analytic expressions for the variance of the second-stage estimator, and compared its performance with the results from the simulation.<p>Our analytical solutions give acceptable approximations in a reasonable range of circumstances.  They are most acceptable when the number of groups is not small and p is not large.  This is a useful result for group testing, which to be of major benefit, relies on a reasonable number of groups and a small to moderate prevalence.<p>Hepworth G & Watson RK (2017) Revisiting retesting in the estimation of proportions by group testing.  Communications in Statistics – Simulation and Computation 46:261–274.<p>Hepworth G & Walter SD (2019) Estimation of proportions by group testing with retesting of positive groups.  Communications in Statistics – Theory and Methods DOI:10.1080/03610926.2019.1620280). <br><br>
          </td>
          </tr>
        </tbody>
      </table>
    </div>
    <!--                 -->
    <!----Second Stream --->
    <!--                 -->
    <h2>Contributed Talks Session 1b: Modelling the Environment</h2>
    <h4><i>Room: Exhibition Hall</i></h4>
    <a class="btn btn-template-main btn-sm expand-btn" type="button" data-toggle="collapse" data-target=".multi-collapse3" aria-expanded="false" aria-controls="1collapsed 2collapsed 3collapsed">Expand All</a>
    <div class="table-responsive tg-wrap">
      <table class="abstract-table">
        <thead>
          <tr>
            <th>Presenter</th>
            <th>Abstract Title</th>
            <th>Time</th>
            <th>Slides</th>
          </tr>
        </thead>
        <tbody>
          <tr class="clickable" data-toggle="collapse" id="9" data-target=".9collapsed">
            <td>Rune Christiansen&#42;</td>
            <td>Towards causal inference for spatio-temporal data: adjusting for time-invariant latent confounders</td>
            <td>11:00 - 11:20</td>
            <td></td>
          </tr>
          <tr class="out budgets 9collapsed collapse multi-collapse3" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          In statistical causality, we are interested not only in modeling the behaviour of a system that is passively observed, but also how the system reacts to changes in the data generating mechanism. Given knowledge of the underlying causal structure, such interventional behaviour can often be estimated from purely observational data (e.g., using covariate adjustment). Typically, the assumption is that data are generated as independent replications from the same underlying mechanism — an assertion that is often hard to justify in practice: geographically varying conditions in which the system is embedded induce spatial heterogeneity, and close-by observations (in space and time) tend to be strongly dependent. In this talk, I present causal models for spatio-temporal data that are adapted to these characteristics, and introduce a simple approach that allows for the estimation of causal effects under the influence of arbitrarily many latent confounders, as long as these confounders do not vary across time. Non-parametric hypothesis tests for the existence of causal effects are constructed based on data resampling, and do not rely on any distributional assumptions on the spatial dependence structure of the data. The method is applied to the problem of inferring the (potential) causal relationship between armed conflict and tropical forest loss, based on a spatio-temporal data set from Colombia. This talk does not require any prior knowledge in causal inference. <br><br>
          </td>
          </tr>
          <tr class="clickable" data-toggle="collapse" id="10" data-target=".10collapsed">
            <td>Francis Hui</td>
            <td>Spatial Confounding in GEEs – Why the Working Correlation Matters (well, sort of)</td>
            <td>11:20 - 11:40</td>
            <td></td>
          </tr>
          <tr class="out budgets 10collapsed collapse multi-collapse3" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          Generalized Estimating Equations (GEEs) are a popular tool in many scientific disciplines for investigating the effects of covariates on the mean of a response. In the context of spatial data analysis, GEEs rely on specifying a regression model for the marginal mean, a variance function, and a spatial working correlation matrix characterizing the spatial autocorrelation between observational units. One of the main advantages of GEEs is that estimation of the covariate effects is robust to misspecification of the choice of (spatial) working correlation matrix: the choice only affects the efficiency of the estimator. <p>In ongoing research, we investigate the impact of spatial confounding in GEEs. That is, what happens when the covariates included in a GEE, where a spatial working correlation matrix is used, are also spatially correlated. Under the conditional mixed model approach, the issue of spatial confounding is explicit and arises due to artificial multicollinearity between the spatially correlated covariates and the spatial random effect. We show that for GEEs, such multicollinearity also arises but occurs implicitly between spatially correlated covariates and the spatial working correlation matrix. Results suggests different choices of the working correlation matrix can lead to different attributions of the effect of the covariate on the mean versus on the spatial correlation i.e., on the first versus second moment. In turn, we consider using a so-called “restricted spatial working correlation matrix” that ensures all the variability in the direction of the covariates is attributed to the marginal mean, and is more in line with the underlying aim of GEEs. The issue of standard error estimation via the sandwich covariance matrix, and how it is impacted by spatial confounding, will also be discussed.<br><br>
          </td>
          </tr>
          <tr class="clickable" data-toggle="collapse" id="12" data-target=".12collapsed">
            <td>Ian Renner</td>
            <td>Model reliability of presence-only species distribution models fitted with a lasso penalty</td>
            <td>11:40 - 12:00</td>
            <td></td>
          </tr>
          <tr class="out budgets 12collapsed collapse multi-collapse3" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          Species distribution models (SDMs) require the user to input information about species occurrence and environmental data to produce a map of predicted intensity of the species throughout the region of interest. When the species information comes in the form of presence-only data, which consists of a list of observed records, a point process model (PPM) may be used to map the species distribution. PPMs may be fitted with a number of software packages, including the well-known R package spatstat, which provides diagnostic tools and maps of uncertainty such that the reliability of the model may be assessed. Point process models may be fitted with a lasso-type penalty with the R package ppmlasso, which has been shown to improve predictive performance. However, the incorporation of the lasso-type penalty makes assessment of model reliability theoretically difficult as there is no closed-form standard errors for model coefficients or intensities. As such, the predicted output from ppmlasso is merely a point estimate of the true intensity surface. As these maps may be used to inform conservation decisions, practitioners may want to determine how reliable this output is.<br><br>
In this talk, I will present a new set of diagnostic tools that can provide insight regarding model reliability for point process models fitted with lasso-type penalties. These tools measure alignment of the coefficient estimates and fitted intensity maps between models fitted to random subsets of the input species data and the model fitted with all available species data. The trace plots of a number of measures of model alignment may therefore be used to determine the sample size at which the models appear to stabilise. I will demonstrate the use of these tools in modelling the distribution of stag beetles in France.<br><br>
          </td>
          </tr>
          <tr class="clickable" data-toggle="collapse" id="11" data-target=".11collapsed">
            <td>Emy Guilbault&#42;</td>
            <td>Fitting species distribution models with uncertain species labels using point process models.</td>
            <td>12:00 - 12:20</td>
            <td></td>
          </tr>
          <tr class="out budgets 11collapsed collapse multi-collapse3" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          The popularity of species distribution models (SDMs) and the suite of tools to fit them have greatly increased over the last decade. The most common type of species data is presence-only data, which comes from citizen science. Point process models (PPMs) provide a flexible way to fit SDMs to presence-only data. Nonetheless, the quality of presence-only records (both identification and positional location) that serve as input to presence-only SDMs can be questioned. However most species distribution modelling methods applied to presence-only data assume certainty about species identity, but there are many practical situations in which this may not be the case. As an example, observers can be unable to clearly differentiate close species and taxonomists can split a species into multiple distinct species. We investigate the latter case, in which the species identities of records prior to a taxonomic change are confounded. In this talk, I will present two new tools for accommodating confounded records in PPMs. With these tools, we reclassify and incorporate records with uncertain species identities via finite mixture modelling or an iterative algorithm inspired by machine learning methods. Through simulation, we compare performance in classification and in prediction of these tools with different implementations to a standard approach which uses only records with known species labels, varying species abundance, correlation among species distributions, and the proportion of records with missing species labels. We also apply the best-performing methods to fit the distribution of 3 species of native Australian frogs that belong to the genus Myxophies. Among these species, 2 were newly described in 2006 in the northern range of the genus distribution and thus confounded previous records in the area made over the previous few decades.<br><br>
          </td>
          </tr>
          <tr class="clickable" data-toggle="collapse" id="13" data-target=".13collapsed">
            <td>Louise McMillan</td>
            <td>clustglm and clustord: R packages for clustering with covariates for binary, count, and ordinal data</td>
            <td>12:20 - 12:40</td>
            <td></td>
          </tr>
          <tr class="out budgets 13collapsed collapse multi-collapse3" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          We present two new R packages for model-based clustering with covariates. Both packages can perform clustering and biclustering (clustering sites and species simultaneously, for example). Both use likelihood-based methods for clustering, which enables users to compare models using AIC and BIC as measures of relative goodness of fit. <p>clustglm implements techniques from Pledger and Arnold (2014) for handling binary and count data, or data from other single-parameter exponential family distributions, such as normal distributions with constant variance. It leverages glm and can fit pattern detection models that include individual-level effects alongside cluster effects. For example, when applied to presence/absence data, users can cluster sites and species while also taking into account any single-species effects, and any additional covariates. clustglm can also be applied to capture-recapture data, to cluster individuals based on their capture patterns over multiple occasions. <p>clustglm can accommodate balanced and non-balanced designs, and numerical or categorical covariates. It provides the clustering equivalent of biplots, and also profile plots. We will illustrate the use of clustglm with a selection of ecological datasets. <p>clustord handles ordinal categorical data, using techniques outlined in Fernández et al. (2016). It builds on the ordered stereotype model, which accommodates flexibility in the ordinal scale used. The clustering results can reveal when two ordinal categories are effectively equivalent and can be combined to simplify the model.<br><br>
          </td>
          </tr>
        </tbody>
      </table>
    </div>
    <!--                -->
    <!----First Stream --->
    <!--                -->
    <h2>Contributed Talks Session 2: Experimental Design</h2>
    <h4><i>Room: Exhibition Hall</i></h4>
    <a class="btn btn-template-main btn-sm expand-btn" type="button" data-toggle="collapse" data-target=".multi-collapse5" aria-expanded="false" aria-controls="1collapsed 2collapsed 3collapsed">Expand All</a>
    <div class="table-responsive  tg-wrap">
      <table class="abstract-table">
      <thead>
        <tr>
          <th>Presenter</th>
          <th>Abstract Title</th>
          <th>Time</th>
          <th>Slides</th>
        </tr>
      </thead>
        <tbody>
          <tr class="clickable" data-toggle="collapse" id="17" data-target=".17collapsed">
            <td>Emlyn Williams</td>
            <td>Error variance bias in neighbour balance and evenness of distribution designs</td>
            <td>16:00 - 16:20</td>
            <td></td>
          </tr>
          <tr class="out budgets 17collapsed collapse multi-collapse5" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          Neighbour balance and evenness of distribution designs help to address user concerns in the two-dimensional layout of agricultural field trials.  This is done by minimizing the occurrence of pairwise treatment plot neighbours and ensuring that the replications of treatments are spread out across rows and columns of a trial.  Such considerations result in a restriction on the normal randomization process for a row-column design which can lead to error variance bias.  In this talk results from the analysis of uniformity trial data are presented to demonstrate the degree of error variance bias for both resolvable and non-resolvable designs.  Comparisons are made with linear variance spatial designs. <p>Williams, E.R. and Piepho, H.P. (2018). An evaluation of error variance bias in spatial designs. Journal of Agricultural, Biological, and Environmental Statistics 23, 83-91.<p>Piepho, H.P., Michel, V. and Williams, E.R. (2018). Neighbour balance and evenness of distribution of treatment replications in row-column designs. Biometrical Journal 60, 1172-1189.<br><br>
          </td>
          </tr>
          <tr class="clickable" data-toggle="collapse" id="18" data-target=".18collapsed">
            <td>David  Steel</td>
            <td>Prof Ken Russell and the Design of Experiments for Generalized Linear Models</td>
            <td>16:20 - 16:40</td>
            <td></td>
          </tr>
          <tr class="out budgets 18collapsed collapse multi-collapse5" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          Prof Ken Russell passed away in August of this year. Ken made many contributions to the practice and theory of experimental design, through his excellent teaching, research, collaborations and work with industry. He recently published a major monograph on the Design of Experiments for Generalized Linear Models (CRC Press). To the best of my knowledge this is the first book to be written specifically on this topic. This talk will give a review of the book and its key ideas and results.<br><br>
          </td>
          </tr>
          <tr class="clickable" data-toggle="collapse" id="19" data-target=".19collapsed">
            <td>Richard Jarrett</td>
            <td>Designs with many singly replicated treatments</td>
            <td>16:40 - 17:00</td>
            <td></td>
          </tr>
          <tr class="out budgets 19collapsed collapse multi-collapse5" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          This has been a topic of enduring interest, culminating in the paper on p-rep designs by Cullis et al.(2006).  We will review a number of results, mainly for block designs, with and without random block effects, and extend this to the case where test lines are considered as random effects. An indication will be given of the implications for row-column designs and designs with spatial correlation. <br><br>
          </td>
          </tr>
        </tbody>
      </table>
    </div>
    <!--                -->
    <!--    Posters     -->
    <!--                -->
    <h2>Poster Session</h2>
    <h4><i>Room: The Gallery</i></h4>
    <div class="table-responsive  tg-wrap">
      <table class="abstract-table">
      <thead>
        <tr>
          <th>Presenter</th>
          <th>Poster Title</th>
        </tr>
      </thead>
        <tbody>
          <tr>
            <td>Angela Anderson</td>
            <td>Cross-validation of pasture biomass predictions from handheld NDVI sensor measures</td>
          </tr>
          <tr>
            <td>Mohammad Javad Davoudabadi&#42;</td>
            <td>Bayesian Approaches to Carbon Cycle Modelling</td>
          </tr>
          <tr>
            <td>Nathaniel Jewell</td>
            <td>Analysis of continuous water use data for wheat plants grown on a Droughtspotter platform</td>
          </tr>
          <tr>
            <td>Olena Kravchuk</td>
            <td>Comparative study of probability models for agriculture field index data</td>
          </tr>
          <tr>
            <td>Chris Lisle&#42;</td>
            <td>Fitting a nugget variance to the analysis of National Variety Trials</td>
          </tr>
          <tr>
            <td>Yao Lu</td>
            <td>Yield response curves using fixed effects vs random coefficient regression across environments</td>
          </tr>
          <tr>
            <td>Esther Meenken</td>
            <td>Multivariate analysis for Greenhouse Gas Emissions from New Zealand Sheep and Beef Farm Systems</td>
          </tr>
          <tr>
            <td>Lucas Peitton&#42;</td>
            <td>Is the SpATS model as good as we would like it to be for the spatial analysis of field trials?</td>
          </tr>
          <tr>
            <td>Nishika Ranathunga&#42;</td>
            <td>Computation of the expected value of a function of a chi-distributed random variable</td>
          </tr>
          <tr>
            <td>Sam Rogers</td>
            <td>A comparison of linear mixed model packages in R for analysis of plant breeding experiments</td>
          </tr>
          <tr>
            <td>Eugenia Settecase&#42;</td>
            <td>Exploration of trait relationships in mungbean using a multivariate linear mixed model</td>
          </tr>
          <tr>
            <td>Alan Welsh</td>
            <td>Random thoughts on p-values</td>
          </tr>
          <tr>
            <td>Carole Wright</td>
            <td>NIRS Classification</td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
  <div id="wednesday" class="tab-pane fade">
    <!-- Wed -->
    <!-- <div class="table-responsive"> -->
    <!--                -->
    <!----First Stream --->
    <!--                -->
    <h2>Contributed Talks Session 1a: Methods I</h2>
    <h4><i>Room: Vines</i></h4>
    <a class="btn btn-template-main btn-sm expand-btn" type="button" data-toggle="collapse" data-target=".multi-collapse6" aria-expanded="false" aria-controls="1collapsed 2collapsed 3collapsed">Expand All</a>
    <div class="table-responsive tg-wrap">
      <table class="abstract-table">
        <thead>
          <tr>
            <th>Presenter</th>
            <th>Abstract Title</th>
            <th>Time</th>
            <th>Slides</th>
          </tr>
        </thead>
        <tbody>
          <tr class="clickable" data-toggle="collapse" id="20" data-target=".20collapsed">
            <td>Paul Kabaila</td>
            <td>Confidence intervals centred on bootstrap smoothed estimators</td>
            <td>8:50 - 9:10</td>
            <td></td>
          </tr>
          <tr class="out budgets 20collapsed collapse multi-collapse6" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          Bootstrap smoothed (or bagged; Breiman, 1996) parameter estimators have been proposed as an improvement on estimators found after preliminary data-based model selection. The key result of Efron (2014) is a formula for a delta method approximation to the standard deviation of the bootstrap smoothed estimator. This formula is valid for any exponential family of models and has the attractive feature that it simply re-uses the parametric bootstrap replications that were employed to find this estimator. It also has the attractive feature that it is applicable in the context of complicated data-based model selection. It is natural then to propose the use of a confidence interval that is centred on the bootstrap smoothed estimator and has width proportional to the estimate of this approximation to the standard deviation. We describe the results of an evaluation of the performance of this confidence interval, using a testbed that consists of two nested linear regression models and preliminary model selection using a t-test.<p> References<p>Breiman, L. (1996) Bagging predictors. Machine Learning.<p>Efron, B. (2014) Estimation and accuracy after model selection. Journal of the American Statistical Association.<p>Kabaila, P. and Wijethunga, C. (2019) Confidence intervals centred on bootstrap smoothed estimators. Australian & New Zealand Journal of Statistics.<p>Kabaila, P. and Wijethunga, C. (2019) On confidence intervals centred on bootstrap smoothed estimators. Stat. <br><br>
          </td>
          </tr>
          <tr class="clickable" data-toggle="collapse" id="21" data-target=".21collapsed">
            <td>Fernando Marmolejo-Ramos</td>
            <td>Towards distributional analyses of biomarker data</td>
            <td>9:10 - 9:30</td>
            <td></td>
          </tr>
          <tr class="out budgets 21collapsed collapse multi-collapse6" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          Current literature reviews of published datasets in the cognitive sciences (e.g. psychology, education, neuroscience) indicate that normally distributed data is not the norm but the exception. One such type of data is biomarker data. In a nutshell, biomarkers can be redefined as measures that index changes in neuropsychobiological states. This definition hence includes, among others, measures such as reaction times, event-related potentials, thermographic data, and blood pressure. Canonical statistical methods (e.g. t-tests, ANOVA) give biased results when dealing with non-normal data. The goal of this talk is to provide a snapshot of new statistical techniques that allow proper distributional and robust analyses. The emphasis will be on statistical graphics and conceptual definitions rather than mathematical elaborations. It is argued that adopting these techniques will ultimately lead to novel findings by revamping the way in which biomarker data are explored and analysed.<br><br>
          </td>
          </tr>
          <tr class="clickable" data-toggle="collapse" id="22" data-target=".22collapsed">
            <td>Linh Nghiem</td>
            <td>Simulation-Selection-Extrapolation: Estimation in High Dimensional Errors-in-Variables Models</td>
            <td>9:30 - 9:50</td>
            <td></td>
          </tr>
          <tr class="out budgets 22collapsed collapse multi-collapse6" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          Errors-in-variables models in high-dimensional settings pose two challenges in application. Firstly, the number of observed covariates is larger than the sample size, while only a small number of covariates are true predictors under an assumption of model sparsity. Secondly, the presence of measurement error can result in severely biased parameter estimates, and also affects the ability of penalized methods such as the lasso to recover the true sparsity pattern. A new estimation procedure called SIMSELEX (SIMulation-SELection-EXtrapolation) is proposed. This procedure makes double use of lasso methodology. Firstly, the lasso is used to estimate sparse solutions in the simulation step, after which a group lasso is implemented to do variable selection. The SIMSELEX estimator is shown to perform well in variable selection, and has significantly lower estimation error than naive estimators that ignore measurement error. SIMSELEX can be applied in a variety of errors-in-variables settings, including linear models, generalized linear models, and Cox survival models. It is furthermore shown in the supporting information how SIMSELEX can be applied to spline-based regression models. A simulation study is conducted to compare the SIMSELEX estimators to existing methods in the linear and logistic model settings, and to evaluate performance compared to naive methods in the Cox and spline models. Finally, the method is used to analyze a microarray dataset that contains gene expression measurements of favorable histology Wilms tumors. <br><br>
          </td>
          </tr>
          <tr class="clickable" data-toggle="collapse" id="23" data-target=".23collapsed">
            <td>Brenton R Clarke</td>
            <td>Trimmed Estimators - and a Hybrid-Censored Data Approach to Estimation</td>
            <td>9:50 - 10:10</td>
            <td></td>
          </tr>
          <tr class="out budgets 23collapsed collapse multi-collapse6" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
         Using the idea of trimmed likelihood in location, we revisit the functional form of the trimmed mean and specify the functional form of the trimmed likelihood estimator as per Bednarski and Clarke (1993).<br>This definition leads in the case of the exponential distribution to a naturally robust estimator which is highly efficient whose functional form is weakly continuous and Fr&eacute;chet differentiable at the exponential model. See Clarke et al (2000). This is known as the &beta;-trimmed mean.  But what about censored data?  Should we use the maximum likelihood estimator (mle) because censoring  seemingly implies outliers are automatically taken care of?  We explore a proposal of a hybrid estimator that combines the &beta;-trimmed mean and the mle for some interesting results. See Clarke et al. (2017).<br>
          </td>
          </tr>
          <tr class="clickable" data-toggle="collapse" id="24" data-target=".24collapsed">
            <td>Michael Stewart</td>
            <td>Robust scale estimation under small measurement errors</td>
            <td>10:10 - 10:30</td>
            <td></td>
          </tr>
          <tr class="out budgets 24collapsed collapse multi-collapse6" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          Our motivating example is the estimation of robust scale functionals (like interquartile range or median absolute deviation) of the latent distribution in random effect models. This can be cast as a measurement error problem, where we "estimate" the random effects associated with each cluster. These estimates can in turn be regarded as the true random effects, plus some measurement errors. By "small measurement errors" we mean that we adopt a particular asymptotic scheme where both the number of clusters, and their sizes, tend to infinity. We propose to apply a "missing information principle" whereby we approximate the conditional expectation of the semiparametrically efficient score equations, given the observed data. We report some very interesting simulation study results and briefly sketch some accompanying theory. <br><br>
          </td>
          </tr>
        </tbody>
      </table>
    </div>
    <!--                 -->
    <!----Second Stream --->
    <!--                 -->
    <h2>Contributed Talks Session 1b: Mixed Models in Agriculture</h2>
    <h4><i>Room: Exhibition Hall</i></h4>
    <a class="btn btn-template-main btn-sm expand-btn" type="button" data-toggle="collapse" data-target=".multi-collapse7" aria-expanded="false" aria-controls="1collapsed 2collapsed 3collapsed">Expand All</a>
    <div class="table-responsive tg-wrap">
      <table class="abstract-table">
        <thead>
          <tr>
            <th>Presenter</th>
            <th>Abstract Title</th>
            <th>Time</th>
            <th>Slides</th>
          </tr>
        </thead>
        <tbody>
          <tr class="clickable" data-toggle="collapse" id="25" data-target=".25collapsed">
            <td>Bethany Macdonald</td>
            <td>Performance of factor analytic models in multi-environment trial data with small variety numbers</td>
            <td>8:50 - 9:10</td>
            <td></td>
          </tr>
          <tr class="out budgets 25collapsed collapse multi-collapse7" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          Much of the research undertaken in crop science involves evaluating varieties in field trials spanning a range of years and locations, where data arising from these sets of trials are known as multi-environment trial (MET) data. Analysis methods for MET data are concerned with investigating the nature of the variety by environment (VxE) effects, which describe the performance of different varieties across different environments, often with the aim of determining those varieties with superior performance. Ideally the variance of the VxE effects would be estimated using an unstructured form, assumed to be of full rank, however, this estimation is computationally difficult and can be unstable. The factor analytic (FA) model proposed by Smith et al. (2001) offers a more parsimonious option and has been shown to provide a good approximation to the unstructured form. The FA model has been shown to model the VxE effects accurately when there are large numbers of varieties, however, the accuracy of the model when variety numbers are small or varietal concurrence (the number of varieties in common between trials) is varied is unclear. The accuracy of FA models in scenarios when variety numbers are small and VxE and concurrence patterns vary was investigated through simulation. The study considered four model types for the variance of the VxE effects for MET data, with 10, 15, 25 and 50 varieties per trial. These data sets contained three types of VxE patterns, two levels of varietal concurrence and nine or 52 trials, resulting in 48 different scenarios. This study found that the accuracy of the FA model is affected when the number of varieties per trial are small, but the extent is dependent on other factors such as the number of trials and underlying VxE pattern.  <br><br>
          </td>
          </tr>
          <tr class="clickable" data-toggle="collapse" id="26" data-target=".26collapsed">
            <td>Bethany Rognoni</td>
            <td>An evaluation of separable variance structures for highly genetically correlated environments</td>
            <td>9:10 - 9:30</td>
            <td></td>
          </tr>
          <tr class="out budgets 26collapsed collapse multi-collapse7" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          In agricultural field trials, genotypes can be tested in the presence of interacting factors, resulting from either imposed treatments, repeated measurements or across multiple environments. When the aim is to select superior performing genotypes under these conditions, the factorial combination of conditions is often collapsed into one overall ‘environment’ factor, with a genetic variance structure fitted for this term, in a linear mixed model framework. This enables the estimation of a separate genetic variance for each of the levels (referred to as environment types) corresponding to the combinations of the original factorial structure, along with genetic covariance between the environment types. <p>As an alternative to this, an individual genetic variance structure for each of the factors can be fitted, resulting in a separable variance model. This may be a more parsimonious approach to modelling the genetic variance due to estimation of fewer parameters in total, and could provide a more intuitive interpretation of genotype behaviour across environment types. However, separable models have been shown to be less flexible, as they impose more restrictive variance structures. <p>A set of nematode resistance field trials motivated the exploration of separable variance models, where final nematode counts for each genotype were measured under three different soil depths, two previous nematode population densities resulting from prior crops and three trials. The analysis was first conducted using an overall environment model, where each environment represented a unique combination of soil depth, nematode population and trial. This model showed consistently high genetic correlations between all pairs of environments. The analysis was then performed using a separable genetic variance structure for the three-way factorial. There were substantial differences in the genetic variances and correlations that resulted from the different parameterisation of both models. <br><br>
          </td>
          </tr>
          <tr class="clickable" data-toggle="collapse" id="27" data-target=".27collapsed">
            <td>Isabel Munoz-Santa</td>
            <td>Multi environment trial analysis to determine the tolerance of cereal varieties to cyst nematode</td>
            <td>9:30 - 9:50</td>
            <td></td>
          </tr>
          <tr class="out budgets 27collapsed collapse multi-collapse7" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          Cereal Cyst nematodes (CCN) are considered a major nematode pest which cause significant yield losses in wheat and barley with a high economic cost to the grain industry.  A feasible solution is to breed for varieties which are tolerant; i.e. varieties which are able to yield in the presence of CCN in the field, this being an important research area for cereal nematologists.<p>In this study, we conducted 6 field trials from 2011 to 2018 in South Australia and Victoria with the objective of providing tolerance ratings of 92 different cereal varieties under high and low levels of pre-established nematode densities in the field.  Multi environment trial analyses were used to analyse the data where the term environment refers to each year by location by nematode density combination. Spatial techniques were used to account for the spatial variability in each trial and a factor analytic model was fitted to model the genotype by environment interaction effects. <p>Multi environment trial analyses revealed high genetic correlation between high and low environments for each of the trials. This indicates that selecting varieties under high levels of CCN is equivalent to select varieties under low levels and thus analogous to select high yielding varieties irrespective of the nematode density. Therefore, a measure to assess the performance of varieties under high levels of nematodes independently of their performance under low levels was defined and named “tolerance index”.<p>Multi environment trial analyses together with the tolerance index allowed us to select for high yielding varieties as well as give a more useful information to growers in relation to the comparison of varieties between high and low levels of CCN. The definition of the tolerance index and results obtained from this set of trials will be presented in this talk. <br><br>
          </td>
          </tr>
          <tr class="clickable" data-toggle="collapse" id="28" data-target=".28collapsed">
            <td>Clayton Forknall</td>
            <td>An across trials random regression approach to describe tolerance of wheat cultivars to disease</td>
            <td>9:50 - 10:10</td>
            <td></td>
          </tr>
          <tr class="out budgets 28collapsed collapse multi-collapse7" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          In plant pathology, tolerance to disease can be defined as the rate of change in productivity (yield), given a unit increase in pathogen burden. When applied to field crops, experiments to compare the tolerance of cultivars requires the establishment of a range of pathogen burdens over which the grain yield of a cultivar is measured, where tolerance to disease is then defined as the slope of a regression of yield against pathogen burden. <p>A recent publication (Forknall et al. (2019), Phytopathology) describes a method for the statistically robust design and analysis of a single field experiment to quantify the rate of change in yield per unit increase in pathogen burden of five wheat cultivars for the disease crown rot. Using a random regression approach, implemented in a linear mixed model (LMM) framework, response curves describing the relationship between yield and crown rot pathogen burden were estimated for each of the cultivars in the experiment. <p>This methodology is now extended to an across trials random regression approach, implemented in an LMM framework, which enables the estimation of different response curves for each cultivar in each experiment, where the response of each cultivar is modelled around an overall (average) yield response profile for each experiment. This modelling approach also provides a means of capturing the genetic correlation (covariance) between model parameters, both within and between experiments. <p>The model is demonstrated by an application to 15 field experiments, estimating the yield response of the same set of five wheat cultivars to crown rot. The analysis revealed variation in the rate of change in yield, or tolerance, of cultivars across experiments, identifying that the tolerance of some cultivars was more influenced by environmental conditions than others. Also presented are graphical tools to assist in unlocking the interaction between cultivars tolerance and environmental conditions. <br><br>
          </td>
          </tr>
          <tr class="clickable" data-toggle="collapse" id="29" data-target=".29collapsed">
            <td>Michael Mumford</td>
            <td>Clustering environments in a combined trial analysis of yield response to plant population</td>
            <td>10:10 - 10:30</td>
            <td></td>
          </tr>
          <tr class="out budgets 29collapsed collapse multi-collapse7" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          One of the key management practices of interest in agricultural crops is yield response to plant population and its contribution to yield in different genetic backgrounds. When field trials are run across multiple environments (i.e. years and locations), it is imperative to model the environment effects and the interaction of environment with hybrid and plant population. The challenge is then to compare the response models across environments. <p>A fixed effects combined trial analysis for yield response to plant population in a linear mixed model framework is presented. Clustering of the treatments (e.g. hybrid and environment combinations) is performed such that parallel curves are fitted to treatments within the same cluster to i) simplify the interaction and ii) increase the information used for fitting each response function by combining data across treatments within the same cluster. The categorisation of treatments to clusters is considered adequate when there is no significant interaction effect between plant population and treatment within each cluster. This presentation will focus on an objective method for categorising treatments into clusters. Furthermore, a sensitivity analysis will be presented to explore the adequacy of the proposed clustering methodology.<p>The methodology is applied to a large set of sorghum trials implemented across New South Wales, Australia in two seasons consisting of different hybrids, row spacings and trial locations. Furthermore, it provides a general framework for a fixed effects regression analysis in a linear mixed model framework that can account for i) experimental design terms, ii) separate residual variances and iii) spatial field trend at each trial. <br><br>
          </td>
          </tr>
        </tbody>
      </table>
    </div>
    <h2>Invited Speakers: Environmental</h2>
    <h4><i>Room: Exhibition Hall</i></h4>
    <a class="btn btn-template-main btn-sm expand-btn" type="button" data-toggle="collapse" data-target=".multi-collapse8" aria-expanded="false" aria-controls="1collapsed 2collapsed 3collapsed">Expand All</a>
    <div class="table-responsive">
      <table class="abstract-table">
        <thead>
          <tr>
            <th>Presenter</th>
            <th>Abstract Title</th>
            <th>Time</th>
            <th>Slides</th>
          </tr>
        </thead>
        <tbody>
          <tr class="clickable" data-toggle="collapse" id="30" data-target=".30collapsed">
            <td>Christopher K. Wikle</td>
            <td>Using Deep Neural Models to Facilitate Statistical Modeling of Complex Spatio-Temporal Dynamics</td>
            <td>11:00 - 12:00</td>
            <td></td>
          </tr>
          <tr class="out budgets 30collapsed collapse multi-collapse8" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          Spatio-temporal data are ubiquitous in the sciences and engineering, and their analysis is important for understanding and predicting a wide variety of processes. One of the difficulties with statistical modeling of spatial processes that change in time is the complexity of the dependence structures that must describe how such a process varies, and the presence of high-dimensional complex datasets and large prediction domains. It is particularly challenging to specify parameterizations for nonlinear dynamic spatio-temporal models (DSTMs) that are simultaneously useful scientifically, efficient computationally, and allow for proper uncertainty quantification.  Alternatively, the machine learning community has developed a suite of deep neural models and learning paradigms (e.g., convolutional neural networks, recurrent neural networks, reinforcement learning) that can be combined in novel ways to predict spatio-temporal processes.  However, these deep neural models are typically implemented in a deterministic framework that limits formal inference.  Here we explore some recent attempts to build hybrid models in which deep neural models can be embedded within a formal statistical DSTM framework. The approaches are illustrated with examples applied to environmental and ecological data.<br><br>
          </td>
          </tr>
          <tr class="clickable" data-toggle="collapse" id="31" data-target=".31collapsed">
            <td>Blair Robertson</td>
            <td>Quasi-random spatially balanced sampling</td>
            <td>12:00 - 13:00</td>
            <td></td>
          </tr>
          <tr class="out budgets 31collapsed collapse multi-collapse8" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          A spatial sampling design determines where sample locations are placed in a study area. The main objective is to select sample locations in such a way that valid scientific inferences can be made to all regions of the study area. To achieve good estimates of population characteristics, the spatial pattern of the sample should be similar to the spatial pattern of the population. However, the spatial pattern of the response variable is usually not known. Fortunately, when sampling natural resources, nearby locations tend to be similar because they interact with one another and are influenced by the same set of factors. This means sample efficiency can be increased by spreading sample locations evenly over the resource. A sample that is well-spread over the resource is called a spatially balanced sample. In this talk, we show how quasi-random sequences can be used to draw spatially balanced samples from natural resources. <br><br>
          </td>
          </tr>
        </tbody>
      </table>
    </div>
    <!-- </div> -->
    <!-- Wed -->
  </div>
  <div id="thursday" class="tab-pane fade">
    <!-- Thurs -->
    <!--                -->
    <!----First Stream --->
    <!--                -->
    <h2>Contributed Talks Session 1a: Methods II</h2>
    <h4><i>Room: Vines</i></h4>
    <a class="btn btn-template-main btn-sm expand-btn" type="button" data-toggle="collapse" data-target=".multi-collapse9" aria-expanded="false" aria-controls="1collapsed 2collapsed 3collapsed">Expand All</a>
    <div class="table-responsive tg-wrap">
      <table class="abstract-table">
        <thead>
          <tr>
            <th>Presenter</th>
            <th>Abstract Title</th>
            <th>Time</th>
            <th>Slides</th>
          </tr>
        </thead>
        <tbody>
          <tr class="clickable" data-toggle="collapse" id="32" data-target=".32collapsed">
            <td>Takeshi Kurosawa</td>
            <td>A new Liu estimator under a linear constraint</td>
            <td>8:50 - 9:10</td>
            <td></td>
          </tr>
          <tr class="out budgets 32collapsed collapse multi-collapse9" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          A problem in parameter estimation for a linear model arises multi-colinearity if a data set is ill-posed. One of the solutions, Liu (1993) proposed his estimator called the Liu estimator. Furthermore, Kaciranlar et al. (1999) generalized the Liu estimator under the condition with a linear constraint among the parameters. However, their estimator is an ad-hoc method because they treated the two problems independently. In this study, we interpret the Liu estimator as the solution of a certain loss function, and then we propose a new estimator under the condition with the linear constraint. We show theoretical bias and RMSE of our estimator and give a necessary and sufficient condition for the superiority of our estimator against other estimators in terms of RMSE. We also perform a simple simulation study using empirical RMSE. <br><br>
          </td>
          </tr>
          <tr class="clickable" data-toggle="collapse" id="33" data-target=".33collapsed">
            <td>Zhanglong Cao</td>
            <td>Model selection and principle of parsimony in statistical modelling in agriculture</td>
            <td>9:10 - 9:30</td>
            <td></td>
          </tr>
          <tr class="out budgets 33collapsed collapse multi-collapse9" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          Model selection is an important issue in biostatistical, psychological and agricultural studies. Root mean squared error (RMSE), Akaike's information criterion (AIC), Bayesian information criterion (BIC) and their relatives are commonly used as selection criteria for goodness-of-fit of statistical models. However, there is no robust technique that can be applied in every aspect of parameter estimation and model selection. Sometimes, the winning model is 'cursed', while the best model based on the selection criteria leads to over-fitting in practice. Goodness-of-fit must be balanced against model complexity to avoid over-fitting issues. We discuss the trap in model selection and the principle of parsimony, and present a weighted neighbouring cross-validation method. The latter will be illustrated on agricultural experimental data set. <br><br>
          </td>
          </tr>
          <tr class="clickable" data-toggle="collapse" id="34" data-target=".34collapsed">
            <td>Hwan-Jin Yoon</td>
            <td>On the effect of dependencies between regressors and random effects when analysing hierarchical structured data</td>
            <td>9:30 - 9:50</td>
            <td></td>
          </tr>
          <tr class="out budgets 34collapsed collapse multi-collapse9" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          Hierarchically structured data arises frequently in practice, in many fields of sciences including social science. Linear mixed models (LMMs) is one of the most common statistical methods to deal with the structured or clustered data.<p> Yoon & Welsh (2019) studied the effect of ignoring clustering in $x$ on fitting LMM, and showed that it can be obtained misleading assessments of both the association between $y$ and $x$ and of the variance components. They also showed that, as the within cluster variance of $x$, $\tau_x$, increases, the likelihood and the REML criterion develop two distinct local maxima and which of these is the global maximum changes at the jump point. <p>In LMMs for clustered or hierarchical structured data, regressors can be correlated with random effects. When the random effects and regressors independence assumptions are violated, not only regression coefficient estimators but also variance components can be severely biased. <p>In this study, we investigate how the violation of the random effects and regressors independence assumption could affect on the estimates of parameters and compare the results with the effect of ignoring clustering in $x$ when fitting LMM (Yoon & Welsh). We also extend our study to the case of correlated binary data. <br><br>
          </td>
          </tr>
          <!-- <tr class="clickable" data-toggle="collapse" id="35" data-target=".35collapsed">
            <td>Olena Kravchuk</td>
            <td>Comparative study of probability models for agriculture field index data</td>
            <td>9:50 - 10:10</td>
            <td></td>
          </tr>
          <tr class="out budgets 35collapsed collapse multi-collapse9" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
         This simulation study is motivated by the challenges of the analysis of field indices, like Harvest Index and Nutrient Use Efficiencies, in agriculture research. The index data we are interested in represents the quotient of two positively correlated random variables, X/(X+Y), but is only observed as a single index variate, Z. Based on the analysis of that index, important decisions are made about the ranking of agronomic factors and conditions. In this study, we are concerned with probability models for such indices, considering and contrasting several choices for X and Y. The choices include: normal, Beta and log-normal distributions, as well as mixtures of either Beta or log-normal. We demonstrate that the mixture of log-normal provides an identifiable and flexible model. <br><br> -->
          </td>
          </tr>
          <tr class="clickable" data-toggle="collapse" id="36" data-target=".36collapsed">
            <td>Warren Muller</td>
            <td>Modelling and Parameterization of Soil-Water Retention Curves</td>
            <td>9:50 - 10:10</td>
            <td></td>
          </tr>
          <tr class="out budgets 36collapsed collapse multi-collapse9" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          The prediction of soil water storage and water supply to plants is essential in the investigation of vegetation response to rainfall. In particular, soil water retention curves (WRCs) which depict the relationship between the volumetric water content (VWC) and the soil water potential (h) are used by soil scientists in their studies of soil hydraulic properties. <p>If the shape of the water retention curve is sigmoid, then such data sets can be characterized by several models. The most commonly used model is the van Genuchten model (Soil Sci. Soc. Am. J. 44, 1980, 892-898). <p>Fitting the van Genuchten model to data sets relating VWC to h involves estimation of four parameters, some of which have a physical significance in understanding soil-water relationships. However typically these data sets only have 8 to 10 (VWC, h) pairs, which leads to difficulty in estimating some of the parameters and, in some cases, the van Genuchten model is difficult to fit.<p>We fitted the van Genuchten model to VWC vs. h data for 35 water retention curves from semi-arid rangeland soils and seven vineyard soils from the Yass Valley, NSW. We present examples of these fitted models. Some new parameters were derived from the fitted values, and relationships between the four estimated parameters and these derived parameters are also presented. The results from this study show that<p>
          (i)	On some occasions the van Genuchten model fits poorly or doesn’t fit, so is inappropriate;<br>
          (ii)	There are strong relationships between some of the estimated and derived parameters, meaning the model is most likely over-parametrized;<br>
          (iii)	Alternative models should be used when the VWC vs. h relationship is not a distinct sigmoid shape, for example curvilinear or near linear. <br><br>
          </td>
          </tr>
        </tbody>
      </table>
    </div>
    <!--                 -->
    <!----Second Stream --->
    <!--                 -->
    <h2>Contributed Talks Session 1b: Collaboration</h2>
    <h4><i>Room: Exhibition Hall</i></h4>
    <a class="btn btn-template-main btn-sm expand-btn" type="button" data-toggle="collapse" data-target=".multi-collapse10" aria-expanded="false" aria-controls="1collapsed 2collapsed 3collapsed">Expand All</a>
    <div class="table-responsive tg-wrap">
      <table class="abstract-table">
        <thead>
          <tr>
            <th>Presenter</th>
            <th>Abstract Title</th>
            <th>Time</th>
            <th>Slides</th>
          </tr>
        </thead>
        <tbody>
          <tr class="clickable" data-toggle="collapse" id="37" data-target=".37collapsed">
            <td>Susan Wilson</td>
            <td>Big Biometric Data: A Biostatistical Perspective</td>
            <td>8:50 - 9:10</td>
            <td></td>
          </tr>
          <tr class="out budgets 37collapsed collapse multi-collapse10" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          Technological advances in biology and medicine, ranging from high-throughput sequencing to wearable electronic devices, are producing a “tsunami” of big biometric data. These data are of very widely varying types and quality. Many challenges abound on how to deal with such data, including wide-ranging deliberations concerning statistical modelling. This presentation will give an overview, including some current developments to meet the more pressing of these challenges. As well, in medicine in particular, big biometric data are giving rise to subtle and evolving ethical issues, many of which concern data analysts. Particular attention will be given to how these affect modern developments including applications such as personalised medical treatment. <br><br>
          </td>
          </tr>
          <tr class="clickable" data-toggle="collapse" id="38" data-target=".38collapsed">
            <td>Teresa Neeman</td>
            <td>Bridging the gap between science and statistics</td>
            <td>9:10 - 9:30</td>
            <td></td>
          </tr>
          <tr class="out budgets 38collapsed collapse multi-collapse10" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          Biology has undergone a huge transformation in the last 50 years from an observational science with occasional data to an experimental science with terabytes of data. The computational challenges in visualising and analysing large biological data sets are formidable for most biologists who trained in more data-naïve environments. This is potentially a huge opportunity for statisticians, whose training can help biologists discover mechanisms, patterns of behaviour, and even new biological paradigms. But training research students often occurs in “silos” in both fields, leaving huge communication gaps between the biological sciences and statistics.  Biologists miss the chance to sophisticated statistical machinery that may elucidate biological functions. Statisticians miss out on discovering the power of data to address important questions.  In this talk, I explore how we can start to bridge this communication gap. As statisticians, we need to teach biologists statistical concepts that are relevant to experimental sciences. These concepts need to emphasise experimental design and mixed effects models. We need to challenge ourselves to learn the language of biologists and challenge our statistics students with real-life complex data problems. Finally, we need to connect research students with one another and encourage research collaborations. <br><br>
          </td>
          </tr>
          <tr class="clickable" data-toggle="collapse" id="39" data-target=".39collapsed">
            <td>Sharon Nielsen</td>
            <td>Statistics for agronomists: a constructive synthesis of workplace learning and community of practice</td>
            <td>9:30 - 9:50</td>
            <td></td>
          </tr>
          <tr class="out budgets 39collapsed collapse multi-collapse10" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          Stakeholders in agronomy, and many other discipline areas, are promoting reproducible and transparent research, allowing research results to be replicated. The need for scientific rigour is paramount to the agronomic industry and can be achieved through appropriate design (with replication and randomisation) and robust and appropriate modelling techniques.<p>Agronomic evaluation of plants – quantity and quality, fertilisers and herbicides and pest control strategies are achieved through agronomic experiments, usually grown in the field, glasshouse or temperature control rooms. During the past three years staff from SAGI-STH training program have developed and run a series of statistical workshops, using adult learning methodologies, to improve the statistical competency of agronomists who conduct these agronomic experiments.   The workshops start with an introduction to R, move through design and then analysis of agronomic experiments and end by introducing these scientists to reproducible research through R markdown. The workshops use active learning strategies and real-world examples relevant to the researchers.<p>On completion of the workshops, participants are then invited to join our community of practice, where we explore their data and work on solving statistical problems as a team. The community of practice is via online meetings, which are recorded so that participants can join synchronously or asynchronously. In this talk we explore the benefits of these workshops and community of practice and what it has meant in practice to the agronomists. <br><br>
          </td>
          </tr>
          <tr class="clickable" data-toggle="collapse" id="40" data-target=".40collapsed">
            <td>Esther Meenken</td>
            <td>Uncertainty in digital agriculture: An interdisciplinary perspective</td>
            <td>9:50 - 10:10</td>
            <td></td>
          </tr>
          <tr class="out budgets 40collapsed collapse multi-collapse10" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          Digitilisation in agricultural systems provides more, and increasingly real time, data to farmers, consumers, and others along the supply chain than ever before. Turning this data into actionable knowledge through eg bio-physical or statistical models should aid decisions related to activities such as farm management, policy development and product selection. A connected farm has data generating IoT systems proliferated throughout: In and on the soil, monitoring weather patterns and crop growth, and tracking the movement, interactions and welfare of animals. This burgeoning supply of data is accompanied by uncertainty that carries through and is modified as users perceive and interact with it.  For example, a researcher building a crop simulation model will be subject to sensor uncertainties due to bias, lack of precision, sensor failure and incomplete calibration of the sensors.  The model will exhibit direct uncertainties reflecting a) these measurement errors as well as b) lack of complete knowledge about the system being modelled and c) scenario specification. On the other hand, a farmer using information provided by the model to manage irrigation allocation may additionally experience indirect uncertainties stemming from, e.g., a lack of trust in the modellers or communicators which decrease the perceived certainty of a model, particularly in contexts where trust functions as a coping mechanism for an inability to fully assess a model’s direct uncertainty. Uncertainty may also arise due to ‘contextual uncertainty’, defined as the bio-physical or socio-cultural environment which shapes the structure of the model or the way it is used, and determines how ‘fit-for-purpose’ it may be. We hypothesise a conceptual framework that attempts to visually indicate the relative uncertainties as data and biophysical/sociocultural uncertainty are incorporated into a model and as the model in turn becomes incorporated into wider, and increasingly complex, contexts once shared and used. <br><br>
          </td>
          </tr>
          <tr class="clickable" data-toggle="collapse" id="6" data-target=".6collapsed">
            <td>Peter Kasprzak</td>
            <td>Partial automation of sampling and data collection to yield better estimates for faba and canola seed emergence project</td>
            <td>10:10 - 10:30</td>
            <td></td>
          </tr>
          <tr class="out budgets 6collapsed collapse multi-collapse10" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          An often overlooked part of experimental research is the data collection process.  Errors in sampling propagate through the entire experiment, with protocols often comprising a significant portion of resources from limited budgets.  The challenge is to automate sections of this process, while keeping the necessary human checks, to decrease time, manpower, and overall costs of this process.  One important step is the selection of sampling protocol.  Often a simple random sample can be improved upon in terms of smaller standard estimator error, and a more representative sample gathered from a smaller number of total samples.  We attempt to show how simulation can be run on a representative data set to determine the optimal sampling protocol for the circumstance, and at the same time re-introduce a nearly forgotten sampling technique, Ranked Set Sampling.  Under utilized for 60 years since its inception at the CSIRO by G. A. McIntyre in 1952, advances in modern technology now make it feasible to add this protocol to the go-to toolbox of sampling, and realize potential gains in efficiency, with the ultimate goal of wrapping these benefits in a easy to use, field ready, minimal training required piece of software. <br><br>
          </td>
          </tr>
        </tbody>
      </table>
    </div>
    <h2>Invited Speakers: Methods</h2>
    <h4><i>Room: Exhibition Hall</i></h4>
    <a class="btn btn-template-main btn-sm expand-btn" type="button" data-toggle="collapse" data-target=".multi-collapse11" aria-expanded="false" aria-controls="1collapsed 2collapsed 3collapsed">Expand All</a>
    <div class="table-responsive">
      <table class="abstract-table">
        <thead>
          <tr>
            <th>Presenter</th>
            <th>Abstract Title</th>
            <th>Time</th>
            <th>Slides</th>
          </tr>
        </thead>
        <tbody>
          <tr class="clickable" data-toggle="collapse" id="41" data-target=".41collapsed">
            <td>Claudia Czado</td>
            <td>Vine copulas and health applications</td>
            <td>11:00 - 12:00</td>
            <td></td>
          </tr>
          <tr class="out budgets 41collapsed collapse multi-collapse11" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          Vine copulas (vine-copula.org) provide a wide class of multivariate dependence models. They allow for arbitrary marginal models and the dependence is characterized by a copula, which is build using only bivariate copulas. They are joined to form a valid multivariate copula using conditioning arguments, which is identified in a set of linked trees called the vine structure. Since all terms can be chosen independently they can accommodate different tail dependence both symmetric and asymmetric for groups of variables. I will introduce the construction, discuss the selection of vine structure and the step wise estimation procedure. This  allows to select and fit models in very high dimensions. After this I will show how these models can be applied in some health applications.<br><br>
          </td>
          </tr>
          <tr class="clickable" data-toggle="collapse" id="42" data-target=".42collapsed">
            <td>Marti J. Anderson</td>
            <td>Copula models for ecological community data</td>
            <td>12:00 - 13:00</td>
            <td></td>
          </tr>
          <tr class="out budgets 42collapsed collapse multi-collapse11" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          I shall describe a recently developed pathway for multivariate analysis of data consisting of counts of species abundances that includes two key components: copulas, to provide a flexible joint model of individual species, and dissimilarity-based methods, to integrate information across species and provide a holistic view of the community. Individual species are characterised using suitable (marginal) statistical distributions, with the mean, the degree of over-dispersion and/or zero-inflation being allowed to vary among a priori groups of sampling units. Associations among species are then modelled using copulas. A Gaussian copula smoothly captures changes in an index of association that excludes joint-absences in the space of the original species variables, but more flexible vine copulas might also be used. A permutation-based filter with exact family-wise error can optionally be applied a priori to reduce the dimensionality of the copula estimation problem. An MCEM algorithm provides efficient estimation of the copula correlation matrix with discrete marginals (counts). Given the resulting model, we may then simulate realistic ecological community data under fully specified null or alternative hypotheses. Distributions of community centroids derived from simulated data can be visualised in ordinations of ecologically meaningful dissimilarity spaces. Multinomial mixtures of data drawn from copula models also yield smooth power curves in dissimilarity-based settings. The proposed analysis pathway provides new opportunities to combine model-based approaches with dissimilarity-based methods, enhancing our understanding of ecological systems. I shall demonstrate implementation of the pathway with an example dataset of fish counts from a New Zealand marine reserve, the Poor Knights, and will also touch briefly on more recent extensions that embrace models of species along environmental gradients.<br><br>
          </td>
          </tr>
        </tbody>
      </table>
    </div>
    <!--                -->
    <!----First Stream --->
    <!--                -->
    <h2>Contributed Talks Session 2a: Biostatistics II</h2>
    <h4><i>Room: Vines</i></h4>
    <a class="btn btn-template-main btn-sm expand-btn" type="button" data-toggle="collapse" data-target=".multi-collapse12" aria-expanded="false" aria-controls="1collapsed 2collapsed 3collapsed">Expand All</a>
    <div class="table-responsive tg-wrap">
      <table class="abstract-table">
        <thead>
          <tr>
            <th>Presenter</th>
            <th>Abstract Title</th>
            <th>Time</th>
            <th>Slides</th>
          </tr>
        </thead>
        <tbody>
          <tr class="clickable" data-toggle="collapse" id="43" data-target=".43collapsed">
            <td>Alice Richardson</td>
            <td>Determination of Indirect Reference Intervals for Immunoglobulin in an Australian Population</td>
            <td>14:10 - 14:30</td>
            <td></td>
          </tr>
          <tr class="out budgets 43collapsed collapse multi-collapse12" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          Diagnostic pathology test results are typically supplied with reference intervals, a pair of values delineating the range within which a healthy individual’s test result should lie. These reference intervals are essential for interpretation of the tests, but calculation of these intervals is controversial from both a statistical and a biological point of view.<p>In this presentation we introduce the indirect method for reference interval calculation, based on secondary analysis of administrative data rather than direct identification of a healthy population leading to reference interval calculation. We’ll describe the statistical and biochemical issues that arise from the indirect approach.<p>We will also investigate the effect of two methods of outlier removal (Tukey elimination and the block method) and three methods of calculation (parametric, non-parametric and robust) on the indirect intervals obtained. The presentation will be illustrated with a large Australian data set relating to serum immunoglobulin A, G and M for males and females across the entire human age range.<p>The outlier elimination method was more important in the production of the indirect reference intervals than the calculation method. The Tukey elimination procedure consistently eliminated more values than the block method. If Tukey elimination was applied, variation between intervals produced by the different calculation methods was then minimal. The non-parametric intervals were actually more sensitive to outliers which, for certain assays, led to higher and wider intervals for older age groups. There were only minimal differences between robust and parametric reference intervals.<p>The interaction between outlier elimination and calculation method will be investigated further, and suggestions made for moving forward with indirect intervals in the diagnostic setting. <br><br>
          </td>
          </tr>
          <tr class="clickable" data-toggle="collapse" id="44" data-target=".44collapsed">
            <td>Tugba Akkaya-Hocagil</td>
            <td>The Propensity Score with Semi-continuous Exposures</td>
            <td>14:30 - 14:50</td>
            <td></td>
          </tr>
          <tr class="out budgets 44collapsed collapse multi-collapse12" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          Propensity score methodology has become increasingly popular in recent years as a tool for estimating causal effects of treatment or exposure using data from observational studies. For the most part, discussion has focussed on binary treatment/exposure scenarios. While some authors have discussed propensity score methodology for more general exposures, including continuous, this topic has been less well studied.   In this presentation we discuss the context of environmental epidemiology where interest typically focuses on exposure variables that include zero values representing non-exposed individuals as well as long tails representing highly exposed individuals.  We develop a propensity score methodology based on a two-part model and show how this can be used to more reliably estimate the causal effects of a semi-continuous exposure variable. We compare and evaluate the performance of our proposed method relative to the more standard generalized propensity score method and direct covariate adjustment through simulation studies. We find that when the outcome model satisfies linear regression model assumptions, all three methods yield unbiassed results. However, when the outcome model violates the assumptions of linear regression, our proposed method outperforms both direct covariate adjustment and the generalized propensity score method. We illustrate our method using data from the Detroit Longitudinal Cohort Study where exposure corresponds to prenatal alcohol exposure, with a long tail and many zero values. <br><br>
          </td>
          </tr>
          <tr class="clickable" data-toggle="collapse" id="45" data-target=".45collapsed">
            <td>Olivier Thas</td>
            <td>Compositional Rank Methods for Testing for Differential Abundance in Microbiome Studies</td>
            <td>14:50 - 15:10</td>
            <td></td>
          </tr>
          <tr class="out budgets 45collapsed collapse multi-collapse12" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          Microbiome count data can be considered as compositional mutivariate observations, which are characterised by a sum-constraint. Popular methods for testing for differential abundance rely on the (zero-inflated) negative binomial (NB) distribution. We have developped a new goodness-of-fit test for this distributional assumption, and we have applied the test to several public data sets. We conclude that more than 50% of the OTUs do not show a NB distribution and we demonstrate that this lack-of-fit causes poor FDR control. Robust or nonparametric methods for compositional data are needed. <p>Many data analysis methods have been developed for compositional data. They make use of log-ratios of counts, but these are problematic in the presence of many zero counts, as is the case for microbiome. We have developed semiparametric rank methods for compositional microbiome data. The methods do not rely on strong distributional assumptions, avoid log-ratios and account for library size variability. The methods make use of either means, rank or sign statistics. False discovery rate control happens through a new permutation method that accounts for the discreteness of the p-value null distributions. Results from a realistic simulation study suggest that the new methods perfom well and that particularly the sign-based methods perform well for overdispersed microbiome data. <br><br>
          </td>
          </tr>
          <tr class="clickable" data-toggle="collapse" id="46" data-target=".46collapsed">
            <td>Tong Wang</td>
            <td>Comparison of Methods for the Detection of Outlier and Associated Biomarker in Mislabeled Omics Data</td>
            <td>15:10 - 15:30</td>
            <td></td>
          </tr>
          <tr class="out budgets 46collapsed collapse multi-collapse12" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          Background: Previous studies have reported that labeling errors are not uncommon in omics data. Potential outliers may severely undermine the correct classification of patients and the identification of reliable biomarkers for a particular disease. Three methods have been proposed to address the problem: sparse label-noise-robust logistic regression (Rlogreg), robust elastic net based on the least trimmed square (enetLTS), and “Ensemble.” Ensemble is an ensembled classification based on distinct feature selection and modeling strategies. The accuracy of biomarker selection and outlier detection of these methods needs to be evaluated and compared so that the appropriate method can be chosen. Results: The accuracy of variable selection, outlier identification, and prediction, and the running time of the three methods were compared in scenarios with various sample sizes, dimensions, and proportions of outliers with or without leverage points. From the results of the simulation study, Ensemble was best in terms of the variable selection accuracy. enetLTS selected the most variables with the highest positive selection rate and highest false discovery rate. In terms of the mislabeled samples detected, enetLTS performed best, with high sensitivity and a controlled false positive rate within 5%. Rlogreg detected most outliers, with the highest FPR, which exceeded 5% in some cases. Rlogreg had the lowest runtime. The three methods were applied to a triple negative breast cancer (TNBC) dataset, which included individuals with discordant labels. Conclusions: Our study highlighted how to choose methods for feature selection and outlier detection in high-dimensional datasets with mislabeled samples. If a low FDR was required to reduce the failure of subsequent experimental validation, then Ensemble was the best choice. If screening associated genes broadly or the prediction of a response was required, then enetLTS was the best choice. In terms of the mislabeled samples detected, enetLTS performed best.<br><br>
          </td>
          </tr>
        </tbody>
      </table>
    </div>
    <!--                 -->
    <!----Second Stream --->
    <!--                 -->
    <h2>Contributed Talks Session 2b: Samples & Surveys</h2>
    <h4><i>Room: Exhibition Hall</i></h4>
    <a class="btn btn-template-main btn-sm expand-btn" type="button" data-toggle="collapse" data-target=".multi-collapse13" aria-expanded="false" aria-controls="1collapsed 2collapsed 3collapsed">Expand All</a>
    <div class="table-responsive tg-wrap">
      <table class="abstract-table">
        <thead>
          <tr>
            <th>Presenter</th>
            <th>Abstract Title</th>
            <th>Time</th>
            <th>Slides</th>
          </tr>
        </thead>
        <tbody>
          <tr class="clickable" data-toggle="collapse" id="47" data-target=".47collapsed">
            <td>Robert Clark</td>
            <td>Statistical Efficiency of Distance Sampling</td>
            <td>14:10 - 14:30</td>
            <td></td>
          </tr>
          <tr class="out budgets 47collapsed collapse multi-collapse13" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          Distance sampling is a technique for estimating the abundance of animals or other objects in a region. Animals can be observed in a wide strip around the observer, while hopefully avoiding undercount by adjusting for detection rates which can decline with distance, provided that a set of strong model assumptions are justified. The impact of uncertainty about the detection model on variances of abundance estimates will be discussed. An expression for the asymptotic penalty factor is stated; it would typically be at least 2 but could be much higher if detection rates drop steeply. Various approaches are compared in simulations which incorporate clumping of animal locations. The take home message is that the significant penalty due to unknown detection parameters should be factored into decisions about the methodology and scale of abundance studies. <br><br>
          </td>
          </tr>
          <tr class="clickable" data-toggle="collapse" id="48" data-target=".48collapsed">
            <td>Scott Foster</td>
            <td>Being Random and Efficient for Transect-Based Ecological Surveys</td>
            <td>14:30 - 14:50</td>
            <td></td>
          </tr>
          <tr class="out budgets 48collapsed collapse multi-collapse13" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          In ecology, many sampling techniques rely on taking measurements along a transect; an example is the collection of underwater imagery from towed platforms. Despite this, methods to generate randomised survey designs have not hitherto been developed. We present an approach to generate a randomisation of transects using three steps: 1) calculate transect inclusion probabilities from user-specified cell inclusion probabilities, which allows particular environments to be sampled more often; 2) alter the cell and transect inclusion probabilities so that when transects are sampled the frequencies of sampling cells approximate the cell inclusion probabilities, and; 3) draw a spatially-balanced probability sample of transects. The resulting designs are for images constrained to lie on transects. The transect-based designs approximately respect the specified cell-inclusion probabilities whilst maintaining spatial-balance and still being straightforward to specify. We illustrate with application of the method to a towed-camera survey of deep-sea (500-2,000m depths) seamounts off Tasmania, Australia.  This was a challenging area to survey due to its complex topology, and uneven inclusion probabilities for the property of interest - the presence of a stony coral that forms large areas of biogenic reef and supports elevated biodiversity. <br><br>
          </td>
          </tr>
          <tr class="clickable" data-toggle="collapse" id="49" data-target=".49collapsed">
            <td>Omer Ozturk</td>
            <td>Two-Stage Cluster Samples with Judgment Post-Stratification</td>
            <td>14:50 - 15:10</td>
            <td></td>
          </tr>
          <tr class="out budgets 49collapsed collapse multi-collapse13" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          Estimation of the population mean or total in a clustered population can be done using two-stage cluster samples.  Here we present a design in which  cluster sample in each stage is constructed either using a judgement post-stratified (JPS) or a simle random sampling design. <p>The JPS sampling design is implemented with or without replacement, but the SRS sample is always  constructed without replacement. The paper presents design-unbiased estimators for the population mean and total, and the variances of these estimators. The efficiency improvement of the sampling designs compared with the SRS sampling design is investigated. The proposed estimator has a smaller variance than a two-stage SRS sample, but the level of improvement in efficiency depends on the intra-cluster correlation coefficient and the choices of the sampling designs in stage I and II of samplings. The paper also presents an approximate confidence interval for the population mean and total. For a fixed cost, the optimal sample sizes for stage I and stage II samples are constructed by maximizing the information content of the sample. The proposed sampling designs and estimators are applied to a two-stage sampling in an agricultural application. <br><br>
          </td>
          </tr>
          <tr class="clickable" data-toggle="collapse" id="50" data-target=".50collapsed">
            <td>Dan Gladish</td>
            <td>Optimal design for monitoring groundwater quality using geostatistical modelling</td>
            <td>15:10 - 15:30</td>
            <td></td>
          </tr>
          <tr class="out budgets 50collapsed collapse multi-collapse13" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          Collecting groundwater data is a critical aspect for evaluating potential impact on the regional freshwater supply from resource development.  Assessing baseline water quality indicators in coal seam gas development areas is important to develop improved understanding of the groundwater system and inform managerial decisions and evaluate potential issues.  However, prediction of groundwater quality indicators is difficult, and often results in high uncertainty due to the sparse nature of available data.  Interest is therefore in determining future borehole locations for monitoring.  However, drilling boreholes for groundwater monitoring is expensive.  Therefore, determining optimal borehole locations that will reduce prediction uncertainty of groundwater quality indicators is useful.  In this study, we propose a method that utilizes kriging models to interpolate groundwater quality indicators in the aquifer.  We then combine the predicted values from these geostatistical models and use the Differential Evolution algorithm to determine optimal locations that would reduce spatial prediction uncertainty.  We apply our method to a portion of one of the Great Artisan Basin aquifers, specifically in the Namoi region in New South Wales, Australia.  Using this method, we outline 10 potential borehole locations for monitoring groundwater quality indicators that will minimize prediction uncertainty. <br><br>
          </td>
          </tr>
        </tbody>
      </table>
    </div>
    <!--                -->
    <!----First Stream --->
    <!--                -->
    <h2>Contributed Talks Session 3a: Visualisation</h2>
    <h4><i>Room: Vines</i></h4>
    <a class="btn btn-template-main btn-sm expand-btn" type="button" data-toggle="collapse" data-target=".multi-collapse14" aria-expanded="false" aria-controls="1collapsed 2collapsed 3collapsed">Expand All</a>
    <div class="table-responsive tg-wrap">
      <table class="abstract-table">
        <thead>
          <tr>
            <th>Presenter</th>
            <th>Abstract Title</th>
            <th>Time</th>
            <th>Slides</th>
          </tr>
        </thead>
        <tbody>
          <tr class="clickable" data-toggle="collapse" id="51" data-target=".51collapsed">
            <td>Thomas Lumley</td>
            <td>Multiclass Hexbin Plots</td>
            <td>16:00 - 16:20</td>
            <td></td>
          </tr>
          <tr class="out budgets 51collapsed collapse multi-collapse14" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          Hexagonal binning allows for the efficient display of very large data sets in graphs with many of the benefits of scatterplots. Hexbinning also supports weighted data. However, it does not allow the equivalent of plotting points in different colours to display a discrete third variable in a scatterplot.   I will present multiclass hexbins plots that partition each hex into six triangles for the display of multiple classes. Multiclass hexbins are a form of icon plot or glyph plot and show how coarsening/stylisation of information can still be beneficial.  I will also describe an R implementation in the 'hextri' package. <br><br>
          </td>
          </tr>
          <tr class="clickable" data-toggle="collapse" id="52" data-target=".52collapsed">
            <td>Connor James Smith&#42;</td>
            <td>Visualisation of model stability information for better prognosis based feature extraction</td>
            <td>16:20 - 16:40</td>
            <td></td>
          </tr>
          <tr class="out budgets 52collapsed collapse multi-collapse14" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          Identifying key features and their regulatory relationships which underlie biological processes is the fundamental objective of much biological research; this includes the study of human diseases, with direct and important implications in the development of target therapeutics. We report new statistical approaches to identify various types of interpretable feature representations that are prognostically informative in classifying complex diseases.  We present new ways to utilize information from thousands of resamples in modern selection methods and repeated subsampling to identify what features best predict disease progression.  <p>The new method VIVID utilizes feature importance measures via pairwise feature comparisons to identify significant features.  We show how the selected features are repeatedly ranked higher and are more stable than other features.  Taking advantage of cluster analysis, we construct a set of nested feature groups and then select an optimal group of features from the candidate models. Different methods of visualisation for this resampled information are presented.  The computational speed and requirements of VIVID are discussed and how the method is able to deal with data where the number of features is continually increasing.<br><br>
          </td>
          </tr>
          <tr class="clickable" data-toggle="collapse" id="53" data-target=".53collapsed">
            <td>Kevin Wang&#42;</td>
            <td>mcvis: A new framework for collinearity discovery, diagnostic and visualization</td>
            <td>16:40 - 17:00</td>
            <td></td>
          </tr>
          <tr class="out budgets 53collapsed collapse multi-collapse14" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          An essential step prior to any linear regression fitting is checking for collinearity. Without this step, hidden collinearity could compromise the statistical estimation, inference and interpretation of models. There exist several collinearity diagnostic statistics like the variance inflation factor and condition numbers in the literature. However, these collinearity measures have several limitations in practice. We present mcvis, a new framework that utilises conventional diagnostic statistics and sampling methods to better understand the cause of collinearity. We will present both simulated examples as well as real data examples to illustrate the novelty of mcvis. We will also introduce a bipartite graph visualisation that aids to reveal the variables causing collinearity beyond the usual diagnostics using correlation matrix. <br><br>
          </td>
          </tr>
          <tr class="clickable" data-toggle="collapse" id="54" data-target=".54collapsed">
            <td>Petra Kuhnert</td>
            <td>Vizumap: An R package for visualizing uncertainty in spatial data</td>
            <td>17:00 - 17:20</td>
            <td></td>
          </tr>
          <tr class="out budgets 54collapsed collapse multi-collapse14" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          The quantification, visualization and communication of uncertainty in spatial and spatio-temporal data is important for decision-making. It can highlight regions on a map that are poorly predicted and identify a need for further sampling. Uncertainty can also help to prioritise regions in terms of where to focus remediation efforts and allocate investment. It can also provide some assurance on where modelling efforts are working well and where it fails to trigger further investigation. Unfortunately, uncertainty is rarely included on maps that convey spatial or spatio-temporal estimates. <p>Approaches for visualizing uncertainty in spatial and spatio-temporal data will be presented. These include the bivariate choropleth map, map pixelation, glyph rotation and exceedance probability maps. Bivariate choropleth maps explore the “blending” of two colour schemes, one representing the estimate and a second representing the margin of error. The second approach uses map pixelation to convey uncertainty. The third approach uses a glyph to represent uncertainty and is what we refer to as glyph rotation. The final map based exploration of uncertainty is through exceedance probabilities. <p>Vizumap, is an R package that has been developed within Digiscape for visualising uncertainty in spatial and spatio-temporal data. To illustrate the methods, I use an example from the Great Barrier Reef, where sediment loads were quantified from a Bayesian Hierarchical Model (BHM) that assimilated estimates of sediment concentration and flow with modelled output from a catchment model spanning 21 years of daily outputs and 411 spatial locations.<br><br>
          </td>
          </tr>
        </tbody>
      </table>
    </div>
    <!--                 -->
    <!----Second Stream --->
    <!--                 -->
    <h2>Contributed Talks Session 3b: Genetics & Evolution</h2>
    <h4><i>Room: Exhibition Hall</i></h4>
    <a class="btn btn-template-main btn-sm expand-btn" type="button" data-toggle="collapse" data-target=".multi-collapse15" aria-expanded="false" aria-controls="1collapsed 2collapsed 3collapsed">Expand All</a>
    <div class="table-responsive tg-wrap">
      <table class="abstract-table">
        <thead>
          <tr>
            <th>Presenter</th>
            <th>Abstract Title</th>
            <th>Time</th>
            <th>Slides</th>
          </tr>
        </thead>
        <tbody>
          <tr class="clickable" data-toggle="collapse" id="55" data-target=".55collapsed">
            <td>Conrad Burden</td>
            <td>Estimation of mutation rate matrices from genomic site frequency data</td>
            <td>16:00 - 16:20</td>
            <td></td>
          </tr>
          <tr class="out budgets 55collapsed collapse multi-collapse15" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          We describe how the full 4x4 genomic mutation rate matrix can, in principle, be estimated from population site frequency data obtained by sampling independent neutrally evolving sites within a multiple alignment of genomes.  The method relies on calculated stationary sampling distributions of the diffusion limit of the mutation-drift Wright-Fisher model.  These distributions can be obtained for an arbitrary general, non-reversible rate matrix, to first order in the mutation rates, either from the forward Kolmogorov equation or from a coalescent argument.  The method will be applied to extracted sequence information from short autosomal introns of 196 Drosophila melanogaster individuals resulting in a site frequency spectrum of 218,942 nucleotides. <br><br>
          </td>
          </tr>
          <tr class="clickable" data-toggle="collapse" id="56" data-target=".56collapsed">
            <td>Beata Sznajder</td>
            <td>A multi-locus variable selection strategy for association mapping analysis</td>
            <td>16:20 - 16:40</td>
            <td></td>
          </tr>
          <tr class="out budgets 56collapsed collapse multi-collapse15" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          In high dimensional gene-trait association studies often the challenge is to detect true associations of the phenotype with a small subset of genetic markers from a high dimensional set of markers. Additional challenges stem from statistical non-independence of genetic markers (linkage disequilibrium), the presence of population structure and cryptic relatedness in the population of sampled individuals. <p>A common approach to genetic association and QTL mapping is to fit uni-variable linear mixed models testing each marker sequentially for associations with phenotype. Population structure is incorporated in the model and the false positive rate is usually controlled through adjustment of the usual 0.05 alpha level for multiple comparisons. <p>The major disadvantage of this approach is that it does not provide an adjustment for multiple markers or potential gene-gene interactions. Testing of these additional terms can become  problematic  due to the substantial increase in the number of associations requiring testing compared to the number of sampled observations (the so-called p >> n scenario). <p>We present an application of Bayesian variable selection for association mapping, implemented in the R package BayesVarSel. The approach of BayesVarSel employs model averaging to provide measures of association of phenotype with predictors (here genetic markers) across multi-variable models and includes functionality for scenarios where p >> n. Additionally this approach explicitly accounts for multiple markers acting simultaneously on the phenotype. We compare the results obtained from BayesVarSel with the traditional uni-variable mixed model methodology through an application of QTL mapping of resistance to net-form-net-blotch (NFNB) in double haploid populations of barley.<br><br>
          </td>
          </tr>
          <tr class="clickable" data-toggle="collapse" id="57" data-target=".57collapsed">
            <td>Anabel Forte</td>
            <td>Variable selection for genome wide association analysis in plant breeding</td>
            <td>16:40 - 17:00</td>
            <td></td>
          </tr>
          <tr class="out budgets 57collapsed collapse multi-collapse15" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          In modern plant breeding comparative experiments, there is often a necessity to accurately determine the underlying genetic bases of industry driven phenotypic traits. With the availability of low cost high-throughput genotyping technology, this involves the mapping of quantitative trait loci (QTL) through a high dimensional genome wide association analysis pipeline. Within this pipeline, there may be several methods to reduce the dimension of the genetic marker set for further scrutiny.<p>In this work we present an efficient multi-step genome wide association analysis pipeline which incorporates a Bayesian variable selection strategy to identify putative QTL. In the initial step of this pipeline, a genomic prediction is conducted to obtain a complete set of marker effects. These effects are then used with a modification of a popular genome wide binning strategy to dramatically reduce the dimensionality of the marker set. With this reduced set of markers, a Bayesian variable selection is conducted to determine a small subset of markers linked to putative QTL. The complete genome wide analysis pipeline is illustrated with phenotypic and genotypic data obtained from a large Australian wheat panel. <p>However, the genetic structure of lines may not be the only source of variability when trying to understand an output. In this sense, multienvironmental trials poses a mayor challenge adding an underlaying, complex, correlation structure. <p> In this work we discuss a two steps genome wide association analysis which makes use of a Bayesian variable selection strategy to determine markers significantly linked to a supposed QTL. The method is illustrated with a large Australian wheat panel.<br><br>
          </td>
          </tr>
          <tr class="clickable" data-toggle="collapse" id="58" data-target=".58collapsed">
            <td>Julian Taylor</td>
            <td>Genetic dissection of phytophthora root rot resistance in chickpea using modern statistical methods</td>
            <td>17:00 - 17:20</td>
            <td></td>
          </tr>
          <tr class="out budgets 58collapsed collapse multi-collapse15" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          Phytophthora root rot (PRR) is a major soil borne disease that has the potential to significantly limit the yield potential of chickpea across the northern growing region of Australia. Although sources of resistance for PRR have been identified, the molecular basis of this resistance still requires quantification.  This research discusses the statistical modelling approaches used to associate regions of the chickpea genome to PRR disease resistance traits obtained from multiple Recombinant Inbred (RIL) chickpea populations grown in varying field and glasshouse hydroponics experiments. Initially, the talk focusses on complex phenotypic and genetic analysis approaches used to detect quantitative trait loci (QTL) of plant survival traits across multiple field environments. The multi-environment analyses are then extended to include a plant survival trait derived from binary longitudinal measurements obtained from a high-throughput hydroponics screening system. The results from these analyses indicate PRR disease resistance in the RIL populations is strongly genetically related between field and controlled environment conditions. The results of this work have been recently published in two high impact international plant research journals. <br><br>
          </td>
          </tr>
        </tbody>
      </table>
    </div>
    <!-- Thurs -->
  </div>
  <div id="friday" class="tab-pane fade">
    <!-- Fri -->
    <h2>JABES/Biometrics Showcase</h2>
    <h4><i>Room: Exhibition Hall</i></h4>
    <a class="btn btn-template-main btn-sm expand-btn" type="button" data-toggle="collapse" data-target=".multi-collapse16" aria-expanded="false" aria-controls="1collapsed 2collapsed 3collapsed">Expand All</a>
    <div class="table-responsive  tg-wrap">
      <table class="abstract-table">
      <thead>
        <tr>
          <th>Presenter</th>
          <th>Abstract Title</th>
          <th>Time</th>
          <th>Slides</th>
        </tr>
      </thead>
        <tbody>
          <tr class="clickable" data-toggle="collapse" id="59" data-target=".59collapsed">
            <td>Dan Pagendam</td>
            <td>Improving Estimates of Fried’s Index from Mating Competitiveness Experiments</td>
            <td>9:00 - 9:30</td>
            <td></td>
          </tr>
          <tr class="out budgets 59collapsed collapse multi-collapse16" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          Sterile insect technique (SIT) and incompatible insect technique (IIT) are current methods for biological control of insect populations. Critical to the successful implementation of these biocontrol programs is quantifying the competitiveness of sterile/incompatible male insects for female mates relative to wildtype males. Traditionally, entomologists measure this mating competitiveness through a quantity known as Fried’s Index. We establish that Fried’s Index is mathematically equivalent to the mating competitiveness coefficient that features in many population models used in SIT/IIT programs. Using this insight, we propose a new approach for estimating Fried’s Index from mating competitiveness experiments. We show that this approach offers greater precision and accuracy than the traditional approach that is currently used in many studies. This is demonstrated using both simulation experiments and by analysing real experimental data. To facilitate uptake of the proposed method, we also provide an R package that can be used to easily analyse data from mating competitiveness experiments.<br><br>
          </td>
          </tr>
          <tr class="clickable" data-toggle="collapse" id="60" data-target=".60collapsed">
            <td>Louise McMillan</td>
            <td>Visualization and measures of population differentiation based on the saddlepoint approximation</td>
            <td>9:30 - 10:00</td>
            <td></td>
          </tr>
          <tr class="out budgets 60collapsed collapse multi-collapse16" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          We propose a method for visualizing genetic assignment data by characterizing the distribution of genetic profiles for each candidate source population (McMillan & Fewster, 2017). This method enhances the assignment method of Rannala & Mountain (1997) by calculating appropriate graph positions for individuals for which some genetic data are missing. The saddlepoint method also provides a way to visualize assignment results calculated using the leave-one-out procedure.<p>This approach offers an advance upon assignment software such as GeneClass2, and is biologically more interpretable than plots provided by the widely-used software STRUCTURE. The visualization method makes it straightforward to detect features of population structure and to judge the discriminative power of the genetic data for assigning individuals to source populations.<p>We also propose new methods for quantifying population genetic structure. The measures we propose are closely related to the visualization approach, and enable visual features obvious from the plots to be expressed more formally. One measure is interloper detection probability: for two random genotypes arising from populations A and B, the probability that the one from A has the better fit to A and thus the genotype from B would be correctly identified as the `interloper' in A. Another measure is correct assignment probability: the probability that a random genotype arising from A would be correctly assigned to A rather than B. <p>Using permutation tests, we can test two populations for significant population structure. These permutation tests are sensitive to subtle population structure, and are particularly useful for eliciting asymmetric features of the populations being studied, e.g. where one population has undergone extensive genetic drift but the other population has remained large enough to retain greater genetic diversity.<p>We illustrate these methods using microsatellite genotype data from ship rats and southern right whales, and SNP data from human populations. <br><br>
          </td>
          </tr>
          <tr class="clickable" data-toggle="collapse" id="61" data-target=".61collapsed">
            <td>David Warton</td>
            <td>Generalised latent variable models for multivariate abundances in ecology</td>
            <td>10:00 - 10:30</td>
            <td></td>
          </tr>
          <tr class="out budgets 61collapsed collapse multi-collapse16" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          Technological advances have enabled a new class of multivariate models for ecology, with the potential to specify a statistical model for abundances jointly across many taxa, to simultaneously explore interactions across taxa and also the response of abundance to environmental variables. This talk will focus on generalised latent variable models, essentially a factor analytic extension of generalised linear models.  These models can be used for a number of purposes of interest to ecologists, including: estimating patterns of residual correlation across taxa; ordination; multivariate inference about environmental associations; accounting for missing predictors; prediction of multi-taxon quantities like species richness. We discuss computation challenges fitting these models, current computational approaches and future directions.<br><br>
          </td>
          </tr>
        </tbody>
      </table>
    </div>
    <h2>Invited Speakers: Agriculture</h2>
    <h4><i>Room: Exhibition Hall</i></h4>
    <a class="btn btn-template-main btn-sm expand-btn" type="button" data-toggle="collapse" data-target=".multi-collapse17" aria-expanded="false" aria-controls="1collapsed 2collapsed 3collapsed">Expand All</a>
    <div class="table-responsive">
      <table class="abstract-table">
        <thead>
          <tr>
            <th>Presenter</th>
            <th>Abstract Title</th>
            <th>Time</th>
            <th>Slides</th>
          </tr>
        </thead>
        <tbody>
          <tr class="clickable" data-toggle="collapse" id="62" data-target=".62collapsed">
            <td>Daniela Bustos-Korts</td>
            <td>Opportunities from combining statistical and crop growth models to predict Genotype × Environment interactions over time</td>
            <td>11:00 - 12:00</td>
            <td></td>
          </tr>
          <tr class="out budgets 62collapsed collapse multi-collapse17" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          Genotype by environment interaction (G×E) for the target trait, e.g. yield, is an emerging property of agricultural systems and results from the interplay between a hierarchy of secondary traits involving the capture and allocation of environmental resources during the growing season. This hierarchy of secondary traits ranges from basic traits that correspond to response mechanisms/sensitivities, to intermediate traits that integrate a larger number of processes over time and therefore show a larger amount of G×E. Traits underlying yield differ in their contribution to adaptation across environmental conditions and have different levels of G×E. Here, we provide a framework to study the performance of genotype-to-phenotype (G2P) modelling approaches. We generated and analysed response surfaces, or adaptation landscapes, for yield and yield related traits, emphasizing trait dynamics and interactions over time. We used the crop growth model APSIM-wheat with genotype-dependent parameters as a tool to simulate non-linear trait responses over time with complex trait dependencies, and applied it to Australian environments. Such simulated data opens new opportunities to i) study the relationships between traits over time and across environments, ii) evaluate genotype-to-phenotype models for multiple traits and environments, iii) compare models with an increased integration of statistical and biological aspects, iv) develop network models that allow visualizing how causality is propagated in biological systems and v) design efficient high throughput phenotyping schedules and methods. We show applications to wheat under contrasting water deficit patterns.<br><br>
          </td>
          </tr>
          <tr class="clickable" data-toggle="collapse" id="63" data-target=".63collapsed">
            <td>Joanne De Faveri</td>
            <td>Statistical Methods for data from High Throughput Phenotyping in Agriculture</td>
            <td>12:00 - 13:00</td>
            <td></td>
          </tr>
          <tr class="out budgets 63collapsed collapse multi-collapse17" aria-expanded="false" style="height: 0px;">
          <td colspan="4">
          High throughput phenotyping (HTP) data is being collected in the field and laboratory by drones, helicopters, sensors and buggies, often in the form of images and spectra. In plant trials these phenotyping methods often result in large amounts of data being collected over the crop growing season. The spatial location of the plants may impact on the growth of the plants and influence the HTP traits being measured, while the temporal correlation between repeated measurements and trends over time will also impact the traits. <p>In plant breeding trials, modelling the genetic effects of HTP traits is of primary interest but there is also a need to account for non-genetic effects (design, spatial and temporal) to obtain accurate and unbiased estimates of the genetic effects. The size of the HTP data may cause issues with traditional spatial and temporal modelling approaches, hence alternatives are proposed based on multi-dimensional reduced rank tensor smoothing splines. <p>Not only can HTP data be measured over time and space but also over thousands of wavelengths for hyperspectral data and the data may also be measured at multiple sites. The interaction between environment, time, space and wavelength needs to be modelled at both genetic and non-genetic levels in suitable ways.<p>Often HTP traits are measured with the aim of informing other traits of primary interest, for example yield. In many cases HTP data is used together with genomic information for genomic prediction of these primary traits. Functional Data Analysis (FDA) models provide one approach for the analysis of this type of data. New functional regression models in ASReml are presented, allowing for spatio-temporal modelling and efficient modelling of Genotype by environment (GxE) effects.  <p>This talk aims to provide a snapshot of some exciting statistical developments in the analysis of HTP data and to discuss further research topics. <br><br>
          </td>
          </tr>
        </tbody>
      </table>
    </div>
    <!-- Fri -->
  </div>
</div>
&#42; Indicates student
