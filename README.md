# •	Sistema de controle de versões (VCS)? (mínimo 10 linhas)
R= Basicamente o controle de versão é uma prática que rastreia e gerencia as alterações feitas em um arquivo ou em um conjunto de arquivos ao longo do tempo. Com isso, permitindo que os utilizadores mantenham o histórico das modificações, revertam para versões anteriores, colaborem e, projetos e resolvam conflitos de forma \eficiente. 
1-	O rastreamento das mudanças: que é o sistema de controle de versão ter o poder de registrar cada alteração feita num arquivo, criando um histórico detalhado.
2-	 2- Armazenamento de versões: onde são as versões que são armazenadas e podem ser acessadas a qualquer momento, permitindo que se volte a um estado anterior ao arquivo. 
3-	3- Colaboração: Permite que vários utilizadores trabalhem no mesmo projeto simultaneamente, evitando conflitos de edição. 
4-	4- Resolução de conflitos: Identifica e ajuda a resolver automaticamente ou manualmente as diferenças entre versões, permitindo que o projeto siga em frente

•	Cite 5 vantagens em utilizar um sistema de controle de versão
1-	Recuperar versões: Se um erro for cometido ou se algum arquivo for perdido, é possível recuperar uma versão anterior
2-	Trabalho em equipe: Facilita a colaboração em projetos, permitindo que vários utilizadores trabalhem em conjunto, com o mínimo de conflitos 
3-	Gestão de códigos: Permite um controle e gestão eficaz do código, garantindo a sua integridade e qualidade 
4-	Auditoria: Facilita a identificação de quem fez que alterações, quando e porquê, permitindo uma revisão do histórico do projeto 
 
•	Cite 3 exemplos de sistema de controle de versão
GIT
Subversion (SVN)
Concurrent
Mercurial

Desafio 2 

1 A Programação Orientada a Objetos (POO) é um paradigma que organiza o software em torno de objetos, que são instâncias de classes. Esses objetos combinam dados (atributos) e comportamentos (métodos) relacionados. A POO é usada para modelar sistemas de forma mais próxima do mundo real, facilitando a manutenção e a reutilização de código.

Seus principais pilares são:

Encapsulamento – oculta os detalhes internos dos objetos, expondo apenas o necessário.

Herança – permite que classes compartilhem atributos e métodos, promovendo o reuso.

Polimorfismo – possibilita que objetos diferentes respondam de maneira específica a uma mesma ação.

Abstração – foca nos aspectos essenciais de um objeto, ignorando os detalhes desnecessários.

Esses pilares tornam o desenvolvimento mais modular, seguro e flexível.

2 Num sistema bancário, a abstração cria uma classe genérica Conta com métodos como sacar() e depositar(), sem detalhes específicos. As classes Conta Corrente e Conta Poupança herdam de Conta e implementam suas próprias regras, como taxas ou limites. Assim, o sistema interage apenas com a classe Conta, ignorando as diferenças internas. Isso simplifica o código e permite adicionar novos tipos de conta sem grandes mudanças.

Q3 Imagine uma classe Funcionario em um sistema de RH. Ela possui um atributo privado salario, que não pode ser acessado ou alterado diretamente por outras partes do programa. Para modificar o salário, a classe oferece métodos públicos como aumentarSalario(valor), que garante que o aumento seja sempre positivo e dentro de limites permitidos. Para consultar o salário, há um método getSalario(), que retorna o valor atual. Assim, o encapsulamento protege o dado sensível (salário), evitando alterações indevidas e garantindo que as regras de negócio sejam respeitadas.


Q4 Suponha um sistema que gerencia veículos. Criamos uma classe base chamada Veiculo, que possui atributos comuns como marca, modelo e métodos como ligar() e desligar(). A partir dela, criamos subclasses específicas, como Carro e Moto, que herdam esses atributos e métodos da classe Veiculo, mas também adicionam características próprias, como quantidadeDePortas para o Carro e tipoDeGuidão para a Moto. Com a herança, reaproveitamos código comum e estendemos funcionalidades específicas para cada tipo de veículo, facilitando a organização e manutenção do sistema.




Q5 Imagine um sistema de desenho gráfico que tem uma classe base chamada Forma, com um método chamado desenhar(). As classes Circulo, Quadrado e Triangulo herdam de Forma e implementam o método desenhar() de formas diferentes, cada uma desenhando sua própria forma.

No programa principal, você pode criar uma lista de objetos do tipo Forma e chamar o método desenhar() para cada objeto, sem se preocupar com o tipo específico. Cada objeto executa sua versão do método, mostrando o comportamento adequado — isso é polimorfismo, onde um mesmo método age de forma diferente dependendo do objeto.



Q6 cinco vantagens da Programação Orientada a Objetos (POO):

Reuso de código – através da herança, é possível aproveitar código já existente em novas classes.

Modularidade – o código é organizado em objetos e classes, facilitando a manutenção e o entendimento.

Facilidade de manutenção – o encapsulamento protege os dados e reduz impactos ao modificar partes do código.

Flexibilidade – o polimorfismo permite usar diferentes objetos de forma intercambiável, facilitando extensões.

Modelagem realista – permite representar entidades do mundo real de forma mais intuitiva, facilitando o desenvolvimento.