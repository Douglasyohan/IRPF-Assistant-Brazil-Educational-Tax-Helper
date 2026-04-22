# Assistente Educacional IRPF 2026

Aplicação web estática (HTML/CSS/JS) desenvolvida para auxiliar cidadãos brasileiros a entenderem as regras do Imposto de Renda Pessoa Física (IRPF) para o exercício de 2026, com foco especial na nova faixa de isenção.

## 📝 Descrição do Projeto

O projeto nasceu da necessidade de simplificar a comunicação fiscal. Ele atua como uma interface de "baixa carga cognitiva", traduzindo termos jurídicos e contábeis para uma linguagem acessível ao público leigo. O sistema guia o usuário por uma jornada de aprendizado antes de permitir a simulação de valores.

## ⚖️ Princípios de Compliance e Regras de Negócio

### 1\. Isenção Atualizada

O motor de cálculo foi ajustado para a nova diretriz de 2026:

  * **Piso de Isenção:** R$ 5.000,00 mensais.
  * **Base Anual:** R$ 60.000,00.
  * **Lógica:** O imposto é simulado apenas sobre o excedente da base de isenção, considerando deduções por dependentes e saúde.

### 2\. Privacidade e Segurança

  * **Zero Backend:** Não existem bancos de dados ou APIs externas.
  * **Local Storage:** Os dados são salvos apenas no navegador do usuário para persistência temporária.
  * **Segurança de Dados:** Nenhuma informação financeira sai do dispositivo do usuário.

### 3\. Pilares de UX (User Experience)

  * **Educação Primeiro:** É obrigatório passar pelo bloco didático antes da ferramenta de cálculo.
  * **Linguagem Cidadã:** Termos como "Deduções" são apresentados como "Descontos por gastos essenciais".
  * **Acessibilidade:** Interface limpa, mobile-first e sem elementos visuais distrativos.

## 🛠️ Tecnologias Utilizadas

  * **HTML5:** Estrutura semântica.
  * **CSS3:** Design responsivo utilizando Variáveis CSS para padronização de cores.
  * **Vanilla JavaScript:** Lógica de cálculo e manipulação de DOM sem dependências de frameworks.

## 📂 Estrutura do Código

A correção aplicada nesta versão focou em:

1.  **Documentação JSDoc:** Comentários nas funções JavaScript para facilitar a manutenção.
2.  **Remoção de Emojis:** Interface limpa seguindo padrões profissionais de design institucional.
3.  **Analogias Didáticas:** Inclusão da explicação de imposto como "Taxa de Condomínio" no Passo 1.

## 🚀 Como Executar

1.  Faça o download do arquivo `index.html`.
2.  Abra o arquivo em qualquer navegador moderno (Chrome, Firefox, Edge ou Safari).
3.  Nenhuma conexão com a internet é necessária após o carregamento inicial.

-----

## 👨‍💻 Desenvolvedor

**Douglas Yohan**
Analista de Infraestrutura e Segurança | Estudante de Ciências Contábeis

  * [LinkedIn](https://www.google.com/search?q=https://linkedin.com/in/douglasyohan)
  * [GitHub](https://www.google.com/search?q=https://github.com/Douglasyohan)
  * [Lattes](https://www.google.com/search?q=https://lattes.cnpq.br/4064564945245811)

-----

**Nota:** Esta ferramenta é um guia educativo e não substitui o Programa Gerador de Declaração (PGD) da Receita Federal do Brasil.# 🧾 IRPF Assistant (Brazil) — Educational Tax Helper

## 📌 Description

A simple, privacy-first web assistant designed to help Brazilian users understand and prepare for their Income Tax (IRPF) declaration. This tool does **not** file taxes — it educates and guides users through the process in a clear and accessible way.

---

## 🎯 Purpose

This project was built to reduce confusion around Brazilian income tax by:

* Explaining how IRPF works in simple terms
* Helping users understand if they may need to declare
* Guiding users step-by-step through their financial information
* Organizing data before using the official government system

---

## ⚠️ Disclaimer

> This application is **not affiliated with Receita Federal** and does **not replace official tools**.
> All results are **educational estimates only**.
> Users are fully responsible for their final tax declaration.

---

## 🧠 Core Concept

The system is designed around three pillars:

### 1. Education

Users first learn how income tax works before interacting with the assistant.

### 2. Assistance

A guided, conversational interface helps users input and understand their financial situation.

### 3. Decision Support

The system applies tax rules to provide insights such as:

* احتمال need to declare
* potential risks or alerts
* structured financial summary

---

## 🏗️ Project Structure

```
/
├── index.html
├── styles.css
├── script.js
├── /modules
│   ├── rules.js        # Tax rules engine (IRPF logic)
│   ├── assistant.js    # Conversational flow
│   ├── ui.js           # Interface rendering
│   └── storage.js      # Local data persistence
└── README.md
```

---

## ⚙️ Technologies

* HTML5
* CSS3
* Vanilla JavaScript
* LocalStorage (client-side only)
* Optional: PWA support

---

## 🔐 Privacy First

* No backend
* No data collection
* No external storage
* All user data stays in the browser

---

## 📊 Key Features

* 📘 Educational introduction (beginner-friendly)
* 🤖 Interactive assistant (step-by-step guidance)
* 📈 Basic tax estimation (non-official)
* ⚠️ Smart alerts (risk indicators)
* 📁 Data organization for official declaration
* 💾 Local save (via LocalStorage)

---

## 📌 Tax Rules Coverage (IRPF 2026)

The assistant considers:

* Annual income thresholds
* Exempt income scenarios
* Asset ownership
* Investments and stock market activity
* Capital gains (sale of assets)
* Foreign income

⚠️ All rules are simplified for educational purposes.

---

## 🚀 Deployment

This is a static application and can be deployed easily using:

* Netlify
* GitHub Pages
* Vercel (static mode)

### Example (Netlify):

1. Upload project files
2. Set publish directory to root
3. Deploy

---

## 📈 Roadmap

### MVP

* Core assistant
* Basic rules engine
* Educational content

### Next Steps

* PWA (offline support)
* Improved UX
* Expanded tax scenarios

### Future Vision

* Integration with economic data APIs
* Personalized insights
* Optional backend for advanced features

---

## 🧩 Contribution

This project is designed as a learning and utility tool. Contributions are welcome for:

* UX improvements
* Tax rule updates
* Accessibility enhancements

---

## 📎 License

MIT License — free to use and modify.

---

## 💡 Final Note

This project is not about replacing the tax system —
it's about making people **understand it better** before they use it.
