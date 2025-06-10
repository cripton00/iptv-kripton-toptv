# 🚀 Instruções para Testar o Site IPTV

## ✅ Verificação Rápida

### 1. Teste Básico
Acesse: `http://localhost/index%20iptv/teste.html`

Se aparecer a página de teste com "Status: Funcionando!", o servidor está OK.

### 2. Página Principal
Acesse: `http://localhost/index%20iptv/index.html`

Deve aparecer a landing page completa do IPTV KRIPTON.

## 🔧 Solução de Problemas

### Problema: Página em branco
**Solução:**
1. Verifique se o XAMPP está rodando
2. Acesse: `http://localhost/`
3. Se não funcionar, reinicie o Apache no XAMPP

### Problema: CSS não carrega
**Solução:**
1. Verifique se o arquivo `styles.css` existe
2. Abra o console do navegador (F12)
3. Veja se há erros de carregamento

### Problema: Imagens não aparecem
**Solução:**
1. As imagens são externas (placeholder.com)
2. Verifique sua conexão com a internet
3. As imagens carregarão automaticamente

### Problema: Botões não funcionam
**Solução:**
1. Os botões abrem WhatsApp
2. Certifique-se de ter o WhatsApp instalado
3. Teste clicando nos botões

## 📱 Teste em Diferentes Dispositivos

### Desktop
- Chrome, Firefox, Safari, Edge
- Resolução: 1920x1080, 1366x768

### Mobile
- Abra no celular: `http://SEU_IP/index%20iptv/`
- Ou use o modo responsivo do navegador (F12)

### Tablet
- Teste em diferentes orientações
- Verifique se os botões são clicáveis

## 🌐 Para Produção

### Upload para Hospedagem
1. Faça upload de todos os arquivos para a raiz do servidor
2. Acesse: `https://seudominio.com/`
3. O site deve funcionar automaticamente

### Configurações Importantes
- ✅ `index.html` - Página principal
- ✅ `styles.css` - Estilos
- ✅ `.htaccess` - Configurações do servidor
- ✅ `404.html` - Página de erro

## 📞 Suporte

Se ainda houver problemas:
1. Verifique o console do navegador (F12)
2. Teste a página `teste.html` primeiro
3. Verifique se todos os arquivos estão na pasta correta

---

**🎯 Objetivo:** Ter uma landing page funcional e responsiva para o IPTV KRIPTON! 