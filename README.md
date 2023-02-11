
# Linux Commands
Below are some underrated Linux Commands that I have used and might be helpful for others
## 1 - nl
The nl command might be an underrated linux command. Usually whenever we want to print the content of a file in linux we use the ```cat``` command. However, it doesn't display the line numbers along with the content. In larger files, it becomes a  lot harder to read files without line number. Hence a solution for that is the ```nl``` command. ```nl filename``` displays the content of the file with line numbers.
## 2 - ss
The ```ss``` command investigates the socket and shows information similar to ```netstat``` command. However, it displays more informations regarding states than other tools.
## 3 - curl ifconfig.me
Normally, we have to go to google to check our external address. However, we can easily get that using this command. ```curl ifconfig.me``` shows the external address. You have to install the ```curl``` package first to run this.
## 4 - head
We are all well aware of the ```tail``` command which we use a lot to see the last few lines of a file or piped output. However, sometimes we might be in a situation where we just want to see the first few lines of a very large piped output or a file. The ```head``` command is a solution for that.
```head -n filename``` where n is the number of lines we want to see. If we do not include -n, it just displays the first 10 lines.
## 5 - fold
```fold``` helps to fold the content of a long line of code or documentation to adjust to the width of the display. By default, ```fold file.txt``` will fold the content upto the 80th character. We can assign our own limit by using ```fold -w 50 file.txt```. In this case, the lines will fold after 50th character. 
## 6 - look
Instead of going to the internet to search for the spelling of anything, we can use the ```look``` command which will search the dictionary and show all the words started with that particular string. For example, ```look dev``` will show all the words starting with the string ```dev```. 
## 7 - factor
While working with mathematical problems, to look for the factors of a number, you have to google again and again. However, you can easily use your terminal and get the factors of a number using the ```factor``` command. For example, ```factor 112``` will return all the factors of 112.
## 8 - tac
Similar to ```cat``` command, the ```tac``` command displays the file in a reverse order.
## 9 - free
Mostly when working in terminals, we are unaware with how much memory we have used. Or if we want to install a large package or file and don't know how much memory is available, we can use the ```free``` command to see the available memory. It also displays the memory used by the buffers and cache memory as well.
## 10 - man
The most underrated and useful command in the entirety of linux commands is the ```man``` command. It displays the manual for using any command in linux. It is the most helpful and very useful for beginners.
