# João Pessoa Inteligente

Simulação da **matriz de serviços públicos por bairro** — protótipo para o projeto de P&D / convênio PMJP–UFPB/LEMA.

## Demo

**[Abrir mapa interativo](https://diogodalbuquerque.github.io/jp/)**

Malha Filipeia (64 bairros) + população do Censo 2022 (IBGE). A matriz cruza importância, cobertura e qualidade para indicar **qual serviço** priorizar em cada território.

Serviços: educação infantil, saúde (APS), assistência social, segurança, iluminação, calçamento, saneamento básico e lazer.

> População e contagens de escolas/praças usam fontes públicas. Demais indicadores de cobertura/qualidade são **ilustrativos** para demonstrar a lógica da matriz.

## Local

```bash
cd simulacao
python3 -m http.server 8765
# http://127.0.0.1:8765/
```

## Conteúdo

- `index.html` / `data.js` — app do mapa (GitHub Pages)
- `simulacao/` — fontes GeoJSON e artefatos de construção
- `JP_Inteligente_Projeto_PD_Convenio_PMJP_UFPB_revisao.docx(.pdf)` — proposta do projeto
