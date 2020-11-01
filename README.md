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

* Capomulin	40.675741
* Ceftamin	52.591172
* Infubinol	52.884795
* Propriva	52.320930
* Ramicane	40.216745

2. According to Bar and Pie Charts, each regimen has around **23 to 25** different mice tested. And ``49.04%`` of mice are female.

3. From Quartiles, Outliers and Boxplots report, four regimens with best performance were analyzed: ``Capomulin``, ``Ramicane``, ``Infubinol``, and ``Ceftamin``. With the statistical calculations, only one outlier in Infubinol regimen was found:
* Mouse ID: ``c326``
* Tumor Volume (mm3): ``36.32``

4. The box plotting also confirms the previous conclusion. The final tumor volumes vary from 20 to 70 mm3.

5. From Line and Scatter Plots, The mouse was used to plot is s185. From the chart, **the tumor volume decreases linearly as the time goes**, changing from 45 mm3 to around 23 mm3.

6. A linear regression model was applied on the scatter chart. The correlation coefficient is 0.84194, which means it behaves a **strong correlation** between the *mouse weight and average tumor volume* (0.7~0.9).
