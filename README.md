# Cortana Voice Command Definitions

## Goal

This repository contains the voice command definition file for [2Day](www.2day-app.com) the best productivity app for Windows.
The voice command definitions are described in a simple XML file (VoiceCommands.xml) that is embedded in 2Day. This what enables Cortana support in the app.

## Getting started

Best way to get started is to use existing commands as reference.

Syntax

- [word] describe an optional word
- {item} map to an item described at the bottom of the definition

At run-time, 2Day fill the item lists (views, folders, smart views, contexts, tags) with the availables items in user's data.

## Contribute

Please submit pull-requests to add new language or improve commands on existing commands.
Once a pull-request is merged in this repository, the voice commands will be included in the next update of 2Day.
