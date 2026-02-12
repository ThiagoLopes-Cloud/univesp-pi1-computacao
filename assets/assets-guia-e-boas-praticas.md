# Uso e Boas Práticas da Pasta `assets/` – Projeto Integrador 1 (UNIVESP)

Este documento define como utilizar corretamente a pasta `assets/` dentro do repositório do Projeto Integrador 1, garantindo organização, padronização e clareza visual do projeto.

---

## 📁 Objetivo da Pasta `assets/`

A pasta `assets/` deve armazenar todos os arquivos visuais e recursos de apoio ao projeto, como imagens, diagramas e materiais gráficos utilizados na documentação ou apresentação do sistema.

Ela NÃO deve conter código-fonte ou documentos acadêmicos em PDF.

---

## 📂 Estrutura Recomendada

```
assets/
├── images/
├── diagrams/
└── presentations/
```

### 📸 `images/`

* Prints do sistema
* Logos
* Mockups de interface
* Imagens usadas no README ou na documentação

### 📊 `diagrams/`

* Diagramas UML
* Diagramas de arquitetura
* Modelagem de banco de dados
* Fluxogramas

### 📽 `presentations/` (opcional)

* Slides exportados em PDF
* Materiais visuais de apresentação

---

## ✅ Boas Práticas

### 1️⃣ Padronização de nomes

Use nomes descritivos e em minúsculo, separados por hífen:

Correto:

* diagrama-arquitetura-v1.png
* fluxo-login-usuario.png
* modelo-er-banco-dados.png

Evitar:

* imagem1.png
* print-final.png
* novo-diagrama.png

---

### 2️⃣ Controle de versão visual

Se atualizar um diagrama, prefira:

* Atualizar o arquivo mantendo o mesmo nome
  ou
* Usar sufixo de versão (v1, v2) apenas quando necessário

Evite criar múltiplas versões desnecessárias que confundam o grupo.

---

### 3️⃣ Organização por contexto

Se o projeto crescer, é possível criar subpastas específicas:

```
assets/diagrams/backend/
assets/diagrams/frontend/
```

---

### 4️⃣ Tamanho dos arquivos

* Evitar imagens muito pesadas
* Preferir PNG ou SVG para diagramas
* Compactar imagens quando possível

Arquivos muito grandes deixam o repositório pesado e dificultam o versionamento.

---

## 🚫 O que NÃO deve ir em `assets/`

* Código-fonte
* PDFs oficiais da disciplina (devem ir em `docs/`)
* Atas de reunião
* Arquivos temporários

---

## 📌 Regra Geral

Se o arquivo é visual e ajuda a explicar o projeto, ele pertence à pasta `assets/`.

Se é documentação formal da disciplina, pertence à pasta `docs/`.

---

Documento mantido pelo grupo do Projeto Integrador 1 – UNIVESP.
