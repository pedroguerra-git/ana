# ISOS Clinic — Landing Page

Landing page **estática** (HTML + CSS + JS) pronta para subir no GitHub.

## Estrutura
- `index.html` — página única
- `assets/` — imagens locais (inclui as fotos da doutora)

## Ajustes rápidos
Abra `index.html` e procure:

### 1) WhatsApp
Troque o número em:
```js
const phone = "5500000000000";
```

### 2) Link de agendamento
Troque o link em:
```js
const schedulingUrl = "COLE_AQUI_SEU_LINK";
```

## Publicar sem terminal (GitHub Pages)
1. Crie um repositório no GitHub.
2. Clique em **Add file → Upload files**.
3. Arraste todos os arquivos desta pasta e faça **Commit**.
4. Vá em **Settings → Pages**.
5. Em "Build and deployment", selecione:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/ (root)**
6. Aguarde o link aparecer em Pages.

## Observação sobre o vídeo do Hero
O Hero usa um vídeo hospedado externamente. Se você preferir um vídeo local:
- Coloque `assets/hero.mp4`
- Troque o `src` do `<source>` no `index.html`.
