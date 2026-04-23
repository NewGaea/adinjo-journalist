### III.2 - Pokémon Yellow Script Changes
#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#
#$#$#$#$#$#$#$                               $#$#$#$#$#$#$#
#$# [03'02] ---        Pokemon Yellow       --- [03'02] #$#
#$#$#$#$#$#$#$                               $#$#$#$#$#$#$#
#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#

While lines with different wording than in Red/Blue are transcribed herein,
script wherefor merely punctuation has been altered is omitted.


#$#$#$#$#$#$#$#$#$#$#$#$#$#$#
$#  02'01  |  Pallet Town  #$
#$#$#$#$#$#$#$#$#$#$#$#$#$#$#

   [ Opening ]
* - An image of Pikachu appears instead of a Nidorino. The first option for
    Red's name is Yellow; the rival's is Blue.





   [ Social Script ]
* - Oak Pokemon Research Lab:

Blue      : Yo YELLOW! Gramps isn't around! I ran here 'cos he said he had
            a POKEMON for me.

Poke Ball : That's a POKE BALL. There's a POKEMON inside!





   [ Oak Pokemon Research Lab ]
* - When trying to leave town via the grassy path to the north:

Oak       : Hey! Wait! Don't go out!

* - Oak approaches Yellow.

Oak       : That was close! Wild POKEMON live in tall grass!

* - A Pikachu appears, ready to fight. Oak catches it in a Poke Ball.

Oak       : Whew... A POKEMON can appear anytime in tall grass. You need your
            own POKEMON for your protection. I know! Here, come with me!

* - He takes Yellow to his laboratory. They approach a table upon which one
    Poke Ball has been placed, and next to which Blue is present.

Blue      : Gramps! I'm fed up with waiting!

Oak       : Hmm? BLUE? Why are you here already? I said for you to come by
            later... Ah, whatever! Just wait there.

            Look, YELLOW! Do you see that ball on the table? It's called a
            POKE BALL. It holds a POKEMON inside. You may have it! Go on,
            take it!

Blue      : Hey! Gramps! What about me?

Oak       : Be patient, BLUE, I'll give you one later.



* - Before selecting a Pokemon:

Oak       : Go ahead, it's your!

Blue      : Humph! I'll get a better POKEMON than you!

* - Upon attempting to leave:

Oak       : Hey! Don't go away yet!



* - As Yellow approaches the Poke Ball, Blue shoves him aside and takes it.

Blue      : No way! Yellow, I want this POKEMON!

<game>    : BLUE snatched the POKEMON!

Oak       : BLUE! What are you doing?

Blue      : Gramps, I want this one!

Oak       : But, I... Oh, all right then. That POKEMON is yours. I was going to
            give you one anyway... YELLOW, come over here.

            YELLOW, this is the POKEMON I caught earlier. You can have it.
            I caught it in the wild and it's not tame yet.



* - Before leaving:

Oak       : If a wild POKEMON appears, your POKEMON can fight against it!
            Afterward, go on to the next town.

Blue      : Heh, my POKEMON looks a lot stronger.



* - Upon attempting to leave:

Blue      : Wait YELLOW! Let's check out our POKEMON! Come on, I'll take you on!

* - His Pokemon is an Eevee. At the battle's end:

Blue      : WHAT? Unbelievable! I picked the wrong POKEMON! Okay! I'll make my
            POKEMON fight to toughen it up! RED! Gramps! Smell you later!

* - He takes his leave of the laboratory, as well as the town.

    Yellow's Pikachu comes out of its Poke Ball.

Oak       : What? Would you look at that! It's odd, but it appears that your
            PIKACHU dislikes POKE BALLs. You should just keep it with you.
            That should make it happy! You can talk to it and see how it feels
            about you.





     [ Social Script ]
Oak       : You should talk to it and see how it feels.

Mother    : YELLOW, if you drive your POKEMON too hard, they'll dislike you.
            You should take a rest.

            Oh good! You and your POKEMON are looking great! Take care now!


#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#
$#  02'03  |  Viridian City  #$
#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#

   [ Social Script  -  Buildings ]
* - Pokemon Mart:

[004]     : This shop sells a lot of PARLYZ HEALs.

[005]     : The shop finally has some POTIONs in stock.

-----
* - In the house with [006] and [007].

[010]     : Sis says POKEMON will become tame if you treat them nicely.





   [ Pallet Town  -  Oak's laboratory ]
<game>    : YELLOW delivered OAK's PARCEL.

Oak       : Ah! This is the custom POKE BALL I ordered! Thanks, YELLOW!
            By the way, I must ask you to do something for me.

* - Blue enters the building.

Blue      : Gramps! Gramps, my POKEMON has grown stronger! Check it out!

Oak       : Ah, BLUE, good timing! I needed to ask both of you to do something
            for me. On the desk there is my invention, POKEDEX! It automatically
            records data on POKEMON you've seen or caught! It's a hi-tech
            encyclopedia!

            YELLOW and BLUE! Take these with you!

* - Thereafter, the event continues as in Red/Blue.





   [ Pallet Town  -  Blue's house ]
* - After leaving and reentering, having acquired the map:

Blue's Sis: Spending time with your POKEMON makes them more friendly to you.





   [ Social Script ]
[004]     : Ahh, I've had my coffee now and I feel great! Sure you can go
            through! I'm sorry I was so rude to you! I see you're using a
            POKEDEX. I'll show you how to catch POKEMON as my apology.

* - He finds a wild Rattata and tries to catch it, but it escapes.

[004]     : That didn't work! I must be losing my touch. I've run out of POKE
            BALLS too. I have to get some at the POKEMON MART.



* - Upon speaking to him once he returns:

[004]     : Hmm? You want me to show you how to catch POKEMON again?

            -----------------------------------------------
                 -(YES)
            Dandy! Watch what I do closely now!

              * - He finds another Rattata, which is successfully caught.

            First, you need to weaken the target POKEMON.



                 -(NO)
            Oh... I'm not good enough for you.
            -----------------------------------------------


#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#
$#  02'04  |  Route 2 & Viridian Forest  #$
#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#

   [ Pre-forest ]
[002]     : You have to roam far to get new kinds of POKEMON. Look for other
            types outside of VIRIDIAN FOREST.





   [ Forest ]
Trainer 04:{Start} Hi, do you have a PIKACHU?
           {Class} LASS
           {End} Oh no, really?
           {After} I looked forever, but I never found a PIKACHU here!

Trainer 05:{Start} I'm gonna be the best. You just can't beat me!
           {Class} BUG CATCHER
           {End} After all I did...
           {After} A METAPOD is cool because its attack is its defense!



#$#$#$#$#$#$#$#$#$#$#$#$#$#$#
$#  02'05  |  Pewter City  #$
#$#$#$#$#$#$#$#$#$#$#$#$#$#$#

   [ Social Script  -  Buildings ]
* - Pokemon Center:

[009]     : POKEMON CENTERS are wonderful! They heal POKEMON completely.
            Even conditions like sleep, burn, poison and others are cured.





   [ Social Script  -  Museum (via main entrance) ]
[007]     :{1} I'd like to get that PIKACHU off you, but it's too attached
               to you.
           {2} Your PIKACHU looks untamed. May I have it for my daughter?





   [ Pokemon Gym ]
[001]     : Hiya! I can tell you have what it takes to become a POKEMON champ!
            I'm no trainer, but I can tell you how to win! Let me take you to
            the top!

            -----------------------------------------------
                 -(YES)
            All right! Let's get happening!

            It will be tough for your PIKACHU at this GYM! Electric attacks are
            harmless to BROCK's ground-type POKEMON.



                 -(NO)
            It's a free service! Let's get happening!

            The 1st POKEMON out in a match is at the top of the POKEMON LIST!
            By changing the order of POKEMON, matches could be made easier!
            -----------------------------------------------

Brock     :{After} There are all kinds of trainers in the world! Some raise POKEMON
               for fights. Some see them as pets. I'm in training to become a
               POKEMON breeder. If you take your POKEMON training seriously,
               go visit the GYM in CERULEAN and test your abilities!


#$#$#$#$#$#$#$#$#$#$#$#$#$
$#  02'07  |  Mt. Moon  #$
#$#$#$#$#$#$#$#$#$#$#$#$#$

* - Shortly after taking the Helix/Dome Fossil, two members of Team Rocket--
    who look identical to Jessie and James of the series' anime adaptation--
    approach Yellow. Both are identified as merely "Rocket," so which of them
    is speaking cannot be determined.

Jess/James:{Start} Stop right there! That fossil is TEAM ROCKET's! Surrender now,
               or prepare to fight!
           {Class} ROCKET
           {End} A brat beat us?

               TEAM ROCKET, blast off at the speed of light!

                 * - They disappear.


#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#
$#  02'09  |  Cerulean City  #$
#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#

   [ Social Script  -  Outside ]
<game>    : ELECTRODE is loafing around...
[003]     : ELECTRODE, TACKLE! No! You blew it again!

[006]     : These poor people here were robbed. We're positive that TEAM ROCKET
            is behind this terrible deed. Even our POLICE FORCE has trouble
            with the ROCKETs!





   [ Social Script  -  Buildings ]
* - [009] and [010] are no longer present. In their place:

[014]     : I take care of injured POKEMON. I nursed this BULBASAUR back to
            health. It needs a good trainer to take care of it now.

              * - After having defeated Misty, she continues:

            I know! Would you take care of this BULBASAUR?

            -----------------------------------------------
                 -(YES)
            Please take care of BULBASAUR!

              * - When speaking to her again:

            Is BULBASAUR doing well?



                 -(NO)
            Oh... That's too bad...
            -----------------------------------------------

Oddish    : Orddissh!

Sandshrew : Pikii!

Bulbasaur : Bubba! Zoar!





   [ Pokemon Gym ]
Misty     :{Start} Hi, you're a new face! What's your policy on POKEMON? What is
               your approach? My policy is an all-out offensive with water-type
               POKEMON! MISTY, the world-famous beauty, is your host! Are you
               ready, sweetie?

           {End} I can't believe I lost! All right! You can have the CASCADEBADGE
               to show you beat me!

               The CASCADEBADGE makes all POKEMON up to L30 obey! That includes
               even outsiders! There's more, you can now use CUT anytime!
               You can CUT down small bushes to open new paths! You can also
               have my favorite TM!

                 * - If the inventory is full:
               You better make room for this!

                 * - If there is room, she provides TM11.

           {After} TM11 teaches BUBBLEBEAM! Use it on an aquatic POKEMON!


#$#$#$#$#$#$#$#$#$#$#$#$#$
$#  02'10  |  Route 24  #$
#$#$#$#$#$#$#$#$#$#$#$#$#$

[001]     : I'm not good at raising POKEMON. I should release my CHARMANDER
            because I haven't raised it well... If you promise me you'll care
            for it, it's yours.

            -----------------------------------------------
                 -(YES)
            Take good care of my CHARMANDER!

              * - When speaking to him again:

            How's CHARMANDER doing?



                 -(NO)
            Oh... I'd better release it then.
            -----------------------------------------------


#$#$#$#$#$#$#$#$#$#$#$#$#$
$#  02'11  |  Route 25  #$
#$#$#$#$#$#$#$#$#$#$#$#$#$

Trainer 01:{Start} I just got down from MT.MOON, but I'm ready!
           {Class} HIKER
           {End} You worked hard!
           {After} Drat! A ZUBAT bit me back in there.

Trainer 05:{Start} Hi! My boy friend is cool!
           {Class} LASS
           {End} I'm in a slump!
           {After} I wish my guy was as good as you!


#$#$#$#$#$#$#$#$#$#$#$#$#
$#  02'12  |  Route 5  #$
#$#$#$#$#$#$#$#$#$#$#$#$#

   [ Building 3 ]
* - [003] wants a Cubone, in exchange for her Machoke (nicknamed Ricky).


#$#$#$#$#$#$#$#$#$#$#$#$#
$#  02'13  |  Route 6  #$
#$#$#$#$#$#$#$#$#$#$#$#$#

* - Trainer 02 and 03 are speaking to each other.

Trainer 02:{Start} I'm doing this out of love. Leave me alone!
           {Class} JR.TRAINER  (Male)
           {End} No, this can't be...
           {After} My love will leave me in disgust.

Trainer 03:{Start} I'm training for my love. Don't bother me!
           {Class} JR.TRAINER  (Female)
           {End} My textbook never...
           {After} Now I understand, POKEMON isn't about calculated numbers.


#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$
$#  02'14  |  Vermilion City  #$
#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$

   [ Social Script  -  Outside ]
[004]     : I just caught a SQUIRTLE that was always getting into mischief.
            I think it needs a good trainer to set it straight.





   [ Social Script  -  Buildings ]
* - Pokemon Fan Club:

[008]     : I chair the POKEMON Fan Club! I have more than 100 POKEMON.
            I love them all! I'm very fussy when it comes to POKEMON!
            So... Did you come to hear me brag about my POKEMON?

* - [011]'s Pikachu is now a Clefairy. Yellow's Pikachu seems to take quite an
    interest in the Clefairy, such that hearts appear above its head.

Clefairy  : Pippii!

-----

* - In place of [007]:

[013]     : Once a POKEMON learns an HM, the technique can't be replaced.
            Better think carefully before you teach HM moves.





   [ Pokemon Gym ]
Lt. Surge :{Start} Ten-hut! Welcome to VERMILION GYM! Will you look at that,
               a pint-size challenger! Hahaha! You've got big and brassy nerves
               to take me on with your puny power! A POKEMON battle is war!
               I'll show you, civilian! I'll shock you into surrender!




   [ Social Script  -  Outside ]
[004]     : You have the THUNDERBADGE!? You must be a good trainer!
            I just caught a SQUIRTLE that was always getting into mischief.
            Would you take good care of it?

            -----------------------------------------------
                 -(YES)
            OK! Please treat SQUIRTLE right!

              * - When speaking to her again:

            How is SQUIRTLE doing?



                 -(NO)
            Oh... What am I to do now?
            -----------------------------------------------


#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$
$#  02'15  |  Diglett's Cave & Route 2  #$
#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$

   [ Route 2 ]
* - [002] wants a Clefairy, in exchange for his Mr. Mime (nicknamed Miles).


#$#$#$#$#$#$#$#$#$#$#$#$#
$#  02'16  |  Route 9  #$
#$#$#$#$#$#$#$#$#$#$#$#$#

Trainer 03:{Start} I aim to be the ultimate trainer!
           {Class} YOUNGSTER
           {End} My SANDSHREW lost?
           {After} I'll restart my 100-win streak with SANDSHREW.


#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$
$#  02'20  |  Celadon City  #$
#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$

   [ Social Script  -  Outside ]
[003]     : I got my KOFFING from my friend! We get along now, because I was
            very nice to it!





   [ Social Script  -  Celadon Mansion ]
* - First floor:

[001]     : My dear POKEMON keep me company. MEOWTH even brings money home!

            Oh, you have an adorable PIKACHU with you.

           {1} Why don't you take more care with PIKACHU?
           {2} You must be happy to have a POKEMON that cute.
           {3} Your PIKACHU seems tamed.
           {4} Your PIKACHU looks happy with you.
           {5} You look like a fantastic duo. You're making me jealous!





   [ Social Script  -  Pokemon Mart ]
* - Fourth floor:

[009]     : I'm getting a gift for COPYCAT in CERULEAN CITY. It's got to be a
            POKE DOLL. They are trendy!





   [ Rocket Game Corner ]
* - Trainers 10 and 11 have disappeared from Giovanni's floor. In their place,
    Jessie and James approach upon entering.

Jess/James:{Start} Not another step, brat! How dare you humiliate us at MT.MOON!
               It's payback time, you brat!
           {Class} ROCKET
           {End} Such a dreadful twerp!

               Looks like TEAM ROCKET's blasting off again!

                 * - They disappear.


#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#
$#  02'21  |  Lavender Town  #$
#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#

   [ Pokemon Tower ]
* - Trainers 14, 15 and 16 are not present on the highest floor. In their place,
    Jessie and James appear.

Jess/James:{Start} Stop right there! Grampa here wanted to complain, so we're
               setting him straight. So render yourself invisible, or prepare
               to fight!
           {Class} ROCKET
           {End} You will regret this!

               Looks like TEAM ROCKET's blasting off again!

                 * - They disappear.


#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$
$#  02'22  |  Saffron City  #$
#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$

   [ Silph Co. Office Building ]
* - Seventh floor:

Trainer 19:{Start} Aha! I smell a little rat!

-----
* - Seventh floor, via teleportation:

Blue      :{End} Oh-oh! So, you are ready for BOSS ROCKET!

-----
* - Eleventh floor, via teleportation:

    In place of Trainer 31, Jessie and James appear.

Jess/James:{Start} Hold it right there, brat! Our BOSS is in a meeting! You better
               not disturb him!
           {Class} ROCKET
           {End} Like always...

               TEAM ROCKET, blast off at the speed of light! Again...

                 * - They disappear.





   [ Pokemon Gym ]
Trainer 03:{After} Psychic POKEMON fear only bugs!


#$#$#$#$#$#$#$#$#$#$#$#$#$
$#  02'23  |  Route 11  #$
#$#$#$#$#$#$#$#$#$#$#$#$#$

* - [003] wants a Lickitung, in exchange for his Dugtrio (nicknamed Gurio).


#$#$#$#$#$#$#$#$#$#$#$#$#$
$#  02'30  |  Route 18  #$
#$#$#$#$#$#$#$#$#$#$#$#$#$

* - [002] wants a Tangela, in exchange for his Parasect (nicknamed Spike).


#$#$#$#$#$#$#$#$#$#$#$#$#$#$#
$#  02'32  |  Sea Roue 19  #$
#$#$#$#$#$#$#$#$#$#$#$#$#$#$#

* - A house is now located on the beach south of Fuchsia City. Therein:

Poster 1  : 30 years of waves!
            SURFIN' DUDE

Poster 2  : SUMMER BEACH HOUSE
            POKEMON welcome!

Poster 3  : The sea unites all in surfdom!

Pikachu   : Pikaa

SurfinDude: Dogs and burgers on special today!



* - If, via special methods, Yellow's Pikachu knows Surf, then:

SurfinDude: Whoa! Your PIKACHU knows how to SURF! So, I'm not alone... Great!
            You earned the right to SURF with the DUDE! Give it a go?

            -----------------------------------------------
                 -(YES)
              * - Pikachu goes for a surfing session, rated on remaining HP
                  and "radness."

            Use Control Pad to Surf Rad!



                 -(NO)
            Come SURF anytime, my friend!
            -----------------------------------------------



* - The writing upon the posters has now been changed.

Poster 1  : SURFIN' DUDE's scribbles... When I shoot the tube, the tunes hit
            the groove!

Poster 2  : SURFING TIP 1!
            After flips, line the board up with a wave for a cool effect!

Poster 3  : SURFING TIP 2!
            Pulling flips in a jump is totally rad!


#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#
$#  02'34  |  Cinnabar Island  #$
#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#

   [ Social Script  -  Buildings ]
* - [007] wants a Golduck, in exchange for his Rhydon (nicknamed Buffy).
    When speaking to him after the trade, he says, "Hello there! Your old
    GOLDUCK is magnificent!"

    [009] wants a Growlithe, in exchange for her Dewgong (nicknamed Cezanne).

    [012] wants a Kangaskhan, in exchange for his Muk (nicknamed Sticky).





   [ Pokemon Gym ]
* - Preceding the questions, the machines state:

Question 1: POKEMON Quiz! Get it right and the door opens to the next room!
            Get it wrong and face the trainer blocking the way! If you want to
            conserve your POKEMON for the GYM LEADER... Then get it right!
            Here we go!

Question2+: POKEMON Quiz! Test your skill!



* - Before attempting the corresponding question, the trainers say:

Trainer 01: This GYM is also known as the QUIZ GYM. You have to take a quiz
            if you want to see BLAINE. You don't have to fight us if you get
            it right.

* - Trainer 02 is not associated with a question.

Trainer 03: Think you can do it?
Trainer 04: This one's tricky!
Trainer 05: POKEMON enjoy quizzes too!
Trainer 06: I like it here at the QUIZ GYM.
Trainer 07: This is the last question.


#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$
$#  02'40  |  Indigo Plateau  #$
#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$

Agatha    :{End} Woo-hoo! You're something special, child!

               You win! I see what the old duff sees in you now! I have nothing
               else to say! Run along now, child!


#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#
#$#$#$#$#$#$#$                               $#$#$#$#$#$#$#
#$# [03'03] ---           Pokedex           --- [03'03] #$#
#$#$#$#$#$#$#$                               $#$#$#$#$#$#$#
#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#$#

"{1}"  =  Red, Blue
"{2}"  =  Yellow


#$#$#$#$#$#$#$#$#$#$#$#$#$#$#
$#  Pokedex Rating System  #$
#$#$#$#$#$#$#$#$#$#$#$#$#$#$#

<game>    : Accessed PROF.OAK's PC. Accessed POKEDEX Rating System. Want to get
            your POKEDEX rated?

            -----------------------------------------------
                 -(YES)
            POKEDEX completion is: <###> POKEMON seen <###> POKEMON owned

            PROF.OAK's Rating:   <see below>

            Closed link to PROF.OAK's PC.



                 -(NO)
            Closed link to PROF.OAK's PC.
            -----------------------------------------------

* - The rating is determined by the number of Pokemon that have been obtained;
    the amount of Pokemon that have been encountered is irrelevant.

001  : You still have lots to do. Look for POKEMON in grassy areas!
010  : You're on the right track! Get a FLASH HM from my AIDE!
020  : You still need more POKEMON! Try to catch other species!
030  : Good, you're trying hard! Get an ITEMFINDER from my AIDE!
040  : Looking good! Go find my AIDE when you get 50!
050  : You finally got a least 50 species! Be sure to get EXP.ALL from my AIDE!

060  :{1} Ho! This is getting even better!
      {2} Oh! This is getting even better!
070  : Very good! Go fish for some marine POKEMON!
080  : Wonderful! Do you like to collect things?
090  : I'm impressed! It must have been difficult to do!
100  : You finally got at least 100 species I can't believe how good you are!

110  : You even have the evolved forms of POKEMON! Super!
120  : Excellent! Trade with friends to get some more!
130  : Outstanding! You've become a real pro at this!
140  : I have nothing left to say! You're the authority now!
150  :{1} Your POKEDEX is entirely complete Congratulations!
      {2} Your POKEDEX is fully complete! Congratulations!

* - Note: The lack of punctuation after "species" in 100 is an in-game error,
          as is the lack of punctuation after "complete" in Red/Blue 150.


#$#$#$#$#$#$#$#
$#  Entries  #$
#$#$#$#$#$#$#$#

001  BULBASAUR
     SEED
     HT  2'04"
     WT  15.0 lb

     {1} A strange seed was planted on its back at birth. The plant sprouts and
         grows with this POKEMON.

     {2} It can go for days without eating a single morsel. In the bulb on its
         back, it stores energy.

002  IVYSAUR
     SEED
     HT  3'03"
     WT  29.0 lb

     {1} When the bulb on its back grows large, it appears to lose the ability
         to stand on its hind legs.

     {2} The bulb on its back grows by drawing energy. It gives off an aroma
         when it is ready to bloom.

003  VENUSAUR
     SEED
     HT  6'07"
     WT  221.0 lb

     {1} The plant blooms when it is absorbing solar energy. It stays on the
         move to seek sunlight.

     {2} The flower on its back catches the sun's rays. The sunlight is then
         absorbed and used for energy.

004  CHARMANDER
     LIZARD
     HT  2'00"
     WT  19.0 lb

     {1} Obviously prefers hot places. When it rains, steam is said to spout
         from the tip of its tail.

     {2} The flame at the tip of its tail makes a sound as it burns. You can
         only hear it in quiet places.

005  CHARMELEON
     FLAME
     HT  3'07"
     WT  42.0 lb

     {1} When it swings its burning tail, it elevates the temperature to
         unbearably high levels.

     {2} Tough fights could excite this POKEMON. When excited, it may blow out
         bluish-white flames.

006  CHARIZARD
     FLAME
     HT  5'07"
     WT  200.0 lb

     {1} Spits fire that is hot enough to melt boulders. Known to cause forest
         fires unintentionally.

     {2} When expelling a blast of super hot fire, the red flame at the tip of
         its tail burns more intensely.

007  SQUIRTLE
     TINYTURTLE
     HT  1'08"
     WT  20.0 lb

     {1} After birth, its back swells and hardens into a shell. Powerfully
         sprays foam from its mouth.

     {2} Shoots water at prey while in the water. Withdraws into its shell
         when in danger.

008  WARTORTLE
     TURTLE
     HT  3'03"
     WT  50.0 lb

     {1} Often hides in water to stalk unwary prey. For swimming fast, it moves
         its ears to maintain balance.

     {2} When tapped, this POKEMON will put in its head, but its tail will still
         stick out a little bit.

009  BLASTOISE
     SHELLFISH
     HT  5'03"
     WT  189.0 lb

     {1} A brutal POKEMON with pressurized water jets on its shell. They are
         used for high speed tackles.

     {2} Once it takes aim at its enemy, it blasts out water with even more
         force than a fire hose.

010  CATERPIE
     WORM
     HT  1'00"
     WT  6.0 lb

     {1} Its short feet are tipped with suction pads that enable it to
         tirelessly climb slopes and walls.

     {2} If you touch the feeler on top of its head, it will release a horrible
         stink to protect itself.

011  METAPOD
     COCOON
     HT  2'04"
     WT  22.0 lb

     {1} This POKEMON is vulnerable to attack while its shell is soft, exposing
         its weak and tender body.

     {2} Hardens its shell to protect itself. However, a large impact may cause
         it to pop out of its shell.

012  BUTTERFREE
     BUTTERFLY
     HT  3'07"
     WT  71.0 lb

     {1} In battle, it flaps its wings at high speed to release highly toxic
         dust into the air.

     {2} Its wings, covered with poisonous powders, repel water. This allows
         it to fly in the rain.

013  WEEDLE
     HAIRY BUG
     HT  1'00"
     WT  7.0 lb

     {1} Often found in forests, eating leaves. It has a sharp venomous stinger
         on its head.

     {2} Beware of the sharp stinger on its head. It hides in grass and bushes
         where it eats leaves.

014  KAKUNA
     COCOON
     HT  2'00"
     WT  22.0 lb

     {1} Almost incapable of moving, this POKEMON can only harden its shell
         to protect itself from predators.

     {2} Able to move only slightly. When endangered, it may stick out its
         stinger and poison its enemy.

015  BEEDRILL
     POISON BEE
     HT  3'03"
     WT  65.0 lb

     {1} Flies at high speed and attacks using its large venomous stingers
         on its forelegs and tail.

     {2} It has 3 poisonous stingers on its forelegs and its tail. They are
         used to jab its enemy repeatedly.

016  PIDGEY
     TINY BIRD
     HT  1'00"
     WT  4.0 lb

     {1} A common sight in forests and woods. It flaps its wings at ground level
         to kick up blinding sand.

     {2} Very docile. If attack, it will often kick up sand to protect itself
         rather than fight back.

017  PIDGEOTTO
     BIRD
     HT  3'07"
     WT  66.0 lb

     {1} Very protective of its sprawling territorial area, this POKEMON will
         fiercely peck at any intruder.

     {2} This POKEMON is full of vitality. It constantly flies around its large
         territory in search of prey.

018  PIDGEOT
     BIRD
     HT  4'11"
     WT  87.0 lb

     {1} When hunting, it skims the surface of water at high speed to pick off
         unwary prey such as MAGIKARP.

     {2} This POKEMON flies at Mach 2 speed, seeking prey. Its large talons
         are feared as wicked weapons.

019  RATTATA
     RAT
     HT  1'00"
     WT  8.0 lb

     {1} Bites anything when it attacks. Small and very quick, it is a common
         sight in many places.

     {2} Will chew on anything with its fangs. If you see one, it is certain
         that 40 more live in the area.

020  RATICATE
     RAT
     HT  2'04"
     WT  41.0 lb

     {1} It uses its whiskers to maintain its balance. It apparently slows down
         if they are cut off.

     {2} Its hind feet are webbed. They act as flippers, so it can swim in
         rivers and hunt for prey.

021  SPEAROW
     TINY BIRD
     HT  1'00"
     WT  4.0 lb

     {1} Eats bugs in grassy areas. It has to flap its shorts wings at high
         speeds to stay airborne.

     {2} Inept at flying high, However, it can fly around very fast to protect
         its territory.

022  FEAROW
     BEAK
     HT  3'11"
     WT  84.0 lb

     {1} With its huge and magnificent wings, it can keep aloft without ever
         having to land for rest.

     {2} A POKEMON that dates back many years. If it senses danger, it flies
         high and away, instantly.

023  EKANS
     SNAKE
     HT  6'07"
     WT  15.0 lb

     {1} Moves silently and stealthily. Eats the eggs of birds, such as PIDGEY
         and SPEAROW, whole.

     {2} The older it gets, the longer it grows. At night, it wraps its long
         body around tree branches to rest.

024  ARBOK
     COBRA
     HT  11'06"
     WT  143.0 lb

     {1} It is rumored that the ferocious warning markings on its belly differ
         from area to area.

     {2} The frightening patterns on its belly have been studied. Six variations
         have been confirmed.

025  PIKACHU
     MOUSE
     HT  1'04"
     WT  13.0 lb

     {1} When several of these POKEMON gather, their electricity could build and
         cause lightning storms.

     {2} It keeps its tail raised to monitor its surroundings. If you yank its
         tail, it will try to bite you.

026  RAICHU
     MOUSE
     HT  2'07"
     WT  66.0 lb

     {1} Its long tail serves as a ground to protect itself from its own high
         voltage power.

     {2} When electricity builds up inside its body, it becomes feisty.
         It also glows in the dark.

027  SANDSHREW
     MOUSE
     HT  2'00"
     WT  26.0 lb

     {1} Burrows deep underground in arid locations far from water. It only
         emerges to hunt for food.

     {2} Its body is dry. When it gets cold at night, its hide is said to become
         coated with a fine dew.

028  SANDSLASH
     MOUSE
     HT  3'03"
     WT  65.0 lb

     {1} Curls up into a spiny ball when threatened. It can roll while curled up
         to attack or escape.

     {2} It is skilled at slashing enemies with its claws. If broken, they start
         to grow back in a day.

029  NIDORAN  (Female)
     POISON PIN
     HT  1'04"
     WT  15.0 lb

     {1} Although small, its venomous barbs render this POKEMON dangerous.
         The female has smaller horns.

     {2} A mild-mannered POKEMON that does not like to fight. Beware, its small
         horns secrete venom.

030  NIDORINA
     POISON PIN
     HT  2'07"
     WT  44.0 lb

     {1} The female's horn develops slowly. Prefers physical attacks such as
         clawing and biting.

     {2} When resting deep in its burrow, its thorns always retract.
         This is proof that it is relaxed.

031  NIDOQUEEN
     DRILL
     HT  4'03"
     WT  132.0 lb

     {1} Its hard scales provide strong protection. It uses its hefty bulk to
         execute powerful moves.

     {2} Tough scales cover the sturdy body of this POKEMON. It appears that
         the scales grow in cycles.

032  NIDORAN  (Male)
     POISON PIN
     HT  1'08"
     WT  20.0 lb

     {1} Stiffens its ears to sense danger. The larger its horns, the more
         powerful its secreted venom.

     {2} Its large ears are always kept upright. If it senses danger,
         it will attack with a poisonous sting.

033  NIDORINO
     POISON PIN
     HT  2'11"
     WT  43.0 lb

     {1} An aggressive POKEMON that is quick to attack. The horn on its head
         secretes a powerful venom.

     {2} Its horns contain venom. If they are stabbed into an enemy, the impact
         makes the poison leak out.

034  NIDOKING
     DRILL
     HT  4'07"
     WT  137.0 lb

     {1} It uses its powerful tail in battle to smash, constrict, then break
         the prey's bones.

     {2} Its steel-like hide adds to its powerful tackle. Its horns are so
         hard, they can pierce a diamond.

035  CLEFAIRY
     FAIRY
     HT  2'00"
     WT  17.0 lb

     {1} Its magical and cute appeal has many admirers. It is rare and found
         only in certain areas.

     {2} Adored for their cute looks and playfulness. They are thought to be
         rare, as they do not appear often.

036  CLEFABLE
     FAIRY
     HT  4'03"
     WT  88.0 lb

     {1} A timid fairy POKEMON that is rarely seen. It will run and hide
         the moment it senses people.

     {2} They appear to be very protective of their own world. It is a kind of
         fairy, rarely seen by people.

037  VULPIX
     FOX
     HT  2'00"
     WT  22.0 lb

     {1} At the time of birth, it has just one tail. The tail splits from its
         tip as it grows older.

     {2} Both its fur and its tails are beautiful. As it grows, the tails
         split and form more tails.

038  NINETALES
     FOX
     HT  3'07"
     WT  44.0 lb

     {1} Very smart and very vengeful. Grabbing one of its many tails could
         result in a 1000-year curse.

     {2} According to an enduring legend, 9 noble saints were united and
         reincarnated as this POKEMON.

039  JIGGLYPUFF
     BALLOON
     HT  1'08"
     WT  12.0 lb

     {1} When its huge eyes light up, it sings a mysterious soothing melody that
         lulls its enemies to sleep.

     {2} Uses its alluring eyes to enrapture its foes. It then sings a pleasing
         melody that lulls the foe to sleep.

040  WIGGLYTUFF
     BALLOON
     HT  3'03"
     WT  26.0 lb

     {1} The body is soft and rubbery. When angered, it will suck in air and
         inflate itself to an enormous size.

     {2} Its body is full of elasticity. By inhaling deeply, it can continue
         to inflate itself without limit.

041  ZUBAT
     BAT
     HT  2'07"
     WT  17.0 lb

     {1} Forms colonies in perpetually dark places. Uses ultrasonic waves to
         identify and approach targets.

     {2} Emits ultrasonic cries while it flies. They act as a sonar used to
         check for objects in its way.

042  GOLBAT
     BAT
     HT  5'03"
     WT  121.0 lb

     {1} Once it strikes, it will not stop draining energy from the victim
         even if it gets too heavy to fly.

     {2} It attacks in a stealthy manner, without warning. Its sharp fangs
         are used to bite and suck blood.

043  ODDISH
     WEED
     HT  1'08"
     WT  12.0 lb

     {1} During the day, it keeps its face buried in the ground. At night,
         it wanders around sowing its seeds.

     {2} It may be mistaken for a clump of weeds. If you try to yank it out
         of the ground, it shrieks horribly.

044  GLOOM
     WEED
     HT  2'07"
     WT  19.0 lb

     {1} The fluid that oozes from its mouth isn't drool. It is a nectar that is
         used to attract prey.

     {2} Smells incredibly foul! However, around 1 out of 1,000 people enjoy
         sniffing its nose-bending stink.

045  VILEPLUME
     FLOWER
     HT  3'11"
     WT  41.0 lb

     {1} The larger its petals, the more toxic pollen it contains. Its big head
         is heavy and hard to hold up.

     {2} Flaps its broad flower petals to scatter its poisonous pollen.
         The flapping sound is very loud.

046  PARAS
     MUSHROOM
     HT  1'00"
     WT  12.0 lb

     {1} Burrows to suck tree roots. The mushrooms on its back grow by drawing
         nutrients from the bug host.

     {2} Burrows under the ground to gnaw on tree roots. The mushrooms on its
          back absorb most of the nutrition.

047  PARASECT
     MUSHROOM
     HT  3'03"
     WT  65.0 lb

     {1} A host-parasite pair in which the parasite mushroom has taken over the
         host bug. Prefers damp places.

     {2} The bug host is drained of energy by the mushrooms on its back.
         They appear to do all the thinking.

048  VENONAT
     INSECT
     HT  3'03"
     WT  66.0 lb

     {1} Lives in the shadows of tall trees where it eats insects. It is
         attracted by light at night.

     {2} Its large eyes act as radars. In a bright place, you can see that
         they are clusters of many tiny eyes.

049  VENOMOTH
     POISONMOTH
     HT  4'11"
     WT  28.0 lb

     {1} The dust-like scales covering its wings are color coded to indicate the
         kinds of poison it has.

     {2} The powdery scales on its wings are hard to remove. They also contain
         poison that leaks out on contact.

050  DIGLETT
     MOLE
     HT  0'08"
     WT  2.0 lb

     {1} Lives about one yard underground where it feeds on plant roots.
         It sometimes appears above ground.

     {2} It prefers dark places. It spends most of its time underground,
         though it may pop up in caves.

051  DUGTRIO
     MOLE
     HT  2'04"
     WT  73.0 lb

     {1} A team of DIGLETT triplets. It triggers huge earthquakes by burrowing
         60 miles underground.

     {2} A team of triplets that can burrow over 60 MPH. Due to this,
         some people think it's an earthquake.

052  MEOWTH
     SCRATCHCAT
     HT  1'04"
     WT  9.0 lb

     {1} Adores circular objects. Wanders the streets on a nightly basis to look
         for dropped loose change.

     {2} Appears to be more active at night. It loves round and shiny things.
         It can't stop from picking them up.

053  PERSIAN
     CLASSY CAT
     HT  3'03"
     WT  71.0 lb

     {1} Although its fur has many admirers, it is tough to raise as a pet
         because of its fickle meanness.

     {2} The gem on its forehead glows on its own! It walks with all the grace
         and elegance of a proud queen.

054  PSYDUCK
     DUCK
     HT  2'07"
     WT  43.0 lb

     {1} While lulling its enemies with its vacant look, this wily POKEMON will
         use psychokinetic powers.

     {2} Always tormented by headaches. It uses psychic powers, but it is
         not known if it intends to do so.

055  GOLDUCK
     DUCK
     HT  5'07"
     WT  169.0 lb

     {1} Often seen swimming elegantly by lake shores. It is often mistaken for
         the Japanese monster, Kappa.

     {2} Its slim and long limbs end in broad flippers. They are used for
         swimming gracefully in lakes.

056  MANKEY
     PIG MONKEY
     HT  1'08"
     WT  62.0 lb

     {1} Extremely quick to anger. It could be docile one moment then thrashing
         away the next instant.

     {2} An agile POKEMON that lives in trees. It angers easily and will not
         hesitate to attack anything.

057  PRIMEAPE
     PIG MONKEY
     HT  3'03"
     WT  71.0 lb

     {1} Always furious and tenacious to boot. It will not abandon chasing its
         quarry until it is caught.

     {2} It stops being angry only when nobody else is around. To view this
         moment is very difficult.

058  GROWLITHE
     PUPPY
     HT  2'04"
     WT  42.0 lb

     {1} Very protective of its territory. It will bark and bite to repel
         intruders from its space.

     {2} A POKEMON with a friendly nature. However, it will bark fiercely
         at anything invading its territory.

059  ARCANINE
     LEGENDARY
     HT  6'03"
     WT  342.0 lb

     {1} A POKEMON that has been admired since the past for its beauty.
         It runs agilely as if on wings.

     {2} A legendary POKEMON in China. Many people are charmed by its grace
         and beauty while running.

060  POLIWAG
     TADPOLE
     HT  2'00"
     WT  27.0 lb

     {1} Its newly grown legs prevent it from running. It appears to prefer
         swimming than trying to stand.

     {2} The direction of the spiral on the belly differs by area. It is more
         adept at swimming than walking.

061  POLIWHIRL
     TADPOLE
     HT  3'03"
     WT  44.0 lb

     {1} Capable of living in or out of water. When out of water, it sweats to
         keep its body slimy.

     {2} Under attack, it uses its belly spiral to put the foe to sleep.
         It then makes its escape.

062  POLIWRATH
     TADPOLE
     HT  4'03"
     WT  119.0 lb

     {1} An adept swimmer at both the front crawl and breast stroke.
         Easily overtakes the best human swimmers.

     {2} Swims powerfully using all the muscles in its body. It can even
         overtake champion swimmers.

063  ABRA
     PSI
     HT  2'11"
     WT  43.0 lb

     {1} Using its ability to read minds, it will identify impending danger and
         TELEPORT to safety.

     {2} Sleeps 18 hours a day. If it senses danger, it will teleport itself to
         safety even as it sleeps.

064  KADABRA
     PSI
     HT  4'03"
     WT  125.0 lb

     {1} It emits special alpha waves from its body that induce headaches
         just by being close by.

     {2} Many odd things happen if this POKEMON is close by. For example,
         it makes clocks run backwards.

065  ALAKAZAM
     PSI
     HT  4'11"
     WT  106.0 lb

     {1} Its brain can out-perform a supercomputer. Its intelligence quotient is
         said to be 5,000.

     {2} A POKEMON that can memorize anything. It never forgets what it learns--
         that's why this POKEMON is smart.

066  MACHOP
     SUPERPOWER
     HT  2'7"
     WT  43.0 lb

     {1} Loves to build its muscles. It trains in all styles of martial arts
         to become even stronger.

     {2} Very powerful in spite of its small size. Its mastery of many types
         of martial arts makes it very tough.

067  MACHOKE
     SUPERPOWER
     HT  4'11"
     WT  155.0 lb

     {1} Its muscular body is so powerful, it must wear a power save belt to be
         able to regulate its motions.

     {2} The belt around its waist holds back its energy. Without it, this
         POKEMON would be unstoppable.

068  MACHAMP
     SUPERPOWER
     HT  5'03"
     WT  287.0 lb

     {1} Using its heavy muscles, it throws powerful punches that can send the
         victim clear over the horizon.

     {2} One arm alone can move mountains. Using all four arms, this POKEMON
         fires off awesome punches.

069  BELLSPROUT
     FLOWER
     HT  2'04"
     WT  9.0 lb

     {1} A carnivorous POKEMON that traps and eats bugs. It uses its root feet
         to soak up needed moisture.

     {2} Prefers hot and humid places. It ensnares tiny insects with its vines
         and devours them.

070  WEEPINBELL
     FLYCATCHER
     HT  3'03"
     WT  14.0 lb

     {1} It spits out POISONPOWDER to immobilize the enemy and then finishes it
         with a spray of ACID.

     {2} When hungry, it swallows anything that moves. Its hapless prey is
         melted inside by strong acids.

071  VICTREEBEL
     FLYCATCHER
     HT  5'07"
     WT  34.0 lb

     {1} Said to live in huge colonies deep in jungles, although no one has ever
         returned from there.

     {2} Lures prey with the sweet aroma of honey. Swallowed whole, the prey is
         melted in a day, bones and all.

072  TENTACOOL
     JELLYFISH
     HT  2'11"
     WT  100.0 lb

     {1} Drifts in shallow seas. Anglers who hook them by accident are often
         punished by its stinging acid.

     {2} It can sometimes be found all dry and shriveled up on a beach.
         Toss it back into the sea to revive it.

073  TENTACRUEL
     JELLYFISH
     HT  5'03"
     WT  121.0 lb

     {1} The tentacles are normally kept short. On hunts, they are extended to
         ensnare and immobilize prey.

     {2} Its 80 tentacles can stretch and contract freely. They wrap around prey
         and weaken it with poison.

074  GEODUDE
     ROCK
     HT  1'04"
     WT  44.0 lb

     {1} Found in fields and mountains. Mistaking them for boulders, people
         often step or trip on them.

     {2} Commonly found near mountain trails, etc. If you step on one by
         accident, it gets angry.

075  GRAVELER
     ROCK
     HT  3'03"
     WT  232.0 lb

     {1} Rolls down slopes to move. It rolls over any obstacle without slowing
         or changing its direction.

     {2} Often seen rolling down mountain trails. Obstacles are just things to
         roll straight over, not avoid.

076  GOLEM
     MEGATON
     HT  4'07"
     WT  662.0 lb

     {1} Its boulder-like body is extremely hard. It can easily withstand
         dynamite blasts without damage.

     {2} Once it sheds its skin, its body turns tender and whitish. Its hide
         hardens when it's exposed to air.

077  PONYTA
     FIRE HORSE
     HT  3'03"
     WT  66.0 lb

     {1} Its hooves are 10 times harder than diamonds. It can trample anything
         completely flat in little time.

     {2} Capable of jumping incredibly high. Its hooves and sturdy legs absorb
         the impact of a hard landing.

078  RAPIDASH
     FIRE HORSE
     HT  5'07"
     WT  209.0 lb

     {1} Very competitive, this POKEMON will chase anything that moves fast
         in the hopes of racing it.

     {2} Just loves to run. If it sees something faster than itself, it will
         give chase at top speed.

079  SLOWPOKE
     DOPEY
     HT  3'11"
     WT  79.0 lb

     {1} Incredibly slow and dopey. It takes 5 seconds for it to feel pain
         when under attack.

     {2} Incredibly slow and sluggish. It is quite content to loll about
         without worrying about the time.

080  SLOWBRO
     HERMITCRAB
     HT  5'03"
     WT  173.0 lb

     {1} The SHELLDER that is latched onto SLOWPOKE's tail is said to feed on
         the host's left over scraps.

     {2} Lives lazily by the sea. If the SHELLDER on its tail comes off,
         it becomes a SLOWPOKE again.

081  MAGNEMITE
     MAGNET
     HT  1'00"
     WT  13.0 lb

     {1} Uses anti-gravity to stay suspended. Appears without warning and uses
         THUNDER WAVE and similar moves.

     {2} It is born with the ability to defy gravity. It floats in air on
         powerful electromagnetic waves.

082  MAGNETON
     MAGNET
     HT  3'03"
     WT  132.0 lb

     {1} Formed by several MAGNEMITEs linked together. They frequently appear
         when sunspots flare up.

     {2} Generates strange radio signals. It raises the temperature by 3.6F
         degrees within 3,300 feet.

083  FARFETCH'D
     WILD DUCK
     HT  2'07"
     WT  33.0 lb

     {1} The sprig of green onions it holds is its weapon. It is used much like
         a metal sword.

     {2} Lives where reedy plants grow. They are rarely seen, so it's thought
         their numbers are decreasing.

084  DODUO
     TWIN BIRD
     HT  4'07"
     WT  86.0 lb

     {1} A bird that makes up for its poor flying with its fast food speed.
         Leaves giant footprints.

     {2} Its short wings make flying difficult. Instead, this POKEMON runs
         at high speed on developed legs.

085  DODRIO
     TRIPLEBIRD
     HT  5'11"
     WT  188.0 lb

     {1} Uses its three brains to execute complex plans. While two heads sleep,
         one head stays awake.

     {2} One of DODUO's 2 heads splits to form a unique species. It runs close
         to 40 MPH in prairies.

086  SEEL
     SEA LION
     HT  3'07"
     WT  198.0 lb

     {1} The protruding horn on its head is very hard. It is used for bashing
         through thick ice.

     {2} Loves freezing cold conditions. Relishes swimming in a frigid climate
         of around 14F degrees.

087  DEWGONG
     SEA LION
     HT  5'07"
     WT  265.0 lb

     {1} Stores thermal energy in its body. Swims at a steady 8 knots even in
         intensely cold waters.

     {2} Its entire body is a snowy-white. Unharmed by even intense cold,
         it swims powerfully in icy waters.

088  GRIMER
     SLUDGE
     HT  2'11"
     WT  66.0 lb

     {1} Appears in filthy areas. Thrives by sucking up polluted sludge that is
         pumped out of factories.

     {2} Made of hardened sludge. It smells too putrid to touch. Even weeds
         won't grow in its path.

089  MUK
     SLUDGE
     HT  3'11"
     WT  66.0 lb

     {1} Thickly covered with a filthy, vile sludge. It is so toxic, even its
         footprints contain poison.

     {2} Smells so awful, it can cause fainting. Through degeneration, it lost
         its sense of smell.

090  SHELLDER
     BIVALVE
     HT  1'00"
     WT  9.0 lb

     {1} Its hard shell repels any kind of attack. It is vulnerable only when
         its shell is open.

     {2} The shell can withstand any attack. However, when it is open, the
         tender body is exposed.

091  CLOYSTER
     BIVALVE
     HT  4'11"
     WT  292.0 lb

     {1} When attacked, it launches its horns in quick volleys. Its innards have
         never been seen.

     {2} For protection, it uses its harder-than-diamonds shell. It also shoots
         spikes from the shell.

092  GASTLY
     GAS
     HT  4'03"
     WT  0.2 lb

     {1} Almost invisible, this gaseous POKEMON cloaks the target and puts it to
         sleep without notice.

     {2} Said to appear in decrepit, deserted buildings. It has no real shape
         as it appears to be made of a gas.

093  HAUNTER
     GAS
     HT  5'03"
     WT  0.2 lb

     {1} Because of its ability to slip through block walls, it is said to be
         from another dimension.

     {2} By licking, it saps the victim's life. It causes shaking that won't
         stop until the victim's demise.

094  GENGAR
     SHADOW
     HT  4'11"
     WT  89.0 lb

     {1} Under a full moon, this POKEMON likes to mimic the shadows of people
         and laugh at their fright.

     {2} A GENGAR is close by if you feel a sudden chill. It may be trying to
         lay a curse on you.

095  ONIX
     ROCK SNAKE
     HT  28'10"
     WT  463.0 lb

     {1} As it grows, the stone portions of its body harden to become similar to
         a diamond, but colored black.

     {2} Burrows at high speed in search of food. The tunnels it leaves are used
         as homes by DIGLETTs.

096  DROWZEE
     HYPNOSIS
     HT  3'03"
     WT  71.0 lb

     {1} Puts enemies to sleep then eats their dreams. Occasionally gets sick
         from eating bad dreams.

     {2} If you sleep by it all the time, it will sometimes show you dreams
         it has eaten in the past.

097  HYPNO
     HYPNOSIS
     HT  5'03"
     WT  167.0 lb

     {1} When it locks eyes with an enemy, it will use a mix of PSI moves
         such as HYPNOSIS and CONFUSION.

     {2} Avoid eye contact if you come across one. It will try to put you
         to sleep by using its pendulum.

098  KRABBY
     RIVER CRAB
     HT  1'04"
     WT  14.0 lb

     {1} Its pincers are not only powerful weapons, they are used for balance
         when walking sideways.

     {2} Its pincers are superb weapons. They sometimes break off during battle,
         but they grow back fast.

099  KINGLER
     PINCER
     HT  4'03"
     WT  132.0 lb

     {1} The large pincer has 10000 hp of crushing power. However, its huge size
         makes it unwieldy to use.

     {2} One claw grew massively and as hard as steel. It has 10,000-HP
         strength. However, it is too heavy.

100  VOLTORB
     BALL
     HT  1'08"
     WT  23.0 lb

     {1} Usually found in power plants. Easily mistaken for a POKE BALL,
         they have zapped many people.

     {2} It is said to camouflage itself as a POKE BALL. It will self-destruct
         with very little stimulus.

101  ELECTRODE
     BALL
     HT  3'11"
     WT  147.0 lb

     {1} It stores electric energy under very high pressure. It often explodes
         with little or no provocation.

     {2} Stores electrical energy inside its body. Even the slightest shock
         could trigger a huge explosion.

102  EXEGGCUTE
     EGG
     HT  1'04"
     WT  6.0 lb

     {1} Often mistaken for eggs. When disturbed, they quickly gather and attack
         in swarms.

     {2} The heads attract each other and spin around. There must be 6 heads
         for it to maintain balance.

103  EXEGGUTOR
     COCONUT
     HT  6'07"
     WT  265.0 lb

     {1} Legend has it that on rare occasions, one of its heads will drop off
         and continue on as an EXEGGCUTE.

     {2} Its cries are very noisy. This is because each of the 3 heads thins
         about whatever it likes.

104  CUBONE
     LONELY
     HT  1'04"
     WT  14.0 lb

     {1} Because it never removes its skull helmet, no one has ever seen this
         POKEMON's read face.

     {2} Wears the skull of its deceased mother. Its cries echo inside the skull
         and come out as a sad melody.

105  MAROWAK
     BONEKEEPER
     HT  3'03"
     WT  99.0 lb

     {1} The bone it holds is its key weapon. It throws the bone skillfully like
         a boomerang to KO targets.

     {2} Small and weak, this POKEMON is adept with its bone club. It has grown
         more vicious over the ages.

106  HITMONLEE
     KICKING
     HT  4'11"
     WT  110.0 lb

     {1} When in a hurry, its legs lengthen progressively. It runs smoothly with
         extra long, loping strides.

     {2} When kicking, the sole of its foot turns as hard as a diamond on impact
         and destroys its enemy.

107  HITMONCHAN
     PUNCHING
     HT  4'07"
     WT  111.0 lb

     {1} While apparently doing nothing, it fires punches in lightning fast
         volleys that are impossible to see.

     {2} Punches in corkscrew fashion. It can punch its way through a concrete
         wall in the same way as a drill.

108  LICKITUNG
     LICKING
     HT  3'11"
     WT  144.0 lb

     {1} Its tongue can be extended like a chameleon's. It leaves a tingling
         sensation when it licks enemies.

     {2} Its tongue spans almost 7 feet and moves more freely than its forelegs.
         Its licks can cause paralysis.

109  KOFFING
     POISON GAS
     HT  2'00"
     WT  2.0 lb

     {1} Because it stores several kinds of toxic gases in its body, it is prone
         to exploding without warning.

     {2} In hot places, its internal gases could expand and explode without
         any warning. Be very careful!

110  WEEZING
     POISON GAS
     HT  3'11"
     WT  21.0 lb

     {1} Where two kinds of poison gases meet, 2 KOFFINGs can fuse into a
         WEEZING over many years.

     {2} It lives and grows by absorbing dust, germs and poison gases that are
         contained in toxic waste and garbage.

111  RHYHORN
     SPIKES
     HT  3'03"
     WT  254.0 lb

     {1} Its massive bones are 1000 times harder than human bones. It can easily
         knock a trailer flying.

     {2} A POKEMON with a one-track mind. Once it charges, it won't stop
         running until it falls asleep.

112  RHYDON
     DRILL
     HT  6'03"
     WT  265.0 lb

     {1} Protected by an armor-like hide, it is capable of living in molten lava
         of 3,600 degrees.

     {2} Walks on its hind legs. Shows signs of intelligence. Its armor-like
         hide even repels molten lava.

113  CHANSEY
     EGG
     HT  3'07"
     WT  76.0 lb

     {1} A rare and elusive POKEMON that is said to bring happiness to those who
         manage to get it.

     {2} A gentle and kindhearted POKEMON that shares its nutritious eggs
         if it sees an injured POKEMON.

114  TANGELA
     VINE
     HT  3'03"
     WT  77.0 lb

     {1} The whole body is swathed with wide vines that are similar to seaweed.
         Its vines shake as it walks.

     {2} Its identity is obscured by masses of thick, blue vines. The vines are
         said to never stop growing.

115  KANGASHKHAN
     PARENT
     HT  7'03"
     WT  176.0 lb

     {1} The infant rarely ventures out of its mother's protective pouch until
         it is 3 years old.

     {2} Raises its young in its belly pouch. Won't run from any fight to keep
         its young protected.

116  HORSEA
     DRAGON
     HT  1'04"
     WT  18.0 lb

     {1} Known to shoot down flying bugs with precision blasts of ink from the
         surface of the water.

     {2} If it senses any danger, it will vigorously spray water or a special
         type of ink from its mouth.

117  SEADRA
     DRAGON
     HT  3'11"
     WT  55.0 lb

     {1} Capable of swimming backwards by rapidly flapping its wing-like
         pectoral fins and stout tail.

     {2} Touching the back fin causes numbness. It hooks its tail to coral
         to stay in place while sleeping.

118  GOLDEEN
     GOLDFISH
     HT  2'00"
     WT  33.0 lb

     {1} Its tail fin billows like an elegant ballroom dress, giving it the
         nickname of the Water Queen.

     {2} When it is time for them to lay eggs, they can be seen swimming up
         rivers and falls in large groups.

119  SEAKING
     GOLDFISH
     HT  4'03"
     WT  86.0 lb

     {1} In the autumn spawning season, they can be seen swimming powerfully up
         rivers and creeks.

     {2} It is the male's job to make a nest by carving out boulders in a stream
         using the horn on its head.

120  STARYU
     STARSHAPE
     HT  2'07"
     WT  76.0 lb

     {1} An enigmatic POKEMON that can effortlessly regenerate any appendage
         it loses in battle.

     {2} As long as the center section is unharmed, it can grow back fully
         even if it is chopped to bits.

121  STARMIE
     MYSTERIOUS
     HT  3'07"
     WT  176.0 lb

     {1} Its central core glows with the seven colors of the rainbow.
         Some people value the core as a gem.

     {2} The center section is named the core. People think it is communicating
         when it glows in 7 colors.

122  MR.MIME
     BARRIER
     HT  4'03"
     WT  120.0 lb

     {1} If interrupted while it is miming, it will slap around the offender
         with its broad hands.

     {2} Always practices its pantomime act. It makes enemies believe something
         exists that really doesn't.

123  SCYTHER
     MANTIS
     HT  4'11"
     WT  123.0 lb

     {1} With ninja-like agility and speed, it can create the illusion that
         there is more than one.

     {2} Leaps out of tall grass and slices prey with its scythes. The movement
         looks like that of a ninja.

124  JYNX
     HUMANSHAPE
     HT  4'07"
     WT  90.0 lb

     {1} It seductively wiggles its hips as it walks. It can cause people to
         dance in unison with it.

     {2} Appears to move to a rhythm of its own, as if it were dancing.
         It wiggles its hips as it walks.

125  ELECTABUZZ
     ELECTRIC
     HT  3'07"
     WT  66.0 lb

     {1} Normally found near power plants, they can wander away and cause major
         blackouts in cities.

     {2} If a major power outage occurs, it is certain that this POKEMON has
         eaten electricity at a power plant.

126  MAGMAR
     SPITFIRE
     HT  4'03"
     WT  98.0 lb

     {1} Its body always burns with an orange glow that enables it to hide
         perfectly among flames.

     {2} Born in an active volcano. Its body is always cloaked in flames,
         so it looks like a big ball of fire.

127  PINSIR
     STAGBEETLE
     HT  4'11"
     WT  121.0 lb

     {1} If it fails to crush the victim with its pincers, it will swing it
         around and toss it hard.

     {2} Grips its prey in its pincers and squeezes hard! It can't move if
         it's cold, so it lives in warm places.

128  TAUROS
     WILD BULL
     HT  4'07"
     WT  195.0 lb

     {1} When it targets an enemy, it charges furiously while whipping its body
         with its long tails.

     {2} A rowdy POKEMON with a lot of stamina. Once running, it won't stop
         until it hits something.

129  MAGIKARP
     FISH
     HT  2'11"
     WT  22.0 lb

     {1} In the distant past, it was somewhat stronger than the horribly weak
         descendants that exist today.

     {2} Famous for being very unreliable. It can be found swimming seas,
         lakes, rivers and shallow puddles.

130  GYARADOS
     ATROCIOUS
     HT  21'04"
     WT  518.0 lb

     {1} Rarely seen in the wild. Huge and vicious, it is capable of destroying
         entire cities in a rage.

     {2} Brutally vicious and enormously destructive. Known for totally
         destroying cities in ancient times.

131  LAPRAS
     TRANSPORT
     HT  8'02"
     WT  485.0 lb

     {1} A POKEMON that has been over-hunted almost to extinction. It can ferry
         people across the water.

     {2} A gentle soul that can read the minds of people. It can ferry people
         across the sea on its back.

132  DITTO
     TRANSFORM
     HT  1'00"
     WT  9.0 lb

     {1} Capable of copying an enemy's genetic code to instantly transform
         itself into a duplicate of the enemy.

     {2} When it spots an enemy, its body transfigures into an almost perfect
         copy of its opponent.

133  EEVEE
     EVOLUTION
     HT  1'00"
     WT  14.0 lb

     {1} Its genetic code is irregular. It may mutate if it is exposed to
         radiation from element STONEs.

     {2} Its genetic code is unstable, so it could evolve in a variety of ways.
         There are only a few alive.

134  VAPOREON
     BUBBLE JET
     HT  3'03"
     WT  64.0 lb

     {1} Lives close to water. Its long tail is ridged with a fin which is often
         mistaken for a mermaid's.

     {2} Its cell structure is similar to water molecules. It will melt away
         and become invisible in water.

135  JOLTEON
     LIGHTNING
     HT  2'07"
     WT  54.0 lb

     {1} It accumulates negative ions in the atmosphere to blast out 10000-volt
         lightning bolts.

     {2} A sensitive POKEMON that easily becomes sad or angry. Every time its
         mood changes, it charges power.

136  FLAREON
     FLAME
     HT  2'11"
     WT  55.0 lb

     {1} When storing thermal energy in its body, its temperature could soar to
         over 1600 degrees.

     {2} It has a flame chamber inside its body. It inhales, then blows out
         fire that is over 3,000F degrees.

137  PORYGON
     VIRTUAL
     HT  2'07"
     WT  80.0 lb

     {1} A POKEMON that consists entirely of programming code. Capable of moving
         freely in cyberspace.

     {2} The only POKEMON people anticipate can fly into space. None has managed
         the feat yet, however.

138  OMANYTE
     SPIRAL
     HT  1'04"
     WT  17.0 lb

     {1} Although long extinct, in rare cases, it can be genetically resurrected
         from fossils.

     {2} An ancient POKEMON that was recovered from a fossil. It swims by
         cleverly twisting its 10 tentacles about.

139  OMASTAR
     SPIRAL
     HT  3'03"
     WT  77.0 lb

     {1} A prehistoric POKEMON that died out when its heavy shell made it
         impossible to catch prey.

     {2} Sharp beaks ring its mouth. Its shell was too big for it to move
         freely, so it became extinct.

140  KABUTO
     SHELLFISH
     HT  1'08"
     WT  25.0 lb

     {1} A POKEMON that was resurrected from a fossil found in what was once the
         ocean floor eons ago.

     {2} A POKEMON that was recovered from a fossil. It uses the eyes on its
         back while hiding on the sea floor.

141  KABUTOPS
     SHELLFISH
     HT  4'03"
     WT  89.0 lb

     {1} Its sleek shape is perfect for swimming. It slashes prey with its claws

         and drains the body fluids.

     {2} A slim and fast swimmer. It slices its prey with its sharp sickles
         and drinks the body fluids.

142  AERODACTYL
     FOSSIL
     HT  5'11"
     WT  130.0 lb

     {1} A ferocious, prehistoric POKEMON that goes for the enemy's throat with
         its serrated saw-like fangs.

     {2} A savage POKEMON that died out in ancient times. It was resurrected
         using DNA taken from amber.

143  SNORLAX
     SLEEPING
     HT  6'11"
     WT  1014.0 lb

     {1} Very lazy. Just eats and sleeps. As its rotund bulk builds, it becomes
         steadily more slothful.

     {2} Will eat anything, even if the food happens to be a little moldy.
         It never gets an upset stomach.

144  ARTICUNO
     FREEZE
     HT  5'07"
     WT  122.0 lb

     {1} A legendary bird POKEMON that is said to appear to doomed people who
        are lost in icy mountains.

     {2} A legendary bird POKEMON. It freezes water that is contained in winter
         air and makes it snow.

145  ZAPDOS
     ELECTRIC
     HT  5'03"
     WT  116.0 lb

     {1} A legendary bird POKEMON that is said to appear from clouds while
         dropping enormous lightning bolts.

     {2} This legendary bird POKEMON is said to appear when the sky turns dark
         and lightning showers down.

146  MOLTRES
     FLAME
     HT  6'07"
     WT  132.0 lb

     {1} Known as the legendary bird of fire. Every flap of its wings creates
         a dazzling flash of flames.

     {2} A legendary bird POKEMON. As it flaps its flaming wings, even the
         night sky will turn red.

147  DRATINI
     DRAGON
     HT  5'11"
     WT  7.0 lb

     {1} Long considered a mythical POKEMON until recently when a small colony
         was found living underwater.

     {2} The existence of this mythical POKEMON was only recently confirmed
         by a fisherman who caught one.

148  DRAGONAIR
     DRAGON
     HT  13'01"
     WT  36.0 lb

     {1} A mystical POKEMON that exudes a gentle aura. Has the ability to change
         climate conditions.

     {2} According to a witness, its body was surrounded by a strange aura
         that gave it a mystical look.

149  DRAGONITE
     DRAGON
     HT  7'03"
     WT  463.0 lb

     {1} An extremely rarely seen marine POKEMON. Its intelligence is said to
         match that of humans.

     {2} It is said that this POKEMON lives somewhere in the sea and that it
         flies. However, it is only a rumor.

150  MEWTWO
     GENETIC
     HT  6'07"
     WT  269.0 lb

     {1} It was created by a scientist after years of horrific gene splicing and
         DNA engineering experiments.

     {2} Its DNA is almost the same as MEW's. However, its size and disposition
         are vastly different.

151  MEW
     NEW SPECIE  [sic]
     HT  1'04"
     WT  9.0 lb

     {1} So rare that it is still said to be a mirage by many experts.
         Only a few people have seen it worldwide.

     {2} When viewed through a microscope, this POKEMON's short, fine, delicate
         hair can be seen.


                                End of Document