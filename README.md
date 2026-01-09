# 🛋️ E-commerce Product Showcase

<div align="center">

![Product List](https://github.com/fqgiord/ecommerce/blob/main/img1.png?raw=true)

![Product Detail](https://github.com/fqgiord/ecommerce/blob/main/img2.png?raw=true)

[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

</div>

## 📋 Sobre o Projeto

Uma aplicação web moderna de e-commerce para exibição de produtos, desenvolvida com HTML, CSS e JavaScript puro. O projeto apresenta uma interface elegante para listagem de produtos de móveis (cadeiras lounge) e páginas de detalhes individuais.

## ✨ Funcionalidades

- 🏠 **Página Principal**: Lista todos os produtos disponíveis em um grid responsivo
- 🔍 **Página de Detalhes**: Exibe informações detalhadas de cada produto
- 📱 **Design Responsivo**: Interface adaptável para diferentes tamanhos de tela
- 🎨 **UI Moderna**: Design limpo e profissional
- 📊 **Carregamento Dinâmico**: Produtos carregados via JSON
- 🛒 **Produtos Similares**: Sugestões de produtos relacionados

## 🚀 Tecnologias Utilizadas

<div align="center">

| Tecnologia | Descrição |
|------------|----------|
| ![HTML5](https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg) <br> **HTML5** | Estrutura da aplicação |
| ![CSS3](https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg) <br> **CSS3** | Estilização e layout responsivo |
| ![JavaScript](https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg) <br> **JavaScript** | Lógica e interatividade |
| 📦 **JSON** | Armazenamento de dados dos produtos |

</div>

## 📁 Estrutura do Projeto

```
ecommerce/
│
├── index.html          # Página principal com lista de produtos
├── detail.html         # Página de detalhes do produto
├── style.css           # Estilos da aplicação
├── products.json       # Banco de dados dos produtos
│
├── img/                # Pasta de imagens dos produtos
│   ├── 1.png
│   ├── 2.png
│   └── ...
│
├── img1.png            # Screenshot da lista de produtos
├── img2.png            # Screenshot da página de detalhes
└── README.md           # Documentação do projeto
```

## 💻 Como Executar

### Pré-requisitos

- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Servidor local (opcional, mas recomendado para evitar problemas de CORS)

### Instalação e Execução

1. **Clone o repositório**
   ```bash
   git clone https://github.com/fqgiord/ecommerce.git
   cd ecommerce
   ```

2. **Opção 1: Usar um servidor local (Recomendado)**
   
   Com Python 3:
   ```bash
   python -m http.server 8000
   ```
   
   Com Node.js (usando `http-server`):
   ```bash
   npx http-server
   ```
   
   Com PHP:
   ```bash
   php -S localhost:8000
   ```

3. **Opção 2: Abrir diretamente**
   
   Abra o arquivo `index.html` no seu navegador.

4. **Acessar a aplicação**
   
   Navegue até `http://localhost:8000` no seu navegador.

## 🎯 Funcionalidades Detalhadas

### Página de Listagem (index.html)

- Exibe todos os produtos em um grid responsivo
- Cada produto mostra:
  - Imagem
  - Nome
  - Preço
- Click em qualquer produto redireciona para a página de detalhes

### Página de Detalhes (detail.html)

- Informações completas do produto selecionado
- Botões de ação (Check Out, Add to Cart)
- Seção de produtos similares
- Navegação entre produtos relacionados

### Arquivo de Dados (products.json)

Estrutura do JSON:
```json
[
  {
    "id": 1,
    "name": "LD01 LOUNGE CHAIR",
    "price": 200,
    "image": "img/1.png",
    "description": "TextOne, description, etc"
  }
]
```

## 🎨 Recursos de Design

- Layout responsivo com CSS Grid e Flexbox
- Paleta de cores moderna e profissional
- Tipografia legível e hierarquia visual clara
- Animações suaves e transições
- Ícones do Boxicons para melhor UX

## 🔧 Personalizações Possíveis

### Adicionar Novos Produtos

1. Adicione a imagem do produto na pasta `img/`
2. Edite o arquivo `products.json` adicionando um novo objeto:
   ```json
   {
     "id": 7,
     "name": "NOVO PRODUTO",
     "price": 500,
     "image": "img/7.png",
     "description": "Descrição do produto"
   }
   ```

### Modificar Estilos

Edite o arquivo `style.css` para personalizar:
- Cores
- Fontes
- Espaçamentos
- Layout

## 📱 Responsividade

O projeto foi desenvolvido com abordagem mobile-first e é totalmente responsivo:

- 📱 Mobile: < 768px
- 💻 Tablet: 768px - 1024px
- 🖥️ Desktop: > 1024px

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para:

1. Fazer um Fork do projeto
2. Criar uma branch para sua feature (`git checkout -b feature/NovaFuncionalidade`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova funcionalidade'`)
4. Push para a branch (`git push origin feature/NovaFuncionalidade`)
5. Abrir um Pull Request

## 📄 Licença

Este projeto é de código aberto e está disponível para uso educacional e comercial.

## 👨‍💻 Autor

**fqgiord**

- GitHub: [@fqgiord](https://github.com/fqgiord)

## 🙏 Agradecimentos

- Imagens de produtos utilizadas para demonstração
- Ícones fornecidos pelo [Boxicons](https://boxicons.com/)
- Comunidade open source

---

<div align="center">

**⭐ Se este projeto foi útil para você, considere dar uma estrela!**

Feito com ❤️ por [fqgiord](https://github.com/fqgiord)

</div>
