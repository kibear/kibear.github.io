
# chatterbot install
pip install chatterbot

# Quick Start Guide
```python
# -*- coding: utf-8 -*-
from chatterbot import ChatBot
chatbot = ChatBot("Ron Obvious")

from chatterbot.trainers import ListTrainer

conversation = [
    "Hello",
    "Hi there!",
    "How are you doing?",
    "I'm doing great.",
    "That is good to hear",
    "Thank you.",
    "You're welcome."
]

chatbot.set_trainer(ListTrainer)
chatbot.train(conversation)

response = chatbot.get_response("Good morning!")
print(response)
```

