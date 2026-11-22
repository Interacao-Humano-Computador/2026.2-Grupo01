## Tabela de contribuição
| Data       | Contribuição      | Autor(es)   | Revisor(es) |
| ---------- | ----------------- | ----------- | ----------- |
| 22/11/2026 | Criação da página | Lucas Sales | A definir   |

## Introdução

Inspeções são um método formal, eficiente e econômico de encontrar erros em projeto e código (FAGAN, 1976, p. 189). Como o custo de retrabalho cresce quanto mais tarde o erro é corrigido, achar defeitos perto de onde nasceram sai de 10 a 100 vezes mais barato do que corrigi-los na segunda metade do processo (FAGAN, 1976, p. 186). Em um estudo da IBM, a adição das inspeções I1 e I2 aumentou em 23% a produtividade da etapa de codificação (FAGAN, 1976, p. 187), e a amostra inspecionada teve 38% menos erros do que uma amostra revisada por *walk-throughs* (FAGAN, 1976, p. 188). Em outro caso, o programa de aplicação do Aetna, as inspeções detectaram 82% dos erros e economizaram 25% das horas de programação previstas, como descrito na [figura 1](#figura-1) (FAGAN, 1976, p. 189).

<a id="figura-1">
![Eficiência de detecção de erro](../../../assets/error_detection_efficiency.png)
</a>
<p align="center">Figura 1 - Eficiência de detecção de erro </p>

O que torna a técnica tão eficaz é o processo bem definido, com papéis claros (moderador, projetista, codificador e testador) e etapas que separam os objetivos: visão geral, preparação, inspeção, retrabalho e acompanhamento, como declarados na [figura 2](#figura-2) (FAGAN, 1976, p. 190). Na reunião de inspeção o foco é apenas encontrar erros, sem tentar resolvê-los na hora, o que mantém a equipe concentrada em um objetivo por vez (FAGAN, 1976, p. 193). Diferente dos walk-throughs, que variam muito de lugar para lugar e geram resultados pouco repetíveis, a inspeção usa moderador treinado, checklists de "como achar erros" e a distribuição dos tipos de erro mais frequentes, como descrito na [figura 3](#figura-3) (FAGAN, 1976, p. 200), além de um acompanhamento que reduz as correções mal feitas (FAGAN, 1976, p. 194).

<a id="figura-2">
![Processo de inspeção](../../../assets/fagan_processo_de_inspecao.png)
</a>
<p align="center">Figura 2 - Processo de inspeção de Fagan. </p>

<a id="figura-3">
![Tipos de erro](../../../assets/inspecao_e_walkthrough.png)
</a>
<p align="center">Figura 3 - Comparação entre inspeção e walk-through. </p>

Além de achar defeitos, a inspeção traz benefícios de longo prazo. O programador recebe feedback detalhado e rápido sobre os tipos de erro que mais comete e tende a melhorar até dentro do mesmo projeto (FAGAN, 1976, p. 197), e os participantes ganham muito conhecimento do produto em pouco tempo (FAGAN, 1976, p. 203). Os dados coletados também permitem identificar módulos mais propensos a erros (FAGAN, 1976, p. 198-199) e acompanhar a qualidade e o andamento do projeto já na primeira metade do cronograma (FAGAN, 1976, p. 202-203). Fagan ressalta que esses resultados devem servir ao aprendizado da equipe e nunca à avaliação de desempenho individual (FAGAN, 1976, p. 197), e conclui que as inspeções aumentam a produtividade, melhoram a qualidade final e fortalecem o controle do processo (FAGAN, 1976, p. 205).

Desta forma, o presente documento visa, utilizando as técnicas de Fagan, declarar uma **lista de verificação** para a etapa 1 da disciplina de Interação Humano Computador(IHC) da Faculdade de Ciências e Tecnologia em Engenharia (FCTE) da Universidade de Brasília (UnB).

**Fonte**

Conteúdo de Fagan (1976).
<a id="figura-4"></a>
<p align="left">Página 189. </p>
![Inspeções](../../../assets/fagan_189.png)
<p align="center">Figura 4 - Método de inspeções por Fagan </p>
<a id="figura-5"></a>
<p align="left">Página 186. </p>
![Custo de retrabalho](../../../assets/fagan_186.png)
<p align="center">Figura 5 - Custo de retrabalho  </p>
<a id="figura-6"></a>
<p align="left">Página 187. </p>
![Produtividade](../../../assets/fagan_187.png)
<p align="center">Figura 6 - Produtividade em relação às inspeções  </p>
<a id="figura-7"></a>
<p align="left">Página 188. </p>
![Erros em relação à inspeção](../../../assets/fagan_188.png)
<p align="center">Figura 7 - Porcentagem de erro a menos entre as amostras I1 e I2.  </p>
<a id="figura-8"></a>
<p align="left">Página 189. </p>
![Economias e eficiência](../../../assets/fagan_189_2.png)
<p align="center">Figura 8 - Relação de economia e eficiência na detecção de erros.  </p>
<a id="figura-9"></a>
<p align="left">Página 190. </p>
![Papeis na inspeção](../../../assets/fagan_190.png)
<p align="center">Figura 9 - Papéis na inspeção.  </p>
<a id="figura-10"></a>
<p align="left">Página 193. </p>
![Objetivo da inspeção](../../../assets/fagan_193.png)
<p align="center">Figura 10 - Objetivo da inspeção.  </p>



## Os entregáveis
Para a entrega da etapa 2, os seguintes itens devem ser apresentados:

1. Perfil do usuário,
2. Técnica de elicitação do perfil do usuário,
3. Personas,
4. Cenários,
5. Diagrama HTA das tarefas elicitadas,
6. Diagrama CTT das tarefas elicitadas


## Listas de verificação

[Perfil do usuário](./01LucasSalesVerifacaçãoListaPerfilUsuario.pdf)

[Técnica de elicitação do perfil do usuário](./01LucasSalesVerifacaçãoListaMetodosdeAvaliação.pdf)

[Personas](./01LucasSalesVerifacaçãoListaPersonas.pdf)

[Cenários](./01LucasSalesVerifacaçãoListaCenários.pdf)

[Análise hierárquica de tarefas (HTA)](./01LucasSalesVerifacaçãoListaHTA.pdf)

[Análise de tarefas (CTT)](./01LucasSalesVerifacaçãoListaCTT.pdf)


## Agradecimento e Uso de IA generativa

O documento utiliza IA generativa nos seguintes pontos:

- Formatação e redação de texto;
- Geração e adaptação de código markdown;


## Referências Bibliográficas

> 1. BARBOSA, Simone Diniz Junqueira et al. Interação humano-computador e experiência do usuário. 1. ed. Rio de Janeiro: Simone Diniz Junqueira Barbosa, 2021.
> 2. FAGAN, M. E. Design and code inspections to reduce errors in program development. IBM Systems Journal, v. 15, n. 3, 1976.




## Histórico de versão
| Versão | Data       | Descrição          | Autor(es)   | Revisor(es) |
| ------ | ---------- | ------------------ | ----------- | ----------- |
| `1.0`  | 22/11/2026 | Criação da página. | Lucas Sales |             |