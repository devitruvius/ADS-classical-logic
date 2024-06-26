# Conceitos de Lógica Clássica

## Objetivo

Este repositório contém uma série de questões de lógica clássica resolvidas, desenvolvidas como parte das atividades da disciplina de Introdução à Lógica de Computação do curso de Análise e Desenvolvimento de Sistemas (ADS) da Universidade Federal do Cariri (UFCA). Neste repositório, cada questão é acompanhada por exemplos práticos implementados em Python. Esses exemplos ilustram a aplicação dos conceitos de lógica clássica em cenários computacionais, proporcionando uma compreensão mais profunda e prática dos fundamentos lógicos abordados.

## Estrutura do Repositório

O conteúdo está organizado em tópicos correspondentes a cada conjunto de questões. Cada tópico inclui as questões específicas resolvidas para aquela atividade. A estrutura do repositório foi pensada para facilitar a navegação e revisão das questões, proporcionando uma experiência intuitiva aos usuários.

## Questionário

1. **Como um silogismo é estruturado e qual sua aplicação na lógica?**

   ```python
   def silogismo(premissa_maior, premissa_menor, termo_conclusao):
     """
     Função que verifica a validade de um silogismo.
   
     Argumentos:
       premissa_maior (str): A premissa maior do silogismo.
       premissa_menor (str): A premissa menor do silogismo.
       termo_conclusao (str): O termo de conclusão do silogismo.
   
     Retorna:
       bool: True se o silogismo for válido, False caso contrário.
     """
   
     if termo_conclusao not in premissa_maior:
       return False
   
     if termo_conclusao not in premissa_menor:
       return False
   
     return True
   
   # Exemplo de uso
   premissa_maior = "Todos os mortais são vulneráveis a doenças."
   premissa_menor = "Sócrates é mortal."
   termo_conclusao = "Sócrates é vulnerável a doenças."
   
   if silogismo(premissa_maior, premissa_menor, termo_conclusao):
     print("Silogismo válido!")
   else:
     print("Silogismo inválido!")
<hr>

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
<hr>

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
<hr>

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
<hr>

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
<hr>
  
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
<hr>
  
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
<hr>

8. **Como podemos definir a inferência indutiva?**

   ```python
   # Teste de Inferência Indutiva
   
   observacoes = [2, 4, 6, 8, 10]
   
   # Inferência: Todos os números observados são pares, portanto, por indução, o próximo número também será par
   proximo_numero = 12
   
   # Imprime a inferência
   print("O próximo número provavelmente será par:", proximo_numero)
<hr>

9. **Como podemos definir a lógica formal?**

   ```python
   # Validação da Lógica Formal
   
   premissa1 = True
   premissa2 = True
   
   # Conclusão válida pela lógica formal
   if premissa1 and premissa2:
       conclusao = True
   else:
       conclusao = False
   
   # Imprime a conclusão
   print("A conclusão é válida pela lógica formal?", conclusao)
<hr>

10. **Qual é a relação entre silogismo e falácia na estrutura argumentativa?**

    ```python
    # Teste de Validade Silogística
    
    # Silogismo válido, premissas verdadeiras
    premissa1 = True
    premissa2 = True
   
    if premissa1 and premissa2:
       conclusao = True
    else:
       conclusao = False
   
    print("Silogismo válido:", conclusao)
   
    # Falácia, premissas falsas
    premissa1 = False
    premissa2 = False
   
    if premissa1 and premissa2:
       conclusao = True
    else:
       conclusao = False
   
    print("Falácia:", conclusao)

## Navegação
* **Questionário 1: Lógica Clássica**
   - [Repositório do Questionário 1](https://github.com/devitruvius/ADS-Logica-Classica)

* **Questionário 2: Lógica Proposicional**
   - [Repositório do Questionário 2]()

* **Questionário 3: Consequências Lógicas e Argumentos**
   - [Repositório do Questionário 3]()

* **Questionário 4: Lógica de Predicados**
   - [Repositório do Questionário 4]()

* **Questionário 5: Lógica de Prolog**
   - [Repositório do Questionário 5]()

* **Repositório Pai: Lógica Computacional**
   - [Lógica Computacional](https://github.com/devitruvius/ADS-logica-computacional/)

## Licença

Este repositório está licenciado sob a licença [MIT](https://choosealicense.com/licenses/mit/).
