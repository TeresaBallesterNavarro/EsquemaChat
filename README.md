# EsquemaChat

Hay 2 archivos: esquema_chat_client.py y esquema_chat_listener.py. Ambos implementados en código Python, ambos archivos forman un programa distribuido de paso de mensajes. El archivo client se encarga de mandar mensajes a listener, subscribiéndose en el canal (mediante el puerto:'port'). En caso de que la conexión sea la correcta, listener lee ('escucha') los mennsajes.
