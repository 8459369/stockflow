## PROJETO
- Stockflow

## Funcionalidade

** Funcionalidade escolhida:** 
- Registar uma nova encomenda.

- O funcionário regista uma nova encomenda para um cliente, indicando um ou mais produtos e as respetivas quantidades. A encomenda só pode ser criada se existir stock disponível.

Escolhemos esta funcionalidade porque é o centro do domínio do StockFlow: envolve quase todas as classes do projeto e contém a principal regra de negócio (não é possível encomendar mais do que o stock existente).

O sistema valida o stock de cada produto antes de confirmar a encomenda.
