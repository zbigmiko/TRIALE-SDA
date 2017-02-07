var tablica = [];

var zmiennaTemp = 0

for (var i = 0; i <= 10; i++) {

tablica.push(i);

zmiennaTemp = Math.floor(Math.random() * 10); 

tablica[i] = zmiennaTemp

}

var zmiennaMax = tablica[0];

var zmiennaMin = tablica[0];

for (var j = 0; j < tablica.length; j++) {

  if (zmiennaMin > tablica[j]) {
    zmiennaMin = tablica[j];
  }
  if (zmiennaMax < tablica[j]) {

zmiennaMax = tablica[j];
  }
}

var suma = 0;

var srednia = 0;

for (var k = 0; i < tablica.length; i++) {
  suma = suma + tablica[k];

}

srednia = suma / tablica.length;

 
console.log(tablica + " zmianna max:" + zmiennaMax+ " zmianna min:" + zmiennaMin + " srednia:" + srednia);

 

