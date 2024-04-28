<h3><b>CHATBOT: A Comparative Analysis</b></h3>


This project focuses on the development and evaluation of an AI-driven chatbot capable of comparative analysis across different models trained on two distinct datasets: Mental Health and Customer Support. By fine-tuning pretrained language models such as GPT-2, RoBERTa, and BERT on these datasets, the project aims to assess their performance in understanding and generating responses tailored to each domain. Through experimentation and evaluation, the project aims to provide insights into the effectiveness of various model architectures and training strategies for tasks involving mental health conversations and customer support interactions.


The Video Demonstration of this project: https://youtu.be/jcuoEOSYwpo

<h3> Project Description </h3>
<p>This project endeavors to construct an AI-driven chatbot capable of conducting a comparative analysis of Natural Language Processing (NLP) models across diverse datasets, focusing primarily on Mental Health and Customer Support datasets. Leveraging three pre-trained models—GPT-2, BERT (Bidirectional Encoder Representations from Transformers), and RoBERTa (a refined variant of BERT)—we fine-tune them on the datasets to assess their performance. Through rigorous experimentation and evaluation, we measure the accuracy of these models to discern their efficacy in handling specific datasets. We compare their performance to determine which model is better suited for a particular dataset, which should help with the selection of NLP models for various applications. This project not only contributes to advancing the field of NLP but also facilitates informed decision-making in deploying AI-driven solutions tailored to specific domains.</p><br/>

<h3> Project Components</h3>
<h4> Datasets</h4>
<h5> Mental Health Dataset </h5>
<p>The Mental Health dataset comprises conversations between patients and healthcare assistants discussing various mental health issues. Each entry in the dataset consists of conversational pairs of questions and answers, reflecting the dialogue flow between the patient and the healthcare provider<br/>
The dataset is publicly available and can be accessed via the provided link. The dataset is comprised of a single field:<br/>
    
●	text: This field contains conversational pairs representing questions posed by patients and corresponding answers provided by healthcare assistants. These exchanges encompass various mental health issues, offering a comprehensive view of the language used in such conversations.
</p>
<h5> Customer Support Dataset </h5>
<p>
  The Customer Support dataset includes discussions between clients and help desk agents, documenting a variety of questions and exchanges that take place in the customer support area. The dataset provides a rich collection of dialogues representing various categories of customer queries with a total of 26,872 rows.<br/>
    Each row is structured with the following fields:<br/>
●	Flags: This field employs tags to categorize different customer queries, allowing for targeted analysis of specific support needs.<br/>
●	Instruction: This field captures the actual customer request phrased in a natural language format, simulating real-world customer interactions.<br/>
●	category: This field provides a high-level understanding of the customer's intent by assigning a broader semantic category to the request.<br/>
●	intent: This field delves deeper, pinpointing the specific intent behind the customer's instruction, enabling more precise model responses.<br/>
●	response: This field presents an example answer crafted by a human support agent, offering a benchmark for training the NLP model to generate appropriate responses.<br/>

</p>

<h4> Model Training</h4>
 <p>
      In this project, we undertake a meticulous process of training and fine-tuning three leading pre-trained NLP models—GPT-2, BERT, and RoBERTa—on the Mental Health and Customer Support datasets. Leveraging transfer learning techniques, we initialize the models with pre-trained weights and fine-tune them on domain-specific data to capture nuanced language patterns and semantics within each domain. Throughout the iterative training process, we optimize hyperparameters, monitor training metrics, and conduct rigorous evaluations using task-specific metrics. This iterative refinement ensures that our models are effectively adapted to the characteristics of the datasets, enhancing their performance, and enabling more accurate analyses and responses tailored to the Mental Health and Customer Support domains. 

 </p> 

 <h4>Conclusion</h4>
 <p>
     
This project successfully evaluated the performance of GPT-2, RoBERTa, and BERT models on Mental Health and Customer Support datasets. While RoBERTa outperformed on Mental Health data, BERT showed superiority in Customer Support tasks. This underscores the importance of selecting models based on application domains. BERT exhibited exceptional performance across both datasets, particularly excelling in Customer Support. RoBERTa's potential in mental health tasks was evident, possibly due to its masked language modeling capability. GPT-2, though moderately accurate, didn't match BERT and RoBERTa's performance. These insights provide valuable guidance for practitioners, suggesting BERT as a promising choice for customer support chatbots and RoBERTa for mental health support.
 </p>
