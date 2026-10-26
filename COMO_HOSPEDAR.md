# Passo a Passo para Hospedagem e Configuração do Painel (CMS)

Como todo o código (HTML, JSON e configurações do painel) já está 100% pronto no seu computador, o próximo passo é colocar o site no ar.

Existem duas formas principais. Para o seu caso (que deseja acessar usando Email e Senha), a **Opção 1 (Netlify)** é a mais recomendada.

---

## OPÇÃO 1: NETLIFY (Recomendado - Login por Email e Senha)

O Netlify é gratuito e já possui um sistema nativo perfeito para gerenciar senhas e e-mails do painel de controle.

### Passo 1: Subir o código para o GitHub
1. Crie uma conta gratuita no [GitHub](https://github.com/).
2. No canto superior direito, clique em **"+"** e depois em **"New repository"**.
3. Dê o nome de `portfolio-arquitetura` (ou o que preferir), deixe como **Public** ou **Private** e clique em **Create repository**.
4. Na tela seguinte, clique no link azul que diz **"uploading an existing file"**.
5. Arraste **TODOS os arquivos e pastas** do seu site (a pasta `admin`, `data`, `Projetos`, `index.html`, etc.) para dentro dessa janela no GitHub.
6. Clique no botão verde **"Commit changes"**. Pronto! O código está nas nuvens.

### Passo 2: Publicar o site no Netlify
1. Crie uma conta gratuita no [Netlify](https://www.netlify.com/).
2. No painel inicial do Netlify, clique em **"Add new site"** e depois em **"Import an existing project"**.
3. Escolha a opção **GitHub** e autorize a conexão.
4. Selecione o repositório `portfolio-arquitetura` que você acabou de criar.
5. Role até o fim da página e clique em **"Deploy site"**. (Em alguns segundos, o site estará no ar e você receberá um link).

### Passo 3: Ativar o Sistema de Login (Identity)
1. No painel do seu site no Netlify, vá no menu superior em **Site configuration** > **Identity** e clique no botão **Enable Identity**.
2. Desça a página até a seção **Registration preferences** e marque a opção **Invite only** (para que ninguém além de você possa criar conta no seu site).
3. Role mais para baixo até **Services** > **Git Gateway** e clique em **Enable Git Gateway**. (Isso permite que o painel salve os dados no seu GitHub).

### Passo 4: Criar o seu Login
1. Ainda na aba **Identity** no painel do Netlify, clique no botão **Invite users**.
2. Digite o seu email (ex: `jmeuren.arq@gmail.com`) e envie.
3. Você receberá um e-mail. **Clique no link** presente no e-mail.
4. O seu site vai abrir. Digite uma senha forte e salve.

🎉 **Tudo Pronto!** Agora você pode acessar `seulinkdonetlify.com/admin`, digitar seu email e a senha que acabou de criar, e adicionar novos projetos pelo painel visual!

---

## OPÇÃO 2: VERCEL (Login com conta do GitHub)

Se por algum motivo você preferir a Vercel, o processo de subir o site é quase o mesmo, mas o login no painel será diferente.

### Passo 1: Subir para o GitHub e Vercel
1. Crie a conta no GitHub e faça o upload dos arquivos (Exatamente como o Passo 1 do Netlify).
2. Crie uma conta gratuita na [Vercel](https://vercel.com/).
3. Clique em **"Add New Project"**, conecte seu GitHub e importe o repositório `portfolio-arquitetura`.
4. Clique em **"Deploy"**.

### Passo 2: Configurar o Login OAuth
Como a Vercel não tem o botão mágico do Netlify Identity, o acesso ao painel CMS será feito autorizando o seu próprio GitHub.
1. Será necessário instalar uma integração ou configurar um servidor OAuth simples (como o *Decap CMS Vercel OAuth* disponível na comunidade).
2. Como isso requer configurações avançadas de segurança de API, **sugerimos fortemente o uso do Netlify** para uma experiência mais fluida sem necessidade de programação extra.
