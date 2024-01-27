# Deep-generative-transformer-based-model-for-de-novo-design-of-proteins
I developed a Transformer-based generative model tailored explicitly for training on protein datasets, focusing on generating de novo proteins. The model is structured similarly to a GPT, containing approximately 80 million trainable parameters. I employed this model to create LLPS-positive proteins, a challenging task due to the scarcity of available data. Notably, when fine-tuning complex protein generative models like ProtGPT2 and ProGen on our dataset, the result was the production of proteins containing highly repetitive sequences, reflecting the limitations of the training data. However, our simple model demonstrated an exciting outcome. It successfully generated LLPS-positive proteins with diverse and non-repetitive sequences, achieving high LLPS scores and promising BLAST results.


 
