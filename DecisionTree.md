##Estrutura de Decisão - Decision Tree (Árvore de Decisão)

QUESTÃO: Utilize estruturas de decisão <se-senão> para construir um script que simule uma árvore de decisão. Para cada nó da árvore, o usuário deve fornecer um valor a ser armazenado em uma variável e utilizado para verificar o fluxo que deve ser seguido até atingir um dos nós-folha, exibindo algum dos valores "Opção 1", "Opção 2" ou "Opção 3".

### Script:

<Definindo as variáveis e respectivos valores iniciais: X1, X2, X3 e X4>

x1 = 0

x2 = 0

x3 = 0

x4 = 0

print ("Insira o valor para X1 entre 0 e 5:") <Solicita que o usuário digite um valor inicial para a variável X1 dentro de um range de 1 a 5 (valor arbitrário!)>

x1 = input()

x1 = float(x1) <Transforma a variável X1 em tipo float para que estruturas matemáticas possam ser aplicadas posteriormente>

if x1 > 3.77: <Vai fazer uma comparação de X1 com o valor 3.77>

​    print ("Opção 1") <Caso o valor seja maior que 3.77, irá retornar para o usuário o texto "Opção 1", caso contrário, irá seguir com o script>

else: 

​    print ("Insira o valor para X2 entre 0 e 1:") <Solicita que o usuário digite um valor inicial para a variável X2 dentro de um range de 0 a 1>

​    x2 = input()

​    x2 = float(x2) <Transforma a variável X2 em tipo float para que estruturas matemáticas possam ser aplicadas posteriormente>

​    if x2 > 0.5: <Avalia a condição de X2 ser maior que 0.5. Em caso positivo, solicita ao usuário inclusão do valor de X3. Caso contrário, ou seja, X2 ser menor ou igual a 0.5, solicita ao usuário a inclusão do valor da variável X4>

​        print ("Insira o valor para X3 entre 0 e 1:") <Solicita que o usuário digite um valor inicial para a variável X3 dentro de um range de 0 a 1>

​        x3 = input()

​        x3 = float(x3) <Transforma a variável X3 em tipo float para que estruturas matemáticas possam ser aplicadas posteriormente>

​        if x3 >= 0.78: <Cria uma nova condição de decisão para X3>

​            print("Opção 2") <Avalia a condição de X1 ser menor ou igual a 3.77, e X2 ser maior que 0.5, e X3 ser maior ou igual a 0.78, retornando para o usuário o texto "Opção 2">

​        else:

​            print("Opção 1") <Avalia a condição de X1 ser menor ou igual a 3.77, e X2 ser maior que 0.5, e X3 ser menor 0.78, retornando para o usuário o texto "Opção 1">

​    else:

​        print ("Insira o valor para X4 entre 0 e 1:") <Solicita que o usuário digite um valor inicial para a variável X4 dentro de um range de 0 a 1>

​        x4 = input()

​        x4 = float(x4) <Transforma a variável X4 em tipo float para que estruturas matemáticas possam ser aplicadas posteriormente>

​        if x4 <= 0.25: <Cria uma nova condição de decisão para X4>

​            print("Opção 2") <Avalia a condição de X1 ser menor ou igual a 3.77, e X2 ser menor ou igual a 0.5, e X4 ser menor ou igual a 0.25, retornando para o usuário o texto "Opção 2">

​        else:

​            if x4 == 0.5: <Cria uma nova condição de decisão para X4>

​                print("Opção 3") <Avalia a condição de X1 ser menor ou igual a 3.77, e X2 ser menor ou igual a 0.5, e X4 ser igual a 0.5, retornando para o usuário o texto "Opção 3">

​            else:

​                if x4 > 0.5: <Cria uma nova condição de decisão para X4>

​                    print("Opção 2") <Avalia a condição de X1 ser menor ou igual a 3.77, e X2 ser menor ou igual a 0.5, e X4 ser maior do que 0.5, retornando para o usuário o texto "Opção 2">

​                else:

​                    print("Opção 1") <Avalia a condição de X1 ser menor ou igual a 3.77, e X2 ser menor ou igual a 0.5, e X4 ser maior do que 0.25 e menor do que 0.5, retornando para o usuário o texto "Opção 1">