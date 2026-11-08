# Black Friday do Aluno: Aulas para Professores

Página de vendas estática (HTML + CSS), publicada na Vercel.

- `index.html`: a página, com o player do vídeo e o repasse de UTMs para o checkout.
- `assets/css/style.css`: estilos (desktop e celular).
- `assets/video/vsl.mp4`: vídeo de vendas (540×960, H.264, pronto para começar a tocar antes de baixar inteiro).
- `assets/img/`: fotos do Max, capa do vídeo e prints de depoimentos.

## UTMs

O script no fim do `index.html` lê da URL da página `utm_*`, `a` (afiliado Eduzz), `src`, `sck`, `fbclid`, `gclid` e `ttclid`, guarda na sessão e acrescenta tudo aos links do checkout (`a.js-checkout`).

Exemplo: `https://SEU-DOMINIO/?utm_source=instagram&utm_campaign=bf` leva o comprador para
`https://chk.eduzz.com/Z0B1XYPJ9A?utm_source=instagram&utm_campaign=bf`.

## Trocar o link do checkout

Procure por `chk.eduzz.com/Z0B1XYPJ9A` no `index.html` e troque em todos os botões.
