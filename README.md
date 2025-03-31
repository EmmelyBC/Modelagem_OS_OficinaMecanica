# Modelagem Conceitual de uma Oficina Mecânica
Modelagem de um sistema de controle de ordens de serviço em uma oficina mecânica no MySQL Workbench.

## 📝Narrativa
- Sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica
- Os clientes levam veículos à oficina mecânica para serem consertados ou para passarem por revisões periódicas
- Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenchem uma OS com data de entrega
- A partir da OS calcula-se o valor de cada serviço consultando-se uma tabela de referência de mão de obra
- O valor de cada peça também irá compor a OS
- O cliente autoriza a execução dos serviços
- A mesma equipe avalia e executa os serviços

## 🧍🏽‍♀️Entidades Principais
- Mecânico
- Cliente 
- Carro
- Ordem de Serviço
- Serviço
- Estoque de Peças

## ♾️ Entidades de Relacionamento
- Equipe/OS: Relação de um conjunto de mecânicos responsáveis por uma ou mais Ordens de Serviço
- Serviço/OS: Relação de um ou vários serviços para uma ou mais OS
- Peça/OS: Relação de uma ou mais peças para uma ou mais OS



