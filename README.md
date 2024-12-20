# Conversor de Unidades em Linguagem C

## Descrição
Este projeto implementa um conversor de unidades simples, permitindo conversões entre diferentes sistemas de medidas.

## Tabela de Conteúdos

- [Objetivo do Projeto](#objetivo-do-projeto)
- [Estrutura do Repositório](#estrutura-do-repositório)
- [Como Rodar o Projeto](#como-rodar-o-projeto)
- [Delegação de Tarefas](#delegação-de-tarefas)
- [Prazos e Datas Importantes](#prazos-e-datas-importantes)
- [Links Importantes](#links-importantes)

## Objetivo do Projeto

O objetivo deste projeto é criar uma ferramenta de conversão de unidades de medidas para diferentes categorias, como:
- Comprimento (metros, centímetros, milímetros)
- Massa (quilogramas, gramas, toneladas)
- Volume (litros, mililitros, metros cúbicos)
- E mais...

A aplicação será desenvolvida em C, organizada de maneira modular, com cada conversor responsável por uma categoria de unidades.

## Estrutura do Repositório

A estrutura do repositório é organizada da seguinte forma:

````
conversor-unidades/
├── src/             # Código-fonte (arquivos .c)
├── include/         # Cabeçalhos (arquivos .h)
├── tests/           # Testes
├── README.md        # Documentação do projeto
````


## Como Rodar o Projeto

Para rodar o projeto localmente, siga os seguintes passos:

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/adimael/conversor-unidades.git
   ````
2. Entre na pasta do projeto:
````
cd conversor-unidades
````

3. Compile o código: Para compilar o projeto, utilize o seguinte comando:
````
gcc -o conversor main.c src/comprimento.c src/massa.c src/volume.c -Iinclude
````

4. Execute o programa: Após a compilação, execute o programa com o comando:
````
./conversor
````

## Delegação de Tarefas

Cada membro do projeto ficou responsável por uma parte específica do conversor. Abaixo estão as tarefas delegadas, com o nome do responsável e o nome sugerido para a branch.

| **Membro**           | **Tarefa**                                  | **Branch Sugerida**            |
|----------------------|---------------------------------------------|--------------------------------|
| **Matheus Mato**      | Criar conversor de comprimento              | `feature/conversor-comprimento` |
| **Vivian Rodrigues**  | Criar conversor de massa                    | `feature/conversor-massa`      |
| **Daniel Silva**      | Criar conversor de volume                   | `feature/conversor-volume`     |
| **Adimael Santos**    | Criar conversor de temperatura              | `feature/conversor-temperatura`|
| **Mychael Matos**     | Criar conversor de velocidade               | `feature/conversor-velocidade` |
| **Eric Franco**       | Criar conversor de potência                 | `feature/conversor-potencia`   |
| **Caio Bruno**        | Criar conversor de área                     | `feature/conversor-area`       |
| **Mychael Matos**     | Criar conversor de tempo                    | `feature/conversor-tempo`      |
| **Saulo**             | Criar conversor de dados                    | `feature/conversor-dados`      |
| **Tarefa Livre**      | Implementar Interface de usuário            | `feature/interface-usuario`   |
| **Tarefa Livre**      | Implementar testes e depuração              | `tests/implementacao`          |
| **Adimael Santos**    | Criar o arquivo README.md                   | `docs/readme`                  |

## Prazos e Datas Importantes

- Data de início do projeto: 15/12/2024

- Data para finalizar e subir as tarefas: 22/12/2024 (como combinado durante a reunião)

- Data para revisão e merge das branches: 23/12/2024

- Data final do projeto: 26/12/2024

## **Links Importantes**

- [Material de Orientação e Organização para o Projeto](docs/Tutorial_Orientação_e_Organização_para_o_Projeto.pdf)

