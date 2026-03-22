# PRIME-X (site estático)

Este site é estático (HTML/CSS/JS). Ele já contém:
- Seção de planos com links de contratação
- Seção de mídia (banners + vídeo)
- Botões para WhatsApp e e-mail

## Abrir no computador

Abra `index.html` no navegador.

## Rodar com servidor local (recomendado)

```powershell
cd C:\corretora-seguros-site
python -m http.server 5173
```

Acesse `http://localhost:5173`.

## Onde ficam os arquivos

- Página: `index.html`
- Banners: `assets/banners/`
- Vídeo: `assets/media/prime-x.mp4`

## Publicar (colocar no ar)

### Opção A — Netlify (mais fácil)

1. Crie uma conta no Netlify.
2. Em **Add new site** → **Deploy manually**.
3. Arraste a pasta `C:\corretora-seguros-site` para o Netlify.
4. Ele vai gerar um link (ex.: `https://...netlify.app`).

**Domínio próprio:** em Netlify → **Domain settings**, aponte seu domínio no seu provedor (DNS) e ative HTTPS.

### Opção B — GitHub Pages (gratuito)

1. Crie um repositório no GitHub.
2. Envie os arquivos da pasta `C:\corretora-seguros-site` para o repositório.
3. Vá em **Settings** → **Pages** e selecione a branch/pasta.

### Opção C — Hospedagem tradicional (Hostinger, Locaweb etc.)

1. Acesse o painel da hospedagem → **Gerenciador de arquivos**.
2. Envie o conteúdo da pasta `C:\corretora-seguros-site` para `public_html`.

## Checklist antes de publicar

- Confirme WhatsApp e e-mail (já configurados)
- Teste os 4 links de contratação na seção `#planos`
- Abra o vídeo e os banners na seção `#midia`
