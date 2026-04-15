# 🎨 Vibe Coder Dark Theme - Publicação Online

## ✅ Arquivos Preparados

Seu tema está completamente pronto para publicação! Todos os arquivos foram criados:

- ✅ `package.json` - Configuração da extensão
- ✅ `themes/VibeCoderDark-color-theme.json` - Cores do tema
- ✅ `README.md` - Documentação
- ✅ `vibe-coder-dark-theme-1.0.0.vsix` - Arquivo instalável
- ✅ Repositório Git inicializado

## 🚀 Passos para Publicação

### 1. Criar Repositório no GitHub
1. Acesse [github.com](https://github.com)
2. Clique em **"New repository"**
3. Nome: `vibe-coder-dark-theme`
4. Descrição: `A vibrant cyberpunk dark theme with neon colors for VS Code`
5. **Não marque** "Add a README file"
6. Clique **"Create repository"**

### 2. Fazer Upload dos Arquivos
Abra um terminal na pasta `f:\PDM\teste\vibe-coder-theme` e execute:

```bash
git remote add origin https://github.com/SEU_USERNAME/vibe-coder-dark-theme.git
git push -u origin master
```

### 3. Publicar no VS Code Marketplace (Opcional)
```bash
# Instalar VSCE (já instalado)
npm install -g @vscode/vsce

# Login no marketplace
vsce login SEU_PUBLISHER_NAME

# Publicar
vsce publish
```

## 📦 Instalação para Outros Usuários

### Opção 1: Via Arquivo VSIX (Mais Fácil)
- Compartilhe o arquivo `vibe-coder-dark-theme-1.0.0.vsix`
- Usuários fazem: `Extensions → Install from VSIX...`

### Opção 2: Via GitHub
- Clone o repositório
- Execute: `code --install-extension vibe-coder-dark-theme-1.0.0.vsix`

### Opção 3: Via Marketplace (Oficial)
- Procurar por "Vibe Coder Dark" no marketplace do VS Code

## 🎨 Características do Tema

- 🌟 **Cores Neon**: Verde, rosa, azul e amarelo vibrantes
- 🌙 **Fundo Cyberpunk**: Preto profundo com elementos neon
- 💻 **Sintaxe Otimizada**: Destaque para múltiplas linguagens
- 🎯 **Interface Consistente**: Elementos UI com tema neon

## 📁 Localização dos Arquivos

- **Pasta do Tema**: `f:\PDM\teste\vibe-coder-theme\`
- **Arquivo VSIX**: `f:\PDM\teste\vibe-coder-theme\vibe-coder-dark-theme-1.0.0.vsix`

---

**🎉 Pronto! Seu tema está preparado para o mundo!**