# MTGmeta.io Changelog

[MTGmeta.io](https://mtgmeta.io) log of the most important changes made (design, code, structure or new implementations).

- [Changelog](#changelog)
- [mtgmeta related Links](#links)
- [bug reports](#bugreports)

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
* [api](https://mtgmeta.io/api) no longer public, only for beta testers and/or patreons.
* when adding a new deck shows first the current era
* when checking the user tools order by most current format
* view selection (list or grid) for [/decks](https://mtgmeta.io/decks), [/tournaments](https://mtgmeta.io/tournaments), [/users/decks](https://mtgmeta.io/users/decks), [/users/matches](https://mtgmeta.io/users/matches), and [/users/events](https://mtgmeta.io/users/events)
* updated auto verification to work with companion decks
* sponsored users can use get referred users
* mtgo matches importer is now being tested for beta users
* on desktop in the metagame matrix you can now drag horizontally
* mobile small redesign of the vs deck in the single deck view
* deck filter now is case isensitive (was only matching with lowercase)

## Links

* [mtgmeta :chart_with_upwards_trend:](https://mtgmeta.io)
* [roadmap (planned implementations) :clipboard:]()
* [reddit]() 
* [patreon]()
* [twitter]() 
* [discord]()
* [email :email:]()

## Bug Reports

If you find any problem (even misslabeled decks) you can enter in contact preferebly via... TODO
