# Minacapelle · Cardápio digital

Cardápio digital da Minacapelle Padaria & Confeitaria (Santana de Parnaíba, SP). Tem sacola, checkout em 3 etapas e orçamento para empresas, e envia tudo pelo WhatsApp.

- Site estático: `index.html` + `app.js`, sem build e sem back-end
- Cabeçalhos de segurança em `vercel.json`
- Número que recebe os pedidos: constante `WHATSAPP` no início do `app.js`
- Taxa de entrega por distância: `LOJA` (coordenadas), `FAIXAS_ENTREGA` (km e valor), `FRETE_GRATIS_ACIMA` e `FATOR_TRAJETO` no `app.js`. O endereço vem do CEP pelo ViaCEP, e a distância é calculada com o OpenStreetMap

Desenvolvido por Orbyn Tech.
