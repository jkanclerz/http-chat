Sieci komputerow - uek 2019
---------------------------

Przykładowy czat 

Aby uruchomić serwer

```bash
cd server
python httpchat.py
```

Wysyłka wiadomości
```bash

curl -X POST -d '{"text": "Hello World"}' http://{ip_address}:8888
```

Pobranie wiadomości
```bash

curl -X POST -d '{"last_message_id":-1}' http://{ip_address}:8888/messages | python -m json.tool
```


![alt text][chat]

[chat]: ./images/Przykładowy_HTTP_chat.png "Logo Title Text 2"



------------------------------------------------------------
"Zrozumieć programowanie", Gynvael Coldwind PWN, Warszawa 2015
https://github.com/gynvael/zrozumiec-programowanie 