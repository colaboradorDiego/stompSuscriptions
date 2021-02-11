# stompSuscriptions

# Lecturas recomendadas
	1. STOMP - en video https://www.youtube.com/watch?v=zKkPrwpmesM

# stomp.py
“stomp.py” is a Python client library for accessing messaging servers (such as ActiveMQ, Artemis or RabbitMQ) using the STOMP protocol
	project -> https://pypi.org/project/stomp.py/
	docs -> http://jasonrbriggs.github.io/stomp.py/index.html
	
	https://github.com/search?q=stomp+client
	cliente ejemplo -> https://github.com/sithu/stomp-client/tree/master/python/stomppy
	cliente mas profesional -> https://github.com/openraildata/stomp-client-python
	
	Entendiendo un poco mas de STOMP
	STOMP What is it? -> https://stomp.github.io/
	STOMP for sysAdmins -> https://medium.com/@bilal.rifas/stomp-protocol-dc54813c3b95
	
# PS_1
	Luego de probar fallidamente utilizando stomp.py comence a buscar otra alternativa, ahi encontre a stomper.py
	Entiendo que son dos clientes que hacen los mismo pero me di cuenta que el error que cometia es que no lo
	estaba utilizando sobre websockets, sino como cliente directo.
	Por general nadie expone los servicios de mensages directos sino que lo hacen con un api expuesta por websockets 
	para darle mayor segurigad al sistema.
	

# stomper.py
	https://pypi.org/project/stomper/
	https://stackoverflow.com/questions/34574349/sockjs-python-client
	
	https://github.com/sockjs/sockjs-client
	https://github.com/openraildata/stomp-client-python/blob/master/opendata-nationalrail-client.py
	https://github.com/sithu/stomp-client/blob/master/python/stomppy/publisher.py
