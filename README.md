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
