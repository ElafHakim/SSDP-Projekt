# SSDP (Simple Service Discovery Protocol)

In dieser Aufgabe besteht die Anforderung, einen SSDP6-Client (Simple Service Discovery Protocol) zu entwickeln. Dieser Client hat die Aufgabe, nach verfügbaren Geräten im lokalen Netzwerk zu suchen und eine Liste dieser erkannten Geräte zu verwalten. Die Implementierung muss nicht exakt den nachfolgenden Vorschlägen entsprechen, sollte jedoch die gleiche Funktionalität bieten und dieselben Befehle unterstützen.
---
Es wird empfohlen, drei Threads zu implementieren:

1. **Listener-Thread**: Zuständig für den Empfang von Datagrammen.
2. **Worker-Thread**: Übernimmt die Verarbeitung der empfangenen Datagramme.
3. **User-Thread**: Liest Eingaben des Benutzers und führt die entsprechenden Aktionen aus.
---

