#include <stdio.h>
#include <stdlib.h>
    int sd, sm, se, md, me;
	void Ler_sensor();
	void IA();
	void resposta();
int main()
{
loop:
scanf("%d %d %d", &se, &sm, &sd);
if((se == 0) && (sm == 0) && (sd == 0)){
    me = 1;
    md = 1;
}
else if (((se == 1) && (sm == 1) && (sd == 0)) || ((se == 1) && (sm == 0) && (sd == 0))) {
    me = 1;
    md = 0;
}
else{
    me = 0;
    md = 1;
 }
 printf("me = %d, md = %d", me, md);
goto loop;
    return 0;
}
void Ler_sensor(){

}
