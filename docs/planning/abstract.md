# Generierung von Schnittstellen-Tests für eine Microservice-Architektur anhand eines Barrakuda-Models

Ein sehr wichtiger Bestandteil in der Definition of Done der Landeshauptstadt München ist eine umfassende Testabdeckung. Unit- und Integrations Tests sind fest in viele Entwicklungsprozesse integriert und finden besonders auch in agilen Entwicklerteams großen Zuspruch. Allerdings sind Tests auch dafür verantwortlich, dass die Aufwände für ein Projekt sich mindestens verdoppeln und somit nicht nur zeitliche, sondern auch finanzielle Kostenfaktoren sind.
Dieser zeitliche Aufwand wird, trotz des Bewusstseins dafür, häufig bei Projekten ignoriert, sodass häufig erst am Ende einer Entwicklung viel zu wenig Zeit in die Tests investiert wird, und somit die Softwarequalität beim Ausliefern leidet.

Bei der LHM wurde im vergangenen Jahr das Softwareprojekt Barrakuda entwickelt, welches anhand eines nach Domain Driven Design (DDD) aufgebauten Domänen-Modells Microservice Architekturen generieren kann. Die ursprüngliche Idee baute direkt auf dem Problem, welches im ersten Absatz geschildert wurde, auf: Software anhand von simplen Modellen generieren, um möglichst viel Zeit beim Entwickeln von "Boiler Plate"-Code einzsuparen, und die Software-Qualität nicht nur durch ersparte Entwicklungszeit, sondern auch durch homogene Projektstrukturen in allen generierten Systemen, und damit erhöhte Wartbarkeit, zu verbessern.

Im Rahmen dieser Bachelor-Arbeit soll die These geprüft werden, dass sich aus einem reinen Domänen-Modell genügend Informationen zum Testen eines Microservice-Frameworks extrahieren lassen, um eine ausreichende Testabdeckung für die generierten Services zu bieten.

Hierzu ist ein tieferes Verständnis der zu Generierung eingesetzten Sprache Barrakuda, welche von Martin Kurz in seiner Masterarbeit „Verbesserung des Softwareentwicklungsprozesses der Landeshauptstadt München durch modellgetriebene Softwareentwicklung“ entwickelt wurde, nötig. Diese wird in einem weiteren Abschnitt erklärt und anhand von Beispielen demonstriert. Um die Verbindung von Barrakuda zum DDD hervorzuheben, wird dies im weiteren Vorgehen näher beleuchtet.

Im zweiten Teilabschnitt werden dann die gängigsten Methoden und Praktiken, sowie Frameworks, die beim Testen von Microservice-Architekturen eingesetzt werden, identifiziert und weitere Anforderungsanalysen für diese durchgeführt, um die benötigte Bandbreite der generierten Tests abzugrenzen.

Im letzten Schritt der Vorbereitung soll dann aus den zusammengetragenen Informationen festgestellt werden, für welches Framework ein generativer Ansatz zum Erstellen von Testfällen am sinnvollsten ist. Außerdem sollen eventuell benötigte Erweiterungen und/oder Änderungen von Barrakuda festgelegt werden, die für den generativen Ansatz von Nöten sind.

Im praktischen Teil der Arbeit werden dann zunächst einige Referenzimplementierungen definiert, anhand derer im nächsten Teilschritt die Generierung von den Tests unter Zuhilfenahme von Barrakuda und den im vorherigen Teil festgelegten Änderungen in die Tat umgesetzt wird.
