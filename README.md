# LLM-powered-Clickbait-Detector
This project aims to develop and deploy a clickbait detection system leveraging cutting-edge NLP models and prompting techniques. `Comet ML` was used for  was used for experiment managenment and model versioning, prompt logging, tracking and debugging our prompts and results.
Three prompting techniques have been considered:
- Zero-shot: This technique provides the model with the infomation that tells it what task to perform but with no examples.
- Few-shot: This approach involves feeding the LLM model high quality examples to steer its response more effectively.
- Chain-of-Thought: In this approach, we guide the model through series of logical steps.

Regarding LLM model selection, OpenAI's gpt-3.5-turbo was selected as the base model. In comparison to the base LLM,  Google's flan-t5 model was fine-tuned to the specific requirements of the project

Follow through the attached jupyter notebooks to see the application of LLM for detecting whether a news article headline is clickbait or not.
