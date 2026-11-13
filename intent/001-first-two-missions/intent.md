# Intent: the game, and its first two missions

Author: Juan Pineros. Status: accepted once merged into `main`. First
conversation: 10 November 2026.

## Problem

Bogotá 1995 exists today as a room: a bedroom on a rainy afternoon, with a
radio, a phone, a TV and a window. In its study, 68 strangers stayed a median
of 18 seconds and 36 of them opened no object. Only 5 were still there when
the first thing designed for the afternoon happened. Its author finds it
boring too.

The room asks nothing of a visitor. They can't move, want anything or lose
anything. It also shows a bedroom, when what the author wants to see again is
the city he lived in at 15.

## Proposed outcome

A game played in the browser in which you are a 15-year-old boy living in
Palermo, Bogotá, in 1995. You see the barrio through your own eyes, in 3D, and walk it.

You do missions: things a 15-year-old really had to get done. The difficulty
comes from the time and the age, not from enemies or puzzles. You have little
money, nobody can reach you once you leave home, every plan needs permission
and has a curfew, and the city changes after dark. The action is movement,
timing and risk.

The first version has two missions, both on one Saturday.

### Mission 1: the guitar lesson (afternoon, inside the barrio)

- **Goal:** get to your classical guitar lesson, a few blocks away, on time,
  with the guitar on your back and your mother's errand on Calle 45 done on
  the way.
- **What it shows:** home, your grandparents' house across the street, the
  church, and Calle 45 by day with its tiendas, bakeries, bookshops and the
  billar.
- **What makes it hard:** the clock, exact money for the errand, and friends
  who want you to stay.
- **How it ends:** the tutor sets you a piece, and Andrés tells you about a
  party tonight on the other side of Carrera 30.

### Mission 2: the first party (evening, beyond the barrio)

- **Goal:** go to your first party, in a house in Nicolás de Federmán, and be
  home by curfew with everything you left with.
- **Before:** you ask for permission. That conversation sets your curfew and
  your money. You choose whether to take the guitar.
- **At the party:** the music of the time (rock in English, salsa, rock en
  español). You are shy, about dancing and about Angie, the girl you like and
  have never dared to tell. Asking her to dance is the hardest thing in the
  room. If you brought the guitar, you are asked to play.
- **The way home:** the bridge at Calle 63 over Carrera 30, which is
  dangerous at night. It is a road bridge with a narrow walkway beside the
  cars, so there is no room to keep away from anyone on it. You can cross
  now, take the long way and be late, wait for other people to cross with, or
  take a taxi if you still have the fare.
- **What you can lose:** your money and the guitar, for good. A careful
  player keeps them. If it goes wrong you hand things over; you don't fight.

The bridge and the lost guitar come from the author's own memory, a few years
later than 1995.

### What success looks like

- The author enjoys it and wants to play it again. Choices change how the
  Saturday ends.
- It brings back memories for people who lived in Bogotá then, and it can be
  played by someone who didn't.
- It looks professional. The benchmark is these two browser scenes:
  [a town drawn entirely in code](https://x.com/BlendiByl/status/2121130385723789637)
  and [a photoreal courtyard](https://x.com/XRarchitect/status/2120947265007440052).
- A first-time player knows what they are trying to do within the first
  seconds.

## Affected users and systems

- **Players:** anyone, on a computer, in Spanish first.
- **The author:** product owner and first player.
- **The room** ([bogota-1995](https://github.com/juancopi81/bogota-1995)):
  the game takes its recorded voices and some of its music. Two of its
  characters come with them: Andrés, a friend, and Angie, the girl you like.
  It does not keep the room's look or its objects. The room stays as it is;
  the game lives in this repo.
- **Hosting:** none yet. The game is built and played locally.

## Constraints

- Web-based, with nothing to install and no account.
- Game text and voices in Spanish first. This repo's documents stay in
  English.
- First person, in 3D. One barrio built densely, not the whole city.
- Real places, fictional people. Where the author's memory and the record
  disagree, memory wins.
- The real Bogotá, with one or two hard realities. Getting mugged on the
  bridge is one. It is not a crime game.
- The main character is a 15-year-old boy with no name. No drinking is shown.
- No copyrighted music, footage or photos in the repo. Music is original or
  Creative Commons, in the style of the time; real songs can be named but not
  included. Villa-Lobos is still in copyright, so the lesson piece comes from
  older repertoire.
- Out of scope: school days, other barrios, driving, fighting, multiplayer,
  phones and tablets, and the room's later ideas about agents and lost
  futures.

## Open questions

- The author believes the Calle 63 bridge was there in 1995. How did it look
  then (railings, lighting), compared with today?
- How is shyness played, at the dance and with Angie?
- The room's voices were recorded for the room's script. Which lines can be
  used as they are, and how are new ones made in the same voices?
- How does the player get from Palermo to the party and the bridge: a
  simplified walk past Galerías and El Campín, or a buseta?
- Which look: drawn in code, generated photoreal scenes, or a mix?
- How are people shown so they look as good as the buildings?
- Is the main character ever seen (his hands, a mirror, a photo)?
- How much of the mugging is chance, and how much is the player's choices?
- What number would say strangers stay? To be decided; the room's baseline is
  18 seconds.
