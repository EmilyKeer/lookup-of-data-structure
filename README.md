# lookup-of-data-structure
## Data structure | Lookup
### Keywords:`sequential search`       `binsearch`      `sequence list`      `keywords`


Language: C </br>
> The repository includes:
* 1 source file
* 1 input_txt (for testing the source code)
* 1 demmand for the code (in Chinese; complete requirement for the tasks)

TASK concerning **Lookup** :</br>
*  Write an `algorithm`: 
*  1.create a sequence list according to the keyword
*  2.look up the designated keyword, using:  
   **sequential search**  
   **binserach**

*  3.output the position of the keyword and comparison times


***

### Preview:

```c
#include<stdio.h>
#include<stdlib.h>
#include<malloc.h>
#define Max_num 100
int create_list(int s1[], int s2[], int n, FILE*fp, FILE*fp2);
void post_error(FILE *fp2);
void post_null(FILE *fp2);
int bisearch (int s[], int x, int low, int high, int *pCount);
int seqsearch (int s[], int x,int high, int *pCount);


```



### Say thanks to ...
This project is my assignment for the course Data Structure when I was a first-year student at :blue_book: [the Department of Electrical Engineering at South China University of Technology](http://www.scut.edu.cn/ee/). </br>
I really appreciate the guidance and help from my teacher Dr. Qin, along with my classmates.:bowtie:

`Please feel free to give suggestions and comments!`
