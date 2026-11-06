<div style="display: flex; justify-content: flex-end; align-items: center; gap: 8px; margin: 10px 0;">
 <span style="font-size: 14px; color: #555; font-weight: bold;">Tamanho do texto:</span>
 <button onclick="diminuirFonte()" title="Diminuir texto" style="padding: 6px 12px; font-weight: bold; cursor: pointer; border: 1px solid #ccc; border-radius: 4px; background: #f8f9fa;">A-</button>
 <button onclick="resetarFonte()" title="Tamanho normal" style="padding: 6px 12px; font-weight: bold; cursor: pointer; border: 1px solid #ccc; border-radius: 4px; background: #f8f9fa;">A</button>
 <button onclick="aumentarFonte()" title="Aumentar texto" style="padding: 6px 12px; font-weight: bold; cursor: pointer; border: 1px solid #ccc; border-radius: 4px; background: #f8f9fa;">A+</button>
 
 <button onclick="window.print()" style="background-color: #0056b3; color: white; padding: 6px 16px; border: none; border-radius: 5px; font-size: 14px; cursor: pointer; box-shadow: 0 2px 4px rgba(0,0,0,0.2); margin-left: 10px;">
 🖨️ Imprimir ou baixar esta página
 </button>
</div>

# ANEXO I - MEMÓRIA DE CÁLCULO E FÓRMULAS PARA ANÁLISE COMPARATIVA

Este anexo apresenta fórmulas e exemplos destinados a apoiar a reconstrução dos cenários tributários apresentados no corpo do material. A lógica utilizada é: decomposição do preço de origem, identificação da base econômica comparável e recomposição do cenário posterior.

Os valores e as alíquotas dos exemplos devem ser substituídos pelos dados da PCFP, pelas condições da contratação e da pesquisa de preço ou pelos parâmetros efetivamente aplicáveis ao caso concreto.

<br>

## 1. Como comparar os cenários tributários

A comparação entre os preços segue três etapas:

| Etapa | O que fazer |
| :--- | :--- |
| **1. Decomposição** | Identificar e retirar do preço original os tributos considerados na comparação. |
| **2. Base econômica comparável** | Manter a mesma base econômica para comparar os dois cenários. |
| **3. Recomposição** | Aplicar à base econômica os tributos e as regras do cenário posterior. |

Na sistemática do IBS e da CBS, a base de cálculo corresponde, em regra, ao valor da operação, observadas as exclusões previstas na legislação, inclusive as regras de transição do art. 12, § 2º, da Lei Complementar nº 214, de 2025.

#### 1.1. Como considerar o lucro

Para comparar especificamente os efeitos da Reforma Tributária, recomenda-se manter o valor monetário do lucro registrado no Módulo 6 da PCFP do modelo da Seges.

$$\text{Lucro da comparação} = \text{valor monetário do lucro constante no Módulo 6 da PCFP}$$

<br>

## 2. Como calcular o preço de serviços

#### 2.1 Decomposição do preço com PIS, Cofins e ISS

Primeiro, é necessário identificar os valores de PIS, Cofins e ISS incluídos no preço original do serviço.

Esses valores são retirados do preço de referência para calcular a base econômica comparável (BEC).

**Fórmulas:**
$$\text{BEC} = \text{PC}_a - \text{PIS} - \text{Cofins} - \text{ISS}$$  
$$\text{PIS} = \text{PC}_a \times \text{alíquota do PIS}$$  
$$\text{Cofins} = \text{PC}_a \times \text{alíquota da Cofins}$$  
$$\text{ISS} = \text{PC}_a \times \text{alíquota do ISS}$$

| Componente | Descrição |
| :--- | :--- |
| **$\text{PC}_a$** | Preço contratado atual. |
| **BEC** | Base econômica comparável do serviço. |
| **PIS** | Valor de PIS incorporado ao preço do serviço ($\text{PC}_a$). |
| **Cofins** | Valor de Cofins incorporado ao preço do serviço ($\text{PC}_a$). |
| **ISS** | Valor de ISS incorporado ao preço do serviço ($\text{PC}_a$). |

#### 2.2. Recomposição considerando a CBS e o IBS

Depois de identificar a BEC, calcula-se o preço conforme as regras de CBS e IBS utilizadas na comparação.

Nessa etapa, os tributos são calculados conforme suas respectivas metodologias, considerando as regras aplicáveis ao período analisado.

**Fórmulas:**
$$\text{Preço contratado } (\text{PC}_r) = \text{BEC} + \text{CBS} + \text{IBS} + \text{ISS}$$  
$$\text{CBS} = \text{BEC} \times \text{alíquota da CBS}$$  
$$\text{IBS} = \text{BEC} \times \text{alíquota do IBS}$$  
$$\text{ISS} = \left[ \frac{\text{BEC}}{1 - \text{ISS}} \right - \text{BEC}$$

| Componente | Descrição |
| :--- | :--- |
| **$\text{PC}_r$** | Preço contratado considerando a reforma tributária. |
| **BEC** | Base econômica comparável. |
| **CBS** | Valor da CBS aplicada sobre a BEC. |
| **IBS** | Valor do IBS aplicado sobre a BEC. |
| **ISS** | Valor de ISS incorporado ao BEC (utiliza a metodologia atual de cálculo, sem considerar a CBS e o IBS na base de cálculo). |

<br>

## 3. Como calcular o preço de materiais e insumos

#### 3.1 Identificação dos tributos no preço original

Para analisar os pedidos de reequilíbrio econômico-financeiro relacionados aos materiais e insumos do Módulo 5 da PCFP, deve ser utilizada uma metodologia de comparação equivalente à aplicada aos serviços.

Isso significa que não basta identificar o ICMS incluído no preço original dos materiais.

Também devem ser considerados o PIS e a Cofins, quando esses tributos estiverem incluídos no preço do material e forem relevantes para a comparação.

#### 3.2 Decomposição do preço com PIS, Cofins e ICMS

Assim como no cálculo dos serviços, a análise começa pelo preço de referência do material.

Em seguida, são identificados e retirados os valores de PIS, Cofins e ICMS considerados no cenário original, para calcular a base econômica comparável.

**Fórmulas:**
$$\text{BEC} = \text{PC}_a - \text{PIS} - \text{Cofins} - \text{ICMS}$$  
$$\text{PIS} = \text{PC}_a \times \text{alíquota de PIS}$$  
$$\text{Cofins} = \text{PC}_a \times \text{alíquota de Cofins}$$  
$$\text{ICMS} = \text{PC}_a \times \text{alíquota de ICMS}$$

| Componente | Descrição |
| :--- | :--- |
| **BEC** | Base econômica comparável do material. |
| **$\text{PC}_a$** | Preço contratado do material atual. |
| **PIS** | Valor de PIS identificado no preço contratado do material ($\text{PC}_a$). |
| **Cofins** | Valor de Cofins identificado no preço contratado do material ($\text{PC}_a$). |
| **ICMS** | Valor de ICMS identificado no preço contratado do material ($\text{PC}_a$). |

#### 3.3 Recomposição com CBS e IBS

Depois de retirar os valores de PIS, Cofins e ICMS do preço original, utiliza-se a BEC para calcular o preço conforme as regras do cenário posterior.

Essa etapa segue a mesma lógica utilizada para os serviços, mas considera os tributos aplicáveis aos materiais.

**Fórmulas:**
$$\text{Preço contratado } (\text{PC}_r) = \text{BEC} + \text{CBS} + \text{IBS} + \text{ICMS}$$  
$$\text{CBS} = \text{BEC} \times \text{alíquota da CBS}$$  
$$\text{IBS} = \text{BEC} \times \text{alíquota efetiva do IBS}$$  
$$\text{ICMS} = \left[ \frac{\text{BEC}}{1 - \text{alíquota do ICMS}} \right - \text{BEC}$$

| Componente | Descrição |
| :--- | :--- |
| **$\text{PC}_r$** | Preço contratado do material considerando a reforma tributária. |
| **BEC** | Base econômica comparável do material. |
| **CBS** | Valor da CBS aplicada sobre a BEC. |
| **IBS** | Valor do IBS aplicado sobre a BEC. |
| **ICMS** | Valor de ICMS incorporado ao BEC (utiliza a metodologia atual de cálculo, sem considerar a CBS e o IBS na base de cálculo). |

#### 3.4 Planilha exemplificativa

O exemplo a seguir demonstra como decompor o preço original de um material e reconstruí-lo conforme as regras tributárias utilizadas na simulação.

**Parâmetros utilizados:**

| Tributo ou parâmetro | Percentual |
| :--- | :--- |
| **ICMS** | 18% |
| **PIS** | 0,65% |
| **Cofins** | 3% |
| **CBS** | 11,3% (TCU) |
| **IBS** | 0,1% |

**Exemplo 1. Cálculo sem apropriação de créditos: CBS e IBS não integram a base de cálculo do ICMS.**

| Elemento | Exemplo | Fórmulas |
| :--- | :--- | :--- |
| **Valor do material na planilha** | R$ 10.000,00 | — |
| **DECOMPOSIÇÃO** | | |
| **PIS** | -R$ 65,00 | $\text{PC}_a \times \text{alíquota PIS}$ |
| **Cofins** | -R$ 300,00 | $\text{PC}_a \times \text{alíquota Cofins}$ |
| **ICMS** | -R$ 1.800,00 | $\text{PC}_a \times \text{alíquota ICMS}$ |
| **Base econ. comparável do material (BEC)** | R$ 7.835,00 | $\text{BEC} = \text{PC}_a - \text{PIS} - \text{Cofins} - \text{ICMS}$ |
| **RECOMPOSIÇÃO** | | |
| **CBS** | R$ 885,35 | $\text{BEC} \times \text{alíquota CBS}$ |
| **IBS** | R$ 7,83 | $\text{BEC} \times \text{alíquota IBS}$ |
| **ICMS** | R$ 1.719,88 | $[\text{BEC} \div (1 - \text{alíquota ICMS}) - \text{BEC}$ |
| **Preço contratado após a Reforma Tributária ($\text{PC}_r$)** | R$ 10.448,06 | $\text{PC}_r = \text{BEC} + \text{CBS} + \text{IBS} + \text{ICMS}$ |

<br>
<div style="text-align: right; margin: 10px 0;">
 <button onclick="window.print()" style="background-color: #0056b3; color: white; padding: 10px 20px; border: none; border-radius: 5px; font-size: 16px; cursor: pointer; box-shadow: 0 2px 4px rgba(0,0,0,0.2);">
 🖨️ Imprimir ou baixar esta página
 </button>
</div>
