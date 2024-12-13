# ChatBOT_Parameter

## Terms/Parameters to Explain:
- Messages
- Model  
- Max Completion Tokens
- n
- Stream
- Temperature
- Top_p
- Tools

# 1. Messages
The message parameter is the  conversation history the list of every that we chat with chatbot it save all the history of chat between user ans Chatbot . 
### Purpose:
- It allows the assistant to keep track of chat to maintain a smooth conversation.

# 2. Model
The model parameter tells the system which version of the chatbot model to use for generating responses.like ChatGPTgpt-3.5-turbo , gpt-4
### Purpose:
- It lets you choose the version of the chatbot depending on how powerful or fast you need the responses to be.

# 3. Max Completion Tokens
max_tokens limits the length of the chatbot’s response, measured in tokens. Tokens are chunks of words. 
### Purpose:
- It helps you control how long or short the response should be.

# **4. n**
The n parameter specifies how many different answers you want the chatbot to generate for a single input.
### Purpose:
- It is useful when you want to see multiple anser of the same question.

# 5. Stream
The stream parameter controls whether the model should send the response piece-by-piece as it is generated or wait until it completed the full response .
### Purpose:
- It lets you decide if you want to get responses quickly ,or wait for complition.

# 6. Temperature
The temperature parameter controls how creative or random the assistant responses should be.
- it is 0.2 and 0.8 
### 0.2
- The response will be more predictable and serious.
### 0.8
- the response will be more creative or random.
### Purpose:
- It allows you to control how much variation you want in the assistant answers.

# 7. Top_p
Top_p is another way to control the creativity of the response, but it works differently from temperature. It controls how many possible words the assistant can choose from when creating a response.

# 8. Tools
The tools parameter allows the assistant to use external tools (like a calculator, search engine, or other APIs) to answer questions. This lets the assistant do more than just generate text—it can pull in real-time data or perform various tasks.
### Purpose:
- It lets the assistant access external resources to give you better or more accurate answers.
