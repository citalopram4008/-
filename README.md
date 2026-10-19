# -
C语言的矩阵行列变换代码
#include <stdio.h>

int main() {
            int arr[10][10]={0};
            int n=0;int m=0;
            scanf("%d %d",&n,&m);//输入行数和列数
            int i=0;int j=0;
            for (i=0; i<n; i++) 
        {
            for (j=0; j<m; j++)
             {
                scanf("%d",&arr[i][j]);//输入指定的矩阵
            }
        }
         for (i=0; i<m; i++) 
        {
            for (j=0; j<n; j++)
             {
                printf("%d ",arr[j][i]);//输出行列变换矩阵
            }
                printf("\n");
        }

    
        
   
    return 0;
}


