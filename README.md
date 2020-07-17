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

## Related Links

* [mtgmeta :chart_with_upwards_trend:](https://mtgmeta.io)
* [roadmap (planned implementations) :clipboard:]()
* [reddit]() 
* [patreon]()
* [twitter]() 
* [discord]()
* [email :email:]()

## Bug Reports

If you find any problem (even misslabeled decks) you can enter in contact preferebly via... TODO
