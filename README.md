# Eco-Libre Life-Line

This repo contains designs for an off-grid community's water system.


<img src="docs/images/life-line_2025.10.jpg?raw=true" alt="Screenshot of CAD file"></a>

# Design Goals

The water system should be:

1. Low-Maintenance
1. Hygienic

## Low-Maintenance

**Low-Maintenance** means that low-tech automation and well-engineered, self-cleaning systems should be employed so that the system only needs routine maintenance once or twice per year.

## Hygienic

**Hygienic** means that the water stored in the clean water tanks and delivered to sinks should free of contamination (bacteria, parasites) and be safe to drink.

## Size

**Pico (3-person)** (the smallest Eco-Libre Life-Line water system) should provide sufficient water for 3-people.

**Nano (15-person)** The small-size system should be horizontally scalable by multiplying the number of filters and tanks to provide sufficient water for a 15-person community

**Micro (30-person)** To handle a community of up to 30-people, a larger system design is provided.

**Milli (150-person)** To handle a community of up to 150-people, the micro system is horizontally scaled.

# Components

## Intake

The water intake will consist of a weir on a stream with two openings with turbulence bars that channel turbulent water down onto a screen-covered 200-liter barrel angled at at downward slope.

This is a common low,budget, self-cleaning intake design that will shed organic debris during high-flow (eg a heavy rain).

The distance from the bottom of the weir to the top of the screen should be at least 20 cm.

The size of the holes in the screen should be 1-5 mm (it should be supported by a expanded metal screen below it).

The screen on the barrel should be mounted on a hinge to allow for routine maintenance.

## Settling Tank

A radial-flow settling tank should be located very near to the intake and will remove sediment that passed the intake screen.

## Large Sediment Filter

A self-cleaning spin down filter (largest size micron available) will remove debris that passed through the settling tank.

The flush valve should be automatically opened electronically by a timer.

## Pre-Filter

This pre-filter will remove turbidity from the water before it enters the slow sand filter.

This is [built](https://web.archive.org/web/20070728135100/http://www.refugeecamp.org/learnmore/water/slow_sand_filter.htm) from a 200-litre HDPE drum that's filled with rocks and (mostly coarse) sand.

## Slow Sand Filter

The [Slow Sand Filter](https://en.wikipedia.org/wiki/Slow_sand_filter) will remove harmful bacteria and parasites from the water.

This is [built](https://web.archive.org/web/20070728135100/http://www.refugeecamp.org/learnmore/water/slow_sand_filter.htm) from a 200-litre HDPE drum that's filled with rocks and (mostly fine) sand.

## Media Sediment Filter

A self-cleaning spin down filter (smallest size micron available) will remove filtering media debris (sand) that may have come-out of the filters

The flush valve should be automatically opened electronically by a timer.

## Clean Water Tank

The clean water tank stores potable water.

## Lifeline

Pipes supply clean water from the clean water tanks to the community.

# License

Copyright (C) 2023 Michael Altfield and the Eco-Libre Team

The contents of this repo are under the GPL version 3 or later.
In addition, any content other than code can also be used, at your
choice, under CC-BY-SA version 4.0.

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
