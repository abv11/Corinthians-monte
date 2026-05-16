# ⚫ Corinthians Monte — Site Informativo Oficial

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
  <img src="https://img.shields.io/badge/MPA-121212?style=for-the-badge&logo=googlechrome&logoColor=white">
  <img src="https://img.shields.io/badge/LTP2-IFPE-black?style=for-the-badge">
  <img src="https://img.shields.io/badge/STATUS-FINALIZADO-success?style=for-the-badge">
</p>

<p align="center">
  <img width="100%" src="https://images.unsplash.com/photo-1547347298-4074fc3086f0?q=80&w=1600&auto=format&fit=crop">
</p>

---

# 🏴 Sobre o Projeto

O **Corinthians Monte** é um sistema web estático desenvolvido como atividade da disciplina **Linguagem Técnica de Programação 2 (LTP2)** do curso **Técnico Integrado em Informática para Internet** do Instituto Federal de Pernambuco.

O projeto consiste em um **site informativo institucional** desenvolvido exclusivamente em **HTML puro**, utilizando arquitetura **MPA (Multi-Page Application)**.

O desenvolvimento teve como foco:

* organização estrutural;
* navegação intuitiva;
* separação modular de páginas;
* acessibilidade;
* clareza na disposição das informações;
* boas práticas de estruturação HTML.

---

# 🎯 Objetivos do Sistema

O sistema foi projetado para permitir que usuários:

✔️ Naveguem entre páginas independentes  
✔️ Conheçam a história do clube  
✔️ Visualizem títulos conquistados  
✔️ Consultem informações do elenco  
✔️ Utilizem uma interface simples e funcional  

---

# 🌐 Link do Projeto

O site já está publicado e pode ser acessado online aqui:

👉 **[Clique aqui para acessar o site](https://abv11.github.io/Corinthians-monte/)**

---

# 🗺️ Arquitetura de Navegação

O site foi estruturado com navegação bidirecional entre a página principal (`index.html`) e as páginas secundárias.

### Fluxo de Navegação

* `index.html` ➜ `historia.html`
* `index.html` ➜ `titulos.html`
* `index.html` ➜ `elenco.html`

As páginas secundárias também possuem retorno para a página inicial.

---

# 📁 Estrutura de Arquivos

```txt
├── brasao.png
├── elenco.html
├── historia.html
├── index.html
├── README.md
└── titulos.html
```

---

# 🖥️ Estrutura de Navegação

```mermaid
graph TD

A[index.html]
A --> B[historia.html]
A --> C[titulos.html]
A --> D[elenco.html]

B --> A
C --> A
D --> A
```

---

# 📚 Tecnologias Utilizadas

| Tecnologia | Finalidade |
|---|---|
| HTML5 | Estruturação completa do sistema |
| Hyperlinks | Navegação entre páginas |
| Navegador Web | Execução local do projeto |

---

# ✨ Funcionalidades

## Requisitos Funcionais

* Sistema composto por múltiplas páginas HTML;
* Navegação interligada entre todas as páginas;
* Página inicial institucional;
* Página dedicada à história do clube;
* Página de títulos e conquistas;
* Página destinada ao elenco.

---

# 🔒 Requisitos Não Funcionais

* Desenvolvimento exclusivamente em HTML;
* Compatibilidade com navegadores modernos;
* Execução local sem necessidade de servidor;
* Organização modular dos arquivos;
* Navegação clara e objetiva.

---

# 📖 Documento de Requisitos de Software

## 📌 Informações Acadêmicas

| Campo | Informação |
|---|---|
| Instituição | Instituto Federal de Pernambuco |
| Curso | Técnico Integrado em Informática para Internet |
| Disciplina | Linguagem Técnica de Programação 2 |
| Docente | Carlos Fernandes |
| Local | Palmares — PE |
| Data | 5 de maio de 2026 |

---

## 👩‍💻 Discentes

* Angélica Benigno de Vasconcelos
* Laura Fernanda Galdino Ramos

---

# 📑 Sumário do Documento de Requisitos

```txt
1. Prefácio
2. Introdução
3. Glossário
4. Definição de Requisitos do Usuário
5. Arquitetura do Sistema
6. Especificação de Requisitos do Sistema
7. Modelos de Sistema
8. Evolução do Sistema
9. Apêndices
```

---

# 📌 Prefácio

Este documento apresenta a especificação de requisitos do sistema **“Site Informativo Corinthians Monte”**, desenvolvido como atividade acadêmica da disciplina **LTP2**.

Seu principal objetivo é documentar formalmente:

* funcionalidades;
* estrutura;
* requisitos;
* restrições;
* possibilidades futuras de expansão do sistema.

---

# 📘 Introdução

O projeto consiste em um sistema web estático voltado para apresentação institucional do clube fictício **Corinthians Monte**.

Toda a aplicação foi desenvolvida exclusivamente com HTML, visando:

* prática de arquitetura MPA;
* estruturação semântica;
* organização de páginas web;
* utilização correta de hyperlinks;
* padronização estrutural;
* experiência de navegação;
* documentação técnica.

---

# 📚 Glossário Técnico

| Termo | Definição |
|---|---|
| HTML | Linguagem de marcação utilizada para estruturar páginas web |
| Hyperlink | Elemento responsável pela navegação entre páginas |
| MPA | Multi-Page Application |
| Requisito Funcional | Define comportamentos do sistema |
| Requisito Não Funcional | Define restrições e qualidades |

---

# 📋 Requisitos do Usuário

| Código | Descrição |
|---|---|
| RU01 | Acessar página inicial |
| RU02 | Navegar entre páginas |
| RU03 | Visualizar história do clube |
| RU04 | Consultar títulos |
| RU05 | Visualizar elenco |

---

# ⚙️ Requisitos do Sistema

## Funcionais

| Código | Descrição |
|---|---|
| RF01 | Possuir quatro páginas HTML |
| RF02 | Interligação entre páginas |
| RF03 | Página inicial com menu |
| RF04 | Página de história |
| RF05 | Página de títulos |
| RF06 | Página de elenco |

---

## Não Funcionais

| Código | Descrição |
|---|---|
| RNF01 | Desenvolvimento apenas em HTML |
| RNF02 | Compatibilidade com navegadores modernos |
| RNF03 | Execução local |
| RNF04 | Organização correta dos arquivos |
| RNF05 | Navegação clara |

---

# 🔮 Evolução do Projeto

O sistema foi planejado para possíveis expansões futuras, incluindo:

* estilização visual utilizando CSS;
* implementação de interatividade com JavaScript;
* responsividade para dispositivos móveis;
* integração com banco de dados;
* autenticação de usuários;
* consumo de APIs;
* transformação do sistema em aplicação dinâmica.

---

# 📷 Preview do Projeto

<p align="center">
  <img width="100%" src="https://images.unsplash.com/photo-1511886929837-354d827aae26?q=80&w=1600&auto=format&fit=crop">
</p>

---

# 🚀 Como Executar

```bash
# Clone o repositório
git clone https://github.com/abv11/Corinthians-monte.git

# Abra o arquivo index.html no navegador
```

---

# 📁 Convenções de Nomeação

* arquivos em letras minúsculas;
* nomes sem espaços;
* organização modular;
* separação lógica dos arquivos.

---

# 🏛️ Instituição

Projeto acadêmico desenvolvido no Instituto Federal de Pernambuco, no curso Técnico Integrado em Informática para Internet, como atividade da disciplina Linguagem Técnica de Programação 2 (LTP2).

---

# 📄 Licença

Projeto desenvolvido exclusivamente para fins educacionais e acadêmicos.

---

<p align="center">
  <b>Corinthians Monte © 2026</b><br>
  Desenvolvido para a disciplina de LTP2 — IFPE Campus Palmares
</p>
