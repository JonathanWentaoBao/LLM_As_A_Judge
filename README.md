# LLM_As_A_Judge

Referenced and used https://huggingface.co/opencompass/CompassJudger-2-32B-Instruct for building the notebook and the model. 


## Procedure 
We generated 2 model prompts to a user by telling GPT-5 "Suppose you are a chatbot for a company that gives internal knowledge to the company employees about HR policies, benefits, and procedures." 
We then gave 2 intentionally poor prompts to GPT-5 to test evaluation. 
CompassJudger-2-7B-Instruct was told that the model it was evaluating should only respond in certain ways (that were violated by the poor prompts given), and we tested to see if it would return poor scores. 

Exact phrases used can be viewed in the bottom 2 cells of the notebook. 