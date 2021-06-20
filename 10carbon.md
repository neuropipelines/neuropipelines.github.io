---
title: Carbon Footprinting
layout: template
filename: 10carbon
--- 

## Carbon Footprint Quantification

The increasing supply of large datasets and machine-learning models has pushed the computational demand beyond Moore’s law [1,2]. The success of deep-learning models in the areas of image segmentation, classification and natural-language-processing (NLP) has enabled the development of novel applications in the field of neuroimaging towards image processing, clinical diagnosis and prognosis. So far, the research effort in this area has mainly focussed on achieving state-of-the-art task-accuracy via Monte-Carlo sampling of bigger and more complex model architectures. With the popularization of deep-learning approaches, it is important to take account of the compute costs and the consequent environmental impact of such model selection strategy [3,4]. The carbon footprint of training an AI model is estimated to be 284 Kgs of CO2 (5x lifetime emissions of a car or 300x RT-flights for single passenger between NYC and SF [2,4]. Moreover, the energy consumption of the deep-learning based and the existing neuroimaging pipelines during deployment needs to be estimated in order to minimize the carbon emissions resulting from processing of big datasets, such as UKBiobank. 

This working group aims to: 
* Compare various carbon footprinting tools available for use in neuroimaging pipelines
* Benchmark the carbon emissions of existing and novel neuroimaging pipelines 
* Propose strategies to promote environmentally sustainable research practices in computational neuroscience 


***
1. Amodei D, Hernandez D, Sastry G, Clark J, Brockman G, Sutskever I. [AI and Compute](https://openai.com/blog/ai-and-compute/). Published May 16, 2018.
2. Hao, Karen. [Training a single AI model can emit as much carbon as five cars in their lifetimes](https://www.technologyreview.com/2019/06/06/239031/training-a-single-ai-model-can-emit-as-much-carbon-as-five-cars-in-their-lifetimes/). MIT Technology Review (2019).
3. Schwartz R, Dodge J, Smith NA, Etzioni O. Green AI. arXiv [csCY]. Published online July 22, 2019. 
4. Emma Strubell, Ananya Ganesh, and Andrew McCallum. Energy and policy considerations for deep learning in NLP. In Proceedings of the 57th Annual Meeting of the Association for Computational Linguistics, pages 3645–3650, 2019.

## Resources

Quantifying carbon footprint of neuroimaging pipelines is one of the key objectives of our workgroup. Some of these tools could be useful in developing a complete solution. 
* [Experiment-impact-tracker](https://github.com/Breakend/experiment-impact-tracker)
* [Carbontracker](https://github.com/lfwa/carbontracker/)
* [CodeCarbon](https://github.com/mlco2/codecarbon)



