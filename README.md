# zadanie_przelicznik
#jeden nie dokonczony kod
<!DOCTYPE html>
<html>
<head>
<title>Konweter jednostek</title>
</head>
<body>
    <header>
<h1>Konwerter Jednote</h1>
    </header>     
<script languge="JavaScript">
const number1 = parseFloat(prompt('Na jaką jednostkę chcesz przeliczyć km czy mile'));
const number2 = parseFloat(prompt('Podaj ilość km/mil:'));

 if (isNaN)(number1) {
    document.write('wpisz poprawnie jednostkę');
 } else if (isNaN(number2)) {
document.write ('wpisz poprawną liczbe');
 } else {
document.write('<p>konwenter jedenostek<p>' 

}
</script>
</body>
</html>
#dreugi nie dokonczony kod tez nie dziala
<!DOCTYPE html>
<html>
<head>
<title>Konweter jednostek</title>
</head>
<body>
    <header>

    </header>     
<script languge="JavaScript">
<h1>Konwerter km na mile i mile na km</h1>

 function konwertujdomil() {
     const km = parseFloat(document.getElementById('kilometry').value);
if (!isNan(km)) {
document.getElementById('mile').val ue = (km * 0.621).toFixed(2) ; } else {

    document.getElementById('mile').val ue= '';

}

}
function konwertujdokm() {
    const miles = parseFloat(document.getElementById('mile').value);
    if (!isNan(mile)) {
        document.getAnimations('kiolmetry').value = '';

    }
}


</script>
</body>
</html>
