# GoCF
Contest parser for codeforces (only C++)

**Requirements** <br>
1. Python v2/3 <br>
2. [Python Beautiful Soup](http://www.crummy.com/software/BeautifulSoup/bs4/doc/)<br>
3. [Colorama](https://pypi.python.org/pypi/colorama)<br>

tested on Ubuntu 14.04<br>

**While Parsing Contest initially**

![alt text](while_parsing.png " Parsing test cases!")

**While testing your solution**

![alt text](CE.png " Testing your Solution!")
![alt text](WA.png " Testing your Solution!")
![alt text](TLE.png " Testing your Solution!")
![alt text](AC.png " Testing your Solution!")

**How to install it?** <br>
* copy `gocf` and `incf` file to `/bin/` directory <br>
* give permissions to them by `sudo chmod 755 /bin/gocf` and `sudo chmod 755 /bin/incf` <br>
* Now create a directory in your `home` folder and name it `GoCF` <br>
* copy `Parse.py` from `GoCF_files` to `GoCF` and if neccessary do `chmod` <br>

**How to use it?** <br>
* After the contest begins, fire up your terminal and type `incf` <br>
* Now, enter the contest code <br>
* GoCF will now download the test cases for you! <br>
* Now, for example let us take contest code as `624`, name your problems as `624_A.cpp`, `624_B.cpp`, . .(Case sensitive)<br>
* Code in your favourite editor<br>
* now, for testing your solution just `gocf 624_A.cpp` <br>

**That's it!**<br>

*Star it* <br>


[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/sukeesh/gocf/trend.png)](https://bitdeli.com/free "Bitdeli Badge")
