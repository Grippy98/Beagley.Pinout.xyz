Dieser Anschluss kann auch als [UART](https://de.wikipedia.org/wiki/Universal_Asynchronous_Receiver_Transmitter) Empfangsleitung genutzt werden. Empfangen heißt im Englischen 'receive' - daher die Bezeichnung RXD. 

Er wird im Allgemeinen auch als serielle Schnittstelle bezeichnet. Über diesen Pin empfängt der Pi standardmäßig Zeichen und 
leitet sie an die Kommandozeile weiter. Zusammen mit TXD kannst Du so Deinen Pi über die Kommandozeile mit der seriellen Schnittstelle steuern.

Die serielle Schnittstelle ist sehr nützlich, wenn Du z.B. einen Arduino oder ein Propeller Board mit Deinem Pi verbinden möchtest. Dabei musst Du allerdings
darauf achten, dass Du vorher die serielle Kommandozeile (Console) in der raspi-config deaktivierst.

Die serielle Schnittstelle benötigst Du auch, wenn Du den Pi ohne ein Display ("headless") aufsetzen möchtest, denn dann kommst Du so auch an die Kommandozeile ran.

[Erfahre mehr über UART](/pinout/uart)
