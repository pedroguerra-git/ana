# Landing Page — Clínica Premium (Emagrecimento & Saúde)

Projeto estático (HTML + CSS + JS) pronto para subir no GitHub.

## Estrutura

- `index.html` — página completa
- `assets/` — imagens e arquivos locais
  - `hero-2560x900.(jpg|webp)` e `hero-1920x700.(jpg|webp)` — **hero (fundo)**
  - `doctor-1536x1024.(jpg|webp)` — **foto da doutora**

> As demais imagens (suplementos, genética, etc.) ainda estão via URLs externas (Unsplash) como *sample*.

## Como publicar (sem terminal)

### Opção A — GitHub Pages

1. Crie um repositório no GitHub (ex.: `clinica-landing`).
2. Abra o repositório → **Add file → Upload files**.
3. Arraste **tudo** desta pasta (incluindo `index.html`, `assets/`, `README.md`) e clique em **Commit changes**.
4. No repositório, vá em **Settings → Pages**.
5. Em **Build and deployment**:
   - Source: **Deploy from a branch**
   - Branch: **main** / **root**
6. Salve. O GitHub vai mostrar a URL do site.

### Opção B — Netlify (upload manual)

1. Acesse o Netlify.
2. Em **Sites**, use **Add new site → Deploy manually**.
3. Arraste a pasta do projeto (ou o `.zip`).

## Personalização rápida

### 1) WhatsApp
No `index.html`, procure por:

- `const phone = "5500000000000";`

Troque para seu número (com DDI 55). Ex.: `5561999999999`.

### 2) Agendamento
Procure por `openScheduling()` e substitua o `alert()` pelo seu link (Calendly/Doctoralia/etc.).

### 3) Textos, nome da clínica e rodapé
Troque:
- Nome e slogan no topo
- Seção “A Doutora” (bio e credenciais)
- Endereço/telefone/e-mail no rodapé

### 4) Imagens externas (opcional)
Se quiser deixar 100% institucional, substitua as imagens externas dos blocos por arquivos em `assets/` e troque os `src` no `index.html`.

