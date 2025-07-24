<!-- Use this file to provide workspace-specific custom instructions to Copilot. For more details, visit https://code.visualstudio.com/docs/copilot/copilot-customization#_use-a-githubcopilotinstructionsmd-file -->

# IT Soluções Digitais - Copilot Instructions

## Project Overview
Este é um projeto de website/portfólio para a empresa "IT Soluções Digitais", especializada em transformação digital e soluções tecnológicas. O site foi desenvolvido com HTML5, CSS3 e JavaScript vanilla, baseado no template Fluxco da KitPro.

## Tecnologias Utilizadas
- **HTML5**: Estrutura semântica e acessível
- **CSS3**: Estilos modernos com Flexbox e Grid
- **JavaScript ES6+**: Funcionalidades interativas
- **Font Awesome**: Ícones
- **Google Fonts**: Tipografia (Inter)
- **AOS Library**: Animações on scroll

## Estrutura do Projeto
```
AgenciaIT/
├── index.html
├── assets/
│   ├── css/
│   │   ├── style.css
│   │   └── responsive.css
│   ├── js/
│   │   └── main.js
│   └── images/
│       └── (placeholders para imagens)
├── .github/
│   └── copilot-instructions.md
└── .vscode/
    └── tasks.json
```

## Diretrizes de Código

### HTML
- Use estrutura semântica (header, main, section, footer)
- Mantenha acessibilidade com ARIA labels quando necessário
- Use atributos alt em imagens
- Mantenha hierarquia correta de headings (h1, h2, h3...)

### CSS
- Use variáveis CSS (custom properties) definidas em :root
- Siga a metodologia BEM para nomenclatura de classes quando aplicável
- Mantenha responsividade com mobile-first approach
- Use Grid e Flexbox para layouts
- Prefira rem/em sobre px para tipografia
- Mantenha consistência com o design system estabelecido

### JavaScript
- Use ES6+ features (const/let, arrow functions, template literals)
- Mantenha código modular e bem comentado
- Use event delegation quando apropriado
- Implemente debouncing/throttling para eventos de performance
- Mantenha acessibilidade em mente para interações

## Padrões de Design

### Cores Principais
- Primary: #D4FF00 (amarelo vibrante da logo)
- Primary Dark: #B8E600 (amarelo escuro)
- Secondary: #000000 (preto da logo)
- Text Primary: #000000
- Text Secondary: #333333

### Typography
- Font Family: 'Inter', sans-serif
- Escala tipográfica consistente
- Line-height: 1.6 para texto corrido

### Componentes
- Botões com estados hover e focus
- Cards com sombras sutis e efeitos de hover
- Formulários com labels flutuantes
- Navegação responsiva com menu hamburger

## Funcionalidades Implementadas

1. **Navegação Fixa**: Header que muda ao fazer scroll
2. **Menu Mobile**: Hamburger menu para dispositivos móveis
3. **Smooth Scroll**: Navegação suave entre seções
4. **Filtros Portfolio**: Sistema de filtros JavaScript
5. **Formulários**: Validação e estados de loading
6. **Animações**: AOS library para reveal animations
7. **Back to Top**: Botão de voltar ao topo
8. **Responsive Design**: Layout adaptável para todos os dispositivos

## Seções do Site

1. **Header/Navigation**: Navegação principal fixa
2. **Hero**: Seção principal com CTA e estatísticas
3. **About**: Sobre a empresa, missão e visão
4. **Services**: Serviços oferecidos (6 cards)
5. **Portfolio**: Projetos realizados com filtros
6. **Team**: Equipe de profissionais
7. **Pricing**: Planos e pacotes
8. **Contact**: Formulário de contato e informações
9. **Footer**: Links, social media e newsletter

## Otimizações

### Performance
- Lazy loading para imagens
- Throttling/debouncing para eventos
- CSS otimizado com variáveis
- JavaScript modular

### SEO
- Meta tags apropriadas
- Estrutura semântica
- URLs âncoras para navegação
- Schema markup (pode ser adicionado)

### Acessibilidade
- Skip links
- Focus indicators
- ARIA labels
- Keyboard navigation
- Color contrast compliance

## Placeholders
O projeto usa placeholders para:
- Imagens da equipe
- Projetos do portfólio
- Imagens da seção sobre
- Ícones podem ser substituídos por imagens quando necessário

## Próximos Passos Sugeridos

1. **Imagens Reais**: Substituir placeholders por imagens reais
2. **Backend Integration**: Conectar formulários a um backend
3. **CMS**: Integrar com um CMS para conteúdo dinâmico
4. **Analytics**: Implementar Google Analytics ou similar
5. **SEO**: Adicionar meta tags específicas e schema markup
6. **PWA**: Considerar transformar em Progressive Web App
7. **Performance**: Otimizar ainda mais com lazy loading avançado

## Manutenção

- Mantenha consistência visual ao adicionar novas seções
- Teste em diferentes dispositivos e navegadores
- Mantenha acessibilidade em todas as modificações
- Documente mudanças significativas
- Use linting para manter qualidade do código

## Contato Fictício
- **Nome**: IT Soluções Digitais
- **Email**: contato@itsolucoes.com.br
- **Telefone**: (11) 99999-9999
- **Endereço**: Rua das Tecnologias, 123 - São Paulo, SP

Este projeto serve como base sólida para um site profissional de uma empresa de TI, com foco em conversão e experiência do usuário.
