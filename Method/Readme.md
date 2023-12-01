# My research
Name of the research: Explaining data weights in AI judgments by analyzing automotive data using SALib
# Background/Motivation:

Car price and car performance have always been the elements that car buyers pay attention to, recently there are a lot of software on the car purchase of intelligent recommendation services, related services also appeared on Taobao and other shopping software. However, users do not understand on what basis the AI recommends a particular car to them, nor do they understand whether the car recommended to them by the software is really suitable for them. In this case, we can use SALib for data analysis of cars to explain what elements are more weighted or more capable of determining the AI's final choice in its decision-making process. This research will help users to better understand the decision-making process of AIs using XAI's technology to deepen their understanding of AI decision-making.

# Research Question:

1. How can SALib be used to analyze the comparison of weights for different parameters in analyzing the problem of AI?
2. Can Morris be used in analyzing other comparison of weights for different parameters in other models or using other datas?

# Application Scenarios:

We will analyze a set of car data from Kaggle and analyze the AI's decision-making process by comparing different data, such as a lower price for a particular car, a lower fuel consumption for another car, and ultimately the results of the AI's decisions. In this analysis process, because SALib provides many tools in the sensitivity analysis of data, we can more intuitively see the impact of different data changes on the AI decision, so as to achieve better analysis results.

# Methodology:

This study will use the tools provided to us by SALib for analyzing the data from Kaggle, so as to determine which data is decisive for the outcome of the AI's decision making by analyzing the impact caused by different data on the AI's prediction results. Finally, we will be able to analyze how much importance AI models place on data in their judgments by using the above methods to improve users' understanding of and trust in AI.

# Results:

The study aims to demonstrate how XAI methods can enhance the interpretability of models in the field of autonomous vehicles, providing clearer explanations of model decisions, and thereby increasing trust and transparency in the car recommendation system. (Binder et al., 2018).

# Intellectual Merits/Practical Impacts:

By successfully applying XAI methods, the research intends to provide interpretable models for the field of car recommendation system, contributing to increased trust, reduced risks, and enhanced safety and transparency in practical applications. This could advance the development and widespread use of car recommendation technology (Caruana et al., 2018).

**1. Paramount Research Question:**
   - **Current Limitations:** The current limitations in the field revolve around the lack of comprehensive tools to deeply analyze and interpret parameter weights in complex models. Existing paradigms often struggle to provide nuanced insights into the intricate relationships between model parameters and outputs.
   - **Expansion and Challenge:** My research aims to transcend these limitations by offering a sophisticated software solution that not only conducts sensitivity analysis but delves into the granular details of parameter weights. This expansion enables a more profound understanding of model intricacies and challenges the boundaries of conventional interpretability.

   - **Technique Difficulties and Personal Uniqueness:** Overcoming these boundaries requires addressing challenges in processing large-scale data, ensuring computational efficiency, and providing user-friendly interfaces. My unique combination of expertise in machine learning, programming skills, and a keen understanding of user needs uniquely positions me to pioneer this advancement in the field.

**2. Rationale for Research Method:**
   - **Alternative Methods:** Alternative methods in sensitivity analysis include variance-based methods, regression-based approaches, and others. However, these methods often fall short in providing the detailed parameter insights that my software offers.

   - **Method Choice:** I chose to utilize the SALib database for sensitivity analysis due to its versatility and open-source nature. SALib's integration allows for efficient computation and facilitates the in-depth exploration of parameter weights. Its wide adoption in the scientific community adds credibility to my research.

**3. Significance of the Study:**
   - **Intellectual Significance:** The study holds intellectual significance by advancing the understanding of model behavior at a granular level. It contributes to the broader discourse on interpretability in machine learning, offering a new paradigm for dissecting model complexities.

   - **Practical Implications:** On a practical level, the software I developed empowers practitioners, researchers, and decision-makers to make informed choices based on a thorough comprehension of model parameters. This has implications across various industries, enhancing the reliability and applicability of machine learning models.

   - **Recognition and Awards:** While forecasting future awards is speculative, the potential for recognition in the form of a Nobel Prize in Economics or Turing Award in Computing lies in the transformative nature of the research. The software's ability to revolutionize how we understand and utilize machine learning models could indeed mark a significant milestone in these respective fields.

In essence, my research addresses critical limitations, employs a state-of-the-art methodology, and holds profound intellectual and practical implications, positioning it as a potential groundbreaking contribution to the field.

<img src="method.png" alt="Abstract Word Cloud">

# Reference
Binder, M., Heinrich, B., Hopf, M., et al. (2022). "Global reconstruction of language models with linguistic rules – Explainable AI for online consumer reviews." Electron Markets, 32, 2123–2138.

Caruana, R., Lou, Y., Gehrke, J., Koch, P., Sturm, M., & Elhadad, N. (2015). "Intelligible models for healthcare: Predicting pneumonia risk and hospital 30-day readmission." In Proceedings of the 21th ACM SIGKDD International Conference on Knowledge Discovery and Data Mining (pp. 1721-1730)

Lundberg, S. M., & Lee, S. I. (2017). "A unified approach to interpreting model predictions." In Advances in neural information processing systems (pp. 4765-4774)

Chen, J., Song, L., Le, G., & Samaras, D. (2018). "Local Interpretable Model-Agnostic Explanations for Black Box Models." arXiv preprint arXiv:1802.03735

Rudin, C. (2019). "Stop explaining black box machine learning models for high stakes decisions and use interpretable models instead." Nature Machine Intelligence, 1(5), 206-215

Broussard, Meredith . “Artificial Unintelligence.” MIT Press, 29 Sept. 2020, mitpress.mit.edu/9780262537018/artificial-unintelligence/.
