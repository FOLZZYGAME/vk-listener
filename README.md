<h1 align="center">vk-listener - Module for Listening to VKontakte Albums.</h1>

<br>

<h1 align="center"> How to use </h1>

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
