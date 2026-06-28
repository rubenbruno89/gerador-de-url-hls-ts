# 🔗 Gerador de URL HLS & TS

Um gerador de URLs rápido e elegante para formatos **HLS** e **TS (MPEG-TS)**, perfeito para trabalhar com servidores IPTV e streaming.

**🌐 Acesse agora:** [https://rubenbruno89.github.io/gerador-de-url-hls-ts/](https://rubenbruno89.github.io/gerador-de-url-hls-ts/)

---

## ✨ Características

- ✅ **Interface moderna** com design glassmorphism e gradiente animado
- ✅ **Totalmente responsivo** - funciona perfeitamente em desktop, tablet e celular
- ✅ **Sem dependências externas** - apenas HTML, CSS e JavaScript puro
- ✅ **Offline** - todos os dados ficam apenas no seu navegador
- ✅ **Cópia rápida** - copie as URLs com um clique
- ✅ **Barra de rolagem estilizada** - design consistente em todos os navegadores
- ✅ **Notificações visuais** - feedback imediato das ações

---

## 🚀 Como Usar

### Online (Recomendado)
Simplesmente acesse: [https://rubenbruno89.github.io/gerador-de-url-hls-ts/](https://rubenbruno89.github.io/gerador-de-url-hls-ts/)

### Localmente
1. Baixe o arquivo `index.html`
2. Abra no seu navegador (duplo clique)
3. Pronto! 🎉

---

## 📋 Como Funciona

1. **Preencha os campos:**
   - **DNS**: URL do seu servidor (ex: `http://seu.servidor.com:8080`)
   - **Usuário**: Seu nome de usuário
   - **Senha**: Sua senha

2. **Clique em "Gerar URLs"**

3. **Copie as URLs geradas:**
   - **HLS**: Para reprodutores que suportam formato HLS
   - **TS**: Para reprodutores que suportam formato MPEG-TS

### URLs Geradas
```
HLS: {DNS}/get.php?username={usuario}&password={senha}&type=m3u_plus&output=hls
TS:  {DNS}/get.php?username={usuario}&password={senha}&type=m3u_plus&output=mpegts
```

---

## 🔒 Privacidade

- **Nenhum dado é armazenado** no servidor
- **Nenhuma requisição é enviada** para terceiros
- **Tudo funciona localmente** no seu navegador
- Seus dados de acesso nunca saem do seu computador

---

## 🎨 Design

O site utiliza um design moderno com:
- **Glassmorphism**: Cards com efeito de vidro fosco
- **Gradiente animado**: Fundo dinâmico e elegante
- **Tipografia premium**: Space Grotesk + JetBrains Mono
- **Responsividade total**: Adapta-se a qualquer tamanho de tela
- **Barra de rolagem customizada**: Com gradiente azul-roxo

---

## 💻 Tecnologias

- **HTML5** - Estrutura semântica
- **CSS3** - Estilos modernos com media queries
- **JavaScript Vanilla** - Sem frameworks ou dependências
- **Google Fonts** - Tipografia premium

---

## 📱 Compatibilidade

| Navegador | Desktop | Mobile |
|-----------|---------|--------|
| Chrome    | ✅      | ✅     |
| Firefox   | ✅      | ✅     |
| Safari    | ✅      | ✅     |
| Edge      | ✅      | ✅     |
| Opera     | ✅      | ✅     |

---

## 🛠️ Desenvolvimento

### Estrutura do Projeto
```
gerador-de-url-hls-ts/
├── index.html          # Arquivo único com HTML, CSS e JS
├── README.md           # Este arquivo
└── .github/
    └── workflows/
        └── deploy.yml  # GitHub Actions para deploy automático
```

### Fazer Deploy no GitHub Pages

1. **Crie um repositório** no GitHub chamado `gerador-de-url-hls-ts`

2. **Clone o repositório:**
   ```bash
   git clone https://github.com/SEU_USUARIO/gerador-de-url-hls-ts.git
   cd gerador-de-url-hls-ts
   ```

3. **Copie o arquivo `index.html`** para a raiz do repositório

4. **Faça commit e push:**
   ```bash
   git add index.html README.md
   git commit -m "Initial commit: URL generator HLS & TS"
   git push origin main
   ```

5. **Ative GitHub Pages:**
   - Vá em **Settings > Pages**
   - Escolha **Source**: `Deploy from a branch`
   - Escolha **Branch**: `main`
   - Clique em **Save**

6. **Seu site estará disponível em:**
   ```
   https://SEU_USUARIO.github.io/gerador-de-url-hls-ts/
   ```

---

## 📝 Licença

Este projeto é de **código aberto** e pode ser usado livremente. Sinta-se livre para:
- ✅ Usar em produção
- ✅ Modificar e adaptar
- ✅ Compartilhar com outros
- ✅ Fazer fork do projeto

---

## 🤝 Contribuições

Sugestões e melhorias são bem-vindas! Se encontrar algum bug ou tiver ideias, abra uma **Issue** ou **Pull Request**.

### Ideias para Melhorias
- [ ] Histórico de gerações (localStorage)
- [ ] Botão "Copiar ambas as URLs"
- [ ] Mostrar/ocultar senha
- [ ] Temas claro/escuro
- [ ] Suporte a múltiplos servidores
- [ ] Exportar URLs em arquivo

---

## 📧 Contato

Se tiver dúvidas ou sugestões, abra uma **Issue** no repositório.

---

## 🎯 Roadmap

- [x] Interface responsiva
- [x] Gerador de URLs HLS e TS
- [x] Cópia rápida
- [x] Design moderno
- [ ] Histórico de gerações
- [ ] Temas customizáveis
- [ ] Suporte a múltiplos formatos

---

**Desenvolvido com ❤️ para facilitar sua vida com streaming IPTV**

Acesse agora: [https://rubenbruno89.github.io/gerador-de-url-hls-ts/](https://rubenbruno89.github.io/gerador-de-url-hls-ts/)
