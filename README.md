# Exemplo Aquitetura MVC
Objetivo:

Separar dados ou lógica de negócios (Model) da interface do usuário (View) e do fluxo da aplicação (Control)
A idéia é permitir que uma mesma lógica de negócios possa ser acessada e visualizada através de várias interfaces.
Na arquitetura MVC, a lógica de negócios (chamaremos de Modelo) não sabe de quantas nem quais interfaces com o usuário estão exibindo seu estado.

Sobre a MVC:

Um dos primeiros padrões identificados; 
surgiu na comunidade de Smalltalk;

Contexto: 
aplicações interativas que requerem interfaces flexíveis.

Solução com a MVC:

A aplicação é dividida em três partes:

Modelo (MODEL): Lógica de negócio;

Visão (VIEW): Camada de interface com o usuário. 

Nesta camada o usuário vê o estado do modelo e pode manipular a interface, para ativar a lógica doenegócio;

Controlador (CONTROLLER): Transforma eventos gerados pela interface em ações de negócio, alterando o modelo.
