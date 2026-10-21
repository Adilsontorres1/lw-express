[README.md](https://github.com/user-attachments/files/33759495/README.md)
# Produção Fotovoltaica

Trabalho de recuperação da UC00618 – Criar aplicações em linguagem de programação Python (CET TPSI, Turma 01-25).

# Problema:

Criar uma aplicação de consola para gerir proprietários de painéis solares e as suas instalações. Cada proprietário pode ter uma ou várias instalações, e cada instalação tem código, potência (kW), localização, tipo de painel, estado (Operacional / Não Operacional) e data da última verificação.

#A aplicação permitirá:

- adicionar e remover proprietários;
- adicionar e remover instalações de um proprietário;
- alterar o estado de uma instalação (atualizando a data e hora da verificação);
- listar proprietários e calcular potências (total, operacional e não operacional, por proprietário e global);
- listar os proprietários com instalações não operacionais;
- mostrar as instalações não operacionais por ordem decrescente de potência;
- guardar os dados num ficheiro e carregá-los automaticamente ao iniciar.

# O que vou usar:

- **Python 3**, só com a biblioteca padrão.
- **Dicionários e listas** para ligar cada proprietário às suas instalações.
- **Funções**, uma por funcionalidade, para o código ficar organizado.
- **Ciclos `for`** para percorrer os dados e **`if`** para as decisões.
- **`try/except`** para tratar erros, por exemplo valores inválidos ou o ficheiro não existir.
- **Ficheiro de texto** para guardar os dados.
- Um **menu** em ciclo para escolher as opções.

## Etapas do projeto

1. Ler o enunciado e decidir como guardar os dados (proprietários e instalações).
2. Criar o menu principal.
3. Implementar adicionar e remover proprietários e instalações, com validações (código repetido, potência negativa, estado inválido).
4. Implementar as consultas e os cálculos de potência.
5. Implementar a alteração de estado e a ordenação das instalações não operacionais.
6. Implementar guardar e carregar dados do ficheiro.
7. Testar tudo, tratar os erros e comentar o código.
8. Limpar o código final (remover testes e código desnecessário).


Nome: Adilson A. F. Torres
Nº 01  
Turma: Cet0125*
