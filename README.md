==========================================
Netzob : Inferring Communication Protocols
==========================================

Description
===========

Netzob is an opensource tool for reverse engineering, traffic generation
and fuzzing of communication protocols. This tool allows to infer the message format (vocabulary)
and the state machine (grammar) of a protocol through passive and active processes.
Its objective is to bring state of art academic researches to the operational field,
by leveraging bio-informatic and grammatical inferring algorithms in a semi-automatic manner.

Netzob is suitable for reversing network protocols, structured files and system and
process flows (IPC and communication with drivers and devices).
Dedicated modules are provided to capture and import data in multiple contexts (network, file and process data acquisition).
Once inferred, a protocol model can afterward be exported to third party tools (Peach, Scapy, Wireshark, etc.)
or used in the traffic generation engine, to allow simulation of realistic and controllable communication endpoints and flows.

Netzob handles different types of protocols: text protocols (like HTTP and IRC), delimiter-based protocols,
fixed fields protocols (like IP and TCP) and variable-length fields protocols (like TLV-based protocols).

Repository
==========

Netzob is available on [https://github.com/netzob/netzob](https://github.com/netzob/netzob).