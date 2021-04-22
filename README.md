<h1 align="center">vk-listener - Module for Listening to VKontakte Albums.</h1>

<br>

<h1 align="center"> How to use </h1>

```python
import listener

# hide(hide) or show(add) browser
listener.init('hide')

# authorization
listener.authorization('login', 'password')

# vk authorization check
if(listener.check()):
	print('Authorization was successful!')
else:
	print('Authorisation Error!')

# listening, provide the link to your album and the listening delay time
listener.loop('album title', 15)
```
