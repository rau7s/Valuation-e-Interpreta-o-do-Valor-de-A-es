# **Como interpretar uma ação e valuation**

---

## **1. Conceitos básicos**

* **Preço da ação**: valor da última transação no mercado.
* **Valor da ação**: valor intrínseco, baseado nos fluxos de caixa futuros.
* **Investimento atrativo**: quando **Valor > Preço**.

  * Ex.: Valor esperado = R\$50, Preço atual = R\$40 → oportunidade de compra.
* **Visão de longo prazo**: foco em dividendos + valorização futura.

---

## **2. Conceitos financeiros importantes**

* **Goodwill**: riqueza além do capital investido.
* **Patrimônio líquido (PL)**: reflete o passado da empresa, não o valor de mercado.
* **Ativos**: não são garantia de valor; o que importa é o fluxo futuro.

📌 Resumo:
**Valuation = futuro**
**Patrimônio/Ativos = passado**

---

## **3. Fontes de estudo e pesquisa**

* **The Complete List of Unicorn Companies** → benchmarking.
* **Invest.com** → estudo de ações.

---

## **4. CAPM Ajustado**

O CAPM tradicional pode ser **ajustado** com risco-país, inflação e porte da empresa.

$$
Ke = Rf + \beta \cdot (Rm - Rf) + Risco_{BR} + (INF_{BR} - INF_{USA}) + SP
$$

* **Rf:** taxa livre de risco (T-Bonds).
* **Rm:** retorno de mercado (S\&P, NYSE).
* **β:** beta (comparáveis).
* **SP:** Size Premium (prêmio por porte).
* **Inflação BRA vs USA:** prêmio adicional.

---

## **5. Custo de Capital e Estrutura**

* **Custo de capital de terceiros (Ki):** vem da dívida.
* **Custo médio de capital (WACC):** mistura capital próprio + terceiros.
* **Estrutura ótima:** quando o **WACC é mínimo**.

📌 **Fontes práticas**:

* ValorData (SELIC, CDI).
* Betas por setor (EUA).
* Instituto Assaf (Ibovespa, IPCA, Selic).

---

## **6. Métodos de Valuation**

### **6.1 Fluxo de Caixa Descontado (FCD)**

* O mais usado e aceito.
* Traz expectativas futuras de caixa a valor presente.
* Inclui valor de continuidade.

---

### **6.2 Stern Stewart (Lucro Econômico / EVA)**

Base: medir **lucro econômico**.

**Principais fórmulas**

* **WACC**

$$
WACC = We \cdot Ke + Wi \cdot Ki
$$

* **ROE**

$$
ROE = \frac{LL}{PL} = ROI + (ROI - Ki) \cdot \frac{P}{PL}
$$

* **EVA**

$$
EVA = (ROI - WACC) \cdot Investimento
$$

$$
EVA = (ROE - Ke) \cdot PL
$$

* **Goodwill (MVA)**

$$
Goodwill = \frac{EVA}{WACC}
$$

* **Valor da empresa**

$$
Valor = Investimento + Goodwill
$$

---

### **6.3 Estrutura prática (DF e DRE ajustada)**

#### **6.3.1 DRE Ajustada**

* Receita líquida – Custo vendas = **Lucro Bruto**
* Lucro Bruto – Despesas operacionais = **EBIT**
* **EBITDA = EBIT + Depreciação**
* **EBT = EBIT – Depreciação**
* **NOPAT restrito = EBIT – IR/CSLL**
* **NOPAT amplo = NOPAT restrito + Receita financeira – IR/CSLL**
* **Lucro líquido = NOPAT amplo – Despesas financeiras + Benefício fiscal**

📌 Criar coluna com **comparativo anterior x atual** e calcular **médias**.

---

#### **6.3.2 Área de Investimento**

$$
Investimento = Capital de Terceiros + PL
$$

---

#### **6.3.3 Indicadores**

* **ROI = NOPAT / Investimento**
* **ROE = Lucro Líquido / PL**

---

#### **6.3.4 Custos de Capital**

* Despesa financeira líquida de IR = Despesa bruta – Benefício fiscal.
* **Ki = Desp. Financ. Líq. IR / Capital de Terceiros**
* **Ke = Rf + \beta\_{alav} (Rm - Rf) + (Inf BRA - Inf USA)**

---

#### **6.3.5 Estrutura de Capital**

* **Wi = Capital de Terceiros / Investimento Total**
* **We = PL / Investimento Total**

---

#### **6.3.6 Beta Alavancado**

$$
\beta_{alav} = \beta_u \times \Big[1 + \frac{P}{PL} \cdot (1 - IR)\Big]
$$

---

#### **6.3.7 WACC**

$$
WACC = Wi \cdot Ki + We \cdot Ke
$$

---

📌 **Fontes**: T-Bond, S\&P, Instituto Assaf (Risco BR, IPCA, CPI).

---

### **6.4 Avaliação pelo Lucro Econômico**

Quatro formas equivalentes:

* $LE = MOPAR - WACC \cdot Investimento$
* $LE = (ROI - WACC) \cdot Investimento$
* $LE = LL - Ke \cdot PL$
* $LE = (ROE - Ke) \cdot PL$

Depois:

* **Goodwill (MVA):** $Goodwill = \frac{LE}{WACC}$
* **Valor da Empresa = Goodwill + Investimento**
* **Valor do PL = Valor da Empresa – Dívida**
* **Valor por ação = Valor do PL / nº ações**

---

### **6.5 Análise de Sensibilidade**

* Beta não alavancado como base.
* Cenários:

  * **Otimista:** 0,8
  * **Mais provável:** 1,0
  * **Pessimista:** 1,1

---
