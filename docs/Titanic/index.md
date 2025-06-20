# Zapraszam do zapoznania się z analizą danych pasażerów Titanica – jednej z najbardziej znanych katastrof morskich w historii.
**_Data utworzenia_: luty 2025**

W ramach eksploracyjnej analizy danych (EDA) przygotowałam analizę zbioru danych dotyczących katastrofy Titanica. Celem było zrozumienie struktury danych, sprawdzenie brakujących wartości oraz poznanie zależności między cechami pasażerów a ich szansami na przeżycie. Przeanalizowałam m.in. wpływ płci, wieku, klasy podróży czy liczby członków rodziny na pokładzie na przeżywalność. Analiza została wsparta wizualizacjami, które pozwoliły lepiej zobrazować ukryte wzorce i zależności w danych.

<a href="TITANIC notebook.ipynb" class="md-button md-button--primary">Pobierz Notebook</a>

<iframe
    id="content"
    src="TITANIC notebook.html"
    width="100%"
    style="border:1px solid black;overflow:hidden;"
></iframe>
<script>
function resizeIframeToFitContent(iframe) {
    iframe.style.height = (iframe.contentWindow.document.documentElement.scrollHeight + 50) + "px";
    iframe.contentDocument.body.style["overflow"] = 'hidden';
}
window.addEventListener('load', function() {
    var iframe = document.getElementById('content');
    resizeIframeToFitContent(iframe);
});
window.addEventListener('resize', function() {
    var iframe = document.getElementById('content');
    resizeIframeToFitContent(iframe);
});
</script>