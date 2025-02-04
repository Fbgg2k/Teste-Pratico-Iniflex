```markdown
# Teste Prático - Iniflex

Este projeto consiste em um sistema para gerenciar uma lista de funcionários de uma indústria. O sistema foi desenvolvido em Java e implementa diversas funcionalidades para manipular as informações dos funcionários.

## Requisitos

O projeto atende aos seguintes requisitos:

1. Classe `Pessoa` com os atributos:
   - `nome` (String)
   - `dataNascimento` (LocalDate)

2. Classe `Funcionario` que estende a classe `Pessoa`, com os atributos:
   - `salario` (BigDecimal)
   - `funcao` (String)

3. Classe `Principal` para executar as seguintes ações:
   1. Inserir todos os funcionários na mesma ordem e informações da tabela fornecida.
   2. Remover o funcionário "João" da lista.
   3. Imprimir todos os funcionários com todas suas informações:
      - Data deve ser exibida no formato `dd/mm/aaaa`.
      - Valores numéricos devem ser exibidos com separador de milhar como ponto e decimal como vírgula.
   4. Aplicar um aumento de 10% nos salários e atualizar a lista de funcionários.
   5. Agrupar os funcionários por função em um `Map`, onde a chave é a função e o valor é a lista de funcionários.
   6. Imprimir os funcionários agrupados por função.
   7. Imprimir os funcionários que fazem aniversário em outubro e dezembro.
   8. Imprimir o funcionário com a maior idade, exibindo nome e idade.
   9. Imprimir a lista de funcionários em ordem alfabética.
   10. Imprimir o total dos salários dos funcionários.
   11. Imprimir quantos salários mínimos ganha cada funcionário, considerando que o salário mínimo é R$ 1212.00.

## Executando o Projeto

Para executar o projeto, siga os seguintes passos:

1. Clone o repositório:
   ```bash
   git clone https://github.com/seuusuario/nome-do-repositorio.git
   cd nome-do-repositorio
   ```

2. Compile o projeto usando o Maven ou Java Compiler:
   ```bash
   mvn compile
   ```

3. Execute a classe principal:
   ```bash
   java -cp target/classes Main
   ```

## Estrutura do Projeto

- `src/main/java`: Contém as classes `Pessoa`, `Funcionario` e `Principal`.
- `src/test/java`: Contém testes automatizados (se houver).

## Contribuição

Sinta-se à vontade para fazer um fork deste projeto e enviar pull requests com melhorias ou correções.

## Licença

Este projeto é licenciado sob a MIT License - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

```

Esse README fornece uma visão clara do projeto. Sinta-se à vontade para personalizá-lo conforme a sua necessidade!
