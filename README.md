# Healthcare_Challenge

## Requirement and filepath
This challenge was conducted locally, if you are to test this code please replace filepath in the Jupyter Notebook with your own filepath destination to the Anthem table of contents data.
The requirements are only: Python, Pandas, IJSON, and matplotlib. Latest versions should all work. 

## Some thoughts and assumptions on the process
First, they certainly do not make it easy, do they? Here are some time approximations of my operations of about 3 hours. (2 sittings due to dog vet appointment 1.5 hours each)
1) Download the file: 13 minutes
2) Getting to know the data a little: 30 minutes
3) Looking through Anthem website to understand vernacular: 10 minutes
4) Parsing through the data succesfully: 1 hour
5) Sifting through data, filtering for duplicates, understanding the answer: 1 hour
6) Write up and thoughts: 30 minutes

## Assumptions
1) I assumed the tables schema provided was the correct path without putting too much thought into it.
2) I found that the table 'file_location_df' that contained only two columns, a description column and location column,  were the only things I needed as I saw that both New York and PPO were present in the description column.
3) I assume that New York and PPO don't have other variations or nicknames in the world of healthcare. That could be wrong, and with more time, I would explore that.
4) There were only 2 unique locations, and 70 unique addresses. This probably means there are lots of descriptions (URLs) assocciated with each location.
   -Random note: New York CIty is in the southeast of the state of New York that hosts a large majority of the state's population. Notheastern NY and Western NY are the only descriptions present. I would 
   explore that if I had more time.

## What would I have done differently?
1) I would explore the latest techniques in how to make things run faster with some kind of parallel computation.
2) I chose my tech stack to be what was familiar. Donwloading the file, using python notebook, and sifting through a JSON file. There are more sophisticated ways to do this which would take more time for me to setup and learn.

# MY FINAL ANSWER
It is attached as final_url_list
