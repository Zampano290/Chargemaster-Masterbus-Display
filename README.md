# Chargemaster-Masterbus-Display

Der Mastervolt Chargemaster (z.B. 12/35, 12/50) verfügt über eine Masterbus Schnittstelle, die an ein Maservolt Easy5 oder RemoteDisplay verbunden werden kann.
Das RemoteDisplay unterstützt zur Zeit noch nicht den Chargemaster.
Über das Easy5 werden aber auch Kaum brauchbare Daten angezeigt.

Über einen Arduino mit CAN Schnittstelle (MCP2515) kann über Masterbus kommuniziert werden und die Daten über ein Nextion Display ausgegeben bzw konfiguriert werden.
