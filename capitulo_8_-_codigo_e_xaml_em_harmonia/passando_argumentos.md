## Passando Argumentos {#passando-argumentos}

Como você viu, o _parser_ XAML instancia elementos, chamando o construtor sem parâmetro da classe ou estrutura correspondente e, em seguida, inicializa o objeto resultante definindo as propriedades sobre os valores de atributos. Isso parece razoável, no entanto, os desenvolvedores que usam XAML, por vezes, têm a necessidade de reinstanciar objetos com construtores que exigem argumentos ou chamar o método de criação estática. Estas necessidades geralmente não envolvem a própria API, mas em vez disso envolvem classes de dados externas referenciadas pelo arquivo XAML que interage com a API.

Em 2009 a especificação XAML introduziu o elemento **x:Arguments** e atributo **x:FactoryMethod **para estes casos, e Xamarim.Forms os suporta. Estas técnicas não são frequentemente utilizadas em circunstancias ordinárias, mas você deve ver como elas funcionam em caso de necessidade.

