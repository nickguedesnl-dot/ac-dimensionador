# ❄️ ArcThermal — Dimensionador de Ar-Condicionado v3

Ferramenta web para dimensionamento de sistemas de A/C — UC Refrigeração e Ar-Condicionado · Edital A3 2026-1 · Ânima Educação.

## ✨ Funcionalidades

| Aba | Descrição |
|---|---|
| **Visão geral** | Dashboard com métricas e gráfico de carga |
| **✏️ Editor** | Edite cômodos, áreas, ocupação e parâmetros globais em tempo real |
| **Carga térmica** | Tabela completa com decomposição por componente |
| **🧮 Calculadora** | Cálculo manual passo a passo com fórmulas explicitadas |
| **Equipamentos** | Seleção de splits por cômodo |
| **CAPEX/OPEX** | Análise econômica com curva de custo acumulado |
| **Memória** | Documento completo para copiar/imprimir |

## 🧮 Metodologia

```
Q_total = (Q_env + Q_pess + Q_ilum + Q_eq) × 1,10
Q_env   = U_cob × A × ΔT × FS_sol   (3,5 × A × 10 × 1,3)
Q_pess  = N × 125 W/pessoa
Q_ilum  = 15 W/m² × A
Q_eq    = (20/8/5) W/m² × A
```

## 🚀 Uso

Abra `index.html` no navegador — sem instalação, funciona offline.

## 🌐 GitHub Pages

Settings → Pages → Source: main → / (root) → Save

