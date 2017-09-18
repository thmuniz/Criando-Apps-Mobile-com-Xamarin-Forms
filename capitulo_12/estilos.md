# Capítulo 12

## Estilos

Aplicações "Xamarin.Forms" geralmente contém múltiplos elementos com configurações de propriedades idênticas. Por exemplo, você pode ter diversos botões com as mesmas cores, tamanhos de fonte, e opções de "layout". No código, você pode designar propriedades idênticas para múltiplos botões em um "**loop"**, porém "**loops**" não estão disponíveis em XAML. Se você quiser evitar muita remarcação repetitiva, outra solução é necessária;

A solução é a classe "**Style**", que é uma coleção de configurações de propriedade consolidadas em um objeto . Você pode definir um objeto "**Style**" para a propriedade "**Style**" de qualquer classe que deriva de "**VisualElement**".

Geralmente, você vai aplicar o mesmo objeto **Style **para vários elementos, eo estilo é compartilhado entre estes elementos.

O estilo é a principal ferramenta para dar uma aparência consistente aos elementos visuais em suas aplicações “Xamarin.Forms". Estilos ajudam a reduzir marcação repetitiva em arquivos XAML e permite que aplicações sejam mais facilmente alteradas e mantidas.

Estilos foram projetados principalmente com "XAML" em mente, e eles provavelmente não teriam sido inventados em um ambiente somente de código. No entanto, você verá neste capítulo como definir e usar estilos em código e como combinar o código e a formatação para alterar o estilo do programa dinamicamente em tempo de execução.

