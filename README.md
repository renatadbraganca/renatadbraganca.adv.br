# Duarte Bragança Saúde Legal

Landing page profissional para Renata Bragança — advogada em Direito Médico, Hospitalar e da Saúde.

## 📋 Instruções para GitHub Pages

### Passo 1: Criar repositório no GitHub

1. Acesse [github.com](https://github.com) e faça login (ou crie conta)
2. Clique em **"New"** (canto superior esquerdo)
3. Nome do repositório: `renatabraganca.adv.br` (ou outro nome que preferir)
4. Descrição: "Landing page - Renata Bragança | Direito Médico e da Saúde"
5. Selecione **"Public"**
6. Clique em **"Create repository"**

### Passo 2: Upload dos arquivos

1. Na página do repositório, clique em **"Add file"** → **"Upload files"**
2. Arraste os 2 arquivos:
   - `index.html` (sua landing page)
   - `CNAME` (arquivo de configuração de domínio)
3. Commit message: `Initial commit - Landing page`
4. Clique em **"Commit changes"**

### Passo 3: Habilitar GitHub Pages

1. Vá para **Settings** (abas no topo do repositório)
2. Menu esquerdo → **"Pages"**
3. Source: Selecione **"Deploy from a branch"**
4. Branch: **main** | Pasta: **/root**
5. Clique em **"Save"**

Pronto! GitHub vai gerar um URL como: `https://seu-usuario.github.io/renatabraganca.adv.br/`

### Passo 4: Registrar domínio .adv.br

1. Acesse [registro.br](https://www.registro.br)
2. Procure por `renatabraganca.adv.br`
3. Preencha o formulário com dados de Renata (CPF + inscrição OAB)
4. Finalize o pagamento (~R$50-60/ano)

### Passo 5: Vincular domínio ao GitHub Pages

Após registrar o domínio:

1. Acesse [registro.br](https://www.registro.br) → Meus domínios
2. Clique em `renatabraganca.adv.br` → Configurar DNS
3. Adicione os registros DNS do GitHub Pages:
   - **Tipo A**: Apontam para `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - **Tipo CNAME**: `seu-usuario.github.io`

4. Volta no GitHub → Settings → Pages
5. Em "Custom domain", coloque: `renatabraganca.adv.br`
6. Clique em **"Save"**
7. Aguarde alguns minutos para o DNS propagar
8. Marque **"Enforce HTTPS"** (segurança)

Pronto! Seu domínio estará ativo em `https://renatabraganca.adv.br`

---

## 📝 Como atualizar a página depois

1. Faça login no GitHub
2. Abra o repositório
3. Clique no arquivo `index.html`
4. Clique no ícone de lápis (Edit)
5. Faça suas mudanças
6. Scroll para baixo → **"Commit changes"**
7. A página atualiza automaticamente em segundos!

---

## ⚡ Suporte rápido

**Problema**: Domínio não funciona após DNS
- Aguarde 24-48h para propagação completa do DNS

**Problema**: Página não carrega
- Verifique se o arquivo se chama `index.html` (case-sensitive)
- Confirme que está na raiz do repositório (não dentro de pasta)

**Problema**: Precisa fazer mudanças rápidas
- Edite direto no GitHub (não precisa baixar, clonar, ou usar terminal)

---

## 💡 Dicas

- O arquivo `CNAME` garante que o domínio seja lembrado pelo GitHub Pages
- Se trocar de repositório depois, não perca o arquivo `CNAME`
- GitHub Pages é 100% gratuito — só precisa pagar pelo domínio
- HTTPS é automático e obrigatório (segurança)

---

**Criado**: Setembro de 2026  
**Advogada**: Renata Bragança - Direito Médico, Hospitalar e da Saúde
