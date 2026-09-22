# Battery Pack Wiring

How six 18650 cells become one 21 Ah battery, and how that battery reaches the
rest of a polar weather probe through two wires and one plug.

**Read it → https://ildarcheg.github.io/battery-pack-wiring/**

## What this is

A build page for the battery pack of **meteo**: solar-assisted, ESP32-based
weather probes that batch hourly readings and forward them over the Iridium
satellite network. Three are built for the 2026/27 austral season — two land
stations beside reference series on King George Island, and one expendable buoy
released mid-Drake Passage.

It shows what joins what, in what order, and which of those joints carries the
whole probe's current. Companion to the
[Buoy Parts Book](https://ildarcheg.github.io/buoy-parts-book/), which carries
the same power source onward from the plug.

It is a school co-build project.

## Read the safety notes, not just the drawing

The page opens with them rather than ending on them. Two matter most: the six
cells must be state-of-charge matched before they are joined, because nothing
in the design limits the balancing inrush between mismatched neighbours; and
nothing is soldered or welded to a cell anywhere in the build — every joint
lands on a contact.

## About this repository

This repo holds **one published page and nothing else**. It is a mirror, not a
source: `index.html` is generated from the working repository, where every
figure has an owning document that argues it. Corrections belong there — an
edit made directly here is overwritten by the next publish.

The page is self-contained: no JavaScript, no images, no analytics, no cookies.
It fetches web fonts from Google Fonts and falls back to system fonts offline.
Save the file and it still works.

## Status

The design is not finished, and the page says so where it matters. Five things
are marked open rather than guessed — including that the bus-bar channel is
read off the model rather than specified, and that the twelve cell contacts
have no retention design yet.

## Licence

[CC BY 4.0](LICENSE). Reuse it, adapt it, publish it, with credit to
**SouthPing** (<https://southping.org/>) and a link back. Source code in the
project is Apache-2.0. Manufacturers' datasheets and product photographs
remain theirs and are not covered by this grant.
