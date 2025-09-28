# 🦷 DentalCare - Landing Page Moderna

Uma landing page moderna e responsiva para clínica odontológica, desenvolvida com HTML, CSS e JavaScript puro, seguindo um design system elegante e profissional.

## ✨ Características

### 🎨 Design System
- **Paleta de Cores:**
  - Primária: `#1F3D2A` (verde escuro elegante)
  - Secundária: `#5D7C6A` (verde suave)
  - Fundo: `#FFFFFF` (branco limpo)
  - Texto principal: `#1A1A1A`
  - Texto secundário: `#555555`

- **Tipografia:**
  - Títulos: Playfair Display (serif elegante)
  - Corpo: Inter (sans-serif legível)

- **Componentes:**
  - Bordas arredondadas (8px - 12px)
  - Sombras suaves com hover effects
  - Transições suaves (0.3s ease-in-out)

### 📱 Responsividade
- Design mobile-first
- Breakpoints otimizados para todos os dispositivos
- Menu mobile com toggle
- Grid layouts adaptativos

### ⚡ Funcionalidades
- **Carrossel de Depoimentos** com navegação automática
- **Scroll Reveal** para animações no scroll
- **Navegação Suave** entre seções
- **Header Fixo** com efeitos de scroll
- **Botão Scroll to Top**
- **Menu Mobile** responsivo
- **Animações CSS** e transições suaves

## 🏗️ Estrutura da Página

### 1. Header Fixo
- Logo à esquerda
- Navegação central
- CTA "Agendar Consulta" à direita
- Menu mobile para dispositivos menores

### 2. Hero Section
- Layout em duas colunas
- Título impactante e subtítulo
- Botões CTA duplos
- Imagem placeholder ilustrativa

### 3. Seção de Benefícios
- 3 cards com ícones
- Atendimento Rápido, Tecnologia Avançada, Cuidado Personalizado
- Hover effects com elevação

### 4. Seção de Serviços
- 3 cards de serviços principais
- Limpeza Profissional, Implantes, Clareamento
- Botões "Saiba Mais" em cada card

### 5. Depoimentos
- Carrossel interativo
- 3 depoimentos com avaliações
- Controles de navegação
- Auto-play a cada 5 segundos

### 6. Como Funciona
- 3 passos numerados
- Processo simples e transparente
- Design visual intuitivo

### 7. Call to Action
- Seção full-width com fundo contrastante
- Título e subtítulo persuasivos
- Botão CTA principal

### 8. Footer
- 3 colunas: sobre, serviços, contato
- Links para redes sociais
- Informações de contato
- Copyright

## 🚀 Como Usar

### Instalação
1. Clone ou baixe os arquivos do projeto
2. Abra o arquivo `index.html` em um navegador
3. Ou use um servidor local para desenvolvimento

### Desenvolvimento Local
```bash
# Usando Python
python -m http.server 8000

# Usando Node.js (se tiver http-server instalado)
npx http-server

# Usando PHP
php -S localhost:8000
```

### Estrutura de Arquivos
```
projeto/
├── index.html          # Estrutura HTML principal
├── styles.css          # Estilos CSS completos
├── script.js           # Funcionalidades JavaScript
├── Design.json         # Design system (referência)
└── README.md           # Documentação
```

## 🎯 Personalização

### Cores
As cores podem ser facilmente alteradas editando as variáveis CSS no arquivo `styles.css`:

```css
:root {
    --primary: #1F3D2A;
    --secondary: #5D7C6A;
    --accent: #D6E4DC;
    /* ... outras variáveis */
}
```

### Conteúdo
- Substitua os textos placeholder por conteúdo real
- Adicione imagens reais no lugar dos placeholders
- Atualize informações de contato no footer

### Funcionalidades
- Modifique os botões CTA para redirecionar para formulários reais
- Integre com sistemas de agendamento
- Adicione formulários de contato funcionais

## 📱 Compatibilidade

### Navegadores Suportados
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

### Dispositivos
- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (320px - 767px)

## 🔧 Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **CSS3** - Estilos modernos com Grid e Flexbox
- **JavaScript ES6+** - Funcionalidades interativas
- **Font Awesome** - Ícones
- **Google Fonts** - Tipografia

## 📈 Performance

### Otimizações Implementadas
- CSS com variáveis para reutilização
- JavaScript modular e eficiente
- Animações otimizadas com CSS transforms
- Lazy loading para imagens (preparado)
- Debounce e throttle para eventos de scroll

### Métricas Esperadas
- Lighthouse Score: 90+
- First Contentful Paint: < 1.5s
- Largest Contentful Paint: < 2.5s
- Cumulative Layout Shift: < 0.1

## 🎨 Design System Detalhado

### Espaçamento
- Seções: 80px padding vertical
- Container: 1200px max-width
- Grid gap: 24px
- Card padding: 24px

### Sombras
- Cards: `0px 4px 12px rgba(0,0,0,0.08)`
- Hover: `0px 6px 16px rgba(0,0,0,0.12)`

### Transições
- Padrão: `all 0.3s ease-in-out`
- Hover effects suaves
- Animações de entrada

## 🤝 Contribuição

Para contribuir com o projeto:

1. Faça um fork do repositório
2. Crie uma branch para sua feature
3. Implemente suas mudanças
4. Teste em diferentes dispositivos
5. Envie um pull request

## 📄 Licença

Este projeto está sob a licença MIT. Sinta-se livre para usar, modificar e distribuir conforme necessário.

## 📞 Suporte

Para dúvidas ou sugestões:
- Abra uma issue no repositório
- Entre em contato através do email: contato@dentalcare.com

---

**Desenvolvido com ❤️ para proporcionar a melhor experiência em cuidados odontológicos**
