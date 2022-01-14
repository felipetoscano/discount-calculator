# discount-calculator
Projeto em C# que realiza descontos, utilizando o Design Pattern Chains of Responsability

Neste exemplo, precisamos calcular um desconto em função do resultado do outro. Por exemplo, primeiro tentamos calcular o desconto na classe **FiveItensDiscount**. Caso o desconto seja aplicado, será retornado o valor final e o resultado apresentado na tela. Mas se o desconto não for aplicado, ela irá chamar a próxima classe **FiveHundredDiscount** e assim sucessivamente, de acordo com o que foi configurado na classe **DiscountProcessor**. Por isto o nome "Chains of Responsability", cada classe se liga com outra formando uma cadeia e com cada uma funcionando de forma independente, concentrando apenas suas regras de responsabilidade. Tudo isso irá acarretar em um código mais limpo, de mais fácil manutenção e evitando um número enorme de "ifs".
