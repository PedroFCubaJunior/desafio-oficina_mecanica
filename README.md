# desafio-oficina_mecanica
Desafio DIO curso Formação SQL Database Specialist por Juliana Mascarenhas

Como um cliente pode ter vários veículos e cada veículo pode ter vários donos (no caso do veículo ser vendido e continuar mantendo histórico de serviços com o novo dono) foi gerado uma relação m:n que gerou uma terceira entidade que nomeei Veículo e proprietário atual

Criei uma entidade Avaliação que relaciona com Mecânico (gerando Equipe de mecâqnicos) e Veículo e proprietário atual

A Ordem de serviço possui relação 1:1 com Equipe de mecânicos, m:n com Mão de obra (gerando Lista de serviços mão de obra) e m:n com pedido de peças (gerado de Peças e Fornecedor)

Deixei a identificação se o serviço é preventivo ou corretivo no atributo Objetivo do serviço dentro da entidade Ordem de serviço

Deixei como atributo da entidade Avaliação a aprovação do cliente. Obs.: não consegui usar o tipo Boolean neste atributo, por isso deixei como tipo VARCHAR(1) para S ou N.
