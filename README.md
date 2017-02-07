var tablica = [];

var zmiennaTemp = 0

for (var i = 0; i <= 10; i++) {

tablica.push(i);

zmiennaTemp = Math.ceil(Math.random() * 10); 

tablica[i] = zmiennaTemp

}

var zmiennaMax = tablica[0];

var zmiennaMin = tablica[0];

for (var i = 0; i < tablica.length; i++) {

  if (zmiennaMin > tablica[i]) {
    zmiennaMin = tablica[i];
  }
  if (zmiennaMax < tablica[i]) {

zmiennaMax = tablica[i];
  }
}

var suma = 0;

var srednia = 0;

for (var i = 0; i < tablica.length; i++) {
  suma = suma + tablica[i];

}

srednia = suma / tablica.length;

 
console.log(tablica + " zmianna max:" + zmiennaMax+ " zmianna min:" + zmiennaMin + " srednia:" + srednia);

 

