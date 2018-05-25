DCC033 - Analise Numérica - 2018.1
==================================

Professor: Fabricio Murai

Turmas:
 * TB1, Sala 1022, Ter e Qui 9:25 - 11:05
 * TN1 e TN2, Auditorio I, Ter e Qui 14:55 - 16:35

Horário de monitoria:

 * Seg: 7:30 - 9:10 - 2060 (gabrielcalegari at ufmg, monitor oficial da TB1)
 * Ter: 18:30 - 20:10 - 2073 (alexandre.a.andrade at hotmail.com, monitor oficial das TN)
 * Qui: 14:50 - 16:30 - 2073 (marcelofaraj at ufmg)



Atualizações importantes!
-------------------------
 * TODAS: Lista sobre Integração Numérica (**Versão final**) disponível aqui [Lista IN].
 * TODAS: Lista sobre Ajuste de Curvas (**Versão final**) disponível aqui [Lista AC].
 * TB1: Trabalho de Programação 1 disponível na página.
 * TB1: Lista de exercícios 3 (**Versão final**) disponível na página.
 * TB1: Notas da Prova 1 disponíveis [aqui](https://docs.google.com/spreadsheets/d/1JBNt5ETcFQLfBDUVJyC8JDJnn6jJs_tcqGOYpMQ1FUg/edit?usp=sharing)


Aulas
-----

**Plano de aulas inicial**

|Aula  |  Dia     | Parte I: Sistemas Numéricos e Sistemas lineares | Link Slides |
|------|----------|--------------------------------------------------------------|-------------|
|01|Mar 06| Apresentação da disciplina. Sistemas Numéricos.  | [Apresentacao] [Erros]|
|02|Mar 08| Aritmética de Ponto Flutuante. Revisão de AL. | [Erros] [Notebook PF] [Revisao AL]|
|03|Mar 13| Revisão de AL. Eliminação de Gauss. | [Revisao AL] |
|04|Mar 15| Decomposição LU. Backward stability. | [Fatoracao LU] |
|05|Mar 20| Decomposição Cholesky. Modelagem de tópicos. | [Cholesky] [SVD] |
|06|Mar 22| SVD. Uso da Decomposição. | [SVD] [UsoDecomposicao] |
|07|Mar 27| Decomposição Espectral. | [DecomposicaoEspectral]|
|08|Abr 03| Numero de condição. Pagerank. | [DecomposicaoEspectral] [NumeroCondicao] |
|09|Abr 05| Aula de revisão. ||
|10|Abr 07| Prova 1 (Sábado às 10:00)  ||

|Aula  |  Dia     | Parte II: Interp. Polinomial, Ajuste de Curvas | Link Slides |
|------|----------|--------------------------------------------------------------|-------------|
|11 |Abr 10 | Interpolação Polinomial. Polinômio de Lagrange.  | [InterpolacaoPolinomial] [InterpolacaoLagrange]|
|12 |Abr 12 | Polinômio de Netwon.  | [InterpolacaoNewton]|
|13 |Abr 17 | Erro de truncamento. Escolha de pontos.  | [ErroTruncamento] |
|14 |Abr 19 | Ajuste de curvas. Qualidade do ajuste. Mínimos quadrados.  | [AjusteCurvas] |
|15 |Abr 24 | Regressão Linear Simples, Múltipla e Polinomial.  | [RegressaoLinear] |
|16 |Abr 27 | Coeficiente de Determinação. Complexidade. Linearizações.  | Sem notebook, feito no quadro. |
|17 |Mai 03 | Escolha do Modelo. Validação cruzada. Regularização.  | [SelecaoModelo] |
|18 |Mai 08 | Problema de Quadrados Mínimos Linear. Decomposição QR.  | [QuadradosMinimosLinear] [QRdecomp] |
|22 | Mai 19  | Prova 2 (Sábado às 15:00)                        | |


|Aula  |  Dia     | Parte III: Integração Numérica, EDOs e Raízes de equações    | Link Slides |
|------|----------|--------------------------------------------------------------|-------------|
|19 |Mai 10 | Integração Numérica. Fórmulas de Newton-Cotes.   | [IntegracaoNumerica] [NewtonCotes] | 
|20 |Mai 15 | Erro de Integração. Quadratura de Gauss-Legendre.  | [ErroIntegracao] [GaussLegendre]|
|21 |Mai 17 | Aula de revisão da Parte II.  | |
|23 |Mai 20 | Quadratura de Gauss-Legendre em [a,b]. Erro de Integração. | [GaussLegendre] |
|30 |Jun 16| Prova 3 (Sábado às 10:00)                                           |             |

Trabalhos de Programação
------------------------
 * [TP1]: baixar, resolver e entregar até 17/05/2018 via Moodle.


Listas de exercícios
--------------------
 * [Lista IN]: lista sobre Integração Numérica e (TN: Isolamento de raízes, TB1: EDOs), entrega 05/06/2018 via Moodle.
 * [Lista AC]: entrega 16/05/2018 via Moodle.
 * [Lista SL]: entrega 23/03/2018 via Moodle.
 * [Lista SL2]: entrega 05/04/2018 via Moodle (**atrasos não serão permitidos desta vez**).
 * [Lista IP]: entrega 26/04/2018 via Moodle.

Tutoriais
---------
Python:

https://tutorial.djangogirls.org/pt/python_introduction/

Numpy:

http://cs231n.github.io/python-numpy-tutorial/
https://www.tutorialspoint.com/numpy/index.htm

Anaconda/Jupyter:

https://paulovasconcellos.com.br/como-baixar-anaconda-31fd49c19bd8


Material Suplementar
--------------------
 * [Métodos de decomposição QR por Peter Alfeld](https://pdfs.semanticscholar.org/6b42/3dfa845827ca4dc57f6f1736754e938b9c58.pdf)
* [Fatoração QR e Decomposição em Valores Singulares](http://www.cs.princeton.edu/courses/archive/fall11/cos323/notes/cos323_f11_lecture09_svd.pdf)
* [Condicionamento e Estabilidade Numérica por Eric Liu, Yelp](http://web.mit.edu/ehliu/Public/Yelp/conditioning_and_precision.pdf)
 * "When Pi is not 3.14" (vídeo sobre normas): https://www.youtube.com/watch?v=ineO1tIyPfM
 * Site interativo sobre regressão linear: http://shiny.estatistica.ccet.ufrn.br/regressao-linear-interativa
 * Livro colaborativo de Cálculo Numérico da UFRGS (com introdução ao Python): https://www.ufrgs.br/reamat/CalculoNumerico/livro-py/main.html
 * Cálculo Numérico -- Fundamentos e Aplicações. Claudio Hirofume Asano e Eduardo Colli [Livro CN].
 * Numerical Computing with MATLAB. Cleve Moler. SIAM, Philadelphia, 2004 [Numerical MATLAB].


[Livro CN]: https://www.ime.usp.br/~asano/LivroNumerico/LivroNumerico.pdf
[Numerical MATLAB]: http://www.mathworks.com/moler/index_ncm.html


Exercícios do Prof. Renato Assunção
-----------------------------------
*ATENÇÃO*: Estas *não* são as listas de exercícios da nossa turma. São apenas material suplementar.
 * [Lista 1] [Gabarito 1]
 * [Lista 2]
 * [Lista 3] [Gabarito 3]
 * [Lista 4]
 * [Lista 5]
 * [Lista 6]
 * [Lista 7]
 * [Lista 8]
 * [Lista 9]

[Lista SL]: ../../ancn_slides/lista1.pdf
[Lista SL2]: ../../ancn_slides/lista2.pdf
[Lista IP]: ../../ancn_slides/lista3.pdf
[Lista AC]: ../../ancn_slides/listaAC.pdf
[Lista IN]: ../../ancn_slides/listaIN.pdf
[Lista 1]: http://homepages.dcc.ufmg.br/~assuncao/an/Lista01.pdf
[Gabarito 1]: http://homepages.dcc.ufmg.br/~assuncao/an/gabarito_lista_01.pdf
[Lista 2]: http://homepages.dcc.ufmg.br/~assuncao/an/Lista02.pdf
[Lista 3]: http://homepages.dcc.ufmg.br/~assuncao/an/Lista03.pdf
[Gabarito 3]: http://homepages.dcc.ufmg.br/~assuncao/an/gabarito_lista_03.pdf
[Lista 4]: http://homepages.dcc.ufmg.br/~assuncao/an/Lista04.pdf
[Lista 5]: http://homepages.dcc.ufmg.br/~assuncao/an/Lista05.pdf
[Lista 6]: http://homepages.dcc.ufmg.br/~assuncao/an/Exerc06.pdf
[Lista 7]: http://homepages.dcc.ufmg.br/~assuncao/an/Lista07.pdf
[Lista 8]: http://homepages.dcc.ufmg.br/~assuncao/an/Lista08.pdf
[Lista 9]: http://homepages.dcc.ufmg.br/~assuncao/an/Lista09.pdf

[Apresentacao]:../../ancn_slides/Apresentacao.pdf
[TP1]:../../ancn_slides/TP1.ipynb
[GaussLegendre]:https://nbviewer.jupyter.org/github/fabriciomurai/teaching/blob/master/ancn_slides/GaussLegendre.ipynb
[ErroIntegracao]:https://nbviewer.jupyter.org/github/fabriciomurai/teaching/blob/master/ancn_slides/ErroIntegracao.ipynb
[QuadradosMinimosLinear]:https://nbviewer.jupyter.org/github/fabriciomurai/teaching/blob/master/ancn_slides/QuadradosMinimosLinear.ipynb
[RegressaoLinear]:https://nbviewer.jupyter.org/github/fabriciomurai/teaching/blob/master/ancn_slides/RegressaoLinear.ipynb
[AjusteCurvas]:https://nbviewer.jupyter.org/github/fabriciomurai/teaching/blob/master/ancn_slides/AjusteCurvas.ipynb
[SelecaoModelo]:https://nbviewer.jupyter.org/github/fabriciomurai/teaching/blob/master/ancn_slides/SelecaoModelo.ipynb
[IntegracaoNumerica]:https://nbviewer.jupyter.org/github/fabriciomurai/teaching/blob/master/ancn_slides/IntegracaoNumerica.ipynb
[NewtonCotes]:https://nbviewer.jupyter.org/github/fabriciomurai/teaching/blob/master/ancn_slides/NewtonCotes.ipynb
[InterpolacaoPolinomial]:https://nbviewer.jupyter.org/github/fabriciomurai/teaching/blob/master/ancn_slides/InterpolacaoPolinomial.ipynb
[InterpolacaoLagrange]:https://nbviewer.jupyter.org/github/fabriciomurai/teaching/blob/master/ancn_slides/InterpolacaoLagrange.ipynb
[ErroTruncamento]:https://nbviewer.jupyter.org/github/fabriciomurai/teaching/blob/master/ancn_slides/ErroTruncamento.ipynb
[InterpolacaoNewton]:https://nbviewer.jupyter.org/github/fabriciomurai/teaching/blob/master/ancn_slides/InterpolacaoNewton.ipynb
[Notebook PF]:https://nbviewer.jupyter.org/github/fabriciomurai/teaching/blob/master/ancn_slides/PontoFlutuante.ipynb
[Revisao AL]:https://nbviewer.jupyter.org/github/fabriciomurai/teaching/blob/master/ancn_slides/RevisaoAL.ipynb
[Fatoracao LU]:https://nbviewer.jupyter.org/github/fabriciomurai/teaching/blob/master/ancn_slides/FatoracaoLU.ipynb
[Cholesky]:https://nbviewer.jupyter.org/github/fabriciomurai/teaching/blob/master/ancn_slides/Cholesky.ipynb
[SVD]:https://nbviewer.jupyter.org/github/fabriciomurai/teaching/blob/master/ancn_slides/SVD.ipynb
[UsoDecomposicao]:https://nbviewer.jupyter.org/github/fabriciomurai/teaching/blob/master/ancn_slides/UsoDecomposicao.ipynb
[NumeroCondicao]:https://nbviewer.jupyter.org/github/fabriciomurai/teaching/blob/master/ancn_slides/NumeroCondicao.ipynb
[DecomposicaoEspectral]:https://nbviewer.jupyter.org/github/fabriciomurai/teaching/blob/master/ancn_slides/DecomposicaoEspectral.ipynb


[00-Intro]: ../../ancn_slides/00te-Intro.pdf
[01-Pseudo]: ../../ancn_slides/01-Conceitos.pdf
[02-SL]: ../../ancn_slides/02-SistemasLineares.pdf
[02-AL]: ../../ancn_slides/A02-RevisaoAL.pdf
[03-SN]: ../../ancn_slides/A03-SistemasNumericos.pdf
[04-SL]: ../../ancn_slides/A04-SistemasLineares.pdf
[Aula05]: ../../ancn_slides/A05-DecomposicaoLU.pdf
[Aula06]: ../../ancn_slides/A06-Cholesky.pdf
[Aula07]: ../../ancn_slides/A07-UsoDecomposicao.pdf
[Aula08]: ../../ancn_slides/A08-Condicionamento.pdf
[Aula09]: ../../ancn_slides/A09-Interpolacao.pdf
[Aula10]: ../../ancn_slides/A10-PolinomioNewton.pdf
[Aula11]: ../../ancn_slides/A11-GregoryNewton.pdf
[Aula12]: ../../ancn_slides/A12-ErroInterpolacao.pdf
[Erros]: ../../ancn_slides/PontoFlutuanteErros.pdf
[QRdecomp]: ../../ancn_slides/QRdecomp.pdf
[QuizzTeorico]: ../../ancn_slides/quizz-theory.pdf
[GabaritoTeorico]: ../../ancn_slides/gabarito-theory.pdf
[Quizz01]: ../../ancn_slides/quizz01.pdf
[Quizz02]: ../../ancn_slides/gabarito02.pdf
[Quizz03]: ../../ancn_slides/gabarito03.pdf
[Quizz04]: ../../ancn_slides/gabarito04.pdf
[Quizz05]: ../../ancn_slides/gabarito05.pdf
[Quizz06]: ../../ancn_slides/gabarito06.pdf
[Quizz07]: ../../ancn_slides/gabarito07.pdf
[Quizz08]: ../../ancn_slides/gabarito08.pdf
[Quizz09]: ../../ancn_slides/gabarito09.pdf
[Maratona]: ../../ancn_slides/divulgacao-maratona.pdf
[Notas]: https://docs.google.com/spreadsheets/d/1s3jH3t-UhV2gQFDU8lJxeavxx06HK-6vq22bMz0Gnp4/edit?usp=sharing
[Formulario]: http://homepages.dcc.ufmg.br/~lcerf/slides/formulario.pdf

[P2-Notas]: https://drive.google.com/open?id=1ZbdjVT78HYdY5fVuoqiAxi1AelN-ngjD53r5_XgiG2s
[P1-Stats]: ../../ancn_slides/p1_stats.pdf
[P2-Stats]: ../../ancn_slides/p2_stats.pdf
[P1-Notas]: ../../ancn_slides/p1_notas_an.pdf
[Aula09]: ../../ancn_slides/A09-Interpolacao.pdf
[03-Interpolacao]: ../../ancn_slides/03-InterpolacaoPolinomial.pdf
