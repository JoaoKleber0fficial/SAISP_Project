# README - Análise de Desastres Hídricos no Estado de São Paulo

## 🔹 Sobre o Projeto
Este projeto visa analisar a relação entre **chuvas intensas (PLU)**, **nível dos rios (FLU)** e os desastres registrados no Estado de São Paulo, utilizando dados de **rios estratégicos**, **postos SAISP** e **desastres** do **Atlas Digital de Desastres no Brasil**.  

O foco é entender como eventos de chuva podem levar a **enxurradas, alagamentos e inundações**, avaliando também os impactos sociais e econômicos.

---

## 🔹 Rios Selecionados
- **Tietê**: cobertura macro, atravessa várias cidades do interior e da capital.  
- **Pinheiros**: impacto urbano direto na capital (Zona Oeste/Sul).  
- **Capivari**: região de Campinas e interior, com afluentes importantes.

---

## 🔹 Cidades Foco
**Região do Rio Tietê**: São Paulo, Sorocaba, Rio Claro, Capivari  
**Região do Rio Capivari**: Capivari, Sumaré, Valinhos  
**Região do Rio Pinheiros**: São Paulo (Zona Oeste/Sul)

---

## 🔹 Dados Planejados

### SAISP (pendente de obtenção)
As colunas selecionadas serão:  
- `PLU (mm)` – precipitação acumulada  
- `FLU (m)` – nível do rio  
- `Data/Hora` – alinhamento temporal  
- `Posto` – identificação do rio/bacia

> Observação: A base completa da SAISP ainda não foi obtida. Por enquanto, as cidades, rios e postos de interesse foram mapeados e selecionados utilizando Atlas Digital de Dasastres no Brasil.

### Atlas Digital de Desastres no Brasil
Já disponíveis e serão utilizados para cruzar com os dados da SAISP:  
- `Sigla_UF`  
- `descricao_tipologia` (Enxurradas, Alagamentos, Inundações…)  
- `nome_municipio`  
- `data_evento`  
- `DH_MORTOS`, `DH_FERIDOS`, `DH_ENFERMOS`, `DH_DESABRIGADOS` - impacto social caso as hípoteses, após as hipóteses serem provadas.
- `PEPL` e `PEPR` – impacto econômico público e privado, após as hipóteses serem provadas.

---

## 🔹 Objetivos da Análise
- Avaliar se picos de **PLU** estão relacionados a **aumentos de FLU** nos rios escolhidos.  
- Identificar períodos e regiões com maior probabilidade de **enxurradas, alagamentos e inundações**.  
- Cruzar eventos com impactos **sociais** (desabrigados, feridos, mortos) e **econômicos** (setores público e privado).  

---

## 🔹 Próximos Passos
1. Obter a base completa da **SAISP**.  
2. Consolidar séries temporais de PLU e FLU por **rio, posto e cidade**.  
3. Cruzar dados da SAISP com os eventos do **Atlas Digital**.  
4. Gerar visualizações por rio, cidade, posto e tipo de desastre.  
5. Analisar padrões de risco ao longo do tempo e identificar relações entre chuva e resposta dos rios.  

---

## 🔹 Observações
- O projeto ainda está em **fase de organização de dados e planejamento**.  
- A base SAISP será incorporada assim que estiver disponível, permitindo o teste das hipóteses sobre a relação chuva → nível do rio → desastre.  
