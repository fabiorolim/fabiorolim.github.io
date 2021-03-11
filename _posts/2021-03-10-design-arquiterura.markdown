---
layout: post
title:  "Design e Arquiterura de Sistemas"
date:   2021-03-10 22:23:00
categories: Desenvolvimento Arquitetura Design 
---


#### Você sabe o que esses termos significam ? 



Bom, se você já leu sobre isso antes, deve saber o quanto esses termos são debatidos.
 
No livro **Clean Arquiteture**, o [Uncle Bob](https://blog.cleancoder.com), promete acabar com a confusão entre esses conceitos e afirma que não existe nenhuma diferença entre **Arquitetura e Design**!
 
Para explicar isso, Uncle Bob faz uma analogia de um software com uma casa, onde a arquitetura da casa é definida pela forma da casa, aparência externa, layouts, espaços etc. Todas essas seriam definições e características de alto nível de uma casa.
Entretanto, os detalhes de baixo nível como quantidade de interruptores, tomadas etc. estão todos presentes na planta da casa.
 
Portanto, Unble Bob afirma que, na prática, todos esses detalhes, sejam de alto ou baixo nível, fazem parte do design da casa como um todo, que nenhum desses conceitos existem isoladamente e não há linhas de separação entre eles.
 
Mas se na prática esses conceitos são inseparáveis, podemos ao menos em teoria isolá-los para defini-los a fim de uma melhor compreensão.
 
De forma simples e resumida, podemos dizer que a arquitetura lida com a complexidade do software em alto nível e o design com os detalhes de baixo nível.
 
Vamos comparar o motor de um carro a um software para compreendermos outros aspectos relevantes.
 
No motor em funcionamento, veremos vários componentes interligados e colaborando entre si para transformarem combustão (energia química) em energia cinética.
 
Cada um desses componentes (alternador, cabeçote, cilindros, pistões, virabrequim etc.) tem uma responsabilidade no sistema automotivo e são construídos especificamente para cumprirem suas funções. Se houver uma falha em um dos componentes o sistema inteiro enfrentará problemas, ou pelo menos o resultado final será comprometido de alguma forma.
 
Como esses componentes se comunicam, tipo de cabo, protocolo de comunicação, injeção direta ou indireta, são fatores que determinarão algumas características importantes do veículo como: desempenho, consumo, custo de mão de obra, confiabilidade etc.
 
Da mesma forma, um software é formado por partes menores (componentes) que também mantém um fluxo de comunicação. As estratégias de como essa interação ocorre são atividades arquiteturais, que devem ser definidas de forma a garantir que os atributos de qualidade, restrições de alto nível e objetivos do negócio sejam atendidos pelo sistema.
 
Se refletirmos sobre as relações entre design e arquitetura, é aceitável uma compreensão de que decisões arquiteturais sempre influenciam no design. Retornando à analogia, se a regra de negócio exigir um carro com mais desempenho e a estratégia for estabelecer uma injeção direta de combustível (decisão arquitetural), obviamente, os componentes responsáveis por esse processo devem ser projetados para isso. (Design)
