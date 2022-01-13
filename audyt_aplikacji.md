# <center>Raport z audytu aplikacji e-commerce-food-shop-with-qr-codes</center>
#### <center> Testowana aplikacja (wykonana w ramach pracy inżynierskiej): https://github.com/face1337/e-commerce-food-shop-with-qr-codes </center>
### Wersja raportu : 1.0
### Data wykonania audytu : 11.01.2022
# Spis treści
#### **1. Podsumowanie**
#### **2. Zakres i cele** 
####  2.1 Cel i metodologia audytu
####  2.2 Zakres audytu
####  2.3 Wykonane czynności
####  2.4 Napotkane ograniczenia
####  2.5 Aplikacja 
#### **3. Testowanie komponentów i obszarów**
#### **4. Przegląd wyników i zaleceń** 
#### **5. Sprawdzone zostało również**
## **1. Podsumowanie**
#### Audyt aplikacji realizowany był jako audyt zgodności ze standardem Application Security Verification Standard 4.0.3 jak również pod kątem ogólnego bezpieczeństwa aplikacji.
#### Ogólny stan zgodnośći aplikacji ze standardem ,,Application Security Verification Standard 4.0.3" można określić jako **TODO**.
#### Wyróżniono kilka głównych problemów wpływających na niezgodność aplikacji z wymaganiami standardu: TODO
## **2. Zakres i cele** 
### **2.1 Cel i metodologia audytu**
### **2.2 Zakres Audytu**
####  Audyt objął nastepujące obszary :
##### Audyt został przeprowadzony zgodnie z Level 1 ASVS

##### V2. Uwierzytelnianie
##### V3. Zarzadzanie sesjami
##### V4. Kontrol dostępu
##### V5. Walidacja, sanityzacja i kodowanie 
##### V6. Kryptografia
##### V7. Obsługa błędów i logowanie
##### V8. Ochrona danych
##### V9. Komunikacja
##### V10. Złośliwy kod
##### V11. Logika biznesowa
##### V12. Pliki i zasoby
##### V13. Api i webserwisy
##### V14. Konfiguracja
### **2.3 Wykonane czynności**
### **2.4 Napotkane ograniczenia**
Analizowana aplikacja jest dostępna tylko w formie developerskiej. Nie została zahostowana na żadnym z portali co uniemożliwa przetestowanie niektórych punktów kontrolnych dostępnych tylko dla aplikacji w fazie produkcyjnej, gdyż są zależne od sposobu wdrożenia aplikacji. 
Dodatkowo aplikację przetestowano aby sprawdzić czy jest zgodna z Level 1 ASVS. Tym samym wiele z wymagań zostało wyłączonych (w tym cała kategoria V1: Architektura, projektowanie i modelowanie zagrożeń)
### **2.5 Aplikacja**
Aplikacja e-commerce-food-shop-with-qr-codes jest aplikacją webową opartą o architekturę typu MVT (Model-View-Template). Jako backend aplikacji wykorzystano popularny framework Django (python), frontend zaś został utworzony przy pomocy Bootstrap'a i dodatkowych styli CSS. Użyta baza danych to PostgreSQL
## **3. Testowanie komponentów i obszarów**
## **4. Przegląd wyników i zaleceń** 
## **5. Sprawdzone zostało również**
