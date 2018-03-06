# Input Adapters

> ChatterBot’s input adapters are designed to allow a chat bot to have a versatile method of
receiving or retrieving input from a given source.

> The goal of an input adapter is to get input from some source, and then to convert it into a
format that ChatterBot can understand. This format is the Statement object found in ChatterBot’s conversation module.

```python
chatbot = ChatBot(
    "My ChatterBot",
    input_adapter="chatterbot.input.VariableInputTypeAdapter"
)
```
