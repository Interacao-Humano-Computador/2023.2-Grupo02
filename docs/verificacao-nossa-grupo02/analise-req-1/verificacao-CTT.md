# Verificação do ConcurTaskTrees - CTT

## Introdução

Este documento é uma verificação do artefato [ConcurTaskTrees - CTT](https://interacao-humano-computador.github.io/2023.2-Ventoy/AnaliseDeRequisitos/analisedetarefas/ConcurTaskTrees/) na versão 1.1 de data 08/10/2023, autorada por [Milena Baruc](https://github.com), que é integrante do [grupo 02](https://github.com/Interacao-Humano-Computador/2023.2-Ventoy/tree/main), cujo projeto tem como foco o site do [Ventoy](https://www.ventoy.net/en/index.html). O propósito desta verificação é identificar possíveis problemas no artefato.

## Metodologia 

A verificação do artefato seguirá o [planejamento](https://interacao-humano-computador.github.io/2023.2-Ventoy/) estabelecido pelo nosso grupo. Conforme detalhado no planejamento, destaca-se a relevância do subtópico da metodologia neste documento, para apresentar a tabela contendo os checklists utilizados para realizar essa verificação deste artefato em específico. 

<br>

<center>

**Tabela 1** - Checklist Geral não preenchido
  
| ID | Descrição                                                                                              | Avaliação  | Observação                                                             | Referência           |
|----|------------------------------------------------------------------------------------------------------- |------------|------------------------------------------------------------------------|----------------------|
| 1  | O artefato possui Introdução?                                                                          | -          | -                                                                      | [Ventoy](https://www.ventoy.net/en/index.html)                     |
| 2  | O artefato possui a metodologia utilizada?                                                             | -          | -                                                                      | [Ventoy](https://www.ventoy.net/en/index.html)                     |
| 3  | O artefato possui bibliografia/referências bibliográficas?                                             | -          | -                                                                      | [Ventoy](https://www.ventoy.net/en/index.html)                     |
| 4  | O artefato possui um histórico de versões com o id e descrição das versões, data, autores e revisores? | -          | -                                                                      | [Ventoy](https://www.ventoy.net/en/index.html)                     |
| 5  | Todos os textos estão na norma padrão?                                                                 | -          | -                                                                      | [Ventoy](https://www.ventoy.net/en/index.html)                     |

Fonte: [Altino Arthur](https://github.com/arthurrochamoreira)

</center>

<br>

<center>

**Tabela 2** - Checklist Específico não preenchido

| ID  | Descrição                                                                                                         | Avaliação  | Observação                                                                   | Referência                           |
|----|------------------------------------------------------------------------------------------------------------------|------------|------------------------------------------------------------------------------|--------------------------------------|
| 1  | O modelo inclui tarefas do usuário externas ao sistema?                                                           | -          | -                                                                            | Barbosa e Silva 2010, Capítulo 6     |
| 2  | Inclui tarefas do sistema sem interação do usuário?                                                               | -          | -                                                                            | Barbosa e Silva 2010, Capítulo 6     |
| 3  | Inclui tarefas interativas (diálogos usuário-sistema)?                                                             | -          | -                                                                            | Barbosa e Silva 2010, Capítulo 6     |
| 4  | Possui tarefas abstratas para auxiliar na decomposição?                                                           | -          | -                                                                            | Barbosa e Silva 2010, Capítulo 6     |
| 5  | As relações de ativação entre tarefas são definidas? (Tarefa T2 inicia após T1)                                    | -          | -                                                                            | Barbosa e Silva 2010, Capítulo 6     |
| 6  | As tarefas alternativas (escolhas) são mutuamente exclusivas?                                                      | -          | -                                                                            | Barbosa e Silva 2010, Capítulo 6     |
| 7  | Tarefas concorrentes que podem ser realizadas simultaneamente estão identificadas?                                 | -          | -                                                                            | Barbosa e Silva 2010, Capítulo 6     |
| 8  | Relações de suspensão e retomada de tarefas estão presentes?                                                       | -          | -                                                                            | Barbosa e Silva 2010, Capítulo 6     |

Fonte: [Altino Arthur](https://github.com/arthurrochamoreira)

</center>

<br>

<center>

**Tabela 3** - Checklist Geral preenchido

| ID | Descrição                                                                                              | Avaliação (Sim, Não, Incompleto)  | Observação                                                             |
|----|------------------------------------------------------------------------------------------------------- |------------|------------------------------------------------------------------------|
| 1  | O artefato possui Introdução?                                                                          |   Sim      |                                                                       |
| 2  | O artefato possui a metodologia utilizada?                                                             |   Sim      |                                                                       |
| 3  | O artefato possui bibliografia/referências bibliográficas?                                             |    Sim     |                                                                       |
| 4  | O artefato possui um histórico de versões com o id e descrição das versões, data, autores e revisores? |    Sim     |                                                                       |
| 5  | Todos os textos estão na norma padrão?                                                                 |    Sim     |                                                                       |

Fonte: [Altino Arthur](https://github.com/arthurrochamoreira)

</center>

<br>

<center>

**Tabela 4** - Checklist Específico preenchido

| ID | Descrição                                                                                                         | Avaliação (Sim, Não, Incompleto)  | Observações               |
|----|------------------------------------------------------------------------------------------------------------------|------------|---------------------------|
| 1  | O modelo inclui tarefas do usuário externas ao sistema?                                                          |   Sim      |                          |
| 2  | Inclui tarefas do sistema sem interação do usuário?                                                              |   Sim         |                          |
| 3  | Inclui tarefas interativas (diálogos usuário-sistema)?                                                           |   Sim         |                          |
| 4  | Possui tarefas abstratas para auxiliar na decomposição?                                                          |   Incompleto        |  Nem todas as relações de ativação estão claramente definidas nos diagramas.                        |
| 5  | As relações de ativação entre tarefas são definidas? (Tarefa T2 inicia após T1)                                  |   Incompleto       |     Não está totalmente claro se todas as tarefas alternativas são mutuamente exclusivas.                     |
| 6  | As tarefas alternativas (escolhas) são mutuamente exclusivas?                                                    |   Sim        |                          |
| 7  | Tarefas concorrentes que podem ser realizadas simultaneamente estão identificadas?                               |   Sim       |                          |
| 8  | Relações de suspensão e retomada de tarefas estão presentes?                                                     |   Incompleto        |     As relações de suspensão e retomada não estão completamente detalhadas em todos os diagramas.                     |

</center>

## Verificação em Trio

<center>

**Tabela 5** - Cronograma de verificação

| Participantes | Data | Horário | Link da Gravação|
|--------------|-------|---------|-----------------|
| Luis Miranda, Vinicius Mendes e Altino Arthur | 04/12/2023 | 00:00/00:00| [Link da Gravação]()  |

Fonte: [Altino Arthur](https://github.com/arthurrochamoreira)

</center>

## Sugestões de Melhorias

</center>

## Acompanhamento

A figura 1 e 2 apresenta um gráfico com o percentual de respostas conforme, não conforme, incompleto ou não se aplica, obtidas através da checklist geral e específico de verificação.

<center>

**Figura 1** - Percentual das respostas obtidas na verificação checklist geral


Fonte: [Altino Arthur](https://github.com/arthurrochamoreira)
</center>

<center>

**Figura 2** - Percentual das respostas obtidas na verificação checklist específico


Fonte: [Altino Arthur](https://github.com/arthurrochamoreira)
</center>

### Figura 1 - Gráfico do Resultado da Verificação

### Percentual de Aproveitamento

Para saber a porcentagem de aproveitamento do artefato, será utilizado a Equação na figura 3:

**Figura 3** - Equação de percentual de aproveitamento

![Equação](../../assets/equacao.PNG)

Através dos checklists realizados, podemos observar que:

- **9/13** exigências são atendidas (Conformes);
- **4/13** exigências estão incompletas;
- **0/13** exigências estão erradas ou não foram realizadas (Não conformes).
- **0/13** não se aplica.

Onde 13 é a quantidade de itens avaliados na verificação (considerando a soma dos itens das Tabelas 1 e 2).

Portanto, com base no cálculo apresentado, pode-se dizer que o aproveitamento deste artefato está em 69,23%.

## Retrabalho

| Data de Correção | Descrição                                                                                   | Responsável(eis)  | Revisor(es)  | Status  |
|------------------|---------------------------------------------------------------------------------------------|-------------------|--------------|---------|
| 04/12/2023       | Clarificação das relações de ativação entre tarefas nos diagramas CTT                       | Altino Arthur     | [Mayara Alves](https://github.com/Mayara-tech)              | Executado|
| 04/12/2023       | Verificação da exclusividade mútua em tarefas alternativas                                  | Altino Arthur     |  [Mayara Alves](https://github.com/Mayara-tech)            | Executado|
| 04/12/2023       | Detalhamento das relações de suspensão e retomada de tarefas nos diagramas CTT              | Altino Arthur     |    [Mayara Alves](https://github.com/Mayara-tech)          | Executado|

## Bibliografia

> BARBOSA, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021);Interação Humano-Computador e Experiência do usuário.<br>
> BILHETERIA DIGITAL. Interacao-Humano_computador. Distrito Federal, 2023. Disponível em: <https://interacao-humano-computador.github.io/2023.1-BilheteriaDigital/>. Acesso em: 10/11/2023.<br>

## 📑 Histórico de Versões

| Versão | Data       | Descrição              | Autor(es)                                        | Revisor(es)                                      |
| ------ | ---------- | ---------------------- | ------------------------------------------------ | ------------------------------------------------ |
|  1.0   | [02/12/2023] | Criação da verificação do ConcurTaskTrees - CTT | [Altino Arthur](https://github.com/arthurrochamoreira) |[Mayara Alves](https://github.com/Mayara-tech)   |     
