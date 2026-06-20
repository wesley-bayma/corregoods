# CORRE GOODS · Apresentação 001 — Guia de uso

Apresentação estratégica em HTML para defender o projeto **CORRE GOODS** com um possível investidor/parceiro.
Não é página pública de venda de ingresso — é um pitch visual de marca + modelo de negócio.

**Arquivo principal:** `corre-goods-001-apresentacao.html`
**Assets:** pasta `assets/` (logos reais da marca, já vinculados)

---

## 1. Como usar

- **Abrir:** dê duplo clique em `corre-goods-001-apresentacao.html` (abre em qualquer navegador moderno: Chrome, Edge, Safari, Firefox). Nada a instalar.
- **Na reunião:** abra em tela cheia (`F11`). A página é uma narrativa de rolagem — vá descendo por seção enquanto apresenta. Os botões do topo (`A tese`, `Oportunidade`, `Edição 001`, `Negócio`, `Proposta`) saltam direto para cada bloco.
- **Enviar por e-mail / WhatsApp:** zipe a pasta inteira (`corre-goods-001-apresentacao.html` + pasta `assets/`) mantendo a estrutura. O HTML precisa da pasta `assets/` ao lado dele.
- **Virar PDF:** abra no Chrome → `Ctrl+P` → "Salvar como PDF" → ative **"Gráficos de plano de fundo"** (senão as seções pretas saem brancas). As animações já têm rede de segurança: o conteúdo aparece mesmo sem rolar, então o PDF sai completo.
- **Internet:** só é usada para baixar as fontes (Google Fonts). Sem internet, o navegador usa uma fonte de sistema parecida — funciona, mas o ideal é apresentar online.

---

## 2. O que já está pronto (assets reais da marca)

Identidade da pasta original, em `assets/` (já embutidos):

| Arquivo em `assets/` | Origem | Onde aparece |
|---|---|---|
| `brand-board.jpg` | `corregoods.png` (board completo) | Seção 06 — Visual da marca (board grande) |
| `wordmark-stacked.png` | `CorreGoods (3).png` | Seção 06 — card "Marca principal" |
| `monogram.png` | `CorreGoods (2).png` — C·G | Seção 06 — card "Monograma" |

O wordmark **CORRE GOODS.** do topo e do encerramento é renderizado como texto (fonte pesada + ponto verde-ácido), fiel ao seu logo — assim escala perfeito em qualquer tela.

---

## 3. As 9 fotos da marca (JÁ INTEGRADAS e otimizadas)

As 9 imagens da pasta `imagens/` foram copiadas para `assets/`, **redimensionadas (1500px) e convertidas para JPG** (os originais ficam intactos em `imagens/`). Total de assets: de ~24MB para **~2,9MB**. Cada foto tem fallback: se o arquivo sumir, a página mostra a moldura desenhada — nunca quebra.

| Seção | Arquivo em `assets/` | Conteúdo |
|---|---|---|
| Hero | `cg-hero-orla.jpg` | corredores na orla ao amanhecer (bandeira + muro CG) |
| Oportunidade | `cg-som-movel.jpg` | carro de som com DJ guiando o pelotão (banda 21:9) |
| Como funciona | `cg-checkin.jpg` | check-in / estande na orla |
| Edição 001 | `cg-dj-movimento.jpg` | DJ no carro de som (DJ em movimento) |
| Visual da marca | `cg-merch-kit.jpg` | flat-lay do kit/merch 001 |
| Para quem é | `cg-publico.jpg` | corredores sorrindo + placa 001 |
| After run | `cg-after-run.jpg` | estande com bebidas, 18+ e produtos |
| Ativações | `cg-carro-dj.jpg` | carro de apoio com DJ (som móvel) |
| São Luís | `cg-saoluis.jpg` | evento 001 na orla (crop 3:4) |

**Para trocar qualquer foto:** substitua o arquivo `.jpg` correspondente em `assets/` mantendo o mesmo nome.

---

## 4. Shot list para o evento real (substituir as imagens-conceito)

As 9 fotos atuais são **conceito/mockup** da marca. Quando rodar o piloto (ou um ensaio teaser antes), recapture este pacote com gente e local reais de São Luís e troque os arquivos em `assets/`:

1. **Hero** — grupo correndo na orla ao amanhecer, de trás, contra a primeira luz, com a faixa/identidade visível.
2. **DJ em movimento** — DJ com som móvel (carro/bike de apoio) acompanhando o grupo durante o percurso.
3. **After run** — galera parada, social, água de coco / café gelado, sorrindo (bebida 18+ só em frames pontuais e responsáveis).
4. **Detalhe de produto** — camiseta off-white 001, boné, pulseira da edição (flat lay + no corpo).
5. **Orla / cenário** — Litorânea, areia, ciclovia, quiosque na luz da manhã (sem foto, vertical).
6. **Retratos de público** — 2–3 pessoas em look streetwear/corrida, estética de moda.
7. **Photo wall / credencial** — alguém na frente do painel com a marca.
8. **Recap em movimento** — frames de vídeo (largada → corrida com DJ → after run).

Direção: **luz natural de amanhecer / primeira luz**, tons off-white/areia/preto, nada de estética de prova esportiva tradicional (sem medalhão, pódio, numeração de peito). Pensar "lookbook de marca de roupa", não "corrida de rua".

---

## 5. Como editar textos e números

- Tudo é texto direto no HTML — `Ctrl+F` pelo trecho que quer mudar e edite.
- **Números do modelo de negócio e P&L** (seções 07 e 11) são *referências do relatório estratégico*, marcados como "a validar localmente". Ajuste para os valores reais de São Luís assim que tiver orçamentos fechados (DJ, som, permits, local do after).
- **Contato:** o botão final e o rodapé apontam para `wesleycarvalho.coach@gmail.com`. Troque se quiser usar um e-mail/Instagram da marca. Procure por `wesleycarvalho.coach@gmail.com` no arquivo.
- **Cores:** estão centralizadas no topo do `<style>` em `:root` (`--off-white`, `--acid`, etc.). Mudou ali, mudou no site todo.

---

## 6. Observações / ajustes finais sugeridos

- **Acessibilidade:** contraste do texto de corpo já ajustado para passar leitura confortável sobre o off-white. Mantenha verde-ácido só em detalhes/fundos pretos — não use verde como cor de texto longo.
- **Fontes:** uso `Archivo` (display + corpo) e `Martian Mono` (tags/credencial 001) — evitei as fontes "cara de IA" e mantive fiel ao peso do seu logo. Se quiser comprar a fonte exata do logo depois, dá pra trocar só a `--font` sem mexer no layout.
- **Sem reggae:** a seção "Por que São Luís" trata a cidade como cenário (orla, sol, calor social) e afirma o território **eletrônico** — exatamente como pediu.
- **Movimento:** animações com `prefers-reduced-motion` respeitado e rede de segurança (conteúdo nunca some, mesmo em PDF/print). Inclui: reveals com blur na rolagem, **stagger** (cards entram em sequência), **count-up** dos números da Oportunidade, **zoom da foto no hover**, pulse dos marcadores e marquee que pausa no hover.
- **Imagens:** otimizadas para JPG (~2,9MB no total). Lazy-load — carregam conforme a rolagem.

---

## 7. Checklist de melhorias para a v2 (pós-piloto)

- [x] ~~Trocar placeholders por fotos~~ — feito: 9 fotos da marca integradas e otimizadas.
- [ ] Recapturar as 9 fotos com **gente e local reais** do piloto (hoje são conceito) e trocar em `assets/`.
- [ ] Inserir um **vídeo recap** curto (loop mudo) no Hero ou na Edição 001.
- [ ] Adicionar **logos reais dos primeiros patrocinadores/collabs** (faixa "apoiam o 001").
- [ ] **Playlist oficial** embutida (player Spotify/SoundCloud) na seção de ativações — CG Sounds.
- [ ] **Mapa da rota de 6km** real (imagem ou embed) na Edição 001.
- [ ] P&L com **números fechados de São Luís** (DJ, som, permits, local, merch).
- [ ] **Depoimentos / prova social** após o primeiro evento (NPS, frases de participantes).
- [ ] **Lista de espera**: trocar o CTA de e-mail por um formulário real (quando virar captação).
- [ ] Versão **deck/slide** (uma seção por tela) para projetor, se a reunião exigir.
- [ ] Meta tags de **compartilhamento** (Open Graph) + favicon CG, caso vá virar link público.

---

## 8. Estrutura de seções (índice da narrativa)

1. **Hero** — impacto, *running / music / street*, edição 001 + meados de outubro + morning run, CTA
2. **A tese** — corrida, som e rua (DJ em movimento + after monetizado)
3. **Oportunidade** — dados de mercado reais (R$1,1bi, +85%, ~800% Strava, 0 concorrentes em SLZ)
4. **Como funciona** — 6 passos (check-in → 6km → DJ em movimento → after → ativações → conteúdo)
5. **Edição 001** — pôster/credencial "A RUA É O PONTO" + spec + **fluxo do dia (operação)**
6. **Visual da marca** — board real + paleta + tipografia + aplicações
7. **Para quem é** — público-alvo (tag cloud)
8. **Como o piloto monetiza** — 4 frentes (ingresso, after run, ativação, merch) + **hipótese de receita**
9. **O after run** — área de consumo (bebidas / comida leve / produtos) + **ativação de cerveja 18+**
10. **Ativações** — checklist do que cria marca
11. **Por que São Luís** — cidade como cenário ao amanhecer (território eletrônico)
12. **Do conceito ao piloto** — roadmap 10 passos + plano de 30 dias
13. **A proposta** — o que somamos juntos, P&L do piloto, por que agora
14. **Encerramento** — "A rua é o ponto" + CTA

---

*Construído com base no relatório `docs/pesquisa-estrategica-corre-goods.md` e na identidade visual da pasta do projeto. Direção de design e polimento de UI apoiados nas skills `impeccable`, `ui-ux-pro-max` e `make-interfaces-feel-better`.*
