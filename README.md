# Ebay-DataScraping
**In this Repo we use a python program to search through ebay** 
## What does this Program do
This Program goes through the first 10 pages of ebay for whatever search term is put in and gives out a json or csv file enlisting the, item status, the price of the item, the name of the item, the shipping cost of the item and the return policy of the item. It can work for any search term. Hence this prgram essentially scrapes data of ebay for whatever desired search term. 
## How to use it
### Getting a JSON file 
First you'll have to download the python file `ebay-dl.py`. After downlading the file and opening it up in vscode, you'll have to write in the terminal `$ python3 ebay-dl.py 'hammer' --num_page=10` this would create a JSON file called hammer.json with the desired results. You can use whatever search term you want, it could be chair, it could be caps literally anything and the program will search for that term across ebay. Even for terms that have a gap in the middle say stuffed animals, or like I took the example of laptop stand youll have to do something similar `$ python3 ebay-dl.py 'stuffed animals' --num_page=10`. Writing this in the terminal will give the desired output. If you don't want 10 pages worth of data you could change the ` --num_page= ` to whatever number of pages you want. If you want one page you put in 1, if you want two page you put in 2 and so on. 
### Getting a csv file 
Getting a csv file is pretty similar, you just have to add one thing in the terminal ` $ python3 ebay-dl.py 'hammer' --num_page= 10 --csv a` the addition or the difference between this and the Json one is that `--csv a` flag. What this does is, it tells the program that you want a csv file instead of a JSon file, and then the output comes in a csv file. You can write any term after the ` --csv` i just wrote the letter `a` but you could literally write any gibberish and the output would be the same for example you could write `--csv fgh` and youll get the desired csv file. 

To make your own program visit this [page](https://github.com/mikeizbicki/cmc-csci040/tree/2021fall/hw_03) 
