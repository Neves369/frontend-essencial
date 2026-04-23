# Dia 1: Introdução ao Frontend e HTML

## 🎯 Objetivo da Aula

Entender os conceitos iniciais de desenvolvimento web e aprender a estrutura básica e as principais tags do HTML.

---

# 1. O que é Frontend?

## 🔹 Frontend

É a parte **visual de um site**, ou seja, tudo aquilo que o usuário vê e interage.

### Tecnologias principais:

- **HTML** → estrutura
    
- **CSS** → estilo
    
- **JavaScript** → comportamento
    

---

## 🔹 Backend

É a parte que roda no servidor:

- Processa dados
    
- Conecta com banco de dados
    
- Define regras do sistema
    

---

## 🔹 Tipos de Linguagens

- **Marcação:** HTML
    
- **Estilização:** CSS
    
- **Programação:** JavaScript
    

---

# 2. Estrutura Básica do HTML

Todo documento HTML segue uma estrutura padrão:

```html
<!DOCTYPE html>
<html>
<head>
</head>
<body>
</body>
</html>
```

## Explicação das partes:

### 🔸 `<!DOCTYPE html>`

Define que o documento usa **HTML5**.

---

### 🔸 `<html>`

Elemento raiz da página.

---

### 🔸 `<head>`

Contém **informações invisíveis**:

- Metadados
    
- Título da página
    
- Configurações
    

---

### 🔸 `<body>`

Contém **tudo que aparece na tela**:

- Textos
    
- Imagens
    
- Links
    
- Botões
    

---

# 3. Metadados Importantes

Dentro da tag `<head>` usamos:

```html
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="Descrição do site">
<meta name="author" content="Seu nome">
```

## Para que servem?

- **charset** → suporte a acentos
    
- **viewport** → responsividade
    
- **description** → SEO (Google)
    
- **author** → autor da página
    

---

# 4. Tags Essenciais do HTML

## 🔹 Cabeçalhos (Títulos)

```html
<h1>Mais importante</h1>
<h2>...</h2>
<h6>Menos importante</h6>
```

 Usados para organizar conteúdo (hierarquia)

---

## 🔹 Parágrafos

```html
<p>Isso é um parágrafo</p>
```

---

## 🔹 Formatações de Texto

| Tag        | Função                         |
| ---------- | ------------------------------ |
| `<b>`      | Negrito visual                 |
| `<strong>` | Negrito semântico (importante) |
| `<i>`      | Itálico                        |
| `<u>`      | Sublinhado                     |
| `<mark>`   | Destaque                       |
| `<small>`  | Texto pequeno                  |
| `<del>`    | Texto removido                 |
| `<ins>`    | Texto inserido                 |
| `<sub>`    | Subscrito                      |
| `<sup>`    | Sobrescrito                    |

---

###  Exemplo:

```html
<p><strong>Importante</strong></p>
<p><i>Itálico</i></p>
<p>H<sub>2</sub>O</p>
<p>10<sup>2</sup></p>
```

---

#  5. Links

## 🔹 Criando um link:

```html
<a href="https://www.google.com">Ir para o Google</a>
```

## 🔹 Abrir em nova aba:

```html
<a href="https://www.google.com" target="_blank">Abrir</a>
```

---

# 6. Divisões: `div` vs `span`

## 🔹 `<div>` (Bloco)

- Ocupa toda a largura
    
- Quebra linha
    

```html
<div>Sou uma div</div>
```

---

## 🔹 `<span>` (Inline)

- Não quebra linha
    
- Usado dentro de textos
    

```html
<p>Texto com <span>destaque</span></p>
```

---

## 📌 Diferença visual

| Elemento | Tipo   | Comportamento           |
| -------- | ------ | ----------------------- |
| `<div>`  | Bloco  | Quebra linha            |
| `<span>` | Inline | Continua na mesma linha |

---

# 🎨 7. Introdução ao CSS (básico)

CSS pode ser usado dentro do HTML:

```html
<style>
body {
    font-family: sans-serif;
}
</style>
```

---

##  Exemplo simples:

```html
<p style="color: blue;">Texto azul</p>
```

---

#  8. Boas Práticas

✅ Use HTML semântico (`strong` ao invés de `b`)  
✅ Organize bem a estrutura  
✅ Use indentação (código bonito)  
✅ Sempre teste no navegador

---

#  9. Atividades Práticas

## 📝 Exercício 1

Crie um HTML com:

- Um título (`h1`)
    
- Dois parágrafos
    
- Um texto em negrito e itálico
    

---

## 📝 Exercício 2

Adicione:

- Um link para um site
    
- Uma `div` com cor de fundo
    
- Um `span` dentro de um texto
    

---

## 📝 Exercício 3

Monte uma página com:

- Cabeçalho
    
- Conteúdo
    
- Rodapé
    

---

#  Resumo Final

Você aprendeu:

✅ O que é frontend  
✅ Estrutura básica do HTML  
✅ Principais tags  
✅ Links  
✅ Diferença entre div e span  
✅ Noções básicas de CSS

---

# 📚 Próximo Passo

No **Dia 2**, você vai aprender:

- Listas    
- HTML semântico
- Formulários
---
