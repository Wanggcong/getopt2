# getopt2
has tested
Note:there are some key point here：
1 head file
//#include <unistd.h>  //for unix or linux
#include <windows.h>   //for window
2 key function
int getopt(int argc, char * const argv[], const char *optstring);
here, there is no difference between main(int argc, char * const argv[])and getopt(),but optring.



reference:
http://www.cnblogs.com/sunyubo/archive/2010/09/17/2282120.html
