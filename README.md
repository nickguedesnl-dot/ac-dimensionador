# ❄️ ArcThermal — Dimensionador de Ar-Condicionado

Ferramenta web para dimensionamento de sistemas de ar-condicionado, desenvolvida como projeto da UC **Refrigeração e Ar-Condicionado** — Edital A3 2026-1 (Ânima Educação).

🔗 **[Acesse a ferramenta online](https://seu-usuario.github.io/ac-dimensionador)**

---

## 📐 Sobre o projeto

A ferramenta realiza o cálculo de carga térmica e dimensionamento de equipamentos para uma edificação de **814 m²** com **13 cômodos**, conforme os dados do edital:

- Pavimento único com pé-direito de 2,5 m
- Forro em laje de concreto armado
- Divisórias em alvenaria de bloco cerâmico
- Temperatura interna entre 19°C e 26°C (NBR 16401)

---

## ✨ Funcionalidades

| Seção | Descrição |
|---|---|
| **Visão geral** | Dashboard com métricas resumidas e gráfico de carga por cômodo |
| **Cômodos** | Tabela com os 13 ambientes, áreas e ocupações |
| **Carga térmica** | Cálculo pelo método ASHRAE simplificado / NBR 16401 com parâmetros editáveis |
| **Equipamentos** | Seleção automática de splits com margem de segurança de 10% |
| **CAPEX / OPEX** | Estimativa de investimento, custo operacional e curva de payback |
| **Memória de cálculo** | Documento completo para exportação/cópia |

---

## 🧮 Metodologia de cálculo

```
Q_total = Q_env + Q_sol + Q_pessoas + Q_ilum + Q_equip

Q_env   = U_parede × A_envelope × ΔT
Q_sol   = α × I_solar × A_cobertura   (α = 0,80)
Q_pess  = n_pessoas × q_pessoa
Q_ilum  = q_ilum × Área
Q_equip = q_equip × Área
```

**Conversões:** 1 TR = 3.517 W · 1 W = 3,412 BTU/h

---

## 🚀 Como usar localmente

Não requer instalação. Basta clonar e abrir o arquivo:

```bash
git clone https://github.com/seu-usuario/ac-dimensionador.git
cd ac-dimensionador
# Abra o index.html no navegador
open index.html        # macOS
xdg-open index.html    # Linux
start index.html       # Windows
```

---

## 🌐 Deploy no GitHub Pages

1. Faça o fork ou clone deste repositório
2. Vá em **Settings → Pages**
3. Em *Source*, selecione `main` e pasta `/root`
4. Clique em **Save**
5. Acesse `https://seu-usuario.github.io/ac-dimensionador`

---

## 🗂️ Estrutura do projeto

```
ac-dimensionador/
├── index.html      # Aplicação completa (single-file)
├── README.md       # Este arquivo
└── .gitignore
```

> A aplicação é um único arquivo HTML autocontido — sem dependências externas além de fontes Google e Chart.js via CDN.

---

## 📦 Tecnologias

- HTML5 / CSS3 / JavaScript (vanilla)
- [Chart.js 4.4](https://www.chartjs.org/) — gráficos
- [Google Fonts](https://fonts.google.com/) — Syne + DM Mono + DM Sans

---

## 👥 Grupo

> Preencha com os nomes do seu grupo

- Integrante 1
- Integrante 2
- Integrante 3
- Integrante 4
- Integrante 5
- Integrante 6

---

## 📄 Referências

- ASHRAE Handbook — Fundamentals
- NBR 16401 — Instalações de ar-condicionado
- Edital A3 UC Refrigeração e Ar-Condicionado 2026-1
