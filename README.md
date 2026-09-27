# Sistema de Gamers - Módulo 2

Projeto de terminal desenvolvido em JavaScript para gerenciar uma equipe de
gamers. O usuário interage com o sistema por um menu e informa os dados pelo
teclado.

## Estrutura do projeto

```text
CursoJS-Modulo02/
├── sistema-de-gamers.js  # Menu e operações da equipe
├── package.json          # Dependência do projeto
├── package-lock.json     # Versões instaladas das dependências
└── .gitignore            # Arquivos e pastas ignorados pelo Git
```

## Recursos

- Cadastrar jogadores com nome, função e pontuação inicial.
- Remover um jogador pelo nome.
- Exibir os jogadores cadastrados e seus dados.
- Calcular a pontuação média da equipe.
- Acrescentar pontos à pontuação de um jogador.
- Validar pontuações e informar quando a equipe está vazia ou um jogador não
  foi encontrado.

Os dados ficam na memória do programa e não são preservados ao encerrá-lo.

## Como executar

É necessário ter o Node.js e o npm instalados. Na pasta do projeto, instale a
dependência e inicie o programa:

```bash
npm install
node sistema-de-gamers.js
```

Siga as opções exibidas no menu para utilizar o sistema. A opção **6 - Sair**
encerra a execução.