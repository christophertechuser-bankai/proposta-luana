# Proposta de parceria — Avantis + LB Marketing Jurídico

## Status

- **Página no ar:** https://christophertechuser-bankai.github.io/proposta-luana/
- **Repo:** https://github.com/christophertechuser-bankai/proposta-luana (público — privatizar depois que Luana ler, ~2 dias)
- **Arquivo principal:** index.html (self-contained)
- **Vídeos:** hero-bg.mp4 (desktop, holographic brain widescreen), hero-bg-mobile.mp4 (vertical, brain centralizado, sem marca d'água)

## Sobre a Luana

- **Nome:** Luana Bett
- **Empresa:** LB Marketing Jurídico
- **Relação:** Parceira comercial (não cliente). Ela traz advogados, Avantis entrega o produto.
- **Comissão:** 30% setup + 20% recorrência mensal

## Design

- Dark fintech aesthetic, verde esmeralda (#10b981) + dourado (#c5a55a)
- Font: Raleway (display) + Inter (body) + JetBrains Mono (terminal demo)
- Glassmorphism, GSAP ScrollTrigger animations

## Interatividades implementadas (2026-07-18)

1. **Typing demo** — Terminal animado com 4 cenários (pesquisa, tese, prazos, revisão). Botões para alternar. Auto-start on scroll.
2. **Flip cards** — 6 mind-clones viram no hover (desktop) / toque (mobile) mostrando especialidades.
3. **Slider calculadora** — Range 1-100 clientes, calcula receita mensal e setup acumulado com mix de planos (60% essencial, 30% completo, 10% escritório).

## Precificação (o que o cliente paga)

| Plano | Setup | Mensal |
|---|---|---|
| Essencial (2 áreas) | R$2.000 | R$197/mês |
| Completo (todas) | R$3.000 | R$397/mês |
| Escritório (3+ advogados) | R$5.000 | R$697/mês |

## Pendências

- [ ] Privatizar repo depois que Luana ler (~2 dias da data de envio)
- [ ] WhatsApp configurado: 5521968103478 (confirmar se é o número correto da Bianca)
- [ ] Proposta da Larissa (C:\dev\AVANTIS PROJECT\clientes\larissa-machado\proposta\) — WhatsApp também precisa do número real

## Decisões tomadas

- Headline: "o mercado jurídico tem um produto novo. E ele é nosso." (não framing de "criamos porque você queria")
- Gênero: "juntos/donos" (Christopher é homem, Bianca é esposa)
- Font mudou de Playfair Display (serif) para Raleway (corporate, straight)
- Video hero mobile opacity: 0.15 (quase invisível, só textura)

## Git quirk

- O sandbox do Claude Code não consegue fazer `git add` de arquivos grandes (>5MB) neste repo — dá Permission Denied nos objetos git. Workaround: clonar o repo em pasta temp, fazer o add/commit/push por lá, e deletar.
