# LLM & RAG
LLMs have taken the world by storm and rightfully so. They help you with every day tasks like building a coding project, creating a recipe, or even writing a Medium article. While this is great, there are still major limitations that still exist. In my opinion, there are two key issues:

They do not have access to real time information.
They are prone to hallucinations.
I’m sure many of you have seen a response like this where it is not able to generate a response due to its training data:

We are at the mercy of when new models are released with expanded training data. But what if we want an assistant that can answer a question about something that happened in 2023? What about asking questions about something that happened this week? Or what if you want the LLM to have more information so that we can improve response accuracy?

In these scenarios, fine tuning is an option but comes with its own risks/challenges:

Model Drift: Over time, as the model is continuously fine-tuned with new data, it might start to drift from its original performance and behavior. This could lead to unexpected and undesirable results.
Costly and Complex: This approach not only presents significant technical challenges, but it also incurs substantial costs. The need to fine-tune our model on a weekly basis would require a considerable investment in terms of computational resources and expert manpower, making it a complex and expensive endeavor.
