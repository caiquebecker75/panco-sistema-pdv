# Panco · Sistema de presença no PDV — 75 LAB

Apresentação comercial em HTML (13 telas) da proposta estratégica da 75 LAB para a **Panco**:
um sistema de presença no ponto de venda que integra as três frentes do briefing —
**Linha Sobremesas**, **Lançamento Tortillas** e **Ilha Cash & Carry** — em um menu modular
de MPDV, com piloto, rollout por ondas e cenários de dimensionamento.

Inclui o **enxoval de categorização do ponto natural**: as 10 peças (placa, móbile aéreo, tag,
testeira, cubo e display de chão) que identificam as 8 categorias Panco na gôndola, lacuna
identificada no Trade Visit.

> **Sem valores.** O deck não exibe preço, orçamento ou faixa de investimento em nenhuma tela —
> o investimento é apresentado em proposta comercial separada. O único dado em R$ é o tamanho de
> mercado da tela 04 (fontes públicas ABIMAPI/ABRAS).

**No ar:** https://projetos.75lab.com.br/panco-sistema-pdv/

## Roteiro (começo · meio · fim)
| # | Tela | Papel |
|---|------|-------|
| 01 | A marca mais fácil de encontrar | capa, com a marca Panco em destaque |
| 02 | Três frentes, a mesma raiz | o desafio e as três perguntas do briefing |
| 03 | A tese: arquitetura de PDV | o insight (leitura em 10 m / 3–5 m / 0–1 m) |
| 04 | Por que agora | dados de mercado (ABIMAPI, ABRAS) |
| 05 | Jornada do shopper | a escada de leitura + os 4 key visuals |
| 06 | Trade Visit: cinco travas | o diagnóstico em campo, com o registro fotográfico por trava |
| 07 | Enxoval de categorização | as 10 peças que separam as 8 categorias no ponto natural |
| 08 | Antes e depois | três situações da loja, antes e com o sistema aplicado |
| 09 | As frentes na prática | Linha Sobremesas e Ilha Cash & Carry, lado a lado |
| 10 | Menu modular de MPDV | 14 peças em 3 níveis de ambição |
| 11 | O piloto como laboratório | cronograma (Trade Visit já concluído), números e KPIs |
| 12 | Dimensionamento e pacotes | 4 cenários de lojas/peças/prazo + 3 pacotes de contratação |
| 13 | Próximo passo | Trade Visit ✓ → Piloto → Rollout |

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

## Fotos do Trade Visit e antes/depois
`assets/tv-a1..e3.webp` são 15 fotos da visita (10/09/2026), três por trava da tela 06.
A tela 08 compara três situações: o *antes* usa `tv-a2`, `tv-a3` e `tv-e1`; o *depois* espera
`assets/dep-1.webp`, `dep-2.webp` e `dep-3.webp`. Enquanto esses arquivos não existirem, o painel
mostra um slot pontilhado; basta salvar as artes com esses nomes para elas entrarem automaticamente.

## Fonte da estratégia
`PANCO_Estrategia_3_Frentes_MPDV_75LAB.pptx` (38 slides) — diagnóstico, arquitetura de leitura,
menu de MPDV, piloto, rollout, premissas de custo e governança. As faixas de custo do estudo
não foram levadas para o deck.
