A classe Dado representa um dado de 6 lados.

valor é um atributo que armazena o número obtido na última jogada.

O construtor inicializa o valor do dado como 1 por padrão.

Cria um objeto Random para gerar números aleatórios.

random.nextInt(6) gera um número de 0 a 5, por isso somamos +1 para obter um número de 1 a 6, como um dado real.

O número gerado é armazenado no atributo valor e também retornado.

Método getter que retorna o valor atual do dado. Pode ser usado se você quiser apenas ver o valor sem rolar novamente.

Sobrescreve o método toString() da classe Object.

Permite imprimir o objeto diretamente com System.out.println(dado) e mostrar o resultado da jogada.

