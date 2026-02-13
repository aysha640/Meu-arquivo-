# 💬 Chat em Tempo Real

Um chat privado em tempo real com suporte a mensagens de texto, fotos e vídeos.

## 🔐 Senha de Acesso

**Senha:** `0000`

## 🎨 Temas Disponíveis

- **index.html** - Tema Vermelho/Preto (padrão)
- **chat-azul.html** - Tema Preto/Azul (alternativo)

## ✨ Funcionalidades

- ✅ Senha de proteção (0000)
- ✅ Mensagens em tempo real com Firebase
- ✅ Envio de fotos e vídeos via Cloudinary
- ✅ Nome de usuário personalizável
- ✅ Design responsivo (funciona em mobile)
- ✅ Animações suaves
- ✅ Indicador de horário nas mensagens
- ✅ Scroll automático para novas mensagens

## 🚀 Como Usar

### Opção 1: Abrir localmente
1. Baixe o arquivo ZIP
2. Extraia os arquivos
3. Abra o arquivo `index.html` no navegador
4. Digite a senha: **0000**
5. Comece a conversar!

### Opção 2: Hospedar no GitHub Pages

1. Crie um repositório no GitHub
2. Faça upload dos arquivos
3. Vá em **Settings** > **Pages**
4. Selecione a branch **main** e a pasta **/ (root)**
5. Clique em **Save**
6. Aguarde alguns minutos e acesse: `https://seu-usuario.github.io/nome-do-repositorio`

### Opção 3: Outros serviços de hospedagem gratuita

- **Netlify**: Arraste a pasta para netlify.com/drop
- **Vercel**: Importe o repositório do GitHub
- **Firebase Hosting**: Use `firebase deploy`

## 🔧 Configuração

As credenciais do Firebase e Cloudinary já estão configuradas nos arquivos HTML:

### Firebase (já configurado)
- Database URL: https://chat-6ac88-default-rtdb.firebaseio.com
- Project ID: chat-6ac88

### Cloudinary (já configurado)
- Cloud Name: drgtsc5cx
- Upload Preset: chatbox

## 📱 Compatibilidade

- ✅ Chrome, Firefox, Safari, Edge
- ✅ Desktop e Mobile
- ✅ Tablets

## ⚠️ Importante

1. **Segurança do Firebase**: 
   - Configure as regras de segurança no Firebase Console
   - Vá em "Realtime Database" > "Regras"
   - Use regras básicas de autenticação se necessário

2. **Limite de Upload**:
   - Fotos e vídeos: máximo 300MB por arquivo
   - Formatos suportados: JPG, PNG, GIF, MP4, MOV, AVI, etc.

3. **Privacidade**:
   - Qualquer pessoa com a senha (0000) pode acessar o chat
   - Para maior segurança, considere mudar a senha no código

## 🛠️ Como Mudar a Senha

Abra o arquivo `index.html` ou `chat-azul.html` e procure por:

```javascript
if (password === '0000') {
```

Substitua `'0000'` pela senha desejada.

## 📝 Estrutura do Projeto

```
chat-realtime/
├── index.html          # Versão vermelho/preto (principal)
├── chat-azul.html      # Versão preto/azul (alternativa)
└── README.md           # Este arquivo
```

## 💡 Dicas de Uso

- O nome de usuário pode ser alterado a qualquer momento
- Clique nas imagens para abri-las em tamanho real
- Pressione Enter para enviar mensagens rapidamente
- O chat sincroniza automaticamente em todos os dispositivos conectados

## 🐛 Problemas Comuns

**Mensagens não aparecem?**
- Verifique sua conexão com a internet
- Abra o Console do navegador (F12) para ver erros
- Confirme que o Firebase Realtime Database está ativo

**Upload de arquivo não funciona?**
- Verifique o tamanho do arquivo (máx 10MB)
- Confirme que o Cloudinary Upload Preset está configurado como "Unsigned"

**Chat não carrega?**
- Limpe o cache do navegador
- Tente em modo anônimo/privado
- Verifique se o JavaScript está habilitado

## 📞 Suporte

Se tiver problemas:
1. Verifique o Console do navegador (F12)
2. Confirme que o Firebase Realtime Database está ativo
3. Verifique se o Cloudinary Upload Preset está público (Unsigned)

## 🎉 Pronto!

Seu chat está pronto para uso! Compartilhe o link com quem você quiser dar acesso (não esqueça de passar a senha 0000).

Divirta-se! 🚀💬
