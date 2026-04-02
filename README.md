# JS Custom Slide 📸

## Slide Moderno e Responsivo | Portfólio de Engenharia de Software

<br />

<div align="center">
	<img src="https://i.imgur.com/r9lrbPG.png" title="source: imgur.com" width="35%"/>
</div>

<br />

<div align="center">
  <img src="https://img.shields.io/github/languages/top/jrs-neto/slide?style=flat-square" />
  <img src="https://img.shields.io/github/repo-size/jrs-neto/slide?style=flat-square" />
  <img src="https://img.shields.io/github/languages/count/jrs-neto/slide?style=flat-square" />
  <img src="https://img.shields.io/github/last-commit/jrs-neto/slide?style=flat-square" />
  <img src="https://img.shields.io/badge/status-conclu%C3%ADdo-brightgreen" alt="Status: Concluído">
</div>

------

<br />

## 🎯 Sobre o Projeto

O **JS Custom Slide** é um componente de carrossel de imagens desenvolvido inteiramente em **JavaScript Vanilla**, focado em performance, modularidade e experiência do usuário. 

Diferente de bibliotecas prontas, este projeto foi construído do zero para demonstrar o domínio de **Manipulação do DOM**, **Eventos de Toque/Arraste**, e **Programação Orientada a Objetos (POO)**. Ele oferece uma navegação fluida tanto em desktops (mouse) quanto em dispositivos móveis (touch screen).

<br />

> [!NOTE]
> Este projeto foi desenvolvido como parte de um estudo aprofundado de JavaScript, aplicando conceitos avançados de lógica e arquitetura de componentes front-end.

<br />

## ✨ Funcionalidades Implementadas

- **Navegação por Arraste (Drag & Touch):** Suporte completo para deslizar as imagens com o mouse ou o dedo, garantindo uma experiência nativa.
- **Controles Customizados (Thumbnails):** Interface reativa com miniaturas que permitem a pré-visualização e seleção rápida de cada slide.
- **Navegação por Setas:** Botões clássicos de navegação lateral para maior acessibilidade.
- **Design Responsivo:** O componente detecta automaticamente mudanças no tamanho da janela e recalcula as dimensões para manter o alinhamento perfeito.
- **Performance Otimizada (Debounce):** Implementação de função debounce para prevenir execuções excessivas de scripts durante o redimensionamento da tela.
- **Transições Suaves:** Movimentação baseada em CSS Transitions integrada via script para fluidez visual premium.

<br />

## 🛠️ Tecnologias Utilizadas

| Item | Descrição |
| :--- | :--- |
| **Linguagem** | JavaScript (ES6+ e Modular) |
| **Estruturação** | HTML5 Semântico |
| **Estilização** | CSS3 (Vanilla) |
| **Otimização** | Debounce Helper para performance |
| **Versionamento**| Git & GitHub |

<br />

## 📦 Estrutura do Projeto

A organização do código segue o princípio de separação de responsabilidades e modularidade:

```bash
📦 slide
 ┣ 📂 css
 ┃ ┗ 📜 style.css       # Estilização do componente e animações
 ┣ 📂 js
 ┃ ┣ 📜 slide.js        # Core do componente (Classe Slide e SlideNav)
 ┃ ┣ 📜 debounce.js     # Utilitário de otimização de performance
 ┃ ┗ 📜 script.js       # Ponto de entrada e instanciação
 ┣ 📂 img               # Assets de imagens e thumbnails
 ┣ 📜 index.html        # Estrutura do documento
 ┗ 📜 README.md         # Documentação do projeto
```

<br />

## 🚀 Como Executar o Projeto

Como o projeto utiliza apenas tecnologias nativas da web, não é necessário configurar servidores ou instalar dependências complexas.

**1. Clone o repositório:**
```bash
git clone https://github.com/jrs-neto/slide.git
```

**2. Acesse a pasta:**
```bash
cd slide
```

**3. Abra o arquivo principal:**
Basta abrir o arquivo `index.html` em qualquer navegador moderno (Chrome, Firefox, Safari ou Edge).

<br />

## 📖 Como Usar

Para integrar o slide em novos contextos, a classe principal pode ser instanciada passando os seletores necessários:

```javascript
/* Exemplo de uso no script.js */
import { SlideNav } from './slide.js';

const slide = new SlideNav('.slide', '.slide-wrapper');
slide.init();
slide.addArrow('.prev', '.next');
slide.addControl('.custom-controls');
```

<br />

## 🚧 Implementações Futuras

- [ ]  Autoplay com tempo configurável
- [ ]  Efeito de Loop Infinito (Seamless Loop)
- [ ]  Suporte para legendas (captions) dinâmicas
- [ ]  Transição de fade como alternativa ao slide lateral

<br />

## 🤝 Contribuições

Sugestões e melhorias são sempre bem-vindas. Sinta-se à vontade para abrir uma **issue** ou enviar um **pull request**.

<br />

## ⚖️ Licença

Este projeto está sob a licença **MIT** — sinta-se livre para estudar, modificar e reutilizar em seus próprios projetos.

<br />

## 📞 Autor

**José Rodrigues — Desenvolvedor Full Stack**

🔗 **GitHub:** [https://github.com/jrs-neto](https://github.com/jrs-neto)  
🔗 **LinkedIn:** [https://www.linkedin.com/in/jrodrigues-neto/](https://www.linkedin.com/in/jrodrigues-neto/)

🔗 **Portfólio:** [https://jrs-neto.github.io/portfolio/](https://jrs-neto.github.io/portfolio/)

---
*Projeto desenvolvido para demonstração técnica e evolução contínua em engenharia de software frontend.*
