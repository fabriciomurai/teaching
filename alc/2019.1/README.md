﻿Álgebra Linear Computacional - 2019.1
=====================================

Professores: Fabricio Murai e Letícia Pereira Pinto

Horário: Ter e Qui 17:00 - 18:40

Local: CAD1 - Auditório 1A

Turmas:
 
* DCC033 - 2019_1 - ANALISE NUMERICA - TZ
* DCC049 - 2019_1 - TOPICOS EM SISTEMAS DE INFORMACAO - TZ
* DCC639 - 2019_1 - ÁLGEBRA LINEAR COMPUTACIONAL - TZ
* DCC639 - 2019_1 - ÁLGEBRA LINEAR COMPUTACIONAL - TZ1


Horário de monitoria:

* Quarta 12:30 às 14:00, Sala 2031 (Álvaro)
* Quinta 07:50 às 09:20, Sala 2031 (Juliana)


Atualizações importantes
-------------------------
 * [Lista 06] e [EP 6] podem ser baixados aqui (Moodle está indisponível).


Aulas
-----

**Plano de aulas inicial**

|Aula|   Dia  | Assunto | Link Slides |
|----|--------|--------------------------------------------------------------|-------------|
| 01 | Feb 26 | Apresentação da disciplina.  | [Apresentacao] |
| 02 | Mar 12 | Acurácia, Uso de Memória, Velocidade, Escalabilidade.  | [Caracteristicas] |
| 03 | Mar 14 | SVD, Ortogonalidade e Normas Vetoriais.  | [SVD e NMF] |
| 04 | Mar 19 | Revisão SVD, NMF, Normas Matriciais, SVD truncado.  | [SVD e NMF] |
| 05 | Mar 21 | Posto e valores singulares, SVD randomizado, Complexidade.  | [SVD e NMF] |
| 06 | Mar 26 | Análise de Componentes Principais.  | [PCA slides] |
| 07 | Abr 02 | Interpretação SVD e Exemplo PCA.  | [PCA] |
| 08 | Abr 04 | Sistemas Lineares: existência e unicidade.  | [PCA] [PCA slides] |
| 09 | Abr 09 | Prova 1.  |  |
| 10 | Abr 11 | Sistemas triangulares. Eliminação de Gauss. Pivotação.  | [SLs] [SLs slides] |
| 11 | Abr 16 | Fatoração LU. Fatoração PA=LU.  | [SLs] [SLs slides] |
| 12 | Abr 23 | Estabilidade. Decomposição Cholesky. Uso de decomposição.  | [SLs] |
| 13 | Abr 25 | Implementação, complexidade e estabilidade de Cholesky.Numero de condição.  | [SLs] |
| 14 | Abr 30 | Ajuste de curvas. Qualidade do ajuste. Método dos Quadrados mínimos.  | [Ajuste slides] [AjusteCurvas] |
| 15 | Mai 02 | Regressão Linear Simples e Múltipla.  | [RegressaoLinear] |
| 16 | Mai 07 | Complexidade da Regressão Linear. Decomposição QR.  | [RegressaoLinear] [QRdecomp] |
| 17 | Mai 09 | Prova 2.  | |


Listas de exercícios
--------------------
 * Lista 1 e EP1: entrega 24/03/2019 via Moodle.
 * Lista 2 e EP2: entrega 28/03/2019 via Moodle.
 * Lista 3 e EP3: entrega 04/04/2019 via Moodle.
 * Lista 4 e EP4: entrega 23/04/2019 via Moodle.
 * Lista 5 e EP5: entrega 30/04/2019 via Moodle.
 * Lista 6 e EP6: entrega 07/05/2019 via Moodle.

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
 * [Python notebook Hello World](https://github.com/data-8/stat89a/blob/gh-pages/MatricesAndGraphsNB1.ipynb)
 * [Métodos de decomposição QR por Peter Alfeld](https://pdfs.semanticscholar.org/6b42/3dfa845827ca4dc57f6f1736754e938b9c58.pdf)
 * [Fatoração QR e Decomposição em Valores Singulares](http://www.cs.princeton.edu/courses/archive/fall11/cos323/notes/cos323_f11_lecture09_svd.pdf)
 * [Condicionamento e Estabilidade Numérica por Eric Liu, Yelp](http://web.mit.edu/ehliu/Public/Yelp/conditioning_and_precision.pdf)
 * "When Pi is not 3.14" (vídeo sobre normas): https://www.youtube.com/watch?v=ineO1tIyPfM
 * Site interativo sobre regressão linear: http://shiny.estatistica.ccet.ufrn.br/regressao-linear-interativa
 * Livro colaborativo de Cálculo Numérico da UFRGS (com introdução ao Python): https://www.ufrgs.br/reamat/CalculoNumerico/livro-py/main.html
 * Cálculo Numérico -- Fundamentos e Aplicações. Claudio Hirofume Asano e Eduardo Colli [Livro CN].


[Livro CN]: https://www.ime.usp.br/~asano/LivroNumerico/LivroNumerico.pdf


[Caracteristicas]: https://nbviewer.jupyter.org/github/fabriciomurai/teaching/blob/master/alc/2019.1/nbs/1.%20Why%20are%20we%20here.ipynb
[SVD e NMF]: https://nbviewer.jupyter.org/github/fabriciomurai/teaching/blob/master/alc/2019.1/nbs/2.%20Topic%20Modeling%20with%20NMF%20and%20SVD.ipynb
[PCA]: https://nbviewer.jupyter.org/github/fabriciomurai/teaching/blob/master/alc/2019.1/nbs/3.%20PCA.ipynb
[SLs]: https://nbviewer.jupyter.org/github/fabriciomurai/teaching/blob/master/alc/2019.1/nbs/4.%20Gaussian%20Elimination%20and%20LU%20factorization.ipynb

[Lista SL]: ../../ancn_slides/lista1.pdf
[Lista SL2]: ../../ancn_slides/lista2.pdf
[Lista IP]: ../../ancn_slides/lista3.pdf
[Lista AC]: ../../ancn_slides/listaAC.pdf
[Lista IN]: ../../ancn_slides/listaIN.pdf
[Lista RE]: ../../ancn_slides/listaRE.pdf
[Lista 06]: ../../ancn_slides/semana6.pdf
[EP 6]: ../../ancn_slides/ep6.zip
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
[Apresentacao]:../../ancn_slides/01_Apresentacao.pdf
[Otimizacao 1]:../../ancn_slides/raizes-otimizacao.pdf
[Otimizacao 2]:../../ancn_slides/raizes-otimizacao03.pdf
[TP2]:../../ancn_slides/TP2.ipynb
[TP1]:../../ancn_slides/TP1.ipynb
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


[PCA slides]: ../../ancn_slides/PCA.pdf
[SLs slides]: ../../ancn_slides/SLs.pdf
[Ajuste slides]: ../../ancn_slides/AjusteCurvas.pdf
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
