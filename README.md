## 📄 Documentação

A documentação completa do projeto, contendo os requisitos funcionais, não funcionais, design e gestão, está disponível em PDF:

👉 [Especificação de Requisitos - Estação de Bebidas e Sabores](docs/WEBSITE%20-%20ESTAÇÃO%20DE%20BEBIDAS%20E%20SABORES.pdf)


# Estação de Bebidas e Sabores

Este projeto é um site institucional para o restaurante fictício "Estação de Bebidas e Sabores". O objetivo é apresentar, de forma clara e acessível, informações como o menu, promoções, pedidos e formas de contato com o restaurante.

## ✨ Tecnologias Utilizadas

- **HTML5**: Para a estrutura da página.
- **CSS3**: Utilizado na personalização do estilo visual de cada página.
- **Bootstrap 5**: Usado para facilitar a criação de um layout responsivo e moderno.
- **JavaScript** (planejado): Embora ainda não implementado, planejamos utilizar para melhorar a interatividade.
- **Acessibilidade**: Adoção de boas práticas como o uso de `aria-labels` e contraste adequado.

> 🔧 **Motivo das escolhas:**  
> Bootstrap foi escolhido por sua facilidade na criação de layouts responsivos. HTML e CSS puros foram utilizados para facilitar o controle visual e o aprendizado de fundamentos. JavaScript será incorporado posteriormente para funções interativas.

## 📚 Funcionalidades

- **Página Inicial** (`index.html`): Introdução ao restaurante com link para o menu.
- **Menu** (`menu.html`): Listagem de comidas, bebidas e sobremesas.
- **Promoções** (`promocoes.html`): Seção com ofertas especiais.
- **Pedidos** (`pedidos.html`): Explicação de como fazer pedidos online.
- **Sobre** (`sobre.html`): História e proposta do restaurante.
- **Contato** (`contato.html`): Formulário e informações de contato.
- **Política de Privacidade** (`politica-privacidade.html`): Informações sobre tratamento de dados pessoais conforme a LGPD.

## 🔐 Conformidade com a LGPD

Dando continuidade ao projeto, implementamos os seguintes requisitos de privacidade e proteção de dados:

- **Tipos de dados pessoais coletados**:
  - Nome, telefone, e-mail, mensagem/pedido (via formulários).

- **Bases legais aplicáveis**:
  - Consentimento do titular;
  - Execução de contrato ou procedimentos preliminares;
  - Legítimo interesse (sem prejuízo aos direitos do titular).

- **Principais riscos e medidas de mitigação**:
  - Riscos: vazamento, acesso indevido, uso indevido.
  - Medidas: minimização de dados, uso de HTTPS, comunicação segura por e-mail.

- **Direitos dos titulares**:
  - Acesso, retificação, exclusão e revogação do consentimento;
  - Canal de contato: **contato@seudominio.com**.

- **Arquitetura segura e transparente**:
  - Página dedicada de Política de Privacidade;
  - Design simples, informativo e acessível ao usuário.

- **Mecanismo de aceite**:
  - Implementação de banner de cookies visível ao usuário ao acessar o site;
  - Consentimento explícito sobre uso de dados e política de privacidade.

## 📂 Estrutura de Diretórios

```plaintext
estacao-bebidas-sabores/
│
├── index.html             # Página principal
├── menu.html              # Página com o cardápio
├── promocoes.html         # Promoções ativas
├── pedidos.html           # Informações de pedidos
├── sobre.html             # Sobre o restaurante
├── contato.html           # Formulário de contato
├── politica-privacidade.html # Política de privacidade
│
├── style.css              # Estilo geral
├── politica.css           # Estilo da política de privacidade
├── menu.css, etc.         # Estilos específicos de cada página
│
└── imagens/               # Imagens utilizadas
    ├── imagem1.jpg
    ├── imagem2.jpg
    └── imagem3.jpg

última edição 15/05/2025
