# 📋 Guia IR 2026

> Ferramenta educacional e de simulação do Imposto de Renda Pessoa Física 2026 — desenvolvida como projeto de Iniciação Científica.

---

## ⚠️ Aviso Legal

Esta ferramenta **não é da Receita Federal** e **não substitui o sistema oficial (Programa IRPF)**.  
É uma aplicação educacional que ajuda o usuário a entender o imposto, organizar informações e simular cenários de forma aproximada.  
Nenhum dado sai do navegador do usuário. Nenhum dado é enviado a servidores.

---

## 🎯 Objetivo

Criar uma ferramenta que:

1. **Ensina** o usuário do zero, sem termos técnicos
2. **Guia** passo a passo pela lógica do imposto de renda
3. **Simula** cenários de tributação de forma aproximada
4. **Organiza** as informações para uso no sistema oficial

Público-alvo: universitários e trabalhadores de baixa renda que nunca declararam ou têm dificuldade com o processo.

---

## ✨ Funcionalidades

### 📚 Bloco Educacional
- O que é o Imposto de Renda e para que serve
- Quem é obrigado a declarar (com critérios para 2026)
- O que precisa ser informado (rendimentos, bens, gastos)
- Como funciona a tabela progressiva de alíquotas
- O que acontece em caso de erro ou não entrega

### 🤖 Assistente de Simulação
- Conversa guiada em 6 passos
- Coleta: estado civil, dependentes, rendimentos, gastos dedutíveis, bens
- Comparação entre modelo simplificado (20%) e declaração completa
- Estimativa de imposto a pagar ou valor a restituir
- Alertas contextuais (renda de investimentos, limite de educação, etc.)
- Resumo final organizado pronto para consulta

---

## 🏗️ Tecnologia

| Item | Detalhe |
|------|---------|
| Stack | HTML5 + CSS3 + JavaScript vanilla |
| Arquitetura | Single-page, single-file (`index.html`) |
| Backend | Nenhum — 100% client-side |
| Armazenamento | Estado em memória (sessão apenas) |
| Dependências externas | Google Fonts (Sora + DM Serif Display) |
| Tamanho do arquivo | ~52 KB |

---

## 📁 Estrutura

```
guia-ir-2026/
└── index.html      # Aplicação completa (HTML + CSS + JS embutidos)
```

---

## 🚀 Como usar

Não há instalação. Basta abrir o arquivo no navegador:

```bash
# Clone ou baixe o repositório
git clone https://github.com/Douglasyohan/guia-ir-2026.git

# Abra o arquivo no navegador
open index.html
# ou arraste o arquivo para o navegador
```

Funciona completamente offline após o carregamento das fontes.

---

## 🧮 Critérios de Simulação (IRPF 2026 — ano-base 2025)

Os cálculos seguem a legislação vigente de forma aproximada:

**Tabela progressiva mensal (referência):**

| Faixa de renda mensal | Faixa anual | Alíquota | Dedução |
|---|---|---|---|
| Até R$ 5.000 | Até R$ 60.000 | 0% (isento) | — |
| R$ 5.001 – R$ 6.252 | R$ 60.001 – R$ 75.024 | 7,5% | R$ 4.500,00 |
| R$ 6.253 – R$ 7.664 | R$ 75.025 – R$ 91.968 | 15% | R$ 9.189,00 |
| R$ 7.665 – R$ 9.830 | R$ 91.969 – R$ 117.960 | 22,5% | R$ 15.624,00 |
| Acima de R$ 9.830 | Acima de R$ 117.960 | 27,5% | R$ 21.513,00 |

**Deduções consideradas:**
- INSS estimado (9% do salário, teto R$ 9.000)
- Dependentes: R$ 2.275,08 por pessoa (anual)
- Educação: até R$ 3.561,50 por pessoa (anual)
- Saúde: sem limite (gastos comprovados)
- Desconto simplificado: 20% da renda, máximo R$ 16.754,34

> **Nota:** Estes valores são referência para fins educacionais. Consulte sempre a legislação atualizada e um contador para sua declaração real.

---

## 📸 Estrutura da Interface

```
┌─────────────────────────────────────┐
│  Aviso legal (barra fixa no topo)   │
├─────────────────────────────────────┤
│  Header com logo e botão de acesso  │
├─────────────────────────────────────┤
│  Hero / apresentação                │
├─────────────────────────────────────┤
│  📚 BLOCO EDUCACIONAL               │
│   ├── O que é IR?                   │
│   ├── Quem precisa declarar?        │
│   ├── O que informar?               │
│   ├── Como o imposto é calculado?   │
│   └── E se errar ou não declarar?  │
├─────────────────────────────────────┤
│  🎯 CHAMADA PARA AÇÃO (CTA)         │
├─────────────────────────────────────┤
│  🤖 ASSISTENTE (6 passos)           │
│   ├── Passo 1: Estado civil         │
│   ├── Passo 2: Dependentes          │
│   ├── Passo 3: Rendimentos          │
│   ├── Passo 4: Gastos dedutíveis    │
│   ├── Passo 5: Bens                 │
│   └── Passo 6: Modelo de declaração │
├─────────────────────────────────────┤
│  📊 RESULTADO DA SIMULAÇÃO          │
│   ├── Preciso declarar?             │
│   ├── Comparação dos modelos        │
│   ├── Alertas contextuais           │
│   └── Resumo para declaração        │
├─────────────────────────────────────┤
│  Footer com links                   │
└─────────────────────────────────────┘
```

---

## 🔗 Contexto Acadêmico

Este projeto foi desenvolvido como parte de pesquisa de **Iniciação Científica** no curso de **Ciências Contábeis** da **UNICENTRO — Universidade Estadual do Centro-Oeste**, campus Guarapuava–PR.

Linha de pesquisa: educação financeira gamificada para universitários de baixa renda.  
Registro de propriedade intelectual: **App-Renda-Finanças$** (INPI).

---

## 👤 Autor

**Douglas Yohan**  
Estudante de Ciências Contábeis · UNICENTRO · Guarapuava–PR

[![LinkedIn](https://img.shields.io/badge/LinkedIn-douglasyohan-0A66C2?logo=linkedin)](https://www.linkedin.com/in/douglasyohan/)
[![GitHub](https://img.shields.io/badge/GitHub-Douglasyohan-181717?logo=github)](https://github.com/Douglasyohan)
[![Lattes](https://img.shields.io/badge/Lattes-CNPq-005A8C)](http://lattes.cnpq.br/4064564945245811)

---

## 📄 Licença

Este projeto é de uso educacional e acadêmico. Para uso comercial, entre em contato com o autor.

---

*Guia IR 2026 · Ferramenta educacional independente · Não é da Receita Federal*
