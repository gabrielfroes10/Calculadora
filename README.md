# 📊 Calculadoras Financeiras Corporativas

![Status do Projeto](https://img.shields.io/badge/Status-Concluído-success)
![Licença](https://img.shields.io/badge/License-MIT-blue)
![Versão](https://img.shields.io/badge/Version-2.0-blueviolet)

> Uma suíte de ferramentas web para auxiliar empreendedores, gestores e estudantes na precificação e análise de viabilidade financeira.

---

## 🖼️ Preview

![Screenshot do Projeto](<img width="1348" height="640" alt="image" src="https://github.com/user-attachments/assets/9b4ef9a3-8088-4440-95a0-422ccef09ae2" />

![Uploading image.png…]()


---

## 🚀 Funcionalidades

O projeto consiste em uma SPA (Single Page Application) leve, contendo quatro módulos de cálculo essenciais para a gestão empresarial:

### 1. ⚖️ Ponto de Equilíbrio (Break-even Point)
Calcula a quantidade exata de vendas necessárias para cobrir todos os custos (fixos e variáveis), resultando em lucro zero.
- **Entradas:** Custos Fixos, Preço de Venda, Custo Variável.
- **Saída:** Unidades a vender, Receita mínima e Margem de contribuição.

### 2. 💰 Lucratividade
Mede a eficiência operacional do negócio, revelando o percentual de ganho sobre a receita total.
- **Fórmula:** `(Lucro Líquido / Receita Total) * 100`

### 3. 📈 Rentabilidade (ROI)
Calcula o Retorno Sobre o Investimento, indicando o quanto o negócio rendeu em relação ao capital investido.
- **Fórmula:** `(Lucro Líquido / Investimento Inicial) * 100`

### 4. 🏷️ Markup Divisor (Precificação)
Ferramenta avançada para formação de preço de venda baseada na estrutura de custos "por dentro". Considera que o preço final deve cobrir o custo de produção + todas as taxas percentuais + margem de lucro.

---

## 🧠 Lógica do Markup Divisor

A calculadora de precificação utiliza o método **Markup Divisor**, amplamente aceito na contabilidade de custos para garantir que a margem de lucro seja real sobre o preço de venda, e não apenas sobre o custo.

**A Fórmula aplicada:**

$$
Preço = \frac{Custo\ Unitário}{1 - (\sum Taxas\%)}
$$

**Onde as Taxas incluem:**
* Comissões de Vendedores
* Tributos (Vendas + Lucro)
* Custos Fixos (Rateio)
* Despesas Fixas (Rateio)
* Margem de Lucro Desejada

---

## 🛠️ Tecnologias Utilizadas

O projeto foi construído utilizando tecnologias web padrão, sem dependência de frameworks pesados, garantindo máxima performance e compatibilidade.

* ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) **Estrutura Semântica:** Telas modulares e navegação fluida.
* ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white) **Estilo Clean Blue:** Design minimalista, corporativo, responsivo e focado em UX (User Experience).
* ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) **Lógica Pura:** Cálculos em tempo real, formatação de moeda BRL (`Intl.NumberFormat`) e manipulação de DOM.

---

## 📂 Estrutura do Projeto

```bash
calculadora-financeira/
│
├── index.html        # Estrutura das telas e inputs
├── calculadora.css   # Estilização visual (Clean Blue Theme)
├── calculadora.js    # Lógica matemática e interatividade
└── README.md         # Documentação
