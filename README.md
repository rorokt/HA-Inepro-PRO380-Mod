# HA-Inepro-PRO380-Mod
Inepro PRO380-Mod integráció Home Assistantba

Beállítások:
1. A fogyasztásmérőn:
parity: N
address: 2

2. A modbus.yaml fájt be kell másolni a /config könyvtárba

3. Configuration.yaml-be:
modbus: !include modbus.yaml

4. reboot
