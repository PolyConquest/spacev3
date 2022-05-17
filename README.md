# Spacev3

Default layout for the Space game version3.

## Goal

Reach the endpoint which is the DO planet.
You start on Earth.

## Actions

- `move <src> <dest>` : moves the ship from the source planet to the destination planet

## Available Input

- `readLine` : returns a stringified JSON object representing the solar system. {planets: [{id,name}], paths:[src,dest], startingPoint, endingPoints}

## Win Condition

You win by being on the endpoint BUT you also used the less moves possible.