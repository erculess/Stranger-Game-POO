#  Propostas de Projeto

## 1.Campus of Chaos

## 2. Descrição Geral

O jogo é um título de luta em formato arcade, fortemente inspirado nas clássicas mecânicas de combate 2D de Mortal Kombat, focando em confrontos diretos, combos e no uso de habilidades especiais únicas. A ambientação ocorre exclusivamente no ginásio do campus do IFRN, utilizando a quadra esportiva como a arena de embate, com limites laterais bem definidos que restringem a movimentação dos personagens. Para trazer mais vida e imersão ao cenário, as arquibancadas ao redor da quadra são preenchidas por alunos da instituição, que assistem e reagem às lutas. A ideia principal do projeto é promover um torneio imaginário e bem-humorado onde os próprios professores do campus são os lutadores. Cada docente possui um estilo de combate e um visual autoral que faz referência direta à disciplina que leciona, transformando conceitos de sociologia, linguagens, exatas e tecnologia da informação em ataques e poderes especiais, criando assim uma experiência de jogo divertida e altamente identificável para a comunidade escolar.

## 3. Objetivo do Jogo

O objetivo principal do jogo é vencer os confrontos diretos contra os professores adversários na arena do ginásio. Para alcançar a vitória, o jogador precisa dominar o conjunto de movimentos do seu personagem escolhido, utilizando ataques básicos, combos e habilidades especiais temáticas de cada disciplina, para reduzir a barra de vida (HP) do oponente a zero. Como não há coleta de itens, exploração de mapas ou sistema de recompensas, a meta central foca inteiramente na habilidade de combate e na sobrevivência. O jogador deve superar o oponente no formato tradicional de luta arcade, vencendo a maioria dos rounds (como em uma disputa de melhor de três) para vencer a partida e provar a supremacia da sua disciplina no campus.

## 4. Personagens Principais

Por se tratar de um jogo de luta estilo Mortal Kombat, não existe um único "personagem principal" no formato clássico de jogos de aventura. O jogador terá à disposição uma tela de seleção de personagens composta por 12 lutadores, todos eles professores do campus do IFRN. O jogador escolhe um deles para representá-lo a cada partida.

​Quem são os personagens?:

* ​Diego (Sociologia): Baseado em Ermac, representa a consciência coletiva, utilizando ataques que simulam a força da sociedade agindo como uma só.
* ​Felipe (Português): Baseado em Shang Tsung, um lutador eloquente e estratégico, cujos poderes derivam do domínio da linguagem, argumentação e comunicação.
* ​Joaildo (Matemática): Baseado em Geras, calculista e exato. Seus golpes manipulam o tempo, o espaço e a lógica absoluta através de fórmulas.
* ​Mirelly (Inglês): Baseada em Kitana, possui movimentos rápidos e elegantes. Utiliza livros, bandeiras ou certificados internacionais de forma letal (como os leques da Kitana).
* ​Rickson (Educação Física): Baseado em Jax Briggs, é o lutador de combate corpo a corpo mais robusto, focando em força física bruta, resistência e imobilizações.
* ​Ricardo (Artes): Baseado em Rain, possui movimentos visualmente extravagantes, utilizando tintas, pinceladas e explosões de cores como projéteis.
* ​Avelino (Geografia): Baseado em Tremor, utiliza ataques ligados ao relevo e tectonismo, controlando rochas e causando terremotos na arena.
* ​Saulo (Química): Baseado em Reptile, ataca utilizando reações químicas perigosas, ácidos e substâncias corrosivas em combate.
* ​Hugo (Banco de Dados): Baseado em Cyrax, um lutador metódico que planta armadilhas no cenário (backups) e utiliza mecanismos automatizados (consultas SQL) para atacar.
* ​Max (POO): Baseado em Triborg, é a personificação da herança e do polimorfismo, reunindo múltiplos estilos de luta em um só personagem.
* ​Anderson (Redes): Baseado em Sektor, foca em tecnologia e comunicação remota, disparando ataques guiados (como pacotes de dados) pelo cenário.
* ​Thales (APOO): Baseado em Quan Chi, atua como um estrategista sombrio que arquiteta estruturas complexas, armadilhas e invocações (modelagem de sistemas) durante a luta.

​Como eles se movimentam:

A movimentação ocorre em um plano 2D (eixos X e Y restritos) com os personagens sempre virados um para o outro.

Os movimentos básicos incluem:
- ​Andar para frente e recuar (esquerda/direita).
- ​Pular (reto, para frente ou para trás) para ataques aéreos ou esquivas.
- ​Agachar para se defender de golpes altos ou desferir golpes baixos.
- ​Dash (avanço ou recuo rápido) para encurtar ou criar distância rapidamente.

​Quais atributos possuem:
- ​Barra de Vida (HP): Atributo principal e igual para todos no início do round (ex: 100%). Representa a resistência do professor. O esgotamento da barra resulta em derrota (nocaute).
- ​Velocidade e Força: Estes atributos variam para equilibrar o jogo. Professores como Rickson terão mais força e menos velocidade, enquanto Mirelly terá maior velocidade com golpes de menor impacto isolado.
- ​Barra de Especial (Estamina/Cooldown): Uma barra que enche conforme o professor ataca ou defende, permitindo que ele execute seus golpes especiais ou combos devastadores temáticos.
​Nota: Conforme definido na proposta, não há atributos de pontuação (score), coleta de itens, moedas ou experiência. O foco é estritamente o combate.

## 5. Inimigos e Obstáculos

Por seguir a estrutura clássica de jogos de luta como Mortal Kombat, o conceito tradicional de "inimigos" espalhados por uma fase não se aplica. O principal e único inimigo em cada partida é o professor adversário, que pode ser controlado por um segundo jogador em uma disputa local ou pela própria Inteligência Artificial (IA) do jogo. Quando controlado pela máquina, o oponente terá um comportamento focado no combate direto, programado para se aproximar, defender-se de investidas e utilizar seu arsenal de golpes temáticos de forma estratégica para tentar zerar a barra de vida do jogador. A colisão com os ataques desse adversário resulta em perda progressiva de HP e em reações de impacto, como recuo ou interrupção de movimento.

​Quanto aos obstáculos, o ambiente foi pensado para manter o foco na fluidez da luta, sendo o cenário do ginásio totalmente limpo, sem elementos no meio do caminho para atrapalhar os golpes. Os únicos obstáculos reais são os próprios limites laterais da quadra esportiva, que funcionam como barreiras invisíveis nas extremidades da tela. Ao colidir ou ser empurrado contra esses limites, o personagem não sofre dano de ambiente, mas sua movimentação é interrompida. Isso cria o clássico efeito de encurralamento dos jogos de luta, onde o jogador ou o inimigo perdem espaço de recuo, ficando em desvantagem e muito mais vulneráveis a combos agressivos.

## 6. Cenário (Mapa)

​O jogo se desenrola em um ambiente único e contínuo: a quadra do ginásio do campus do IFRN, que funciona como a arena principal e exclusiva para os combates 2D. O mapa é construído em perspectiva lateral, típica dos jogos de luta, onde o piso da quadra representa a zona segura e a única área de movimentação permitida para os professores. Não existem caminhos alternativos, plataformas ou labirintos; o design é focado no confronto direto. As extremidades laterais da tela funcionam como paredes invisíveis, delimitando o espaço de luta e impedindo que os personagens fujam da zona de conflito. O grande destaque visual do cenário fica ao fundo, nas arquibancadas do ginásio, que estarão repletas de alunos assistindo às disputas, compondo a atmosfera e trazendo imersão escolar ao torneio. Fiel à proposta de focar apenas nas mecânicas do Mortal Kombat, o mapa não possui itens coletáveis, baús ou áreas secretas. O objetivo final de cada cenário se resolve ali mesmo, no centro da quadra, finalizando quando um dos lutadores é nocauteado.

## 7. Sistema de Vida

Seguindo a lógica dos tradicionais jogos de luta, o sistema de vida do projeto não utiliza o conceito de "vidas extras" de jogos de plataforma, mas sim uma barra de energia (HP) individual para cada combate. Cada professor inicia o round com sua barra de vida superior completamente cheia, representando 100% de sua aptidão física e foco para a luta. Durante o embate, o jogador perde vida progressivamente sempre que não consegue se defender e é atingido por ataques básicos, combos ou pelas habilidades especiais temáticas do adversário. Quando essa barra é totalmente esgotada, o personagem sofre um nocaute e perde aquele round. Como as partidas são estruturadas em um formato de "melhor de três", o jogador precisa esgotar a barra do oponente duas vezes para sair vitorioso da partida. Caso o próprio jogador tenha sua barra de vida zerada em dois rounds distintos, a luta se encerra em derrota, exigindo que ele recomece a disputa ou retorne à tela de seleção de professores para tentar uma nova estratégia.

## 8. Controles

Para garantir precisão e fluidez durante as lutas, os comandos foram desenhados para o teclado e divididos em três categorias principais de ação: movimentação, combate e sistema.

​A movimentação do personagem pela quadra do ginásio é controlada pelas teclas direcionais clássicas. A tecla 'W' executa o pulo (que pode ser reto ou diagonal, se combinada com as teclas laterais); o 'S' faz o professor agachar, permitindo esquivar de golpes altos ou preparar um ataque rasteiro; o 'A' movimenta o lutador para a esquerda e o 'D' para a direita. Para adicionar mais dinamismo ao posicionamento, pressionar 'A' ou 'D' duas vezes rapidamente executará um Dash (um avanço ou recuo ágil para encurtar ou criar distância do oponente).

​O combate e a defesa ficam mapeados de forma acessível para a mão direita. A barra de 'Espaço' aciona a guarda (bloqueio), uma mecânica essencial para mitigar o dano recebido. A ofensa é dividida em quatro botões distintos para permitir a criação de combos variados: o 'J' aplica um soco rápido/fraco, o 'K' desfere um soco forte/pesado, o 'U' executa um chute rápido/fraco e o 'I' dispara um chute forte. As habilidades especiais temáticas de cada disciplina não possuem um botão único; elas são conjuradas ao realizar uma combinação rápida de movimento seguida de ataque (por exemplo: sequenciar 'S', 'D' e pressionar 'J', simulando o clássico "baixo, frente e soco").

​Por fim, os controles de sistema gerenciam o fluxo da aplicação. A tecla 'Enter' é utilizada para confirmar as opções nos menus e selecionar o seu lutador na tela inicial. Já a tecla 'ESC' serve para pausar a luta a qualquer momento, congelando a ação na tela e abrindo um menu com opções para retomar o combate, voltar à seleção de professores ou fechar o jogo.

## 9. Fluxo do Jogo

A experiência tem início assim que o jogo é executado, apresentando um menu principal que leva diretamente à tela de seleção de lutadores. Neste momento, todos os doze professores do campus já estarão previamente desbloqueados e disponíveis para escolha. Após o jogador selecionar o seu representante e o adversário ser definido, a tela transiciona para a arena do ginásio, com os lutadores posicionados de frente um para o outro e os alunos na arquibancada reagindo ao início do embate. O confronto é estruturado no formato clássico de "melhor de três". Assim que o comando de início é dado, a partida se desenrola de forma dinâmica, com ambos os lados trocando golpes físicos, defendendo-se e utilizando suas habilidades temáticas para tentar esgotar a barra de energia do oponente.

​A condição de vitória de cada round é alcançada assim que a barra de vida (HP) de um dos lutadores chega a zero, resultando em um nocaute. 
Para que o jogador consiga a vitória definitiva da partida, é necessário que ele vença dois rounds completos. Caso obtenha sucesso, uma tela de vitória celebrará o professor vencedor, permitindo que o jogador retorne ao menu para iniciar um novo combate com personagens diferentes. Por outro lado, se a barra de vida do jogador for zerada em dois rounds pelo oponente, a condição de derrota é acionada, exibindo uma tela de encerramento que oferece a opção de tentar uma revanche imediata ou voltar à tela de seleção de personagens para repensar a sua estratégia.

## 10. Regras do Jogo

As regras fundamentais do torneio no ginásio foram estabelecidas para garantir o equilíbrio e o funcionamento técnico das lutas, mantendo o foco na habilidade de combate. A interação primária do jogo é governada pelo sistema de colisão (hitboxes e hurtboxes), onde o dano só é validado e descontado da barra de vida se a área de alcance do golpe de um professor atingir diretamente o corpo do adversário enquanto este estiver desprotegido. Caso o oponente esteja acionando o comando de guarda, o golpe não o derrubará e o dano será drasticamente reduzido, servindo apenas para causar um leve desgaste.

​Em termos de movimentação e restrições espaciais, os lutadores não podem atravessar o corpo um do outro simplesmente andando na mesma direção; a única maneira de cruzar o cenário e trocar de lado com o oponente é realizando um pulo por cima dele. Além disso, os limites laterais da quadra do ginásio funcionam como barreiras sólidas. É expressamente proibido ultrapassar as extremidades da tela, e qualquer personagem que for empurrado até esses limites ficará encurralado, perdendo a capacidade de recuar e precisando lutar para recuperar espaço. Como a proposta dispensa mecânicas de aventura, não existem regras para coleta de itens, power-ups ou interações físicas com os alunos que assistem na arquibancada. Toda a lógica do jogo exige que os limites da arena sejam respeitados e que a vitória seja definida puramente pela superioridade na troca de golpes.
