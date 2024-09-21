# Predective-Modelling
##### (Data Encoding, Linear Regression, Logistic Regression, LDA & Decision Tree)

## Problem Statment 1:
#### The comp-activ database comprises activity measures of computer systems. Data was gathered from a Sun SPARC station 20/712 with 128 Mbytes of memory, operating in a multi-user university department. Users engaged in diverse tasks, such as internet access, file editing, and CPU-intensive programs. Being an aspiring data scientist, you aim to establish a linear equation for predicting 'usr' (the percentage of time CPUs operate in user mode). Your goal is to analyse various system attributes to understand their influence on the system's 'usr' mode.
### Data Description:
#### System measures used:
#### lread - Reads (transfers per second ) between system memory and user memory
#### lwrite - writes (transfers per second) between system memory and user memory
#### scall - Number of system calls of all types per second
#### sread - Number of system read calls per second .
#### swrite - Number of system write calls per second .
#### fork - Number of system fork calls per second.
#### exec - Number of system exec calls per second.
#### rchar - Number of characters transferred per second by system read calls
#### wchar - Number of characters transfreed per second by system write calls
#### pgout - Number of page out requests per second
#### ppgout - Number of pages, paged out per second
#### pgfree - Number of pages per second placed on the free list.
#### pgscan - Number of pages checked if they can be freed per second
#### atch - Number of page attaches (satisfying a page fault by reclaiming a page in memory) per second
#### pgin - Number of page-in requests per second
#### ppgin - Number of pages paged in per second
#### pflt - Number of page faults caused by protection errors (copy-on-writes).
#### vflt - Number of page faults caused by address translation .
#### runqsz - Process run queue size (The number of kernel threads in memory that are waiting for a CPU to run. Typically, this value should be less than 2. Consistently higher values mean that the system might be CPU-bound.)
#### freemem - Number of memory pages available to user processes
#### freeswap - Number of disk blocks available for page swapping.
#### usr - Portion of time (%) that CPUs run in user mode


