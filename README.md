# ♿ Landing Page Interativa - Cadeira de Rodas Motorizada Dellamed D800

Uma landing page interativa, responsiva e de alta conversão para o anúncio e venda particular de uma **Cadeira de Rodas Motorizada Dellamed D800** seminova. 

O projeto foi desenvolvido com foco em **UX/UI (Design Centrado no Usuário)**, aplicando princípios de alívio cognitivo, microinterações, visibilidade do estado do sistema (Heurísticas de Nielsen) e transparência nas informações financeiras e logísticas.

---

## 📸 Demonstração do Projeto

A aplicação conta com uma galeria interativa com visualizador dinâmico de fotos reais do produto, suporte a alternância de tema (Dark/Light Mode), calculador de economia, simulador de frete/CEP e modais de conversão rápida para WhatsApp.

---

## 🚀 Funcionalidades Principais

- **🎨 Tema Dinâmico (Dark / Light Mode):** Alternador de tema acessível com transição suave que adapta todas as cores e contraste da página para leitura confortável em qualquer iluminação.
- **🖼️ Galeria de Imagens Interativa:**
  - Alternância rápida via miniaturas (thumbnails).
  - Modal de ampliação (*Zoom Viewer*) com descrições detalhadas da foto.
- **💰 Calculadora de Economia Real:** Comparativo visual de valor do produto novo em loja vs. seminovo oferecido, destacando o valor economizado e a porcentagem de desconto.
- **📍 Simulador de Logística de Retirada por CEP:**
  - Validação de formato de CEP.
  - Feedback visual automático informando a localização do comprador (Capão Bonito - SP, região do Sudoeste Paulista ou fora de alcance de retirada presencial).
- **💬 Integramento com WhatsApp (Modais de Conversão):**
  - Opções de mensagens pré-formatadas para facilitar o primeiro contato do interessado ("Verificar disponibilidade", "Agendar teste presencial", "Tirar dúvidas").
- **🔔 Toast Notifications:** Sistema de feedback visual temporário para ações do usuário (ex: alternância de tema, avisos).
- **📱 Design 100% Responsivo:** Layout adaptável para smartphones, tablets e desktops utilizando Tailwind CSS.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Estruturação semântica e acessível.
- **Tailwind CSS (via CDN):** Estilização moderna baseada em utilitários com suporte nativo a Dark Mode (`class`).
- **JavaScript (ES6+):** Manipulação de DOM, controle de estado da galeria, temas, simulador de CEP e modais.
- **FontAwesome 6:** Iconografia rica para elementos visuais e indicadores de status.
- **Google Fonts (Inter):** Tipografia moderna e legível.

---

## 📁 Estrutura de Arquivos

Para o correto funcionamento da galeria de fotos, a estrutura de arquivos no repositório deve estar organizadas da seguinte forma:

```text
├── index.html              # Arquivo HTML principal do projeto
├── README.md               # Documentação do repositório
├── VisaoGeral.jpeg         # Imagem real 1: Visão geral da cadeira
├── VistaLateral.jpeg       # Imagem real 2: Vista lateral do chassi
├── MotorTrava.jpeg         # Imagem real 3: Detalhe do motor 250W e trava
├── PneuTraseiro.jpeg       # Imagem real 4: Pneu traseiro maciço
└── RodaDiantairaApoio.jpeg # Imagem real 5: Roda dianteira 360° e apoio de pé
```

---

## ⚙️ Como Executar o Projeto

1. **Clonar o Repositório:**
   ```bash
   git clone https://github.com/seu-usuario/dellamed-d800-landing-page.git
   ```

2. **Acessar a pasta do projeto:**
   ```bash
   cd dellamed-d800-landing-page
   ```

3. **Abrir a aplicação:**
   - Como o projeto utiliza apenas **HTML5, Tailwind CSS e Vanilla JavaScript**, basta dar um duplo clique no arquivo `index.html` para abri-lo diretamente no seu navegador de preferência.
   - Alternativamente, utilize extensões como o **Live Server** no VS Code.

---

## 💡 Princípios de UX/UI Aplicados

- **Prevencão de Erros:** Alertas claros informando sobre a política de retirada apenas presencial antes que o comprador inicie a negociação.
- **Alívio Cognitivo:** Organização de especificações em cartões visuais (Grid) e destaques legíveis para peso suportado ($120\text{ kg}$), potência dos motores ($2 \times 250\text{W}$) e baterias.
- **Visibilidade do Estado do Sistema:** Microinterações com feedback visual imediato em cliques, alternâncias de imagens e envios de formulário.

---

## 📄 Licença

Este projeto é um modelo de demonstração e anúncio de landing page de código aberto disponível para fins de estudo e adaptação.
