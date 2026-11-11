# RADAR — site estático

Site em português para apresentar tendências internacionais e comparar sinais de adoção nos Estados Unidos e no Brasil.

## Arquivos

- `index.html` — estrutura e conteúdo do site.
- `styles.css` — identidade visual e layout responsivo.
- `app.js` — navegação interna, busca, filtros, páginas de tendências e favoritos.

## Como funciona

- Site estático: não precisa de servidor, banco de dados ou processo de compilação.
- Navegação por hash (`#/inicio`, `#/explorar`, `#/brasil`, `#/metodo`, `#/tendencia/oculos` etc.).
- Os cartões abrem páginas internas em vez de rolar a mesma página.
- Busca e filtros funcionam no navegador.
- Favoritos ficam salvos localmente no navegador usando `localStorage`.
- Os links de fontes abrem as publicações originais em outra aba.

## Atualização editorial

Os números e análises desta versão têm data de corte de 11/11/2026. Atualize `trends` em `app.js` e os cartões/tabela de `index.html` quando publicar uma nova edição. Mantenha a métrica, a fonte, o período e a data de consulta juntos. Não trate volume de buscas como vendas nem disponibilidade de um produto como popularidade.

## Fontes usadas nesta edição

- IDC — Smart Glasses Growth Cools to 35%: https://www.idc.com/resource-center/blog/smart-glasses-growth-cools-to-35-as-meta-doubles-down-on-distribution/
- Meta Brasil — Ray-Ban Meta Gen 2 chegam ao Brasil: https://about.fb.com/br/news/2025/09/oculos-ray-ban-meta-gen-2-chegam-ao-brasil/
- Meta — novas linhas de óculos com IA (set. 2026): https://about.fb.com/br/news/2026/09/apresentamos-os-ray-ban-meta-audio-e-a-nossa-linha-mais-completa-de-oculos-com-ia-ate-hoje/
- TokConnect — TikTok product search snapshot (11/11/2026): https://tokconnect.com/trends/products/
- Google — Search data and “touch grass” trends: https://blog.google/products-and-platforms/products/search/touch-grass-trends/
- NextBig Pulse — Mahjong trend: https://nextbig.io/trend/mahjong
- WBUR — Why Mahjong is surging in popularity: https://www.wbur.org/hereandnow/2026/04/29/mahjong-popularity
- PYMNTS — Brazil Edition: The New Brazilian Shopper: https://www.pymnts.com/report/playbook/global-digital-shopping-index-new-brazilian-shopper/
- PYMNTS — Global Digital Shopping Index: https://www.pymnts.com/report/study/global-digital-shopping-ai-powered-shopper/
- Exploding Topics — kitchen trends: https://explodingtopics.com/kitchen-topics
