# Design System --- ZAPSpeak

## 1. Referência visual

A direção visual do site deve ser construída a partir da apostila
**ZAPSpeak --- Apostila Básico 1**, mantendo a mesma linguagem visual do
material didático.

A apostila apresenta uma identidade infantil, educativa, acolhedora e
descontraída. O universo visual combina elementos de escola e
aprendizagem com ilustrações cartoon, personagens, balões de fala e
pequenos elementos decorativos.

O site deve parecer uma extensão digital da experiência apresentada na
apostila: amigável para crianças, mas organizado e claro o suficiente
para transmitir confiança aos pais e responsáveis.

**Referência principal:** páginas internas da apostila, especialmente as
páginas sobre alfabeto, pronomes, membros da família e verbo *to be*. A
capa também serve como referência para a marca e para o uso dos
elementos espaciais.

## 2. Personalidade visual

Palavras-chave:

-   Infantil, sem parecer excessivamente infantilizado.
-   Divertido e acolhedor.
-   Educativo e didático.
-   Leve e descontraído.
-   Colorido, mas organizado.
-   Próximo e familiar.
-   Fácil de compreender.

A interface deve transmitir a ideia de que aprender inglês pode ser uma
atividade divertida e compartilhada entre criança e mãe.

Evitar uma aparência corporativa, rígida, formal ou semelhante à de uma
plataforma escolar tradicional.

## 3. Paleta de cores

A paleta deve seguir as cores recorrentes da apostila. Os códigos abaixo
são aproximações visuais para orientar a implementação; podem ser
ajustados para manter contraste e legibilidade.

  -----------------------------------------------------------------------
  Cor                     Código aproximado       Aplicação
  ----------------------- ----------------------- -----------------------
  Roxo principal          `#514477`               Títulos, textos de
                                                  destaque, marca e
                                                  elementos de navegação

  Roxo escuro             `#35245F`               Ênfases, botões
                                                  principais e áreas de
                                                  destaque

  Verde suave             `#8CCB91`               Elementos positivos,
                                                  aprendizagem,
                                                  atividades e destaques

  Verde claro             `#DDF4C5`               Fundos suaves e áreas
                                                  de apoio

  Amarelo pastel          `#F8E39A`               Destaques, pequenos
                                                  detalhes e chamadas

  Lilás claro             `#D8C5E8`               Fundos de cartões e
                                                  elementos secundários

  Rosa claro              `#F6D8E2`               Detalhes delicados e
                                                  áreas de apoio

  Branco quente           `#FFFEFC`               Fundo principal e áreas
                                                  de leitura
  -----------------------------------------------------------------------

### Regras de uso

-   Roxo é a cor de maior reconhecimento da marca e deve funcionar como
    cor principal.
-   Verde deve equilibrar o roxo e destacar informações positivas ou
    relacionadas à aprendizagem.
-   Amarelo, lilás e rosa entram como cores de apoio, sem competir com o
    conteúdo.
-   Priorizar fundos claros e textos escuros.
-   Não usar todas as cores com a mesma intensidade em uma única seção.
-   Manter contraste suficiente entre texto e fundo, especialmente em
    textos pequenos.

## 4. Tipografia

A apostila utiliza títulos em letras maiúsculas, pesadas e de leitura
rápida, com aparência arredondada e amigável. Os textos explicativos são
simples, bem destacados e fáceis de acompanhar.

### Direção tipográfica

-   **Títulos:** fonte sans-serif arredondada, encorpada e amigável.
    Preferir pesos bold ou extra-bold.
-   **Subtítulos:** sans-serif com boa presença, em bold ou semibold.
-   **Textos corridos:** sans-serif simples, com boa legibilidade em
    telas pequenas.
-   **Rótulos e chamadas:** podem utilizar caixa alta, seguindo o estilo
    dos títulos da apostila.

Sugestões de fontes que podem reproduzir essa linguagem: - Nunito ou
Nunito Sans. - Fredoka para títulos mais expressivos. - Quicksand para
textos curtos e elementos auxiliares.

Usar no máximo duas famílias tipográficas no site. A fonte escolhida
deve possuir acentos e caracteres em português.

### Hierarquia

-   Títulos principais grandes e curtos.
-   Subtítulos claramente separados dos textos.
-   Parágrafos curtos.
-   Listas com espaçamento confortável.
-   Evitar blocos longos de texto em letras maiúsculas.

## 5. Ilustrações e elementos gráficos

As ilustrações são uma parte central da identidade da apostila e devem
orientar a linguagem visual do site.

### Estilo de ilustração

-   Personagens em estilo cartoon, com aparência amigável e expressiva.
-   Crianças, mãe/responsável e professora como figuras de aprendizagem
    e interação.
-   Desenhos com contornos suaves e cores alegres.
-   Ilustrações que ajudem a explicar a informação, em vez de serem
    apenas decoração.
-   Elementos relacionados a inglês, comunicação e estudo.

Apostila também utiliza uma personagem feminina como
professora/mentora, com cabelo escuro, óculos e roupas em tons escuros e
rosados. Caso essa personagem seja representada no site, manter sua
aparência coerente com a referência, sem criar versões visuais
conflitantes.

### Elementos gráficos recorrentes

-   Balões de fala.
-   Estrelas e pequenos brilhos.
-   Corações.
-   Foguete e planeta.
-   Ícones escolares e de aprendizagem.
-   Pequenos desenhos de apoio ao redor de títulos e seções.
-   Cartões ilustrados para apresentar conceitos.

Esses elementos podem aparecer em detalhes e pequenas intervenções. Não
devem prejudicar a leitura nem ocupar mais espaço que as informações
principais.

### Uso de imagens

Priorizar ilustrações próprias ou imagens que mantenham o mesmo estilo
da apostila. Evitar misturar ilustrações cartoon com fotografías
genéricas de banco de imagens em uma mesma área, pois isso pode quebrar
a unidade visual.

**Elementos de imagem já definidos:**

- **`cartaoquadrado.jpeg`**: Logo da marca - deve aparecer no header como ícone identificador, junto ao nome ZAPSpeak. Usado como favicon/site icon e como elemento de marcação nos cards.
- **`moeda.jpeg`**: Ilustração do sistema Speakts - deve ser exibida como ícone giratório na seção de Speakts do Grupo Misto,representando a dinâmica de pontos e recompensas. Deve ter animação CSS de rotação contínua (20s por volta).
- **`poster1.jpeg`**: Capa da apostila - usada nos cards "Sobre" como imagem principal ilustrando o conceito "Aprender juntos é mais divertido".
- **`poster2.jpeg`**: Material didático - usada como referência visual de apoio nas seções.
- **`formas.jpeg`**: Elementos geométricos/formatos da identidade visual - podem ser usados como padrões de fundo sutis ou elementos decorativos ao redor de títulos e seções, mantendo a unidade visual da apostila.
- **`cartao.jpeg`**: Textura ou elemento de card - pode ser usado como padrão de fundo interno dos cartões ou como detalhe decorativo nos cantos.
- **`modoregra.jpeg`**: Material de referência geral - para consulta caso seja necessário elementos adicionais de identidade visual.

## 6. Componentes e padrões de interface

### Cartões de conteúdo

A apostila organiza conteúdos em blocos separados, com títulos claros,
cores de apoio e ilustrações. Reproduzir essa lógica em cartões
digitais.

Características: - Cantos arredondados. - Fundo claro ou em uma das
cores pastel da paleta. - Título destacado. - Ícone ou ilustração
relacionado ao conteúdo. - Espaçamento interno confortável. - Sombra
discreta, se necessária.

Usar cartões para apresentar benefícios, etapas, atividades, informações
das modalidades e perguntas frequentes.

### Botões

-   Formato arredondado.
-   Texto curto e direto.
-   Peso tipográfico bold.
-   Cor roxa para a ação principal.
-   Verde ou amarelo pastel para ações secundárias, desde que o
    contraste seja adequado.
-   Estados visuais claros de hover, foco e clique.

O botão de contato pelo WhatsApp deve ser facilmente identificável e
manter destaque em relação às ações secundárias.

### Ícones

Utilizar ícones simples, amigáveis e visualmente consistentes. Sempre
que possível, seguir a linguagem ilustrada da apostila em vez de
misturar muitos estilos de ícones diferentes.

### Listas e etapas

A apostila usa exemplos visuais, personagens e organização por blocos.
Para listas digitais: - Usar ícones ou marcadores ilustrados. - Separar
cada informação com espaço suficiente. - Destacar palavras-chave. -
Evitar listas muito densas.

### Caixas de destaque

Usar fundos pastel para informações importantes, avisos e chamadas. O
roxo pode ser utilizado em áreas de maior destaque, mantendo o texto com
contraste adequado.

## 7. Layout e composição

A composição deve ser arejada e fácil de percorrer. A apostila utiliza
áreas brancas amplas, conteúdo centralizado, títulos evidentes e
elementos ilustrados distribuídos ao redor das informações.

Diretrizes: - Manter uma largura de leitura confortável. - Criar
separação clara entre as seções. - Usar espaços em branco para evitar
excesso de informação. - Alternar seções claras com blocos de destaque
em cores pastel. - Combinar texto e ilustração sem deixar a página
visualmente carregada. - Em telas pequenas, reorganizar cartões em uma
única coluna. - Garantir que textos, preços e botões sejam legíveis em
dispositivos móveis.

Não transformar cada seção em um bloco colorido intenso. As cores devem
organizar a experiência, não competir com o conteúdo.

## 8. Aplicação da identidade nas áreas do site

### Cabeçalho e navegação

-   Apresentar a marca ZAPSpeak com destaque.
-   Incluir o logo `cartaoquadrado.jpeg` ao lado do nome da marca.
-   Navegação simples e fácil de entender.
-   Manter a identidade roxa e os detalhes ilustrados da apostila.
-   O acesso ao contato deve ser fácil de localizar.

### Apresentação inicial

-   Usar uma chamada principal curta e de leitura imediata.
-   Apoiar a mensagem com ilustração relacionada à aprendizagem, à
    comunicação ou à relação entre mãe e criança.
-   Utilizar roxo como destaque e cores pastel como apoio.
-   Evitar excesso de elementos decorativos na área inicial.

### Explicação da mentoria

-   Organizar informações em blocos ou cartões.
-   Usar ícones e ilustrações para representar atividades e etapas.
-   Manter títulos curtos e textos objetivos.

### Modalidades e preços

-   Apresentar Grupo Misto e VIP em cartões separados.
-   Diferenciar as modalidades com cores de apoio, sem alterar a
    identidade principal.
-   Dar destaque visual aos preços e às diferenças entre os benefícios.
-   Manter as informações comparáveis e fáceis de localizar.

### Sistema Speakts

-   Utilizar elementos visuais ligados a pontos, conquistas e
    recompensas.
-   **Usar a imagem `moeda.jpeg` com animação de rotação contínua** para
    representar o sistema de pontos Speakts no Grupo Misto.
-   Estrelas, troféus e pequenos símbolos podem reforçar a ideia de
    progresso.
-   Apresentar a informação de forma organizada, evitando aparência de
    painel complexo.

### Contato e chamada final

-   Utilizar uma chamada visual clara.
-   Dar destaque ao botão do WhatsApp.
-   Manter a comunicação amigável e coerente com o restante da página.

## 9. Responsividade e acessibilidade

-   Desenvolver primeiro pensando na experiência mobile, já que a
    mentoria acontece pelo WhatsApp e o público provavelmente acessará o
    site pelo celular.
-   Garantir textos confortáveis para leitura em telas pequenas.
-   Não depender apenas das cores para diferenciar informações.
-   Usar contraste adequado entre textos e fundos pastel.
-   Usar áreas de toque confortáveis nos botões.
-   Manter hierarquia de títulos e navegação compreensível.
-   Fornecer descrições alternativas para imagens informativas.
  - `poster1.jpeg`: "Capa da apostila ZAPSpeak Básico 1 - criança e mãe estudando"
  - `moeda.jpeg`: "Ícone do sistema Speakts - moeda de pontos para recompensa"
  - `cartaoquadrado.jpeg`: "Logo da marca ZAPSpeak - quadrado com design da apostila"
  - `formas.jpeg": "Elementos gráficos de apoio ao redor de títulos e seções"
-   Respeitar a preferência por redução de movimento do dispositivo.
-   Evitar animações excessivas, efeitos piscantes e elementos que se
    movimentem continuamente.

## 10. O que evitar

-   Visual corporativo ou excessivamente formal.
-   Estética adulta, tecnológica ou minimalista demais, que
    descaracterize a apostila.
-   Cores neon ou saturadas que não aparecem na referência.
-   Grandes áreas com muitas cores fortes ao mesmo tempo.
-   Tipografia fina, condensada ou difícil de ler.
-   Excesso de fontes diferentes.
-   Fotografias genéricas misturadas sem critério às ilustrações
    cartoon.
-   Ícones com estilos visuais incompatíveis entre si.
-   Elementos decorativos em excesso.
-   Animações que distraiam da leitura.
-   Layout muito denso ou com aparência de material escolar burocrático.

## 11. Síntese para implementação

Criar uma interface infantil, educativa e acolhedora, inspirada
diretamente na apostila ZAPSpeak Básico 1.

A identidade deve combinar: - Roxo como cor principal. - Verde, amarelo,
lilás e rosa em tons pastel. - Fundos predominantemente claros. -
Tipografia arredondada e encorpada. - Personagens e ilustrações
cartoon. - Balões de fala, estrelas e elementos lúdicos. - Cartões
arredondados e conteúdo organizado em blocos. - Layout arejado,
responsivo e com prioridade para dispositivos móveis.

O resultado deve parecer parte do mesmo universo visual da apostila, sem
reproduzir literalmente suas páginas. Adaptar a linguagem gráfica para
uma experiência de site funcional, acessível e fácil de navegar.

**Referências de imagem implementadas:**

- `cartaoquadrado.jpeg` → Logo da marca no header e como ícone identificador
- `moeda.jpeg` → Animação giratória na seção Speakts (20s por volta, infinite)
- `poster1.jpeg` → Imagem principal nos cards "Sobre" (child + mother)
- `formas.jpeg` → Padrões de fundo sutis ou elementos decorativos ao redor de títulos