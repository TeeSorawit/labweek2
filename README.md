#include<stdio.h>

//จงเขียนโปรแกรมเพื่อรับค่าตัวเลข 2 ตัว แล้วแสดงผลบวก ลบ คูณ หาร ของตัวเลขทั้งสองตัวนั้น โดยใช้ตัวแปรน้อยที่สุด (Level 1)

int main()
{
    int a,b,result;

    printf("enter your number ");

    scanf("%d",&a);

    printf("enter your number ");

    scanf("%d",&b);

    result = a+b;

    printf("Your answer is %d",result);

    return 0;

}
