# Chatbot de D&D

Este projeto implementa um chatbot interativo destinado a mestres e jogadores de Dungeons & Dragons (D&D). O chatbot facilita várias funcionalidades comuns em sessões de D&D, como rolagem de dados, criação de personagens e geração de narrativas envolventes.

## Funcionalidades

### Rolagem de Dados
- **Comando Básico**: Os usuários podem rolar dados especificando o tipo e a quantidade (por exemplo, `1d20`, `3d6`).
- **Resultado Detalhado**: O chatbot mostra o resultado de cada dado rolado e o total, proporcionando uma visão completa da rolagem.
- **Padrão**: Se nenhum dado for especificado, o chatbot assume uma rolagem padrão de `1d20`.

### Criação de Personagens
- **Inicialização**: Os usuários podem criar uma ficha de personagem, com pontos de atributos distribuídos conforme especificado.
- **Distribuição de Pontos**: A distribuição de pontos segue regras específicas, como limites para atributos máximos.

### Geração de Histórias
- **Descrições Envoltas em Mistério e Aventura**: O chatbot pode gerar narrativas detalhadas baseadas em prompts fornecidos pelo usuário, enriquecendo a experiência do jogo.

## Tecnologias Utilizadas
- Python: Lógica principal do chatbot.
- OpenAI API: Para a geração de narrativas e descrições.
- Bibliotecas Python como `random` para rolagem de dados.

## Como Usar
1. **Iniciar o Chatbot**: Execute o script principal User Interface.
2. **Interagir**: Siga os prompts no terminal para interagir com o chatbot.
3. **Sair**: Digite 'sair' para terminar a sessão do chatbot.

## Exemplo de Uso
```bash
Digite algo: rolar 2d6
Resultado da rolagem: 3, 5 (Total: 8) com 2d6
