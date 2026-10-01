# ♟️ Xadrez em C# (Console)

Jogo de xadrez para dois jogadores, executado no terminal e desenvolvido em **C# / .NET**.
O projeto foi construído durante o curso **C# Completo: Programação Orientada a Objetos + Projetos** (Udemy, Nelio Alves) para praticar e consolidar os conceitos de POO.

## Funcionalidades

- Tabuleiro 8x8 exibido no console, com a posição das peças
- Todas as peças do xadrez: Rei, Dama, Torre, Bispo, Cavalo e Peão
- Validação dos movimentos de cada peça
- Alternância de turnos entre as peças brancas e pretas
- Detecção de xeque e xeque-mate
- Jogadas especiais: roque, en passant e promoção do peão
- Tratamento de erros para jogadas inválidas, com mensagens claras ao jogador

> Ajuste esta lista deixando apenas o que está implementado no seu código.

## Conceitos de C# e POO aplicados

| Conceito | Onde aparece no projeto |
|---|---|
| Classes e encapsulamento | Tabuleiro, posição, peças e partida |
| Herança e polimorfismo | Cada peça herda de uma classe base e define seu próprio movimento |
| Classes abstratas | Classe base `Peca` com o comportamento comum |
| Enumerações | Cor das peças |
| Composição | A partida utiliza o tabuleiro, que contém as peças |
| Tratamento de exceções | Exceção própria para erros do tabuleiro e das regras |
| Coleções (List, HashSet) | Controle das peças em jogo e das capturadas |

## Como executar

Pré-requisito: [.NET SDK](https://dotnet.microsoft.com/download) na versão indicada no arquivo `.csproj` do projeto.

```bash
git clone https://github.com/EngKaiodev/Xadrez.git
cd Xadrez
dotnet run --project Xadrez-console
```

## Como jogar

1. O jogo começa com as peças brancas.
2. Informe a posição de origem da peça (exemplo: `e2`) e pressione Enter.
3. O tabuleiro destaca as jogadas possíveis.
4. Informe a posição de destino (exemplo: `e4`).
5. O jogo continua até o xeque-mate.

## Estrutura do projeto

```
Xadrez/
├── Xadrez-console.slnx
└── Xadrez-console/      # código-fonte do jogo
```

## Tecnologias

- C#
- .NET
- Git e GitHub

## Aprendizados

Este projeto me ajudou a fixar, na prática, como organizar um sistema em classes, separar responsabilidades e usar herança, polimorfismo e interfaces para reduzir código repetido e facilitar a manutenção.

## Autor

**Kaio dos Santos Lopes**
[LinkedIn](https://linkedin.com/in/lopeskaio) | [GitHub](https://github.com/EngKaiodev)
