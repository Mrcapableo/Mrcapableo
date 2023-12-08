int topla(int a, int b){

//Sayıları toplar
 int c;
 c=a+b;
 return c;
 }
  int fark(int a, int b) {
     return a-b;
}

void dortislem(int a, int b) {
  //Sayıları toplar
  int tpl= a+b;
  int frk= a-b;
  int crp= a*b;
  double blm = a / b;
  print("Toplamı :${tpl} Farkı:${frk} Çarpımı:${crp} Bölümü${blm}");
  }
  
  void main() {
  //Function kullanımı
     //Çağırma
  int toplami= 0;
  int farki= 0;
  toplami = topla (234,5);
  farki = fark(200,10);
  print("Toplamı: ${toplami} Farkı: ${farki}");
  
  dortislem(200,100);
  dortislem(120,40);
  dortislem(150,5);
}
