DCC033/034 - Analise Numérica/Cálculo Numérico - 2018.2
=======================================================

Professor: Fabricio Murai

Turmas:
 * Cálculo Numerico TB1 (Fabricio) + TB3 (Sebastián), Auditório II, Ter e Qui 9:25 - 11:05
 * Análise Numérica TN1 (Fabricio) + TN2 (Frederico), Auditorio I, Ter e Qui 14:55 - 16:35

Horários de monitoria (a definir):

 * Dia da semana: Horário - Local (email, monitor oficial?)



Atualizações importantes!
-------------------------
 * 24/08: Lista 4-2 disponível aqui [Lista 04-2]
 * 24/08: Lista 4-1 disponível aqui [Lista 04-1]
 * 21/08: Lista 3 disponível aqui [Lista 03]
 * 14/08: Lista 2 disponível aqui [Lista 02]
 * 07/08: Lista 1 disponível aqui [Lista 01]

Aulas
-----

**Plano de aulas inicial**

|Aula  |  Dia     | Parte I: Sistemas Numéricos e Sistemas lineares | Link Slides |
|------|----------|--------------------------------------------------------------|-------------|
|01|Ago 07| Apresentação da disciplina. Sistemas Numéricos.  | [Apresentacao] [Erros] [Notebook PF] |
|02|Ago 09| Introdução Python. | [Python intro]|
|03|Ago 14| Revisão de AL. Sistemas triangulares. |  [Revisao AL] |
|04|Ago 16| Eliminação de Gauss. Contagem de Operações. | |
|05|Ago 21| Uso da Decomposição. | [UsoDecomposicao] |
|06|Ago 23| Decomposição LU. | [Fatoracao LU] |
|07|Ago 28| Decomposição de Cholesky. | [Cholesky]|
|08|Ago 30| Análise do erro na solução de sistemas. | [NumeroCondicao] |
|09|Set 01| Prova 1 (Sábado às 10:00, Sala ??) | |

|Aula  |  Dia     | Parte II: Interp. Polinomial, Ajuste de Curvas | Link Slides |
|------|----------|--------------------------------------------------------------|-------------|
|10 | Set 04 | Interpolação Polinomial. Polinômio de Lagrange.  | [InterpolacaoPolinomial] [InterpolacaoLagrange]|
|11 | Set 06 | Polinômio de Netwon.  | [InterpolacaoNewton]|
|12 | Set 11 | Polinômio de Gregory-Newton.  | |
|13 | Set 13 | Escolha de pontos. Erro de truncamento.  |  [ErroTruncamento] |
|14 | Set 18 | Regressão Linear Simples.  | [AjusteCurvas] [RegressaoLinear] |
|15 | Set 20 | Qualidade do ajuste.  | Sem notebook, feito no quadro. |
|16 | Set 25 | Regressão Linear Múltipla.  | [SelecaoModelo] |
|17 | Set 27 | Ajuste via decomposição em valores singulares.  | [QuadradosMinimosLinear] [QRdecomp] |
|18 | Set 29  | Prova 2 (Sábado às 10:00, Sala ??)                        | |


|Aula  |  Dia     | Parte III: Integração Numérica e Raízes de equações    | Link Slides |
|------|----------|--------------------------------------------------------------|-------------|
|19 |Out 02| Integração Numérica. Fórmulas de Newton-Cotes.   | [IntegracaoNumerica] [NewtonCotes] | 
|20 |Out 04| Erro de Integração de Newton-Cotes.  | [ErroIntegracao]|
|21 |Out 09|  Quadratura de Gauss-Legendre.  |  [GaussLegendre]|
|22 |Out 11| Erro de Integração de Gauss-Legendre. | [GaussLegendre] |
|23 |Out 16 | Isolamento de raízes de polinômios. | Sem slides |
|24 |Out 18 | Isolamento de raízes.  | [RaizesEquacoes] |
|25 |Out 23 | Método da bisseção  | [BaseadosTangente] |
|26 |Out 25 | Métodos baseados em aperoximação Linear.  |  |
|27 |Out 30 | Métodos baseados em aperoximação Linear. |   |
|28| Nov 1 | Métodos baseados em tangente. |             |
|29| Nov 6 | Compração dos métodos. |             |
|30| Nov 10 | Prova 3 (Sábado às 10:00, Sala ??)                                           |             |

Trabalhos de Programação
------------------------
 * 


Listas de exercícios
--------------------
 * [Lista 01]: entrega 14/08/2018 via Moodle.
 * [Lista 02]: entrega 21/08/2018 via Moodle.
 * [Lista 03]: entrega 28/08/2018 via Moodle.
 * [Lista 04-1]: entrega 30/08/2018 via Moodle.
 * [Lista 04-2]: entrega 04/09/2018 via Moodle.

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

[Lista 01]: ../../ancn_slides/semana1.pdf
[Lista 02]: ../../ancn_slides/semana2.pdf
[Lista 03]: ../../ancn_slides/semana3.pdf
[Lista 04-1]: ../../ancn_slides/semana4-1.pdf
[Lista 04-2]: ../../ancn_slides/semana4-2.pdf
[Lista SL]: ../../ancn_slides/lista1.pdf
[Lista SL2]: ../../ancn_slides/lista2.pdf
[Lista IP]: ../../ancn_slides/lista3.pdf
[Lista AC]: ../../ancn_slides/listaAC.pdf
[Lista IN]: ../../ancn_slides/listaIN.pdf
[Lista RE]: ../../ancn_slides/listaRE.pdf
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

[EDOs]:../../ancn_slides/aula-solucao-edo.pdf
[Apresentacao]:../../ancn_slides/Apresentacao.pdf
[Otimizacao 1]:../../ancn_slides/raizes-otimizacao.pdf
[Otimizacao 2]:../../ancn_slides/raizes-otimizacao03.pdf
[TP2]:../../ancn_slides/TP2.ipynb
[TP1]:../../ancn_slides/TP1.ipynb
[Python intro]:https://nbviewer.jupyter.org/github/data-8/stat89a/blob/gh-pages/MatricesAndGraphsNB1.ipynb
[Otimizacao]:https://nbviewer.jupyter.org/github/fabriciomurai/teaching/blob/master/ancn_slides/MinimosLocais.ipynb
[GaussLegendre]:https://nbviewer.jupyter.org/github/fabriciomurai/teaching/blob/master/ancn_slides/GaussLegendre.ipynb
[ErroIntegracao]:https://nbviewer.jupyter.org/github/fabriciomurai/teaching/blob/master/ancn_slides/ErroIntegracao.ipynb
[QuadradosMinimosLinear]:https://nbviewer.jupyter.org/github/fabriciomurai/teaching/blob/master/ancn_slides/QuadradosMinimosLinear.ipynb
[RaizesEquacoes]:https://nbviewer.jupyter.org/github/fabriciomurai/teaching/blob/master/ancn_slides/RaizesEquacoes.ipynb
[BaseadosAproxLinear]:https://nbviewer.jupyter.org/github/fabriciomurai/teaching/blob/master/ancn_slides/BaseadosAproxLinear.ipynb
[BaseadosTangente]:https://nbviewer.jupyter.org/github/fabriciomurai/teaching/blob/master/ancn_slides/BaseadosTangente.ipynb
[Otimizacao]:https://nbviewer.jupyter.org/github/fabriciomurai/teaching/blob/master/ancn_slides/MinimosLocais.ipynb
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
