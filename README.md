# Hangman app

## Bygga ett användargränssnittet och använda MVC

Att bygga en iOS applikation kräver ofta att man behärskar flera färdigheter så som att strukturera kod och bygga ett grafiskt användargränssnitt. Att bygga ett snyggt och enkelt grafiskt användargränssnitt är inte enkelt och kräver att programmeraren har goda kunskaper om ramverkets möjligheter och begränsningar.

Enkel och tydlig kod är en viktigt komponent för en applikation som är tänkt att utvecklas och hållas buggfri. För att uppnå detta krävs struktur och planering. Ett av de vanligaste hjälpmedlen för att hålla en bra struktur i ett iOS-projekt är MVC. MVC är ett designmönster för att strukturera och separera kod till mindre och mer hanterbara komponenter.

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

I den här uppgiften ska du få testa hur det är att bygga en komplett applikation från början till slut. Applikationen kommer vara ett ["Hänga gubben"][hänga-gubbe]-spel. Du kommer att behöva bygga ett GUI och och spelets logik. Du ska utgå från "Single View Application" template i Xcode. Du får själv välja om du vill utveckla till iPhone eller iPad (båda behövs ej).

[hänga-gubbe]:https://sv.wikipedia.org/wiki/Hänga_gubbe

Applikationen ska bestå av minst två vyer. En startskärm och en spelskräm. Hur användargränssnittet kommer se ut är helt fritt så så länge kraven nedan uppfylls. Orden som användaren ska gissa på ska slumpas fram från en hårdkodad lista som man får välja själv. Om man vill ladda orden från en extern källa så som fil eller en server så är det okej det också.

- Startskärm
	- Ska innehålla spelets titel
	- Ha en knapp för att starta spelet
- Spelskärm
	- Ett textfält där användaren kan mata in bokstäver
	- Det ska framgå hur många gissningar användaren har gjort
	- Det ska framgå hur många gissningar det finns kvar innan spelet är slut
	- Det ska framgå vilka bokstäver användaren har gissat på, och på vilken plats de finns i ordet

Att bygga ett användargränssnitt är är bara halva uppgiften och resten av uppgiften är att bygga logiken för applikationen. Spellogiken ska vara separerad till modeltyper. Det ska inte finnas någon spellogik i vy-kontrollerna utan bara kod för att tolka och sedan förmedla vad som händer till modeltyperna.

Försök inte göra ett avancerat användargränssnittet om du inte känner att du har tid. Att användargränssnittet är enkelt och tydligt är viktigare än animationer och former.

Denna uppgift ska göras i Swift. Det betyder att all kod som lämnas in ska vara skriven i Swift.

## Redovisning

Packa ihop projektet och skicka per mail till din handledare. Ange '725G72 - Laboration 6 - Redovisning' som ämne. Skriv med ditt LiU-id (t ex abcde123) om du inte mailar från din studentadress.
