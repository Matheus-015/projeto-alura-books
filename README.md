# 📚 Alura Books - E-commerce de Livros Técnicos

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Mobile-First](https://img.shields.io/badge/Mobile_First-✓-success?style=for-the-badge)

Projeto completo de e-commerce desenvolvido com metodologia **Mobile First**, representando a consolidação de todos os conceitos aprendidos na formação Front-End da Alura.

## 🎯 Sobre o Projeto

O Alura Books é uma plataforma de venda de livros técnicos de tecnologia, desenvolvido com foco em **responsividade e experiência do usuário**. Este projeto demonstra a evolução de conceitos básicos até técnicas avançadas de desenvolvimento web.

## ✨ Destaques Técnicos

- **📱 Mobile First**: Desenvolvimento progressivo para mobile → tablet → desktop
- **🎨 Design System**: Variáveis CSS para cores e tipografia
- **🔧 Arquitetura CSS**: Separação modular por componentes
- **📐 Layout Responsivo**: 3 breakpoints (mobile, tablet, desktop)
- **🔄 Carrossel Interativo**: Integração com Swiper.js
- **♿ Acessibilidade**: Navegação por teclado e elementos semânticos

## 🛠️ Tecnologias e Conceitos Aplicados

### Fundamentos Consolidados
- HTML5 Semântico
- CSS3 com Custom Properties
- Flexbox
- Metodologia BEM
- Position (relative, absolute)
- Pseudo-classes (:hover, :checked)

### Técnicas Avançadas
- Media Queries (`min-width: 1024px`, `min-width: 1728px`)
- Mobile First Methodology
- CSS Combinators (`~`, `+`)
- Integração de Bibliotecas (Swiper.js)
- Organização de Arquivos por Componentes

## 🎨 Design System

```css
:root {
    --cor-cinza: #EBECEE;
    --cor-laranja: #EB9B00;
    --cor-azul: #002F52;
    --cor-azul-degrade: linear-gradient(97.54deg, #002F52 35.49%, #326589 165.37%);
    --fonte-Poppins: "Poppins";
    --fonte-Josefin: "Josefin Sans";
}
```

## 📱 Layout Responsivo
| Breakpoint      | Dispositivo               | Características                  |
|:---------------:|:--------------------:|:--------------------------------:|
| < 1024px        | Mobile               | Layout vertical, menu hamburger  |
| 1024px+         | Tablet               | Layout adaptativo, menus expandidos |
| 1728px+         | Desktop              | Layout completo, carrossel lateral |

## 🚀 Como Executar
```bash
# Clone o repositório
git clone https://github.com/Matheus-015/alura-books.git

# Abra o arquivo index.html no navegador
```

## 📁 Estrutura do Projeto
```text
alura-books/
├── index.html
├── styles/
│   ├── reset.css
│   ├── header.css
│   ├── main.css
│   └── footer.css
│   └── styles.css
├── assets/
│   ├── iconsBooks/
│   ├── iconsFooter/
│   └── (demais imagens)
└── README.md
```

## 🔧 Funcionalidades Implementadas
- Header responsivo com menu
- Carrossel de livros com Swiper.js
- Cards de produtos interativos
- Seção de tópicos em grid flexível
- Formulário de newsletter
- Footer com links organizados
- Design responsivo em 3 breakpoints

## 📊 Evolução Técnica
Este projeto representa a consolidação completa de:
- Posicionamento com Flexbox e Position
- Organização com metodologia BEM
- Responsividade com Mobile First
- Manutenibilidade com CSS modularizado
- Integração de bibliotecas externas

## 👨‍💻 Autor
Matheus Mendoza Souza

