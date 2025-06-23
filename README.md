# 📌 ft_printf

Reimplementação da função `printf` da biblioteca padrão C como parte do currículo da 42.

Este projeto tem como objetivo recriar a função `printf`, manipulando diretamente strings, números e ponteiros, gerenciando a saída formatada via file descriptor padrão. Ele aprofunda o uso de ponteiros, variáveis variádicas (`va_list`) e conversões de tipos.

---

## ✅ Funcionalidades implementadas

- `%c` → caractere  
- `%s` → string  
- `%p` → ponteiro (formato hexadecimal com prefixo `0x`)  
- `%d` / `%i` → número decimal com sinal  
- `%u` → número decimal sem sinal  
- `%x` / `%X` → número hexadecimal (minúsculas / maiúsculas)  
- `%%` → imprime o caractere `%`

---

## 🛠️ Tecnologias e ferramentas

- Linguagem C (C99)
- Makefile
- Norminette (42 coding standard)

---

## 📂 Estrutura do projeto

- `ft_printf.c` – Função principal e controlador de formatos  
- `ft_handle_char.c` – Funções que lidam com strings e caracteres   
- `ft_handle_int.c` – Funções que lidam com inteiros
- `ft_handle_hex.c` – Funções que lidam com hexadecimais  
- `libftprintf.a` – Biblioteca gerada com as funções compiladas  
- `Makefile` – Compilação automatizada
- 
---

## 🧠 Aprendizados

- Uso de `stdarg.h` para manipular argumentos variádicos  
- Conversão de inteiros para strings em diferentes bases  
- Contagem manual de caracteres escritos  
- Tratamento de formatos e flags básicas  

---


