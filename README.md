# Häfele Connect Mesh for Homey — issues and support

> [!IMPORTANT]
> **Unofficial app.** The Häfele Connect Mesh app for Homey is not made, endorsed or supported by Häfele. Please do not contact Häfele about it — report it here instead.

This repository is the public issue tracker for the Homey app **Häfele Connect Mesh**, which controls Häfele Connect Mesh lighting directly over Bluetooth Mesh, without a Häfele gateway.

## Report a problem or ask a question

[Open an issue](../../issues/new/choose) and pick a template: **Bug report**, **Feature request** or **Question**. English or Dutch is fine.

## Keep your network keys private

> [!CAUTION]
> **Never post your `.connect` file, or any part of it.** It contains the keys of your lighting network: anyone with it can control your lights.

What *is* safe to share: a screenshot of the **Diagnostics** page in the app settings (Homey app › Settings › Apps › Häfele Connect Mesh). It shows the connection, signal strength, mesh addresses and the result of a network scan — never key material.

## Before you report

- Is at least one lamp switched on and within Bluetooth range of your Homey Pro?
- A lamp accepts one Bluetooth connection at a time: is your phone connected to that lamp with the Häfele app? Close the app, or use the *Release* Flow card.
- Signal weaker than −80 dBm in Diagnostics? Move Homey closer to a lamp.

---

## Nederlands

**Niet-officiële app**: niet gemaakt, goedgekeurd of ondersteund door Häfele. Meld problemen hier, niet bij Häfele.

[Maak een issue aan](../../issues/new/choose) met een van de sjablonen; Nederlands mag. **Plak nooit (een deel van) je `.connect`-bestand**: daarin staan de sleutels van je verlichtingsnetwerk. Een schermafbeelding van de *Diagnose*-pagina in de app-instellingen is wel veilig.
