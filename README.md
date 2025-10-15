# 💻 Hashtag Watch - Simulação de Página de Produto Apple Watch
Este é um projeto de simulação de uma página de detalhes de produto do Apple Watch (pulseiras), desenvolvido para praticar e consolidar conhecimentos em HTML, CSS e JavaScript.

## 🌟 Funcionalidades
Navegação Estática: Estrutura de navegação de um site de e-commerce (barra superior).

Seleção de Opções de Produto:

Troca de Cores (com atualização do título do produto e das imagens de visualização).

Troca de Tamanhos de Caixa (41mm e 45mm), que altera o título do produto e aplica um efeito visual na imagem de visualização (zoom/escala).

Seleção da Imagem de Visualização principal a partir de miniaturas.

Visualização Dinâmica: As informações exibidas (título, cor e imagem principal) são atualizadas em tempo real com base nas escolhas do usuário, simulando a experiência de compra.

## 🚀 Tecnologias Utilizadas
Tecnologia	Descrição
HTML5	Estruturação semântica do conteúdo da página.
CSS3 (SCSS/BEM)	Estilização avançada com uso de @font-face (para simular a fonte "San Francisco"), Flexbox para layout responsivo, e uma estrutura modular de estilos (simulando SCSS/BEM com CSS puro para fins práticos).
JavaScript (Vanilla)	Manipulação do DOM para criar a interatividade dinâmica da seleção de opções (cores, tamanhos, e imagens) e atualização do título do produto.

Exportar para as Planilhas
### 📁 Estrutura do Projeto
.
├── index.html          # Estrutura principal da página
├── style.css           # Estilização (inclui as regras apresentadas)
├── script.js           # Lógica de interatividade (inclui o código apresentado)
└── imagens/            # Pasta com todas as imagens do produto
    ├── opcoes-cores/
    │   ├── imagens-azul-inverno/
    │   ├── imagens-verde-cipreste/
    │   └── ... (outras pastas de cores)
    └── outros-recursos/
        └── ... (selos e outros ícones)
## 🎯 O que aprendi neste projeto
Manipulação Avançada do DOM: Como selecionar e modificar elementos dinamicamente (e.g., innerText, src, classList.add/remove) em resposta a eventos de click em radio buttons.

Criação de Objetos para Dados: Utilização de objetos JavaScript para estruturar os dados do produto (cores, nomes de pasta, status de estoque), facilitando a gestão e atualização das informações.

Layout Profissional: Aplicação de CSS para replicar um design de e-commerce limpo e focado no produto, com atenção especial aos detalhes de UX (como o estado checked dos radio buttons).

Feito com 💙 e código.
