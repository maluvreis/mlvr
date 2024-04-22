# Desenvolvimento e Avaliação de uma Ferramenta de Inteligência Artificial para Laudos de Exames de Ultrassonografia de Tireoide: Aplicação do TI-RADS para a Classificação de Nódulos #

## Instruções ##

[Introdução ](https://github.com/maluvreis/mlvr/edit/main/Project/Revis%C3%A3o_sistem%C3%A1tica.md#1-introdu%C3%A7%C3%A3o)

[Metodologia](https://github.com/maluvreis/mlvr/edit/main/Project/Revis%C3%A3o_sistem%C3%A1tica.md#4-metodologia) 

[Discussão](https://github.com/maluvreis/mlvr/edit/main/Project/Revis%C3%A3o_sistem%C3%A1tica.md#5-discuss%C3%A3o) 

[Conclusão](https://github.com/maluvreis/mlvr/edit/main/Project/Revis%C3%A3o_sistem%C3%A1tica.md#6-conclus%C3%A3o) 

[Referências ](https://github.com/maluvreis/mlvr/edit/main/Project/Revis%C3%A3o_sistem%C3%A1tica.md#7-refer%C3%AAncias)

## 1. Introdução ##

 O diagnóstico precoce e preciso de nódulos tireoidianos é fundamental devido à sua alta prevalência na população e à possibilidade de malignidade. Segundo Paulino et al. (2020) Nódulos tireoidianos são achados comuns em exames de imagem, e embora a maioria seja benigna, a identificação de nódulos malignos é crucial para iniciar o tratamento adequado o mais cedo possível, melhorando assim o prognóstico e a qualidade de vida do paciente. Além disso, um diagnóstico preciso permite evitar procedimentos invasivos desnecessários em pacientes com nódulos benignos, proporcionando uma abordagem terapêutica mais personalizada e eficaz.                   Conforme citam Chamberlaim et al (2023) e Lobo (2017) em suas publicações, o uso de ferramentas de inteligência artificial (IA) na medicina diagnóstica tem crescido significativamente. Essas ferramentas processam grandes quantidades de dados médicos, como imagens de exames, para auxiliar na interpretação e diagnóstico de doenças. Com algoritmos cada vez mais avançados, a IA pode identificar padrões e anomalias, proporcionando diagnósticos mais precisos e rápidos. Essa tecnologia está se tornando essencial para melhorar a eficiência e a precisão dos diagnósticos médicos.
    Esta revisão sistemática demostra grande importância para fundamentar a pesquisa. Ela oferece uma compreensão do estado atual da literatura científica, identificando lacunas de conhecimento e direcionando a pesquisa de forma precisa. Esta revisão será a base teórica para o trabalho, gerando novos conhecimentos nessa área em rápida evolução da medicina diagnóstica.
     

## 2. Metodologia ##

 ### 2.1. Definição dos critérios de inclusão e exclusão dos estudos.
 
**Critérios de inclusão:**
1. Estudos que abordem o desenvolvimento ou avaliação de ferramentas de inteligência artificial (IA) para laudos de ultrassonografia de tireoide.
2. Artigos que usem o TI-RADS (Thyroid Imaging Reporting and Data System) para classificação de nódulos.
3. Artigos mais relacionados a produção de laudos.
4. Pesquisas que envolvam a aplicação de técnicas de IA para a detecção, classificação, ou prognóstico de nódulos tireoidianos.
5. Estudos publicados em inglês, espanhol ou português.
6. Artigos publicados nos últimos 5 anos para garantir relevância e atualidade.

**Critérios de exclusão:**
1. Estudos que não se relacionam diretamente com o desenvolvimento ou avaliação de ferramentas de IA para laudos de ultrassonografia de tireoide.
2. Artigos que não utilizem o TI-RADS para classificação de nódulos.
3. Pesquisas que não envolvam a aplicação de técnicas de IA na análise de exames de ultrassonografia de tireoide.
4. Estudos publicados em idiomas diferentes dos especificados nos critérios de inclusão.
5. Artigos desatualizados ou sem revisão por pares.
6. Estudos com amostras pequenas ou metodologias inadequadas que comprometam a qualidade dos resultados.


### 2.2 Estratégia de busca em bases de dados 

 As bases escolhidas foram PubMed, Scielo, Web of Science e Google Scholar, esta escolha está justificada pela ampla cobertura e reputação consolidada. Essas plataformas são reconhecidas por indexar uma vasta gama de literatura científica, incluindo revistas de alto impacto e artigos revisados por pares, tornando-as fontes confiáveis de informação. A busca se concentra em termos-chave relacionados à produção de laudos de imagens de ultrassonografia de tireoide, como ultrassonografia de tireoide, inteligência artificial, TI-RADS e classificação de nódulos. Esses termos são adaptados conforme necessário para cada base de dados específica e seus idiomas, garantindo uma busca abrangente e precisa. O objetivo é identificar estudos relevantes que abordem o desenvolvimento e avaliação de ferramentas de IA para a produção de laudos de ultrassonografia de tireoide, com foco na aplicação do TI-RADS para a classificação de nódulos. Esses estudos serão fundamentais para embasar tanto a revisão sistemática quanto a pesquisa de mestrado, fornecendo uma base sólida de evidências para o trabalho proposto.
Conforme descrito nas notas de aula de Oliveira (2019), foram seguidas as seguintes estratégias:

 **PubMed**:
   - A busca no PubMed foi fundamental devido à sua vasta cobertura de literatura médica, incluindo revistas científicas renomadas e artigos revisados por pares.
   - A estratégia de busca na PubMed envolveu termos relacionados à ultrassonografia de tireoide e seus laudos, inteligência artificial, TI-RADS e classificação de nódulos.
 

 **Scielo**:
   - Scielo é uma base de dados que inclui uma grande quantidade de literatura científica.
   - A estratégia de busca foi seguir os mesmos termos usados na PubMed, com ajustes para termos equivalentes em inglês ou português, quando necessário.
 

 **Web of Science**:
   - Web of Science é uma plataforma abrangente que indexa uma grande variedade de revistas científicas, permitindo uma busca detalhada.
   - A estratégia de busca na Web of Science foi semelhante à utilizada na PubMed, com a vantagem da possibilidade de acessar diferentes revistas e conferências.
   

4. **Google Scholar**:
   - Google Scholar é útil para encontrar artigos em uma ampla gama de fontes, incluindo teses, dissertações e artigos de acesso aberto.
   - A busca no Google Scholar foi mais genérica, utilizando os termos de busca principais, mas, em alguns momentos exigiu filtragem adicional de resultados.

A estratégia de busca foi relacionada ao trabalho através da seleção de termos e palavras-chave relevantes, como "ultrassonografia de tireoide", "Laudos de tireoide", "inteligência artificial", "TI-RADS","Laudos TI-RADS", "classificação de nódulos", entre outros. Esses termos foram combinados logicamente com operadores booleanos (AND, OR) para refletir o escopo da pesquisa. Por exemplo, uma busca poderia incluir os termos "ultrassonografia de tireoide AND inteligência artificial AND TI-RADS".

### 2.3 Desenvolvimento de Ferramentas de IA para Laudos de Ultrassonografia de Tireoide

  **2.3.1 Descrição das técnicas de inteligência artificial utilizadas nos estudos selecionados.**
    Os estudos relacionados ao desenvolvimento e avaliação de ferramentas de inteligência artificial (IA) para laudos de exames de ultrassonografia de tireoide, com aplicação do TI-RADS para classificação de nódulos, frequentemente utilizam técnicas avançadas de processamento de linguagem natural (PLN). O PLN é uma área da IA que permite aos sistemas computacionais entender, interpretar e gerar linguagem humana de forma semelhante à forma como os seres humanos a entendem.

Aprendizado de Máquina (Machine Learning) e Redes Neurais: Essas técnicas são amplamente empregadas nos estudos de IA relacionados a laudos de ultrassonografia de tireoide. Algoritmos de aprendizado de máquina, como redes neurais convolucionais (CNNs), são treinados com grandes conjuntos de dados de imagens de ultrassonografia para aprender padrões que possam identificar e classificar nódulos tireoidianos com base em características específicas, como forma, textura e ecoestrutura (KIM et al.,2021).
Processamento de Imagens: Além do PLN, o processamento de imagens é uma parte essencial desses estudos. Técnicas como segmentação de imagem e extração de características são utilizadas para identificar regiões de interesse nos exames de ultrassonografia e extrair informações relevantes sobre os nódulos.
Extração de Características: O PLN é usado para extrair características relevantes dos relatórios de ultrassonografia. Os relatórios são analisados para identificar termos-chave, como tamanho, forma, ecogenicidade e margens do nódulo, que são importantes para a classificação de acordo com o TI-RADS.
Modelos de Linguagem e Processamento de Texto: Modelos de linguagem, como o BERT (Bidirectional Encoder Representations from Transformers), são utilizados para compreender o texto dos relatórios de ultrassonografia e interpretar informações relevantes sobre os nódulos. O processamento de texto é empregado para traduzir os relatórios em dados estruturados que possam ser usados pelos algoritmos de classificação.
Essas técnicas de inteligência artificial, principalmente no contexto do processamento de linguagem natural, são cruciais para o desenvolvimento de ferramentas eficazes de laudos de ultrassonografia de tireoide, proporcionando uma análise mais precisa e automatizada dos nódulos e contribuindo para uma medicina diagnóstica mais avançada e eficiente.

## 3. Discussão   ##


## 4. Conclusão  ##


## 5. Referências ##

PAULINO, J. P. G. et al. Importância da ultrassonografia nas doenças nodulares tireoidianas do Ambulatório de Endocrinologia da SCMRP. Revista Interdisciplinar de Saúde e Educação, v. 1, n. 2, p. 227–248, 19 dez. 2020.

CHAMBERLAIM, A. et al. Inteligência Artificial (IA) e suas aplicações em exames de imagem: uma nova era para diagnósticos na área da saúde. Cuadernos de Educación y Desarrollo, v. 15, n. 12, p. 17605–17624, 29 dez. 2023.

LOBO, L. C. Inteligência Artificial e Medicina. Revista Brasileira de Educação Médica, v. 41, n. 2, p. 185–193, jun. 2017.

OLIVEIRA, M.C. Como encontrar e ler um Artigo Ciêntífico. Universidade Federal de Alagoas, 2019.

KIM, G. R. et al. Convolutional Neural Network to Stratify the Malignancy Risk of Thyroid Nodules: Diagnostic Performance Compared with the American College of Radiology Thyroid Imaging Reporting and Data System Implemented by Experienced Radiologists. American Journal of Neuroradiology, v. 42, n. 8, p. 1513–1519, 13 maio 2021.

‌

