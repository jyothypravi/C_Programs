# C_Programs
#include<stdio.h>
void main(){
  int n=5;
  int a[5],i,j,b[5],t;
  for(i=0;i<=n;i++){
    scanf("%d",&a[i]);  
  }
  for(i=0;i<=n;i++){
      for(j=i+1;j<=n;j++){
    if(a[i]<a[j]) {
        t=a[i];
        a[i]=a[j];
        a[j]=t;
    }
    
  }
  }
  for(i=0;i<=n;i++){
    printf("%d",a[i]);  
  }
  
}
