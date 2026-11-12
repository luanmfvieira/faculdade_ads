Matéria de algoritmos e programação foi abordado conceitos simples onde visto anteriormente no curso de algoritmos e logica com guanabara, apenas revisando

aprendi um pouco o uso do C em algumas funções, revisei também conceitos como if else o que é bem simples.

![alt text](image.png)

---------------------

Linguagem C

Primeiro você precisa de um compilador, algo que transforma o seu código em binarios para o seu computador

Explicação simples

Você escreve o código:

printf("Olá mundo");

O compilador (GCC) traduz isso para binário, algo como:

101010101010010101010

Esse binário vira um programa executável.

GCC significa:

    *GNU Compiler Collection 🧰*

📌 Separando o nome

GNU → projeto de software livre criado por Richard Stallman

Compiler → compilador (programa que traduz código)

Collection → coleção de compiladores

📌 Por que "collection"?

Porque o GCC não compila só C. Ele inclui compiladores para várias linguagens:

C

C++

Fortran

Ada

Objective-C

#include <stdio.h>
int main()
{
	printf("Bem vindo ao seu primeiro Jogo em C!\n");
	return 0;
}

stdio.h  - biblioteca padrão, uma das possibilidades sendo comandos de entrada e saida.
int é inteiro e main() - função principal, onde o programa começa a execução.

entre as chaves é onde todo o código C será traduzido

return 0 é para o main retornar 0 informando que o codigo chegou até lá e deu certo.




--------------

Instalar o GCC

Abra o PowerShell como administrador e rode:

winget install -e --id BrechtSanders.WinLibs.POSIX.UCRT

Isso instala GCC + ferramentas de C/C++.

2️⃣ Verificar se instalou

Depois digite:

gcc --version

Se aparecer algo tipo:

gcc (Rev...) 13.x.x

Então está funcionando.

![alt text](image.png)

--------------------------------
