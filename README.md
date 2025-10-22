lo# Sator
Import java.utils.Scanner;
  Declaración de variable 
   String palabra = "SATOR"
int cont =0 
    System.out.println("La palabra se repite"+contigo+"5")
         String [][] matriz={
    {"S","A","T","O","R"},
    {"A","R","E","P","O"},
    {"T","E","N","E","T"},
    {"O","P","E","R","A"},
    {"R","O","T","A","S"},
}
  Recorrido horizontal 
      for( int i=o ; i<5 ; i++){
Variable encontrada 
    boolean encontrada = true
for( int j=0  ;  j<5  ; j++){
 if ( matriz [i][j] !=palabra.chartAt(j)){
        encontrada=false 
       break
 }
} 
     if (encontrada) {
             contador++;

  }
}
  
 Recorrido vertical
 for ( int j=0 ; j<5 ; i++){
 Ahira se verifica la columna completa 
   boolean encontrada = true 
for( i=0 ; i<5 ;i++){
  if ( matriz [i][j] !=palabra.chartAt(i)){
    encontrada=false 
  break
 }
}
  if (encontrada){
    contador++
 }
}
  return contador ; 
}
