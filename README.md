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


# Recheck the RetryOutput Parser is very obligatory to do it in every action

# If you want to transform the text to embeddings and chunks:
- Keeping Knowledge Organized with Indexes
- What are Text Splitters and Why they are useful
