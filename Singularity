Bootstrap:docker
From: nfcore/atacseq:1.0.0

%setup

%environment

%files

%post
  mkdir -p /athena
  mkdir -p /scratchLocal
  mkdir /scratch
  echo "install.packages(\"ggplot2\", repos=\"https://cran.rstudio.com\")" | R --no-save
  echo "install.packages(\"ggrepel\", repos=\"https://cran.rstudio.com\")" | R --no-save
  echo "install.packages(\"dplyr\", repos=\"https://cran.rstudio.com\")" | R --no-save
  
