# Bank-Software-Project
Management of multiple Accounts (Kontos), Management of the associated Tasks

Aufgabenstellung:
  Für das Kundenterminal einer Bank soll eine Software geschrieben werden, mit welcher grundlegende Kontenverwaltungsvorgänge und           Geldtransaktionen durchgeführt werden können!
  
  User-Story 1:
    Der Bankkunde soll seinen Kontostand abfragen können *Konto.standabfragen()*, damit er weiß, wieviel Geld er noch hat.
    
  User-Story 2:
    Der Bankkunde soll von seinem Konto bis zum maximalen Überziehungs-kredit (Dispositionskredit) Geld abheben können, damit er        Bargeld hat. *konto.abheben(float menge)*
    
  User-Story 3:
    Der Bankkunde soll von seinem Konto bis zum maximalen Überziehungs-kredit (Dispositionskredit) Geld auf ein anderes Konto überweisen können, damit er Rechnungen bezahlen kann. *konto.überweisen(konto ziel, float menge)*
    
Die Software soll nach dem MVC-Prinzip unterteilt werden!
