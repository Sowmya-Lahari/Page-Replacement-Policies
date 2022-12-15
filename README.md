# Page replacement algorithms

The purpose of this project is to write a memory management simulator that uses paging
and measure the performances of page replacement algorithms such as FIFO (first in first
out), LRU (least recently used), LFU (least frequently used), MFU (most frequently used),
OPT (optimal page replacement). Keep track of what pages are being loaded. Observed that
the performance of all these page replacement algorithms depending on the situation that
they are handling.


## Steps to run the project
- Open your terminal with present working directory as the project folder. Then run the this command.
    ```g++ -o driver driver.cpp```
- Then enter this command to start application, 
    ```./driver```
    ## output
    * Three graphs will be shown between number of frames versus miss ratio and number of frames versus hit ration and number of frames versus number of swaps
    