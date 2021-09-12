## Dokumentation einer ioBroker HA-Umgebung

Nach dem Durcharbeiten dieser Anleitung steht eine (virtuelle) HA-Umgebung auf Basis von 3 Proxmox-Nodes zur Verfügung. Innerhalb dieser Nodes werden die Daten der Container auf einem Shared-Storage des Typs GlusterFS verfügbar gehalten. ioBroker ist konfiguriert als file(redis)/objects(redis) und hat Zugriff auf 3 Redis-Server-Nodes mit 6 Redis-Server-Prozessen (je Container ein Prozess für die file- und objects-Datenbank). Redis-Sentinel überwacht die Redis-Nodes und stellt die Verfügbarkeit dieser sicher.

Im ioBroker-Forum kann unter folgenden Link darüber Diskutiert werden. Mitarbeit ist erwünscht :)

https://forum.iobroker.net/topic/47478/dokumentation-einer-proxmox-iobroker-redis-ha-umgebung

## License

The MIT License (MIT)

Copyright (c) 2021 darkiop

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
