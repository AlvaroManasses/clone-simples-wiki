# Desafio DIO: Estrutura de Site Similar à Wikipédia

Este projeto faz parte de um desafio do curso da **Digital Innovation One (DIO)**. O objetivo principal foi treinar a construção de uma estrutura de site semelhante à Wikipédia, aplicando os conhecimentos adquiridos sobre **semântica** e **acessibilidade** na linguagem HTML.

## Recursos Utilizados

### 1. **HTML Semântico**
   - Utilizamos as tags semânticas do HTML5 (`<header>`, `<nav>`, `<main>`, `<aside>`, `<footer>`) para estruturar o conteúdo da página de forma que os mecanismos de busca e leitores de tela possam entender melhor a hierarquia das informações.
   - O uso correto dessas tags melhora a acessibilidade e a experiência do usuário, especialmente para aqueles que dependem de tecnologias assistivas.

### 2. **Acessibilidade**
   - Implementamos atributos **ARIA** (Accessible Rich Internet Applications) para descrever melhor os elementos da página e suas funções, como `role` e `aria-labelledby`.
   - Também configuramos estilos CSS para melhorar o foco nos elementos interativos, como links e botões, usando `outline` para destacar os elementos focados.
   - A estrutura do site foi planejada para ser navegável por teclado, considerando boas práticas de acessibilidade.

### 3. **CSS**
   - Foi aplicado um layout flexível com `flexbox`, adaptando-se a diferentes tamanhos de tela e dispositivos.
   - Estilizamos a página com foco na legibilidade, utilizando uma paleta de cores contrastantes que atendem aos requisitos de acessibilidade para pessoas com deficiência visual.
   - Estilos de foco personalizados foram implementados para garantir que os usuários de teclado saibam onde está o foco na navegação.

### 4. **Links Internos**
   - Utilizamos âncoras para navegação dentro da página, permitindo ao usuário pular para diferentes seções do conteúdo com facilidade, algo muito comum em plataformas como a Wikipédia.

## Estrutura do Projeto

O projeto consiste em uma única página HTML, dividida em várias seções:
- **Cabeçalho**: Inclui a logo da empresa.
- **Navegação**: Links para diferentes partes da página.
- **Conteúdo Principal**: Inclui seções detalhadas sobre "Automação de Investimentos", abordando principais plataformas, métodos e estratégias.
- **Barra Lateral**: Links rápidos para seções específicas da página.
- **Rodapé**: Informações sobre direitos autorais.
