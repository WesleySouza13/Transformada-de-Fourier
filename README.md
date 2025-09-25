# **Demonstração em Python - Transformada Rapida de Fourier (FFT)**

![alt text](image.png)

Jean-Baptiste Joseph Fourier (Auxerre, 21 de março de 1768 — Paris, 16 de maio de 1830) foi um matemático e físico francês, conhecido por iniciar a investigação das séries de Fourier, que posteriormente se desenvolveram na análise de Fourier e na análise harmônica, com aplicações em problemas de transferência de calor e vibrações. A transformada de Fourier e a Lei de Fourier da condução térmica também receberam seus nomes em sua homenagem. Fourier também é geralmente creditado pela descoberta do efeito estufa.[2] -- Wikipedia


Nesse estudo, vamos ver a aplicaçao da Transformada de Fourier em dados temporais. 


# Transformada de Fourier

A transformada de Fourier tem como objetivo decompor sinais ruidosos que variam no domínio do tempo ou do espaço, transformando-os em componentes de frequência.

Suas aplicações são amplamente encontradas em setores como finanças, saúde, engenharia, entre muitos outros, devido à sua capacidade de revelar padrões que estão escondidos em meio a grandes volumes de dados e ruído.

Por exemplo, ao analisar os picos de uma série temporal de um ativo financeiro, o grande volume e a complexidade dos dados tornam a tarefa difícil. É nesse contexto que a transformada de Fourier se torna uma ferramenta poderosa, permitindo identificar e interpretar esses padrões de forma clara.


A Definição matemática é dada por: 

![alt text](image-1.png)

Aqui, tratamos a série como uma função de decaimento rápido, ou seja, ela tende rapidamente a zero a partir de valores muito grandes positivos ou negativos.


Recomendação para estudo: 

Séries de Fourier - Professor Possani: [text](https://www.youtube.com/watch?v=Wp0jZeBQfxI)

Transformadas de Laplace e de Fourier - Professor Possani: [text](https://www.youtube.com/watch?v=vncQ5m3dlH8)

Aplicações da Transformada de Fourier - Professor Possani: [text](https://www.youtube.com/watch?v=xb5wdbdztGE)



**No arquivo fft.ipynb eu deixei um exemplo de aplicação do método, utilizando dados de um ativo financeiro da IBM**
