# README - *Exercícios de Programação em Java*

*Este repositório contém soluções para diferentes exercícios de programação em Java. Cada exercício propõe a criação de classes seguindo os princípios de orientação a objetos.*

---

## *1. Cadastro de Alimentos Orgânicos*

### *Requisitos:*

*Crie um sistema para registrar produtos orgânicos vendidos em uma feira.*

- *Criar uma classe **`Produto`** com atributos privados:*
  - *`nome`** (String)*
  - *`preco`** (double)*
- *Criar uma classe **`AlimentoOrganico`** que herda de **`Produto`** e adiciona um atributo privado:*
  - *`certificado`** (boolean)*
- *Implementar getters e setters.*
- *No **`main`**, criar um array com 5 produtos e exibir apenas os alimentos certificados.*

### *Estrutura das Classes:*

- *`Produto.java`*
- *`AlimentoOrganico.java`*
- *`Main.java`*

---

## *2. Energia Renovável*

### *Requisitos:*

*Crie um sistema para monitorar o desempenho de placas solares em uma usina.*

- *Criar uma classe **`EquipamentoEletrico`** com atributos privados:*
  - *`potencia`** (double)*
  - *`fabricante`** (String)*
- *Criar uma classe **`DispositivoMonitoramento`** com atributo privado:*
  - *`tipoSensor`** (String)*
- *Criar uma classe **`PlacaSolar`** que ****não**** herda diretamente das outras, mas contém instâncias de **`EquipamentoEletrico`** e **`DispositivoMonitoramento`**.*
- *Implementar getters e setters.*
- *No **`main`**, armazenar informações de placas solares em um array e exibir detalhes das que possuem sensores específicos.*

### *Estrutura das Classes:*

- *`EquipamentoEletrico.java`*
- *`DispositivoMonitoramento.java`*
- *`PlacaSolar.java`*
- *`Main.java`*

---

## *Como Executar os Códigos?*

1. *Crie um diretório para cada exercício.*
2. *Salve os arquivos **`.java`** dentro do diretório correspondente.*
3. *Compile os arquivos com o comando:*
   ```sh
   javac *.java
   ```
4. *Execute o programa principal:*
   ```sh
   java Main
   ```

*Caso precise de mais ajustes ou melhorias, sinta-se à vontade para modificar o código! 🚀*

