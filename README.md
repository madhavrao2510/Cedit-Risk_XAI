# Cedit-Risk_XAI

Title : Credit Risk modelling with XAI (Explainable AI) explainations
	
Problem statement : 
	The large retail/corporate banking systems now rely on AI/ML based automated sollutiond for creit risk modelling. The Credit risk modeling can be performed using various techniques of Classicfication in ML. Neural networks, random forests and gradient boosting machines are all “universal approximators”, meaning they can accurately model continuous functions. Regulatory obligations in Credit risk modeling, particularly in the EU (GDPR) & United States (FCRA), require that models be explainable and actionable.
		
		The Fair Credit Reporting Act (FCRA) governs the collection, assembly and use of consumer report information in the United States. Originally passed in 1970, the U.S. Federal Trade Commission (FTC) and the Consumer Financial Protection Bureau (CFPB) enforce it. Of particular interest in the review is the assignment of “key factors.” They are required, in many circumstances, to be provided by a consumer reporting agency to the user of a provided score or to a consumer who requests a score. 

		Under the FCRA Section 609(f)(2)(B), key factors mean “all relevant elements or reasons adversely affecting the credit score for the particular individual, listed in the order of their importance based on their effect on the credit score.” This information should be of value to a consumer, providing guidance on what areas he/she could work to improve to achieve a higher score, and with that, a better chance of approval or better credit pricing.

		Under the Equal Credit Opportunity Act (ECOA, 1974) of the Consumer Credit Protection Act (1968), the Federal Reserve Board was responsible for drafting and interpreting the implementing regulation. Today, the Consumer Financial Protection Bureau (CFPB) pursuant to the ECOA issues “Regulation B.”  Regulation B prohibits creditors from discriminating the creditworthiness of applicants with regard to their race, color, religion, national origin, sex, marital status or age. Regulation B applies to lending activities that take place within the U.S., whether or not the applicant is a citizen.
		
	A similar regulation exists in section 22 of Europian union GDPR regulations and not all machine learning (ML) techniques fulfill this requirement.
	
	Using an incorrectly designed ML-based credit score, there will be consumers who decrease their total balance on revolving cards but observe ML-based credit score decrease.  This results to a harmful action to the consumer who acted logically and thus may result in violation of the above mentioned regulations.
	
	
Objective of the project :
	We use of Interpretability as a means of explaination for different models used in Credit risk modelling. Apply latest available tools for Interpretability and evaluate Interpretability of different models.
	Points Below Max & Individual Conditional Explanations (ICE), Partial Dependence Plots (PDP), Local Interpretable Model-Agnostic Explanations (LIME) and Shapley values (SHAP) are popular types of explanation techniques applied to ML models. Key factors can be derived as a reult of finding explainations, these key factors can be shared to customers s a measure of transperency from the issuing banks so that the customers can focus on improving on those factors for better rating.


Benefits :
	More transperency into Automted descision making to the business descision makers, customers and agents. Better regulatory compliance.
	Helps in Regulatory complaince and thus avoiding enforcement actions (EA) and thus savings from potential regulatory fines.
	
Scope of work : 
	Explainable AI is an AI system that programmed to give the right explanation on how and why a result achieved. An ML model is developed to make a prediction, and an explanation technique is then selected to generate explanations. Explanation techniques can be applied to any ML model. Use XAI for the explainations on various credit risk models such as Linear models, random forest models, Elastic Net and finally XAI on Deep Learning model. The scope extends to measure explainations and extract "key factors" from the selected credit risk model.
	

Resources needed for the project :
	Hardware : Standard hardware for data processing with GPU for basic Deep learning tasks (Core i7 processor with Nvidia Graphics processors).
	Software : Jupyter, keras, tensor flow, matplotlib, WHAT-IF, LIME, DeepLIFT, Python
	
Potential challenges & risks :
	We may understand the ways an algorithm is working using XAI but, we need clarification on how the system is consistent with a legal or moral code. Below are the concerns for an XAI -
		Bias: How can I ensure that my AI system hasn’t learned a biased view of the world (or perhaps an unbiased view of a biased world) based on shortcomings of the training data, model, or objective function? What if its human creators harbor a conscious or unconscious bias?
		Fairness: If decisions are made based on an AI system, how to verify that they were made fairly? Fairness is contextual and has different perspectives depending on the particular data input given to the machine learning algorithms.
		Transparency: On what basis can individuals have the right to have the AI decisions explained in layman’s terms. Where and how can they be appealed? XAI tries to answer the transparency issues in intelligent systems.
		Safety: Can customers gain confidence in the reliability of the AI system without an explanation of how it reaches conclusions? This is closely related to the fundamental problem of generalization in statistical learning theory i.e. how tightly can we bind errors on the unseen data?
		Causality: Can the learned model provide not only correct inferences but also some explanation for the underlying phenomena? Can users gain a mechanistic understanding of a learned model?
		Engineering: How to debug incorrect output from a trained model?
	The challenge is to bring the balance between addressing these concerns and the predictability of the model.
