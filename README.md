<h1 align="center">VK-Listener - модуль для накручивания прослушиваний на Ваш альбом ВКонтакте.</h1>

<br>

<h1 align="center"> Как использовать </h1>

<h2 align="center"> Установите chromedriver.exe Вашей версии Google Chrome (https://chromedriver.chromium.org/downloads)<h2>
<h2 align="center"> Перетащите chromedriver.exe в C:/Users/User/AppData/Local/Google/Chrome<h2>


```python
import vk-listener

listener.init('hide')

listener.authorization('login', 'password')

if(listener.check()):
	print('Authorization was successful!')
else:
	print('Authorisation Error!')

listener.loop('album title', 15)
```
