[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/27410/https://github.com/27410/27410-2020-group-project-group4_xylitolproduction.git/main)

# 27410 - Group assignment - Group 4 - *Saccharomyces cerevisiae* optimization for xylitol production.

> For this to work you will also have to keep `requirements.txt` up to date (by running `pip freeze > requirements.txt`).

> Furthermore, this will only work if you decide to make your repository public (which you can do under Settings -> Options),

## Project summary (<300 words)
Xylitol is a commercially viable pentitol that has important applications in the food, odonatological and pharmaceutical industries. The market of this product reaches the 823.6 million USD and is expected to achieve the 1.15 billion USD in the upcoming 3 years. The production of xylitol has been fulfilled by chemical synthesis until now. The fermentation process for production has gained attention. Biotechnological xylitol production is based on xylose metabolism in naturally pentose-fermenting microorganisms, mainly by yeasts that have wild type production, however, not all yeast has the pathways to achieve the production of Xylitol. First, Xylose is reduced into xylitol by a NAD(P)H depending XR (Xylose Reductase) followed by xylitol oxidation to xylulose by XDH (Xylitol Dehydrogenase).

Biotechnological production of xylitol is not yet cost-competitive, and several challenges have to be overcome to reduce the high capital and operational expenses in all the main steps of the production process (pretreatment, detoxification, fermentation and xylitol recovery). Therefore, developing a more robust organism capable to produce higher yields of xylitol would not only have a positive impact in the fermentation step and xylitol recovery, but would also have a positive impact in the detoxification step, as it would be less relevant for the performance of the process.

In this project Saccharomyces cerevisiae has been selected among other cell factories with this pathways present. S. cerevisiae is a robust organism and with many models available, however the production of Xylitol is limited. As mentioned, Xylitol is a product with a high impact in the food industry for this reason the use of a GRAS organism is a huge advantage. The aim is to modify cerevisiae to achieve high titers, by knocking out genes and overexpression of others. The Yeast8 model is the one that is going to be used. 

## Project overview

The Project will be developed as following:

1.	Study the model, get to know the metabolites, reactions, medium of growth of Saccharomyces and growth rate, under normal conditions. 
2.	Check for the Xylitol pathway and flux of every reaction 
3.	Xylitol Yield and Productivity and Xylose uptake
4.	Perform the following modifications separately.
a.	Knock out of XDH
b.	Overexpression of XR
c.	Overexpression of Xylose transporters
d.	Overexpression of reactions that produce of Co Factors (NADH, NADPH) (Glucose-6-phosphate dehydrogenase (G6PD), 6-phosphogluconate dehydrogenase (6-PGD))
•	All this modifications study them under different mediums: 100 % Xylose as carbon source, 50% glucose 50% Xylose, 25% glucose 75% Xylose and 75% glucose 25% Xylose.
5.	Combine the modifications to achieve the better yield and productivity. 

