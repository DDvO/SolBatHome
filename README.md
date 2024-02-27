# SolBatHome
Home automation for small solar power systems, optionally with battery

## Overview

This is a collection of configuration files for the
home automation software [Home Assistant](https://www.home-assistant.io/)
using data obtained from digital metering devices for electric power such as
Shelly (Pro) 3EM and Shelly Plus 1PM and from an OpenDTU for Hoymiles inverters
via MQTT.

This can be used to log per hour in a CSV file
the energy consumed and possibly produced by a PV system.
This includes also the directly used solar energy (own consumption),
the overall energy balance (net metering),
as well as the energy imported and exported (two-way metering).
In case a buffer battery is present,
also the energy charged and discharged can be included, as well as
the state of charge of the energy storage at the end of the given hour.

Moreover, all power data can be logged each second:
the balance at the distribution board per phase, the total load by the
household, as well as PV production, charge, and discharge power if present.
Also a per-minute load and PV production profile can be produced,
to use for instance with the PV and energy storage system simulator
[SolBatSim](https://github.com/DDvO/SolBatSim).


## Überblick

Dies ist eine Sammlung von Konfigurationsdateien für die
Hausautomatisierungs-Software [Home Assistant](https://www.home-assistant.io/)
zur Nutzung von Daten, die von
digitalen Strom-Leistungsmessgeräten wie Shelly (Pro) 3EM und Shelly Plus 1PM
und ggf. einer OpenDTU für Hoymiles Wechselrichter über MQTT geliefert werden.

Damit kann man die vom Haushalt verbrauchte und ggf. mit einer PV-Anlage
erzeugte Energie stundenweise in einer CSV-Datei protokollieren lassen,
inklusive des dabei erzielten PV-Eigenverbrauchs, der Gesamt-Energiebilanz,
sowie der importierten und exportierten Energie,
wie sie auch von einen Zweiwegezähler geliefert wird.
Bei Verwendung eines Batteriespeichers
kann auch die gespeicherte und entladene Energie protokolliert werden
sowie der Ladezustand jeweils zum Ende der vollen Stunde.

Außerdem lassen sich die Leistungsdaten (Bilanz am Unterverteiler pro Phase,
saldierte Last, sowie ggf. PV-Leistung, Speicher-Lade- und Entladeleistung)
pro Tag sekundengenau protokollieren
sowie ein minutengenaues Haushalts-Lastprofil und PV-Profil erstellen,
z.B. zur Verwendung mit dem PV- und Speicher- Simulator
[SolBatSim](https://github.com/DDvO/SolBatSim).

<!--
Local IspellDict: german8
LocalWords: pl load csv yield configuration yaml
-->
