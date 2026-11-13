# Vetra Game Lab — Assistência Técnica de Videogames
Modelo demonstrativo da **Guará Agency**, criado a partir da estrutura visual e interativa de `demos/vetra-mobile/index.html` do site da agência.

## O que o modelo demonstra
- Identidade visual azul, branca e grafite, com hero em perspectiva, animação de console e controle criada com CSS.
- Navegação com cinco áreas: Início, Assistência técnica, Consoles e controles, Sobre e Contato.
- Serviços: porta HDMI, reballing/reparo BGA, manutenção térmica, fonte e placa, drift de controles, leitores, armazenamento, firmware/desbloqueio e conectividade.
- Vitrine de plataformas com filtros, busca e abertura de detalhes.
- Formulário orientado a diagnóstico e resumo copiável.
- Consulta **fictícia** de ordem de serviço `VGM-2408`.
- Layout responsivo, CSS autoral, ícones Lucide, controles de teclado e `prefers-reduced-motion`.

## Observações importantes
Esta é uma demonstração de portfólio. A marca é fictícia. **Não existe oficina, atendimento real, preço, estoque, garantia ou integração WhatsApp vinculada a este projeto**.
Acompanhamento de ordem de serviço, orçamentos e formulário funcionam como simulações locais no navegador e não enviam dados.
Serviços BGA/reballing e desbloqueio exigem avaliação técnica, compatibilidade, definição de riscos e observância da legislação e termos aplicáveis. Nenhum serviço é prometido como solução universal ou oferecido para pirataria.
Marcas de consoles são citadas exclusivamente como exemplos de equipamentos, sem vínculo comercial ou afiliação.

## Executar
Abra `index.html` no navegador, ou use:
```bash
python -m http.server 8000
```
Sem Node, framework ou banco de dados. Requer conexão somente para fontes Google Fonts e ícones Lucide via CDN; o texto e a estrutura permanecem disponíveis sem esses recursos.

## Publicação no GitHub Pages
Há um workflow estático em `.github/workflows/pages.yml` com deploy a cada push na `main`.
Em **Settings → Pages**, selecione **Build and deployment → GitHub Actions** na primeira publicação.
URL esperada após ativação: `https://guaraagency-julio.github.io/modelo-assistencia-videogame/`.

## Personalizar para uma oficina real
1. Substituir nome fictício, endereço, canais, horários e condições de atendimento.
2. Confirmar os serviços e compatibilidades de cada modelo.
3. Integrar WhatsApp com número real e sistema de ordens de serviço, caso contratado.
4. Substituir a vitrine ilustrativa por fotos autorizadas e condições reais.
5. Configurar domínio, OG preview PNG, analytics e revisão SEO. Retirar `noindex` apenas quando o negócio real estiver pronto.

Design base: VETRA MOBILE / Guará Agency. Adaptação para nicho de videogames: Vetra Game Lab.
