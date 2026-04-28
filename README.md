# Baptistella · Brand Guide 2026

Manual de marca, posicionamento e comunicação da **Baptistella Alimentos** — fábrica familiar paulista de farinhas de milho e de rosca para empanamento, fundada em 19 de agosto de 1969 em Itatiba — SP.

> *Padrão de indústria, atendimento de família.*

---

## 🚀 Como abrir

Site estático em HTML, sem build, sem dependências.

```bash
# Opção 1 — abrir direto no browser
open index.html        # macOS
xdg-open index.html    # Linux
start index.html       # Windows

# Opção 2 — servir local (recomendado para evitar CORS)
python3 -m http.server 8000
# acesse http://localhost:8000

# Opção 3 — Node
npx serve .
```

---

## 🌐 Deploy

### GitHub Pages
1. Suba este repositório para o GitHub
2. **Settings → Pages** · escolha o branch `main`, raiz `/`
3. URL fica em `https://<usuário>.github.io/<repo>/`

### Netlify
- Arraste a pasta no [app.netlify.com/drop](https://app.netlify.com/drop)
- Ou conecte o repositório e publique sem build command

### Vercel
```bash
vercel
```
Aceite o default · framework: **Other**

### Cloudflare Pages
- Build command: vazio · Build output: `/`

---

## 📁 Estrutura

```
baptistella-brandguide/
├── index.html                    ← single-page com 17 capítulos
├── README.md
├── .gitignore
└── assets/
    ├── logo/                     ← variações do logotipo
    │   ├── logo.svg                    (vetorial original)
    │   ├── logo-main.png               (laranja institucional · uso geral)
    │   ├── logo-orange.png             (Pantone 7572 C #C65A1E)
    │   ├── logo-yellow.png             (Pantone 1235 C #F5AE16 · Liganex)
    │   ├── logo-red.png                (Pantone 1815 C #912014 · Empanex)
    │   ├── logo-beige.png              (Pantone 7506 C #F2C994 · apoio)
    │   ├── logo-white.png              (negativo · fundos escuros)
    │   └── logo-dark.png               (escuro · fundos claros)
    ├── produtos/                 ← banco de imagens de referência
    │   ├── coxinha-classica.png
    │   ├── coxinha-rotisserie.png
    │   ├── coxinha-empanex.png
    │   ├── frango-empanado-1.png
    │   ├── frango-empanado-2.png
    │   ├── bolinha-queijo.png
    │   ├── bolinhas-arroz.png
    │   ├── sushi-empanado.png
    │   └── croquetes.png
    └── aplicacoes/               ← mockups oficiais do manual
        ├── papelaria.jpg               (cartão · papel timbrado · fita)
        ├── cracha.jpg                  (crachá retrátil com B)
        ├── stand-feira.jpg             (backdrop Anutec/Apas/Fispal)
        └── capacete-epi.jpg            (EPI laranja com logo)
```

---

## 📖 Índice

**A Marca**  ·  Capa · História · Essência · Valores
**Posicionamento**  ·  Brand Statement · Públicos B2B · Linhas · Diferenciação
**Identidade**  ·  Logotipo · Paleta · Tipografia · Fotografia
**Voz**  ·  Tom de voz · Dicionário
**Aplicação**  ·  LinkedIn · Aplicações reais · Checklist · Downloads

Todos os 17 capítulos são acessíveis pelo menu lateral fixo.

---

## 🎨 Paleta oficial

Cores extraídas do Manual de Marca original (Pantones registrados):

| Cor | HEX | Pantone | Uso |
|-----|-----|---------|-----|
| Laranja Baptistella | `#C65A1E` | 7572 C | Cor-âncora · logo · CTAs |
| Amarelo Liganex     | `#F5AE16` | 1235 C | Linha 02 · liga e pré-empanamento |
| Vermelho Empanex    | `#912014` | 1815 C | Linha 03 · Empanex premium |
| Marrom Batpronto    | `#753D2A` | 7596 C | Linha 04 · misturas prontas |
| Bege Areia          | `#F2C994` | 7506 C | Apoio · fundos suaves |

---

## ✏️ Como editar

O HTML é vanilla — sem framework. Edite `index.html` direto.

**Tokens CSS** (linha ~14): variáveis de cor, gradientes e tipografia em `:root` no topo.

**Conteúdo**: cada capítulo é uma `<section id="...">`. Para mudar texto, edite o HTML diretamente. Para trocar imagens, substitua os arquivos em `assets/` mantendo o mesmo nome.

**Adicionar nova seção**: adicione um item ao menu lateral (`<a href="#novo">`) e um `<section id="novo">` na ordem desejada.

---

## 📜 Licença

Conteúdo proprietário da Baptistella Alimentos · 2026. Uso interno e parceiros autorizados.

---

## 📞 Contato

- **Site:** [baptistella.com.br](https://www.baptistella.com.br)
- **Instagram:** [@baptistellaalimentos](https://www.instagram.com/baptistellaalimentos)
- **E-mail:** comercial@baptistella.com.br
- **Endereço:** Rua Jundiaí, 947 — Centro · Itatiba — SP · 13.250-200
- **Telefone:** (11) 4487-6630
- **E-mail:** sac@baptistella.com.br
