# The Great Randomiser

## Premise

We have a covers group during COVID 19 lockdown.
Each person in the group submits a song suggestion that they would like to hear covered.
The folks who submitted, each get a song to cover in return.

We take a little under two weeks per round to produce our track and then have a listening party via Zoom to have some beers and appreciate all the masterpieces.

## Prerequisites

You:
- [x] Are running in a shell environment (Linux/Mac Terminal/Windows Powershell)
- [x] Have PHP CLI version 7.1 or above
- [x] Have [composer](https://getcomposer.org/) installed

## How To Use

Organise yer pals. Clone this repo into a directory on your machine and head in there using your terminal. Put the names of the suggesters, along with their suggestion in `data.txt` in the following format:

```text
Paul|Are You Lonely Tonight, Elvis Presley
Sally|Girls Just Wanna Have Fun, Cyndi Lauper
Sian|Innuendo, Queen
```

Install the dependencies via `composer install`.

Run `./rand` in your terminal.

#### That's all folks.

## Known Issues

There's a chance a suggestion will be assigned to the person who suggested it. Just run it again. Can't be bothered to add more logic to fix this. I call that *the secret sauce*.
