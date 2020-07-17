# MTGmeta.io Changelog

[MTGmeta.io](https://mtgmeta.io) log of the most important changes made (design, code, structure or new implementations).

- [Changelog](#changelog)
- [MTGmeta related Links](#related-links)
- [Bug reports](#bug-reports)

## Changelog

### 2020-06-29
* when ordering decks, names that start with letter go to the end now
* small text changes
* dates changed from dd/mm/yyyy to dd MONTH yyyy
* decks when no information is available now show it instead of 404 error
* fix deck export for arena
* deck filter is maintained when changing era on /decks
* mtgo importer decks timeout matches
* fixed error when you would need to get the deck associated to be inserted
* mtgo importer fixes (practice, no plays)
* When checking your deck stats you now have the game turns average

### 2020-05-26
* small performance optimization
* menu redesign
* homepage small mobile redesign
* matrix chart color green now starts at >= 54% instead of 65%
* backend admin upgrades
* fix some cards images (tell me when you find any) wrongly placed and some card name errors
* notice added that you get other stats when you filter on the stats page
* improvement in the auto card identifying, avoiding less manual verification
* [/api](https://mtgmeta.io/api) no longer public, only for beta testers and/or patreons.
* when adding a new deck shows first the current era
* when checking the user tools order by most current format
* view selection (list or grid) for [/decks](https://mtgmeta.io/decks), [/tournaments](https://mtgmeta.io/tournaments), [/users/decks](https://mtgmeta.io/users/decks), [/users/matches](https://mtgmeta.io/users/matches), and [/users/events](https://mtgmeta.io/users/events)
* updated auto verification to work with companion decks
* sponsored users can use get referred users
* mtgo matches importer is now being tested for beta users
* on desktop in the metagame matrix you can now drag horizontally
* mobile small redesign of the vs deck in the single deck view
* deck filter now is case isensitive (was only matching with lowercase)

### 2020-03-23
* on the /decks page you can now filter decks by name
* performance optimization loading fonts
* performance optimization some images and remove parallax from home to help older devices
* fixed error when sometimes confidence interval appear as -0% instead of 0%.
* you can now also track the turns the games had
* loading site performance small upgrade (not noticeable really atm)
* mtgo match importer at roughly 80% completed
* tournament manager at roughly 60% completed
* sideboard guide at roughly 10% completed

### 2020-03-12

- deck insert and Vs deck insert now with a better autocomplete and with fuzzy search
- on submit page, deck and player search with a better autocomplete and fuzzy search
- user events there was an error on the filter by deck, it has been fixed
- when inserting user matches if there is an error you can now go to the error match directly
- user matches when inserting match, besides the trash icon there is also an "delete this match" to clarity
- user add match or deck, optional section are now ALL collapsed
- in user tools section now is possible to save/load you defined meta
- search results small redesign
- started tracking elo for players from the scg events, will be separated from the tracking from GP/PT provided by mtgeloproject but will provide elo stats for SCG events too.
- code improvements and back-office upgrades

### 2020-02-11

* error on some cards name fixed
* error when trying to register with email
* notice to register
* small redesign to deck and tournament views
* mana costs added to cards
* metagame round chart with more info
* metagame sort
* internal code updates
* elo integration for GPs and PTs started
* live events managment started (wltr, wer, self-host)
* sideboard plans development started
* buttons small redesign

### 2020-01-27

- Users can now import matches from csv/xlls files
- cards manacost added
- charts for deck meta and history redesigned, also deck view in tournaments and single deck.
- meta and history for decks now show periods instead of continued (similar to user stats)
- small user stats designs updates
- internal code revisions and small not public updates
- live events manager redone (not public yet)

#### 2020-01-19

- user stats you can now sort on the vs section and on the match section
- go to top button
- option to sort whenever there is a performance matrix
- code optimizations and small design updates Single deck Vs sort
- fixed error when main deck or sideboard would lose formatation in the user deck info

### 2020-01-06

* tool to get expected performance according to parameters (meta, deck adjustments, day2, etc... [/tools](https://mtgmeta.io/users/tools)
* lines in metagame matrix can now be rearranged
* small design changes (deck image top)
* small technical improvements

### 2019-12-08

- small design changes to menubar and mobile menu
- added tag of deck when checking user stats
- fixed soome small bugs for the [/users](https://mtgmeta.io/users)
- added the option to join decks together in the [/metagame](https://mtgmeta.io/metagame)

### 2019-08-06

- added best performant deck adjusted to metagame share
- fixed design for metagame share when there are not at least 16 decks

### 2019-07-11

- added a new color to metagame matrix (decks over 70% performance)
- new tab select implemented
- on deck submition the deck options can be selected with the keyboard, mouse or enter for the first choice
- small homepage design changes
- single user stats tracker register/login done

### 2019-06-18

- format selector redesign
- main page small design update on the box
- architecture and design for user personal stats started

### 2018-01-10

💥


## Related Links

* [mtgmeta :chart_with_upwards_trend:](https://mtgmeta.io)
* [roadmap (planned implementations) :clipboard:](https://github.com/mtgmetaio/roadmap)
* [reddit](https://www.reddit.com/r/mtgMETAio/) 
* [patreon](https://www.patreon.com/mtgmeta)
* [twitter](https://twitter.com/mtgmetaio) 
* [discord](https://discord.gg/3KaXbMQ)
* [email :email:](mailto:hello@mtgmeta.io?subject=[BUG%20REPORT]%20)

## Bug Reports

If you find any problem (even misslabeled decks) you can enter in contact preferebly via [email :email:](mailto:hello@mtgmeta.io?subject=[BUG%20REPORT]%20), [twitter](https://twitter.com/mtgmetaio), [discord](https://discord.gg/3KaXbMQ) or open an issue on the [bugs report](https://github.com/mtgmetaio/bugs-report).
