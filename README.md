# Data_Science_Manutencao

# Departamento de Manutenção

-   **IA e ML estão transformando a indústria, principalmente os  departamentos de produção e manutenção**
-   **De acordo com o relatório do World Economic Forum, essas  tecncologias terão grande impacto na indústria 4.0.**
    -   Departamento de manutenção
    -   Departamento de produção
    -   Cadeia de suprimentos

-   **Técnicas de Deep Learning tem provado serem eficientes para  detecção e localização de defeitos em imagens.**
-   **LandingAI: https://landing.ai/defect-detection/.**
Referência: "https://www.cio.com/article/3302797/how-ai-is-revolutionizing-  manufacturing.html".
**CLASSIFICAÇÃO E SEGMENTAÇÃO**
![Classificação e Segmentação](https://github.com/callacius/Data_Science_Manutencao/blob/main/images/01.png?raw=true)
**MASK (MÁSCARA)**
-   **O objetivo da segmentação de imagens é “entender” a imagem pixel a pixel,  sendo que cada pixel é associado a uma classe**
-   **A saída da segmentação produz uma nova imagem, que é chamada de  “máscara da imagem”.**
-   **Máscaras podem ser representadas associando valores de pixels para  coordenadas.**
-   **Para representar máscaras aplicamos o processo de “flattening” – 1-D array.**
-   **Exemplo: [255, 0, 0, 255], [1, 0, 0, 1].**
![Mask](https://github.com/callacius/Data_Science_Manutencao/blob/main/images/02.png?raw=true)
**RUN LENGTH ENCODING (RLE)**
-   **Técnica para compressão de dados que armazena sequências que contém  dados consecutivos (combinação em um só valor).**
-   **Considerando que temos uma imagem com texto preto em fundo branco.**
**        WWWWWWWWWWWWBWWWWWWWWWW** 
**        WWBBBWWWWWWWWWWWWWWWWWWW**
**        WWWWWBWWWWWWWWWWWWWW**
-   **Run-length encoding (RLE):**
**        12W1B12W3B24W1B14W**
**RESUNET**
-   **Combina a arquitetura UNet com blocos residuais (skip connection) para reduzir o problema do  gradiente desaparecendo (vanish gradient problem)**
-   **Consiste em três partes:**
    -   (1) Encoder or contracting path
    -   (2) Bottleneck
    -   (3) Decoder or expansive path
![Resunet](https://github.com/callacius/Data_Science_Manutencao/blob/main/images/03.png?raw=true)
**ARQUITETURA**
![Arquitetura](https://github.com/callacius/Data_Science_Manutencao/blob/main/images/04.png?raw=true)

Fonte: **https://www.udemy.com/course/ciencia-de-dados-para-empresas-e-negocios**
