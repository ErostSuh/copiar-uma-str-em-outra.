# copiar-uma-str-em-outra.
#include &lt;stdio.h> #include &lt;string.h>  int main(){     char  str1[10] = "Ola";     char * res = str1;     char  str2[10] = "Mundo";     char * aux = str2;          for(;*aux != '\0'; aux++, res++){         *res = *aux;     };     *res = *aux;     puts(str1);     puts(str2);     return 0; }
