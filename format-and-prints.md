## Format and Printing in terminal

Print through loop and echo:

    for i in {1..30}; do echo "Line $i" ; done
    
Create directory for each txt file and move that txt file to the directory with the same name (without extension):

    for x in ./*.txt; do   mkdir "${x%.*}" && mv "$x" "${x%.*}"; done
  
Print through loop and add an extra line:

    for i in {1..30}; do echo "Juzz $i:"; echo ""; done
    
Append a new line of text in a file:

    echo 'export PATH=$PATH:/usr/local/go/bin' >> ~/.bashrc
    echo 'This is another text' >> ~/.bashrc
