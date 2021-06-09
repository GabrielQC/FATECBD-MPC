Gerenciador de currículos inteligente
Gabriel Q. Cordeiro

Faculdade de Tecnologia de São Paulo (FATEC) 
São José dos Campos

1. Introdução

A empresa X possui um software de gerenciamento de vagas e currículos, onde é disponibilizado um site de trabalhe conosco que permite aos interessados cadastrar seus currículos para que sejam analisados para vagas atuais ou futuras. Complementar a esse sistema, a empresa X quer uma inteligência que facilite o preenchimento das vagas com os currículos cadastrados no trabalhe conosco.
A solução proposta é um sistema de buscas dinâmicas, apoiado por uma IA, em um banco de dados que contém, em sua essência, vagas e currículos. A principal função da solução é encontrar possíveis candidatos a preencher determinadas vagas, com a possibilidade de usar filtros definidos pelo usuário. 
Paralelo ao sistema, uma inteligência aprenderá com os erros e acertos durante as buscas por candidatos, utilizando desses resultados apontar quais os melhores currículos para futuras vagas ou reabertura de uma vaga preenchida anteriormente.

2. Fundamentação

	Nessa seção, será feita uma breve explicação quanto aos principais conceitos abordados na solução.


2.1 Inteligência artificial 

   Como definido por John McCarthy (2004), pioneiro da Inteligência Artificial, “a inteligência artificial é a ciência e a engenharia de criar máquinas inteligentes, especialmente programas de computador inteligentes”.
O conceito de IA tem definições por diversos pontos de vista, normalmente divididos em processos de, pensamento e raciocínio, e comportamento, também divididos entre o sucesso em termos de fidelidade ao desempenho humano e o sucesso comparando-o a um conceito ideal de inteligência. (Russell, Stuart J., 2013, p.2).
As duas abordagens se encontram quando o propósito da IA precisa ser definido, podendo ser, por exemplo, uma máquina que simula o pensamento humano e age a partir disso, ou um programa que procura superar o nível do raciocínio de uma pessoa em determinada tarefa, apresentando soluções mais rápidas baseadas em dados de aprendizado.

2.2 Machine Learning

“É o campo de pesquisa entre estatísticas, inteligência artificial e ciência da computação, também conhecida como análises preditivas ou aprendizado estatístico.” (GUIDO, Sarah; MÜLLER, Andreas C., p.1).
Como definido por Müller e Guido, o aprendizado de máquina permite encontrar informações e conhecimento em dados, encontrando padrões, aprendendo com eles e permitindo que exista uma base para tomadas de decisões. 
É importante, durante todo o processo, entender os dados trabalhados para encontrar a melhor solução possível, que se relaciona com o problema a ser resolvido. É uma questão de otimizar e utilizar soluções da melhor forma possível, não aplicando algoritmos eficientes em outros casos mas que não se adequa ao problema em questão.


3. Metodologia e Métodos
	
O sistema consistirá, basicamente, em um armazém de currículos e vagas. Baseado nessa essência, o mesmo permitirá ao usuário fazer buscas baseadas em filtros dinâmicos, retornando os currículos que melhor atenderem aos requisitos.
A inteligência do sistema terá dados coletados através de vagas preenchidas com determinados currículos, encontrando padrões em determinadas vagas e em determinados tipos de vagas, melhorando suas sugestões de currículos quando efetuadas buscas ou quando novas vagas forem incluídas ou reativadas, onde a mesma atuará como uma espécie de “headhunter”.
Os dados coletados serão baseados em acertos e falhas, referentes a sugestões de currículos para determinadas vagas, assim como vagas efetivamente preenchidas por um determinados candidatos, vagas reativadas antes da previsão de conclusão, candidatos que foram sucedidos em suas determinadas vagas, etc.
As sugestões feitas pela IA são produto do aprendizado resultado da análise de vagas preenchidas. Assim, dados como tipos de profissionais preferidos, tempo de experiência do inscrito, termos utilizados com mais frequência em buscas de determinadas vagas, e também fatores negativos como demissões, encerramento de contratos antes da data prevista, serão levados em conta para futuras sugestões de candidatos para uma vaga, além de ajudar a encontrar candidatos para outras oportunidades.



4. Conclusão 

	A aplicação foi disponibilizada através de uma interface web, onde o banco de dados reflete os currículos e vagas de uma base de armazenamento pertencente a uma aplicação de RH. O objetivo é limitar a aplicação a executar somente a tarefa de encontrar os melhores candidatos às vagas de emprego cadastradas.
Inicialmente, o sistema utilizou buscas em parâmetros simples definidos pelo usuário e pelas próprias vagas, podendo assim extrair dados baseados em respostas reais da utilização do sistema.
Após três meses, o sistema passou a levar em consideração os padrões encontrados e os dados coletados no período, aplicando essa inteligência nas buscas e enriquecendo os filtros utilizados.
Nos dois meses seguintes, foi identificado um aumento em currículos rejeitados, dados os quais foram utilizados para enriquecer o conhecimento em que se baseia a IA, revertendo o quadro nos dois meses seguintes, onde se observou um balanço entre currículos rejeitados e aprovados.
No sexto mês, o sistema tem uma taxa de acerto de 85% para vagas já cadastradas e de 65% para vagas novas, mostrando-se eficiente quanto a sua função de melhorar os filtros de candidatos se baseando além de requisitos escritos.
	
Referências

BISHOP, Christopher M. Pattern Recognition and Machine Learning. New York: Springer, 2006.

GUIDO, Sarah; MÜLLER, Andreas C. Introduction to Machine Learning with Python. Sebastapol: O'Reilly Media, 2016.

McCARTHY, John. What is artificial intelligence? Standford: Standford University, 2007. Disponível em: <http://jmc.stanford.edu/articles/whatisai.html>. Acesso em: 22 mai. 2021.

RUSSEL, Stuart J. Inteligência Artificial. 3. ed. Tradução de Regina Célia Simille. Rio de Janeiro: Elsevier, 2013.
