# DistributedSystems
Ziel
Sie sollen ein Mashup entwickeln, welches verschiedene Kennzahlen rund um eine
Kryptowährung übersichtlich zur Verfügung stellt. Hierzu sollen Sie unterschiedliche Quellen
berücksichtigen und aggregieren.
Aufgabenbeschreibung
Ihre Aufgabe ist es, ein MashUp zu entwickeln und zu implementieren, das auf bereits
bestehenden Diensten basiert.
Wenn Sie Ihr MashUp entwickeln, sollten die folgenden Anforderungen erfüllt sein:
• Es sollte verschiedene Datenquellen kombiniert werden.
• Ihre Lösung soll irgendwo gehostet werden, damit sie im Web zugreifbar ist.
• Sie müssen ein Backend-System implementieren, das zumindest Daten von zwei
verschiedenen Diensten aggregiert und den architektonischen Ansatz verwendet, um
mit der Same-Origin-Directive umzugehen. Diese aggregierten Daten sollten ebenfalls
in dem MashUp visualisiert werden.
Das Mashup, das Sie implementieren sollen, wird ein Finanz-Dashboard sein. Hier sollen Sie
Daten über eine Kryptowährung namens Waves integrieren. Der erste Dienst, den Sie
integrieren sollen, sind die Marktpreise, die z. B. hier verfügbar sind:
https://wavescap.com/info/api
Hier implementieren Sie mindestens einen MA (Moving Average) und das Sharpee Ratio für
das Paar Waves / USD (weitere Kennzahlen können Sie gerne implementieren). Zusätzlich
sollten Sie die aktuelle Stimmung gegenüber der Kryptowährung Waves berechnen, indem
Sie Tweets die folgende Hashtags / Benutzer beinhalten analysieren:
@waves.tech
@SignatureChain
@wavesprotocol
@neutrino_proto
$Waves
$USDN
@sasha35625
Sie können hierzu gerne fertige API’s (sowohl im Web als auch als API für eine gängige
Programmiersprache) zur Sentimentanalyse verwenden. Die Implementierung einer eigenen
Sentimentanalyse ist nicht notwendig.
Zusätzlich sollten Sie Ihre eigene Idee umsetzen, wie Sie die auf PyWaves verfügbaren
Zinsdaten für verschiedene Finanzprodukte auf der Waves-Plattform in Ihr Mashup
integrieren können.
