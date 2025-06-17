- Imagine now you run a special shop, like a baby store, selling diapers. Your super-smart friend (the LLM) doesn’t know your special diaper prices from the internet.
    
- With RAG, when you ask “How much for two bags?”, your friend doesn’t immediately guess from the internet.
    
- Instead, they first look into a special notebook (database) you give them, where you wrote down all your diaper prices.
    
- Now, they combine what they read from your special notebook with their ability to do basic math and reasoning.
    
- They respond with the correct answer: “Two bags cost $12.”
    

This is better than just guessing from the internet, because the information is specific and accurate for your business.


When should you use RAG (Retrieval-Augmented Generation)?  
  
RAG is an AI technique that retrieves information from an external knowledge base to ground LLM on accurate, up-to-date information.  
  
Here are some reasons you might want to use RAG:  
  
𝟭. 𝗔𝗰𝗰𝗲𝘀𝘀 𝘁𝗼 𝘂𝗽-𝘁𝗼-𝗱𝗮𝘁𝗲 𝗶𝗻𝗳𝗼𝗿𝗺𝗮𝘁𝗶𝗼𝗻  
The knowledge of LLMs is limited to what they were exposed to during pre-training. With RAG, you can ground the LLM to the latest data feeds, making it perfect for real-time use cases.  
  
𝟮. 𝗜𝗻𝗰𝗼𝗿𝗽𝗼𝗿𝗮𝘁𝗶𝗻𝗴 𝗽𝗿𝗼𝗽𝗿𝗶𝗲𝘁𝗮𝗿𝘆 𝗱𝗮𝘁𝗮  
LLMs weren't exposed to your proprietary enterprise data (data about your users or your specific domain) during their training and have no knowledge of your company data. With RAG, you can expose the LLM to company data that matters.  
  
𝟯. 𝗠𝗶𝗻𝗶𝗺𝗶𝘇𝗶𝗻𝗴 𝗵𝗮𝗹𝗹𝘂𝗰𝗶𝗻𝗮𝘁𝗶𝗼𝗻𝘀  
LLMs are not accurate knowledge sources and often respond with made-up answers. With RAG, you can minimize hallucinations by grounding the model to your data.  
  
𝟰. 𝗥𝗮𝗽𝗶𝗱 𝗰𝗼𝗺𝗽𝗮𝗿𝗶𝘀𝗼𝗻 𝗼𝗳 𝗟𝗟𝗠𝘀  
RAG applications allow you to rapidly compare different LLMs for your target use case and on your data, without the need to first train them on data (avoiding the upfront cost and complexity of pre-training or fine-tuning).  
  
𝟱. 𝗖𝗼𝗻𝘁𝗿𝗼𝗹 𝗼𝘃𝗲𝗿 𝘁𝗵𝗲 𝗸𝗻𝗼𝘄𝗹𝗲𝗱𝗴𝗲 𝘁𝗵𝗲 𝗟𝗟𝗠 𝗶𝘀 𝗲𝘅𝗽𝗼𝘀𝗲𝗱 𝘁𝗼  
RAG applications let you add or remove data without changing the model. Company policies change, customers' data changes, and unlearning a piece of data from a pre-trained model is expensive. With RAG, it's much easier to remove data points from the knowledge your LLM is exposed to.  

![[Pasted image 20250501180444.png]]

[[Semantic Search]]
[[AWS Support for RAG]]