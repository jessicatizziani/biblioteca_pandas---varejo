# Análise de Vendas no Varejo com Pandas

Este dataset contém informações de vendas de uma loja virtual que atua em todo o território nacional, vendendo produtos de diferentes departamentos. A loja utiliza diversos canais de venda, como marketplace, loja própria, entre outros.

## 📌 Premissas de Negócio

Durante a análise dos dados, algumas premissas precisam ser consideradas:

1. **Correção de UF**: Devido a um erro no sistema, algumas compras não possuem informação de UF. A empresa solicitou que, nesses casos, o valor da UF seja substituído por "MS".
2. **Preço com Frete**: O preço final de um produto **não pode ser maior** do que o valor de "preço com frete".

## 📊 Métricas Avaliadas

Com base no contexto e nas premissas de negócio, as seguintes métricas foram avaliadas:

- **Departamentos Mais Vendidos**  
  Identifica os departamentos mais populares entre os clientes, auxiliando no planejamento de estoque e estratégia de vendas.

- **Média de Preço com Frete por Departamento**  
  Avalia o comportamento de preço médio por departamento, o que ajuda a definir estratégias de precificação com base na rentabilidade.

- **Quantidade de Vendas por Mês**  
  Permite observar sazonalidades no comportamento de compra dos clientes, contribuindo para o planejamento de campanhas promocionais.

- **Média de Renda por Canal de Venda**  
  Analisa o perfil socioeconômico dos clientes por canal, permitindo adaptar ações de marketing para públicos específicos.

- **Média de Idade dos Clientes por Bandeira**  
  Ajuda a traçar perfis etários por bandeira de venda, o que colabora para uma estratégia de comunicação mais personalizada.

---

## 🛠 Como editar e salvar usando Git Bash

1. **Abra o Git Bash** e vá até a pasta do seu projeto:
   ```bash
   cd caminho/para/seu/projeto
