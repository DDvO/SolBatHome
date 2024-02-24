# SolBatHome
Home automation for small solar power systems, optionally with battery

## Overview

This is a collection of configuration files for the
home automation software [Home Assistant](https://www.home-assistant.io/).
With digital metering devices for electric power such as a Shelly (Pro) 3EM,
it can be used to produce load profiles, for instance for the PV and energy
storage system simulator [SolBatSim](https://github.com/DDvO/SolBatSim).\
This way, also a further CSV file can be produced
with one line per hour containing the time,
the energy consumed, produced, own use, balance, imported, exported, charged,
and discharged, each of which accumulated during the given hour, as well as the
state of charge of the storage battery (if present) at the end of the hour.

## Überblick

Dies ist eine Sammlung von Konfigurationsdateien für die
Hausautomatisierungs-Software [Home Assistant](https://www.home-assistant.io/).
Zusammen mit digitalen Energiemessgeräten wie einem Shelly (Pro) 3EM
können Lastprofile fü den eigenen Haushalt erstellt werden, z.B. für den
PV-Solar-Eigenverbrauchs-Simulatior [SolBatSim](https://github.com/DDvO/SolBatSim).\
Außerdem ermöglichen sie
die stundenweise Protokollierung der verbrauchten und ggf. erzeugten
Energie, des Eigenverbrauchs, der Gesamt-Energiebilanz, sowie der importierten
und exportierten Energie, wie sie auch von einen Zweiwegezähler geliefert wird,
und bei Verwendung eines Batteriespeichers auch der geladenen und entladenen Energie
sowie des Ladezustands jeweils zum Ende der vollen Stunde.

<!--
Local IspellDict: german8
LocalWords: pl load csv yield configuration yaml
-->
