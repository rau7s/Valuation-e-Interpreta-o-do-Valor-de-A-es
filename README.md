# Como interpretar uma ação e valuation

## 1. Conceitos básicos

 Preço da ação: é o valor da última transação no mercado, ou seja, quanto você pagaria hoje para comprar a ação.
 Valor da ação: é o valor intrínseco, calculado com base nos benefícios futuros de caixa que a empresa deve gerar.
 Investimento: é considerado bom quando o valor estimado do ativo > preço atual no mercado.

   Ex.: Se você espera que a ação valha R\$ 50, mas está sendo negociada a R\$ 40, ela pode ser uma oportunidade de compra.
 Pensamento de longo prazo: compra-se pensando nos dividendos e na valorização futura.

---

## 2. Conceitos financeiros importantes

 Goodwill: representa a riqueza gerada pela empresa além do capital investido, ou seja, quanto a empresa vale mais do que o que foi aportado.
 Patrimônio líquido: reflete o passado da empresa; não é o valor de mercado atual ou futuro.
 Ativos: não necessariamente refletem valor; o que importa para valuation é o valor econômico futuro, baseado em premissas.

> Resumo: o valuation é futuro, enquanto patrimônio/ativos refletem o passado.

---

## 3. Fontes de estudo e pesquisa

 Listas de empresas unicórnio: The Complete List of Unicorn Companies
 Plataformas para estudo de ações: Invest.com

---

## **4. CAPM Ajustado**

O CAPM tradicional pode ser **ajustado** para refletir fatores adicionais como risco-país, inflação e tamanho da empresa.

**Fórmula:**

$$
Ke = Rf + \beta \times (Rm - Rf) + RISCO_{br} + (INF_{br} - INF_{usa}) + SP
$$

* **Rm:** taxa de retorno da carteira de mercado (*benchmark*: S\&P, NYSE)
* **Rf:** taxa livre de risco (*benchmark*: T-Bonds)
* **INF:** taxa de inflação (país vs EUA)
* **β:** beta (média ponderada de empresas comparáveis)
* **SP:** Size Premium (prêmio pelo porte da empresa)

---

## **5. Custo de Capital de Terceiros e Estrutura de Capital**

* **Custo de capital de terceiros:** vem da dívida (obrigação contratual).
* **Custo total de capital (WACC):** média ponderada entre capital próprio e de terceiros.

**Estrutura ótima de capital:** é aquela em que o **WACC é o menor possível**, maximizando o valor da empresa.

📌 **Fontes de dados**:

* **ValorData** → SELIC, CDI, etc.
* **“Betas by Sector (US)”** → fornece beta alavancado/não alavancado e prêmio de risco de mercado.
* **Instituto Assaf** → dados de Ibovespa, IPCA, Selic.

---

## **6. Métodos de Valuation**

### **6.1 Método do Fluxo de Caixa Descontado (FCD)**

* O mais aceito e recomendado.
* Considera expectativas futuras de caixa, trazendo a valor presente.
* Inclui valor de continuidade da empresa.
* Abrange todos os aspectos (crescimento, risco, retorno).

---

### **6.2 Método da Stern Stewart & Co (Lucro Econômico / EVA)**

Considerado um dos mais completos. Avalia o **lucro econômico** da empresa.

#### **Principais fórmulas:**

* **WACC:**

$$
WACC = We \times Ke + Wi \times Ki
$$

* **ROE:**

$$
ROE = ROI + (ROI - Ki) \times \frac{P}{PL}
$$

$$
ROE = \frac{LL}{PL}
$$

* **EVA (Economic Value Added):**

$$
EVA = NOPAT - WACC \times Investimento
$$

$$
EVA = (ROI - WACC) \times Investimento
$$

$$
EVA = LL - Ke \times PL
$$

$$
EVA = (ROE - Ke) \times PL
$$

* **Goodwill:**

$$
Goodwill = \frac{EVA}{WACC}
$$

* **Valor da Empresa:**

$$
Valor = Investimento + Goodwill
$$

* **ROI (ou ROIC/ROCE):**

$$
ROI = \frac{NOPAT}{Investimento}
$$

$$
ROI = \text{Margem Operacional} \times \text{Giro do Investimento}
$$

* Margem operacional:

$$
\frac{NOPAT}{Receita}
$$

* Giro do investimento:

$$
\frac{Receita}{Investimento}
$$

---
### **6.3 Estrutura prática (DF e DRE ajustada)**

Aqui estamos vendo **na prática** como aplicar os conceitos de valuation com base em uma **demonstração financeira emitida pelo cliente**.

#### **6.3.1 Construção da DRE Ajustada**

* Receita operacional líquida – Custo das vendas = **Lucro Bruto**
* Lucro Bruto – Despesas operacionais líquidas = **Lucro antes do resultado financeiro**
* **EBITDA = Lucro antes do resultado financeiro + Depreciação**
* **EBT = Lucro antes do resultado financeiro – Depreciação**
* **NOPAT restrito = EBIT – IR e CSLL** (foco na atividade principal)
* **NOPAT amplo = NOPAT restrito + Receita financeira – IR/CSLL**
* **Lucro líquido = NOPAT amplo – Despesas financeiras + Benefício fiscal (IR das despesas financeiras)**

📌 **Dica prática:** criar uma nova coluna na planilha para comparar **valor anterior x valor atual**, e calcular a **média**.

---

#### **6.3.2 Área de Investimento**

O investimento total é formado por:

$$
\text{Investimento Total} = \text{Capital de Terceiros (dívidas)} + \text{Capital Próprio (PL)}
$$

---

#### **6.3.3 Indicadores de Desempenho**

* **ROI (Retorno sobre Investimento):**

$$
ROI = \frac{NOPAT}{Investimento}
$$

* **ROE (Retorno sobre Patrimônio Líquido):**

$$
ROE = \frac{Lucro Líquido}{PL}
$$

---

#### **6.3.4 Custos de Capital**

* **Despesas financeiras líquidas de IR:**

$$
\text{Desp. Financ. Líq. IR} = \text{Desp. Financ.} - \text{Benefício Fiscal}
$$

* **Ki Líq. IR (Custo de Capital de Terceiros):**

$$
Ki = \frac{\text{Desp. Financ. Líq. IR}}{\text{Capital de Terceiros}}
$$

* **Ke (Custo de Capital Próprio):**

$$
Ke = Rf + \beta_{alavancado} \cdot (Rm - Rf) + (INF_{BRA} - INF_{USA})
$$

---

#### **6.3.5 Pesos Contábeis (Estrutura de Capital)**

* **Peso do capital de terceiros:**

$$
Wi = \frac{\text{Capital de Terceiros}}{\text{Total do Investimento}}
$$

* **Peso do capital próprio:**

$$
We = \frac{\text{Capital Próprio}}{\text{Total do Investimento}}
$$

---

#### **6.3.6 Beta Alavancado**

$$
\beta_{alavancado} = \beta_u \times \left[1 + \frac{P}{PL} \times (1 - IR)\right]
$$

* **P:** Passivos onerosos (dívidas)
* **PL:** Patrimônio líquido
* **IR:** Alíquota de imposto de renda

---

#### **6.3.7 WACC (Custo Médio Ponderado de Capital)**

$$
WACC = Wi \cdot Ki + We \cdot Ke
$$

* **Wi:** peso do capital de terceiros
* **Ki:** custo do capital de terceiros líquido de IR
* **We:** peso do capital próprio
* **Ke:** custo do capital próprio

---

📌 **Fontes de dados**:

* **Risk Free:** T-Bond (1928–2024)
* **Rm (Retorno de Mercado):** S\&P (1928–2024)
* **Risco Brasil, Inflação BRA (IPCA), Inflação USA (CPI):** Instituto Assaf

---

continuando vendo o mesmo assunto:

Avaliação pelo Lucro Econômico, temos 4 formas:
LE = MOPAR - WACC x Investimento
LE = (ROI - WACC) x Investimento
LE = LL - Ke x PL
LE = (ROE - Ke) x PL

