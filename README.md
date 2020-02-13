**Desenvolvido por**: Pedro Rafael D. Marinho </br>
**E-mail**: pedro.rafael.marinho@gmail.com

# Apresentação construída em **xaringan**

O pacote pacote [**xaringan**](https://github.com/yihui/xaringan) está disponível no [**CRAN**](https://cran.r-project.org/web/packages/available_packages_by_date.html) da linguagem [**R**](https://www.r-project.org/) e é útil para a criação de apresentações com o [**remark.js**](https://remarkjs.com/#1) utilizando o [**RMarkdown**](https://rmarkdown.rstudio.com/). 

## Visualizando

Visualize a apresentação clicando [**aqui**](https://prdm0.github.io/apresentacao-laranja/). 

**Dica**: Aperte **F11** para ampliar a apresentação e utilize as teclas as setas direcionais do seu teclado para navegar entre os frames. Utilizando a tecla **p** você entrará no modo apresentador, modo este apenas visível na primeira tela que é utilizada pelo apresentador.

## O que preciso para começar a fazer minhas apresentações utilizando **xaringan**?

Para começar a produzir suas apresentações utilizando a biblioteca [**xaringan**](https://github.com/yihui/xaringan) é necessário conhecer um pouco de [**RMarkdown**](https://rmarkdown.rstudio.com/). 

Um bom material de [**RMarkdown**](https://rmarkdown.rstudio.com/) é intitulado [**R Markdown: The Definitive Guide**](https://bookdown.org/yihui/rmarkdown/). Nesse material você encontrará o que necessita para conhecer de forma safisfatória a sintaxe de [**RMarkdown**](https://rmarkdown.rstudio.com/).

Após entender o [**RMarkdown**](https://rmarkdown.rstudio.com/), ficará fácil compreender o conteúdo do arquivo **index.Rmd**. É o arquivo **index.Rmd** que contém todo o código dessa apresentação. O arquivo **index.Rmd** com as imagens e os arquivos com extensão `.css` serão necessários para a reprodução dessa apresentação. Além disso você necessita instalar algumas bibliotecas.

**Para rodar esse exemplo, preciso instalar quais bibliotecas?**

Muito embora essas bibliotecas não sejam essenciais para construir apresentações com [**xaringan**](https://github.com/yihui/xaringan), você necessita instalá-las, uma vez que a apresentação faz uso de recursos como mapas, ícones e inserção de vídeos. Para instalar todas as bibliotecas necessárias, corra o código que segue:

```r
# Pacotes necessários
install.packages(
  c("devtools",
    "leaflet",
    "rmarkdown",
    "xaringan"
    "icon",
    "vembedr"
  )
)
# Gerador de temas:
devtools::install_github(repo = "gadenbuie/xaringanthemer")
```
A biblioteca [**xaringanthemer**](https://github.com/gadenbuie/xaringanthemer) é útil para que possamos gerar novos temas para as apresentações sem utilizar muito a linguagem [**CSS**](https://pt.wikipedia.org/wiki/Cascading_Style_Sheets). Com essa biblioteca, você facilmente conseguirá modificar o tema disponibilizado nessa apresentação. Clique [**aqui**](https://pkg.garrickadenbuie.com/xaringanthemer/articles/singles/themes.html) para visualizar alguns temas construídos utilizando o pacote [**xaringanthemer**](https://github.com/gadenbuie/xaringanthemer).

Alguns temas adicionais que poderá ajudar a você entender o **xarigan** ou mesmo reproduzir o tema para uma apresentação podem ser visualizados abaixo

+ **Tema Verde**: ver o tema clicando [**aqui**](https://prdm0.github.io/apresentacao-verde/);
+ **Tema Preto**: ver o tema clicando [**aqui**](https://prdm0.github.io/apresentacao-preta/).