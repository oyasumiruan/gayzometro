# gayzometro
	from random import randint

	pergunta = input('qual o nome do gay? ')

	class Gay():
	
	def __init__(self, gay_name):
		self.gay_name = gay_name
		
	def porcentagem(self):
		self.porcento = randint(0, 100)
		print('O ' + self.gay_name.title() + ' e ' + 
		str(self.porcento) + '% gay.')

	gay = Gay(pergunta)
	
	gay.porcentagem()
