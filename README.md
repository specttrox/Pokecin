# Projeto de Programação 1

O PokeCin é um projeto desenvolvido como parte da disciplina de Programação 1 no curso de Sistemas de Informação. Este jogo 2D é fruto do esforço e colaboração dos alunos Alberis Alves da Silva (aas11), Aldo dos Santos Ferreira Lemos (asfl), Arlen Ferreira da Silva Filho (afsf2) e Gustavo Diego (gds4). 

O principal objetivo é aplicar a lógica de programação aprendida durante o curso, proporcionando uma experiência prática e divertida para os jogadores.

---

# PokeCin - Projeto de Jogo em Pygame

## Sumário:

**1. Introdução**
- 1.1 Título do Projeto e Membros da Equipe
- 1.2 Link do Repositório
- 1.3 Organização do Código

**2. Ferramentas, Bibliotecas e Frameworks Utilizados**
- 2.1 Ferramenta 1 (GitHub) - Justificativa
- 2.2 Ferramenta 2 (Notion) - Justificativa
- 2.3 Biblioteca 1 (Pygame) - Justificativa

**3. Divisão de Trabalho**
- 3.1 Alberis Alves da Silva  - Tarefa/Desenvolvimento
- 3.2 Aldo dos Santos Ferreira Lemos - Tarefa/Desenvolvimento
- 3.3 Arlen Ferreira da Silva Filho - Tarefa/Desenvolvimento
- 3.4 Gustavo Diego - Tarefa/Desenvolvimento

**4. Conceitos Aplicados no Projeto**
- 4.1 Classes e Objetos - Aplicação
- 4.2 Funções - Aplicação
- 4.3 Loop - Aplicação

**5. Desafios e Erros**
- 5.1 Maior Erro Cometido - Solução Adotada
- 5.2 Maior Desafio Enfrentado - Solução Adotada
- 5.3 Lições Aprendidas

## 1. Introdução

### 1.1 Título do Projeto e Membros da Equipe

O presente projeto tem como título "PokeCin" — referência ao anime Pokémon e ao Centro de Informática (CIn) da Universidade Federal de Pernambuco. A equipe responsável pela execução do projeto é composta pelos seguintes membros:

- Alberis Alves da Silva (aas11)
- Aldo dos Santos Ferreira Lemos (asfl)
- Arlen Ferreira da Silva Filho (afsf2)
- Gustavo Diego (gds4)

### 1.2 Link do Repositório

O código fonte do projeto encontra-se disponível no [repositório GitHub (PokeCin)](https://github.com/seu-usuario/seu-projeto).

### 1.3 Organização do Código

O código do projeto foi organizado de forma a facilitar a compreensão e manutenção do sistema. A estrutura do código segue os seguintes padrões:

- Pasta "Imagens": Contém todas as imagens que formam o personagem, seus itens, etc.
- Pasta "Sons": Contém todos os efeitos sonoros utilizados no jogo.
- Arquivo "Poke.py": Arquivo python principal do projeto, onde o usuário deve executar o jogo.
- Arquivo "constantes.py": Arquivo python onde são armazenadas informações das constantes utilizadas no jogo (Poke.py), por exemplo, algumas cores como “WHITE = (255, 255, 255)”, etc.
- Arquivo "spritespoke.py": Contém a importação das imagens e sons utilizados no jogo e as classes de cada objeto do jogo (Pikachu, Pokébola, Raio, Estrela) e suas atribuições e métodos.

Essa organização foi adotada para promover a modularização e legibilidade do código, facilitando sua manutenção e futuras implementações.

## 2. Ferramentas, Bibliotecas e Frameworks Utilizados

### 2.1 Ferramenta 1 (GitHub) - Justificativa

A primeira ferramenta utilizada neste projeto é o GitHub. Essa ferramenta foi escolhida devido às suas funcionalidades específicas que contribuem para o desenvolvimento eficiente do projeto. Sua utilização traz os seguintes benefícios:

- Facilidade de colaboração entre os membros da equipe, pois o Git permite que várias pessoas trabalhem ao mesmo tempo no projeto;
- Baixíssimo risco de perda de arquivos, pois ele mantém o projeto salvo em nuvem e atualizado;
- Histórico de versões, o Git possibilita a visualização do histórico de alterações no arquivo, o que permite que restaure ou visualize versões anteriores do projeto.

### 2.2 Ferramenta 2 (Notion) - Justificativa

A segunda ferramenta utilizada neste projeto é o Notion. Essa ferramenta foi selecionada por conta de suas funcionalidades e recursos que são relevantes para a implementação do projeto. A escolha do Notion foi baseada nas seguintes justificativas:

- Nuvem, o Notion mantém um banco de dados em nuvem permitindo que os membros da equipe atualizem as etapas do processo e das organizações com muita facilidade e rapidez;
- Integração com várias ferramentas (como o Google drive, e Slack), facilidade em ferramentas de gerenciamento de projeto;
- Flexibilidade, pois a ferramenta permite uma gama muito ampla de personalização e ajustes que se encaixam melhor em cada tipo de projeto.

### 2.3 Biblioteca 1 (PyGame) - Justificativa

A primeira biblioteca utilizada neste projeto é o Pygame. O Pygame é uma biblioteca amplamente utilizada para o desenvolvimento de jogos em Python. Neste projeto, a escolha do Pygame se deu pelas seguintes justificativas:

- Fácil de aprender, como iniciantes no mundo da programação, decidimos buscar uma plataforma de desenvolvimento que embora não seja tão simples, também não seja muito complicado de iniciantes usarem;
- Código aberto e de graça, o PyGame é de graça e de código aberto, é uma grande vantagem visto que somos estudantes;
- Grande comunidade, o Pygame possui uma comunidade grande e engajada, o que facilita no desenvolvimento.

Essas ferramentas e bibliotecas foram selecionadas com base em critérios específicos para atender às necessidades do projeto e maximizar a eficiência e produtividade da equipe de desenvolvimento.

## 3. Divisão de Trabalho

A divisão de trabalho dentro da equipe foi realizada levando em consideração as habilidades e experiências individuais dos membros. Cada membro ficou responsável por tarefas específicas no desenvolvimento do projeto, conforme detalhado abaixo:

- **3.1 Alberis Alves da Silva** - Tarefa/Desenvolvimento
  - Colaboração na adição e movimentação do item “Pokébola”, movimentação do personagem, adição de efeitos sonoros e organização final do código. Versionamento no GitHub.
  - Pequena colaboração no relatório.

- **3.2 Aldo dos Santos Ferreira Lemos** - Tarefa/Desenvolvimento
  - Colaboração na adição e movimentação do item “Estrela” ao código.
  - Grande colaboração na criação do relatório e slide da apresentação.

- **3.3 Arlen Ferreira da Silva Filho** - Tarefa/Desenvolvimento
  - Colaboração na adição e movimentação do item “Raio” ao código.
  - Grande colaboração na criação do relatório e slide da apresentação.

- **3.4 Gustavo Diego** - Tarefa/Desenvolvimento
  - Colaboração na criação da base do jogo, incluindo tela inicial e tela de game over, adição do personagem e organização final do código. Versionamento no GitHub.
  - Pequena colaboração no relatório.

A divisão de trabalho foi planejada de forma a otimizar a eficiência e a produtividade da equipe, aproveitando as habilidades individuais de cada membro. A comunicação e a colaboração entre os membros foram essenciais para garantir a sincronização e a integração adequada das tarefas realizadas por cada um.

## 4. Conceitos Aplicados no Projeto

No projeto desenvolvido em Pygame com Programação Orientada a Objetos, foram aplicados diversos conceitos fundamentais. Esses conceitos estão relacionados à criação de classes, instanciação de objetos, uso de funções e utilização de loops. A seguir, descrevemos a aplicação desses conceitos no projeto:

### 4.1 Classes e Objetos - Aplicação

A aplicação de classes e objetos no projeto foi essencial para a organização e estruturação do código. Foram criadas classes representando diferentes elementos do jogo, como jogadores, inimigos e objetos interativos. Cada classe possuía atributos e métodos específicos para manipular esses elementos. Por exemplo:

- A classe "Pikachu" possuía métodos para movimentação, colisão e animação do personagem do jogador;
- A classe "Pokeball" tinha métodos para definir a colisão entre o item pokebola e o personagem, visto que o usuário perdia uma vida se encostasse no elemento;
- A classe "Rapidez" contém métodos para manipular interações específicas entre o usuário e o item, como deixar o personagem mais rápido por 5 segundos;
- A classe "Moeda" contém métodos para representar a estrela que, de modo claro, detalhou a contagem de pontos na tela do jogo para o usuário.

Essas classes foram instanciadas no código principal, criando objetos que representavam instâncias específicas desses elementos dentro do jogo.

### 4.2 Funções - Aplicação

No projeto, foram utilizadas funções para realizar tarefas específicas e reutilizáveis. Por exemplo:

- Funções de movimentação: Foram criadas funções para controlar o movimento dos personagens do jogo, permitindo movimentos para a direita e esquerda;
- Funções de colisão: Foram implementadas funções para verificar e lidar com colisões entre os objetos do jogo, como colisões entre o pikachu e os itens (pokebola, estrela e raio).

Essas funções foram chamadas em momentos específicos durante a execução do jogo, contribuindo para o seu funcionamento adequado e para a implementação das regras do jogo.

### 4.3 Loop - Aplicação

A utilização de loops foi crucial para a atualização contínua do jogo e para a criação de uma experiência interativa. O loop principal do jogo, conhecido como "game loop", permitiu que as ações do jogador fossem detectadas e processadas continuamente, mantendo a jogabilidade em tempo real. Dentro desse loop, foram executadas as seguintes etapas:

- O loop principal do jogo é iniciado com o `while tela_inicio`. Ele controla a tela de início do jogo e aguarda a tecla espaço ser pressionada para iniciar o jogo;
- O loop `while inicio` é responsável pelo funcionamento principal do jogo. Ele atualiza a posição dos objetos, verifica colisões, desenha a tela e responde aos eventos do usuário (como teclas pressionadas e eventos de saída);
- O loop `while game_over` é acionado quando o jogador perde todas as vidas. Ele exibe a tela de game over e aguarda o fechamento da janela.

Através da aplicação desses conceitos, o projeto foi estruturado de forma organizada, permitindo a criação de um jogo funcional e interativo. As classes e objetos facilitam a modelagem dos elementos do jogo, as funções proporcionam tarefas reutilizáveis e o loop permitiu a atualização contínua do jogo durante a execução.

## Desafios e Erros

### 5.1 Maior Erro Cometido - Solução Adotada

Durante o desenvolvimento do código, enfrentamos um erro significativo relacionado à falta de tratamento adequado das colisões entre o Pikachu e os objetos do jogo (Pokeballs, raio e estrelas). Isso resultou em comportamentos inconsistentes e imprevisíveis do jogo.

Para solucionar esse problema, implementamos uma lógica aprimorada para detectar colisões corretamente e executar ações específicas para cada tipo de colisão. Agora, quando o Pikachu entra em contato com os objetos do jogo, as ações apropriadas são acionadas, como ajustar a pontuação, as vidas e ativar efeitos especiais. Essa abordagem melhorou a consistência e a jogabilidade do jogo.

### 5.2 Maior Desafio Enfrentado - Solução Adotada

Durante o desenvolvimento do jogo, nos deparamos com um grande desafio: aprender e aplicar os conceitos de Programação Orientada a Objetos (POO) no contexto do Pygame. Para a equipe, a POO era uma abordagem completamente nova, e tivemos que nos familiarizar com ela enquanto trabalhávamos no projeto.

No início, foi desafiador fazer a transição para a POO, pois tivemos que repensar a estrutura do código e dividir a lógica do jogo em partes interconectadas. Compreender os conceitos fundamentais exigiu tempo e esforço de todos os membros da equipe.

Além disso, adaptar esses conceitos ao ambiente do Pygame trouxe uma complexidade extra. Precisamos integrar os elementos visuais, como sprites e animações, com as funcionalidades orientadas a objetos. Isso envolveu a criação de classes para representar o pikachu,, objetos e elementos visuais do jogo, e implementar métodos e atributos adequados para cada um deles.

Para superar esse desafio, dedicamos tempo ao estudo e entendimento dos conceitos de POO. Realizamos pesquisas, revisamos tutoriais e exemplos de código, e trabalhamos juntos para aplicar esses conceitos em nosso projeto. Também utilizamos recursos da comunidade do Pygame, como fóruns e documentação oficial, para obter orientações e resolver dúvidas específicas.

Com o tempo, à medida que ganhamos mais experiência e confiança, a implementação da POO no Pygame se tornou mais fluida. Adaptamos nossas práticas de desenvolvimento para dividir o código em módulos, manter uma boa organização e conexão entre as partes do jogo, e promover a reutilização de código sempre que possível.

No final, conseguimos superar o desafio de aprender e aplicar a POO no Pygame. Essa experiência não apenas aprimorou nosso entendimento de programação orientada a objetos, mas também nos deu uma base sólida para projetos futuros, onde podemos combinar a POO e o Pygame para criar jogos mais complexos e sofisticados.

### 5.3 Lições Aprendidas

Durante o desenvolvimento do jogo, aprendemos lições valiosas que contribuíram para o aprimoramento da nossa equipe. Destacamos as seguintes lições:

- **Planejamento Adequado:** Um planejamento detalhado e realista antes da implementação evitou retrabalhos e facilitou o alcance das metas.
  
- **Comunicação Assertiva:** A comunicação clara e regular entre a equipe promoveu o alinhamento de objetivos e a colaboração eficiente.

- **Organização do Código:** Uma estrutura organizada e nomeação adequada de variáveis e funções facilitaram a manutenção e compreensão do código.

- **Tratamento de Colisões:** Lidar adequadamente com colisões entre personagens e objetos foi essencial para garantir uma jogabilidade correta.

Essas lições nos forneceram uma base sólida para projetos futuros e nos tornaram mais preparados para enfrentar desafios similares no desenvolvimento de jogos.
