# Skills de Instagram (sergebulaev/instagram-skills, licença MIT)

Copiadas em 2026-10-30 de https://github.com/sergebulaev/instagram-skills (só os arquivos Markdown).
As skills ficam em `.claude/skills/ig-*` e as referências compartilhadas aqui em `.claude/references/`.

Não trouxemos a pasta `lib/` nem os scripts Python. Por isso:
- Publicar via Publora (PUBLORA_API_KEY), gerar imagem via Pixfaro (PIXFARO_TOKEN) e ler dados via Apify (APIFY_TOKEN) NÃO rodam sozinhos.
- Sem essas chaves as skills só escrevem o texto (legenda, carrossel, hashtags, plano) para postarmos pelo nosso fluxo (meta/limite.py e Publicador fixo).
- Apify custa créditos: só usar com OK do Kevin.
