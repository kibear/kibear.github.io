# Storage Adapters

> Storage adapters provide an interface that allows ChatterBot to connect to different storage backends.

> The storage adapter that your bot uses can be specified by setting the storage_adapter parameter
to the import path of the storage adapter you want to use.

```python
chatbot = ChatBot(
    "My ChatterBot",
    storage_adapter="chatterbot.storage.SQLStorageAdapter"
)
```

