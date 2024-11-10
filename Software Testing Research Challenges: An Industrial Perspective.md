# Software Testing Research Challenges: An Industrial Perspective

N. Alshahwan, M. Harman and A. Marginean, "Software Testing Research Challenges: An Industrial Perspective," 2023 IEEE Conference on Software Testing, Verification and Validation (ICST), Dublin, Ireland, 2023, pp. 1-10, doi:[10.1109/ICST57152.2023.00008](https://ieeexplore.ieee.org/document/10132192).

## 1. Fichamento de Conteúdo

O artigo analisa os principais desafios enfrentados nas grandes empresas ao implementar testes de softwares em softwares complexos, analisando a partir das experiências da Meta. Ele, por sua vez, cita 3 pontos críticos: Reparo e aprimoramento autmátizado de código, geração automática de testes e a eficiência na manutenção de softwares em grande escala. O artigo ressalta que, mesmo com os avanços na área de automação de testes, ainda é nescessário superar barreiras para o desempenho confiável da automação de testes. O autor cita o test flakiness como um dos problemas mais agravantes, porque esse, por sua vez, pode gerar instabilidades no software, mesmo quando não há grandes mudaças nos códigos realizados, afetando as empresas em seu tempo perdido para realizar a automação dos testes e gastos no desenvolvimento, uma vez que, as equipes de desenvolvimento irão ter que gastar e investir em recursos adicionais para identificar se o problema é real ou somente um teste instável. Outro tema abordado no artigo é a utilização de IA e ML para otimizar os testes de software, esses, podem ajudar a encontrar erros nos códigos e realizar os reparos necessários, mas, caso executado em códigos maiores e mais robustos, podem gerar falhas caso seja realizado sem a intervenção de um dev. O artigo também cita o "oracle problem" (problema do oráculo) que atrasa a validação no comportamento correto do software, ele sugere utilizar testes "end to end", testes de unidade e testes de mutação para aumentar a cobertura do software, apesar do alto gasto computacional. O artigo finaliza dizendo que, embora seja uma forma promissora a automação de testes de software com IA, ainda há a nescessidade de se adaptar a softwares mais complexos, para reduzir custos e aumentar a confiabilidade nos testes de grande escala. 

## 2. Fichamento Bibliográfico 

* _Regression Testing_ (Teste de regressão) Análise na mudança do código, evitando as falhas no desempenho e confiabilidade. (página 01).
* _Unite Testing_ (Teste de unidade) busca utilizar ferramentas que identificam mudanças após a alteração de um software. (página 01).
* _Test Flakiness_ (Teste de instabilidade) Testes feitos com o instuito de descobrir instabilidades do software. (página 03).
* _Generative AI_ (IA generativa) IA utilizada para a detecção e previsão de falhas, essencial para a robustez dos sistemas.  (página 06).
* _Oracle problem_ (Problema do oráculo) desafio em determinar resultados esperados nos testes sem conhecimento prévio. (página 02).

## 3. Fichamento de Citações 

* _"Automated software testing has been widely studied by the research community, leading to considerable industrial uptake, for example at Meta [1], [2], Microsoft [3] and Google [4]."_
* _"Although generally fast to execute and easy to understand, unit tests can also be brittle; small changes in implementation details can cause unit tests to break (becoming inapplicable) or to fail (due to unimportant internal behavioural changes for which they should pass). "_
* _"The past five decades have witnessed and increasing intensity of work on AI-based optimisation techniques for improving software testing [69]–​[71] and, since at least 2001 [33], software engineering more generally. Over the past three decades, software engineers have also become increasingly excited by the potential of machine learning to tackle automation challenges in software engineering [72]–​[74]."_
* _"Testing can always be more efficient, if we can find ways to squeeze the attainment of more valuable test signal into the same amount of available system resources."_
* _"It is important to be able to measure the impact of signals provided by automated testing improvement technologies. This impact assessment also needs to be automated, to support continuous evaluation and improvement of the deployment."_


