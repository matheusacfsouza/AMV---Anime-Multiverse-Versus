# PERSONAGENS AMV / AMV CHARACTERS

> Uma seção por personagem. As regras de estilo (traço, cor, mãos, composição) ficam em `Artes\Guia_de_Estilo_AMV.md`.
> One section per character. Style rules (line, color, hands, composition) live in `Artes\Guia_de_Estilo_AMV.md`.
>
> **Como usar num prompt / How to use in a prompt:** cole o BLOCO-MESTRE do guia + a seção do personagem + o prompt base dele. / paste the guide's MASTER BLOCK + the character's section + its base prompt.

## PROTOCOLO DE NOVO PERSONAGEM / NEW CHARACTER PROTOCOL

**Sempre que o usuário disser que quer criar um novo "personagem", perguntar, nesta ordem:**
1. **Dados da carta:** Nome, Grupo (vai ao lado do nome da carta, depois do "-"), Tipo, Arquétipo, Habilidade, Raridade.
2. **Papel:** herói, vilão, aliado, mentor, criatura? Qual a função dele nas cartas?
3. **Poder ou tema:** o que ele faz e qual o elemento visual do poder.
4. **Aparência:** gênero, idade aparente, tipo físico, cabelo, cor de pele, marcas.
4b. **Corpo acentuado (anamorfose, estilo principal do guia, seção 1.0):** o personagem deve ter uma parte do corpo mais acentuada que as outras? Opções clicáveis: Mãos/punhos, Braços/antebraços, Ombros e tronco, Cabeça, Pernas/pés, Arma ou objeto, Nenhuma. Se escolher uma, perguntar também a intensidade: leve, forte ou extrema.
5. **Paleta de cores (regra 60-30-10):** cor primária (60% da imagem, a dominante, geralmente neutra ou calma), cor secundária (30%, apoio: figurino, fundo, contraste) e cor terciária ou de acento (10%, a mais forte e saturada, para o ponto focal e o poder). O tom do fundo NÃO se pergunta: vem do Tipo do personagem (tabela em `Fundos\Fundos_AMV.md`, seção 0). A cor terciária é a cor de acento que distingue o personagem dos outros.
6. **Personalidade e expressão:** calmo, feroz, brincalhão, cruel etc.
7. **Universo:** gênero do universo do AMV (ainda a definir; NÃO é dark fantasy).

**Formato das perguntas:** o usuário quer escrever o mínimo. Usar perguntas com ITENS CLICÁVEIS (AskUserQuestion) para tudo o que tiver opções comuns (espécie, cor do cabelo, arma, personalidade, papel, cor de acento, universo etc.), e deixar texto livre só para o que for único (Nome, Grupo, Habilidade). Gerar as opções sugeridas pelo Claude, a partir do que já foi escolhido. Raridade, Tipo, Arquétipo e Grupo: usar as listas do jogo assim que o usuário as informar (guardar abaixo).

**Listas do jogo (preencher / fill in):**
- Tipos: Raio (outros: a definir)
- Arquétipos: Emissor, Mestre (outros: a definir)
- Raridades: 1 (outras: a definir)
- Grupos: Velha guarda (outros: a definir)

**Estilo de desenho:** o estilo principal é o da seção 1.0 do guia (gráfico-novela com anatomia acentuada). Montar o prompt na estrutura descrita lá, usando a parte acentuada escolhida na pergunta 4b.

**Depois das respostas:** criar a seção do personagem neste arquivo (PT-BR, EN, prompt base com a Regra de Mãos do guia), adicionar a linha no índice e gerar a arte.

---

## PROTOCOLO DE EDITAR PERSONAGEM / EDIT CHARACTER PROTOCOL

**Quando usar:** o usuário diz "editar personagem" ou envia uma imagem de um personagem (dele ou de referência) e quer mudar algo nela. O objetivo é transformar a imagem em um personagem do AMV: mudar o que ele pedir, manter o que ele pedir, e aplicar o nosso estilo principal (guia, seção 1.0).

**Passos, nesta ordem:**
1. **Ler a imagem e confirmar (curto, em PT-BR):** descrever em poucas linhas o que vejo (espécie, idade aparente, pose e ângulo, roupas, objeto, mãos e dedos, paleta, fundo, estilo de desenho). Se for um personagem que já existe aqui, abrir a ficha e a arte final dele antes.
2. **Perguntar o que MUDAR e o que MANTER** (AskUserQuestion, clicável, seleção múltipla). Categorias: Aparência (rosto, cabelo, pele, idade, corpo), Posicionamento (pose, ângulo de câmera, enquadramento, direção do olhar), Roupas e acessórios, Arma ou objeto, Expressão, Cores e paleta 60-30-10, Poder e efeitos, Fundo (a cor vem do Tipo). Para cada categoria marcada para mudar, fazer uma pergunta clicável de como mudar, com opções sugeridas por mim; texto livre só para detalhes únicos. O que não for marcado fica MANTIDO.
3. **Dados da carta, se for virar carta:** Nome, Grupo, Tipo (define o fundo), Arquétipo, Habilidade, Raridade. Se for só um estudo, pular.
4. **Corpo acentuado (4b):** perguntar a parte do corpo acentuada e a intensidade (leve, forte, extrema) ou Nenhuma.
5. **Montar o prompt em inglês** com esta estrutura: `Use the attached image as the base.` → `KEEP EXACTLY:` (lista do que foi mantido, descrito com precisão) → `CHANGE:` (lista do que muda, descrita com precisão) → `DRAWING STYLE:` (bloco da seção 1.0 do guia, com a parte acentuada escolhida) → `BACKGROUND:` (regra do Tipo, degradê, esfumaçado e linhas de zoom) → fecho (cinco dedos por mão com Regra de Mãos, cores vibrantes mas não estouradas, poderes não tingem pele, quadrado 1:1, sem moldura, texto ou logotipo).
6. **Gemini:** o usuário anexa a imagem (a janela de arquivos só ele escolhe; eu abro o botão "+" e "Arquivos"). Preferir UM pedido com tudo. Se o Gemini perder detalhe ou ignorar partes, fazer em duas etapas (1º mudar o conteúdo, 2º aplicar o estilo) ou começar uma conversa nova com o prompt completo. Quando o Gemini simplificar o personagem, anexar de novo a arte original com mais detalhe como base.
7. **Conferir:** pedir ao usuário um zoom nas mãos e no rosto (as capturas são pequenas e não dá para contar dedos). Corrigir só a parte errada.
8. **Gravar:** se for personagem novo, criar a seção e a linha no índice como no protocolo de novo personagem. Se for personagem existente, atualizar a ficha e anotar a versão nova.

**Regras fixas que continuam valendo na edição:** cinco dedos por mão, olhos, nariz, boca e orelhas (salvo indicação); cores vibrantes, não estouradas; poderes não tingem pele, cabelo nem roupa; arte quadrada 1:1; sem moldura, texto, logotipo; universo "mistura de gêneros", nunca "dark fantasy"; só cartas de personagem têm fundo sem cenário.

---

## ÍNDICE / INDEX

| # | Nome / Name | Papel / Role | Cor de acento / Accent | Arte de referência / Reference art |
|---|---|---|---|---|
| 01 | Sabrina | Vilã, marionetista / Villain, puppeteer | Carmesim + turquesa / Crimson + turquoise | `Sabrina.jpg` |
| 02 | Zé do Trovão - Velha guarda | Mentor, comandante / Mentor, commander | Azul elétrico / Electric blue | (a gerar / to generate) |

---

## 01. SABRINA

**Arte final de referência / Final reference art:** `Artes\Personagens\Sabrina.jpg`

### PT-BR

- **Papel:** vilã. Controla marionetes com fios gerados pela energia da própria alma.
- **Cabelo:** carmesim (vermelho profundo, cor de sangue), NÃO ruivo alaranjado. Corte shag/wolf cut repicado, repartido ao meio, franja cortina solta, pontas leves e irregulares, comprimento até os ombros, volume baixo a médio no topo e nas laterais. Cobre parcialmente as orelhas (as orelhas não precisam aparecer).
- **Rosto:** pele pálida de porcelana, olhos totalmente pretos como de uma boneca (contas de vidro brilhantes, sem íris nem pupila, com um pequeno brilho branco), sobrancelhas anguladas, sorriso largo e maligno com dentes à mostra.
- **Costuras (sutis):** fio vermelho escuro fino e pontos pequenos, de baixo contraste. Uma costura vertical desce pelo eixo central do rosto, alinhada com a ponta do nariz, cruza a boca e vai ao queixo. Pontinhos em X nos cantos da boca e um pequeno detalhe na testa. Nada grosso nem escrachado.
- **Costuras no corpo:** as articulações dos braços (cotovelos e pulsos) têm costuras finas e discretas, como numa boneca de pano.
- **Figurino:** vestido negro sem mangas, liso e inteiro, com gola alta justa ao pescoço. Sem rasgos, sem tecido rasgado.
- **Mãos (aprovadas):** abertas e levantadas na altura da cabeça, dos dois lados, com os dedos pendendo como numa cruz de marionete. Cinco dedos em cada mão, polegar no lado interno, mindinho no lado externo. Um fio turquesa sai de cada ponta de dedo, sem cobrir as mãos.
- **Poder:** fios finos turquesa-pálidos e luminosos de energia da alma, que iluminam as mãos e o rosto por baixo.
- **Marionetes:** de madeira, totalmente sem rosto (cabeça lisa, sem olhos, nariz ou boca), só rachaduras e articulações. Algumas grandes e desfocadas em primeiro plano.
- **Composição da arte final:** close médio da cintura para cima, cabeça inclinada na diagonal, câmera levemente baixa, perspectiva forçada. Fundo cinza vibrante e saturado, desfocado, com linhas de velocidade radiais e fragmentos voando. Sem moldura.
- **Cores saturadas:** só o carmesim do cabelo e o turquesa dos fios.
- **Pose alternativa (se precisar):** punhos semiabertos segurando feixes de fios como rédeas, polegar visível no lado interno.

### EN

- **Role:** villain. Controls puppets with threads made from her own soul energy.
- **Hair:** crimson (deep blood red), NOT orange-red. Shaggy wolf cut with choppy layers, parted in the middle, loose curtain bangs, wispy uneven tips, shoulder length, low-to-medium volume on top and sides. Partly covers the ears (ears do not need to be visible).
- **Face:** pale porcelain skin, fully black doll eyes (glossy glass beads, no iris or pupil, one small white highlight), angled brows, wide wicked grin showing teeth.
- **Stitches (subtle):** fine dark-red thread, small, low-contrast stitches. One vertical seam runs down the central axis of the face, aligned with the tip of the nose, across the mouth to the chin. Tiny X stitches at the mouth corners and a small detail on the forehead. Nothing thick or crude.
- **Body stitches:** arm joints (elbows and wrists) have fine, discreet stitches, like a rag doll.
- **Costume:** sleeveless black dress, smooth and intact, with a snug high neckline. No tears, no ripped fabric.
- **Hands (approved):** open and raised to head height on both sides, fingers hanging like a marionette control. Five fingers on each hand, thumb on the inner side, little finger on the outer side. One turquoise thread falls from each fingertip without covering the hands.
- **Power:** thin, pale-turquoise glowing soul-energy threads that light the hands and the face from below.
- **Puppets:** wooden, completely faceless (smooth head, no eyes, nose or mouth), only cracks and joints. Some large and blurred in the foreground.
- **Final art composition:** medium waist-up shot, head tilted on a diagonal, slightly low camera, forced perspective. Vibrant, saturated blurred grey background with radial speed lines and flying debris. No frame.
- **Saturated colors:** only the crimson hair and the turquoise threads.
- **Alternate pose (if needed):** semi-open fists holding bundles of threads like reins, thumb visible on the inner side.

### Prompt base (Gemini / ChatGPT) / Base prompt

```
Create an image: a villain puppeteer for a card game, in a manga-cover style with Western comic finish. A slender woman with a crimson-red shaggy wolf cut (blood red, no orange): choppy layers, parted in the middle, loose curtain bangs, wispy uneven tips, shoulder length, low-to-medium volume, hair partly covering her ears. Solid glossy black doll eyes with one small white highlight and no iris or pupil, pale porcelain skin, angled brows, a wide wicked grin showing teeth. Subtle, delicate stitches in fine dark-red thread: one vertical seam down the exact center of the face through the tip of the nose, across the mouth to the chin, tiny X stitches at the corners of the mouth, a small stitch detail on the forehead; fine discreet stitches on both elbows and wrists like a rag doll. Sleeveless smooth black dress with a snug high neckline, intact, no tears. Waist-up shot, head tilted on a diagonal, slightly low camera angle, forced perspective. Both arms bent and raised on both sides of her head, both hands open with the back of the hand toward the camera, the wrist bent so the fingers hang downward like a puppeteer holding a marionette: four long fingers dangling with slightly bent knuckles and one thumb clearly visible on the inner side of the hand, five digits per hand, all separate. A thin glowing pale-turquoise thread falls from each fingertip to the puppets without covering the hands. Wooden puppets hanging from the threads are completely faceless (smooth blank heads, only cracks and joints), a few large and motion-blurred in the foreground. Tapered black ink outline, short hatching, digital cel shading with three tones per color and soft gradients. Teal light from the threads lights her face from below. Saturated character against a vibrant, saturated blurred grey background with radial speed lines and flying debris. Only the crimson hair and the turquoise threads are saturated. Anatomically correct hands with exactly five fingers each, two eyes, a nose, a mouth. Full bleed artwork, no frame, no border, no card corners, no text, no logo, no watermark. Square format, 1:1 aspect ratio.
```

---

## 02. ZÉ DO TROVÃO - VELHA GUARDA

**Dados da carta / Card data**
- **Nome:** Zé do Trovão
- **Grupo:** Velha guarda
- **Tipo:** Raio
- **Arquétipo:** Emissor - Mestre
- **Raridade:** 1
- **ATQ:** 1600
- **Habilidade:** Intimidador. Diminui o ATQ dos personagens do oponente em 200.

**Arte final de referência / Final reference art:** (a gerar / to generate)

### PT-BR

- **Paleta 60-30-10:** primária 60% bordô escuro (casaco e corpo do uniforme); secundária 30% dourado fosco (medalhas, botões, galões, ombreiras, detalhes); terciária/acento 10% azul elétrico (aura, faíscas, ponta do cajado, olhos). Fundo: bege envelhecido, desfocado.
- **Papel:** mentor e comandante, linha dura e determinado. Intimida os adversários com autoridade, não com crueldade.
- **Espécie:** meio humano, meio elfo (orelhas longas e pontudas bem visíveis).
- **Aparência:** homem de mais de 55 anos, cerca de 1,70 m, gordinho e robusto (barriga, ombros largos, pescoço grosso). Pele pálida com rugas fundas da idade. Calvo, sem cabelo no topo, com barba branca comprida e sobrancelhas brancas espessas.
- **Rosto e expressão:** severo, olhar duro e fixo, sobrancelhas franzidas em V, boca firme. Expressão de quem dá uma ordem e não aceita contestação.
- **Figurino:** uniforme militar antigo, em bordô escuro (60%) com detalhes em dourado fosco (30%), casaco abotoado de gola alta que cobre o cinto (o cinto fica por baixo do casaco, escondido), camisa para dentro da calça, ombreiras, medalhas e galões dourados gastos. Sem rasgos.
- **Arma:** cajado de comando, robusto, de madeira escura com ponta de metal.
- **Poder:** raios e eletricidade. Aparece como uma aura azul elétrica fina e discreta em volta da silhueta, mais forte perto do cajado e da mão que dá a ordem, com poucas faíscas pequenas.
- **Cor de acento:** azul elétrico (aura, ponta do cajado, olhos com um leve brilho). O resto fica neutro.
- **Pose da arte:** dando uma ordem. Um braço estendido apontando para a câmera, o outro apoiando o cajado no chão. Câmera baixa, perspectiva forçada, corpo da cintura para cima ou três quartos.
- **Mãos:** a mão que aponta tem o indicador estendido, médio, anelar e mindinho dobrados na palma e o polegar apoiado sobre o dedo médio, cinco dedos visíveis. A mão do cajado aperta o cabo, com quatro dedos em volta, juntas visíveis e o polegar por cima, cinco dedos visíveis.
- **Fundo:** bege envelhecido vibrante e saturado, desfocado, com linhas de velocidade radiais, sem moldura.

### EN

- **Role:** mentor and commander, hard-line and determined. Intimidates opponents with authority, not cruelty.
- **Species:** half human, half elf (long, pointed ears clearly visible).
- **Appearance:** man over 55, about 1.70 m, chubby and sturdy (belly, broad shoulders, thick neck). Pale skin with deep age wrinkles. Bald with no hair on top, long white beard and thick white eyebrows.
- **Face and expression:** stern, hard fixed gaze, V-shaped furrowed brows, firm mouth. The look of someone giving an order who accepts no argument.
- **Costume:** old military uniform in deep dark burgundy (60%) with bright saturated gold details (30%), buttoned high-collar coat covering the belt (the belt is worn under the coat, hidden), shirt tucked into the trousers, shoulder guards, worn gold medals and braids. No tears.
- **Weapon:** command staff, sturdy, dark wood with a metal tip.
- **Power:** lightning and electricity. Shown as a thin, discreet electric-blue aura outline around the silhouette, stronger near the staff and the ordering hand, with a few small sparks.
- **Accent color:** electric blue (aura, staff tip, a faint glow in the eyes). Everything else stays neutral.
- **Art pose:** giving an order. One arm extended pointing at the camera, the other resting the staff on the ground. Low camera, forced perspective, waist-up or three-quarter body.
- **Hands:** the pointing hand has the index finger extended, middle, ring and little finger curled into the palm and the thumb resting over the middle finger, five fingers visible. The staff hand grips the shaft, four fingers wrapped around it, knuckles visible and thumb on top, five fingers visible.
- **Background:** vibrant, saturated blurred aged beige with radial speed lines, no frame.

### Prompt base (Gemini / ChatGPT) / Base prompt

```
Create an image: a mentor and commander character for a card game, in a manga-cover style with Western comic finish. A half-human, half-elf elderly man, over 55, about 1.70 m tall, chubby and sturdy with a round belly, broad shoulders and a thick neck. Pale skin with deep age wrinkles. He is bald with no hair on top of his head, a long white beard and thick white eyebrows. Long, pointed elf ears clearly visible. Stern, hard, fixed gaze under furrowed V-shaped brows, firm mouth, the expression of a hard-line commander giving an order. He wears an old military uniform in deep dark burgundy (about 60% of the image) with bright saturated gold details (about 30%): a buttoned high-collar coat that hangs over and covers the belt (the belt is worn under the coat and not visible), the shirt tucked into the trousers, shoulder guards, worn gold medals, buttons and braids, intact with no tears. Medium shot from the waist up, slightly low camera angle with forced perspective. One arm is extended toward the camera pointing: the index finger extended, the middle, ring and little finger curled into the palm and the thumb resting over the middle finger, five fingers clearly visible. The other hand grips a sturdy dark-wood command staff with a metal tip planted on the ground: four fingers wrapped around the shaft with knuckles visible and the thumb on top, five fingers clearly visible. A bright, exuberant electric-blue and white aura glows around his silhouette, with crackling lightning bolts arcing from the staff and the pointing hand, many sparks, and glowing blue eyes; the electricity never tints his skin, beard or clothes, which keep their own colors (pale skin, white beard, burgundy coat). Vibrant saturated colors only. Color palette 60-30-10: dark burgundy 60%, bright saturated gold 30%, electric blue 10% only in the aura, sparks, staff tip and eyes. Tapered black ink outline, thick on the silhouette and thin on details, short hatching, digital cel shading with three tones per color and soft gradients. Vibrant, saturated, blurred aged-beige background with radial speed lines. Anatomically correct hands with exactly five fingers each, two eyes, a nose, a mouth and two ears. Full bleed artwork, no frame, no border, no card corners, no text, no logo, no watermark. Square format, 1:1 aspect ratio.
```

---

## MODELO PARA NOVOS PERSONAGENS / TEMPLATE FOR NEW CHARACTERS

Copie este bloco para o fim do arquivo e preencha. Adicione uma linha no índice. / Copy this block to the end of the file and fill it in. Add a line to the index.

```
## NN. NOME

Arte final de referência: Artes\Personagens\<arquivo>

### PT-BR
- Papel:
- Cabelo:
- Rosto (olhos, expressão, marcas):
- Corpo e anatomia:
- Figurino:
- Mãos aprovadas (fórmula do guia 0.1: lado, pose, cada dedo, polegar no lado interno):
- Poder / efeito visual:
- Elementos recorrentes (criaturas, objetos):
- Composição da arte final:
- Cores saturadas (acento):

### EN
(mesmo conteúdo em inglês / same content in English)

### Prompt base
(um prompt pronto para Gemini/ChatGPT/Midjourney, incluindo "no frame, no text" e a descrição das mãos)
```

---

## ITENS / ITEMS

### 01 CAJADO DE COMANDO DO ZÉ DO TROVÃO (Ferramenta / Tool)

- **Tipo de carta:** Ferramenta (do Zé do Trovão - Velha guarda, tema Raio). Fundo com contexto (regra em `Fundos/Fundos_AMV.md`).
- **Design (PT-BR):** cajado de madeira marrom escura. Ponta de cima (onde ele segura): empunhadura de METAL como na arte do personagem: cilindro reto de aço cinza-chumbo escovado, curto (cerca de uma largura de punho), um pouco mais largo que a haste, com um pequeno colar de aço levemente aberto na parte de baixo, onde encontra a haste de madeira marrom mais fina; topo com corte plano, sem pomo e sem anel largo separado. Ponta de baixo (que toca o chão): ponteira de metal bem ornamentada, em ouro envelhecido e aço, com anéis gravados, pequenos raios entalhados e ponta facetada que brilha em azul elétrico. Raios finos branco-azulados enrolam a haste.
- **Design (EN):** dark-brown wooden staff. Top end (where he holds it): METAL grip as in the character art: a straight cylinder of dark gunmetal-grey brushed steel, short (about one fist-width), slightly wider than the shaft, with a small flared steel collar at its lower end where it meets the thinner brown wooden shaft; flat-cut top, no knob and no separate wide ring, as in the character art. Bottom end (touching the ground): a much more ornate metal ferrule in aged gold and steel with engraved rings, small carved lightning bolts and a faceted spike tip glowing electric blue. Thin white-blue lightning coils around the shaft.
- **Cena / contexto:** o cajado está em pé dentro de um armário de madeira antigo, com as duas portas abertas, nos aposentos do comandante. Dentro: casacos militares bordô com ombreiras douradas e uma prateleira com medalhas. A luz azul vem do próprio cajado e uma luz âmbar entra do quarto. A SOMBRA do Zé do Trovão (barrigudo, careca, orelhas pontudas, barba longa, braço estendido para a porta) aparece no lado, mostrando que foi ele quem abriu. Ele NÃO aparece em cena, só a sombra.
- **Paleta:** bordô, dourado, azul elétrico.
- **Estilo:** principal (guia, seção 1.0), cajado grande em primeiro plano.
- **Composição aprovada para a cena:** visão em primeira pessoa de quem abriu o armário (câmera colada, olhando para dentro). O cajado fica DENTRO do armário, ENCOSTADO na parede lateral esquerda (inclinado, topo na parede, ponteira no chão). Só um casaco. A sombra projetada do Zé, vista como a de alguém DE FRENTE para o armário (de costas para a câmera): sobe do chão na borda de baixo para o fundo do armário, cabeça redonda careca com pontas das orelhas, ombros largos e um braço estendido; sem perfil e sem barba. Ele não aparece.
- **Ajustes pedidos:** cajado MAIS FINO e MENOR (bengala fina, menos que a altura interna do armário); Zé levemente mais alto na sombra e com as proporções da arte (ombros largos, barriga redonda, cabeça careca pequena, orelha pontuda, barba longa); a luz do cajado é AZUL e ilumina tudo em azul (interior, portas, sombra em azul-marinho translúcido), com dourado só nas medalhas e ombreiras.
- **Procedimento:** anexar a arte do Zé no Gemini (o usuário escolhe o arquivo) e escrever no prompt que ela é a referência exata de proporções e do cajado.
- **Arte:** conversa Gemini `gemini.google.com/app/e39c84205f156b2a` (versão com arte anexada, luz azul). Dica: o Gemini mantém a composição da imagem anterior quando se pede edição; para mudar a câmera, começar uma conversa nova com o prompt completo.

- **VERSÃO EQUIP (direção atual, substitui a do armário):** cajado sozinho, grande e centralizado, na diagonal, com aura azul, sobre fundo azul elétrico vibrante cheio de raios (estilo carta Equip/Item, ver guia seção 8b). Arte: conversa Gemini `gemini.google.com/app/f6d15b3727e6573a`. As versões do armário ficam como alternativas.
- **Versão equip com empunhadura de metal curta (atual):** cajado inteiro dentro do quadro, empunhadura de aço curta (cerca de 1/8 do comprimento) com colar aberto, haste de madeira, ponteira ornamentada, fundo azul com raios. Arte: conversa Gemini `gemini.google.com/app/3293019f07b51e61`. Dica: quando uma edição no Gemini não muda o que foi pedido, refazer em conversa nova com o prompt completo.
