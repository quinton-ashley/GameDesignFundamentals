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

Though the main appeal is the gameplay, these games often have creative, social, simulation, competitive, and narrative elements as well.

For instance, Breath of the Wild's core gameplay is based on exploring the game's vast open world, fighting enemies, and solving puzzles. But it also has a great story, the game's world is filled with interesting characters. BOTW has creative elements: players can customize their character's appearance and decorate their house. The game also _loosely_ simulates cooking and wild horse taming. Players can also socialize with others that have played or watched the game, to get help solving a shrine puzzle for example.

---

For the first half of this course, we're going to focus on radpidly prototyping the core gameplay of physics based games, in which players interact with the game world by moving physical objects through space.

2D game prototyping is significantly faster and easier than 3D game prototyping. Most of the world's most famous and respected game designers got their start making 2D games. The concepts you'll learn in this course will apply to 3D games as well.

I don't want you to make a generic 2D platformer during this course. So many great 2D platformers have already been made over the past half century, the genre is extremely saturated. Super Mario Run and Super Mario Maker 2 already exists! The world doesn't need another generic Super Mario Bros. clone. Despite the fact that there has been real innovation in the genre recently, with games like Celeste, it's still very difficult to make a unique 2D platformer.

People want to play games that are unique and interesting. They don't want to play a worse version of a game they've already played before.

---

Simulating real world physics with 100% accuracy isn't really possible. Your computer would have to simulate every atom in the universe to do that!

In a modern 60fps video game, the physics simulator is responsible for updating the game world at least 60 times per second. Each frame must be produced in less than 16.6 milliseconds!

A good physics simulation for video games is one that's accurate enough to be believable, but still runs well on consumer hardware.

Creating a physics simulation for a video game requires a lot of complex math. Most video game developers use game engines that have built-in physics simulators.

p5.play uses the planck physics engine behind the scenes, which provides a good balance between accuracy and performance.

---

## What’s the difference between a hard-core vs a casual approach to gaming?

When taking a hard-core approach, players want to be challenged with more complex games they can research and obsess over to optimize their play.
When taking a casual approach, players want to be entertained with games that have a simple premise so they can pick up and play easily.
People don’t exclusively take a casual or hard-core approach to every game they play.

---

“Instrumental play is a goal-orientated approach that values efficiency, expertise and optimizing strategies as part of play. Crudely put, in instrumental play the point of the playing is not just to reach the end, but to find the best way of getting there (Taylor, 2006). Instrumental play may also be referred to as ‘min-maxing’, ‘power gaming’ or ‘hardcore gaming’. A central feature of this approach is a deep understanding of the game system, which enables one to take advantage of inherent favorable combinations or configurations hidden in the game mechanics, as well as joy in doing so. Instrumental play has received much attention from game studies scholars (eg. Chen, 2012; Eklund & Johansson, 2013; Malone, 2009; Taylor, 2009) as it challenges romantic notions of play as something frivolous, light 5 and enjoyed for its own sake. This tension has also been noted by players who characterize the dedication of power gamers as ‘over the top’. Power gamers are often accused of having no social life outside the game, even for playing incorrectly, by taking the game too seriously. Empirical studies of instrumental power gamers have however shown how they tend to be integral social actors in player communities exactly because of their dedication. In a game where perseverance is a virtue, power gamers are understood as productive and skilled participants whose expertise is sought after and admired (Taylor, 2006). Furthermore, these studies show that a serious approach to play does not exclude fun. Instead enjoyment stem from achieving set goals, finding good strategies and gaining insight into the underlying structures of the game (Consalvo et al., 2010), and serves as a reminder of how games are sites for a wide range of engagements and types of enjoyment (Kallio, Mäyrä, & Kaipainen, 2011).”

Ask, Kristine, ‘The Value of Calculations: The Coproduction of Theorycraft and Player Practices’ (2016) 36(3) Bulletin of Science, Technology & Society 190.

---

Can you think of any “hard-core” gamers who you admire for their intense dedication to a game?

Olympian Michael Phelps
Chess prodigy Magnus Carlson
SSB Melee champion HungryBox (Juan Debiedma)

---

Is it always desirable to be good at a game?

No, if people don’t like a game, they won’t want to play it at all!
If people do like a game, it’s often desirable for them to achieve a game’s objectives, even when playing a game “just for fun”. But this isn’t always the case. For example, playing a game poorly on purpose against an inexperienced opponent to teach them how the game is played.

---

Have you ever played a video game that rewards players for being “bad” at it?

Skate 3 is a skateboarding video game that rewards players for completing tricks. It also has a reward system for counting how many bones the player character breaks after a fall! Players can even unlock achievements for really bad falls. Which technically makes it a form of playing the game well, to get all the fall damage achievements you must find the worst places to fall in the game.

---

“Instrumental play tends towards optimization which can often result in un-fun player behaviors. This gets extended out to the extreme [by the media and some academics], where play framed around challenge or investment is treated as irrational or somehow less genuine than some hypothetically more pure, innocent, unadulterated version of play: unconcerned with doing well. It’s important in this conversation to establish firmly that this is a false dichotomy. [...] they’re not antithetical concepts. Rather than being in conflict with one another they’re in tension, there’s not an opposed relationship but there is a complex one. Because if you back up and think about it, it’s easy to appreciate how someone can find deep enjoyment in improving a skill, achieving goals, and discovering solutions to complex problems. Rather, instrumental play, play focussed on goals, can be juxtaposed with free play. A form of play that is without ending, neither free or instrumental play can exist in their purest form, [...]”

Nathan Landel and Dan Olson, Why It's Rude to Suck at Warcraft, FoldingIdeas Channel on Youtube

---

Have you ever engaged in free play with a work of interactive digital art that you wouldn’t categorize as a video game?

When I was in middle school the iPhone was brand new. There were a few apps that gained popularity perhaps only because the 3.5 inch touch screen of the iPhone was such a novel concept. I downloaded an app that displayed a fixed camera top down view of a Koi Pond. Players could tap on the screen to disperse food for the Koi fish and the fish would swim over to eat the food. If you held your finger on the screen

---

Why can't free play exist in its purest form?

humans are natural game designers, we naturally create little games when engaging in free play

---

Share a real life example of a time you “gamified” an banal activity or created a little game for yourself while waiting for something.

---

Red Remover

Line Rider

---
