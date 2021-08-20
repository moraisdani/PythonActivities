# Estrutura de Decisão - Decision Tree (Árvore de Decisão)

QUESTÃO: 
Utilize estruturas de decisão <se-senão> para construir um script que simule uma árvore de decisão. Para cada nó da árvore, o usuário deve fornecer um valor a ser armazenado em uma variável e utilizado para verificar o fluxo que deve ser seguido até atingir um dos nós-folha, exibindo algum dos valores "Opção 1", "Opção 2" ou "Opção 3".

### Script:

// Definindo as variáveis e respectivos valores iniciais: X1, X2, X3 e X4 \

x1 = 0

x2 = 0

x3 = 0

x4 = 0

// Solicita que o usuário digite um valor inicial para a variável X1 dentro de um range de 1 a 5 (valor arbitrário!) \
print ("Insira o valor para X1 entre 0 e 5:") 

x1 = input()

// Transforma a variável X1 em tipo float para que estruturas matemáticas possam ser aplicadas posteriormente \
x1 = float(x1) 

// Vai fazer uma comparação de X1 com o valor 3.77 \
if x1 > 3.77: 

// Caso o valor seja maior que 3.77, irá retornar para o usuário o texto "Opção 1", caso contrário, irá seguir com o script \
​    print ("Opção 1") 

else: 
// Solicita que o usuário digite um valor inicial para a variável X2 dentro de um range de 0 a 1 \
​    print ("Insira o valor para X2 entre 0 e 1:") 

​    x2 = input()

//  Transforma a variável X2 em tipo float para que estruturas matemáticas possam ser aplicadas posteriormente \
​    x2 = float(x2)

// Avalia a condição de X2 ser maior que 0.5. Em caso positivo, solicita ao usuário inclusão do valor de X3. Caso contrário, ou seja, X2 ser menor ou igual a 0.5, solicita ao usuário a inclusão do valor da variável X4 \
​    if x2 > 0.5: 

// Solicita que o usuário digite um valor inicial para a variável X3 dentro de um range de 0 a 1 \
​        print ("Insira o valor para X3 entre 0 e 1:") 

​        x3 = input()

// Transforma a variável X3 em tipo float para que estruturas matemáticas possam ser aplicadas posteriormente \
​        x3 = float(x3) 

// Cria uma nova condição de decisão para X3 \
​        if x3 >= 0.78: 

// Avalia a condição de X1 ser menor ou igual a 3.77, e X2 ser maior que 0.5, e X3 ser maior ou igual a 0.78, retornando para o usuário o texto "Opção 2" \
​            print("Opção 2") 

​        else:

// Avalia a condição de X1 ser menor ou igual a 3.77, e X2 ser maior que 0.5, e X3 ser menor 0.78, retornando para o usuário o texto "Opção 1" \
​            print("Opção 1") 

​    else:

// Solicita que o usuário digite um valor inicial para a variável X4 dentro de um range de 0 a 1 \
​        print ("Insira o valor para X4 entre 0 e 1:") 

​        x4 = input()

// Transforma a variável X4 em tipo float para que estruturas matemáticas possam ser aplicadas posteriormente \
​        x4 = float(x4) 

// Cria uma nova condição de decisão para X4 \
​        if x4 <= 0.25: 

// Avalia a condição de X1 ser menor ou igual a 3.77, e X2 ser menor ou igual a 0.5, e X4 ser menor ou igual a 0.25, retornando para o usuário o texto "Opção 2" \
​            print("Opção 2") 

​        else:

// Cria uma nova condição de decisão para X4 \
​            if x4 == 0.5: 

// Avalia a condição de X1 ser menor ou igual a 3.77, e X2 ser menor ou igual a 0.5, e X4 ser igual a 0.5, retornando para o usuário o texto "Opção 3" \
​                print("Opção 3") 

​            else:

// Cria uma nova condição de decisão para X4 \
​                if x4 > 0.5: 

// Avalia a condição de X1 ser menor ou igual a 3.77, e X2 ser menor ou igual a 0.5, e X4 ser maior do que 0.5, retornando para o usuário o texto "Opção 2" \
​                    print("Opção 2") 

​                else:
// Avalia a condição de X1 ser menor ou igual a 3.77, e X2 ser menor ou igual a 0.5, e X4 ser maior do que 0.25 e menor do que 0.5, retornando para o usuário o texto "Opção 1" \
​                    print("Opção 1") 
