# Calculadora-de-Investimentos-em-FIIs
Planilha Excel para simular aportes, patrimônio e dividendos em FIIs, com projeções de 2 a 30 anos e divisão de aportes por perfil de investidor.

# Simulador de Investimentos em FIIs

Planilha em Excel para simular a evolução de investimentos em fundos imobiliários (FIIs), desde os aportes mensais até o patrimônio acumulado e os dividendos projetados.

## Funcionalidades

- Projeção de cenários de 2 a 30 anos.
- Cálculo do patrimônio futuro com a função `VF`.
- Distribuição do aporte entre FIIs conforme o perfil do investidor.
- Uso de `PROCV` e de uma tabela de apoio para relacionar perfis e alocações.
- Intervalos nomeados para facilitar a leitura e a manutenção das fórmulas.

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


