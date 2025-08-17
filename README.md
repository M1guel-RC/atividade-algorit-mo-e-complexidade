🧮 Calculadora de Operações Matemáticas em Python (Google Colab)

Um programa simples em Python para realizar operações matemáticas em números reais, diretamente no Google Colab. Você pode calcular quadrado, cubo, raiz quadrada ou potência de um número.

✨ Funcionalidades

O programa oferece as seguintes operações:

Opção	Operação	Descrição
1️⃣	Quadrado	Eleva o número ao quadrado
2️⃣	Cubo	Eleva o número ao cubo
3️⃣	Raiz Quadrada	Calcula a raiz quadrada (somente números positivos)
4️⃣	Potência	Eleva o número a um expoente informado
5️⃣	Sair	Encerra o programa

⚙️ Como o programa funciona

O código importa a biblioteca math para usar a função sqrt (raiz quadrada).
Existem quatro funções principais:

quadrado(x)
cubo(x)
raiz_quadrada(x)
potencia(base, expoente)

A função main() exibe o menu interativo, recebe o número do usuário e chama a função correspondente.
O menu continua até que o usuário escolha sair.

❗ Observações importantes

Para raiz quadrada, números negativos não são permitidos.
O programa aceita números decimais (float).
No Colab, a interação é feita com input(), então você digita os valores diretamente nas células quando solicitado.
