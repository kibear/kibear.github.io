# Logic Adapters

> Logic adapters determine the logic for how ChatterBot selects a response to a given input statement.

> The logic adapter that your bot uses can be specified by setting the logic_adapters parameter to the
import path of the logic adapter you want to use.

> It is possible to enter any number of logic adapters for your bot to use. If multiple adapters are used,
then the bot will return the response with the highest calculated confidence value.
If multiple adapters return the same confidence, then the adapter that is entered into the list first will take priority.

```python
chatbot = ChatBot(
    "My ChatterBot",
    logic_adapters=[
        "chatterbot.logic.BestMatch"
    ]
)
````
