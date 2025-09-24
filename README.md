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
Show, Raul 👌 Vou dar continuidade na sua estrutura organizada, numerando a partir do item 6, já que você tinha parado no **5. Fluxo de Caixa Descontado (FCD)**. Vou organizar as novas anotações em blocos bem claros, destacando fórmulas e observações.

---

# **Como interpretar uma ação e valuation**

*(continuação das suas anotações)*

---

## **6. CAPM Ajustado**

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

## **7. Custo de Capital de Terceiros e Estrutura de Capital**

* **Custo de capital de terceiros:** vem da dívida (obrigação contratual).
* **Custo total de capital (WACC):** média ponderada entre capital próprio e de terceiros.

**Estrutura ótima de capital:** é aquela em que o **WACC é o menor possível**, maximizando o valor da empresa.

📌 **Fontes de dados**:

* **ValorData** → SELIC, CDI, etc.
* **“Betas by Sector (US)”** → fornece beta alavancado/não alavancado e prêmio de risco de mercado.
* **Instituto Assaf** → dados de Ibovespa, IPCA, Selic.

---

## **8. Métodos de Valuation**

### **8.1 Método Contábil**

* Mostra o valor da empresa **naquele momento**.
* Reflete apenas **descontinuidade**, não considera oportunidades de crescimento.

**Tipos:**

* **Valor Patrimonial:** valor do PL do balanço.
* **Valor de Liquidação:** ativos – passivos (se a empresa encerrasse hoje).

---

### **8.2 Método de Valor de Mercado**

* Valor visto no dia a dia na bolsa.
* Fórmula:

  $$
  Valor = \text{Nº de ações} \times \text{Cotação}
  $$
* Limitação: no Brasil há alta concentração de capital → pode distorcer o valor.

---

### **8.3 Método de Múltiplos**

* Avalia a empresa por múltiplos (ex.: **EV/EBITDA**, P/L etc.).
* Baseia-se em comparação com empresas semelhantes.
* Limitações:

  * Não considera crescimento futuro.
  * Difícil encontrar empresas realmente comparáveis.

---

### **8.4 Método do Fluxo de Caixa Descontado (FCD)**

* O mais aceito e recomendado.
* Considera expectativas futuras de caixa, trazendo a valor presente.
* Inclui valor de continuidade da empresa.
* Abrange todos os aspectos (crescimento, risco, retorno).

---

### **8.5 Método da Stern Stewart & Co (Lucro Econômico / EVA)**

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

### **8.6 Estrutura prática (DF e DRE ajustada)** - aqui estamos vendo na pratica como fazer as contas com uma df emitida pelo cliente

* Receita operacional líquida – Custo das vendas = **Lucro Bruto**
* Lucro Bruto – Despesas operacionais líquidas = **Lucro antes do resultado financeiro**
* **EBITDA:** Lucro antes do resultado financeiro + Depreciação
* **EBT:** Lucro antes do resultado financeiro – Depreciação
* **NOPAT restrito:** EBIT – IR e CSLL (só da atividade principal)
* **NOPAT amplo:** NOPAT restrito + Receita financeira – IR/CSLL
* **Lucro líquido:** NOPAT amplo – Despesas financeiras + Benefício fiscal (IR das despesas financeiras)

Tambem é legar a gente criar uma nova coluna e fazer uma média
comparando o valor anterior e atual

criamos uma area de investimento com
Capital de Terceiros (emprestimos e financiamentos) + capital proprio (PL) = Total do investimento

Calculo dos indicadores de desempenho
ROI = NOPAT/Investimento
ROE = Lucro Liq/PL

Custos de Capital: Despesas Financ - (-) Beneficio fiscal = Desp. Financ. Liq. IR  
KI Líq do IR = Desp. Financ. Liq. IR / Capital de Terceiros

Pesos Contábeis:
Beta Alavancado = BU x [1 + P/PL x (1 - IR)]