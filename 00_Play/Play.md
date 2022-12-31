---
# Play
---

In this course you’ll learn the core principles of game design by making games with p5.play!

p5.play is a game engine for online games and interactive art.

You probably signed up for this course because you want to know, “How can I make a good video game that people will enjoy playing?”

These lessons will help you find answers to that big question. Let’s get started!

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

## Humans aren’t the only animals that play games!

We all know animals like dogs can be trained to play games like fetch. But what about wild animals?

---

## Trained Play

<https://www.youtube.com/watch?v=hC9aSP9x0xE>

---

## Rewarded Play in the Wild

Turtles are cold-blooded animals, so they can’t control their body temperature internally. The only way they have to raise their body temperature is to bask to absorb warmth and vital UV rays.

Turtles may look like they’re playing games in these clips, but these are actually examples of rewarded play so that the turtles can regulate their body temperatures.

<https://www.tiktok.com/t/ZTRb2aSSJ>

<https://www.tiktok.com/t/ZTRb2H8hr>

---

## Why do humans and other animals engage in play and design games?

- Play can strengthen social bonds
- Play improves sensory motor coordination skills
- Play improves logical reasoning and abstract thinking abilities
- Play provides the opportunity to prove oneself in competitions
- Play feels fun!

---

People often talk about games in terms of genre. In reality, most games can't be easily categorized into a single genre.

For instance, Minecraft is:

- a creative/sandbox game (creative mode is virtual legos)
- an adventure game (exploring the algorithmically generated open world, defeating the Ender Dragon)
- a survival game (fighting mobs, building defenses, creating traps for enemies)
- an educational game (redstone = electricity)

---

## Why do people play games?

Let's try to categorize games in terms of what their main design or appeal is, why people play them.

---

## To Create/Build

Games where the main goal is to create things.

Minecraft, Poly Bridge, ScribbleNauts

---

## To Engage with a Narrative

Player interaction with these games almost entirely revolves around interacting with the game's story.

Life is Strange, The Wolf Among Us (many games published by TellTale)

---

## To Learn

Educational games are designed to teach players about a specific subject.

CoolMathGames, Type2Learn

---

## To Simulate an Experience

Simulations aren't primarily designed to be games, their main appeal is the simulation of real life activities.

Microsoft Flight Simulator

---

## To Gamble

The main goal of playing these games is to try to win money. Professional gamblers make a living playing these games, albiet a high stakes, stressful one.

Japanese pachinko machines, Slot machines, Axie Infinity (and other NFT based ponzi scheme scam "games")

---

## To Socialize

Games that would be unplayable without other players.

Charades, Heads Up, Pictionary, Among Us

---

## To Compete

Some games are designed to be played in high level competitions.

World of Warcraft, League of Legends, Counter Strike, etc.

---

## To Play

The experience of the gameplay itself is the primary appeal of most games. The majority of players play these games primarily for the sake of playing. Not necessarily "just for fun", but not primarily to engage with narrative, learn, create, experience a simulation, gamble, socialize, or compete at a high level. This category of games covers almost all genres of video games.

Super Mario Odyssey, Wordle, Breath of the Wild, Doodle Jump, Subway Surfers, Mario Kart 8, Portal 2, Tetris, Pong, Asteroids, etc.

---

Though the main appeal is the gameplay, these games often have creative, social, simulation, competitive, and narrative elements as well.

For example, Breath of the Wild's core gameplay is based on exploring the game's vast open world, fighting enemies, and solving puzzles. But it also has a great story, the game's world is filled with interesting characters. BOTW has creative elements: players can customize their character's appearance and decorate their house. The game also _loosely_ simulates cooking and wild horse taming. Players can also socialize with others that have played or watched the game, to get help solving a shrine puzzle for example.

---

There are many different types of video games which you might be interested in making, but during this course we're going to focus on making games that are primarily about the gameplay itself: specifically physics based games, in which players interact with the game world by manipulating physical objects.

During the first half of this course, you'll be tasked with radpidly prototyping, so you can quickly see what works and what doesn't.

Many of the world's most famous and well respected game designers got their start making 2D games. Many of the 2D game concepts you'll learn will apply to 3D games as well.

---

Simulating real world physics with 100% accuracy isn't really possible. Your computer would have to simulate every atom in the universe to do that!

In a modern 60fps video game, the physics simulator is responsible for updating the game world at least 60 times per second. Each frame must be produced in less than 16.6 milliseconds!

A good physics simulation for video games is one that's accurate enough to be believable, but still runs well on consumer hardware.

Creating a physics simulation for a video game requires a lot of complex math. Most video game developers use game engines that have built-in physics simulators.

p5.play uses the planck physics engine behind the scenes, which provides a good balance between accuracy and performance.

---

---
