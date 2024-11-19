Explicação de como executar o arquivo .sh

Acesse o Ubuntu
No usuário jul1985
Acesse a pasta Linux através do comando "cd Linux"
Uma vez na pasta execute o comando "ls" para ver todos os arquivos contidos nesse diretório.
Após realizada as permissões devidas execute o arquivo calculadora.sh por meio do seguinte comando:

./calculadora.sh

O script deve rodar

Explicação do seu código em python

while True:#o While é a condição pra se criar um loop infinito, e o Trué a variável que valida o código
  num1=float(input("Digite o Número:")) #o float nesse caso é a opção para utilização de casas decimais
  num2=float(input("Digite o Número:"))
  operador= input("Digite a operação (+,-,*,/): ")
  if operador == "+":
    resultado = num1 + num2
  elif operador == "-":
    resultado = num1 - num2
  elif operador == "*":
    resultado = num1 * num2
  elif operador == "/":#na divisão há duas subdivisões, se o número que vai dividir é zero dá erro, na outra situação
    #é a divisão normal
    if num2 == 0:
      print("Nenhum número pode ser dividido por zero")
    else:
      resultado = num1/num2
  else: #toda e qualquer informação colocada errada (fora do apresentado no código) vai apresentar um erro
    resultado = "ERRO"
  print(resultado)


