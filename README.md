This repo is a simple example on how to use Lunrjs, a Full-Text search library. The search is based off of the following json data.
```json
[
    {
        "title": "The Creator",
        "text": "The Creator is a 2023 American science fiction action film produced and directed by Gareth Edwards, who co-wrote the screenplay with Chris Weitz. It stars John David Washington, Gemma Chan, Ken Watanabe, Sturgill Simpson and Allison Janney. Set in 2070, 15 years after a nuclear detonation in Los Angeles and a war against artificial intelligence, an ex-special forces agent is recruited to hunt down and kill the \"Creator,\" who has developed a mysterious weapon with the power to end the war."
    },
    {
        "title": "Kill Bill",
        "text": "Kill Bill: Volume 1 is a 2003 American martial arts film written and directed by Quentin Tarantino. It stars Uma Thurman as the Bride, a former assassin who swears revenge on a group of assassins (Lucy Liu, Michael Madsen, Daryl Hannah, and Vivica A. Fox) and their leader, Bill (David Carradine), who tried to kill her and her unborn child. Her journey takes her to Tokyo, where she battles the yakuza."
    },
    {
        "title": "The Animatrix",
        "text": "The Animatrix (Japanese: アニマトリックス, Hepburn: Animatorikkusu) is a 2003 American-Japanese adult animated science-fiction anthology film produced by the Wachowskis.[2] The film compiles nine animated short films, detailing the backstory of The Matrix film series, revealing the major events of the apocalyptic war between humanity and machines which led to the creation of the Matrix in the two parts of The Second Renaissance short, in addition to providing side stories that expand the universe and tie into the film series."
    },
    {
        "title": "The Creator",
        "text": "The Creator is a 2023 American science fiction action film produced and directed by Gareth Edwards, who co-wrote the screenplay with Chris Weitz. It stars John David Washington, Gemma Chan, Ken Watanabe, Sturgill Simpson and Allison Janney. Set in 2070, 15 years after a nuclear detonation in Los Angeles and a war against artificial intelligence, an ex-special forces agent is recruited to hunt down and kill the \"Creator,\" who has developed a mysterious weapon with the power to end the war."
    },
    {
        "title": "John Wick: Chapter 2",
        "text": "John Wick: Chapter 2 is a 2017 American neo-noir action thriller film directed by Chad Stahelski and written by Derek Kolstad. The film is sequel to John Wick (2014) and the second installment in the John Wick franchise. It stars Keanu Reeves as the eponymous character, alongside Common, Laurence Fishburne, Riccardo Scamarcio, Ruby Rose, Lance Reddick, Peter Stormare, Bridget Moynahan, Franco Nero, John Leguizamo, and Ian McShane. In the film, retired hitman John Wick is forced back into his old life to fulfill a blood oath to crime lord Santino D'Antonio (Scamarcio)."
    },
    {
        "title": "The Creator",
        "text": "The Creator is a 2023 American science fiction action film produced and directed by Gareth Edwards, who co-wrote the screenplay with Chris Weitz. It stars John David Washington, Gemma Chan, Ken Watanabe, Sturgill Simpson and Allison Janney. Set in 2070, 15 years after a nuclear detonation in Los Angeles and a war against artificial intelligence, an ex-special forces agent is recruited to hunt down and kill the \"Creator,\" who has developed a mysterious weapon with the power to end the war."
    },
    {
        "title": "Good Burger",
        "text": "Good Burger is a 1997 American teen comedy film directed by Brian Robbins, written by Dan Schneider with Kevin Kopelow and Heath Seifert, and starring Kenan Thompson and Kel Mitchell. The film is a spin-off of the \"Good Burger\" comedy sketch from the Nickelodeon variety series All That, with Mitchell reprising his role as Ed. The story follows Dexter, a high school student who takes a job at a fast-food restaurant called Good Burger in order to pay off the damages he made to his teacher's car as he and Ed, his dimwitted co-worker, stumble upon an evil plot by a rival fast-food restaurant."
    },
    {
        "title": "Spider-Man",
        "text": "Spider-Man follows Peter Parker (Tobey Maguire), an orphaned high schooler who pines after popular girl-next-door Mary Jane Watson (Kirsten Dunst). While on a science class field trip at Columbia University, a genetically-engineered \"super spider\" bites Peter. As a result, Peter gains superhuman abilities, including increased strength, speed, and the abilities to scale walls and generate organic webbing. After his beloved Uncle Ben (Cliff Robertson) is murdered, the teenager realizes that he must use his newfound abilities to protect New York City. Meanwhile, wealthy industrialist Norman Osborn (Willem Dafoe), the father of Peter's best friend Harry Osborn (James Franco), subjects himself to an experimental performance-enhancing serum, which creates a psychotic and murderous split personality. Donning a military battle suit, Norman becomes a freakish \"Green Goblin\", who begins to terrorize the city. Peter, as Spider-Man, now must battle with the Goblin, all while dealing with personal situations involving his domestic and his love life."
    },
    {
        "title": "Pan's Labyrinth",
        "text": "Pan's Labyrinth (Spanish: El laberinto del fauno, lit. 'The Labyrinth Of The Faun') is a 2006 dark fantasy film[4] written, directed and co-produced by Guillermo del Toro. The film stars Ivana Baquero, Sergi López, Maribel Verdú, Doug Jones, and Ariadna Gil. The story takes place in Spain in the summer of 1944, during the early Francoist period, five years after the Spanish Civil War. The narrative intertwines this real world with a mythical world centered on an overgrown, abandoned labyrinth and a mysterious faun creature, with whom the main character, Ofelia, interacts. Ofelia's stepfather, the Falangist Captain Vidal, hunts the Spanish Maquis who fight against the Francoist regime, while Ofelia's pregnant mother grows increasingly ill. Ofelia meets several strange and magical creatures who become central to her story, leading her through the trials of the old labyrinth garden. The film employs make-up, animatronics, and CGI effects to bring life to its creatures."
    },
    {
        "title": "Akira",
        "text": "Akira (Japanese: アキラ) is a 1988 Japanese animated cyberpunk action film[4] directed by Katsuhiro Otomo, produced by Ryōhei Suzuki and Shunzō Katō, and written by Otomo and Izo Hashimoto, based on Otomo's 1982 manga of the same name. Set in a dystopian 2019, it tells the story of Shōtarō Kaneda, the leader of a biker gang whose childhood friend, Tetsuo Shima, acquires incredible telekinetic abilities after a motorcycle accident, eventually threatening an entire military complex amid chaos and rebellion in the sprawling futuristic metropolis of Neo-Tokyo."
    }
    
]
```

![image](https://github.com/oiver555/Searching-with-Lunrjs/assets/69017748/801a30f0-04d3-4bb0-8d82-24e8031adac8)

