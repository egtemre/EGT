# EGT
yemekhane projesi

#include <stdio.h>
#include <stdlib.h>

/* run this program using the console pauser or add your own getch, system("pause") or input loop

 	                                     "yemek hane projesi " 
sisteme hoş geldiniz diye her seferinde mesaj çıkarıyor karşınıza sonrasında 
2 ye 2 lik matriks ve döngümüz var bu döngü ve matriks yemek hanede parmak izini hesaplıyor            
yemekhane de toplam 150 kişi vardır herkes kendi yemeğini alıp parmak izini okutur
iki çeşit yemek çıkar istediğini seçer ayrıca parası ile ekstra ürün de alınabilir 
 parmak izine göre ad soyat aldığı ürünlerin fiyatı belli olur 
 ve daha sonra bir şey almak isterse aynı şekilde 
 devam eder 150 kişi parmak okuttuktan sonra sistem kendini kapatır. 
 her parmak izi okunduğunda yıldız basmaktadır
*/

	int main() 
{	


		int main ()
	{
	mesaj();
	printf("Hos Geldiniz :)) \n");
	return 0 ;
	
	}
	
	
		void mesaj()
		{
					printf("KYK");
					mesaj2();
					
			}	
				void mesaj 2 ()
				{
						printf("YURDUNA");
				}
				
				
		int i=1; int Yemek=0; char Parmakİzi='T'; int sayac =0 ; int fiyat=0; int toplam =0; int kisi =0; int durum=0; int GirenSAyısı =0; int ParmakSayısı=0;
		 int blok=0; int isim=0;int SoyIsim=0; int yas=0;  mesaj=0;
		 

  		int GirenSAyısı = 0
  		
  		
  		
  		printf("isminizi giriniz \n");
  		printf("soyadınızı giriniz\n");
  		printf("yasınızı giriniz\n");
  		scanf("%s" "%s" "%d",&isim,&SoyIsim,&yas);
  		
  			
  		printf("parmaginizi makineye okutunuz");
  		
  		
  		
  		
	printf("Parmak izinizi %c basınız.",Parmakİzi);
	int dizi[150]={1,2,3};
	int j=0;
	int k=0;
	for(j=0;j<parmak izi sayisi;j++)
	{
			printf("sıradaki kişi %d dir .\n",dizi[j]);
			for(k=0;k<dizi[k];k++)
			{printf("*");
		
			}
			printf("\n");
	}
	printf("Yemek fiyatı %d dir.\n",fiyat);
	printf("Toplam ücret %d dir. \n",toplam);
	scanf("%d %d %d ",&Parmakİzi&fiyat&toplam);
	
		while (1)
	{printf("Sıradaki kişi %d dir.\n",i);
	i++;
		if(i==150)
	break 	;
	 else 
 		continue ;	
 		
		 }
while(i<150)
{
	 sayac++;
	 printf("Yemekhaneden Çıkmak istermisiniz (E=1,H=0 girin )?\n");
	 scanf("%d",&durum);
	 if(durum==1)
	 	İ=151;
	 	else
	 	i=149;
	 	
}

  printf("Yemekhaneden %d.ninci olarak çıkıldı\n",sayac);
  
  
   char ParmakSayısı[150]={};
	  		printf("parmak izinizi okutunuz\n");
	  		scanf("%s",ParmakSayısı);
	  		
  
  
  
  int mBlokBir [2] [2], mBlokIki[2] [2],mBlokSonuc	[2] [2] ;
  
  printf("Birinci blokta nerede oldugunzu giriniz\n");
  scanf ("%d",&blok);
for(int i=0; i<2; i++)
for(int j=0; j<2; j++){
printf("[%d][%d]= ", i+1, j+1);
scanf("%d", &mBlokBir[i][j]);
}
printf("Ikınci blokta nerede oldugunuzu giriniz \n");
for(int i=0; i<2; i++)
for(int j=0; j<2; j++){
printf("[%d][%d]= ", i+1, j+1);
scanf("%d", &mBlokIki[i][j]);
}
printf("Sonuc\n");
for(int i=0; i<2; i++){
for(int j=0; j<2; j++){
mBlokSonuc[i][j] = mBlokBir[i][j] + mBlokIki[i][j];
printf("%d ", mBlokSonuc[i][j]);
}
printf("\n");
}
getch();
return 0;
}


void main ()
{
	char sdizi1[]=("YemekSırası");
	char sdizi2[]=("zaman");
	int sonuc=-2;
	
		printf("\n\n\t");
		printf("1.dizi:%s",sdizi1);
		printf("\n\t");
		printf("2.dizi : %s",sdizi2);
		printf("\n\n\t");
		
		sonuc=strcmp(sdizi1,sdizi2);
		
		if(sonuc>0)
		{
			printf("sdizi1>sdizi2");
			
		}
		 	else if (sonuc<0)
		 	{
		 			printf("sdizi1<sdizi2\n\t");
		 			
			 }
			else
			{
					printf("sdizi1=sdizi2\n\t");
				
					}
		
		FILE*dosya;
		int c ;
		dosya=fopen("ParmakIzi",r);
		if(dosya==NULL) printf("Boyle bir dosya yok.\n");
		else { 
		do{
		c=getc(dosya);
		putchar(c)
		
		}while(c!=EOF);
		fclose(dosya);
		
		
}

	
	return 0;
}
