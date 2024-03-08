# ActiveLoop-Course


When you declare a model is like this:

´´´
llm = OpenAI(model="gpt-3.5-turbo-instruct", temperature=0)
´´´

- This are models examples like gpt-3.5-turbo-instruct or text-davincii-002

When you use a ChatModel you need to declare it like this:

´´´
llm = OpenAI(model_name="gpt-3.5-turbo", temperature=0)
´´´
