#Mauricio Diaz-Ortiz September 2017

#Anaconda base image
FROM anaconda

#installing pymoku
RUN conda create --name pymoku
RUN source activate pymoku 
RUN conda config --add channels conda-forge
RUN conda config --add channels liquidinstruments
RUN conda install pymoku