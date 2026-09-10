# Panco · Sistema de presença no PDV — 75 LAB

Apresentação comercial em HTML (10 telas) da proposta estratégica da 75 LAB para a **Panco**:
um sistema de presença no ponto de venda que integra as três frentes do briefing —
**Linha Sobremesas**, **Lançamento Tortillas** e **Ilha Cash & Carry** — em um menu modular
de MPDV, com piloto, rollout por ondas e cenários de dimensionamento.

> **Sem valores.** O deck não exibe preço, orçamento ou faixa de investimento em nenhuma tela —
> o investimento é apresentado em proposta comercial separada. O único dado em R$ é o tamanho de
> mercado da tela 04 (fontes públicas ABIMAPI/ABRAS).

**No ar:** https://projetos.75lab.com.br/panco-sistema-pdv/

## Roteiro (começo · meio · fim)
| # | Tela | Papel |
|---|------|-------|
| 01 | A marca mais fácil de encontrar | capa e promessa |
| 02 | Três frentes, uma mesma pergunta | o desafio |
| 03 | A tese: arquitetura de PDV | o insight (leitura em 10 m / 3–5 m / 0–1 m) |
| 04 | Por que agora | dados de mercado (ABIMAPI, ABRAS) |
| 05 | A arquitetura de leitura | o sistema + os 4 key visuals (horizontal e vertical de cada território) |
| 06 | As 3 frentes na prática | abas interativas com renders |
| 07 | Menu modular de MPDV | 14 peças em 3 níveis de ambição |
| 08 | O piloto como laboratório | cronograma (Trade Visit já concluído), desenho e KPIs |
| 09 | Dimensionamento e pacotes | 4 cenários de lojas/peças/prazo + 3 pacotes de contratação |
| 10 | Próximo passo | Trade Visit ✓ → Piloto → Rollout |

## Como usar
- Abra `index.html` no navegador (ou sirva a pasta com qualquer servidor estático).
- **Navegação:** setas ← →, espaço, PageUp/PageDown, `Home`/`End`, `M` abre o índice, swipe no mobile.
- **Interações:** abas das 3 frentes (tela 06), níveis do menu de MPDV (tela 07),
  cenários de dimensionamento (tela 09), territórios visuais (tela 05) e lightbox em todos os renders.
- **Exportar PDF:** `Cmd+P` — há estilo de impressão, uma tela por página (1600×900).
- Palco fixo de 1600×900 escalado para qualquer tela.

## Identidade
Baseada no **Manual de Identidade Visual da Panco** (ed. 1): vermelho Panco `#E1251B` (Pantone 485),
os três tons institucionais de vermelho (`#A91F24` `#9B1F24` `#8E1F21`), branco em grande destaque,
elemento visual curvo, bolinhas Panco, Reflex Blue `#001689` apenas em detalhes e amarelo
Pantone 116 `#FFCD00`. A fonte oficial **Neris** não tem versão web — está sendo usada **Nunito**
como substituta; trocar se o cliente fornecer os arquivos da Neris.

## Renders
Os 4 key visuals ficam na tela 05: `kv-infantil.webp` / `kv-adulto.webp` (horizontais) e
`kv-infantil-vertical.webp` / `kv-adulto-vertical.webp` (verticais) — cada aba mostra o par do
território e abre em tela cheia no clique.

Os renders em `assets/` vêm do estudo `PANCO_Estrategia_3_Frentes_MPDV_75LAB.pptx` (75 LAB),
otimizados em WebP. Os fundos das três vistas da ilha foram recortados para compor sobre as
áreas vermelhas. Para trocar qualquer peça, basta substituir o arquivo mantendo o nome.

## Fonte da estratégia
`PANCO_Estrategia_3_Frentes_MPDV_75LAB.pptx` (38 slides) — diagnóstico, arquitetura de leitura,
menu de MPDV, piloto, rollout, premissas de custo e governança. As faixas de custo do estudo
não foram levadas para o deck.
