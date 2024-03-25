# Sobre a linguagem C   

A linguagem C foi criada para incentivar a programação multiplataforma, ou seja, programas escritos em C podem ser compilados em diferentes tipos de plataformas e sistemas operacionais, com pequenas alterações. 

Além disso, ela foi desenvolvida com intuito de fornecer uma programação de alto nível, buscando uma proximidade maior com a linguagem humana em relação com o código da máquina, facilitando a compreensão e a manutenção do código. Antes dela, a linguagem mais comum era o Assembly, uma linguagem de baixo nível e difícil de trabalhar.  

A grande vantagem da linguagem C é que ela é estruturalmente simples e pode ser usada em muito sistemas operacionais diferentes, tornando altamente portátil, mas o seu grande diferencial é a rapidez na execução de programas, ideal para o desenvolvimento de softwares, que requer um desempenho otimizado. Muito usada em banco de dados e em uma variedade de sistemas, como os financeiros, governamentais, mídia, saúde, educação. 

Ela é considerada uma das linguagens de programação mais poderosas e é usada em quase todos os grandes sistemas operacionais, como Linux, Windows, MacOS. 

<br>
<br>

## Influência da linguagem:

A linguagem C foi influenciada por diversas linguagens desenvolvidas depois dela, de forma direta e indiretamente, como por exemplo: JAVA, C#, PYTHON, PHP. Provavelmente, a influência mais marcante da linguagem C foi a sua sintática, já que algumas linguagem como Java, PHP e Perl, tem a mesma sintaxe. Nas figuras abaixo e possível ver a evolução da linguagem C e de sua influência nos desenvolvimentos de outras linguagens: 

<div align="center"> 

  ![Captura de tela 2024-03-25 143229](https://github.com/pedro-CL/Desmistificar-a-linguagem-C/assets/82902852/94e91168-91d3-4851-b18a-5796994255e2)
  ![Captura de tela 2024-03-25 143525](https://github.com/pedro-CL/Desmistificar-a-linguagem-C/assets/82902852/df0f918f-058c-4bcc-982c-216d0d9cb53b)
  
</div>

<br>
<br>
<br>

# Esqueleto de um programa em C: 

Todo programa escrito em linguagem C que vier a ser desenvolvido deve possuir o seguinte esqueleto: 
<div align="center"> 
  
![Esqueleto do programa ](https://github.com/pedro-CL/Desmistificar-a-linguagem-C/assets/82902852/54a21c83-a920-4c60-9a8d-7b7c7da2dbb6)

</div>

### Declaração global (#include): 

Essas declarações fazem com que o programa reconheça as funções importantes que vão ser usado. Por exemplo, quando você escreve #include<stdio.h>, está dizendo ao programa incluir as definições que está na biblioteca `<stdio.h>`, que incluem funções, como `printf()`. 

### Início do programa(‘main’): 

A função `main()` serve como o ponto de partida para a execução do programa. Em geral, é dentro dela que você escreve o seu código que deseja que seu programa execute. 

### Return 0: 

No final da função `main()` é encontrado uma instrução `return 0;`. Isso é um indicador, ele diz ao sistema que o programa foi executado com sucesso. Se tiver algum problema na execução, o programa retorna um valor diferente de 0 para indicar que algo deu errado. 

<br>
<br>

Para você entender melhor como a funciona, imagine que você é um escritor, certo? O `#include` é como sua coleção de dicionários e livros de referência. Quando você as abre, encontra todas as palavras e frases que precisa para escrever o seu livro. 

Agora, a `main()` é como o papel em branco que você usa para escrever sua história. É dentro dela que você escreve suas ideias e histórias. 

Mais para a frente vamos ver as funções que é como um personagem. Que não são necessários estar dentro da `main()`, eles são como guias que ajudam a organizar a história. 











