# The Great Randomiser

## Premise

We have a covers group during COVID 19 lockdown.
Each person in the group submits a song suggestion that they would like to hear covered.
The folks who submitted, each get a song to cover in return.

We take about a month per round to produce our track and then have a listening party via Zoom to have some beers and appreciate all the masterpieces.

## The Group Constitution

This changes a lot, people keep adding new rules, at the moment they are something like:

* No negging on yerself
* Suggestions must be...
  * <= 5 minutes long
  * available to listen to online
  * have chord charts online somewhere
  * sent to our benevolent dictator with an accompanying explanation of why you chose it
* You can roll over into the next round, coz sometimes life gets in the way, but you can only do it once
* Submit your song by email to our benevolent dictator on the day of the listening party. A link to a Dropbox  or something for your wav, aiff whatever 
* If you don't finish your song it goes in the chum bucket
* If you finish your song early you can take another from the chum bucket
* If you really can't dig your sing you can put it in the chum bucket and take another out
* Getting a song from the chum bucket...
  * Ask our benevolent dictator Matt who will give you a number
  * Chose a number between 1 and the number Matt gave you
  * Accept your chum with grace and don't bitch about it

## Randomising and divvying out the suggestions

### Prerequisites

You:
- [x] Are running in a shell environment (Linux/Mac Terminal/Windows Powershell)
- [x] Have PHP CLI version 7.1 or above
- [x] Have [composer](https://getcomposer.org/) installed

### How To Use

Organise yer pals. Clone this repo into a directory on your machine and head in there using your terminal. Put the names of the suggesters, along with their suggestion in `data.txt` in the following format:

```text
Paul|Are You Lonely Tonight, Elvis Presley
Sally|Girls Just Wanna Have Fun, Cyndi Lauper
Sian|Innuendo, Queen
```

Install the dependencies via `composer install`.

Run `./rand` in your terminal.

#### That's all folks.
