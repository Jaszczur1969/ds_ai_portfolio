# Analiza Danych dla pasażerów Titanica (EDA)

**2025-08-03**

Zapraszam do zapoznania się z moim projektem dotyczącym analizy danych o pasażerach Titanica wykonanej z pomocą eksploracji domenowej (EDA). 

- Czy kobiety i pasażerowie podróżujący 1 klasą mieli większe szanse na przeżycie katastrofy? 
- Ile osób wchodziło do łodzi ratunkowej? 
- W jakim wieku byli pasażerowie? 
- Ile kosztowały najdroższe bilety i kto je kupił? 

Te oraz inne ciekawostki znajdziesz w poniższym raporcie. Przygotuj się na fascynującą podróż przez dane, która z pewnością wzbogaci Twoją wiedzę i zainspiruje do dalszych badań.

<a href="Titanic.ipynb" class="md-button md-button--primary">Pobierz Notebook</a>

<iframe
    id="content"
    src="Titanic.html"
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
