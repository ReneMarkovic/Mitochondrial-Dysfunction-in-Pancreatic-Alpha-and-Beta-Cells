# Mitochondrial-Dysfunction-in-Pancreatic-Alpha-and-Beta-Cells
Code for:"Mitochondrial Dysfunction in Pancreatic Alpha and Beta Cells Associated with Type 2 Diabetes Mellitus"

We designed computational models incorporating intracellular mechanisms from metabolic processes to hormone secretion in the pancreatic alpha and beta cells. Specifically, models for both cell types include a detailed description of metabolite and oxygen uptake, mitochondrial bioenergetic pathways, and ATP production, as well as the ATP/ADP ratio-mediated KATP-channel activity, which in turn orchestrates the hormone secretion. Particularities of individual segments and parameters of both models were adjusted and specified to match experimental data. A more detailed description of both models is given in Section 2.1 of the article. Furthermore, we incorporate in both cellular models a T2DM-associated mitochondrial dysfunction, which leads to a reduced net flux of ATP from mitochondria and impaired hormone secretion patterns.

We designed within the framework of Berkeley madonna [1]. Berkeley Madonna is a differential equation solver. Its graphical interface provides an intuitive platform for constructing complex mathematical models with ease using symbols rather than writing equations. The software provides a suite of graphical tools for plotting results. More precisely, we designed our code in such a way, that the main parameters are given as sliders, which enables the user to easily investigate the behavior of the model. In addition, the main results are graphically represented automatically when the code is executed. 

References:
1. https://berkeley-madonna.myshopify.com/ 
