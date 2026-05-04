# Sistema de Monitoramento de Reservatório de Água

Este projeto é uma simulação simples de um sistema de monitoramento de nível de água de um reservatório, executado diretamente no terminal.

O sistema utiliza a biblioteca `colorama` para exibir mensagens coloridas conforme o nível informado, facilitando a visualização da situação atual do reservatório.

## Objetivo

O objetivo do projeto é simular um ambiente de monitoramento em que o operador informa o nível atual do reservatório, e o sistema retorna um relatório com a situação correspondente.

Cada nível possui uma cor específica e uma mensagem de análise, representando diferentes estados do reservatório.

## Tecnologias utilizadas

- Python 3
- Biblioteca `colorama`

## Níveis do reservatório

| Nível | Situação | Cor |
|---|---|---|
| 1 | Muito baixo (crítico) | Vermelho |
| 2 | Baixo | Amarelo |
| 3 | Médio | Verde |
| 4 | Alto | Ciano |
| 5 | Muito alto (alerta) | Azul |

## Funcionalidades

- Solicita ao usuário o nível atual do reservatório.
- Valida se a entrada informada é numérica.
- Verifica se o nível informado está entre 1 e 5.
- Exibe um relatório com a situação do reservatório.
- Aplica cores diferentes para cada nível usando `colorama`.
- Restaura o estilo padrão do terminal com `Style.RESET_ALL`.
- Limpa o terminal automaticamente após alguns segundos.

## Instalação

Antes de executar o projeto, é necessário instalar a biblioteca `colorama`.

No terminal, execute:

```bash
pip install colorama
