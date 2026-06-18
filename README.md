# Navbar 🧭

Barra de navegação (navbar) moderna em formato de pílula, desenvolvida com HTML, CSS e JavaScript, sobre um fundo em gradiente azul.

## 📋 Sobre o projeto

A página exibe uma **navbar centralizada** com design em formato de pílula (bordas totalmente arredondadas), contendo os seguintes links de navegação:

- **Home**
- **About**
- **Services**
- **Contact**

O fundo da página é um gradiente nas tonalidades de azul, dando destaque ao menu, que aparece em cor clara contrastando com o fundo.

## 🚀 Tecnologias utilizadas

- **HTML5** — estrutura da navbar (`<nav>`, `<ul>`/`<a>`)
- **CSS3** — estilização com bordas arredondadas (`border-radius`), gradiente de fundo (`linear-gradient`) e centralização via Flexbox

## 📁 Estrutura do projeto

```
.
├── index.html      # Página principal com a navbar
├── style.css       # Estilos da navbar, gradiente e layout
```

> Ajuste esta estrutura conforme os arquivos reais do seu projeto.

## ▶️ Como executar

Este projeto é estático (HTML/CSS/JS), sem necessidade de instalação de dependências.

### Opção 1: Live Server (VS Code)
1. Abra a pasta do projeto no VS Code.
2. Instale a extensão **Live Server**.
3. Clique com o botão direito em `index.html` → **Open with Live Server**.
4. O navegador abrirá automaticamente em algo como:
   ```
   http://127.0.0.1:5500/index.html
   ```

### Opção 2: Abrir diretamente
Basta abrir o arquivo `index.html` direto no navegador (duplo clique).

## ✅ Funcionalidades

- [x] Navbar centralizada com formato de pílula
- [x] Links de navegação: Home, About, Services, Contact
- [x] Fundo em gradiente azul
- [ ] Estado ativo (highlight) no link selecionado *(adicionar se implementado)*
- [ ] Responsividade para dispositivos móveis *(adicionar se implementado)*

## 🎨 Customização

Você pode ajustar facilmente:
- **Cores do gradiente de fundo** — alterando os valores de `background` (linear-gradient) no CSS;
- **Cor e formato da navbar** — alterando `background-color` e `border-radius` do elemento `<nav>`;
- **Itens do menu** — adicionando ou removendo links na lista de navegação;
- **Espaçamento entre os links** — ajustando `gap` (Flexbox) ou `margin`.

## 📸 Demonstração

Navbar em formato de pílula, centralizada na tela, com os itens Home, About, Services e Contact, sobre um fundo em gradiente azul.

## 📄 Licença

Este projeto é livre para uso e modificação.

---

> 💡 **Nota:** este README foi gerado a partir de uma captura de tela do projeto em execução. Para um README mais preciso (com nomes reais de arquivos, dependências exatas e instruções específicas), envie os arquivos do projeto.
