<h1 align="center">
  <img src="assets/reprograma-fundos-claros.png" alt="logo reprograma" width="500">
</h1>

# Condicionais, operadores lógicos, erros e exceções

Turma Online On34 | Python | Semana 03 | 2024 | <a href="https://www.linkedin.com/in/erikacamposdesign/" target="_blank" rel="noopener noreferrer">Professora Erika Campos</a>

### Instruções 
Antes de começar, vamos organizar nosso setup.

Faça passo a passo os tópicos abaixo:
* Fork esse repositório. 
* Clone o fork na sua máquina. Para isso basta abrir o seu terminal e digitar `git clone url-do-seu-repositorio-forkado`.
* Entre na pasta do seu repositório. Para isso basta abrir o seu terminal e digitar `cd nome-do-seu-repositorio-forkado`.  
* Agora você está pronta para trabalhar.

## Conteúdo
### Condicionais
* If
* Else
* Elif

### Operadores Relacionais 
| Operador | Descrição | Exemplo | Resultado |
| --- | --- | --- | --- |
| == | igual | 1 == 1 | True |
| == | igual | 1 == 3 | False |
| != | diferente | 1 != 3 | True |
| != | diferente | 1 != 1 | False |
| > | maior que | 3 > 1 | True |
| > | maior que | 1 > 3 | False |
| >= | maior ou igual | 3 >= 1 | True |
| >= | maior ou igual | 1 >= 3 | False |
| >= | maior ou igual | 1 >= 1 | True |
| < | menor que | 1 < 3 | True |
| < | menor que | 3 < 1 | False |
| <= | menor ou igual | 1 <= 3 | True |
| <= | menor ou igual | 3 <= 1 | False |
| <= | menor ou igual | 3 <= 3 | True |
   
### Operadores Lógicos
| Operador | Tradução |Descrição | Exemplo | Resultado |
| --- | --- | --- | --- | --- |
| and | e | True **e** True para ser True  | 1 != 3(True) and 1 < 3(True) | True |
| and | e | Se True **e** False, é False | 1 != 3(True) and 1 > 3(False) | False |
| or | ou | Só um **ou** outro precisa ser True | 1 == 3 (False) or 1 < 3 (True) | True |
| or | ou | Se os dois dão False, é False | 1 == 3 (False) or 1 > 3 (False) | False |
| not | não | Inverte o booleano | not False | True |
| not | não | Inverte o booleano | not True | False |

### Erros e seus tipos
Vamos ver quais são os variados tipos de erros que você pode encontrar no caminho. Saber que existem é o primeiro passo para conseguir compreender e contornar ;) 

### Usando o Debug do VSCode
Vamos ver como trabalhar com a ferramenta que vai te mostrar o código passo a passo para você encontrar os problemas mais rápido.

### Try e Except
Não queremos que nosso usuário veja um erro feio na tela. Vamos evitar isso com Try e Except.

### Exercícios 
* [Exercícios na sala](https://github.com/reprograma/on34-python-s03-logica-II/tree/main/exercicios/na-sala)
* [Exercícios para casa](https://github.com/reprograma/on34-python-s03-logica-II/tree/main/exercicios/para-casa)
* [Exercícios de Estrutura de Decisão - Python Brasil](https://wiki.python.org.br/EstruturaDeDecisao)
* [Beecrowd - Plataforma de exercícios em português](http://www.beecrowd.com.br/)
* [HackerRank - Plataforma de exercícios em inglês](https://www.hackerrank.com/)

### Material da aula 
* [Slides pré-aula](https://github.com/reprograma/on34-python-s03-logica-II/tree/main/material/Semana3_pre-aula.pdf)
* [Exercícios dos slides](https://github.com/reprograma/on34-python-s03-logica-II/tree/main/exercicios/na-sala/exercicios%20dos%20slides)
* [Exercícios para treinar](https://github.com/reprograma/on34-python-s03-logica-II/tree/main/exercicios/na-sala/para_treinar)

### Para conhecer mais
* [Curso em Vídeo - Condicionais parte 1](https://www.youtube.com/watch?v=K10u3XIf1-Q)
* [Automatize Tarefas Maçantes com Python, site em inglês, mas existe o livro em português](https://automatetheboringstuff.com/)


<p align="center">
Desenvolvido com MUITO :purple_heart:  
</p>

