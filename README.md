# Documentação Go

## Descrição do Projeto

Este projeto tem como objetivo apresentar uma documentação educativa sobre a linguagem Go (Golang), abordando conceitos fundamentais da linguagem de forma simples, prática e organizada.

A documentação foi desenvolvida utilizando Markdown e automatizada com GitHub Actions para integração contínua e deploy da aplicação.

---

## Objetivos

- Explicar os principais conceitos da linguagem Go
- Demonstrar exemplos práticos em código
- Organizar conteúdos educativos em Markdown
- Utilizar CI/CD com GitHub Actions
- Publicar documentação automatizada

---

## Tecnologias Utilizadas

- Go (Golang)
- Markdown
- GitHub Actions
- GitHub Pages
- Zensical
- Git

---

## Estrutura da Documentação

| Arquivo | Conteúdo |
|---|---|
| introducao.md | Introdução à linguagem Go |
| variaveis.md | Declaração de variáveis |
| arrays.md | Arrays em Go |
| controle.md | Estruturas de controle |
| structs.md | Structs |
| goroutines.md | Concorrência com goroutines |
| channels.md | Comunicação entre goroutines |
| errors.md | Tratamento de erros |
| gomodules.md | Gerenciamento de dependências |
| testes.md | Testes automatizados |
| markdown.md | Sintaxe Markdown |

---

## Como executar o projeto localmente

### 1. Clonar o repositório

```bash
git clone https://github.com/impacta-gb/projeto-ctt-ap2-ti-girls.git
```

---

### 2. Entrar na pasta do projeto

```bash
cd projeto-ctt-ap2-ti-girls
```

---

### 3. Criar ambiente virtual

```bash
python -m venv venv
```

---

### 4. Ativar ambiente virtual

#### Windows (Git Bash)

```bash
source venv/Scripts/activate
```

---

### 5. Instalar dependências

```bash
pip install zensical
```

---

### 6. Executar documentação localmente

```bash
zensical serve
```

---

### 7. Abrir no navegador

```text
http://127.0.0.1:8000
```

---

## CI/CD com GitHub Actions

O projeto utiliza GitHub Actions para:

- validação automática da documentação
- build automatizado
- integração contínua
- deploy automatizado

O workflow está localizado em:

```text
.github/workflows/docs.yml
```

---

## Organização do Projeto

```text
docs/
.github/workflows/
README.md
zensical.toml
```

---

## Integrantes

| Nome | RA |
|---|---|
| Daiana Fernanda Oliveira da Conceição | 2404196 |
| Maria Eduarda Rodrigues Ruiz | 2500104 |
| Maria Eduarda Santos Soares | 2303542 |
| Mariana Alves Mendes | 2403346 |

---

## Conclusão

Este projeto foi desenvolvido com foco no aprendizado da linguagem Go, documentação em Markdown e utilização de práticas modernas de versionamento e automação com GitHub Actions.
