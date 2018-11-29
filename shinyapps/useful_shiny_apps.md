
# List of usefull Shiny app

## How to run a shiny app

### 1. Web interface. 

Some shiny apps are hosted online. Just go the webpage and enjoy!

### 2. Run local in R

When an app is not hosted on a web server, but is in a github repo, just run these command in your R environment:

    library(shiny)
    shiny::runGitHub("ACCOUNT/REPO", "REPO") 
    
For instance, to run this shiny app: [https://github.com/jhmatthes/mammal-traits](), just run these lines:
    
    library(shiny)
    shiny::runGitHub("jhmatthes/mammal-traits", "jhmatthes") 


## Plants

- Root architecture model (CRootBox): https://plantmodelling.shinyapps.io/shinyRootBox/
- Water flow in root cross section (MECHA): https://plantmodelling.shinyapps.io/mecha/
- Full plant model, with water, carbon and nitrogen (PlaNet): https://plantmodelling.shinyapps.io/PlaNet_Maize/
- Farquhar photosynthesis model: http://biocycle.atmos.colostate.edu/shiny/photosynthesis/

## Animals:

- Mammal dataset: https://github.com/jhmatthes/mammal-traits


## Genetics :

- Population genetics: https://github.com/jhmatthes/evolution-populations

## Data analysis:

- Mutlivariate analysis: http://mvapp.kaust.edu.sa/MVApp/
- Interactive Manhattan plots: https://chikudaisei.shinyapps.io/shinyaim/

## Others :

- Computational tools to analyse wter flow in plants: https://plantmodelling.shinyapps.io/water_network/
- Bingo generator: https://plantmodelling.shinyapps.io/phenome_bingo/
- Science podcast browser: https://plantmodelling.shinyapps.io/science_podcast
- h-index generator: https://github.com/guillaumelobet/h-index-simulator

