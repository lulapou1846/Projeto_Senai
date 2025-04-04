Programação Orientada a Objetos (POO) e seus Fundamentos
1. O que é a POO e quais são seus princípios essenciais?
A POO se baseia nos seguintes princípios:
Abstração
Transforma ideias do mundo real em classes de forma simplificada. Por exemplo, um sistema bancário pode ter uma classe ContaBancaria que representa uma conta.
Encapsulamento
Restringe o acesso direto a atributos e métodos de um objeto, garantindo maior segurança e confiabilidade. O saldo de uma conta bancária, por exemplo, deve ser privado e acessível apenas por métodos específicos.
Herança
Permite que uma classe herde características e comportamentos de outra, promovendo a reutilização do código. Exemplo: ContaCorrente e ContaPoupanca podem herdar de ContaBancaria.
Polimorfismo
Habilita um objeto a assumir diferentes formas, permitindo que métodos com o mesmo nome tenham comportamentos distintos em classes derivadas. Por exemplo, calcularTaxa() pode ter diferentes implementações em ContaCorrente e ContaPoupanca.
________________________________________
2. Como a abstração é aplicada na POO?
Exemplo de Abstração
Em um sistema bancário, a classe ContaBancaria pode conter:
•	Atributos: saldo, numeroConta, titular.
•	Métodos: depositar(), sacar().
Os detalhes internos dessas operações são ocultados do usuário, que apenas interage com os métodos expostos.
________________________________________
3. Por que o encapsulamento é importante?
Para proteger o saldo de uma conta:
•	O atributo saldo é privado (private).
•	As alterações no saldo ocorrem apenas através dos métodos depositar() e sacar(), garantindo maior segurança.
Isso evita acessos não autorizados e protege as informações da conta bancária.
________________________________________
4. Como a herança facilita o desenvolvimento?
A classe ContaBancaria pode servir de base para outras classes:
•	ContaCorrente: adiciona um limite de crédito.
•	ContaPoupanca: inclui um método para calcular juros.
Isso evita repetição de código e facilita a manutenção.
________________________________________
5. O que é polimorfismo e como ele se manifesta na POO?
A função calcularTaxa() pode ser implementada de diferentes formas:
•	ContaCorrente: taxa fixa.
•	ContaPoupanca: taxa variável baseada no saldo.
Isso permite que um mesmo método tenha comportamentos distintos em classes diferentes.
________________________________________
6. Quais são os principais benefícios da POO?
1.	Reaproveitamento de Código: A herança possibilita o uso de classes existentes sem duplicação.
2.	Facilidade de Manutenção: O código modularizado torna mudanças e correções mais simples.
3.	Maior Segurança: O encapsulamento protege informações sensíveis contra acessos indevidos.
4.	Organização e Clareza: A estrutura baseada em objetos melhora a legibilidade do código.
5.	Expansibilidade: Novas funcionalidades podem ser adicionadas sem comprometer a estrutura existente.
