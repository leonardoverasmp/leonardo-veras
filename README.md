# Site leonardoveras.com.br

Site pessoal do Leonardo Veras — publicado automaticamente pelo **GitHub Pages**.
Tudo mora aqui no GitHub. Sua máquina não guarda nada e não precisa estar ligada.

---

## 🌐 Como o site publica (automático)

- **Hospedagem:** GitHub Pages (nuvem).
- **Fonte:** este repositório, branch **`main`**, pasta raiz (`/`).
- **Domínio:** `www.leonardoveras.com.br` (o `leonardoveras.com.br` redireciona pra `www`).
- **Regra de ouro:** **salvar (commit) na `main` = site atualizado em ~1 minuto.** Não existe passo de "deploy" separado.

## ✏️ Como editar de qualquer lugar (sem instalar nada)

1. **Editor completo no navegador (recomendado):**
   abra **https://github.dev/leonardoverasmp/leonardo-veras**
   (ou, no repositório, aperte a tecla **`.`** ponto). É um VS Code no navegador.
   Edite → no painel de Source Control, escreva a mensagem → **Commit & Push**.

2. **Ajuste rápido de 1 arquivo:**
   abra o arquivo aqui no GitHub → ícone de **lápis** ✏️ → edite → **Commit changes**.

3. **Pelo celular:**
   app **GitHub** (iOS/Android) → este repo → abra o arquivo → edite → commit.

## 📁 Arquivos principais

| Arquivo | O que é |
|---|---|
| `index.html` | O site inteiro (HTML + CSS + JS num arquivo só). É bilíngue: cada texto tem `data-pt` e `data-en`. |
| `CNAME` | Fixa o domínio `www.leonardoveras.com.br`. **Não apagar.** |
| `.nojekyll` | Diz ao Pages pra servir os arquivos como estão. **Não apagar.** |
| `foto-leonardo.jpg`, `og-leonardo.jpg` | Imagens (retrato e preview de compartilhamento). |
| `leonardo-veras.pdf` | One-pager para download. |

> **Editar textos bilíngues:** ao trocar um texto no `index.html`, atualize as **3 partes** do elemento — `data-pt="..."`, `data-en="..."` e o texto visível entre as tags. Se mudar só uma, fica inconsistente ao trocar de idioma.

## ↩️ Reverter uma mudança

Todo o histórico fica salvo. Para desfazer:
- No GitHub: aba **Commits** → abra o commit → **Revert** (cria um commit que desfaz).
- Ou peça pro Claude Code: "reverte o último commit do site".

## 🔒 Infra (para referência)

- HTTPS forçado ✅ | Certificado aprovado ✅
- DNS apex → IPs do GitHub Pages (`185.199.108–111.153`); `www` → `leonardoverasmp.github.io`
- Pendência opcional de segurança: **verificar o domínio** na conta GitHub (Settings → Pages → "Verify domain") para blindar contra domain takeover — exige um registro TXT no provedor de DNS.
