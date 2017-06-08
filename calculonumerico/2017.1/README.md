DCC034 - Cálculo Numérico - 2017.1
==================================

Professores: Fabricio Murai

Local da aula: ICEx, Sala 1023

Horário: Ter/Qui 17:00 - 18:40

Turmas: TZ

Monitor: Rafael Bruno Siqueira 'at' gmail 'dot' com

Local de atendimento: ICEx, Sala 1015

Hoário de atendimento: Sexta 11:10 -- 12:50


Atualizações importantes!
-------------------------
* Mai 31: Detalhamento das notas da Prova 3 disponível [P3-Notas]
* Mai 22: Exercícios recomendados como revisão para prova 3: [Lista 4] (ex. 2, 3 e 5), [Lista 5] (ex. 7), [ListaNewtonCotes] (ex. 4 e 6), [ListaQuadGauss] (ex. 1)
* Mai 9: Detalhamento das notas da Prova 2 disponível [P2-Notas]
* Mai 3: Quiz teórico disponível [QuizTeorico]
* Abr 22: Notas dos quizzes atualizadas
* Abr 12: Notas da P1 atualizadas devido a mudança no critério de correção das questões 8 e 10
* Abr 11: Notas da P1 [P1-Notas] [P1-Stats]
* Abr 04: Lista de fórmulas a ser distribuída na prova [Formulario]
* Mar 22: Notas podem ser visualizadas nesse link [Notas]
* Mar 22: Slides de divulgação da maratona de programação [Maratona]
* Mar 22: Corrigido gabarito do Quiz 01
* Mar 20: Criado Google Group https://groups.google.com/d/forum/cn-2017-1. Por favor entre no grupo.
* Mar 10: Correção na descrição do método de Newton nos slides [00-Intro]. A fórmula correta é

 x_{n+1} = x_n - f(x_n)/f'(x_n).

Aulas
-----

**Plano de aulas inicial**

|Aula  |  Dia     | Sistemas lineares                                            | Link Slides |
|------|----------|--------------------------------------------------------------|-------------|
|1-2   |  09 Mar  | Introdução.                                                  |[00-Intro], [01-Pseudo], [02-SL]|
|3-4   |  14 Mar  | Conceitos fundamentais.                                      |[02-AL], [02-SL] |
|      |  16 Mar  | Não haverá aula (atividades acadêmicas complementares)       |             |
|5-6   |  21 Mar  | Representação numérica                                       |[Quiz01], [03-SN], [Erros]|
|7-8   |  23 Mar  | Erros, Sistemas triangulares, Eliminação de Gauss.           |[Quiz02], [03-SN], [02-SL]      |
|9-10  |  28 Mar  | Eliminação de Gauss, Decomposição LU.                        |[Quiz03], [02-SL], [Aula05] |
|11-12 |  30 Mar  | Decomposição LU, Decomposição de Cholesky.                   |[Quiz04], [02-SL], [Aula06] |
|13-14 |  04 Abr  | Uso da decomposição.                                         |[Quiz05], [02-SL], [Aula07] |
|15-16 |  06 Abr  | Análise de erro na solução de sistemas.                      |[Quiz06], [02-SL], [Aula08] |
|17-18 |  08 Abr  | Prova 1. (Sábado às 12:00)                                    |[P1-Stats], [P1-Notas] |

|Aula  |  Dia     | Interpolação polinomial                                      | Link Slides |
|------|----------|--------------------------------------------------------------|-------------|
|19-20 |  11 Abr  | Polinômios interpoladores. Polinômios de Lagrange.           |[Aula09], [03-Interpolacao] |
|21-22 |  18 Abr  | Polinômios de Newton.                                        |[Quiz07], [03-Interpolacao], [Aula10] |
|23-24 |  20 Abr  | Polinômios de Gregory-Newton e escolha de pontos.            |[Quiz08], [03-Interpolacao], [Aula11] |
|      |  25 Abr  | Não haverá aula (atividades acadêmicas complementares)       |             |
|25-26 |  27 Abr  | Erro de truncamento.                                         |[Quiz09], [Aula12], [03-Interpolacao] |

|Aula  |  Dia     | Ajuste de curvas                                             | Link Slides |
|------|----------|--------------------------------------------------------------|-------------|
|27-28 |  02 Mai  | Regressão linear simples e múltipla                          |[Aula13], [04-Ajuste]|
|29-30 |  04 Mai  | Qualidade do ajuste                                          |[Quiz10], [Aula14], [04-Ajuste] |
|31-32 |  06 Mai  | Prova 2. (Sala 1020, Sábado às 08:00)                        |[P2-Stats], [QuizTeorico], [GabaritoTeorico] |
|33-34 |  09 Mai  | Decomposição QR                                              |[Quiz11], [Aula15], [QR], [Gram-Schmidt], [Video-sobre-QR] |

|aula  |  dia     | Integração numérica                                          | Link Slides |
|------|----------|--------------------------------------------------------------|-------------|
|35-36 |  11 Mai  | Fórmulas de Newton-Cotes.                                    |[Quiz12], [Aula16], [05-Integracao] |
|37-38 |  16 Mai  | Erro de integração de Newton-Cotes.                          |[Quiz13], [Aula17], [05-Integracao] |
|39-40 |  18 Mai  | Quadratura de Gauss-Legendre.                                |[Quiz14], [Aula18], [05-Integracao] |
|41-42 |  23 Mai  | Erro de integração de Gauss-Legendre. Integração iterativa.  |[Quiz15], [Aula19], [05-Integracao] |
|43-44 |  25 Mai  | Prova 3. (Quinta)                                            |[P3-Notas] |

|Aula  |  Dia     | Raízes de equações                                           | Link Slides |
|------|----------|--------------------------------------------------------------|-------------|
|45-46 |  30 Mai  | Isolamento de raízes.                                        |[Aula20], [06-Raizes]|
|47-48 |  01 Jun  | Método da Bisseção.                                          |[Quiz16], [Aula21], [06-Raizes] |
|49-50 |  06 Jun  | Métodos baseados em tangente: Newton                         |[Quiz17], [Aula22], [Raizes01] |
|51-52 |  08 Jun  | Métodos baseados em tangente: Secante e Regula-Falsi         |[Quiz18], [Aula23], [Raizes02]             |
|53-54 |  13 Jun  | Otimização de funções com uma variável                       |[Raizes02] |
|55-56 |  20 Jun  | Caso multivariado                                            |             |
|57-58 |  22 Jun  | Exemplos e Comparação dos métodos.                           |             |
|59-60 |  27 Jun  | Prova 4. (Terça)                                             |             |


Exercícios do Prof. Renato Assunção
-----------------------------------
 * [Lista 1] [Gabarito 1]
 * [Lista 2]
 * [Lista 3] [Gabarito 3]
 * [Lista 4]
 * [Lista 5]
 * [Lista 6]
 * [Lista 7]
 * [Lista 8]
 * [Lista 9]

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
[ListaNewtonCotes]: http://paginapessoal.utfpr.edu.br/tatianecazarin/calculo-numerico/listas-de-exercicios/Lista6_integracao.pdf
[ListaQuadGauss]: http://paginapessoal.utfpr.edu.br/yaratadano/2013-02/cc33d-calculo-numerico/listas-de-exercicios/Lista%20de%20Exerci301cios%204%20-%20Quadratura%20Gaussiana.pdf

[00-Intro]: ../../ancn_slides/00tz-Intro.pdf
[01-Pseudo]: ../../ancn_slides/01-Conceitos.pdf
[02-SL]: ../../ancn_slides/02-SistemasLineares.pdf
[03-Interpolacao]: ../../ancn_slides/03-InterpolacaoPolinomial.pdf
[04-Ajuste]: ../../ancn_slides/04-AjusteCurvas.pdf
[05-Integracao]: ../../ancn_slides/05-IntegracaoNumerica.pdf
[06-Raizes]: ../../ancn_slides/06-RaizesEquacoes.pdf
[QR]: ../../ancn_slides/QRdecomp.pdf
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
[Aula13]: ../../ancn_slides/A13-RegressaoLinear.pdf
[Aula14]: ../../ancn_slides/A14-QualidadeAjuste.pdf
[Aula15]: ../../ancn_slides/A15-QR.pdf
[Aula16]: ../../ancn_slides/A16-NewtonCotes.pdf
[Aula17]: ../../ancn_slides/A17-ErroIntegracao.pdf
[Aula18]: ../../ancn_slides/A18-QuadraturaGauss.pdf
[Aula19]: ../../ancn_slides/A19-ErroQuadraturaGauss.pdf
[Aula20]: ../../ancn_slides/A20-IsolamentoRaizesBissecao.pdf
[Aula21]: ../../ancn_slides/A21-Bissecao.pdf
[Aula22]: ../../ancn_slides/A22-Newton.pdf
[Aula23]: ../../ancn_slides/A23-SecanteRegulaFalsi.pdf
[Erros]: ../../ancn_slides/03-PontoFlutuanteErros.pdf
[Raizes01]: ../../ancn_slides/raizes-otimizacao01.pdf
[Raizes02]: ../../ancn_slides/raizes-otimizacao02.pdf
[Raizes03]: ../../ancn_slides/raizes-otimizacao03.pdf
[QuizTeorico]: ../../ancn_slides/quizz-theory.pdf
[GabaritoTeorico]: ../../ancn_slides/gabarito-theory.pdf
[Quiz01]: ../../ancn_slides/quizz01.pdf
[Quiz02]: ../../ancn_slides/gabarito02.pdf
[Quiz03]: ../../ancn_slides/gabarito03.pdf
[Quiz04]: ../../ancn_slides/gabarito04.pdf
[Quiz05]: ../../ancn_slides/gabarito05.pdf
[Quiz06]: ../../ancn_slides/gabarito06.pdf
[Quiz07]: ../../ancn_slides/gabarito07.pdf
[Quiz08]: ../../ancn_slides/gabarito08.pdf
[Quiz09]: ../../ancn_slides/gabarito09.pdf
[Quiz10]: ../../ancn_slides/gabarito10.pdf
[Quiz11]: ../../ancn_slides/gabarito11.pdf
[Quiz12]: ../../ancn_slides/gabarito12.pdf
[Quiz13]: ../../ancn_slides/gabarito13.pdf
[Quiz14]: ../../ancn_slides/gabarito14.pdf
[Quiz15]: ../../ancn_slides/gabarito15.pdf
[Quiz16]: ../../ancn_slides/gabarito16.pdf
[Quiz17]: ../../ancn_slides/gabarito17.pdf
[Quiz18]: ../../ancn_slides/gabarito18.pdf
[Maratona]: ../../ancn_slides/divulgacao-maratona.pdf
[Notas]: https://docs.google.com/spreadsheets/d/1Jj4B5pZUjqkPsDmNNvjAiSXKOOzk_EtbKYVpVCbxLX4/edit?usp=sharing
[Formulario]: http://homepages.dcc.ufmg.br/~lcerf/slides/formulario.pdf
[P1-Stats]: ../../ancn_slides/p1_stats.pdf
[P1-Notas]: ../../ancn_slides/p1_notas_cn.pdf
[P2-Notas]: https://docs.google.com/spreadsheets/d/1Ojr3uzk5OpZrg0Cw1eHa_lS4Gy9OFwzJ8DSS_EMTZD4/edit?usp=sharing
[P2-Stats]: ../../ancn_slides/p2_stats.pdf
[P3-Notas]: ../../ancn_slides/p3_notas.pdf
[Gram-Schmidt]: http://www.math.ucla.edu/~yanovsky/Teaching/Math151B/handouts/GramSchmidt.pdf
[Video-sobre-QR]: https://www.youtube.com/watch?v=3HS-BRbJOd0
