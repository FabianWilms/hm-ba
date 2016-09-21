# Generierung von Schnittstellen-Tests für eine Microservice-Architektur anhand eines DDD-Models

Ein sehr wichtiger Bestandteil in der Definition of Done der Landeshauptstadt München ist eine umfassende Testabdeckung. Unit- und Integrations Tests sind fest in viele Entwicklungsprozesse integriert und finden besonders auch in Agilen Entwicklerteams großen Zuspruch. Allerdings sind Tests auch dafür verantwortlich, dass die Aufwände für ein Projekt sich mindestens verdoppeln und somit nicht nur zeitliche, sondern auch finanzielle Kostenfaktoren sind.
Dieser zeitliche Aufwand wird, trotz des Bewusstseins dafür, häufig bei Projekten ignoriert, sodass häufig erst am ende einer Entwicklung viel zu wenig Zeit in die Tests investiert wird, und somit die Softwarequalität beim ausliefern leidet.

Bei der LHM wurde im vergangenen Jahr das Softwareprojekt Barrakuda entwickelt, welches anhand eines nach DDD aufgebauten Domänen-Modells Microservice Architekturen generieren kann. Die ursprüngliche Idee baute direkt auf dem Problem, welches im ersten Absatz geschildert wurde, auf: Software anhand von simplen Modellen generieren, um möglichst viel Zeit beim entwickeln von "Boilder Plate"-Code einzsuparen, und die Software-Qualität nicht nur durch ersparte Entwicklungszeit, sondern auch durch homogene Projektstrukturen in allen generierten Systemen, und damit erhöhte Wartbarkeit, zu verbessern.

Im Rahmen dieser Bachelor-Arbeit soll die These geprüft werden, dass sich aus einem reinen Domänen-Modell genügend Informationen zum Testen eines Microservice-Frameworks extrahieren lassen, um eine ausreichende Testabdeckung für die generierten Services zu bieten.

Zunächst sollen dafür die Prinzipien und Ideen hinter dem DDD näher beleuchtet werden, um die mögliche Tiefe der zu extrahierenden Informationen aus einem solchen Modell zu erfassen.

Im zweiten Teilabschnitt werden dann die gängigsten Methoden und Praktiken, sowie Frameworks, die beim testen von Microservice-Architekturen eingesetzt werden, identifiziert und weitere Anforderungsanalysen für diese durchgeführt, um die benötigte Bandbreite der generierten Tests abzugrenzen.

Zum weiteren vorgehen ist ein tieferes Verständnis der zu Generierung eingesetzten Sprache Barrakuda, welche von Martin Kurz in seiner Masterarbeit entwickelt wurde, nötig. Diese wird in einem weiteren Abschnitt erklärt und anhand von Beispielen demonstriert.

Im letzten Schritt der Vorbereitung soll dann aus den zusammengetragenen Informationen festgestellt werden, für welches Framework ein generativer Ansatz zum erstellen von Testfällen am sinnvollsten ist. Außerdem sollen eventuell benötigte Erweiterungen und/oder Änderungen von 'Barrakuda' festgelegt werden, die für den generativen Ansatz von nöten sind.

Im praktischen Teil der Arbeit werden dann zunächst einige Refernzimplementierungen definiert, anhand derer im nächsten Teilschritt die Generierung von den Tests unter zuhilfename von Barrakuda und den im vorherigen Teil festgelegten Änderungen in die Tat umgesetzt wird.
