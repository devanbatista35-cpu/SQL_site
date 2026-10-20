# 🗄️ SQLá,bora!

> Blog educativo sobre **normalização de banco de dados**: 1FN, 2FN e 3FN explicadas com exemplos práticos de tabelas *antes* e *depois*.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![Status](https://img.shields.io/badge/status-concluído-brightgreen)
![Idioma](https://img.shields.io/badge/idioma-pt--BR-blue)

---

## 📖 Sobre o projeto

O **SQLá,bora!** é um blog estático criado por estudantes de computação para explicar, de forma simples e visual, como organizar tabelas em um banco de dados relacional para **evitar repetição de dados, reduzir inconsistências e facilitar a manutenção**.

O artigo parte de um exemplo do dia a dia (uma loja com clientes, pedidos e produtos) e mostra cada forma normal aplicada passo a passo, com tabelas comparativas destacando o que estava errado e como ficou depois da correção.

## 🎯 Conteúdo abordado

| Tópico | O que você vai aprender |
|---|---|
| **O que é normalização?** | Conceito, objetivo e um exemplo de redundância em pedidos e produtos |
| **1FN – Primeira Forma Normal** | Campos atômicos: um único valor por célula (telefones e endereços) |
| **2FN – Segunda Forma Normal** | Eliminação de dependências parciais em chaves primárias compostas |
| **3FN – Terceira Forma Normal** | Eliminação de dependências entre atributos não chave e de valores calculáveis |
| **Conclusão** | Resumo e importância das formas normais na criação de sistemas confiáveis |

### Resumo das formas normais

- **1FN:** cada campo guarda um único valor (atômico).
- **2FN:** todo atributo não chave depende da chave primária inteira.
- **3FN:** atributos não chave não dependem de outros atributos não chave.

## 🛠️ Tecnologias

- **HTML5** semântico
- **CSS3** (`style.css`)
- **Google Fonts**: [Syne](https://fonts.google.com/specimen/Syne) e [DM Sans](https://fonts.google.com/specimen/DM+Sans)

Nenhuma dependência, framework ou etapa de build é necessária.

## 📂 Estrutura do projeto

```
.
├── index.html          # Página principal do blog
├── style.css           # Estilos do site
├── imagens/
│   └── banco-de-dados.svg
├── fotos/              # Fotos dos integrantes da equipe
└── README.md
```

## 🚀 Como executar

1. Clone o repositório:
   ```bash
   git clone <url-do-repositorio>
   ```
2. Acesse a pasta do projeto:
   ```bash
   cd <nome-da-pasta>
   ```
3. Abra o arquivo `index.html` no navegador, ou sirva localmente:
   ```bash
   # com Python
   python -m http.server 8000
   ```
   Depois acesse `http://localhost:8000`.

## 👥 Equipe

| Integrante | Curso | Semestre | Área de interesse | GitHub |
|---|---|---|---|---|
| Vanessa Vieira dos Santos | Ciência da Computação | 2º | Sistemas Embarcados | [@devanbatista35-cpu](https://github.com/devanbatista35-cpu) |
| Gustavo Sacomani Rafael | Ciência da Computação | 2º | Modelagem e Machine Learning | [@GsacomaniR](https://github.com/GsacomaniR) |
| João Pedro Camargo Souza | Análise e Desenvolvimento de Sistemas | 2º | Análise de Dados | [@jpcs120308-cpu](https://github.com/jpcs120308-cpu) |
| Pamela Nunes de Campos | Análise e Desenvolvimento de Sistemas | 1º | Desenvolvimento de Software | [@pamelanunescampos](https://github.com/pamelanunescampos) |
| Henrique Granso | Ciência da Computação | 2º | Desenvolvimento Back-End | [@henriqueogranso](https://github.com/henriqueogranso) |

---

<p align="center">Feito com 💙 pela equipe do <strong>SQLá,bora!</strong></p>
