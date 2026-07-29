# 🥗 Anny Beatriz | Nutricionista — Landing Page

Uma landing page moderna, elegante e totalmente responsiva desenvolvida para a nutricionista **Anny Beatriz**. O projeto foi construído focando em uma experiência de usuário (UX) fluida, com design sofisticado, paleta de cores acolhedora, animações sutis ao rolar a página e otimização para compartilhamento e SEO.

🔗 **Site no ar:** [annybeatriznutricionista.com.br](https://annybeatriznutricionista.com.br/)

---

## 📱 Demonstração & Recursos

- **Design Responsivo & Adaptável**: Layout fluido construído para dispositivos móveis, tablets e desktops (Mobile First / Modern Layouts).
- **Menu Mobile Interativo**: Navegação retrátil com efeito hambúrguer, fechamento automático ao clicar em um link e controle de acessibilidade (`aria-expanded`).
- **Animações Fluidas (Scroll Reveal)**: Elementos surgem suavemente na tela utilizando a API nativa `IntersectionObserver` de alta performance, com fallback via `<noscript>` para garantir conteúdo visível caso o JavaScript esteja desabilitado.
- **Header Dinâmico**: Barra de navegação com desfoque (*glassmorphism*) e indicação visual (`.scrolled`) ao rolar a página.
- **Navegação Suave (*Smooth Scroll*)**: Rolagem com compensação para o topo fixo (`scroll-padding-top`).
- **Navegação Direta para Contato**: Botões de CTA (*Call to Action*) integrados com direcionamento para **WhatsApp** (mensagem pré-preenchida), **E-mail** e **Instagram**.
- **SEO & Compartilhamento Social**: Meta tags completas de `description`, `keywords`, `canonical`, **Open Graph** e **Twitter Card**, com imagem de compartilhamento (`og-image.png`) dedicada.
- **Identidade Visual Completa**: Favicon próprio e logo aplicados no header, no menu mobile e no rodapé.
- **Domínio Próprio**: Publicado via GitHub Pages com domínio customizado (`CNAME`).
- **Credibilidade Profissional**: Registro do CRN exibido no rodapé, reforçando a confiança no atendimento.

---

## 🛠️ Tecnologias Utilizadas

O projeto foi desenvolvido de forma 100% nativa (Vanilla Web), sem a necessidade de bibliotecas pesadas ou frameworks externos:

- **HTML5**: Estruturação semântica, acessível e otimizada para SEO, com metadados completos para redes sociais (Open Graph / Twitter Card).
- **CSS3**:
  - Variáveis CSS (Custom Properties) para fácil manutenção de temas e cores.
  - **Flexbox** e **CSS Grid** para os layouts.
  - Transições e animações customizadas (`@keyframes`).
  - `@media (prefers-reduced-motion)` para suporte a preferências de acessibilidade.
  - Tipografia via **Google Fonts** (*Cinzel*, *Great Vibes*, *Montserrat*).
- **JavaScript (ES6+)**:
  - `IntersectionObserver` para detecção de visibilidade dos elementos.
  - Manipulação de classes DOM para interatividade do menu, header e estados de acessibilidade.

---

## 📁 Estrutura de Arquivos

```text
.
├── assets/
│   ├── icons/
│   │   ├── favicon.png          # Ícone da aba do navegador
│   │   └── logo-nutri.png       # Logo principal
│   ├── images/
│   │   ├── anny-hero.jpeg       # Foto de exibição da seção principal
│   │   └── anny-about.jpeg      # Foto da seção "Sobre mim"
│   └── og-image.png             # Imagem de pré-visualização (Open Graph / Twitter Card)
├── css/
│   └── style.css                # Estilos globais e componentes
├── js/
│   └── script.js                # Lógica de animação, menu e header
├── CNAME                        # Configuração do domínio próprio (GitHub Pages)
├── index.html                   # Estrutura principal da aplicação
└── README.md                    # Documentação do projeto
```

---

## 🚀 Como Executar o Projeto

1. **Clonar o Repositório**:
   ```bash
   git clone https://github.com/jasielrasec18-dev/anny-nutricionista.git
   ```

2. **Navegar até a pasta**:
   ```bash
   cd anny-nutricionista
   ```

3. **Abrir a aplicação**:
   - Basta abrir o arquivo `index.html` em qualquer navegador web de sua preferência.
   - Ou utilize a extensão **Live Server** no VS Code para visualizar com recarregamento automático em tempo real.

---

## 🌐 Publicação (Deploy)

O projeto está hospedado via **GitHub Pages**, com domínio próprio configurado através do arquivo `CNAME`, apontando para `annybeatriznutricionista.com.br`.

---

## 🎨 Paleta de Cores & Design System

- **Fundo Principal (Navy Dark)**: `#03122e`
- **Fundo Secundário (Light Card)**: `#f3f6fa`
- **Card Background**: `#081a3e`
- **Destaques Gold**: `#d8be8a` (hover: `#c4a973`)
- **Texto Principal**: `#ffffff` / `#0d1b2a`
- **Texto Suave**: `#bac7d5` / `#4a5568`
- **Tipografia**: `Cinzel` (títulos), `Great Vibes` (destaques em script), `Montserrat` (corpo de texto)

---

## 📄 Licença

Este projeto foi criado sob medida para **Anny Beatriz Nutricionista**. Sinta-se à vontade para utilizar o código como inspiração ou base para outros projetos de estudos!

---

 Desenvolvido para apresentar um cuidado nutricional humano, individualizado e focado na saúde real.