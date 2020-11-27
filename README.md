# Padr-o-Factory-Methood

Intent->  Definir  uma interface para criar  um objeto , mais  deixa  que as  subclasses decidam  qual classe instanciar  de criação através de subclasses.

Motivation->  Essa aplicação precisa criar objetos  cujas  classes  fazem parte de uma  estrutura de classes, mas não  necessita  ou não tem como  definir qual a subclasse intanciada. Portanto  ele é utilizado  nesses casos  e decide com base do contexto, qual das subclasses ativas. 


Objetivo ->  Disponibilizar  método que permite  criar objeto, centralizando  as dependencias em um  único  ponto. Útil quando  a crição  envolve  uma série de objetos. Reduz  acoplamento  por meio  do principio da responsablidade única.



Applicabillity ->  Quando  se uma  estrutura  complexa de classe que demanda  dependência  com vários tipos. Quando se  classes, como  um único ponto de responsabilidade.



Participantes:  Client : É quem tem uma dependencia com IProduct.

 Creator: Define o Factory  Method para retornar  instancia Concrete Product.
 
 
  IProduct: Define  a interface  de objetos  que o Factory  cria 
  
  
  Product A, Product B -> implementa a interface  do Product.
