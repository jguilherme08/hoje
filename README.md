![X-Ray Editor Banner](https://img.shields.io/badge/X--Ray-Image%20Editor-00ff88?style=for-the-badge&logo=image&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![License MIT](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

**Um editor de imagens avançado com efeitos de transparência e revelação através de tecidos. Ideal para criação de efeitos artísticos, simulações visuais e fins educacionais.**

> ⚠️ **Aviso Importante**: Este projeto é destinado exclusivamente para fins educacionais, artísticos e de pesquisa. Use de forma responsável e ética.

## 🚀 Demos Online

Escolha a versão que melhor se adequa às suas necessidades:

| Versão | Descrição | Link |
|--------|-----------|------|
| **Completa** | Interface moderna com todos os recursos | **[📱 Demo Completo](./demo-completo.html)** |
| **GitHub Style** | Interface limpa estilo GitHub | **[🐙 GitHub Demo](./github-demo.html)** |
| **Médico** | Simulador com tema hospitalar | **[🩻 Editor Médico](./xray-fabric-editor.html)** |
| **Código** | Tema dark para desenvolvedores | **[💻 Editor Código](./xray-editor.html)** |
| **Clean** | Versão minimalista e responsiva | **[✨ Clean Demo](./index-clean.html)** |
| **Original** | Versão com tema escuro X-Ray | **[🔬 Original](./index.html)** |

## ✨ Funcionalidades

- 📸 **Upload de Imagens**: Suporte para JPG, PNG, GIF e WebP (até 10MB)
- 🎨 **Presets Rápidos**: 6 configurações predefinidas para diferentes tipos de tecido
- ⚙️ **Controles Manuais**: Ajuste fino de brilho, contraste, saturação, nitidez e transparência
- 🖱️ **Drag & Drop**: Interface intuitiva para upload de imagens
- 💾 **Download**: Baixe suas imagens editadas em alta qualidade
- 📋 **Copiar**: Copie imagens diretamente para a área de transferência
- ⌨️ **Atalhos**: Ctrl+S (baixar), Ctrl+R (resetar)
- 📱 **Responsivo**: Funciona perfeitamente em desktop e mobile
- 🔒 **Privacidade**: Processamento 100% local, sem upload para servidores

## 🚀 Instalação Rápida

### Opção 1: Download Direto
```bash
# Clone o repositório
git clone https://github.com/SEU_USUARIO/x-ray-image-editor.git

# Entre na pasta
cd x-ray-image-editor

# Abra qualquer arquivo HTML no navegador
start github-demo.html
```

### Opção 2: GitHub Pages
Acesse diretamente: `https://SEU_USUARIO.github.io/x-ray-image-editor/github-demo.html`

### Opção 3: Servidor Local
```bash
# Com Python 3
python -m http.server 8000

# Com Node.js
npx serve .

# Acesse: http://localhost:8000
```

## 🎯 Presets Disponíveis

| Preset | Descrição | Uso Recomendado |
|--------|-----------|-----------------|
| 🩱 Ultra Leve | Máxima transparência | Tecidos muito finos |
| 🩳 Tecido Leve | Transparência moderada | Roupas de verão |
| 👕 Intermediário | Balanceado | Roupas casuais |
| 🧥 Tecido Pesado | Transparência mínima | Roupas de inverno |
| 📄 Texto Oculto | Alto contraste | Revelar texto oculto |
| 🎭 Artístico | Efeito criativo | Arte e design |

## 🛠️ Como Usar

### Método 1: Navegador Local
1. **Baixe ou clone o repositório**
2. **Abra qualquer arquivo HTML** em seu navegador:
   - `demo-completo.html` - Interface moderna completa
   - `github-demo.html` - Estilo GitHub limpo
   - `index-clean.html` - Versão minimalista
   - `index.html` - Tema escuro original

### Método 2: GitHub Pages
1. **Acesse diretamente pelo GitHub Pages** (se configurado)
2. **Escolha a demo desejada** na tabela acima

### Fluxo de Uso
1. **Faça upload de uma imagem** clicando em "Selecionar Imagem" ou arrastando
2. **Escolha um preset** para aplicar efeitos rapidamente
3. **Ajuste manualmente** os controles para personalizar
4. **Baixe o resultado** ou copie para a área de transferência

### Atalhos de Teclado
- **Ctrl + S**: Baixar imagem editada
- **Ctrl + R**: Resetar todos os controles

## 📁 Estrutura do Projeto

```
📦 X-Ray Image Editor
├── 📄 demo-completo.html        # ⭐ Demo principal completa
├── 📄 github-demo.html          # 🐙 Versão estilo GitHub
├── 📄 index-clean.html          # ✨ Versão minimalista
├── 📄 index.html                # 🔬 Versão original (tema escuro)
├── 📄 xray-editor.html          # 💻 Editor de código com tema X-ray
├── 📄 xray-fabric-editor.html   # 🏥 Editor médico especializado
├── 📄 script.js                 # 🔧 Scripts principais funcionais
├── 📄 xray-editor.js            # 💾 Scripts do editor de código
├── 📄 xray-fabric-editor.js     # 🩺 Scripts do editor médico
└── 📄 README.md                 # 📖 Este arquivo
```

## 🎨 Características Visuais

### Interface Limpa e Moderna
- Design responsivo com gradientes suaves
- Controles intuitivos e organizados
- Feedback visual para todas as interações

### Visualização em Tempo Real
- Preview instantâneo das alterações
- Canvas otimizado para performance
- Filtros aplicados dinamicamente

### Experiência do Usuário
- Drag & drop funcional
- Loading indicators
- Botões com hover effects
- Layout adaptativo para mobile

## 🔧 Tecnologias Utilizadas

### Frontend
- **HTML5 Canvas** - Manipulação avançada de imagens
- **CSS3 Grid/Flexbox** - Layout responsivo moderno
- **JavaScript ES6+** - Programação assíncrona e orientada a objetos
- **Web APIs**:
  - `FileReader API` - Upload e leitura de arquivos
  - `Canvas 2D Context` - Renderização e filtros
  - `Drag and Drop API` - Interface intuitiva
  - `Download API` - Exportação de resultados

### Algoritmos de Processamento
- **Manipulação de Pixels RGB/RGBA**
- **Filtros de Convolução**
- **Transformações de Luminância**
- **Aplicação de Matrizes de Cor**
- **Algoritmos de Suavização**

### Performance
- **Web Workers** (planejado) - Processamento em background
- **OffscreenCanvas** (planejado) - Renderização otimizada
- **Lazy Loading** - Carregamento sob demanda
- **Debounced Updates** - Atualizações otimizadas

## 📸 Screenshots

### Interface Principal
A interface apresenta dois painéis principais:
- **Painel de Controles**: Upload, presets e ajustes manuais
- **Área de Canvas**: Visualização da imagem com efeitos aplicados

### Presets em Ação
Cada preset aplica uma combinação específica de filtros para simular diferentes tipos de transparência através de tecidos.

## 🎯 Casos de Uso

### 🎨 Criação Artística
- **Arte Digital**: Criação de efeitos visuais únicos
- **Design Gráfico**: Manipulação artística de imagens
- **Fotografia Conceitual**: Efeitos especiais criativos
- **Arte Experimental**: Exploração de novos estilos visuais

### 📚 Educação e Pesquisa
- **Simulações Visuais**: Demonstrações educativas
- **Pesquisa Acadêmica**: Estudos sobre processamento de imagens
- **Ensino de Física**: Demonstração de propriedades da luz
- **Workshops de Design**: Ferramentas para ensino

### 🔬 Aplicações Técnicas
- **Análise de Materiais**: Estudo de propriedades visuais
- **Desenvolvimento Web**: Referência para filtros CSS
- **Prototipagem**: Testes de conceitos visuais
- **Demonstrações**: Apresentações técnicas

> **Nota Ética**: Este software não deve ser usado para fins inadequados ou invasivos. É destinado exclusivamente para arte, educação e pesquisa legítima.

## 🔒 Privacidade e Segurança

- ✅ **Processamento Local**: Todas as imagens são processadas no navegador
- ✅ **Sem Upload para Servidor**: Nenhuma imagem é enviada para servidores externos
- ✅ **Dados Temporários**: Imagens são mantidas apenas na sessão atual
- ✅ **Código Aberto**: Todo o código está disponível para auditoria
- ✅ **Sem Tracking**: Nenhum dado de usuário é coletado
- ✅ **Funciona Offline**: Após o primeiro carregamento

## ❓ Perguntas Frequentes (FAQ)

### 📸 Sobre as Imagens
**P: Que formatos de imagem são suportados?**  
R: JPG, PNG, GIF, WebP, BMP e TIFF até 10MB.

**P: As imagens são enviadas para algum servidor?**  
R: Não! Todo o processamento acontece localmente no seu navegador.

**P: Posso usar imagens de alta resolução?**  
R: Sim, mas imagens muito grandes podem demorar mais para processar.

### ⚙️ Sobre os Efeitos
**P: Como funcionam os presets?**  
R: Cada preset aplica uma combinação específica de filtros otimizada para diferentes tipos de material.

**P: Posso criar meus próprios presets?**  
R: Atualmente não, mas você pode salvar suas configurações manualmente.

**P: Os efeitos danificam a imagem original?**  
R: Não! A imagem original é preservada e você sempre pode resetar os filtros.

### 🖥️ Compatibilidade
**P: Funciona em dispositivos móveis?**  
R: Sim! A interface é totalmente responsiva e otimizada para touch.

**P: Preciso instalar algum software?**  
R: Não! Funciona diretamente no navegador moderno.

**P: Funciona offline?**  
R: Sim, após o primeiro carregamento da página.

### 🔧 Problemas Técnicos
**P: A página não carrega os controles?**  
R: Verifique se JavaScript está habilitado no seu navegador.

**P: O upload não funciona?**  
R: Verifique se o arquivo é uma imagem válida e menor que 10MB.

**P: Os filtros estão lentos?**  
R: Imagens muito grandes podem ser lentas. Tente redimensionar a imagem.

## 🌟 Contribuindo

Contribuições são muito bem-vindas! Aqui estão algumas maneiras de ajudar:

### 🐛 Reportar Bugs
- Use as [Issues do GitHub](../../issues) para reportar problemas
- Inclua screenshots e detalhes do navegador
- Descreva os passos para reproduzir o bug

### ✨ Sugerir Melhorias
- Novas funcionalidades
- Melhorias na interface
- Otimizações de performance
- Novos presets de filtros

### 🔧 Desenvolvimento
1. **Fork** o projeto
2. **Clone** sua cópia: `git clone https://github.com/SEU_USUARIO/x-ray-image-editor.git`
3. **Crie uma branch**: `git checkout -b feature/MinhaNovaFeature`
4. **Commit** suas mudanças: `git commit -m 'Add: Nova funcionalidade incrível'`
5. **Push** para a branch: `git push origin feature/MinhaNovaFeature`
6. **Abra um Pull Request**

### 📝 Padrões de Commit
- `Add:` Nova funcionalidade
- `Fix:` Correção de bug
- `Update:` Melhoria existente
- `Docs:` Alterações na documentação
- `Style:` Mudanças visuais/CSS
- `Refactor:` Refatoração de código

## 🗺️ Roadmap

### ✅ Versão Atual (v1.0)
- [x] Interface responsiva
- [x] 6 presets principais
- [x] Controles manuais
- [x] Upload drag & drop
- [x] Download de imagens
- [x] Processamento local

### 🔄 Próximas Versões

#### v1.1 - Melhorias de UX
- [ ] **Histórico de Ações** (Ctrl+Z / Ctrl+Y)
- [ ] **Presets Customizáveis** (salvar/carregar)
- [ ] **Comparação Antes/Depois** (modo split)
- [ ] **Zoom e Pan** na área de visualização
- [ ] **Modo Tela Cheia** para edição

#### v1.2 - Funcionalidades Avançadas
- [ ] **Batch Processing** (múltiplas imagens)
- [ ] **Filtros Adicionais** (blur, sharpen, edge detection)
- [ ] **Camadas e Máscaras**
- [ ] **Exportação em Múltiplos Formatos**
- [ ] **Configurações Salvas** (localStorage)

#### v2.0 - Performance e PWA
- [ ] **Web Workers** para processamento
- [ ] **Progressive Web App** (PWA)
- [ ] **Service Worker** para cache
- [ ] **WebAssembly** para algoritmos pesados
- [ ] **WebGL** para aceleração GPU

### 💡 Ideias Futuras
- Integração com APIs de IA
- Plugin para editores de imagem
- Versão desktop com Electron
- API REST para desenvolvedores
- Marketplace de presets da comunidade

## 📝 Licença

Este projeto está licenciado sob a **Licença MIT** - veja o arquivo [LICENSE](LICENSE) para detalhes completos.

### Resumo da Licença MIT:
- ✅ **Uso Comercial** permitido
- ✅ **Modificação** permitida
- ✅ **Distribuição** permitida
- ✅ **Uso Privado** permitido
- ⚠️ **Sem Garantia** (use por sua conta e risco)
- 📄 **Atribuição** necessária (manter copyright)

## 🎖️ Reconhecimentos

### Inspirações
- 🩻 **Tecnologias de Imageamento Médico** - Conceitos de raio-X
- 🎨 **Adobe Photoshop** - Interface e funcionalidades
- 🌐 **WebGL Shaders** - Algoritmos de processamento
- 📱 **Instagram Filters** - UX de aplicação de filtros

### Recursos Utilizados
- 🎨 **CSS Grid & Flexbox** - Layout responsivo
- 📐 **Material Design** - Princípios de design
- 🎭 **Unsplash** - Imagens de exemplo (não incluídas)
- 📚 **MDN Web Docs** - Referências técnicas

### Agradecimentos Especiais
- 👥 **Comunidade Open Source** - Inspiração e suporte
- 🐙 **GitHub** - Platform de desenvolvimento
- 🌍 **Comunidade de Desenvolvedores** - Feedback e sugestões

---

<div align="center">

### 🌟 **Apoie o Projeto** 🌟

Se este projeto foi útil para você, considere:

[![GitHub Stars](https://img.shields.io/github/stars/SEU_USUARIO/x-ray-image-editor?style=social)](../../stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/SEU_USUARIO/x-ray-image-editor?style=social)](../../network/members)
[![GitHub Issues](https://img.shields.io/github/issues/SEU_USUARIO/x-ray-image-editor)](../../issues)

**[⭐ Dar uma Estrela](../../stargazers) • [🐛 Reportar Bug](../../issues) • [💡 Sugerir Funcionalidade](../../issues) • [🤝 Contribuir](../../pulls)**

### 📞 Contato

**Desenvolvido com ❤️ para a comunidade**

[![GitHub](https://img.shields.io/badge/GitHub-SEU_USUARIO-181717?style=for-the-badge&logo=github)](https://github.com/SEU_USUARIO)
[![Email](https://img.shields.io/badge/Email-Contato-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:seu@email.com)

</div>

[🔝 **Voltar ao Topo**](#-x-ray-image-editor)
