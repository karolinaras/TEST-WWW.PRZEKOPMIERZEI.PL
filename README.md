# TEST-WWW.PRZEKOPMIERZEI.PL
Projekt Facebook Mamo Pracuj W IT- Napisanie przypadków testowych oraz raportowanie błędów do strony www.przekopmierzei.pl
Test strony internetowej w ramach projektu prowadzonego na Facebook przez grupę Mamo pracuj w IT. Zadanie polega na przetestowaniu eksploracyjnym w tym napisaniu przypadków testowych i zaraportowaniu błędów stony internetowej www.przekopmierzei.pl

Stronę internetową testowałam na podstawie listy kontrolnej sporządzonej w oparciu o listę kontrolną Piotra Wicherskiego.Testowano w windows XP przeglądarka Google Chrome 64-bit

HEAD
Meta Tag
1. Doctype: HTML5 BRAK
2. Charset: utf=8 OK
3. Viewport: OK
4. Title: mniej niż 55 znaków OK PrintScreen 
5. Description: BRAK
6. Canonical: rel="canonical" BRAK(powielanie treści)

HTML TAGS
1. Language attribute: język -pl BRAK
2. Direction attribute: kierunek rtl BRAK
3. CSS Critical:(style<style)OK
4. CSS order: ?

HTML
1. Error pages:
2. Noopener: BRAK
3. Clean up comments: BRAK (są komentarze)  

HTML TESTING
1.  W3C compliant:PrintScreen
2.  Link checker: W3C LINK znaleziono 2 linki PrintScreen

WEBFONTS
Webfont format: font family Open Sands
Webfond size: 14px

CSS
1. Responsive Web Design: OK
2. CSS Print : OK
3. Unique ID : OK
4. Reset CSS : ?
5. Vendor prefixes: ?

PERFORMANCE
1. Concatenation: BRAK
2. Minification: ?
3. Unused CSS :? 

CSS TESTING
1. Stylelint: ?
2. Responsive web design: OK
3. CSS Validator : Znaleziono 5 błędów Print Screen
4. Desktop Browser : Firefox
5. Mobile Browsers: w trakcie
6. OS: niedotyczy
7.Reading Direction:?

IMAGES
1.Optimization: OK Nie przekracza 1MB PrintSreen
2.Width and Height : OK
3.Alternative text: BRAK PrintScreen
4.Lazy loading:?

SECURITY
1.Scan and check your web site: Site is using HTTP not HTTPS Print Screen, 
2. HTTPS: Scan SSL OK
3.  HTTP Strict Transport Security (HSTS):Nagłówek HTTP jest ustawiony na "Strict-Transport-Security” BRAK Print sreen

TESTY EKSPLORACYJNE:
1.W POLU PRZEZNACZONYM NA KOMENTARZ POD ZDJĘCIAMI JEŚLI WPISZEMY JEDNYM CIĄGIEM DUŻĄ LICZBĘ LITER I WYŻLEMY KOMENTARZ- LITERY WYCHODZĄ POZA RAMKĘ POLA KOMENTARZA.


PODSUMOWUJĄC - RAPORT LIGHTHOUSE
1.DŁUGIE ŁADOWANIE SIĘ STRONY 780 ms
2.DWA BŁĘDY GET 404
3. OGÓLNE WYNIKI NA POMARAŃCZOWO.


