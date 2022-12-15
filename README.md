# E não era exatamente aquilo!

Após a primeira versão do projeto de banco de dados para o sistema hospitalar, notou-se a necessidade de expansão das funcionalidades, incluindo alguns requisitos essenciais a essa versão do software. As funcionalidades em questão são para o controle na internação de pacientes. Será necessário expandir o Modelo ER desenvolvido e montar o banco de dados, criando as tabelas para o início dos testes.

Entenda o assuntoConsidere a seguinte descrição e o diagrama ER abaixo: No hospital, as internações têm sido registradas por meio de formulários eletrônicos que gravam os dados em arquivos. Para cada internação, são anotados a dados de entrada, a dados previstos de alta e dados efetivos de alta, além da descrição textual dos procedimentos a serem realizados. As internações precisam ser vinculadas a quartos, com a numeração e o tipo. Cada tipo de quarto tem sua descrição e seu valor diário (a princípio, o hospital trabalha com apartamentos, quartos duplos e enfermaria). Também é necessário controlar quais profissionais de enfermaria serão responsáveis ​​​​por acompanhar o paciente durante sua internação.Para cada enfermeiro(a), é necessário nome, CPF e registro no conselho de enfermagem (CRE). A internação, obviamente,

Mãos a obra? Faça a ligação do diagrama acima ao diagrama desenvolvido na atividade antrior, construindo relacionamentos com entidades relacionadas. E eleve o seu diagrama para que já selecionando os tipos de dados que serão trabalhados e em quais situações. Por último, crie um script SQL para a geração do banco de dados e para instruções de montagem de cada uma das entidades/tabelas presentes no diagrama completo (considerando as entidades do diagrama da atividade anterior e as novas entidades propostas no diagrama acima). Também chore tabelas para relacionamentos quando necessário. Aplique colunas e chaves primárias e estrangeiras.Use ferramentas, como ERPlus, Lucidchart, draw.io (via web) e MySQL Workbench, ou mesmo um editor de imagens para o diagrama. Você pode utilizar o MySQL Workbench ou o DBdiagram.io para montar os scripts SQL