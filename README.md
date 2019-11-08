# Extractive-Summarization-tool
This tool will take an Long Article or any Text as an input and will give you an summary of following content.

Extractive methods attempt to summarize articles by selecting a subset of words that retain the most important points.  This approach weights the important part of sentences and uses the same to form the summary. Different algorithm and techniques are used to define weights for the sentences and further rank them based on importance and similarity among each other.

![picture alt](https://github.com/shubham769/Extractive-Text-Summarization-tool/blob/master/text.png)


### Running Script

Assuming you have pip installed, if not follow the steps: 

Start by updating the package list using the following command:


`sudo apt update`


Use the following command to install pip for Python 3:

`sudo apt install python3-pip`
 
Now let's import all necessary packages

Use following command to install NLTK 

`pip3 install nltk`

Lets install numpy package

`pip3 install numpy`

Install the current release of networkx with pip

`pip3 install networkx`

Look at this Notebook :https://github.com/shubham769/Extractive-Text-Summarization-tool/blob/master/summary.py

At Line no: 86 in the End of notebook

`generate_summary( "mydata.txt", 2)`

Replace file name with your File location and Number of line summary you want.

Then run the final command :

`python summary.py`

Output will be on your console.

Happy coding :-)

For more info go through this blog: https://blog.knoldus.com/machine-x-text-summarization-in-python/
