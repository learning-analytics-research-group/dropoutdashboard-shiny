Vídeos:

    https://shiny.rstudio.com/tutorial/written-tutorial/lesson1/
    https://shiny.rstudio.com/articles/shinyapps.html
        
Para deploy:

    https://www.shinyapps.io
    library(rsconnect)
    deployApp()
    
Configurar:

    install.packages('rsconnect')
    library(rsconnect)
    rsconnect::setAccountInfo(name="<ACCOUNT>", token="<TOKEN>", secret="<SECRET>")
