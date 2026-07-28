# 🥗 Anny Beatriz | Nutricionista — Landing Page

Uma landing page moderna, elegante e totalmente responsiva desenvolvida para a nutricionista **Anny Beatriz**. O projeto foi construído focando em uma experiência de usuário (UX) fluida, com design sofisticado, paleta de cores acolhedora e animações sutis ao rolar a página.

---

## 📱 Demonstração & Recursos

- **Design Responsivo & Adaptável**: Layout fluido construído para dispositivos móveis, tablets e desktops (Mobile First / Modern Layouts).
- **Menu Mobile Interativo**: Navegação retrátil com efeito hambúrguer e controle de acessibilidade (`aria-expanded`).
- **Animações Fluidas (Scroll Reveal)**: Elementos surgem suavemente na tela utilizando a API nativa `IntersectionObserver` de alta performance.
- **Header Dinâmico**: Barra de navegação com desfoque (*glassmorphism*) e indicação visual ao rolar a página.
- **Navegação Suave (*Smooth Scroll*)**: Rolagem com compensação para o topo fixo (`scroll-padding-top`).
- **Navegação Direta para Contato**: Botões de CTA (*Call to Action*) integrados com direcionamento para **WhatsApp** e **E-mail**.

---

## 🛠️ Tecnologias Utilizadas

O projeto foi desenvolvido de forma 100% nativa (Vanilla Web), sem a necessidade de bibliotecas pesadas ou frameworks externos:

- **HTML5**: Estruturação semântica, acessível e otimizada para SEO.
- **CSS3**:
  - Variáveis CSS (Custom Properties) para fácil manutenção de temas e cores.
  - **Flexbox** e **CSS Grid** para os layouts.
  - Transições e animações customizadas (`@keyframes`).
  - `@media (prefers-reduced-motion)` para suporte a preferências de acessibilidade.
  - Tipografia via **Google Fonts** (*Cinzel*, *Great Vibes*, *Montserrat*).
- **JavaScript (ES6+)**:
  - `IntersectionObserver` para detecção de visibilidade dos elementos.
  - Manipulação de classes DOM para interatividade do menu e header.

---

## 📁 Estrutura de Arquivos

```text
.
├── assets/
│   ├── icons/
│   │   └── logo-nutri.png       # Logo principal
│   └── images/
│       ├── anny-hero.jpeg       # Foto de exibição da seção principal
│       └── anny-about.jpeg      # Foto da seção "Sobre mim"
├── css/
│   └── style.css                # Estilos globais e componentes
├── js/
│   └── script.js                # Lógica de animação e navegação
├── index.html                   # Estrutura principal da aplicação
└── README.md                    # Documentação do projeto
```

---

## 🚀 Como Executar o Projeto

1. **Clonar o Repositório**:
   ```bash
   git clone https://github.com/seu-usuario/anny-beatriz-nutri.git
   ```

2. **Navegar até a pasta**:
   ```bash
   cd anny-beatriz-nutri
   ```

3. **Abrir a aplicação**:
   - Basta abrir o arquivo `index.html` em qualquer navegador web de sua preferência.
   - Ou utilize a extensão **Live Server** no VS Code para visualizar com recarregamento automático em tempo real.

---

## 🎨 Paleta de Cores & Design System

- **Fundo Principal (Navy Dark)**: `#03122e`
- **Fundo Secundário (Light Card)**: `#f3f6fa`
- **Card Background**: `#081a3e`
- **Destaques Gold**: `#d8be8a`
- **Texto Principal**: `#ffffff` / `#0d1b2a`

---

## 📄 Licença

Este projeto foi criado sob medida para **Anny Beatriz Nutricionista**. Sinta-se à vontade para utilizar o código como inspiração ou base para outros projetos de estudos!

---

 Desenvolvido para apresentar um cuidado nutricional humano, individualizado e focado na saúde real.
