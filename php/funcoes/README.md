#Funções

Uma função pode ser definida a partir da utilização da seguinte estrutura:

```php
function nome_da_funcao ()
{
    $valor_retorno="Exemplo de função retornando este valor.";
    return $valor_retorno;
}
```

Uma **função** pode ou não ter parâmetros. A seguir é apresentada uma  função com 1 parâmetro. Caso necessite passar mais parâmetros para uma função, basta inserí-los esepará-los por vírgula (`,`).

```php
function primeira_funcao_param ($arg_1)
{
    return $arg_1;
}
```
Conforme apresenteado, as funções podem ser definidas pelos usuários. Existem também uma série de funçõe definidas na linguagem PHP, por exemplo, funções para manipular strings ou [`arrays`](funcoes-array.md). 

>**Exercícios**


>**Exercício 1**: Faça um programa que gere como saída as tabuadas de adição, subtração, multiplicação e divisão dos números 1, 2, 3, 4, 5, 6, 7, 8, 9 e 10. A saída deve ser em HTML e cada linha da tabuada deve ser gerada automaticamente (através do uso do laço de repetição). Seu código deve ser organizado em funções. Devem conter, no mínimo, 4 funções, uma para cada operação matemática: soma, subtração, multiplicação, divisão. 