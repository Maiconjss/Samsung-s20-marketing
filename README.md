# Get Your Book

## Objetivo do projeto :

Se trata de um projeto bem simples onde o objetivo era realizar uma pequena interação com o usuário, o cliente clicando em um botão automaticamente aparece um pequeno formulário ( contendo sua devida estilização ).Após o clique surgem outras funcionalidades como o preechimento das informações e exigidas e uma ação de enviar esses dados para assim ter seu devido retorno.

Foi utilizado um exemplo bem simples com a manipulação do DOM, onde o 'click' adiciona uma nova classe que contém o formulário e ao clicar novamente ele remove, limpando a tela do usuário.

### Antes do click:

![Screenshot_2020-05-19 Get Your Book](https://user-images.githubusercontent.com/57241193/82291890-31e24f00-9980-11ea-8d90-cf5bf4eb2e34.png)

### Depois do click:

![Screenshot_2020-05-19 Get Your Book(1)](https://user-images.githubusercontent.com/57241193/82291987-5a6a4900-9980-11ea-8b80-efb3404cc1a0.png)

## Javascript :

`document.querySelector('header button') .addEventListener("click", function() { document.querySelector('.form') .classList.toggle('hide') })`j

## Observações :

Ao término desse experimento concluí que através de poucos elementos podemos tornar a experiência do usuário mais agradável, característica que pra mim é de extrema importância para o desenvolvimento front-end.
