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

## 4. Custos de capital e CAPM

### 4.1 CAPM (Capital Asset Pricing Model)

O CAPM é usado para calcular a taxa de retorno exigida de uma ação, considerando risco de mercado:

$$
Ke = Rf + \beta_j \times (Rm - Rf)
$$

 Ke = retorno exigido da ação (Custo de Capital Próprio)
 Rf = taxa livre de risco (ex.: rendimento de renda fixa segura)
 Rm = retorno esperado da carteira de mercado
 βj = Beta da ação, mede a volatilidade da ação em relação ao mercado

---

### 4.2 Beta

 Beta por benchmark: padrão do mercado.
 Beta alavancado (Bl): considera a empresa com dívidas (risco econômico + financeiro):

$$
Bl = Bu \times [1 + (P/PL) \times (1-IR)]
$$

 Bl: Beta alavancado (empresa com dívida)
 Bu: Beta não alavancado (empresa sem dívida)
 P: Passivos onerosos (dívida)
 PL: Patrimônio líquido
 IR: Alíquota de Imposto de Renda

> Ex.: ajusta o risco da empresa conforme sua alavancagem financeira.

---

### 4.3 Exemplos de cálculo do custo de capital

Premissas do exemplo:

 Taxa livre de risco: 7%

 Prêmio de risco de mercado: 9,5% a.a.

 Custo de capital próprio alavancado:

$$
Ke = 7\% + 0,95 \times 9,5\% = 16\%
$$

 Custo de capital próprio sem dívida:

$$
Ke = 7\% + 0,65 \times 9,5\% = 13,2\%
$$

 Prêmio pelo risco financeiro (dívida):

$$
16\% - 13,2\% = 2,8\%
$$

> Ou seja, o risco financeiro (dívida) adiciona 2,8% ao custo do capital próprio.

---

## 5. Fluxo de Caixa Descontado (FCD)

 FCD: método para calcular o valor da empresa com base no fluxo de caixa futuro, descontando pelo custo de capital.
 É a principal técnica de valuation de ações e empresas.

> A lógica: dinheiro no futuro vale menos hoje, por isso se desconta pelo custo de capital (Ke).

---

MODELO CAPM AJUSTADO:
Ke = 𝑹𝑭 + b x (𝑹𝒎 - 𝑹f) + 𝑹𝑰𝑺𝑪𝑶br + (𝑰𝑵𝑭br - 𝑰𝑵𝑭usa) + SP 

𝑹𝑴 = Taxa de Retorno da Carteira de Mercado (benchmarking) S&P, NYSE
𝑹𝑭 = Taxa Livre de Risco (benchmarking) - T-Bonds
INF = Taxa de Inflação
β = Benchmarking (empresas comparáveis) – Média Ponderada dos Betas
SP = Size Premium

---

Custo de Capital de Terceiros:
Vem da divida - é uma obrigação contratual 

O custo total de capital é a media ponderada de capital proprio e capital de terceiros

Estrutura de Capital
Sempre vamos adotar como estrurua ótima de capital, quando o WACC é o menor possível - é onde tenho chances de ter o maior valor

Conseguimos pegar alguns dados do VALORDATA - q pega a SELIC, CDI, enfim - usamos p estudar
Para pegar o beta, vamos usar o "Betas by Sector (US)" - tmb conseguimos pegar beta alavancado, beta nao alavancado, premio como risco de mercado

No Institutoassaf conseguimos pegar o ibovespa, IPCA, selic, enfim

---

Métodos de Valuation - como avaliar uma empresa e chegar no valor da ação
- Método Contábil: Mostra o valor da empresa naquele momento - reflete apenas a descontinudade da empresa, não considera oportunidade de crescimento
tem uma dificuldade de considerar outros oportunidades/produtos
-- esse valor é uma das formas p avaliar empresa p descontinuidade

Valor patrimonial - Calculado c Valor do PL do Balanço da Empresa
Valor de Liquidação/Descontinuidade - Valor de todos os bens do Balanço (-) Dívidas (Passivos)

- Método Valor de Mercado - Valor de Bolsa
É o valor que vemos no dia a dia - 
PL = qtd ação x cotação das ações
limitação: Alto grau de concentração de capital do brasil

- Método Multiplos 
Avalia a empresa por um multiplo - esses variam muito -- ex. ebitda
essencia é atribuir multiplos de empresas semelhantes
Não considera Crescimento Futuro
dificil encontrar emprersas comparaveis

- Método FCD - fluxo de caixa descontado
Mais aceito e recomendado
Considera expectativas futuras de retornos e valor presente
valor de continuidade da empresa
Considera tudo

- Método da Stern Stewart & CO -- esse é o mais pika:
avaliamos pela metodologia do lucro economico

WACC = We x Ke + Wi x Ki
ROE = ROI + (ROI - Ki) x P/PL
ROE = LL/PL
EVA = NOPAT - WACC x Investimento
EVA = (ROI - WACC) x Investimento
EVA = LL - Ke x PL
EVA - (ROE - Ke) x PL
Goodwill = EVA/WACC
Valor da empresa = Investimento + Goodwill
ROI = NOPAT/Investimento
ROI = ROIC = ROCE
ROI = Margem op. x Giro do Invest
Margem op = NOPAT/Receita
GIro do Invest = Receita/Invest

aí o prof abriu uma DF p mostrar a stern stewart na pratica
falou p montar uma DRE ajustada, pode ser do lado da DRE publicada mesmo

