# Copilot Instructions for Quizzparaprogramadores

## Visão Geral do Projeto
Este projeto é um site estático de perguntas e respostas para programadores, com páginas HTML, estilos CSS e imagens. Não há backend ou scripts dinâmicos presentes.

## Estrutura Principal
- `index.html`: Página principal do quiz.
- `sobremim.html`: Página "Sobre mim" do autor.
- `assets/style.css`: Folha de estilos global para todas as páginas.
- `imagens/`: Armazena imagens usadas no site.

## Convenções e Padrões
- **HTML**: Estrutura sem frameworks, apenas HTML puro. Use semântica básica (`<header>`, `<main>`, `<footer>`, etc.) e mantenha a navegação simples.
- **CSS**: Centralize estilos em `assets/style.css`. Prefira classes descritivas e evite estilos inline.
- **Imagens**: Referencie imagens do diretório `imagens/` usando caminhos relativos.
- **Licença**: Consulte o arquivo `LICENSE` para informações de uso.

## Fluxos de Trabalho
- Não há processos de build, testes automatizados ou scripts de deploy.
- Para atualizar estilos, edite diretamente `assets/style.css`.
- Para adicionar perguntas ou conteúdo, edite os arquivos HTML.

## Integrações e Dependências
- Não há dependências externas, bibliotecas JS ou integrações com APIs.

## Exemplos de Padrões
- Para adicionar uma nova imagem:
  ```html
  <img src="imagens/nome-da-imagem.png" alt="Descrição" />
  ```
- Para aplicar um estilo:
  ```html
  <div class="container">
    ...
  </div>
  ```
  E defina em `assets/style.css`:
  ```css
  .container {
    max-width: 800px;
    margin: 0 auto;
  }
  ```

## Recomendações para Agentes AI
- Mantenha o código simples e legível.
- Siga a estrutura de diretórios existente.
- Evite adicionar frameworks ou dependências externas sem solicitação explícita.
- Documente mudanças relevantes diretamente nos arquivos HTML ou CSS, se necessário.

---

Se alguma seção estiver incompleta ou pouco clara, por favor, forneça feedback para que as instruções sejam aprimoradas.