# Exercício Validação
Realizado no 2º Meetup do FCC Brasília.

**Instrução**: utilize os arquivos 'index.html' e/ou 'validacao.js' para resolver os desafios propostos.
Comente seu código.

## Desafio 1

Verificar se os dados informados no formulário estão de acordo com as regras de validação abaixo.

- Nome Completo: deverá ser composto por, pelo menos, nome e um sobrenome.
- Telefone: deverá ter de 8 a 13 dígitos.
- Cartão de Crédito: deverá ter 16 dígitos.
- CPF: deverá ter 11 dígitos.

**Output**
>Desafio 1:

>Nome Completo (tem nome e sobrenome | curto)

>Telefone (não é numérico | curto | tem 11 dígitos | longo)

>Cartão de Crédito (não é numérico | curto | tem 16 dígitos | longo)

>CPF (não é numérico | curto | tem 11 dígitos | longo)


## Desafio 2
- Formatar para que cada parte do **nome completo** tenha somente a primeira letra maiúscula
- Formatar o **telefone** para o padrão +00 (00) 0000-0000
- Formatar o **cartão de crédito** para o padrão 0000-0000-0000-0000
- Formatar o **CPF** para o padrão 000.000.000-00


Obs.: as formatações só devem acontecer se os itens (nome, telefone, ...) passaram na validação do Desafio 1

**Output**:
>Desafio 2:

>Nome Completo: João Pereira

>Telefone: +55 (61) 9999-9999

>Cartão de Crédito: 0000-0000-0000-0000

>CPF: 000.000.000-00

## Desafio 3
- Validar se o **email** informado está em um padrão válido
- Verificar se a data do **cartão de crédito** ainda é válida ou se já está expirada
- Verificar se o **CPF** é válido (ver [algoritmo de CPF](http://www.geradorcpf.com/algoritmo_do_cpf.htm))

**Output**:
>Desafio 3:

>Cartão de Crédito (válido | expirado)

>Email (válido | inválido)

>CPF (válido | inválido)


## Links Úteis:
* [HTML Input Types](http://www.w3schools.com/html/html_form_input_types.asp)
* [innerHTML](http://www.w3schools.com/jsref/prop_html_innerhtml.asp)
* [value](http://www.w3schools.com/jsref/prop_text_value.asp)
* [Condicional IF](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Statements/if...else)
* [Lenght](http://www.w3schools.com/jsref/jsref_length_string.asp)
* [Expressões Regulares 1](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Guide/Regular_Expressions)
* [Expressões Regulares 2](http://eloquentjavascript.net/09_regexp.html)
* [toUpperCase()](http://www.w3schools.com/jsref/jsref_touppercase.asp)
* [Dates](http://www.w3schools.com/js/js_dates.asp)
* [Alert](http://www.w3schools.com/jsref/met_win_alert.asp)
