# Como instalar o R   
## Fedora  
```  
sudo yum install -y R  
```  
  
# Como instalar IDE RStudio    
  
Faça download no link:https://www.rstudio.com/products/rstudio/download/  
Escolha de acordo com a sua distribuição e o pacote que achar mais adequado.  

## Fedora .rpm 

Abra o local do Download do arquivo, com 2 cliques abre o arquivo e clique em instalar. Aguarde até que a instalação termine e a IDE estará instalada.   
  
# Como rodar o projeto
Abra o RStudio, clique em **File** e em seguida **Open file**.  
Selecione o arquivo chamado fluxo-rec-desp.Rmd e clique em abrir para que o arquivo seja carregado no Source do RStudio.  
  
Após concluir o passo anterior, clique em **Run** indicado com uma setinha verde e selecione a opção **Run all**.  
  
Provavelmente faltarão alguma bibliotecas para serem instaladas.  
  
    
# Instalando dependências  
Na console da própria ferramenta digite:  
```  
install.packages("readxl")
```  
  
Após terminar a instalação do **readxl**, instale o **tidyverse** com o seguinte comando:  
```
install.packages("tidyverse")
```  
  
É possível que faltem alguns pacotes para serem instalados, como por exemplo 
