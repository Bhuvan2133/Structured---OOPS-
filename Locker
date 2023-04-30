#include <stdio.h>
#include <stdlib.h>

int main(){
    char m[3][3];
    scanf("%c %c %c",&m[0][0],&m[0][1],&m[0][2]);
    scanf("%c %c %c",&m[1][0],&m[1][1],&m[1][2]);
    scanf("%c %c %c",&m[2][0],&m[2][1],&m[2][2]);
    
    char pass[6];
    for (int i=0;i<3;i++){
        pass[i] = m[i][i];
    }
    pass[3] = m[0][2];
    pass[4] = m[1][1];
    pass[5] = m[2][0];

    printf("Concatenation of Diagonal characters ");
    for (int i=0;i<6;i++){
        printf("%c",pass[i]);
    }
    printf("\n");
}
