# cognitive_search
Passo a passo para utilização do Azuer Cognitive Search

Para utilizar o recursos primeiramente vamos entrar dentro do PORTAL Do AZURE

- Pesquise por AI SEARCH
    ![image](https://github.com/jonathanalbertbh89/cognitive_search/assets/44850467/367eb662-028b-4326-9637-ca1616cb65dc)

- CLique em Create
    ![image](https://github.com/jonathanalbertbh89/cognitive_search/assets/44850467/05af2cb0-d36e-449c-b478-9479c42c037b)

    ![image](https://github.com/jonathanalbertbh89/cognitive_search/assets/44850467/b2e7ca1a-c8dd-4fe7-b50f-e750eb30ce3a)
    **para fins de teste, recomenda-se colocar o plano basic ou free**


- Agora vamos criar um recurso Azure AI Services
  ![image](https://github.com/jonathanalbertbh89/cognitive_search/assets/44850467/ea4556c4-4fb0-4213-8d77-e89b001e7408)

- Agora vamos criar um Storage
    ![image](https://github.com/jonathanalbertbh89/cognitive_search/assets/44850467/2f86ba4e-33fc-4592-990f-1459a3dda4ba)
    **muita atenção na hora de escolher o nome, que precisa ser único de uma forma generalista e a redundância**

    - Após finalização da criação do Storage vá em configuration e habilite o **Allow Blob anonymous access**
      ![image](https://github.com/jonathanalbertbh89/cognitive_search/assets/44850467/e07df389-f882-40a3-bfdf-68bfd59031b8)

   - agora vamos criar um container
     ![image](https://github.com/jonathanalbertbh89/cognitive_search/assets/44850467/6048a3b2-1c45-4092-9e5d-8799e1d7ea65)


   Agora vamos faze o download do arquivo .zip de exemplo da doc
    link https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html
    ![image](https://github.com/jonathanalbertbh89/cognitive_search/assets/44850467/fd66ab8d-0c0c-466a-b842-55df158e2563)

  Extraia os arquivo e faça o upload dentro do Storage 
    ![image](https://github.com/jonathanalbertbh89/cognitive_search/assets/44850467/f5421d3e-ce41-4059-a130-3c84cd28ff36)
    ![image](https://github.com/jonathanalbertbh89/cognitive_search/assets/44850467/5f755db2-6232-47b8-87e7-f1dba49e0d41)


 Seguindo a documentação do link anterior podemos usar o securso de seach para fazer a pesquisa dentro dos srquivos. 
 
