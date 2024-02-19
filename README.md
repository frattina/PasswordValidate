## Desafio

Construa uma aplicação em .NET que exponha uma api web que valide uma senha.

Input: Uma senha (string).  
Output: Um boolean indicando se a senha é válida e caso seja inválida, listar os erros.


# Especificação

Considere uma senha sendo válida quando a mesma possuir as seguintes definições:

- Nove ou mais caracteres
- Ao menos 1 dígito
- Ao menos 1 letra minúscula
- Ao menos 1 letra maiúscula
- Ao menos 1 caractere especial
- Considere como especial os seguintes caracteres: !@#$%^&*()-+
- Não possuir caracteres repetidos dentro do conjunto
- Espaços em branco não devem ser considerados como caracteres válidos

Exemplo:  

```c#
IsValid("") // false  
IsValid("aa") // false  
IsValid("ab") // false  
IsValid("AAAbbbCc") // false  
IsValid("AbTp9!foo") // false  
IsValid("AbTp9!foA") // false
IsValid("AbTp9 fok") // false
IsValid("AbTp9!fok") // true
```


## Pontos que daremos maior atenção

- Abstração, acoplamento, extensibilidade e coesão
- Design de API
- Clean Code
- SOLID
- Documentação da solução no *README* 


### Sobre a documentação

Nesta etapa do processo seletivo queremos entender as decisões por trás do código, portanto é fundamental que o *README* tenha algumas informações referentes a sua solução.

Algumas dicas do que esperamos ver são:

- Instruções básicas de como executar o projeto;
- Detalhes sobre a sua solução, gostariamos de saber qual foi seu racional nas decisões;
- Caso algo não esteja claro e você precisou assumir alguma premissa, quais foram e o que te motivou a tomar essas decisões.


## Como esperamos receber sua solução

Nos envie o link de um repo público com a sua solução.

Se tiver algum imprevisto, dúvida ou problema, por favor, entre em contato com a gente, estamos aqui para ajudar.
