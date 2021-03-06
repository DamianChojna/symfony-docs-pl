.. index::
   single: API

Stabilne API Symfony2
=====================

Stabilne API Symfony2 jest podzbiorem wszystkich publicznych metod (komponentów
oraz rdzennych pakietów) które mają tą właściwość, że niezmienne są:

* przestrzenie nazw oraz nazwy klas;
* nazwy metody;
* deklaracje metod (argumenty oraz zwracane wartości);
* działania metod.

Sama implementacja może się zmienić. Jedyną podstawą do zmiany stabilnego API
jest bład w zakresie bezpieczeństwa.

Stabilne API oparte jest na białej liście oznakowanej znacznikiem `@api`. Dlatego
też wszelki kod nie oznaczony tym znacznikiem nie jest częścią stabilnego API.

.. tip::

    Wszystkie pakiety osób trzecich również powinny udostępniać swoje stabilne API.

Dla najnowszej stabilnej wersji Symfony następujące komponenty posiadają API
oznaczone jako publiczne:

* BrowserKit
* ClassLoader
* Console
* CssSelector
* DependencyInjection
* DomCrawler
* EventDispatcher
* Filesystem
* Finder
* HttpFoundation
* HttpKernel
* Locale
* Process
* Routing
* Templating
* Translation
* Validator
* Yaml
