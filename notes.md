ul list-style: none; - para tirar os pontos da lista

O que é Padding: A propriedade paddingdefine uma a distância entre o conteúdo de um elemento e suas bordas. É um atalho que evita definir uma distância para cada lado separadamente

Para a criação das caixinhas dos links: o que foi configurado
background com a cor da caixas
display: flex;
flex-direction: colum; (para colocar as colunas)
gap: 16px (espaço entre as colunas)

colocando a borda nas colunas: border 1px solid( cor: 255,255,255, 0.5) que fica branco.
border-radius: 8px; arredondamento de borda

para tirar a linha debaixo do texto podemos usar text-decoration: none;
tamanha da fonte: font-weight: 500

colocar transição no botão (transition)

gap: espaçamento
padding: (acredito que seja largura pra cima e baixo)

para adicionar icones temos que colocar esse codigo --> <script src="https://unpkg.com/ionicons@4.5.10-0/dist/ionicons.js"></script> / no final antes do fechamento do body.

no site ionicons podemos encontrar os icones das redes e outros que podemos usar
justify-content: para ajustar (center) - centro

border-radius: colocar a bolinha no icone

#social-links a {
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 16px;
} - esse comando ajusta a bolinha do icone - deixando ela visualmente redonda e com o padding de 16px não fica caindo

footer é usado para a criação do rodapé da página


Começando o Light Mode

root raiz em CSS --text-color: white
toda vez que tiver uma cor branca eu coloco uma variante (var) com o text-color e vai continuar branco. 

Construindo o botão

position: absolute (faz uma sobreposição de camada)
z-index: mudando de camada