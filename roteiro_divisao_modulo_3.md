# Roteiro para reorganização dos capítulos do Módulo 3

## Objetivo geral

Depois da leitura conjunta dos capítulos atuais, das orientações do projeto e, principalmente, de **Johnson & Wichern, Anderson, Eaton e Hair**, a divisão em **núcleo**, **aprofundamentos teóricos** e **aprofundamentos metodológicos e aplicados** pode ser adotada como um protocolo editorial estável para todo o Módulo 3.

A decisão central é:

> **A divisão em núcleo, aprofundamentos teóricos e aprofundamentos metodológicos e aplicados deve organizar o percurso de leitura, e não reduzir o conteúdo do capítulo.**

Nesta etapa, portanto, **não devemos enxugar**. Primeiro classificamos, movimentamos e organizamos. Só depois, em uma revisão independente, avaliamos repetições, redação, lacunas e possíveis novas inclusões.

A ACP e a Análise Fatorial funcionam como capítulos-piloto para essa arquitetura.

---

# 1. Princípio editorial central

Cada capítulo deverá oferecer **três percursos de leitura**.

## 1.1 Núcleo

Deve permitir ao estudante compreender a técnica **sem precisar ler os aprofundamentos**.

Ao terminar o núcleo, o leitor deve conseguir responder:

1. Qual problema estatístico a técnica resolve?
2. Quais são os dados ou objetos de entrada?
3. Qual é o objeto matemático central?
4. Qual modelo, função objetivo, decomposição ou critério define a técnica?
5. Como surge matematicamente a solução?
6. Qual é a interpretação estatística e geométrica dessa solução?
7. Quais propriedades são essenciais para entender o método?
8. Quais são seus pressupostos e limites fundamentais?
9. Qual é a relação com população e amostra, quando pertinente?
10. Como a técnica se relaciona com outras técnicas do módulo?

O núcleo deve preservar a função prevista para o Módulo 3: formular as técnicas a partir dos fundamentos dos Módulos 1 e 2, sem transformar os capítulos em manuais de execução.

O percurso desejado é, em linhas gerais:

```text
problema
→ estrutura de entrada
→ formulação
→ função objetivo ou modelo
→ solução
→ geometria
→ propriedades
→ pressupostos
→ limites
→ relações com outras técnicas
```

## 1.2 Aprofundamentos teóricos

Aqui deve entrar aquilo que responde predominantemente a:

> **Por que esse resultado é verdadeiro, em que condições ele é verdadeiro e quais propriedades matemáticas ou probabilísticas mais profundas sustentam a técnica?**

São candidatos naturais:

- demonstrações longas;
- caracterizações equivalentes;
- resultados de existência e unicidade;
- identificação formal;
- invariâncias;
- indeterminações;
- resultados sobre posto e multiplicidade;
- derivações matriciais mais extensas;
- teoria probabilística que não é necessária para definir a técnica;
- distribuição exata ou assintótica de estatísticas;
- relações com Wishart;
- resultados de máxima verossimilhança mais formais;
- propriedades de estimadores;
- conexões profundas entre diferentes formulações;
- resultados sobre estabilidade ou convergência.

**Importante:** uma equação não vai para o aprofundamento simplesmente porque é difícil. Se ela é necessária para compreender **como a técnica é construída**, permanece no núcleo.

## 1.3 Aprofundamentos metodológicos e aplicados

Aqui deve entrar aquilo que responde predominantemente a:

> **Uma vez compreendida a técnica, quais decisões o analista precisa tomar e como os resultados são examinados e interpretados?**

São candidatos naturais:

- escolha de dimensionalidade;
- escolha de número de fatores ou grupos;
- critérios auxiliares;
- métodos alternativos de estimação;
- variantes operacionais do procedimento;
- critérios específicos de rotação;
- diagnósticos;
- medidas de qualidade de representação;
- contribuições de observações ou variáveis;
- elementos suplementares;
- tratamento operacional de escala;
- escolha de métrica;
- avaliação de adequação;
- avaliação de classificação;
- validação;
- estabilidade;
- leitura de mapas e representações;
- correspondência entre objetos teóricos e saídas do software.

Mas há uma fronteira importante: esse terceiro bloco **continua pertencendo ao Módulo 3**. Ele deve construir a ponte para os módulos aplicados posteriores, e não antecipar integralmente:

- tutoriais de software;
- sequências de cliques;
- estudos de caso longos;
- comparação extensa de pacotes;
- diagnóstico operacional exaustivo;
- interpretação completa de uma pesquisa real.

---

# 2. A divisão não deve ser feita pela dificuldade

Esta regra será muito importante durante a revisão.

Considere três perguntas para cada seção:

| Pergunta | Se a resposta for “sim”, tende a ir para |
|---|---|
| Sem isto, o estudante não compreende o que a técnica é ou como é formulada? | **Núcleo** |
| Isto explica formalmente por que a solução existe, é válida, única, identificável ou possui certa distribuição/propriedade? | **Aprofundamento teórico** |
| Isto orienta uma escolha do analista, avaliação da solução, interpretação, diagnóstico ou uso prático? | **Aprofundamento metodológico e aplicado** |

Há conteúdos que aparecem em duas camadas, exatamente como fizemos em Análise Fatorial.

Exemplo em Análise Fatorial:

```text
Rotação existe e para que serve
→ núcleo

Por que uma transformação ortogonal preserva a estrutura comum
→ aprofundamento teórico

Varimax, quartimax, oblimin etc.
→ aprofundamento metodológico e aplicado
```

Exemplo em ACP:

```text
Na ACP é necessário decidir quantas componentes serão retidas
→ núcleo

Propriedades formais do subespaço principal
→ aprofundamento teórico

Scree plot, Kaiser e outros critérios de retenção
→ aprofundamento metodológico e aplicado
```

Esse padrão deve ser mantido.

---

# 3. Hierarquia das quatro fontes principais

A distribuição das referências deve ser funcional e não mecânica. Não é necessário que os quatro autores apareçam em todos os capítulos.

## 3.1 Johnson & Wichern — espinha dorsal

Adotar **Johnson & Wichern como primeira fonte consultada em praticamente todo capítulo específico de técnica**.

O livro ocupa exatamente a faixa desejada para o material:

- formulação estatística suficientemente rigorosa;
- desenvolvimento matemático;
- passagem população → amostra;
- exemplos;
- interpretação.

### Função predominante

- núcleo: **muito alta**;
- teoria: **alta**;
- metodológico/aplicado: **média**.

Em síntese:

> **Johnson & Wichern deve ser o eixo vertical do capítulo.**

---

## 3.2 Anderson — aprofundamento estatístico e inferencial

Anderson deve entrar quando queremos saber com precisão:

- quais hipóteses estão sendo feitas;
- qual modelo probabilístico sustenta o resultado;
- como aparece a verossimilhança;
- qual é a teoria de raízes e vetores característicos;
- quais resultados inferenciais existem;
- quais são as condições de identificação;
- quais distribuições exatas ou assintóticas estão envolvidas.

### Função predominante

- núcleo: **seletiva**;
- teoria: **muito alta**;
- metodológico/aplicado: **baixa**.

Anderson não deve tornar o núcleo excessivamente inferencial. Deve servir para **dar profundidade e precisão**, principalmente nos aprofundamentos.

---

## 3.3 Eaton — fonte teórica seletiva, não universal

A inclusão de Eaton é especialmente útil quando aparecem:

- espaços vetoriais;
- subespaços;
- projeções;
- produto interno;
- SVD;
- modelos lineares;
- Wishart;
- invariância;
- MANOVA;
- correlações canônicas.

Mas Eaton **não deve ser procurado mecanicamente para todas as técnicas**.

O próprio escopo da obra deixa fora, entre outros temas, discriminação/classificação e análise fatorial.

### Consequências práticas

- MANOVA → Eaton pode ser uma fonte teórica central;
- estruturas geométricas gerais → muito útil;
- AF → não devemos forçá-lo;
- discriminação → não devemos forçá-lo;
- clustering → não é referência central;
- correspondência → não é referência específica da técnica.

### Função predominante

- núcleo: **baixa e seletiva**;
- teoria: **muito alta onde houver aderência**;
- metodológico/aplicado: **praticamente nenhuma**.

---

## 3.4 Hair — eixo metodológico e aplicado

Hair enfatiza:

- planejamento;
- estimação;
- interpretação;
- regras práticas;
- validação;
- decisões analíticas.

Isso coincide quase perfeitamente com o terceiro bloco que estamos criando.

Hair será especialmente útil para:

- adequação dos dados;
- decisões da análise;
- tamanho amostral;
- escolha de procedimentos;
- pressupostos na prática;
- interpretação;
- validação;
- estabilidade;
- diagnóstico;
- significância prática;
- conexão entre resultados estatísticos e problema de pesquisa.

### Função predominante

- núcleo: **seletiva, sobretudo motivação**;
- teoria: **baixa**;
- metodológico/aplicado: **muito alta**.

---

## 3.5 Síntese da arquitetura bibliográfica

```text
Johnson & Wichern
→ estrutura principal

Anderson + Eaton
→ profundidade teórica, conforme a técnica

Hair
→ condução metodológica e aplicada
```

Essa não deve ser uma distribuição por cotas.

> **A função do conteúdo determina sua posição; a fonte não.**

---

# 4. Protocolo de revisão de cada capítulo

## Etapa 1 — Congelar a versão

Antes da revisão:

- guardar a versão original;
- registrar data;
- não editar conteúdo ainda;
- não excluir nada.

A primeira passagem deve ser **estrutural**.

---

## Etapa 2 — Inventariar o capítulo

Antes de decidir qualquer movimentação, produzir um inventário contendo:

| Elemento | Registrar |
|---|---|
| Seções e subseções | título + nível |
| Definições | ID |
| Proposições/teoremas | ID |
| Equações referenciadas | ID |
| Figuras | label |
| Tabelas | label |
| Exemplos | posição |
| Chunks R | label |
| Callouts | tipo/finalidade |
| Referências internas | origem → destino |
| Referências bibliográficas | chave |
| Aprofundamentos já existentes | posição atual |

Isso reduz o risco de perder um bloco ou romper uma referência durante a movimentação.

---

# 5. Etapa 3 — Determinar primeiro o núcleo, não os aprofundamentos

Essa ordem é essencial.

Não começar perguntando:

> “O que podemos retirar do núcleo?”

Começar perguntando:

> **“Qual percurso completo o estudante precisa fazer para entender a técnica na primeira leitura?”**

Para cada capítulo, preencher a ficha abaixo.

## Ficha do núcleo

### Pergunta norteadora

Qual problema a técnica procura resolver?

### Objeto de entrada

Vetor aleatório? Matriz de dados? Tabela de contingência? Grupos conhecidos? Matriz de dissimilaridades?

### Objeto central

\(\boldsymbol{\Sigma}\)? \(\mathbf S\)? \(\mathbf H,\mathbf E\)? Matriz de distâncias? Matriz de perfis?

### Critério/modelo

Maximização? Minimização? Modelo probabilístico? Modelo linear? SVD?

### Solução

Autovetores? Valores singulares? Partição? Regra de decisão?

### Interpretação geométrica

Projeção? Distância? Eixos? Separação? Representação de perfis?

### Formulação populacional/amostral

Existe? É necessária para compreender a técnica?

### Pressupostos definidores

O que pertence à própria formulação?

### Pressupostos inferenciais

O que só se torna necessário para testes ou estimação?

### Limites

O que a técnica não garante?

### Relações

Qual a conexão com técnicas anteriores e posteriores?

Se esses itens estiverem atendidos, temos um **núcleo autossuficiente**.

---

# 6. Etapa 4 — Classificar o restante sem apagar

Depois de fixado o núcleo, cada bloco restante recebe provisoriamente uma das etiquetas:

```text
T = aprofundamento teórico
M = aprofundamento metodológico/aplicado
D = dúvida de classificação
```

O `D` é importante. Não devemos mover um conteúdo para uma categoria inadequada apenas para terminar a revisão.

Para resolver cada `D`, perguntar:

> Ele explica **a natureza matemática/estatística da técnica** ou **uma decisão sobre como conduzi-la**?

---

# 7. Etapa 5 — Criar a arquitetura física do capítulo

O modelo consolidado deverá ser:

```markdown
# Formulação da técnica

[NÚCLEO]

## Aprofundamentos teóricos

::: {.callout-note appearance="simple" icon=false}
## Leitura de aprofundamento

[Texto curto explicando o que esse bloco acrescenta à primeira leitura.]
:::

### ...
### ...
### ...

## Aprofundamentos metodológicos e aplicados

::: {.callout-note appearance="simple" icon=false}
## Leitura de aprofundamento

[Texto curto explicando o que esse bloco acrescenta à condução e interpretação.]
:::

### ...
### ...
### ...

::: {.callout-note appearance="simple" icon=false}
## Correspondência com a implementação utilizada

[Correspondência entre os objetos estudados e o software.]
:::

## Síntese
```

A divisão deve usar **dois grandes blocos de aprofundamento**, como ACP e AF, e não dezenas de callouts individuais.

---

# 8. Etapa 6 — Só movimentar; não reescrever

Na primeira rodada:

- preservar parágrafos;
- preservar equações;
- preservar exemplos;
- preservar figuras;
- preservar IDs;
- preservar chunks;
- preservar citações;
- alterar apenas títulos, níveis hierárquicos e frases de transição estritamente necessárias.

Isso permite separar dois problemas:

```text
Problema A
→ o conteúdo está no lugar certo?

Problema B
→ o conteúdo está escrito da melhor maneira possível?
```

Primeiro resolvemos A.

Depois resolvemos B.

---

# 9. Etapa 7 — Auditoria depois das movimentações

Após cada capítulo, verificar obrigatoriamente:

- nenhum bloco desapareceu;
- nenhum texto foi duplicado acidentalmente;
- IDs continuam únicos;
- referências cruzadas continuam válidas;
- figuras continuam sendo introduzidas antes de aparecer;
- chunks continuam fechados;
- callouts `:::` continuam balanceados;
- equações continuam no contexto correto;
- citações bibliográficas continuam presentes;
- títulos representam corretamente sua relação hierárquica;
- frases como “a seguir”, “posteriormente”, “na próxima seção” continuam verdadeiras;
- o núcleo não referencia como conhecido um conceito que só será definido no aprofundamento;
- a síntese não depende de um aprofundamento para fazer sentido.

Um ponto especialmente importante:

> **Toda movimentação deve ser seguida por uma busca de resíduos da ordem anterior.**

Exemplos:

```text
remissões desatualizadas
frases duplicadas
transições antigas
IDs duplicados
conceitos usados antes de serem definidos
figuras mantidas em dois lugares
parágrafos repetidos
```

---

# 10. Etapa 8 — Segunda revisão, só depois da arquitetura

Somente quando a divisão estiver estável iniciar outra rodada para:

1. corrigir imprecisões;
2. melhorar explicações;
3. eliminar redundâncias reais;
4. harmonizar notação;
5. melhorar figuras;
6. rever referências;
7. acrescentar lacunas;
8. incorporar novos resultados dos livros;
9. criar novos aprofundamentos;
10. eventualmente enxugar o que realmente for repetitivo.

A reorganização deve **facilitar futuras expansões**, e não limitar o capítulo.

---

# 11. Como tratar novas inclusões no futuro

Toda nova inclusão deve, antes de ser escrita, responder:

> **Em qual das três leituras ela é necessária?**

Exemplo em ACP:

```text
Anderson fornece uma teoria assintótica interessante para autovetores.

É necessária para compreender ACP?
→ não

Esclarece propriedades estatísticas profundas?
→ sim

Destino:
Aprofundamentos teóricos
→ Inferência sobre autovalores, autovetores e subespaços
```

Exemplo em AF:

```text
Hair fornece procedimentos de validação por subamostras.

É necessário para compreender o modelo fatorial?
→ não

Orienta a condução e avaliação da solução?
→ sim

Destino:
Aprofundamentos metodológicos e aplicados
→ Estabilidade e validação da solução
```

Esse sistema evita novamente o crescimento desordenado do núcleo.

---

# 12. Aplicação preliminar aos capítulos ainda não reorganizados

## 12.1 Problemas e estruturas das técnicas multivariadas

Este é um capítulo especial. Não é necessário produzir três blocos do mesmo tamanho.

Seu núcleo deve continuar dominante, pois sua função é fornecer o mapa conceitual do Módulo 3.

### Núcleo

- problemas multivariados;
- tipos de dados e objetos;
- dependência × interdependência;
- exploratório × preditivo × inferencial;
- supervisionado × não supervisionado;
- combinações lineares;
- decomposição espectral;
- SVD;
- projeções;
- distâncias;
- modelos lineares;
- variáveis latentes;
- relações gerais entre as técnicas.

### Aprofundamentos teóricos

Pode ser inicialmente pequeno:

- por que técnicas diferentes conduzem à mesma estrutura matemática;
- distinção entre equivalência matemática e equivalência estatística;
- papel de invariância, subespaços e mudança de coordenadas, se futuramente desenvolvidos.

Eaton pode ser útil como fonte de visão geométrica unificadora, sem transformar o capítulo em uma repetição dos fundamentos de espaços vetoriais.

### Aprofundamentos metodológicos e aplicados

- relação problema → tipo de dado → objetivo → família de técnicas;
- fronteiras entre classificações;
- situações em que mais de uma técnica pode ser candidata;
- critérios conceituais para distinguir técnicas semelhantes.

Hair pode contribuir fortemente neste bloco.

---

# 13. Análise de Agrupamentos

## Núcleo

Manter:

- problema de agrupamento;
- representação dos objetos;
- proximidade, distância, dissimilaridade e similaridade;
- efeito da escala em visão conceitual;
- definição de partição;
- centroides;
- dispersão intra e entre grupos;
- formulação de \(k\)-médias;
- significado dos métodos hierárquicos;
- critérios de ligação principais em visão estrutural;
- Ward;
- dendrograma como representação da sequência de fusões;
- diferentes noções de grupo;
- não unicidade e dependência do critério;
- relação conceitual com modelos probabilísticos.

## Aprofundamentos teóricos

Candidatos naturais:

- demonstração de que o centróide minimiza a soma de quadrados;
- decomposição total = intragrupos + entre grupos;
- equivalência entre minimizar dispersão interna e maximizar separação, para \(K\) fixo;
- derivação do incremento de Ward;
- propriedades de existência/não unicidade;
- formulação populacional de quantização, se for acrescentada posteriormente;
- relação formal entre \(k\)-médias e modelos de mistura, se desenvolvida com cuidado.

## Aprofundamentos metodológicos e aplicados

- padronização operacional;
- Gower e dados mistos;
- escolha de \(K\);
- escolha da métrica;
- escolha do método de ligação;
- interpretação do dendrograma;
- sensibilidade à inicialização;
- comparação de soluções;
- estabilidade e validação, futuramente.

### Fontes predominantes

```text
Johnson & Wichern
→ núcleo + teoria

Hair
→ metodológico/aplicado

Anderson e Eaton
→ uso apenas se houver contribuição específica
```

---

# 14. Análise de Correspondência

## Núcleo

- tabela de contingência;
- frequências relativas;
- massas;
- perfis;
- modelo de independência como referência;
- distância qui-quadrado;
- matriz de resíduos padronizados;
- inércia;
- SVD;
- coordenadas principais;
- representação de linhas e colunas;
- dualidade;
- interpretação geométrica;
- relação entre inércia e afastamento da independência;
- relação com ACP e qui-quadrado em nível conceitual;
- limites fundamentais.

## Aprofundamentos teóricos

- reconstrução das diferenças em relação à independência;
- derivação das identidades da inércia;
- relação formal entre inércia total e estatística qui-quadrado;
- relações baricêntricas, quando demonstradas;
- propriedades das diferentes parametrizações/coordenadas;
- formulação probabilística e resultados assintóticos mais detalhados.

## Aprofundamentos metodológicos e aplicados

- contribuições;
- \(\cos^2\);
- escolha de dimensões;
- categorias suplementares;
- leitura do mapa;
- influência de categorias raras;
- cuidados com proximidade entre pontos de tipos diferentes;
- validação ou estabilidade, futuramente.

### Fontes predominantes

```text
Johnson & Wichern
→ núcleo + teoria

Hair
→ metodologia/interpretação

Anderson e Eaton
→ não precisam ser referências específicas da técnica
```

---

# 15. MANOVA

Este tende a ser o capítulo em que a hierarquia bibliográfica funcionará de forma mais clara.

## Núcleo

Devem permanecer:

- problema de comparação de vetores de médias;
- modelo linear multivariado;
- hipótese linear;
- matrizes \(\mathbf H\) e \(\mathbf E\);
- razão de variabilidade em uma combinação linear;
- autovalores generalizados;
- raízes características;
- interpretação geométrica;
- quatro critérios clássicos:
  - Wilks;
  - Pillai;
  - Hotelling–Lawley;
  - Roy;
- significado de cada critério como função das mesmas raízes;
- pressupostos fundamentais;
- relação com ANOVA/modelo linear;
- relação com análise discriminante.

Os quatro critérios devem permanecer no núcleo porque fazem parte da própria formulação da técnica.

## Aprofundamentos teóricos

- teoria Wishart de \(\mathbf H\) e \(\mathbf E\);
- independência das matrizes sob hipóteses clássicas;
- base probabilística dos quatro critérios;
- razão de verossimilhanças;
- distribuição exata e aproximações;
- invariância das raízes;
- forma canônica;
- demonstrações envolvendo o problema generalizado;
- propriedades inferenciais dos critérios.

Aqui **Anderson e Eaton devem ganhar muito peso**.

## Aprofundamentos metodológicos e aplicados

- Box \(M\);
- avaliação prática de homogeneidade;
- consequências do desbalanceamento;
- escolha/interpretação dos critérios;
- avaliação das variáveis dependentes após o teste global;
- contrastes;
- comparações posteriores;
- MANCOVA;
- MANOVA fatorial;
- validação/robustez, conforme futuras inclusões.

### Fontes predominantes

```text
Johnson & Wichern
→ núcleo

Anderson + Eaton
→ teoria

Hair
→ metodologia e aplicação
```

---

# 16. Análise Discriminante

## Núcleo

Manter:

- grupos previamente conhecidos;
- diferença entre discriminação e classificação;
- probabilidades a priori;
- probabilidades posteriores;
- regra de Bayes em sua forma básica;
- classificação normal;
- covariâncias comuns → LDA;
- covariâncias diferentes → QDA;
- regra amostral;
- critério de Fisher;
- dispersão entre e dentro dos grupos;
- autovalores generalizados;
- funções discriminantes;
- interpretação geométrica;
- relação Fisher ↔ classificação normal;
- relação com MANOVA;
- pressupostos e limites.

## Aprofundamentos teóricos

- teoria de decisão com perdas gerais;
- risco;
- derivação completa da regra de Bayes;
- derivação explícita da fronteira quadrática;
- decomposição de covariâncias;
- demonstração do problema de Fisher;
- equivalência Fisher–LDA sob condições apropriadas;
- propriedades probabilísticas do erro de classificação;
- teoria inferencial mais avançada.

Anderson é uma fonte natural para esse bloco.

Eaton não deve ser usado artificialmente aqui.

## Aprofundamentos metodológicos e aplicados

- estimação das probabilidades a priori;
- custos diferenciados em aplicações;
- erro aparente;
- validação cruzada;
- amostra de validação;
- matriz de classificação;
- sensibilidade/especificidade quando pertinentes;
- interpretação de coeficientes;
- cargas discriminantes;
- casos mal classificados;
- avaliação de desempenho em novas observações.

### Fontes predominantes

```text
Johnson & Wichern
→ núcleo e parte da teoria

Anderson
→ teoria probabilística

Hair
→ metodologia, interpretação e validação
```

---

# 17. Regras permanentes derivadas dos capítulos de ACP e AF

## Regra A — o aprofundamento nunca deve corrigir uma lacuna do núcleo

O núcleo precisa funcionar sozinho.

## Regra B — uma noção pode aparecer no núcleo e ser retomada depois

Isso não é duplicação inadequada.

```text
Núcleo
→ diz o que é e por que é necessário.

Aprofundamento teórico
→ explica por que matematicamente é assim.

Aprofundamento metodológico/aplicado
→ explica como utilizar, avaliar ou interpretar.
```

## Regra C — a extensão dos três blocos não precisa ser equilibrada

Exemplos:

```text
MANOVA
→ provavelmente terá muito aprofundamento teórico.

Agrupamentos
→ provavelmente terá bastante aprofundamento metodológico.

Estruturas
→ deverá ter um núcleo proporcionalmente maior.
```

Isso é esperado e correto.

## Regra D — não usar o autor para determinar a posição do conteúdo

Uma passagem de Hair pode eventualmente ser conceitualmente essencial e ficar no núcleo.

Uma passagem de Johnson & Wichern pode ser uma escolha metodológica e ficar no terceiro bloco.

> **A função do conteúdo determina sua posição; a fonte não.**

## Regra E — preservar caminhos para expansão

Cada bloco deve permitir que novas subseções sejam acrescentadas futuramente sem exigir nova reorganização completa do núcleo.

---

# 18. Ficha padrão para cada revisão

Antes de tocar em qualquer arquivo, preencher:

| Item de controle | Decisão |
|---|---|
| Pergunta norteadora do capítulo | |
| Resultado mínimo da primeira leitura | |
| Objeto de entrada | |
| Objeto matemático central | |
| Modelo/função objetivo | |
| Solução matemática | |
| Geometria essencial | |
| Formulação populacional | |
| Formulação amostral | |
| Pressupostos definidores | |
| Pressupostos inferenciais | |
| Limites | |
| Relações com outras técnicas | |
| Seções obrigatórias do núcleo | |
| Candidatos a aprofundamento teórico | |
| Candidatos a aprofundamento metodológico/aplicado | |
| Conteúdos ainda duvidosos | |
| Fonte principal do núcleo | |
| Fontes principais da teoria | |
| Fonte principal da metodologia | |
| Possíveis inclusões futuras | |
| IDs/figuras/chunks que serão movimentados | |
| Referências cruzadas afetadas | |

Essa ficha deve ser preenchida **antes** de começar os blocos `LOCALIZAR → SUBSTITUIR`.

---

# 19. Ordem recomendada para a próxima rodada

Com ACP e AF servindo como capítulos-piloto, a ordem recomendada é:

```text
1. Agrupamentos
2. Correspondência
3. MANOVA
4. Discriminante
5. Estruturas
```

A razão para deixar **Estruturas por último** é que, depois de sabermos exatamente como os cinco capítulos específicos ficaram divididos, podemos voltar ao capítulo inicial e verificar se ele realmente antecipa **o núcleo comum do módulo**, sem antecipar os aprofundamentos.

---

# 20. Síntese do protocolo

A arquitetura geral do Módulo 3 passa a ser:

```text
Núcleo
=
compreender a técnica

Aprofundamento teórico
=
compreender mais profundamente por que ela funciona

Aprofundamento metodológico e aplicado
=
compreender como conduzir, avaliar e interpretar a técnica
```

E a arquitetura bibliográfica geral:

```text
Johnson & Wichern
=
espinha dorsal do núcleo e parte da teoria

Anderson
=
aprofundamento estatístico, probabilístico e inferencial

Eaton
=
aprofundamento geométrico, vetorial, de invariância, Wishart e modelos lineares,
quando a técnica estiver dentro do escopo da obra

Hair
=
planejamento, decisões metodológicas, interpretação, validação e aplicação
```

Com uma ressalva fundamental:

> **Eaton será usado seletivamente, sobretudo onde sua abordagem por espaços vetoriais, modelo linear, Wishart e invariância realmente acrescentar ao capítulo.**

---

# 21. Regra de trabalho para esta etapa

Durante a reorganização dos capítulos restantes:

```text
1. Não enxugar.
2. Não reescrever extensamente.
3. Não excluir.
4. Primeiro classificar.
5. Depois movimentar.
6. Depois auditar resíduos.
7. Só então revisar conteúdo.
8. Apenas após essa revisão avaliar novas inclusões.
```

Esse será o protocolo de referência para a próxima rodada de revisão do Módulo 3.
