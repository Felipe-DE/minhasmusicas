O projeto **"Minhas Músicas"** foi desenvolvido com o objetivo de aplicar os quatro pilares fundamentais da **Orientação a Objetos**: Abstração, Herança, Encapsulamento e Polimorfismo. Utilizando a linguagem **Java** ☕, foram criadas classes que representam músicas e podcasts, cada uma contendo atributos e métodos específicos para garantir a correta implementação das regras de negócio. O código foi organizado em pacotes, promovendo modularidade e reutilização eficiente de código.

No aspecto do **Encapsulamento**, os atributos das classes foram declarados como `private`, assegurando que o acesso e modificação desses valores ocorressem de maneira controlada, por meio de métodos `getter` e `setter`. Esse princípio garante que apenas partes autorizadas do código possam alterar informações sensíveis, preservando a integridade dos dados.  

A **Herança** foi aplicada através da criação de classes genéricas, permitindo que subclasses especializadas reutilizem características comuns. Um exemplo é a classe `Audio`, que serve de base tanto para `Musica` quanto para `Podcast`. Esse mecanismo evita a repetição desnecessária de código e facilita futuras expansões do projeto.  

O **Polimorfismo** está presente na sobrescrita de métodos, permitindo que cada classe tenha comportamentos distintos conforme sua necessidade. Por exemplo, a classe `Podcast` pode definir sua própria implementação do método `reproduzir()`, incluindo introduções ou anúncios antes do conteúdo principal.

A estrutura de arquivos do projeto segue um padrão organizado, facilitando a manutenção e compreensão do código. O diretório contém pacotes separados para modelos, serviços e classes principais, garantindo modularidade. Além disso, o código pode ser executado facilmente ao clonar o repositório no GitHub, abrir em uma IDE Java como **IntelliJ** ou **Eclipse**, e compilar a classe principal `Main.java`.

Um exemplo de uso do projeto seria a criação de um objeto `Musica`, definindo seus atributos e chamando o método `reproduzir()`, o que pode ser feito assim:

```java
Musica musica = new Musica();
musica.setTitulo("Bohemian Rhapsody");
musica.setArtista("Queen");
musica.setDuracao(355);

musica.reproduzir();
```

O projeto foi desenvolvido com **Java**, enfatizando os princípios da **Orientação a Objetos** e estruturando o código de maneira clara e eficiente. Seu propósito é acadêmico, e está aberto para estudos, modificações e melhorias.

Caso queira contribuir ou sugerir melhorias, fique à vontade para explorar o repositório e enviar sugestões! 🚀   
