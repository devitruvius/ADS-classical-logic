# Conceitos de Lógica Clássica

## Objetivo

Este repositório contém questões de lógica clássica resolvidas como parte das atividades relacionadas à disciplina de Introdução à Lógica de Computação, do curso Análise e Desenvolvimento de Sistemas (ADS) pela Universidade Federal do Cariri (UFCA). As questões foram elaboradas para explorar e consolidar os conceitos fundamentais da lógica clássica e sua aplicação em problemas práticos.

## Estrutura do Repositório

O conteúdo está organizado em tópicos correspondentes a cada conjunto de questões. Cada tópico inclui as questões específicas resolvidas para aquela atividade. A estrutura do repositório foi pensada para facilitar a navegação e revisão das questões, proporcionando uma experiência intuitiva aos usuários.

## Questionário

1. **Como um silogismo é estruturado e qual sua aplicação na lógica?**

   ```python
   # Silogismo de Sócrates
   
   premissa1 = "Sócrates é um homem"
   premissa2 = "Todos os homens são mortais"
   
   # Conclusão
   if premissa1 and premissa2:
       conclusao = "Sócrates é mortal"
   else:
       conclusao = "Não é possível determinar se Sócrates é mortal"
   
   # Imprime a conclusão
   print(conclusao)

2. **O que afirma o princípio da identidade na lógica clássica?**

   ```python
   # Teste do Princípio da Identidade
   
   item = "maçã"
   
   # Verifica se o item é igual a si mesmo
   if item == item:
       principio_da_identidade = True
   else:
       principio_da_identidade = False
   
   # Imprime o resultado
   print("O princípio da identidade é válido para", item, "?", principio_da_identidade)

3. **Qual é o principal problema da falácia do apelo à ignorância?**

   ```python
   # Teste da Falácia
   
   afirmacao = "Não há evidências de que os alienígenas não existam."
   
   # Verificação da falácia do apelo à ignorância
   if not afirmacao:
       falacia = "Afirmativa falaciosa"
   else:
       falacia = "Afirmativa não falaciosa"
   
   # Imprime o resultado
   print(falacia)

4. **Qual é o significado do princípio da não contradição na lógica clássica?**

   ```python
   # Teste do Princípio da Não-Contradição
   
   afirmacao1 = True
   afirmacao2 = False
   
   # Verificação do princípio da não contradição
   if afirmacao1 and afirmacao2:
       nao_contradicao = "As afirmações são contraditórias"
   else:
       nao_contradicao = "As afirmações não são contraditórias"
   
   # Imprime o resultado
   print(nao_contradicao)

5. **O que caracteriza a falácia do espantalho?**

   ```python
   # Teste da Falácia do Espantalho
   
   argumento = "Devemos investir em medidas para proteger o meio ambiente."
   argumento_distorcido = "Pessoas que defendem o meio ambiente querem parar todo o desenvolvimento econômico."
   
   # Verificação da falácia do espantalho
   if argumento_distorcido:
       falacia = "Falácia do espantalho presente"
   else:
       falacia = "Não há falácia do espantalho presente"
   
   # Imprime o resultado
   print(falacia)
  
6. **Como o princípio do terceiro excluído é aplicado na lógica clássica?**

   ```python
   # Teste do Princípio do Terceiro Excluído
   
   proposicao = True
   
   # Verificação do princípio do terceiro excluído
   if proposicao or not proposicao:
       terceiro_excluido = "O princípio do terceiro excluído se aplica"
   else:
       terceiro_excluido = "O princípio do terceiro excluído não se aplica"
   
   # Imprime o resultado
   print(terceiro_excluido)
  
7. **Qual é a principal preocupação ao identificar a falácia do apelo à autoridade?**

   ```python
   # Teste da Falácia do Apelo à Autoridade
   
   autoridade = "Médico renomado"
   
   # Verificação da falácia do apelo à autoridade
   if autoridade == "Médico renomado":
       falacia = "A cloroquina é eficaz no tratamento da COVID-19 porque um médico renomado disse."
   else:
       falacia = "A cloroquina não é eficaz no tratamento da COVID-19 apenas porque um médico renomado disse."
   
   # Imprime o resultado
   print(falacia)

8. **Como podemos definir a inferência indutiva?**

   ```python

9. **Como podemos definir a lógica formal?**

   ```python

10. **Qual é a relação entre silogismo e falácia na estrutura argumentativa?**

    ```python

11. **O que caracteriza uma falácia em um argumento?**

    ```python

12. **Como a proposição se diferencia de premissa em um argumento lógico?**

    ```python
