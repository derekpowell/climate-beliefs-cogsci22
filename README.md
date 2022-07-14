# Understanding intuitive theories of climate change

Authors: Brittany Schotsch & Derek Powell

This is the data and code repository for the CogSci22 conference proceedings paper of the same name.

## Reproducibility notes

To reproduce the manuscript and all analyses, follow the following steps after cloning this repository.

**RECOMMENDED**: Install [Docker](https://www.docker.com/) and utilize `cogdatasci/rstudio` docker container. Recommend you run with the following options:
```bash
docker run -d -p 8787:8787 -v "`pwd`":/home/rstudio/working \
 -e PASSWORD=my_password_here cogdatasci/rstudio
 ```
then navigate to `localhost:8787` in your browser to access the rstudio interface.
