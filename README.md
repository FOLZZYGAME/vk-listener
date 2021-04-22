<h1 align="center">VK-Listener - модуль для накручивания прослушиваний на Ваш альбом ВКонтакте.</h1>

<br>

<h1 align="center"> How to use </h1>

<h2 align="center"> Перед использованием убедитесь, что у Вас установлен chromedriver Вашей версии Google Chrome. <h2>


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
