# Sales-Manager
Aplicação gerenciadora de vendas 
## Sobre o projeto ℹ️
O sistema que será desenvolvido tem como objetivo controlar e gerenciar as vendas realizadas por representantes comerciais. A plataforma permitirá que diferentes representantes registrem suas vendas, consultem informações e acompanhem seu desempenho.
O sistema também contará com integração com banco de dados centralizado, permitindo armazenar todas as informações de vendas, clientes e representantes. Além disso, serão gerados relatórios gerenciais, que poderão ser analisados através de ferramentas como Power BI, facilitando a visualização de métricas e resultados.

## Arquitetura Pretendida 🖊️
A arquitetura lógica utilizada será `Cliente-Servidor`, onde múltiplos usuários poderão acessar o sistema simultaneamente.

✅ O cliente será a interface utilizada pelos representantes e gestores.

✅ O servidor será responsável por processar as requisições e aplicar as regras de negócio.

✅ O banco de dados armazenará todas as informações relacionadas às vendas e relatórios.

Esse modelo permite que diversos usuários utilizem o sistema ao mesmo tempo, mantendo os dados centralizados e organizados.

## Recurso Crítico do Sistema ‼️
O recurso crítico identificado no sistema é o registro e atualização das vendas no banco de dados.

Embora vários usuários possam acessar o sistema simultaneamente, é necessário garantir que uma mesma venda ou registro não seja alterado ao mesmo tempo por usuários diferentes, pois isso poderia gerar inconsistência nos dados, como valores incorretos ou duplicação de informações.
Para evitar esse tipo de problema, o sistema deverá utilizar mecanismos de controle de concorrência no banco de dados, garantindo que cada operação seja processada corretamente e mantendo a integridade das informações.
