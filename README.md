# Fábrica de Histórias com IA - Landing Page

Uma landing page moderna e responsiva para um ebook sobre criação de histórias infantis usando Inteligência Artificial.

## 📋 Sobre o Projeto

Esta landing page foi desenvolvida para promover o ebook "Fábrica de Histórias com IA", que ensina pais a criar histórias educativas para crianças usando ferramentas de IA. A página apresenta os benefícios do produto, depoimentos de clientes e um call-to-action claro.

## 🚀 Tecnologias Utilizadas

- **HTML5**: Estrutura semântica e acessível
- **CSS3**: Estilos modernos com animações e responsividade
- **JavaScript**: Interatividade e funcionalidades dinâmicas
- **Tailwind CSS**: Framework CSS via CDN para estilização rápida
- **Google Fonts**: Tipografia Inter para uma aparência profissional

## 📁 Estrutura do Projeto

```
landingpage/
├── .github/
│   └── copilot-instructions.md    # Instruções para GitHub Copilot
├── css/
│   └── main.css                   # Estilos personalizados
├── js/
│   └── main.js                    # Funcionalidades JavaScript
├── index.html                     # Página principal
└── README.md                      # Este arquivo
```

## 🎨 Características

### Design
- **Responsive**: Adaptado para desktop, tablet e mobile
- **Moderno**: Design clean com gradientes e animações suaves
- **Acessível**: Estrutura semântica e navegação por teclado
- **Performance**: Carregamento otimizado com fontes e recursos externos

### Funcionalidades
- **Animações**: Efeitos de fade-in e hover em elementos
- **Navegação suave**: Scroll suave entre seções
- **Interatividade**: Botões com efeitos visuais
- **Configurabilidade**: Sistema de configuração para personalização

### Seções
1. **Hero**: Apresentação principal com CTA
2. **Benefícios**: Três principais vantagens do produto
3. **Conteúdo**: O que será aprendido no ebook
4. **Depoimentos**: Feedback de clientes satisfeitos
5. **CTA Final**: Chamada para ação secundária
6. **Rodapé**: Informações de copyright

## 🛠️ Como Executar

### Opção 1: Abrir diretamente no navegador
1. Navegue até a pasta do projeto
2. Clique duas vezes no arquivo `index.html`
3. A página será aberta no seu navegador padrão

### Opção 2: Servidor local (recomendado)
1. Abra o terminal na pasta do projeto
2. Execute um dos comandos abaixo:

**Com Python:**
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

**Com Node.js:**
```bash
# Instale o http-server globalmente
npm install -g http-server

# Execute o servidor
http-server
```

**Com Live Server (VS Code):**
1. Instale a extensão "Live Server" no VS Code
2. Clique com o botão direito em `index.html`
3. Selecione "Open with Live Server"

3. Acesse `http://localhost:8000` no navegador

## 🔧 Personalização

### Cores
As cores principais podem ser alteradas no arquivo `css/main.css`:

```css
:root {
  --primary-color: #40E0D0;      /* Cor principal (turquesa) */
  --secondary-color: #FFC72C;     /* Cor secundária (amarelo) */
  --surface-color: #98FF98;       /* Cor de superfície (verde claro) */
  --text-color: #333333;          /* Cor do texto */
  --background-color: #FFFFFF;    /* Cor de fundo */
}
```

### Conteúdo
Os textos podem ser alterados editando os elementos correspondentes no `index.html` ou através do sistema de configuração no `js/main.js`.

### Tipografia
Para alterar a fonte, modifique a importação no `index.html` e atualize a propriedade `font-family` no CSS.

## 📱 Responsividade

A landing page é totalmente responsiva com breakpoints para:
- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## ♿ Acessibilidade

- Estrutura semântica HTML5
- Contraste adequado entre cores
- Navegação por teclado
- Textos alternativos para ícones
- Tamanhos de fonte legíveis

## 🚀 Performance

### Otimizações implementadas:
- Carregamento assíncrono de fontes
- CSS minificado via CDN (Tailwind)
- Imagens otimizadas (placeholders SVG)
- JavaScript modular e eficiente

### Métricas esperadas:
- **First Contentful Paint**: < 1.5s
- **Largest Contentful Paint**: < 2.5s
- **Cumulative Layout Shift**: < 0.1

## 🔄 Versionamento

Para futuras atualizações:
1. Mantenha a estrutura de pastas organizada
2. Documente mudanças significativas
3. Teste em diferentes dispositivos e navegadores
4. Valide HTML e CSS antes do deploy

## 📞 Suporte

Para dúvidas ou sugestões sobre o código:
1. Verifique a documentação nos comentários do código
2. Consulte a estrutura no arquivo `copilot-instructions.md`
3. Teste as funcionalidades em diferentes navegadores

## 📄 Licença

Este projeto é um exemplo educacional. Adapte conforme necessário para seu uso específico.

---

**Desenvolvido com ❤️ para o projeto Fábrica de Histórias com IA**