# LinkEduAi - Landing Page 🎓

Esta é a landing page oficial do LinkEduAi, um sistema moderno de gestão educacional que conecta estudantes, pais e professores através de uma plataforma web intuitiva.

## 📋 Sobre a Landing Page

A landing page foi desenvolvida em HTML, CSS e JavaScript puros, apresentando todas as funcionalidades e benefícios do sistema LinkEduAi de forma atrativa e responsiva.

### ✨ Características

- **Design Responsivo**: Funciona perfeitamente em desktop, tablet e smartphone
- **Animações Suaves**: Efeitos visuais modernos com CSS3 e JavaScript
- **Navegação Intuitiva**: Menu de navegação com scroll suave
- **Seções Organizadas**: Informações bem estruturadas sobre recursos e benefícios
- **Credenciais de Demo**: Acesso fácil às contas de demonstração
- **Performance Otimizada**: Carregamento rápido com CDN para bibliotecas externas

## 🚀 Como Usar

### Visualizar Localmente

1. **Abrir o arquivo HTML**:
   ```bash
   # Navegue até o diretório da landing page
   cd edu-connect/landing-page
   
   # Abra o arquivo index.html em seu navegador
   open index.html
   # ou
   google-chrome index.html
   # ou
   firefox index.html
   ```

2. **Usando um servidor local** (recomendado):
   ```bash
   # Com Python 3
   python -m http.server 8000
   
   # Com Node.js (se tiver o pacote http-server instalado)
   npx http-server
   
   # Com PHP
   php -S localhost:8000
   ```

   Acesse `http://localhost:8000` no seu navegador.

### Estrutura de Arquivos

```
landing-page/
├── index.html          # Página principal
├── styles.css          # Estilos customizados
└── README.md          # Este arquivo
```

## 🎨 Seções da Landing Page

### 1. **Header/Navegação**
- Logo do LinkEduAi
- Menu de navegação responsivo
- Links para seções principais

### 2. **Hero Section**
- Título principal chamativo
- Descrição do sistema
- Botões de CTA (Call to Action)

### 3. **Recursos Principais**
Dividido por tipo de usuário:

#### Para Estudantes
- 📊 Dashboard personalizado
- 📚 Visualização de notas
- 📅 Calendário de eventos
- 💬 Sistema de mensagens
- 🚌 Rastreamento de transporte
- 📸 Galeria de fotos
- 📖 Sistema de biblioteca
- 🤖 IA Insights com análise personalizada

#### Para Pais
- 👨‍👩‍👧‍👦 Monitoramento dos filhos
- 💳 Gestão financeira
- 📞 Comunicação direta
- 📈 Relatórios de progresso

#### Para Professores & Equipe
- 👨‍🎓 Gestão de estudantes
- 📝 Gestão de notas
- 📅 Criação de eventos
- 💬 Sistema de mensagens
- 📊 Analytics avançados

### 4. **Stack Tecnológico**
- Frontend: React 19.2.0 + Vite
- Backend: Go + Gin Framework
- Database: PostgreSQL 13

### 5. **Benefícios**
- Performance superior
- Segurança avançada
- Design responsivo
- Escalabilidade
- IA Insights avançados
- Análise preditiva

### 6. **Credenciais de Demo**
Contas pré-configuradas para teste:
- **Estudante**: student@educonnect.com / 123456
- **Pai/Mãe**: parent@educonnect.com / 123456
- **Professor**: teacher@educonnect.com / 123456
- **Admin**: admin@educonnect.com / 123456

### 6. **IA Insights - Inteligência Artificial Educacional**
Seção dedicada aos recursos de inteligência artificial:
- Análise personalizada para estudantes
- Relatórios automáticos para pais
- Insights pedagógicos para professores
- Recursos avançados: análise preditiva, recomendações inteligentes, detecção precoce e personalização adaptativa

### 7. **Call to Action**
- Botões para contato
- Link para demonstração
- Formulário de interesse

### 8. **Footer**
- Informações da empresa
- Links para redes sociais
- Copyright

## 🛠️ Tecnologias Utilizadas

### Frontend
- **HTML5**: Estrutura semântica
- **CSS3**: Estilos modernos com flexbox/grid
- **JavaScript ES6+**: Interatividade e animações
- **Tailwind CSS**: Framework CSS via CDN
- **Font Awesome**: Ícones vetoriais
- **Google Fonts**: Tipografia personalizada

### Recursos CSS
- CSS Grid e Flexbox para layout
- CSS Variables para temas consistentes
- Animações e transições suaves
- Media queries para responsividade
- Gradientes e sombras modernas

### JavaScript Features
- Smooth scrolling para navegação
- Animações on scroll
- Efeitos de hover interativos
- Responsividade dinâmica

## 🤖 IA Insights - Recursos Especiais

A landing page inclui uma seção dedicada aos recursos de Inteligência Artificial:

### Benefícios por Tipo de Usuário
- **Estudantes**: Análise personalizada, recomendações adaptativas, identificação de pontos fortes
- **Pais**: Relatórios automáticos, insights comportamentais, previsões de desempenho
- **Professores**: Análise de efetividade, identificação de alunos em risco, sugestões pedagógicas

### Recursos Avançados
- **Análise Preditiva**: Algoritmos que preveem tendências de desempenho
- **Recomendações Inteligentes**: Sugestões baseadas em padrões de sucesso
- **Detecção Precoce**: Identificação automática de dificuldades
- **Personalização Adaptativa**: Interface que se adapta ao usuário

## 🎯 Customização

### Cores do Tema
As cores principais podem ser alteradas no arquivo `styles.css`:

```css
:root {
    --primary-color: #667eea;
    --secondary-color: #764ba2;
    --accent-color: #4ecdc4;
    /* ... outras variáveis */
}
```

### Conteúdo
Para alterar textos e informações:
1. Edite o arquivo `index.html`
2. Mantenha as classes CSS existentes
3. Atualize os links e credenciais conforme necessário

### Estilos
Para personalizar a aparência:
1. Modifique o arquivo `styles.css`
2. Use as variáveis CSS existentes para consistência
3. Teste a responsividade em diferentes dispositivos

## 📱 Responsividade

A landing page foi desenvolvida com abordagem mobile-first e é totalmente responsiva:

- **Desktop**: Layout completo com todas as funcionalidades
- **Tablet**: Adaptação do grid e navegação
- **Mobile**: Interface otimizada para toque

### Breakpoints
- Mobile: até 480px
- Tablet: 481px a 768px
- Desktop: 769px+

## 🔗 Links Importantes

- **Aplicação Principal**: http://localhost:5173
- **API Backend**: http://localhost:8080
- **Documentação**: Ver README principal do projeto

## 📈 Performance

A landing page foi otimizada para:
- Carregamento rápido (< 3 segundos)
- SEO amigável
- Acessibilidade (WCAG 2.1)
- Core Web Vitals otimizados

## 🤝 Contribuindo

Para contribuir com melhorias na landing page:

1. Fork o repositório
2. Crie uma branch para sua feature
3. Faça suas alterações
4. Teste em diferentes navegadores
5. Submeta um Pull Request

## 📞 Suporte

Para dúvidas sobre a landing page:
- Abra uma issue no GitHub
- Entre em contato com a equipe de desenvolvimento
- Consulte a documentação principal do projeto

---

**Feito com ❤️ para a comunidade educacional**