# 🚀 Dia 2: Estrutura e Semântica HTML, Formulários e Listas

## 🎯 Objetivo da Aula
Aprofundar o uso do HTML com foco em organização, semântica e criação de formulários interativos.

---

## 1. Listas em HTML

As listas são fundamentais para organizar informações de forma hierárquica ou sequencial.

### 🔹 Lista Não Ordenada (`<ul>`)
Usada quando a ordem dos itens não altera o sentido do conteúdo.

```html
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
</ul>
```

### 🔹 Lista Ordenada (`<ol>`)
Usada para sequências lógicas, passos ou rankings.

```html
<ol>
  <li>Primeiro Passo</li>
  <li>Segundo Passo</li>
</ol>
```

### 🔹 Lista de Definição (`<dl>`)
Ideal para glossários, onde temos um termo (`<dt>`) e sua descrição (`<dd>`).

```html
<dl>
  <dt>HTML</dt>
  <dd>Linguagem de marcação para estruturação web.</dd>
</dl>
```

---

## 2. HTML Semântico

### O que é?
O uso de tags que possuem **significado real** além da aparência, o que beneficia diretamente:
*   **Acessibilidade:** Leitores de tela entendem a estrutura.
*   **SEO:** Buscadores como Google indexam melhor o conteúdo.
*   **Manutenibilidade:** Código mais fácil de ler para outros desenvolvedores.

### Principais Tags Semânticas
| Tag | Função |
| :--- | :--- |
| `<header>` | Cabeçalho do site ou de uma seção específica. |
| `<nav>` | Conjunto principal de links de navegação. |
| `<main>` | Conteúdo central e único da página. |
| `<section>` | Agrupamento de conteúdos temáticos relacionados. |
| `<article>` | Conteúdo independente e reutilizável (ex: post de blog). |
| `<aside>` | Conteúdo lateral ou relacionado indiretamente. |
| `<footer>` | Rodapé com informações de contato, autor ou copyright. |

### Exemplo de Estrutura Semântica
```html
<header>
  <h1>Meu Site</h1>
  <nav>
    <ul>
      <li><a href="#">Início</a></li>
    </ul>
  </nav>
</header>

<main>
  <section>
    <h2>Sobre</h2>
    <p>Conteúdo da seção aqui...</p>
  </section>
</main>

<footer>
  <p>&copy; 2024 Meu Projeto</p>
</footer>
```

---

## 3. Formulários HTML

A ponte principal entre o usuário e o servidor para coleta de dados.

### Tipos de Input Comuns
| Tipo | Descrição |
| :--- | :--- |
| `text` | Campo de texto simples. |
| `email` | Valida automaticamente se o formato é de um e-mail. |
| `password` | Oculta os caracteres digitados. |
| `radio` | Seleção única entre várias opções. |
| `checkbox` | Seleção de múltiplas opções. |
| `submit` | Botão que envia o formulário. |

### Exemplo Prático de Formulário
```html
<form action="/submit" method="POST">
  <label for="nome">Nome:</label>
  <input type="text" id="nome" name="nome" placeholder="Digite seu nome" required>

  <label for="email">Email:</label>
  <input type="email" id="email" name="email" required>

  <fieldset>
    <legend>Gênero:</legend>
    <input type="radio" id="masc" name="genero" value="m">
    <label for="masc">Masculino</label>
    <input type="radio" id="fem" name="genero" value="f">
    <label for="fem">Feminino</label>
  </fieldset>

  <button type="submit">Enviar Cadastro</button>
</form>
```

### Atributos Cruciais de Validação
*   `required`: O campo deve ser preenchido obrigatoriamente.
*   `placeholder`: Texto de dica dentro do campo antes da digitação.
*   `pattern`: Validação via Regex (Expressões Regulares).
*   `minlength` / `maxlength`: Limite de caracteres.

---

## 📝 Exercícios de Fixação

### Exercício 1
Crie um arquivo HTML que contenha uma lista de compras (`<ul>`) e uma lista de passos para um tutorial (`<ol>`).

### Exercício 2
Monte a estrutura de uma página de notícias utilizando as tags `<header>`, `<nav>`, `<main>`, `<article>` e `<footer>`.

### Exercício 3
Crie um formulário de contato completo com campos de Nome, Email, Assunto e um botão de envio, garantindo que todos sejam obrigatórios.

---

## 🏁 Resumo
Nesta aula você aprendeu como organizar dados de forma lógica com **listas**, como dar significado à sua estrutura com **HTML Semântico** e como iniciar interações com o usuário através de **formulários**.

## 📅 Próximo Passo
No **Dia 3**, mergulharemos no mundo das cores e estilos com:
*   **Introdução ao CSS**
*   **Seletores e Cores**
*   **Box Model básico**
