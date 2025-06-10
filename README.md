# IPTV KRIPTON TOPTV Premium - Landing Page

## 📋 Descrição

Landing page otimizada para servidores de hospedagem web, promovendo o serviço IPTV KRIPTON TOPTV Premium com teste grátis por 24 horas.

## 🚀 Características

- ✅ **HTML5 Semântico** - Código limpo e otimizado
- ✅ **CSS Responsivo** - Funciona em todos os dispositivos
- ✅ **Performance Otimizada** - Carregamento rápido
- ✅ **SEO Otimizado** - Meta tags para melhor indexação
- ✅ **Compatível com Servidores** - Funciona em Apache, Nginx, etc.
- ✅ **Segurança** - Headers de segurança configurados

## 📁 Estrutura de Arquivos

```
/
├── index.html          # Página principal
├── styles.css          # Estilos CSS
├── .htaccess           # Configurações do servidor
└── README.md           # Este arquivo
```

## 🛠️ Instalação

### 1. Upload dos Arquivos

Faça upload de todos os arquivos para a pasta raiz do seu servidor web:

- `index.html`
- `styles.css`
- `.htaccess`

### 2. Configuração do Servidor

O arquivo `.htaccess` já está configurado com:

- **Compressão GZIP** - Reduz o tamanho dos arquivos
- **Cache do Navegador** - Melhora a performance
- **Headers de Segurança** - Protege contra ataques
- **URL Rewriting** - URLs limpas sem extensão .html

### 3. Personalização

#### Alterar Número do WhatsApp
Edite o arquivo `index.html` e substitua o número:
```html
<a href="https://wa.me/5513996756517" class="btn btn-primary">
```

#### Alterar Imagens
Substitua as URLs das imagens placeholder por suas próprias imagens:
```html
<img src="sua-imagem.jpg" alt="Descrição">
```

#### Alterar Cores
Edite o arquivo `styles.css` e modifique as variáveis de cor:
```css
/* Cor principal do WhatsApp */
color: #25D366;

/* Cor de fundo escura */
background: #1a1a1a;
```

## 🌐 Compatibilidade

### Servidores Suportados
- ✅ Apache
- ✅ Nginx
- ✅ LiteSpeed
- ✅ Cpanel
- ✅ Plesk
- ✅ Hostinger
- ✅ GoDaddy
- ✅ HostGator

### Navegadores Suportados
- ✅ Chrome (todas as versões)
- ✅ Firefox (todas as versões)
- ✅ Safari (todas as versões)
- ✅ Edge (todas as versões)
- ✅ Opera (todas as versões)

## 📱 Responsividade

A página é totalmente responsiva e se adapta a:

- 📱 **Mobile** (320px - 768px)
- 📱 **Tablet** (768px - 1024px)
- 💻 **Desktop** (1024px+)

## 🔧 Configurações Avançadas

### Habilitar HTTPS
Descomente as linhas no `.htaccess`:
```apache
RewriteCond %{HTTPS} off
RewriteRule ^(.*)$ https://%{HTTP_HOST}%{REQUEST_URI} [L,R=301]
```

### Redirecionar www para non-www
Descomente as linhas no `.htaccess`:
```apache
RewriteCond %{HTTP_HOST} ^www\.(.*)$ [NC]
RewriteRule ^(.*)$ https://%1/$1 [R=301,L]
```

### Páginas de Erro Personalizadas
Crie os arquivos:
- `404.html` - Página não encontrada
- `500.html` - Erro interno do servidor

## 📊 SEO e Performance

### Meta Tags Incluídas
- ✅ Title otimizado
- ✅ Description para SEO
- ✅ Keywords relevantes
- ✅ Open Graph (Facebook)
- ✅ Twitter Cards
- ✅ Favicon
- ✅ Viewport mobile

### Otimizações de Performance
- ✅ CSS minificado
- ✅ Imagens otimizadas
- ✅ Lazy loading
- ✅ Cache do navegador
- ✅ Compressão GZIP

## 🔒 Segurança

### Headers de Segurança Configurados
- ✅ X-Content-Type-Options
- ✅ X-Frame-Options
- ✅ X-XSS-Protection
- ✅ Referrer-Policy
- ✅ Permissions-Policy

## 📞 Suporte

Para suporte técnico ou dúvidas sobre a instalação, entre em contato através do WhatsApp disponível na página.

## 📄 Licença

Este projeto é de uso exclusivo para o serviço IPTV KRIPTON TOPTV Premium.

---

**Desenvolvido com ❤️ para máxima compatibilidade e performance** 
**Quem pode me ajuda com pix assim ja consigo colocar mais projotos aqui meu whatsapp e Pix para futuros projetos e (13) 99675-6517**
