##Programa Orientado a objeto

QUESTÃO:  Criar uma classe que modele um ser humano, onde esta deve possuir os seguintes atributos e métodos:

- nome
- idade
- peso
- altura
- envelhecer()
- engordar()
- emagrecer()
- crescer()

O acesso aos atributos deve ser realizado através de métodos. O método *envelhecer* adicionar +1 na idade, o método *engordar* adiciona +1 no peso, o método *emagrecer* subtrai -1 no peso e o método *crescer* adicionar +1 na altura. *OBS.:Considere que a cada ano em que a pessoa envelhece, ela deve crescer 1 cm caso a idade dela seja menor que 20 anos.*



### Script:

class Humano:

​    def __init__(self, nome, idade, peso, altura):

​        self.__nome = nome

​        self.__idade = idade

​        self.__peso = peso

​        self.__altura = altura



​    @property

​    def nome(self):

​        return self.__nome

​    @nome.setter

​    def nome(self, nome):

​        self.__nome = nome

​    @property

​    def idade(self):

​        return self.__idade

​    @idade.setter

​    def idade(self, idade):

​        self.__idade == idade

​        @property

​    def peso(self):

​        return self.__peso

​    @peso.setter

​    def peso(self, peso):

​        return self.__peso == peso

​    @property

​    def altura(self):

​        return self.__altura

​    @altura.setter

​    def altura(self, altura):

​        return self.__altura == altura

​    

​    def envelhecer(self):

​        velho = self.__idade

​        velho = velho + 1

​        return print(velho)



​    def engordar(self):

​        gordo = self.__peso

​        gordo = gordo + 1

​        return print(gordo)



​    def emagrecer(self):

​        magro = self.__peso

​        magro = magro - 1

​        return print(magro)



​    def crescer(self):

​        cresce = self.__idade

​        i = 0

​        j = 0

​        if cresce < 20:

​            i = 20 - cresce.float()

​            while i <= j:

​                j = j + 1

​                altura = altura + j

​        return altura