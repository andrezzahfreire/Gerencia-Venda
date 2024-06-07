## Sistema de Gerenciamento de Vendas em Java

### Descrição

Este projeto implementa um sistema em Java para gerenciar as vendas de uma empresa. O sistema armazena os dados das vendas em um arquivo texto e utiliza uma árvore AVL ou Rubro Negra (sua escolha) para garantir a eficiência na busca e manipulação dos dados.

### Funcionalidades

* Inserir novas vendas:
    * Geração automática de ID aleatório entre 1000 e 9999 (sem repetições).
* Buscar venda por ID:
    * Exibe os dados da venda caso seja encontrada.
    * Exibe mensagem informativa caso não seja encontrada.
* Listar todas as vendas cadastradas.
* Remover uma venda cadastrada.
* Alterar os dados de uma venda (exceto ID).
* Ler dados do arquivo `venda.txt` na inicialização.
* Gravar dados no arquivo `venda.txt` ao finalizar.

### Requisitos

* Java 11 ou superior.
* Biblioteca contendo as funcionalidades do sistema (arquivo `.jar`).

### Instalação

1. Baixe o código do projeto.
2. Compile o código usando o comando `mvn clean install`.
3. Execute o JAR usando o comando `java -jar target/sistema-vendas-1.0-SNAPSHOT.jar`.

### Uso

O sistema apresenta um menu interativo para navegar pelas funcionalidades. Siga as instruções na tela para realizar as operações desejadas.

### Observações

* A biblioteca é genérica e pode ser reutilizada em outros projetos.
* O sistema é robusto e suporta um grande número de vendas.
* A interface do usuário é amigável e fácil de usar.
* O código está documentado de forma clara e concisa.

### Dicas

* Leia a documentação do código antes de usá-lo.
* Utilize ferramentas de controle de versão para gerenciar o código e colaborar com sua equipe.
* Contribua com melhorias no código abrindo issues ou pull requests no repositório do GitHub.

### Acreditamos que este sistema será uma ferramenta valiosa para gerenciar as vendas da sua empresa. Com um bom planejamento e execução, você poderá desenvolver um sistema robusto, eficiente e fácil de usar.
