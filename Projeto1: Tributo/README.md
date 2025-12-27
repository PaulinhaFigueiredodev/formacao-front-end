# Projeto 1: Tributo

Este projeto consiste em uma **página de tributo à banda The Offspring**, desenvolvida com **HTML e CSS puro**, inspirada no layout de um **jornal editorial**.

Como camada adicional de prática, o projeto inclui uma **página intermediária que simula um iPad**, criada apenas com HTML e CSS, funcionando como uma chamada visual para acessar a reportagem principal.

---

## Estrutura do Projeto

```text
Projeto1: Tributo/
├── index.html
├── ipad-index.html
├── README.md
├── css/
│   ├── styles.css
│   └── ipad-styles.css
└── img/
    ├── the-offspring-1.jpg
    └── The-Offspring-2.jpg
````

---

## Página principal — Reportagem

**Arquivos utilizados:**

* `index.html`
* `css/styles.css`
* `img/the-offspring-1.jpg`
* `img/The-Offspring-2.jpg`

Página de tributo em formato de reportagem, com estilo visual inspirado em jornais impressos e conteúdo estático sobre a banda The Offspring.
A estrutura é organizada com cabeçalho editorial, texto introdutório, imagens com legenda, sessões de biografia, citações, curiosidades e link externo para mais informações.

---

## Página de chamada — Simulação de iPad

**Arquivos utilizados:**

* `ipad-index.html`
* `css/ipad-styles.css`

Página criada para praticar navegação entre páginas, simulando visualmente um iPad usando apenas HTML e CSS.
Possui um botão de ação que direciona para a página principal (`index.html`), funcionando como uma chamada visual para a reportagem.

---

## Tecnologias Utilizadas

* HTML5
* CSS3
* Flexbox

Não há uso de JavaScript ou bibliotecas externas.

---

## Como Rodar o Projeto

### Utilizando Python (Servidor Local)

1. Abra o terminal na pasta raiz do projeto (`Projeto1: Tributo`)
2. Execute o comando:

```bash
python -m http.server
```

3. Acesse no navegador:

```text
http://localhost:8000/ipad-index.html
```

4. Páginas disponíveis:

* `http://localhost:8000/ipad-index.html`
* `http://localhost:8000/index.html`

---

### Utilizando Live Preview (VS Code)

1. Abra a pasta **Projeto1: Tributo** no Visual Studio Code
2. Instale a extensão **Live Preview** ou **Live Server**
3. Clique com o botão direito em `ipad-index.html` ou `index.html`
4. Selecione **Open with Live Preview** ou **Open with Live Server**

---

## Considerações

Projeto desenvolvido com foco em prática de HTML semântico, estilização com CSS, organização de arquivos, navegação entre páginas e simulação de componentes visuais sem uso de JavaScript.

