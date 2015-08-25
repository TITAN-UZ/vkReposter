# vkReposter


Для использования скрипта нужно использовать ВК приложение stand-alone. Авторизацию проходить через браузер.

Пример:

oauth.vk.com/authorize?client_id=5024887&v=5.35&scope=wall,offline,groups&redirect_uri=http://oauth.vk.com/blank.html&display=page&response_type=token

client_id =   приложения в vk
scope = права (стена, оффлайн и группы)
redirect_uri - обязательно http://oauth.vk.com/blank.html - иначе не будет магии
response_type -  не менее обязательно, в респонсе этого запроса (в адресной строке вернется аксес токен который можно будет использовать)




