ToDos (throughout the project):

* Review code basis so far in comment boxes
* Take on open ToDos, Notes and Errors
* Keep class diagram updated
* Keep updating doc-book
* Write down your questions of the last week and commit them (including answers) after next meeting/call
* Please document your code (!) (in-code docu)

ALL DOCUMENTATION IS TO DO IN ENGLISH (except doc-book)

------------------------------------------------------------------------------------------------------------------------

ToDos 08/16/2017

MARK TODOS or QUESTIONS as "ToDo: ......" in the code, so that they can be found! Do not just write them there, but MARK THEM!

* ToDos in code (e.g. answer questions in comments, correct the logic, ...)
* Testing
* DocBook
* Presentation slides (inclusive class and sequence diagram, architecture/technology overview, ...)
* Bet text field before displaying the cards
* GUI (e.g.: Hit, stand, insurance buttons need to be clickable only when possible)
* Error pages displaying to user (--> see ToDos in code)
* Review/test concatenated game logic
* Update class diagram
* CSS for start pages
* At least 1 player has to be playing when starting a new game (currently it is possible to start a new game without anyone playing)
* Check for players actually playing on the table (name != "" and balance >= 1 and bet > 0 and bet <= balance) in all relevant functions (e.g. setActivePlayer, checkWinningStatusA, after bet round when activePlayer is 1 again, ...)
* After deleting a player, the other players should remain on their seats at the table (--> no right shifting in GUI)
* Dealer gets his first two cards AFTER the bet-round (at the moment, the dealer gets 2 x 2cards due to the bet-round)
* Old ToDos
* Kartenrückseite

Lower prio:
* (Dynamic adding of players during game in next round should be possible)
* (Casino.xqm (define the rest of the elements and attributes))
* (Bet round with coins)


------------------------------------------------------------------------------------------------------------------------

ToDos 08/11/2017

MARK TODOS or QUESTIONS as "ToDo: ......" in the code, so that they can be found! Do not just write them there, but MARK THEM!

* Insurance function implementation to review/finish
* ToDos in code (e.g. answer questions in comments, implement/discuss need of constructors, correct the logic, ...)
* Testing
* DocBook (no compile errors and no typos)
* Presentation
* Bet vor Ausgabe der Karten
* GUI auf Spiel anpassen (e.g.: hit, stand, bet, insurance buttons need to be integrated in GUI, ...)
* Error pages displaying to user
* concat all the game logic (--> function calls sequence)
* Update class diagram
* Old ToDos

Lower prio:
* (Dynamic adding of players during game in next round should be possible)
* (Casino.xqm (define the rest of the elements and attributes))


------------------------------------------------------------------------------------------------------------------------

ToDos 07/21/2017

* Transform dummy functions into fully-developed ones (hit, stand, ...) ---> in player.xqm
* Implement missing functions (insurance, ...) ---> in player.xqm
* Get XSLT for GUI working (1st step is without responses, 2nd is with responses)
* (eventually start testing)
* casino.dtd has to be finished

------------------------------------------------------------------------------------------------------------------------

ToDos 07/14/2017

* Take on open ToDos and Notes
* Keep class diagram updated
* Implement missing functions (hit, stand, insurance, ...)
* Get protoype for GUI working (1st step is without responses, 2nd is with responses)

------------------------------------------------------------------------------------------------------------------------

ToDos 06/28/2017

XML Zustandsbeschreibung
* Initial Zustand: leerer Tisch, Spiel muss noch gestartet werden, Dealer sitzt immer da
* Geld setzen vor dem Karten ausgeben
* Karten ausgegeben: Dealer hat eine Karte, Spieler haben zwei
* Auswahl: Versicherung, hit, Stand
* Mindestens ein Spieler hat mehr als 2 Karten
* Spieler hat Keine Karten und der Einsatz ist weg
* Dealer hat beide Karten umgedreht

SVG / Grafiken
* Karten
* Coins
* Buttons
* Tisch
* Avatar

BaseX

Jetty Server

DocBook
