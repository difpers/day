#include <iostream>
#include <cmath>
using namespace std;
int get_squre(int a){
return a*a;
}
int get_squre(int a, int b){
return a*b;
}
int main() {
int s = get_squre(5);
int s1 = get_squre(3,4);

return 0;
}
