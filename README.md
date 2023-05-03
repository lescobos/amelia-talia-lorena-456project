# Welcome to our Projects in Data Science Github Repository! 

This project was completed by Amelia Renner, Talia Chait, and Lorean Escobosa-Alcantar. 

For our topic, we were looking into how ocean health changes due to climate related temperature increases? In order to best answer this question, we structured our project in the form of three case studies all of which tell a crucial part of the story. The three case studies are coral bleaching in Australia, ocean chemistry in California, USA, and fish populations in the Mediterranean Sea. In order to make this more widely accesible, we created a quarto website and deployed it through github. Check out this link to learn more about our project and read about the three case studies: https://lescobos.github.io/amelia-talia-lorena-456project/ 

**Data dependencies:** Each case study has different data that went along with the analysis and visualizations. To view the datasets used, click on the "oceanhealth_website" folder and then click on the "Data" folder. In that data folder, there will be six datasets. The sea-surface-temp.csv file is for the home page to describe the overall increase in sea surface temperature. The coralbleaching.csv file is the dataset for the coral bleaching case study. The SantaBarbaraLTER.csv and nineyears.csv files are for the ocean chemistry case study. The fish.csv file is for the fish populations case study. Additionally, the folder called "sst" in the main "oceanhealth_website" folder is the sea surface temperature data for the whole world that is needed to create the spatial maps in the fish population tab. 

While there is a main branch and a quarto branch, they should be identical. We had to create a quarto branch with the docs file outside of the quarto website project in order to publish the website. 

**Code dependencies:** To run our code, you will need to make sure some key packages are downloaded and loaded via the library() function. 

   **Packages to install:** These packages listed are ones that are not a part of the normal packages list that most people would have downloaded. If for some reason, you need to install more packages please install them on your computer. 
  
      install.packages("rnaturalearth")

      install.packages("rnaturalearthdata")

      install.packages("rnoaa")

      install.packages("stringr")

      install.packages("maps")

      install.packages("ggmap")

      install.packages("ersst")
      
      install.packages("ggrepel")

      install.packages("fuzzyjoin")

      install.packages("tiff")

      install.packages("scico")

      install.packages("raster")
      
      install.packages("Rmisc")
      
      
