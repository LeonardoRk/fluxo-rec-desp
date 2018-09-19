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
Para instalar algum pacote no RStudio, vá no terminal da ferramenta e digite:  
```
install.packages(<nome do pacote>)
```  

Na console da própria ferramenta digite:  
- ReadXL
```  
install.packages("readxl")
```  
  
Após terminar a instalação do **readxl**, instale o **tidyverse** com o seguinte comando:  
  
- Tidyverse    
  
Em caso de não ter os pacotes abaixo, instale-os no **terminal**, não no **console**:
```
sudo yum install libxml2-devel  
```   

```
sudo yum install openssl-devel  
```    

```   
sudo yum install libcurl-devel
```    

Volte à **console** e digite:  

```
install.packages("tidyverse")
```    
    
- Plotyly  
```
install.packages("plotly")
```  
  
Após todas as dependências instaladas com sucesso, clique em **Session** e
**Restart R**. Feito isso rode o projeto novamente. [Como rodar o projeto](https://github.com/LeonardoRk/fluxo-rec-desp/blob/configuracao_rstudio/docs/gcs.md#como-rodar-o-projeto)
