# Hangman app

## Bygga ett användargränssnittet och använda MVC

Att bygga en iOS applikation kräver ofta att man behärskar flera färdigheter så som att strukturera kod (gärna MVC eller dylikt) och bygga ett grafiskt användargränssnitt. Att bygga ett snyggt och enkelt grafiskt användargränssnitt är inte enkelt och kräver att programmeraren har en god kunskap om ramverkets möjligheter och begränsningar.

Bakom en applikation är enkel och tydlig kod en viktigt komponent för en applikation som är tänkt att utvecklas och hållas buggfri. Men för att uppnå detta krävs struktur och planering. Ett av de vanligaste hjälpmedlen för att underlätta strukturen av ett projekt i iOS är MVC. MVC är ett design mönster för att strukturera och separera kod till mindre och mer hanterbara komponenter.

# Förberedelser

#### Länkar

* Guider 
	* [Start Developing iOS Apps (Swift)][developing-ios-apps]
	* [Cocoa Core Competencies - Model object][model-object]
	* [Cocoa Core Competencies - MVC][mvc]
	* [The Swift Programming Language][swift-programming-language]
* Dokumentation
	* [UITextField][uitextfield]
	* [UITextFieldDelegate][uitext-field-delegate]
	* [NSAttributedString][nsattributed-string]

[swift-programming-language]:https://developer.apple.com/library/ios/documentation/Swift/Conceptual/Swift_Programming_Language/index.html#//apple_ref/doc/uid/TP40014097

[model-object]:https://developer.apple.com/library/ios/documentation/General/Conceptual/DevPedia-CocoaCore/ModelObject.html#//apple_ref/doc/uid/TP40008195-CH31-SW1

[mvc]:https://developer.apple.com/library/ios/documentation/General/Conceptual/DevPedia-CocoaCore/MVC.html#//apple_ref/doc/uid/TP40008195-CH32-SW1

[developing-ios-apps]:https://developer.apple.com/library/ios/referencelibrary/GettingStarted/DevelopiOSAppsSwift/index.html#//apple_ref/doc/uid/TP40015214-CH2-SW1

[uitextfield]:https://developer.apple.com/library/ios/documentation/UIKit/Reference/UITextField_Class/

[uitext-field-delegate]:https://developer.apple.com/library/ios/documentation/UIKit/Reference/UITextFieldDelegate_Protocol/

[nsattributed-string]:https://developer.apple.com/library/mac/documentation/Cocoa/Reference/Foundation/Classes/NSAttributedString_Class/


## Uppgift

I den här uppgiften ska du få testa hur det är att bygga en komplett applikation från början till slut. Applikationen kommer vara ett ["Hänga gubben"][hänga-gubbe] spel. Du kommer att behöva bygga ett GUI och och spelets logik. Du ska utgå från "Single View Application" template i Xcode. Du får själv välja om du vill utveckla till iPhone eller iPad (båda behövs ej).

[hänga-gubbe]:https://sv.wikipedia.org/wiki/Hänga_gubbe

Applikationen ska bestå av minst tre vyer. En start skärm, en skärm för inmatning av av ett ord och en spelskräm. Hur användargränssnittet kommer se ut är helt fritt så så länge kraven nedan uppfylls.

- Startskärm
	- Ska innehålla spelets title
	- Ha en knapp för att starta spelet
- Inmatningsskärm
	- Ett textfält som användaren kan matta in ett ord. 
	- Det ska framgå att det inmatade ordet kommer användas i spelet på nästa skärm
- Spelskärm
	- Ett textfält som användaren kan matta in ett ord.
	- Det ska framgå hur många gissningar användaren har gjort
	- Det ska framgå hur många gissningar det finns kvar innan spelet är slut
	- Det ska framgå hur vilka ord som användaren har gissat och på vilken plats de finns i ordet.

Att bygga ett användargränssnittet är är bara halva uppgiften och resten av uppgiften är att bygga logiken för applikationen. Spellogiken ska vara separerad till modeltyper. Det ska inte finnas någon spel logik i vy-kontrollerna utan bara kod för att tolka och sedan förmedla vad som händer till modeltyperna.

Försök inte göra ett avancerat användargränssnittet om du inte känner att du har tid. Att användargränssnittet är enkelt och tydligt är viktigare än animationer och former.

Denna uppgift ska göras i Swift. Det betyder att all kod som lämnas in ska vara skriven i Swift.

## Redovisning

Packa ihop projektet och skicka per mail till din handledare. Ange '725G72 - Laboration 6 - Redovisning' som ämne. Skriv med vad du har för LiU-id (t ex abcde123) om du inte mailar från din studentadress.
