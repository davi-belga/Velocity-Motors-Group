# Problema de negócio
    
O Velocity Motors Group é uma rede de concessionárias multimarca estabelecida em estados-chave do Sudoeste e da Costa Oeste dos Estados Unidos (focando em alto volume e diversidade de portfólio, especialmente importados). A empresa compete em um mercado altamente volátil, pressionado pela transição para veículos elétricos e por constantes desafios na cadeia de suprimentos.
    
  ## O Problema de Negócio (O Desafio de Gestão)
    
  Como a Diretoria de Vendas e o Head de Operações podem otimizar o mix de fabricantes e modelos (Toyota, Ford, VW, BMW e Porsche) para garantir que as ações de estoque e marketing estejam alinhadas à **máxima rentabilidade.**
    
    
  # Dado da empresa
    

Análise Descritiva

Passo 1 Coluna:

- Fabricante
- Modelo
- Tipo de combustível
- Ano fabricação
- Quilometragem
- Preço
- Tamanho do motor

Passo 3: Combinação das Dimensões

- Quantidade de Vendas por fabricante
- Quantidade de Vendas por modelo
- Quantidade de Vendas por tipo de combustível
- Quantidade de Vendas por tamanho do motor
- Quantidade de Vendas por ano de fabricação
- Preço médio por fabricante
- Preço médio por modelo
- Média de quilometro por modelo
- Premissas do negócio
    - **Varejo de Bens Duráveis:** O modelo principal é o **Varejo de Alto Valor/Baixa Frequência de Compra** (Venda de Carros)
    
    Visão do negócio: visão vendas, visão faturamento, detalhamento
    
## Estratégia da solução
    
  O painel estratégico foi desenvolvido utilizando as métricas que refletem as 3 principais visões do modelo de negócio da empresa:
    
  - Visão Vendas
  - Visão Faturamento
  - Detalhamento
    
   # Cada visão é representada pelo seguinte conjunto de métricas.
    
  1. Visão vendas
      1. Quantidade de Vendas
      2. Quantidade de Vendas por fabricante
      3. Quantidade de Vendas por tipo de combustível
      4. Quantidade de Vendas por tamanho do motor
      5.  Quantidade de Vendas por ano de fabricação
        
  2. Visão faturamento
      1. Faturamento por fabricante
      2.  Percentual acumulado por modelo 
      3. faturamento total
        
  3.  Detalhamento faturamento
      1. Rank por fabricante e por modelo em faturamento
      2. Acumulado
      3. Faturamento
      4. Média de preço
      5. Quantidade venda
# Top 4 insights de dados
  1. Auto vendido por fabricante
        
     Toyota Lidera em Faturamento, mas Ford e VW Lideram em Volume de Vendas
        
      - **Faturamento Bruto:** A **Toyota** tem o maior faturamento total por fabricante, com **$180.028.908**, seguida pela Ford ($159.646.767) e VW ($154.545.496).
     - **Volume de Vendas:** A **Ford** e a **VW** lideram em volume de unidades vendidas, com 14.959 e 14.913 carros, respectivamente, superando a Toyota (12.554).
      - **Conclusão:** A estratégia da **Toyota** parece focar em **maior margem/valor** por veículo (ticket médio de $14.340,36), enquanto **Ford** e **VW** focam em **maior volume** de mercado (tickets médios de $10.672,29 e $10.363,14, respectivamente).
  2. Venda por tipo de combustível   
      Dependência de Combustíveis Fósseis 
        
      - O gráfico  mostra uma **grande dependência de combustíveis fósseis**:
        - **Diesel:** 51% (25.488 veículos)
        - **Petrol:** 27% (13.268 veículos)
        - **Hybrid (Híbrido)** representa uma fatia menor, mas significativa, de **22% (11.244 veículos)**
  3. **Detalhamento**
        
     Modelos de Baixo Volume e Alto Valor (Porsche e BMW)
        
     A **Porsche** e a **BMW** têm o **maior ticket médio** de vendas:
        
      - **Porsche:** $29.103,76 (Venda: 2.609)
     - **BMW:** $24.429,46 (Venda: 4.965)
        
       Apesar de terem o **menor volume de vendas** entre os 5 principais fabricantes (2.609 e 4.965 unidades, respectivamente), elas garantem um faturamento robusto ($75 milhões e $121 milhões) devido aos seus preços elevados.
        
## O produto final
    
  Dashboard Online, na ferramenta power Bi online e disponível para acesso em qualquer dispositivo conectado à internet.
    
  O painel pode ser acessado através desse link:https://app.powerbi.com/view?r=eyJrIjoiZmZlNTcxYmEtOWMzMS00YTUwLWEyYTYtYmNlZDI1ZGVmYWNiIiwidCI6ImZiY2ExYWE5LTAxMDEtNDRlNC1iZmU1LWEyODRjNzA0YjIyMCJ9&pageName=d9d429c736f89c578732
    
# Conclusão
    
  O objetive desse projeto é cria um conjunto de gráficos ou tabela que exibam essas métricas da melhor forma possível para o CEO.
    
  A principal conclusão é que, para responder ao desafio de gestão, a empresa deve adotar uma **Estratégia de Portfólio Dupla (Volume Rentável e Valor Premium)** e iniciar imediatamente a **Reorientação do Foco de Combustível**.
    
  1. **Otimização Financeira:** Direcionar os maiores investimentos de marketing e estoque para os fabricantes de **Alto Valor/Faturamento** (Toyota, BMW, Porsche), enquanto a Ford e VW devem ser geridas primariamente para **ganho de *share* e eficiência operacional**, e não como fontes primárias de lucro líquido
    
  2. **Preparação para o Futuro:** O risco do negócio está na matriz energética. É crucial investir na expansão da linha **Híbrida** para capitalizar o seu crescimento de 22%# Velocity-Motors-Group
