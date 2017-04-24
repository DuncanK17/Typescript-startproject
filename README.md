# Voorbereiding PRG04

In PRG04 gaan we werken met Typescript en github. Installeer alvast de benodigde tools en kijk of je "Hello World" kan maken.

## Herhaling Javascript Basics
Zorg dat je onderstaande javascript basics beheerst.
- Scope
- Loop
- Array
- Function
- Function arguments
- Function return value

[MDN Javascript basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)

## Typescript en Code Editor
- [Installeer Node en NPM](https://nodejs.org/en/)
- [Installeer Typescript](https://www.typescriptlang.org)
- [Download Visual Studio Code](https://code.visualstudio.com)

## Werken met GitHub
- [Installeer git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- [Maak een github account](https://www.github.com)
- [Git tutorial](https://try.github.io/)

### Fork
- Als je een fork van deze repository maakt heb je meteen je eigen code online staan. 
- Doe `git clone` van je eigen fork naar je lokale machine 
- In Visual Studio Code kan je in het GIT venster `commit` en `sync` doen om je code weer online te plaatsen

### Lokaal
- Clone deze repository rechtstreeks in je werkfolder, of download de ZIP file. 
- Je kan de git folder daarna weg gooien omdat je niet meer terug kan pushen naar deze repository. Open de Visual Studio Code Terminal en typ: `rm -rf .git`

## Localhost instellen
Je test een project altijd via http://localhost/.../project, en niet via file://project/. Localhost kan je aan zetten met:
- MAMP of XAMPP (als je dit al eerder had geïnstalleerd)
- [OS X native localhost](https://coolestguidesontheplanet.com/get-apache-mysql-php-and-phpmyadmin-working-on-macos-sierra/)
- [Windows native localhost](https://msdn.microsoft.com/en-us/library/ms181052(v=vs.80).aspx)

Als je geen localhost op je machine hebt draaien kan je een tijdelijke server voor je project starten met:
- [HTTP Server with Python](http://www.pythonforbeginners.com/modules-in-python/how-to-use-simplehttpserver/)
- [HTTP Server with Node](https://www.npmjs.com/package/http-server)
- [HTTP Server with automatic browser refresh](https://www.browsersync.io)

## Typescript compiler in terminal
- Maak een nieuw javascript bestand met de naam `test.js`
- In het bestand zet je de code `console.log('hello world')`
- Open een terminal window in de map van het bestand.
- Compileer javascript naar typescript met `tsc test.js`

## Visual Studio Code

### Download project
- Maak een projectmap voor PRG4. Maak daarin een map voor week 0 `projecten/prg4/week0/`
- Download de ZIP van dit testproject (zie 'werken met github').

### Openen in browser
- Open de DIST folder in een browser via localhost: http://localhost/projecten/prg4/week0/dist/

### VS Code compiler
- Open Visual Studio Code
- Ga naar **File > Open Folder**. Open de week0 folder die je net gecloned hebt. Zie screenshot!
- Let op dat de root **Folder** in VS Code je projectmap is. Hierin staan al je config en build settings.
- Verwijder de .js file uit de DIST folder.
- Open 'message.ts' in de DEV folder, maak een wijziging, en druk op CMD+SHIFT+B (mac) of CTRL+SHIFT+B (win)
- Kijk of het .js bestand opnieuw wordt gegenereerd.
- Refresh de browser om te zien of je wijziging is doorgevoerd.

![img](http://i.imgur.com/5LEA1E1.png)

### Uitleg bestanden
- De DIST folder bevat de website : html, css en javascript. De javascript files worden automatisch gegenereerd.
- De DEV folder bevat de typescript files. Dit zijn de files waarin je gaat programmeren.
- tsconfig.json bevat instellingen voor het compileren naar javascript.
- tasks.json bevat het 'build' commando. Dit voer je uit met CMD+SHIFT+B

## Links
- [Typescript Documentation](https://www.typescriptlang.org)
- [Typescript Getting Started](https://basarat.gitbooks.io/typescript/content/docs/getting-started.html)
- [New features in ES6](http://es6-features.org)
- [MDN Javascript basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)
- [Javascript Timeline](https://en.wikipedia.org/wiki/ECMAScript)
- [Browser support for new features](http://caniuse.com)
