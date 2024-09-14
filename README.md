# Módulo de validação de senha

Para que a senha seja considerada válida foram adotados os seguintes critérios:

 - Deve conter nove ou mais caracteres;
 - Ao menos 1 dígito;
 - Ao menos 1 letra minúscula;
 - Ao menos 1 letra maiúscula;
 - Ao menos 1 caracter especial;
 - Considere como especial os seguintes caracteres: !@#$%^&*()-+
 - Não possuir caracteres repetidos dentro do conjunto;
 - Não possuir espaços em branco.
 
Exemplo:

IsValid("") // false  
IsValid("aa") // false  
IsValid("ab") // false  
IsValid("AAAbbbCc") // false  
IsValid("AbTp9!foo") // false  
IsValid("AbTp9!foA") // false
IsValid("AbTp9 fok") // false
IsValid("AbTp9!fok") // true




