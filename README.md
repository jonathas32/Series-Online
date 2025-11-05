# 🎬 SeriesFlix - Site de Recomendação de Séries

Um site estático criativo e dinâmico para recomendação de séries, desenvolvido com **HTML5** e **CSS3 puro**.

## 📝 Descrição

SeriesFlix é uma landing page moderna que apresenta recomendações de séries com design criativo, gradientes coloridos, animações suaves e links diretos para trailers no YouTube.

## ✨ Características

- 💻 **100% HTML e CSS** - Sem JavaScript, apenas código puro
- 🎨 **Design Moderno** - Gradientes coloridos e layout responsivo
- ✨ **Animações CSS** - Efeitos de hover, transições e animações dinâmicas
- 📱 **Responsivo** - Funciona perfeitamente em desktop, tablet e mobile
- 🎯 **Cards Interativos** - Cada série tem seu próprio card com informações e link para trailer
- 🔗 **Links do YouTube** - Acesso direto aos trailers de cada série
- 🎭 **Navegação Suave** - Menu fixo com links âncora para cada seção

## 📂 Estrutura do Projeto

```
seriesflix/
│
├── index.html          # Página principal (HTML5 semântico)
├── styles.css          # Estilos e animações CSS3
├── README.md           # Documentação do projeto
└── .gitignore          # Arquivos ignorados pelo Git
```

## 🎯 Séries Incluídas

1. **The Chosen** ✨ - Drama histórico sobre a vida de Jesus Cristo
2. **Peaky Blinders** 🎩 - Crime e drama no submundo britânico
3. **Prison Break** 🔒 - Suspense e ação sobre uma fuga elaborada
4. **This is Us** ❤️ - Drama familiar emocionante
5. **Stranger Things** 👾 - Ficção científica e terror nostálgico
6. **Supernatural** 🔥 - Maratona épica com 15 temporadas

## 🚀 Como Usar

### Opção 1: Abrir Localmente

1. Clone ou baixe este repositório
2. Abra o arquivo `index.html` em seu navegador
3. Pronto! O site está funcionando

### Opção 2: Hospedar no GitHub Pages

1. Faça fork deste repositório
2. Vá em Settings > Pages
3. Selecione a branch `main` como fonte
4. Seu site estará disponível em `https://seu-usuario.github.io/seriesflix`

## 🎨 Customização

### Alterar Cores

Edite as variáveis CSS no arquivo `styles.css`:

```css
:root {
  --primary-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  --secondary-gradient: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
  --accent-gradient: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
}
```

### Adicionar Novas Séries

No arquivo `index.html`, copie um card existente e modifique:

```html
<article class="series-card" id="sua-serie">
  <div class="card-header">
    <span class="card-icon">🎬</span>
    <h3>Nome da Série</h3>
  </div>
  <div class="card-body">
    <p class="card-description">Descrição da série...</p>
    <div class="card-tags">
      <span class="tag">Gênero</span>
    </div>
  </div>
  <div class="card-footer">
    <a href="LINK_DO_YOUTUBE" target="_blank" class="watch-btn">
      ▶ Assistir Trailer
    </a>
  </div>
</article>
```

## 📱 Responsividade

O site é totalmente responsivo com breakpoints em:
- 📱 **Mobile**: até 480px
- 📱 **Tablet**: 481px - 768px
- 💻 **Desktop**: acima de 768px

## 🛠️ Tecnologias Utilizadas

- HTML5 (estrutura semântica)
- CSS3 (Flexbox, Grid, Animations, Gradients)
- Design responsivo com Media Queries

## 👤 Autor

**Isabelly Reis**

- 📅 Data de criação: 05/11/2025
- 💻 Desenvolvido com HTML5 e CSS3

## 📄 Licença

Este projeto é livre para uso pessoal e educacional.

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para:
- Adicionar novas séries
- Melhorar o design
- Corrigir bugs
- Sugerir novas funcionalidades

---

⭐ Se você gostou deste projeto, deixe uma estrela no GitHub!
