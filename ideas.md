# Especificação visual de referência — Dragão Lanches

## Ground truth

Este projeto é uma reprodução fiel do código HTML/CSS/JavaScript fornecido pelo usuário em `texto.txt`. A referência fornecida é a autoridade visual e comportamental; a implementação deve preservar a composição, paleta, tipografia, espaçamentos, microinterações, conteúdo do cardápio e comportamento responsivo originais.

## Direção escolhida

**Estética editorial artesanal de lanchonete tradicional brasileira**, com papel creme, verde garrafa, vermelho tomate, amarelo mostarda, bordas desenhadas, sombras sólidas e tipografia expressiva. A direção não deve ser reinterpretada ou modernizada: deve seguir o código de referência.

### Design Movement

Editorial vernacular / embalagem retrô contemporânea, aplicado com estrutura web semântica e responsiva.

### Core Principles

1. Contraste cromático quente entre creme, verde escuro e vermelho.
2. Hierarquia expressiva com títulos display e texto utilitário legível.
3. Profundidade obtida por bordas escuras e sombras sólidas deslocadas.
4. Conteúdo direto, local e tradicional, sem elementos decorativos que desviem do cardápio.

### Color Philosophy

O creme funciona como papel impresso; o verde comunica tradição e estabilidade; o vermelho atua como apetite e ação; o amarelo aparece como detalhe de destaque. A paleta deve permanecer exatamente nos valores do código original.

### Layout Paradigm

Página de rolagem única com cabeçalho sticky, hero assimétrico em duas colunas, faixa de benefícios, cardápio em painéis de abas, localização em duas colunas e rodapé compacto. Em telas menores, a composição colapsa verticalmente e adiciona barra fixa para ligação.

### Signature Elements

- Faixa superior checkerboard verde/creme.
- Sombras sólidas deslocadas em cards e botões.
- Miniatura circular do dragão no cabeçalho e rodapé, preservada a partir do asset embutido no código enviado.

### Interaction Philosophy

As interações são rápidas e objetivas: navegar por âncoras, alternar categorias do cardápio, abrir modal de pedido por telefone, copiar o número e abrir rota no Google Maps. Cada interação deve fornecer feedback visual claro e acessível.

### Animation

Usar apenas transições curtas e a animação de entrada sutil dos painéis do cardápio já definida na referência. Respeitar `prefers-reduced-motion` e preservar o comportamento original de abertura/fechamento do modal e menu mobile.

### Typography System

`Bricolage Grotesque` para títulos, display, preços e marca; `Work Sans` para navegação, corpo, tabelas e microcopy. Manter a hierarquia e os pesos declarados no código original.

### Brand Essence

A lanchonete tradicional de São Carlos para quem quer lanche feito na hora, com retirada no balcão ou consumo no local. Personalidade: **tradicional, direta, acolhedora**.

### Brand Voice

Headlines e CTAs devem soar locais, confiáveis e sem exagero publicitário. Exemplos: “O sabor mais tradicional de São Carlos” e “Ligar para fazer o pedido”. Evitar preenchimento genérico.

### Wordmark & Logo

Preservar o símbolo circular do dragão contido no código original como marca gráfica, sem substituir por logotipo genérico ou texto renderizado em fonte padrão.

### Signature Brand Color

`#C1442D` — vermelho tomate usado para ação, preço e pontos de atenção.

## Nota de implementação

Cada arquivo de componente/estilo criado para a interface deve começar com um comentário curto lembrando que a reprodução deve seguir esta referência. O backend não faz parte do escopo; o site é frontend-only.
