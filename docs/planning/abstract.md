# Generierung von Schnittstellen-Tests für eine Microservice-Architektur anhand eines DDD-Models

Im Rahmen dieser Bachelor-Arbeit soll ein Generator geplant und entwickelt werden, der es ermöglicht anhand eines Micro-Service Modells nach dem Domain Driven Design Schnittstellentests für eine Domäne zu generieren.

Zunächst sollen die Prinzipien und Ideen hinter dem DDD näher beleuchtet werden, um die mögliche Tiefe der zu extrahierenden Informationen aus einem solchen Modell zu erfassen.

Im zweiten Teilabschnitt werden dann die gängigsten Methoden und Praktiken, sowie Frameworks, die beim testen von Microservice-Architekturen eingesetzt werden, identifiziert und weitere Anforderungsanalysen für diese durchgeführt, um die mögliche Bandbreite der Generierung abzugrenzen.

Zum weiteren vorgehen ist ein tieferes Verständnis der zu Generierung eingesetzten Sprache Barrakuda, welche von Martin Kurz in seiner Masterarbeit entwickelt wurde, nötig. Diese wird in einem weiteren Abschnitt erklärt und anhand von Beispielen demonstriert.

Im letzten Schritt der Vorbereitung soll dann aus den zusammengetragenen Informationen festgestellt werden, für welches Framework ein generativer Ansatz zum erstellen von Testfällen am sinnvollsten ist. Außerdem sollen eventuell benötigte Erweiterungen und/oder Änderungen von 'Barrakuda' festgelegt werden, die für den generativen Ansatz von nöten sind.

Im praktischen Teil der Arbeit werden dann zunächst einige Refernzimplementierungen definiert, anhand derer im nächsten Teilschritt die Generierung von den Tests unter zuhilfename von Barrakuda und den im vorherigen Teil festgelegten Änderungen in die Tat umgesetzt wird.