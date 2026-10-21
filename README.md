# Calculadora-de-Investimentos-em-FIIs
Planilha Excel para simular aportes, patrimônio e dividendos em FIIs, com projeções de 2 a 30 anos e divisão de aportes por perfil de investidor.

# Simulador de Investimentos em FIIs

Planilha em Excel para simular a evolução de investimentos em fundos imobiliários (FIIs), à partir dos aportes mensais calculados sobre um % do seu salário, o tempo de investimento e o somatório do dividend yield reinvestido com o rendimento mensal da carteira, mostrando o patrimônio acumulado, o total aportado, o ganho acumulado ao longo do tempo e a renda mensal projetada após o período de aportes.

## Funcionalidades

- Projeção de cenários de 2 a 30 anos.
- Cálculo do patrimônio futuro com a função `VF`.
- Distribuição do aporte entre FIIs conforme o perfil do investidor.
- Uso de `PROCV` e de uma tabela de apoio para relacionar perfis e alocações.
- Intervalos nomeados para facilitar a leitura e a manutenção das fórmulas(aporte_mensal, dy_mensal, ganho_acumulado, patrimonio_acumulado, renda_mensal, rendimento_carteira, salario, tempo_de_aportes e total_aporte).

## Como usar

1. Baixe o arquivo da planilha na seção **Releases** ou diretamente neste repositório.
2. Abra-o no Microsoft Excel.
3. Preencha os campos de entrada Salário, % de aporte, tempo total de aportes, dividend yield mensal e rendimento mensal da carteira.
4. Consulte os resultados projetados de total aportado, ganho acumulado e patrimônio acumulado.
5. Altere as premissas para comparar diferentes cenários.


## Premissas e limitações

Os resultados são projeções baseadas nas premissas informadas na planilha. Rentabilidade, preços dos ativos e dividendos futuros podem diferir dos valores projetados. A ferramenta não prevê o desempenho futuro dos investimentos nem substitui uma análise financeira individual.
O patrimônio acumulado não considera impostos, taxas nem variações nas taxas, também não considera corretagens e pressupõe que os retornos sejam constantes e reinvestidos mensalmente.
O cálculo pressupõe que o primeiro aporte foi feito no início do primeiro mês para que já tenha rendimento e dividendos pagos.
A renda calculada é uma estimativa bruta inicial, não uma garantia de rendimento. A sustentabilidade depende de o investimento realmente entregar essa taxa líquida de custos e tributos.


## Tecnologias

- Microsoft Excel
- Funções `VF` e `PROCV`
- Intervalos nomeados

## Contribuições

Sugestões e melhorias são bem-vindas. Abra uma *issue* para relatar um problema ou propor uma mudança.

## O que mudou em relação a ferramenta do Expert

Substitui a sugestão de aporte de 20 e 30% por uma célula que o usuário escolhe o seu % de aporte à partir do seu salário.
Adicionei o total de aportes ao longo tempo e o ganho acumulado (calculado pelo somatório do dividend yield e rendimento mensal da carteira).
Adicionei uma sheet contendo um resumo sobre investimentos em FIIs e outra sobre um resumo de usabilidade da calculadora.
Adicionei um gráfico de colunas mostrando a evolução do patrimônio acumulado e da renda mensal ao longo do tempo.


