# Página de vendas — Kit Confeitaria de Luxo no Natal (estrutura nova)

Refaça o index.html do zero, 100% mobile-first e leve (connect rate rápido). Use como MATÉRIA-PRIMA o arquivo COPY.md desta pasta (só informações que estão nele, nada inventado). Imagens: pasta assets/ (use as reais no lugar dos placeholders sempre que existir uma adequada). Mantenha o script da WhatsTrack (whatstrack.html) e o repasse de UTMs para os 2 links de checkout.

## Visual
Parecido com a oferta original de moldes natalinos: Natal de luxo e chamativo — verde-esmeralda escuro, vermelho intenso, dourado e creme, títulos em serifa dourada, CTAs grandes vermelhos com borda dourada. Coluna central máx. 480px. Nunca use travessões na copy.

## Lógica comercial
- PRODUTO PRINCIPAL = plano Básico do COPY.md, R$ 11,99. É a única oferta visível na página.
- PACOTE PREMIUM = plano Completo, R$ 19,99 = produto principal + cada item extra do Completo (os bônus) como PRODUTO ADICIONAL com nome próprio. Nunca escrever "bônus", "brinde", "presente". Não inventar produtos, preços individuais, economia ou desconto.
- Ignore order bumps (eles ficam no checkout).
- Sem plano básico x completo, sem comparação, sem preço âncora/riscado, sem parcelamento, sem cronômetro, sem falsa urgência.

## Botões
- TODO botão fora do card de oferta = âncora com scroll suave até id="oferta". Não abre popup nem checkout.
- SÓ o botão dentro do card de oferta abre o POPUP PREMIUM.
- Popup: fundo escurecido, centralizado, 360–430px, fechável, sem scroll horizontal. Título tipo "ANTES DE FINALIZAR, VEJA ESSA OPÇÃO". Bloco do produto principal + 1 bloco por produto adicional (placeholder quadrado, nome, descrição curta). Botão maior: "QUERO O PACOTE PREMIUM POR R$ 19,99" → https://pay.lowify.com.br/checkout?product_id=b7l4Ff . Abaixo, bem visível: "CONTINUAR SOMENTE COM O KIT POR R$ 11,99" → https://pay.lowify.com.br/checkout?product_id=gE5zga . Ambos com as UTMs.

## Dobras
1. PROMESSA: kicker em letras espaçadas (CONFEITARIA DE NATAL) · headline quantidade + material + nicho · linha decorativa · mídia 9:16 (use a capa-01, sem fundo/borda; sem vídeo) · bullets curtos só do produto principal · botão âncora · "Acesso imediato por celular, tablet ou computador. Arquivos em PDF."
2. O QUE VOCÊ VAI ENCONTRAR: texto curto (o que é, para que serve, para quem) · carrossel 1 animado para a direita · carrossel 2 animado para a esquerda · 4 imagens A4 grandes cada · contínuos, 12s por ciclo, máx. 480px centralizados · só conteúdo do produto principal.
3. POR QUE É VALIOSO: grid 6 benefícios (emoji + título + 1 linha), só do principal.
4. TUDO O QUE VOCÊ VAI RECEBER: badge "ACESSO IMEDIATO" · imagem 1080x1080 · bullets dos itens do principal · grid 6 temas cobertos com emoji · botão âncora.
5. IDEAL PARA VOCÊ QUE DESEJA: grid 6 itens (emoji + título + 1 linha).
6. OFERTA (id="oferta"): título comercial sem falsa escassez · subtítulo curto · 1 card: nome, subtítulo, descrição, imagem, bullets com check, preço R$ 11,99 em destaque, botão "QUERO ACESSAR AGORA" (abre popup) · texto de fechamento.
7. GARANTIA: selo "7 dias" e texto LITERAL: "Você pode pedir reembolso em até 7 dias a partir da compra, pelo art. 49 do CDC." (nada de 30 dias).
8. FAQ: 7 perguntas em acordeão, respostas curtas, escolhidas das 12 do COPY.md (inclua a de uso no celular/computador e a de reembolso). Não revelar os produtos adicionais.
9. RODAPÉ: copyright 2026 · não afiliação a Facebook, Instagram e Google · direitos autorais do material · proibida reprodução/revenda (uso só nos próprios doces).

Salve por cima do index.html.
