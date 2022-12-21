---
# Game Design Fundamentals with p5.play
---

In this course you’ll learn the core principles of game design by making games with p5.play!

p5.play is a 2D game engine for online games and interactive art.

You probably signed up for this course because you want to know, “How can I make a good video game that people will enjoy playing?”

These lessons will hopefully help you find your own answers to that big question. Let’s get started!

---

## So first... What is a game?

- Games have structure, usually they have rules and objectives.
- Some games are competitions, with winners and losers.

---

Share with the class some things you did when you were a little kid or that you’ve seen other young children doing that could be considered “playing” but not considered games. Did this play activity eventually turn into a game?

- Running around -> a game of tag
- Climbing things -> a game of who can climb the fastest, highest, etc.
- Jumping -> a game of who can jump rope faster/longer
- Exploring -> a game of who can find the most of a specific item

---

People often talk about games in terms of genre. In reality, most games can't be easily categorized into a single genre.

For instance, Minecraft is:

- a creative/sandbox game (creative mode is virtual legos)
- an adventure game (exploring the algorithmically generated open world, defeating the Ender Dragon)
- a survival game (fighting mobs, building defenses, creating traps for enemies)
- an educational game (redstone = electricity)

---

## Why do people play games?

- for entertainment
- to socialize with friends and family
- to create things in a virtual world
- to challenge themselves and improve their skills
- escapism from the mundanity or stresses of everyday life
- to make money (gambling)
- to learn new things

---

Let's try to categorize games in terms of what their main appeal is, why people play them.

---

## Creating/Building

Games where the main goal is to create things.

Minecraft, Poly Bridge, ScribbleNauts

---

## Engaging with a Narrative

Player interaction with these games almost entirely revolves around interacting with the game's story.

Life is Strange, The Wolf Among Us (many games published by TellTale)

---

## Learning

Educational games that teach players about a specific subject.

CoolMathGames, Type2Learn

---

## Simulation

Games that aren't really meant to be games, their main appeal is the simulation of real life activities.

Microsoft Flight Simulator

---

## Gambling

The main goal of playing these games is to try to win money.

Japanese pachinko machines, Slot machines, Axie Infinity (and other NFT based "games", which are ponzi scheme scams)

---

## Socializing

Games that would be unplayable without other players.

Among Us

---

## Play based

In this course we're mostly going to focus on making "play based" games that are simply fun to play. This is the most common type of game.

Super Mario Odyssey, Wordle, Breath of the Wild, Doodle Jump, Subway Surfers, Mario Kart 8, Portal 2, Tetris, Pong, Asteroids, etc.

---

Though the main appeal of "play based" games is the gameplay, they often have creative, socializing, simulation, and narrative elements as well.

For instance, Breath of the Wild's core gameplay is based on exploring the game's vast open world, fighting enemies, and solving puzzles.

But it also has a great story, the game's world is filled with interesting characters. BOTW has creative elements, as players can customize their character's appearance and decorate their house. The game also loosely simulates cooking and wild horse taming. Players can also socialize with others that have played or watched the game.

---

Simulating real world physics with 100% accuracy is not the goal of most video games. Also, simulating real world physics with 100% accuracy is not possible. Your computer would have to simulate every atom in the universe to do that!

---

In a 60fps video game, a physics simulator must update the game world 60 times per second. Each frame must be produced in less than 16.6 milliseconds.

A good physics simulation for video games is one that's accurate enough to be believable, but not so accurate that it requires a supercomputer to run.

Creating a physics simulation for a video game requires a lot of complex math. Most video game developers use game engines that have built-in physics simulators.

---

p5.play uses the planck physics engine, which provides a good balance between accuracy and performance.
