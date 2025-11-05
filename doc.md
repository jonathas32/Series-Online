# SeriesFlix - Projeto de Recomendação de Séries

## 📋 Visão Geral

Site de recomendação de séries desenvolvido com **HTML5**, **CSS3** e **JavaScript vanilla**, sem uso de frameworks externos. O projeto foi criado para ser simples, criativo e fácil de versionar no GitHub.

## 🎯 Objetivo do Projeto

Criar um site visualmente atraente que apresenta recomendações de séries com:
- Design moderno e criativo
- Animações CSS dinâmicas
- Imagens atraentes para cada série
- Links diretos para trailers no YouTube
- Música de fundo instrumental
- Layout totalmente responsivo
- Estrutura organizada para versionamento Git

## 📂 Estrutura de Arquivos

```
/
├── index.html      # Página principal com estrutura HTML5 semântica
├── styles.css      # Estilos CSS3 com gradientes e animações
├── images/         # Pasta com imagens das séries
│   ├── the-chosen.jpg
│   ├── peaky-blinders.jpg
│   ├── prison-break.jpg
│   ├── this-is-us.jpg
│   ├── stranger-things.jpg
│   └── supernatural.jpg
├── README.md       # Documentação completa do projeto
├── .gitignore      # Arquivos ignorados pelo Git
└── replit.md       # Documentação interna do projeto
```

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica com tags como header, nav, main, section, article, footer
- **CSS3**: 
  - Flexbox e Grid para layout responsivo
  - Gradientes lineares para visual moderno
  - Animações e transições suaves
  - Efeitos de hover interativos
  - Media queries para responsividade
- **JavaScript**: 
  - Controle do player de música de fundo
  - Toggle play/pause com feedback visual
- **Imagens**: Fotos stock de alta qualidade para cada série

## 🎨 Características de Design

### Paleta de Cores (Gradientes CSS)
- **Primary**: #667eea → #764ba2 (Roxo/Violeta)
- **Secondary**: #f093fb → #f5576c (Rosa/Vermelho)
- **Accent**: #4facfe → #00f2fe (Azul/Ciano)
- **Dark**: #0f2027 → #2c5364 (Escuro)
- **Success**: #11998e → #38ef7d (Verde)

### Elementos Visuais
- Header com gradiente roxo e ícone animado
- Navegação sticky com efeitos de hover
- Cards com sombras e animação de elevação
- Seção destacada para "Supernatural" com fundo escuro
- Footer com informações de autoria

## 📺 Séries Incluídas

1. **The Chosen** - Drama histórico/religioso
2. **Peaky Blinders** - Crime e drama
3. **Prison Break** - Suspense e ação
4. **This is Us** - Drama familiar
5. **Stranger Things** - Ficção científica/Terror
6. **Supernatural** - Fantasia/Terror (destaque especial)

Cada série possui:
- Imagem atraente com efeito zoom no hover
- Card individual com cabeçalho colorido
- Ícone emoji temático
- Descrição resumida
- Tags de gênero
- Botão com link para trailer no YouTube

## 📱 Responsividade

O site adapta-se a diferentes tamanhos de tela:

- **Desktop** (> 768px): Grid de 3 colunas para cards
- **Tablet** (481-768px): Grid de 2 colunas
- **Mobile** (< 480px): Grid de 1 coluna, navegação vertical

## 🎭 Animações e Efeitos Implementados

1. **Rotação** - Ícone do logo gira continuamente
2. **Pulse** - Efeito de pulsação no header
3. **Bounce** - Ícones dos cards saltam suavemente
4. **Hover Effects** - Cards elevam ao passar o mouse
5. **Zoom nas Imagens** - Imagens dos cards aumentam 10% no hover
6. **Flicker** - Ícone da seção Supernatural pisca
7. **Transitions** - Transições suaves em botões e links
8. **Música de Fundo** - Player controlável com botão flutuante
9. **Imagem de Fundo** - Seção Supernatural com imagem desfocada

## 🔗 Links para Trailers

Todos os links direcionam para trailers oficiais no YouTube:
- The Chosen: https://www.youtube.com/watch?v=crafchWM1d0
- Peaky Blinders: https://www.youtube.com/watch?v=oVzVdvGIC7U
- Prison Break: https://www.youtube.com/watch?v=AL9zLctD4Zg
- This is Us: https://www.youtube.com/watch?v=8kLJHto5U08
- Stranger Things: https://www.youtube.com/watch?v=b9EkMc79ZSU
- Supernatural: https://www.youtube.com/watch?v=_T47xOd-l7g

## 👤 Informações do Autor

- **Nome**: Isabelly Reis
- **Data de Criação**: 05/11/2025
- **Tecnologias**: HTML5, CSS3 e JavaScript
- **Recursos**: Imagens, música de fundo instrumental

## 📝 Notas de Desenvolvimento

### Preferências de Estilo
- Código limpo e bem comentado
- Uso de variáveis CSS para fácil customização
- HTML semântico para melhor acessibilidade
- CSS organizado por seções

### Estrutura do CSS
1. Reset e variáveis globais
2. Header e navegação
3. Seções principais
4. Cards de séries
5. Seção destacada (Supernatural)
6. Footer
7. Media queries para responsividade

## 🚀 Próximas Melhorias (Sugestões)

- [ ] Adicionar mais séries em diferentes categorias
- [ ] Criar sistema de filtragem por gênero
- [ ] Implementar modo dark/light
- [ ] Adicionar seção de séries favoritas
- [ ] Criar páginas individuais para cada série
- [ ] Adicionar sistema de avaliação visual

## 📦 Versionamento Git

O projeto está pronto para ser versionado no GitHub:

```bash
git init
git add .
git commit -m "Initial commit: SeriesFlix - Site de recomendação de séries"
git branch -M main
git remote add origin <seu-repositorio>
git push -u origin main
```

## 🎓 Aprendizados

Este projeto demonstra:
- HTML5 semântico e acessível
- CSS3 moderno com gradientes e animações
- Design responsivo sem frameworks
- Organização de código para projetos web estáticos
- Boas práticas de versionamento

---

**Última atualização**: 05/11/2025
