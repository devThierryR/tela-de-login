# 💻 Login & Registration Form (Página de Login e Registro)

Este é um projeto de interface de usuário (UI) para uma tela de login e criação de conta. O layout foi construído com foco em um design moderno, no estilo "cartão flutuante", dividindo a tela entre uma área de boas-vindas e um formulário de registro. 

## ✨ Funcionalidades

- **Design em Cartão:** Layout centralizado na tela com bordas arredondadas e sombras sutis (`box-shadow`), dando um aspecto elegante e flutuante.
- **Totalmente Responsivo:** O layout se adapta perfeitamente a diferentes tamanhos de tela. No desktop, apresenta um formato de duas colunas (lado a lado). Em dispositivos móveis (telas menores que 768px), os elementos são empilhados verticalmente para facilitar a leitura e a navegação.
- **Efeitos de Transição (Hover):** Botões animados que aumentam levemente de tamanho e escurecem ao passar o mouse, proporcionando um bom feedback visual ao usuário.
- **Formulário Estilizado:** Inputs limpos sem bordas pesadas, com mudança de cor no estado `:focus` (quando o usuário clica para digitar), guiando a atenção.
- **Ícones Alinhados:** Espaço dedicado a ícones de redes sociais organizados em linha usando Flexbox.

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Estruturação semântica da página (uso de divs, formulários e botões).
- **CSS3:** Estilização completa do projeto, incluindo:
  - **CSS Grid:** Utilizado para criar a estrutura principal do cartão e dividir as colunas (`1fr 2fr`).
  - **Flexbox:** Utilizado para centralizar elementos nas seções de login e registro, além de alinhar ícones e espaçar o formulário.
  - **Media Queries:** Implementação da responsividade do zero (Mobile-first adaptado).
  - **Box Model Avançado:** Uso de `box-sizing: border-box` e `gap` para um controle perfeito de espaçamentos.

## 🚀 Como executar o projeto

1. Faça o download ou clone este repositório para o seu computador.
2. Certifique-se de que os arquivos `index.html` e o arquivo de estilos (ex: `style.css`) estejam na mesma pasta.
3. Dê um duplo clique no arquivo `index.html` para abri-lo diretamente no seu navegador padrão (Chrome, Firefox, Edge, Safari, etc).
4. (Opcional) Se estiver usando o VS Code, você pode usar a extensão **Live Server** para visualizar o projeto e ver as alterações em tempo real.

## 📱 Demonstração

O projeto conta com dois estados principais:
- **Desktop:** Cartão central com barra verde à esquerda e formulário branco à direita.
- **Mobile:** Fundo verde no topo e formulário na parte inferior, ocupando 100% da largura da tela com margens de respiro confortáveis para toque.

---
*Projeto desenvolvido para fins de estudo e aprimoramento em HTML e CSS.*
