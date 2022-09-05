# A Model Evaluating the Cost-Effectiveness of Two Treatment Strategies for the Use of Glycoprotein IIB/IIIA Antagonists in the Treatment of Non-ST Elevation Acute Coronary Syndrome
A probabilistic cost-utility analysis of Glycoprotein IIB/IIIA antagonists in reducing the risk of myocardial infarction after a non-ST elevation acute coronary syndrome modified from a paper by Palmer et al. (2002): ‘A cost-effectiveness model comparing alternative management strategies for the use of glycoprotein IIb/IIIa antagonists in non-ST-elevation acute coronary syndrome’. Excel model attached.

## BACKGROUND
The objective of this evaluation was to determine the cost-effectiveness of Glycoprotein (GP) IIB/IIIA inhibitors administered under two treatment strategies – Treatment A and Treatment B – as adjunct to Percutaneous Coronary Intervention (PCI) or Coronary Artery Bypass Graft (CABG) following a non-ST elevation myocardial infarction (NSTEMI) or Acute Coronary Syndrome (ACS) in reducing the risk of non-fatal MI and death one year after treatment. NSTEMI or ACS comprises a group of signs and symptoms brought about by acute myocardial ischemia or heart attack (Ward et al. 2007).

Treatments A and B were compared to a baseline strategy in which patients underwent PCI, CABG or no revascularization procedure without receiving GP IIB/IIIA inhibitors. GP IIB/IIIA inhibitors are a class of drugs that prevent platelet aggregation (Palmer et al., 2002). The cost-effectiveness analysis took on the perspective of the UK NHS and is targeted to decision makers of the National Institute of Health and Clinical Excellence (NICE). An intervention is said to be cost-effective if the cost per Quality-Adjusted Life Year (QALY) gained is less than the threshold of £20,000 per QALY.

## METHODS
### Decision Analytic Modelling
A decision-analysis tree model was constructed to illustrate the pathways of three alternative treatment strategies: (1) baseline strategy or no adjunct treatment with GPIIB/IIIA inhibitors; (2) Treatment A; and (3) Treatment B, including the probability of experiencing any of the three treatment outcomes at the end of one year following treatment: non-fatal MI, ischemic heart disease (IHD) or death. To demonstrate the treatment effect of Treatments A and B, their relative risks were applied to the baseline probability of experiencing the said treatment outcomes. The model includes the costs of treatment and QALYs gained.

Below illustrates the decision-analysis tree model at baseline, without adjunct treatment with GP IIB/IIIA inhibitors. In the acute phase following a NSTEMI, patients may undergo PCI, CABG or no revascularization procedure. Those who underwent PCI may or may not need a repeat revascularization, which can be another PCI or CABG. Those who did not undergo a revascularization procedure in the acute phase may have one, either a PCI or CABG, later at 6 months. After the necessary procedures have been performed, patients may die or survive. If they survive, they may have another non-fatal MI or remain in the IHD state. A proportion of patients did not undergo revascularization procedure in the acute phase with either PCI or CABG.
![Decision Tree](https://github.com/1Genevieve/CEA_Model_160135576/blob/main/Decision%20Tree.jpg)

Source: Palmer et al. (2002)
### Markov Modelling
Those who survived at the end of the first year of treatment enter a long-term period of risk. Patients no longer took GP IIA/IIIB inhibitors nor underwent further revascularization procedures during this period. A Markov model was constructed to illustrate the long-term prognosis of these patients. The time horizon of the Markov model is 50 years. During this time, patients transition from one cycle of being in a certain health state to the next with each cycle covering a period of one year.  A half-cycle correction was applied to the state transitions, and a discount rate of 3.5% percent was applied to both costs and QALYs.
![long-term Markov model](https://github.com/1Genevieve/CEA_Model_160135576/blob/main/LT%20Markov.jpg)
### Cost-Effectiveness Analysis
The deterministic and probabilistic values of the total costs, total QALYs gained for each of the three treatment strategies, as well as net monetary benefit (NMB)  at the end of the 50-year horizon was computed. A full incremental analysis was performed to determine which of the three treatment strategies is cost-effective.

Probabilistic values were obtained through probabilistic sensitivity analysis (PSA). Appropriate distributions were applied to baseline parameters to obtain 2,000 sampled values of costs and QALYs. These distributions represent the uncertainty in parameter value estimates.
### Expected Value of Perfect Information
The individual and population Expected Value of Perfect Information (EVPI) was calculated assuming an incidence rate for treatment of 3,000 per annum at a time horizon of 5 years. A discount rate of 3.5% was applied to the EVPI. 

## RESULTS
### Decision-analytic modelling
Table 1 shows the probabilities of receiving either PCI or CABG in the acute phase or later at six months, and the probabilities of ending in any of the treatment outcomes. Table 2 shows the cost of revascularization procedure, PCI, CABG and other resources; probabilities of resource use; length of hospital stay; and cost of care associated with being in any of the health states. Although there is a cost associated with dying, the cost was not considered to be a health care cost and was thus, excluded from the analysis. These costs were based from cost estimates in NHS hospitals in England and PRAIS-UK. Length of hospital stay data were taken from Nottingham Heart Attack Register. All costs were expressed in 2015/16 nominal values. A year of life was assumed to have a utility value of 0.8. 

The relative risks of non-fatal MI and death with Treatments A and B compared to no treatment are shown in Table 3. Data on the effectiveness and cost-effectiveness of GPA IIB/IIIA inhibitors were derived from a rapid review of randomized controlled trials and published economic studies that were undertaken mostly outside the UK (Palmer et al. 2002). The treatment effects are assumed to cover a period of one year. While the baseline risks of ending in the aforementioned health states are specific to the UK population, the relative risks apply universally. These baseline risks were derived from the Prospective Registry of Acute Ischemic Syndromes in the UK (PRAIS-UK) and data on patients who had unstable angina and underwent acute PCI at a large UK cardiac centre in Leeds. Although patients receiving GP IIB/IIIA inhibitors are at risk of gastrointestinal bleeding complication, this was not included in the analysis.

### Markov modelling
Figure 2 shows the constructed Markov model. Once patients enter the long-term period of risk, they may remain in the IHD state, experience another non-fatal MI, transition to a post-MI state or die. The health state transition probabilities are shown in Table 4. These transition probabilities are not time-dependent; they remain the same throughout the long-term period regardless of previous health states experienced. The associated costs of being in any of the said health states and were assumed to be the same as in the initial short-term, one-year period and held constant in the 50-year time horizon. The utility attached to each of the health states was also assumed to the same. No cost was attributed to death. Although patients can be at risk for other co-morbidities which may affect the health state transitions, this risk was not incorporated in the analysis.


### Cost-effectiveness analysis
The total costs, total QALYs and results of the incremental cost-effectiveness analysis are shown in Tables 5 to 7. These are deterministic values. Based on the incremental analysis in Table 6, Treatment A is more cost-effective than Treatment B. The ICER of Treatment A and the baseline strategy is £6,610 per QALY gained which is below the £20,000 per QALY threshold. The ICER of Treatment B and Treatment A, however, is £47,610/QALY.  The net monetary benefit (NMB) still shows that Treatment A is more cost-effective because it has a higher NMB of £583.

### Probabilistic Sensitivity analysis
Results of the incremental analysis from the PSA showed that Treatment A would still be more cost-effective than the baseline strategy at an ICER of £6,618/QALY. The ICER of Treatment B and Treatment A is £40,021/QALY.

Below shows the cost-effectiveness acceptability curve (CEAC) of Treatment A versus Treatment B. At a WTP threshold of £0-£6,000 per QALY, Treatment A has a 100% probability of being more cost-effective than Treatment B. The probability that Treatment A is more cost-effective decreases as the WTP threshold increases, while the probability for Treatment B increases. However, the probability of cost-effectiveness of Treatment A remained higher across the whole range of WTP thresholds.
![CEAC](https://github.com/1Genevieve/CEA_Model_160135576/blob/main/CEAC.png)

Below shows the cost-effectiveness plane or scatter plot of random samples of incremental costs and incremental QALYs of Treatments A and B generated from the PSA. The mean ICER is plotted in red. Most of the scatter plots lie in the northeast quadrant; the costs and QALYs of Treatments A and B is higher than those of the baseline strategy. For Treatment A, all random ICER values are less than the WTP threshold of £20,000 per QALY. For Treatment B, some ICER values are above the WTP threshold.
![CE Plane](https://github.com/1Genevieve/CEA_Model_160135576/blob/main/CE%20Plane.png)

3.5.	Expected Value of Perfect Information (EVPI)
The EVPI is determined based on NMB of treatment. Compared to Treatment B, Treatment A is more cost-effective in 74% of 500 sampled values of costs and QALYs from the PSA with a mean incremental NMB of £684 compared to the mean incremental NMB of Treatment B of £682 using a WTP threshold of £20,000 per QALY. This results to an individual EVPI of £305, which reflects uncertainties in the estimates of cost-effectiveness (based on 500 random sampled values). The population EVPI was computed at £4,277,192.

## DISCUSSION/CONCLUSION
The aim of this study was to determine the cost-effectiveness of Treatment A and Treatment B as adjunct to the baseline strategy where patients may or may not undergo a revascularization procedure with PCI or CABG following a NSTEM or ACS. Clearly, the use of GP IIB/IIIA inhibitors reduces the relative risk of non-fatal MI and death at an additional cost. Hence, this study evaluated whether the additional cost of adjunct treatment is worth the additional benefits or QALYs gained. The treatment pathways were constructed using (1) decision-analytic modelling for the short-term period of one year during which the treatment effects of Treatment A and Treatment B were applied; and (2) Markov modelling to estimate the long-term probabilities of experiencing another non-fatal MI, post-MI, IHD and death. A cost-effectiveness analysis including a full incremental analysis was, then, performed. Both deterministic and probabilistic results of the full incremental analysis showed that Treatment A is more cost-effective than Treatment B based on a WTP threshold of £20,000 per QALY. Treatment A also has a higher NMB. Hence, the recommendation is strongly in favor of the adoption of Treatment A.

Both the short-term decision analysis tree model and long-term Markov model faced a number of structural limitations. The competing risk of treatment complications and other co-morbidities; increasing risk of death as persons age; and probability of using GP II/IIIA inhibitors or undergoing a revascularization procedure anytime during the long-term period were not incorporated in the analysis. The transition probabilities were assumed to remain constant throughout the long-term period.

This study only analyzed two additional treatment strategies. It may be possible that there could be more cost-effective treatments to prevent recurrence of non-fatal MI or reduce the risk of death such as lifestyle-related population-based programmes.

The uncertainty surrounding the higher mean NMB of Treatment A compared to baseline strategy and Treatment B can be resolved by further research or collection of additional data. The population EVPI is the maximum amount that is worth spending to eliminate this uncertainty.



## REFERENCES
Briggs A, Claxton K, Sculpher M. Decision Modelling for Health Economic Evaluation. Oxford University Press, Oxford, 2006.

Palmer S, Sculpher M, Philips Z, Robinson M, Ginnelly L, Bakhai A et al. A cost-effectiveness model comparing alternative management strategies for the use of glycoprotein IIb/IIIa antagonists in non-ST-elevation acute coronary syndrome. NICE Appraisal Report 2002.

Ward S, Jones M, Holmes M, Ara R, Ryan A, Yeo W and Payne N. A systematic review and economic evaluation of statins for the prevention of coronary events. Health Technology Assessment, 2007; 11(14).

Sculpher M, Smith D, Clayton T, Henderson R, Buxton M, Pocock S, Chamberlain D. Coronary angioplasty versus medical therapy for angina. Health service costs based on the second Randomized Intervention Treatment of Angina (RITA-2) trial. Eur Heart J. 2002 Aug;23(16):1291-1300.
