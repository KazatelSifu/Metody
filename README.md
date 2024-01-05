function odmocninaZCisla(cislo) {
  return Math.sqrt(cislo);
}
console.log(odmocninaZCisla(25));

function prumerPetiCisel(cislo1, cislo2, cislo3, cislo4, cislo5) {
  const soucet = cislo1 + cislo2 + cislo3 + cislo4 + cislo5;
  return soucet / 5;
}
console.log(prumerPetiCisel(10, 20, 30, 40, 50));

function jeLiche(cislo) {
  return cislo % 2 !== 0 ? 'je liché' : 'není liché';
}
console.log(jeLiche(7));

function jePrvekVPoli(prvek, pole) {
  return pole.includes(prvek) ? 'je v poli' : 'není v poli';
}
const mojePole = [1, 2, 3, 4, 5];
console.log(jePrvekVPoli(3, mojePole));
