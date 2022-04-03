#Self é um parâmetro uma variável que indica a referência à classe

#A variável nome guarará o nome que iremos passsar. 

#objeto1 = PrimeiraClasse()

# Instanciando um objeto do tipo PrimeiraClasse. Objeto1 é um objeto da classe (acessa atributos e métodos).

class Covid():
    def posicao(self):
        print('-------------')
    def nome(self):
        print('-------------')
    def casos(self):
        print('-------------')
    def mortes(self):
        print('-------------')

#Acima encontra-se a primeira classe do programa, onde as características principais ficam alocadas.

class Brasil(Covid):
    def posicao(self):
        print('3° LUGAR')
    def nome(self):
        print('-> Brasil - América do Sul')
    def casos(self):
        print('29.000.000 casos por Covid-19')
    def mortes(self):
        print('658.000 mortes confirmadas por Covid-19 e cerca de 28.300.000 curados')
#Acima a classe que está utilizando a primeira como referência , contendo os dados da COVID no Brasil.

class main():
 bra = Brasil()
 print('Brasil: ')
 bra.posicao()
 bra.nome()
 bra.casos()
 bra.mortes()

#O programa principal é onde são exibidas as informações inseridas 

if __name__ == "__main__": main()
#O encerramento do programa principal acontece com o “if”
