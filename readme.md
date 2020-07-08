# Tempo SDK for Game Developers

Bring a new stream of revenue into your mobile games using the Tempo SDK. Tempo provides new kinds of ad units that run during gameplay in a non-disruptive manner which provide you revenue WHILE users are playing. Tempo ads can run alongside your existing interstitial and banner ads.

The Tempo SDK provides a quick way to implement Tempo Ad Units into your Unity games (support for Unreal Engine and native iOS/Android games coming in Q1’21). Simply define game elements which can be branded, supply your default textures, and the Tempo Platform handles the rest.

<insert graphic>

# Types of Ad Units

* Branded Placements - Status: Available for Unity games

Advertisers can brand the game elements you define.

* Tempo Minis - Status: Closed beta for select developers

<example>

Used alone or in conjunction with Branded Placements, Tempo Minis provide a way for advertisers to offer a shopping or download experience non-disruptively during your game. 

* Audio Ads  - Status: Beta starting Q4’20

<example>

Used alone or in conjunction with Branded Placements and Tempo Minis, Audio Ads provide a way for advertisers to offer branded messages as sound bites during gameplay. 

# Branded Placements

## How it Works

During Development:

Declare game elements which advertisers can brand using the Tempo SDK

The Tempo SDK automatically uploads the default texture used for the game element and creates a listing on the Tempo Platform for advertisers

At runtime:

1. During game or level initialization (depending on if game elements are specific to a certain level), declare a list of game elements which will be displayed to the user

2. The Tempo SDK checks with the Tempo API to see if branded textures are available and returns branded textures to display to the user along with additional configuration info if a Tempo Mini or Audio Ad is associated with the Branded Placement

3. The Tempo SDK automatically brands the game element when it appears on screen for a certain duration (usually 15 seconds). If the game element goes off screen before the time elapses, it is branded for the remaining duration next time it appears on screen.

## Example Elements Which Can Be Branded

* Bubbles

* Buildings

* Casino

* Clothing

* Coins 

* Display

* Environment

* Electronics

* Food

* Furniture

* Industrials

* Lives

* Narratives

* NPC

* Power Ups

* Special events

* Sports

* Tools

* Vehicles 

* Weapons 

## Additional Information

The maximum size for a branded game texture is `5 MB`.

# Tempo Minis

## How it Works

During Development:

1. Declare game views where advertisers can display Tempo Minis at the bottom 25% of the screen (your game should adapt to display in the upper 75% of the screen)

At runtime:

1. During gameplay when a view which supports Tempo Minis is on screen, the Tempo SDK checks with the Tempo API to see if Tempo Minis are available and returns a configuration file which the Tempo SDK uses to display the Tempo Mini to the user.

2. The Tempo SDK automatically displays the Tempo Mini for a certain duration (usually 15 seconds). If the game view goes off screen before the time elapses, it is displayed for the remaining duration next time the view is displayed. 

3. The Tempo SDK allows a user to swipe between all displayed Tempo Minis displayed in a session when a Tempo Mini is active on the screen.

## Example Views Where Tempo Minis Can be Displayed

* Welcome Screens

* World Selectors

* Level Selectors

* Character Selectors

* Loot Boxes

* Core Game Views

* Game Over 

# Tempo Audio Ads

Information coming soon.

# Metrics

You will receive access to the Tempo for Developers dashboard to track:

* Performance of specific Branded Elements

* Performance of game views for Tempo Minis

* Performance of soundtracks for Audio Ads

* Optimization Tips

* Earnings

* Payouts

# Demo & Download

If you’re interested in integrating the Tempo SDK into your app send an email to [developers@tempoplatform.com](mailto:developers@tempoplatform.com) with the following information:

* Your Name/Email/Phone

* Game Name/Download Link

* Tech Stack

* Average MAU

* Languages Localized In

* Main Geographic Regions Game is Popular In

