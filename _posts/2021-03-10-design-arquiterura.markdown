---
layout: post
title:  "Design e Arquiterura"
date:   2021-03-10 22:23:00
categories: Desenvolvimento Arquitetura Design 
---


#### Vamos refletir sobre esses termos ? 



Bom, se você já leu sobre isso antes, deve saber o quanto esses termos são debatidos.
 
No livro **Clean Arquiteture**, o [Uncle Bob](https://blog.cleancoder.com), promete acabar com a confusão entre esses conceitos e afirma que não existe nenhuma diferença entre **Arquitetura e Design**!
 
Para explicar, Uncle Bob faz uma analogia de um software com uma casa, onde a arquitetura da casa é definida pela forma da casa, aparência externa, layouts, espaços etc. Todas essas seriam definições e características de alto nível de uma casa. Entretanto, os detalhes de baixo nível como quantidade de interruptores, tomadas etc. estão todos presentes na planta da casa.
 
Portanto, Unble Bob afirma que, na prática, todos esses detalhes, sejam de alto ou baixo nível, fazem parte do design da casa como um todo, que nenhum desses conceitos existem isoladamente e não há linhas de separação entre eles.
 
Mas se na prática esses conceitos são inseparáveis, podemos ao menos em teoria isolá-los para defini-los a fim de uma melhor compreensão.
 
De forma simples e resumida, podemos dizer que a arquitetura lida com a complexidade do software em alto nível e o design com os detalhes de baixo nível.
 
Vamos comparar o motor de um carro a um software para compreendermos outros aspectos relevantes.
 
No motor em funcionamento, veremos vários componentes interligados e colaborando entre si para transformarem a energia química, através da combustão, em energia cinética.
 
Cada um desses componentes (alternador, cabeçote, cilindros, pistões, virabrequim etc.) têm uma responsabilidade no sistema automotivo e são construídos especificamente para cumprirem suas funções. Se houver uma falha em um dos componentes o sistema inteiro enfrentará problemas, ou pelo menos o resultado final será comprometido de alguma forma.
 
Como esses componentes se comunicam, tipo de cabo, protocolo de comunicação, injeção direta ou indireta, são fatores que determinarão algumas características importantes do veículo como: desempenho, consumo, custo de mão de obra, confiabilidade etc.
 
Da mesma forma, um software é formado por partes menores, com responsabilidades bem definidas, **componentes de software**, que vão desde simples módulos e classes a camadas de acesso a bancos de dados e middlewares. Estes, também mantém um fluxo de comunicação em **runtime** através de suas **interfaces**.

As decisões de construção desses componentes, em sua estrutura interna (baixo nível), dizem respeito ao **Design** do código. A utilização de blocos if/elif/else ou switch/case, a escolha de um **design pattern**  são exemplos de estratégias a nível de design. 

Já as estratégias de como as interações entre os compoenentes acontecem são decisões arquiteturais, que devem ser definidas de forma a garantir que os atributos de qualidade, restrições de alto nível e objetivos do negócio sejam atendidos pelo sistema.

*De modo geral, os envolvidos no processo arquitetural, devem tomar as decisões de design corretas para atender aos objetivos que a arquiterura pretende alcançar*
 
Portanto, se refletirmos sobre as relações entre design e arquitetura, é aceitável uma compreensão de que decisões arquiteturais sempre influenciam no design. Retornando à analogia, se a regra de negócio exigir um carro com mais desempenho e a estratégia for estabelecer uma injeção direta de combustível (Decisão Arquitetural), obviamente, os componentes responsáveis por esse processo devem ser projetados para isso. (Design)
