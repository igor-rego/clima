# 🌤️ Weather Dashboard - Dashboard de Clima

Um dashboard de clima moderno e responsivo com dados em tempo real, gráficos interativos e previsões detalhadas.

## ✨ Características

- **🌍 Dados em Tempo Real**: Informações climáticas atualizadas a cada 5 minutos
- **📊 Gráficos Interativos**: Visualizações dinâmicas de temperatura, umidade, vento e precipitação
- **🔍 Busca de Cidades**: Pesquise qualquer cidade do mundo
- **📍 Geolocalização**: Detecção automática da sua localização
- **📱 Design Responsivo**: Funciona perfeitamente em desktop, tablet e mobile
- **🌙 Modo Escuro**: Suporte automático para tema claro/escuro
- **⚡ Performance Otimizada**: Carregamento rápido e cache inteligente
- **♿ Acessibilidade**: Totalmente acessível com suporte a leitores de tela

## 🚀 Como Usar

1. **Abra o arquivo `index (1).html`** no seu navegador
2. **Permita o acesso à localização** para ver o clima da sua região
3. **Pesquise uma cidade** usando o campo de busca
4. **Explore os gráficos** clicando nos filtros de período (24h, 7 dias, 30 dias)
5. **Alternar tema** usando o botão de tema no cabeçalho

## ⌨️ Atalhos de Teclado

- `Ctrl + R` - Atualizar dados
- `Ctrl + L` - Usar localização atual
- `Enter` - Pesquisar cidade (quando o campo de busca está focado)

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **CSS3** - Estilos modernos com CSS Grid, Flexbox e variáveis CSS
- **JavaScript ES6+** - Lógica da aplicação com classes e async/await
- **Chart.js** - Gráficos interativos
- **Open-Meteo API** - Dados climáticos em tempo real
- **Google Fonts** - Tipografia moderna (Inter)

## 📁 Estrutura do Projeto

```
APP_CLIMA/
├── index (1).html      # Página principal
├── style.css           # Estilos CSS
├── app.js              # Lógica JavaScript
└── README.md           # Documentação
```

## 🌐 APIs Utilizadas

### Open-Meteo API
- **URL Base**: `https://api.open-meteo.com/v1`
- **Geocoding**: `https://geocoding-api.open-meteo.com/v1`
- **Gratuita**: Sem necessidade de API key
- **Dados**: Temperatura, umidade, vento, precipitação, previsões

## 🎨 Design System

### Cores
- **Primária**: `#3b82f6` (Azul)
- **Secundária**: `#64748b` (Cinza)
- **Acento**: `#f59e0b` (Laranja)
- **Sucesso**: `#10b981` (Verde)
- **Erro**: `#ef4444` (Vermelho)

### Tipografia
- **Fonte Principal**: Inter (Google Fonts)
- **Tamanhos**: Sistema de escala responsiva
- **Pesos**: 300, 400, 500, 600, 700

### Componentes
- **Cards**: Com efeitos hover e glassmorphism
- **Botões**: Com animações e estados visuais
- **Formulários**: Com validação e feedback visual
- **Gráficos**: Responsivos e interativos

## 📱 Responsividade

O dashboard é totalmente responsivo e se adapta a diferentes tamanhos de tela:

- **Desktop** (>1024px): Layout completo com todos os elementos
- **Tablet** (768px-1024px): Layout adaptado com reorganização de elementos
- **Mobile** (<768px): Layout otimizado para telas pequenas

## ♿ Acessibilidade

- **Navegação por teclado**: Todos os elementos são navegáveis via teclado
- **Leitores de tela**: Suporte completo com ARIA labels
- **Contraste**: Alto contraste para melhor legibilidade
- **Redução de movimento**: Respeita preferências de acessibilidade

