# Portfolio de Julio Cesar Fernandes

Site profissional de currículo e portfolio desenvolvido para hospedar no GitHub Pages.

## 🌐 Sobre o Projeto

Este é um site de portfolio pessoal moderno e responsivo que apresenta minhas competências, experiência profissional, formação académica e projetos desenvolvidos. O site foi criado com foco em design clean, performance e acessibilidade.

## ✨ Características

- **Design Responsivo**: Funciona perfeitamente em dispositivos móveis, tablets e desktops
- **Navegação Suave**: Scroll suave entre seções com menu fixo
- **Animações**: Efeitos visuais sutis ao fazer scroll pela página
- **SEO Otimizado**: Meta tags e estrutura semântica para melhor indexação
- **Performance**: Carregamento rápido e otimizado
- **Acessibilidade**: Implementação de boas práticas de acessibilidade web

## 📁 Estrutura de Arquivos

```
portfolio/
├── index.html          # Página principal com todo o conteúdo
├── style.css           # Estilos e design responsivo
├── script.js           # Funcionalidades interativas
├── profile.jpg         # Foto de perfil
├── Profile.pdf         # Currículo em PDF para download
└── README.md           # Este arquivo
```

## 🚀 Como Hospedar no GitHub Pages

### Passo 1: Criar um Repositório no GitHub

1. Acesse [GitHub](https://github.com) e faça login
2. Clique no botão **"New"** ou **"+"** no canto superior direito e selecione **"New repository"**
3. Nomeie o repositório como: `seu-usuario.github.io`
   - Exemplo: `sourcenaiomiocc-creator.github.io`
   - **Importante**: O nome deve ser exatamente assim para funcionar como site principal
4. Marque o repositório como **Public**
5. Clique em **"Create repository"**

### Passo 2: Configurar o Git (se ainda não tiver)

Se você nunca usou Git antes, configure suas credenciais:

```bash
git config --global user.name "Seu Nome"
git config --global user.email "seu-email@gmail.com"
```

### Passo 3: Subir os Arquivos para o GitHub

Abra o terminal/cmd na pasta onde estão os arquivos e execute:

```bash
# Inicializar o repositório Git
git init

# Adicionar todos os arquivos
git add .

# Fazer o primeiro commit
git commit -m "Primeiro commit: Site de portfolio"

# Conectar ao repositório remoto (substitua pelo seu URL)
git remote add origin https://github.com/seu-usuario/seu-usuario.github.io.git

# Enviar os arquivos para o GitHub
git push -u origin main
```

**Nota**: Se o GitHub solicitar `master` ao invés de `main`, use:
```bash
git branch -M main
git push -u origin main
```

### Passo 4: Ativar o GitHub Pages

1. No seu repositório do GitHub, clique em **Settings** (Configurações)
2. No menu lateral, clique em **Pages**
3. Em **Source**, selecione:
   - Branch: `main`
   - Folder: `/ (root)`
4. Clique em **Save**
5. Aguarde alguns minutos (pode levar até 10 minutos)
6. Seu site estará disponível em: `https://seu-usuario.github.io`

## 🔧 Personalizações

### Atualizar Informações

Para atualizar qualquer informação no site:

1. Edite o arquivo `index.html`
2. Faça as alterações necessárias
3. Salve o arquivo
4. Suba as mudanças para o GitHub:

```bash
git add .
git commit -m "Atualizar informações do portfolio"
git push
```

### Mudar Cores

As cores principais do site podem ser alteradas no arquivo `style.css`, na seção `:root`:

```css
:root {
    --primary-color: #2563eb;     /* Cor principal (azul) */
    --secondary-color: #1e40af;   /* Cor secundária */
    --accent-color: #3b82f6;      /* Cor de destaque */
    /* ... */
}
```

### Adicionar Novos Projetos

No arquivo `index.html`, localize a seção `<!-- Projects Section -->` e adicione um novo card seguindo o padrão existente.

## 📱 Compatibilidade

- ✅ Chrome (versões recentes)
- ✅ Firefox (versões recentes)
- ✅ Safari (versões recentes)
- ✅ Edge (versões recentes)
- ✅ Dispositivos móveis (iOS e Android)

## 🎨 Tecnologias Utilizadas

- **HTML5**: Estrutura semântica
- **CSS3**: Estilização moderna com Flexbox e Grid
- **JavaScript ES6+**: Interatividade e animações
- **Font Awesome**: Ícones profissionais
- **GitHub Pages**: Hospedagem gratuita

## 📄 Licença

Este projeto é de uso pessoal. Sinta-se livre para usar como referência, mas por favor, personalize com suas próprias informações.

## 📞 Contato

- **Email**: sourcenaiomiocc@gmail.com
- **LinkedIn**: [linkedin.com/in/julio-cesar-fernandes-b69338343](https://linkedin.com/in/julio-cesar-fernandes-b69338343)
- **GitHub**: [github.com/sourcenaiomiocc-creator](https://github.com/sourcenaiomiocc-creator)

## 🌟 Recursos Adicionais

### Domínio Personalizado (Opcional)

Se você quiser usar um domínio personalizado (ex: `www.juliofernardes.com`):

1. Compre um domínio em sites como Namecheap, GoDaddy, etc.
2. No GitHub, vá em Settings > Pages
3. Em "Custom domain", adicione seu domínio
4. Configure os DNS do seu domínio para apontar para o GitHub Pages:
   ```
   A     185.199.108.153
   A     185.199.109.153
   A     185.199.110.153
   A     185.199.111.153
   CNAME seu-usuario.github.io
   ```

### Análise de Tráfego

Para adicionar Google Analytics:

1. Crie uma conta no [Google Analytics](https://analytics.google.com)
2. Obtenha seu código de rastreamento
3. Adicione o código no `<head>` do `index.html`

### SEO

Para melhorar o SEO:

1. Adicione um arquivo `sitemap.xml`
2. Crie um arquivo `robots.txt`
3. Configure o Google Search Console
4. Compartilhe o site nas redes sociais

---

**Desenvolvido com dedicação por Julio Cesar Fernandes** 💙
