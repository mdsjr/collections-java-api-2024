markdown
Copiar código
# Bootcamp DIO Santander Java

Bem-vindo ao repositório de código para acompanhar as aulas do Bootcamp DIO Santander Java. Este repositório contém exemplos de código e projetos práticos desenvolvidos durante o curso.

## Conteúdo

- **CarrinhoDeCompras**: Implementação de uma classe para gerenciar um carrinho de compras.
- **ListaTarefa**: Implementação de uma classe para gerenciar uma lista de tarefas.

## Estrutura do Projeto

O projeto está organizado no seguinte formato de pacotes:

main
└── java
└── list
└── OperacoesBasicas
├── CarrinhoDeCompras.java
├── Item.java
└── ListaTarefa.java

csharp
Copiar código

### CarrinhoDeCompras

A classe `CarrinhoDeCompras` permite adicionar, remover e calcular o valor total dos itens no carrinho. 

#### Exemplo de Uso

```java
public static void main(String[] args) {
    CarrinhoDeCompras carrinhoDeCompras = new CarrinhoDeCompras();

    carrinhoDeCompras.adicionarItem("Lápis", 2.00, 3);
    carrinhoDeCompras.adicionarItem("Caderno", 35.00, 1);
    carrinhoDeCompras.adicionarItem("Borracha", 2.00, 2);

    carrinhoDeCompras.exibirItens();

    carrinhoDeCompras.removerItem("Lápis");

    carrinhoDeCompras.exibirItens();

    System.out.println("O valor total da compra é = " + carrinhoDeCompras.calcularValorTotal());
}
ListaTarefa
A classe ListaTarefa permite adicionar, remover e listar tarefas.

Exemplo de Uso
java
Copiar código
public static void main(String[] args) {
    ListaTarefa listaTarefa = new ListaTarefa();

    System.out.println("O número total de elementos na lista é: " + listaTarefa.obterNumeroTotalTarefas());

    listaTarefa.adicionarTarefa("tarefa 1");
    listaTarefa.adicionarTarefa("tarefa 1");
    listaTarefa.adicionarTarefa("tarefa 2");

    System.out.println("O número total de elementos na lista é: " + listaTarefa.obterNumeroTotalTarefas());

    listaTarefa.removerTarefa("Tarefa 2");

    System.out.println("O número total de elementos na lista é: " + listaTarefa.obterNumeroTotalTarefas());

    listaTarefa.obterDescricoesTarefas();
}
Requisitos
Java JDK 8 ou superior
IDE de sua preferência (Eclipse, IntelliJ, VSCode, etc.)
Como Executar
Clone o repositório:

sh
Copiar código
git clone https://github.com/seu-usuario/bootcamp-dio-santander-java.git
Importe o projeto em sua IDE de preferência.

Navegue até a classe principal que deseja executar e rode o método main.

Contribuição
Contribuições são bem-vindas! Se você tiver sugestões de melhorias ou novos exemplos, sinta-se à vontade para abrir um pull request.

Licença
Este projeto está licenciado sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.


Adapte conforme necessário, incluindo informações adicionais ou específicas sobre o seu projeto e estrutura do repositório.





