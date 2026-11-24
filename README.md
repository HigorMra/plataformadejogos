# Arcade — Plataforma de Jogos

Loja de demonstração feita em HTML, CSS e JavaScript.

## Acesso de teste

Usuário `michaelw` e senha `michaelwpass`, conta de demonstração existente na lista DummyJSON (id 2). O nome de exibição local está definido como Higor; os campos de username e e-mail exibem os dados devolvidos pelo endpoint.

## Fluxos

- Login via `POST https://dummyjson.com/auth/login`; token salvo no `localStorage`.
- Perfil via `GET https://dummyjson.com/auth/me` com `Authorization: Bearer`.
- Perfil, biblioteca, conquistas, loja de 40 jogos, busca, filtros e detalhes.
- Uma capa principal pública por jogo e pagamento de demonstração por cartão, Pix ou boleto. Os preços em BRL são indicativos, baseados em vitrines digitais consultadas; variam por edição, loja e promoção. A compra na demonstração não é real.

Os pagamentos são apenas simulados; o formulário não deve receber dados de cartão reais.

## Capas e créditos

As capas principais carregam imagens públicas dos catálogos oficiais: assets Steam para jogos vendidos na Steam, uma imagem oficial do site Minecraft.net para Minecraft e arte oficial da Epic Games para Fortnite. Elas são carregadas pela internet; cada capa usa a arte SVG local como reserva caso a imagem externa falhe. Os direitos das artes pertencem a seus respectivos estúdios e publicadoras; este projeto é uma demonstração acadêmica.
