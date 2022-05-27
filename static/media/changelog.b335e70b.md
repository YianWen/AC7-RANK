
# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
- Example Videos of every stat used for the pilots 
- Cheater list page
- Include "Peripherals" as part of the player profile data
- CRUD (Create, Read, Update, Delete) Players from INSIDE the web site
- actual database of players using an actual database (MongoDB, AWS, Cassandra, MySQL, any)
- API REST server to consume the data
- check how to allow to enter from the /pilots page without getting error 404

## [0.6.3] - 2022-05-26
### Added
- Incomplete chinese translation.


## [0.6.2] - 2022-05-25
### Added
- i18n implementation to allow translation into multiple languages.
- Incomplete spanish translation.
- 3 new fonts that matches cyrilic and japanese characters for further translations.
- Badge to indicate the Squadron leader.
- Leader and Legacy icons in the pilot list.

### Changed
- The phrase "LEGACY PROFILE" for an honor medal icon.
- Players grouped by rank in the pilot list.

### Removed 
- Sorting options because seemed useless.


## [0.6.1] - 2022-04-13
### Added
- General rules about submissions.
- Squadron Emblems.
- Return of the average percentage value.
- A detailed explanation about the average weights and the corresponding rank (apologies for the first implementation of this and it's misunderstandings).


## [0.5.2] - 2022-02-22
### Added
- Music control buttons in music player component
- Music scroll control
- Expanded music library

### Removed 
- Music control through keyboard


## [0.5.1] - 2022-02-07
### Added
- Country filter (and country counter) in Pilots List.
- Sorting patterns (Name, Rank) in Pilots List.
- Legacy pilots filter.
- Platforms icons in Pilot Data.

### Fixed
- Platform typo in settings



## [0.4.3] - 2022-02-04
### Added
- Neue Pixel Sans to resemble Ace Combat 5 font
- Envy Code R to resemble Ace Combat Zero font

### Changed
- light up the unfocus letters in ACZ theme
- ACZ theme less bloody

### Fixed
- Click 2 times in a theme changed everything to a broken Ace Combat 7 theme



## [0.4.3] - 2022-02-03
### Added
- "Now Playing" component
- Judges Council section in the About Page
- Themes based on Ace Combat Games

### Changed
- Return label in the Breadcumb of every page, now is called "Click to Return"
- Word "Ranking" for "Pilot Database"



## [0.4.2] - 2022-02-02
### Added
- Changelog page
- Rank badge

### Removed 
- Average value aside the pilot rank
- Information about the average values 



## [0.4.1] - 2022-01-20
### Added
- Font Settings, to change between AC7, AC6 and AC4 fonts
- More music.
- Previous and Next song keys.
- Normalization algorithm for all the stats.



## [0.3.1] - 2021-12-08
### Added
- This CHANGELOG file.
- More music.
- Information about what does every statistic mean.
- grunder favicon and logos.

### Changed
- Music volume from 0.5 to 0.3.
- app short name, name and icons in manifest.json.

### Fixed
- Mobile responsivenes for all pages.



## [0.2.0] - 2021-12-03
### Added
- Consuming "data base" from json files to release it on github pages.
- background music player.
- animated background.
- Helper key bindings shown in Home Page.



## [0.1.0] - 2021-12-02
### Added
- About page.
- Start page in fullscreen automatically.
- Sound effects on menu items.
- Charts for the statistics.

### Changed
- Ranking algorythm using differents coefficients depending the stat.



## [0.0.1] - 2021-12-01
### Added
- Home Page.
- Pilots Page with player data and list of players.
