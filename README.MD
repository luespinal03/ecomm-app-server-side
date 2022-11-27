User Stories.

In this application I am building a clone version of G2A or Gamestop website called "Gameshack". It will be a very simple version, not as in depth as the previously mentioned but it will show that I was able to connect a database to a server side and server side to a front end.

When the user renders the HomePage they will see the main page of my site first, with the logo on the upper left corner, a link to log in/register along with a shopping cart next to it. Perhaps some trending products at the bottom of the HomePage.

When the user clicks on register button it will render the registration page where the user gets prompted for their email and password in order to create their account.

Once user creates their account, the login page should be rendered so the user can log in and start shopping for their desired products and logout option if they choose to.

<!-- data in db -->

db.games.insert([{
"title": "Horizon Zero Dawn",
"console": "PS4",
"features": "A Lush Post-Apocalyptic World – How have machines dominated this world, and what is their purpose? What happened to the civilization here before? Scour every corner of a realm filled with ancient relics and mysterious buildings in order to uncover your past and unearth the many secrets of a forgotten land.Defy Overwhelming Odds – The foundation of combat in Horizon Zero Dawn is built upon the speed and cunning of Aloy versus the raw strength and size of the machines. In order to overcome a much larger and technologically superior enemy, Aloy must use every ounce of her knowledge, intelligence, and agility to survive each encounter.Nature and Machines Collide – Horizon Zero Dawn juxtaposes two contrasting elements, taking a vibrant world rich with beautiful nature and filling it with awe-inspiring highly advanced technology. This marriage creates a dynamic combination for both exploration and gameplay.",
"brand": "Sony",
"price": 7.99,
"genre": "action",
"esrb-rating": "T (Teen)",
"ratings": 4.6,
"image": "https://media.gamestop.com/i/gamestop/10129080/Horizon-Zero-Dawn---PlayStation-4?fmt=auto&$pdp-gallery$"
},
{
"title": "UNCHARTED: Legacy of Thieves Collection",
"console": "PS5",
"features": "UNCHARTED: Legacy of Thieves Collection includes: UNCHARTED 4: A Thief's End and UNCHARTED: The Lost Legacy remastered for PS5 Travel the world in an extrordinary adventure and discover lost treasure and lore.Remastered in stunning detail for the PS5 console with improved visuals and framerate.Experience the action-packed storytelling from the iconic franchise.",
"brand": "Sony",
"price": 39,
"genre": "action",
"esrb-rating": "T (Teen)",
"ratings": 4.6,
"image": "https://media.gamestop.com/i/gamestop/11179571/UNCHARTED-Legacy-of-Thieves-Collection----PlayStation-5?fmt=auto&$pdp-gallery$"
},
{
"title": "Horizon Forbidden West Launch Edition",
"console": "PS5",
"features": "Brave an expansive open world - Discover distant lands, new enemies, rich cultures and striking characters.Confront new dangers - Engage in strategic battles against enormous machines and mounted human enemies by using weapons, gear and traps crafted from salvaged parts.A majestic frontier - Explore the lush forests, sunken cities and towering mountains of a far-future America.Unravel startling mysteries - Uncover the secret behind Earth's imminent collapse and unlock a hidden chapter in the ancient past... one that will change Aloy forever.",
"brand": "Sony",
"price": 39,
"genre": "action",
"esrb-rating": "T (Teen)",
"ratings": 4.6,
"image": "https://media.gamestop.com/i/gamestop/11158704/Horizon-Forbidden-West-Launch-Edition---PlayStation-5?fmt=auto&$pdp-gallery$"
},
{
"title": "NBA 2K23",
"console": "PS5",
"features": "PFeel refined gameplay in the palm of your hands on both sides of the ball in NBA 2K23.Step back in time with era-specific visuals that captured Michael Jordan’s ascent from collegiate sensation to global icon with immersive Jordan Challenges chronicling his career-defining dominance.Step back in time with era-specific visuals that captured Michael Jordan’s ascent from collegiate sensation to global icon with immersive Jordan Challenges chronicling his career-defining dominance.",
"brand": "2k Games",
"price": 39,
"genre": "sports",
"esrb-rating": "E (Everyone)",
"ratings": 3.1,
"image": "https://media.gamestop.com/i/gamestop/11206859-11206849?fmt=auto&$pdp-gallery$"
},
{
"title": "Madden NFL 23 ",
"console": "PS5",
"features": "Plan and strategize like an NFL head coach with refined scouting, staff management, and weekly strategy features to take your Franchise to the top.Develop your dream fantasy roster of current NFL superstars, Hall of Fame legends, and more.Squad up and feel like an NFL superstar in Madden NFL 23’s fast co-op eliminator mode where Superstar X-Factor abilities are always on.",
"brand": "Electronic Arts",
"price": 39,
"genre": "sports",
"esrb-rating": "E (Everyone)",
"ratings": 3.9,
"image": "https://media.gamestop.com/i/gamestop/11190739?fmt=auto&$pdp-gallery$"
},
{
"title": "Super Smash Bros. Ultimate",
"console": "Nintendo Switch",
"features": "New stages and fighters are joined by the combined rosters of every past Super Smash Bros. game Play any way you want—locally, online, in TV mode, Tabletop mode, Handheld mode, or even with GameCube Controllers Face off in 2-4 player battles, or play against the computer Challenge others anytime, anywhere, whether you're on the couch or on the go",
"brand": "Nintendo",
"price": 59,
"genre": "action",
"esrb-rating": "E (Everyone 10+)",
"ratings": 4.8,
"image": "https://media.gamestop.com/i/gamestop/10159620/Super-Smash-Bros.-Ultimate---Nintendo-Switch?fmt=auto&$pdp-gallery$"
},
{
"title": "Sonic Frontiers ",
"console": "Nintendo Switch",
"features": "Experience All-New Open Zone Platforming - Race across 5 massive overworld islands, each with their own unique action-platforming challenges and hidden secrets to uncover.Challenge Yourself in Cyber Space - Unlock Cyber Space levels featuring signature 3D platforming at “Sonic Speeds”, and a variety of challenges to test your skills like never before.A New Adventure Full of Mystery and Intrigue - Become Sonic and journey to uncover the mysteries of the remains of an ancient civilization, plagued by robotic hordes.",
"brand": "SEGA",
"price": 39,
"genre": "action",
"esrb-rating": "E (Everyone 10+)",
"ratings": 4.7,
"image": "https://media.gamestop.com/i/gamestop/20000861-6c0948f1?fmt=auto&$pdp-gallery$"
},
{
"title": "Mario Party Superstars",
"console": "Nintendo Switch",
"features": "Party on 5 classic boards from the Nintendo 64 Mario Party games. All game modes can be played online*. Play using a single Joy-Con controller, two Joy-Con with the Joy-Con grip accessory, Nintendo Switch™ Pro Controller, or Nintendo Switch Lite system. Matches with friends in board game mode are saved after each turn both locally and online*—pick up where you left off. Play 100 minigames from throughout the Mario Party series",
"brand": "Nintendo",
"price": 39,
"genre": "adventure",
"esrb-rating": "E (Everyone 10+)",
"ratings": 4.7,
"image": "https://media.gamestop.com/i/gamestop/11149254/Mario-Party-Superstars---Nintendo-Switch?fmt=auto&$pdp-gallery$"
},
{
"title": "The Legend of Zelda: Breath of the Wild",
"console": "Nintendo Switch",
"features": "Discover Hyrule as never before: by making your own path, choices, and consequences Surprises hide around every corner: scavenge weapons, armor, plants, animals, and more. Utilize special technology: the in-game Sheikah Slate controls objects and enemies in fun ways. Shrines offer hundreds of clever challenges even Legend of Zelda series veterans won’t see coming",
"brand": "Nintendo",
"price": 39,
"genre": "adventure",
"esrb-rating": "E (Everyone 10+)",
"ratings": 4.8,
"image": "https://media.gamestop.com/i/gamestop/10141904/The-Legend-of-Zelda-Breath-of-the-Wild---Nintendo-Switch?fmt=auto&$pdp-gallery$"
},
{
"title": "Pokemon Legends: Arceus ",
"console": "Nintendo Switch",
"features": "Action meets RPG in this new take on the Pokémon series.Unleash moves in the speedy agile style or the powerful strong style in battles.Learn about the Mythical Pokémon Arceus, the key to this mysterious tale.Study Pokémon behaviors, sneak up on them, and toss a well-aimed PokéBall to catch them.Travel to the Hisui region - the Sinnoh of old - and build the region's first Pokédex.",
"brand": "Nintendo",
"price": 59.99,
"genre": "adventure",
"esrb-rating": "E (Everyone 10+)",
"ratings": 4.7,
"image": "https://media.gamestop.com/i/gamestop/11120694/Pokemon-Legends-Arceus---Nintendo-Switch?fmt=auto&$pdp-gallery$"
},
{
"title": "Forza Horizon 5 ",
"console": "Xbox One",
"features": "Explore a world of striking contrast and beauty. Discover living deserts, lush jungles, historic cities, hidden ruins, pristine beaches, vast canyons, and a towering snow-capped volcano.Immerse yourself in a deep campaign with hundreds of challenges that reward you for engaging in the activities you love. Meet new characters and choose the outcomes of their Horizon Story missions.Take on awe-inspiring weather events such as towering dust storms and intense tropical storms as Mexico’s unique, dynamic seasons change the world every week. Keep coming back for new events, challenges, collectibles, and rewards, and new areas to explore. No two seasons will ever be the same.",
"brand": "Microsoft",
"price": 34.99,
"genre": "racing",
"esrb-rating": "E (Everyone)",
"ratings": 4.6,
"image": "https://media.gamestop.com/i/gamestop/11148773/Forza-Horizon-5---Xbox-Series-X?fmt=auto&$pdp-gallery$"
},
{
"title": "Grand Theft Auto V",
"console": "Xbox One",
"features": "Grand Theft Auto Online - Discover an ever-evolving world of choices and ways to play as you climb the criminal ranks of Los Santos and Blaine County in the ultimate shared Online experience.Launch Your Criminal Empire - Launch business ventures from your Maze Bank West Executive Office, research powerful weapons technology from your underground Gunrunning Bunker and use your Counterfeit Cash Factory to start a lucrative counterfeiting operation.Weapons, Clothing & Tattoos - You’ll also get access to the Compact Grenade Launcher, Marksman Rifle and Compact Rifle along with Stunt Racing Outfits, Biker Tattoos and more.Grand Theft Auto V - When a young street hustler, a retired bank robber and a terrifying psychopath land themselves in trouble, they must pull off a series of dangerous heists to survive in a city in which they can trust nobody, least of all each other.",
"brand": "Rockstar Games",
"price": 16.99,
"genre": "action",
"esrb-rating": "M (Mature 17+)",
"ratings": 4.5,
"image": "https://media.gamestop.com/i/gamestop/10115457?fmt=auto&$pdp-gallery$"
},
{
"title": "Call of Duty: Modern Warfare II",
"console": "Xbox One",
"features": "Modern Warfare II - Call of Duty®: Modern Warfare® II drops players into an unprecedented global conflict that features the return of the iconic operators of Task Force 141.Launch Content - Modern Warfare: II will launch with a globe-trotting single-player campaign, immersive Multiplayer combat and a narrative-driven, co-op Special Ops experience.Features - Infinity Ward brings fans state-of-the-art gameplay, with all-new gun handling, advanced AI system, a new Gunsmith and a suite of other gameplay and graphical innovations that elevate the franchise to new heights.",
"brand": "Activision",
"price": 64.99,
"genre": "shooter",
"esrb-rating": "M (Mature 17+)",
"ratings": 2.5,
"image": "https://media.gamestop.com/i/gamestop/11206901-11206902?fmt=auto&$pdp-gallery$"
},
{
"title": "Sniper Elite 4",
"console": "Xbox One",
"features": "New theatre of war - Italy - with most varied environments of any Sniper Elite game. Mountains, forests, fortresses, beaches, fishing towns. Largest campaign in series history. Playtime varies but patient players could take dozens of hours to see everything. New traversal mechanics (climbing, shimmying, leaping and more) allows players more ways to approach/kill/escape. More weapons than any Sniper Elite game before.",
"brand": "Sold Out Sales",
"price": 21.99,
"genre": "shooter",
"esrb-rating": "M (Mature 17+)",
"ratings": 4.4,
"image": "https://media.gamestop.com/i/gamestop/10131815/Sniper-Elite-4---Xbox-One?fmt=auto&$pdp-gallery$"
},
{
"title": "Far Cry 5 ",
"console": "Xbox One",
"features": "Solo, Online Co-Op or Multiplayer - The fate of Hope County is in your hands. Take on the cult solo or team up with a fellow resister in co-op mode and wreak havoc upon Joseph Seed and his band of cult followers. You'll have everything at your disposal – from hired guns to hired fangs and the sickest arsenal this side of the Mississippi.For Hire Systems - You can meet and recruit friends, guns, or Fangs for hire in this open world. Although they may need some help sorting out their own problems before lending you a hand.A World That Hits Back - When you hit hard, the enemy’s going to hit back harder. Far Cry 5®'s dynamic AI tracks the effect you’re having in the game, and alters the enemy's strategy against you. Be prepared: The cult will boost their efforts when you become less of a nuisance and more of a threat.Activities - Even when you feel like taking a break from the campaign, you can take in some leisurely fishing, hunting, and crafting before diving back into your quest.",
"brand": "Ubisoft",
"price": 9.99,
"genre": "action",
"esrb-rating": "M (Mature 17+)",
"ratings": 4.5,
"image": "https://media.gamestop.com/i/gamestop/10148966/Far-Cry-5-Deluxe-Edition?fmt=auto&$pdp-gallery$"
},
{
"title": "Cyberpunk 2077",
"console": "PS4",
"features": "Play as a Mercenary Outlaw - Become a cyberpunk, an urban mercenary equipped with cybernetic enhancements and build your legend on the streets of Night City.Steal the Implant that Grants Eternal Life - Take the riskiest job of your life and go after a prototype implant that is the key to immortality.Live in the City of the Future - Enter the massive open world of Night City, a megalopolis that sets new standards in terms of visuals, complexity and depth.",
"brand": "CD Projekt RED",
"price": 29.99,
"genre": "action",
"esrb-rating": "M (Mature 17+)",
"ratings": 3.5,
"image": "https://media.gamestop.com/i/gamestop/11094722/Cyberpunk-2077---PlayStation-4?fmt=auto&$pdp-gallery$"
},
{
"title": "Red Dead Redemption 2",
"console": "PS4",
"features": "Explore The Rugged Heartland Of America - Discover some of the towns dotted across the vast and varied landscape of Red Dead Redemption 2; from the forests of West Elizabeth to the mountains of Ambarino to the plains of New Hanover to the swamps of Lemoyne.Weaponry - Detail, depth and choice define every aspect of Red Dead Redemption 2, and weapons are no exception.Wildlife - The diverse habitats and climates of Red Dead Redemption 2 are home to around 200 species of animals, birds and fish, all of which behave and respond to their environment in a unique way.",
"brand": "Rockstar Games",
"price": 20.00,
"genre": "shooter",
"esrb-rating": "M (Mature 17+)",
"ratings": 4.6,
"image": "https://media.gamestop.com/i/gamestop/10138091?fmt=auto&$pdp-gallery$"
},
{
"title": "The Last of Us Part II ",
"console": "PS4",
"features": "A Complex and Emotional Story - Experience the escalating moral conflicts created by Ellie's relentless pursuit of vengeance. The cycle of violence left in her wake will challenge your notions of right versus wrong, good versus evil, and hero versus villain.Tense and Desperate Action-Survival Gameplay - New and evolved gameplay systems deliver upon the life-or-death stakes of Ellie's journey through the hostile world. Feel her desperate struggle for survival through improved features such as high-intensity melee combat, fluid movement, and dynamic stealth. A broad variety of weapons, crafting items, skills, and upgrades allows you to personalize Ellie's capabilities to your play style.",
"brand": "Sony",
"price": 10.00,
"genre": "action",
"esrb-rating": "M (Mature 17+)",
"ratings": 4.0,
"image": "https://media.gamestop.com/i/gamestop/11097389/The-Last-of-Us-Part-II---PlayStation-4?fmt=auto&$pdp-gallery$"
},
{
"title": "Assassin's Creed Valhalla",
"console": "PS4",
"features": "Visceral Combat - Dual-wield powerful weapons such as axes, swords and even shields to relive the ruthless fighting style of the Viking warriors.Lead Epic Raids - Launch massive assaults throughout England. Lead your clan in surprise attacks from your longship and then bring the riches back to your people.A Dark-Age Open World - Sail from the harsh and mysterious shores of Norway to the beautiful but forbidding kingdoms of England and beyond.",
"brand": "Sony",
"price": 19.99,
"genre": "action",
"esrb-rating": "M (Mature 17+)",
"ratings": 4.3,
"image": "https://media.gamestop.com/i/gamestop/11102093/Assassins-Creed-Valhalla---PlayStation-4?fmt=auto&$pdp-gallery$"
},
{
"title": "God of War Ragnarok",
"console": "PS4",
"features": "Venture through all Nine Realms towards the prophesied battle that will end the world, Explore in wonder through stunning mythological landscapes, Vanquish Norse gods and monsters alike in fluid, expressive combat",
"brand": "Sony",
"price": 59.99,
"genre": "action",
"esrb-rating": "M (Mature 17+)",
"ratings": 4.3,
"image": "https://media.gamestop.com/i/gamestop/11206962-11206960?fmt=auto&$pdp-gallery$"
}])
