#include <stdio.h>
#include <stdlib.h>
#include <stdint.h>

void nhapsoluongphantu (int *n)
{
    printf ("Nhap so luong phan tu cua mang: ");
    scanf ("%d", n);

    while (((*n) < 0) || ((*n) >=16))
        {
            printf("Khong hop le, nhap lai n \n");
            printf ("Nhap so luong phan tu cua mang: ");
            scanf ("%d", n);
        }
}

void nhapmang(uint64_t mang[], int n)
{
	printf ("Khoi tao mang \n");
    for (int i=0; i < n; i ++)
    {
        printf("Gtri cua phan tu thu %d la: ", i);
        scanf("%ld", &mang[i]); 
    }
}
    
void inmang(uint64_t mang[], int n)
{
	printf("Phan tu cua mang la: ");
    for (int i=0; i < n; i ++)
    {
        printf("%ld", mang[i]);
    }
    printf ("\n");
    printf("Dia chi cua tung phan tu: \n");
    for (int i=0; i < n; i ++)
    {
        printf("Dia chi cua ptu thu %d la: %d\n", i, &mang[i]);
    }
}

int main()
{
    int n;
    uint64_t Mang [100];
    nhapsoluongphantu(&n);
    nhapmang(Mang, n);
    inmang(Mang, n);
    return 0;
}
