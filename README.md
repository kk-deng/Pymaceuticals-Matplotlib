# Pymaceuticals - A Matplotlib Study on SCC Tumor
Data analysis and visualization of a pharmaceutical study of potential treatments for squamous cell carcinoma (SCC).

## Background

This dataset includes data about a new study on anti-cancer drugs with the results of tumor volumes:

* Capomulin
* Ceftamin
* Infubinol
* Ketapril
* Ketapril
* Propriva
* Ramicane
* Stelasyn
* Zoniferol

And one Placebo as reference group.

## Observations and Insights
1. From the table below, these regimens perform better than the reference group:

* Capomulin
* Ceftamin
* Infubinol
* Propriva
* Ramicane


	Mean	Median	Variance	Standard Deviation	SEM
Drug Regimen					
**Capomulin**	40.675741	41.557809	24.947764	4.994774	0.329346
**Ceftamin**	52.591172	51.776157	39.290177	6.268188	0.469821
**Infubinol**	52.884795	51.820584	43.128684	6.567243	0.492236
Ketapril	55.235638	53.698743	68.553577	8.279709	0.603860
Naftisol	54.331565	52.509285	66.173479	8.134708	0.596466
*Placebo*	54.033581	52.288934	61.168083	7.821003	0.581331
**Propriva**	52.320930	50.446266	43.852013	6.622085	0.544332
**Ramicane**	40.216745	40.673236	23.486704	4.846308	0.320955
Stelasyn	54.233149	52.431737	59.450562	7.710419	0.573111
Zoniferol	53.236507	51.818479	48.533355	6.966589	0.516398

2. According to Bar and Pie Charts, each regimen has around **23 to 25** different mice tested. And ``49.04%`` of mice are female.

3. From Quartiles, Outliers and Boxplots report, four regimens with best performance were analyzed: ``Capomulin``, ``Ramicane``, ``Infubinol``, and ``Ceftamin``. With the statistical calculations, only one outlier in Infubinol regimen was found:
* Mouse ID: ``c326``
* Tumor Volume (mm3): ``36.32``

4. The box plotting also confirms the previous conclusion. The final tumor volumes vary from 20 to 70 mm3.

5. From Line and Scatter Plots, The mouse was used to plot is s185. From the chart, **the tumor volume decreases linearly as the time goes**, changing from 45 mm3 to around 23 mm3.

6. A linear regression model was applied on the scatter chart. The correlation coefficient is 0.84194, which means it behaves a **strong correlation** between the *mouse weight and average tumor volume* (0.7~0.9).