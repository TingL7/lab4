# lab4  
## questionA  
 double average(double *n1, double &n2):  
000000000040052d T _Z7averageif  
  
int average(int n1, float n2):  
00000000004004ed T _Z7averagePdRd
  
## questionB  
output:  
1 8  
4 8  
4 8  
8 8  
  
explain:  
char size: 1 byte, so sizeof(a) = 1  
int size: 4 byte, so sizeof(b) = 4  
float size: 4 byte, so sizeof(c) = 4  
double size: 8 byte, so sizeof(d) = 8  
Operating System of VM is Linux Mint 17 Cinnamon 64-bit, so the address is also 64 bit.  
type of pa, pb, pc and pd are pointer, so their size is equal to address, 64 bit and sizeof(pa) = sizeof(pb) = sizeof(pc) = sizeof(pd) = 8.
