# Practice Drill 2

## PIPES

## 1.Download the contents of "Harry Potter and the Goblet of fire" using the command line from here

To download content from external space like browseer we use wget  command 

mountblue@mountblue-pc:~/harrypotter$ wget  https://raw.githubusercontent.com/bobdeng/owlreader/master/ERead/assets/books/Harry%20Potter%20and%20the%20Goblet%20of%20Fire.txt

Above command will download the content and save with same name in the current directory

## 2.Print the first three lines in the book

To print first three line we start from head and will limit upto 3 by using below command





mountblue@mountblue-pc:~/harrypotter$ head -n 3 'Harry Potter and the Goblet of Fire.txt' 

#### Output will be :- 

Harry Potter and the Goblet of Fire
　　By J.K. Rowling





## 3.Print the last 10 lines in the book

To print last 10 line we start from tail part and move upto limit of 10


mountblue@mountblue-pc:~/harrypotter$ tail -n 10 'Harry Potter and the Goblet of Fire.txt'

Output ->

　　and Goyle, who were still lying on the floor, covered in hex marks.
　　Uncle Vernon was waiting beyond the barrier. Mrs. Weasley was close by him. She hugged Harry very tightly when she saw him and whispered in his ear, "I think Dumbledore will let you come to us later in the summer. Keep in touch, Harry."
　　"See you. Harry," said Ron, clapping him on the back.
　　"'Bye, Harry!" said Hermione, and she did something she had never done before, and kissed him on the cheek.
　　"Harry - thanks," George muttered, while Fred nodded fervently at his side.
　　Harry winked at them, turned to Uncle Vernon, and followed him silently from the station.
　　There was no point worrying yet, he told himself, as he got into the back of the Dursleys' car.
　　As Hagrid had said, what would come, would come ... and he would have to meet it when it did. 
您下载的文件来自http://txt.nokiacn.net糯米社区为你制作
【糯米社区-TXT论坛】-立志要做最新最全的txt文本格式电子书下载论坛!

## 4.How many times below words appeared in txt file

Harry -> 
mountblue@mountblue-pc:~/harrypotter$ grep  -w -c 'Harry' 'Harry Potter and the Goblet of Fire.txt'

2572

Ron ->
mountblue@mountblue-pc:~/harrypotter$ grep  -w -c 'Harry' 'Harry Potter and the Goblet of Fire.txt'

945

Hermione ->
mountblue@mountblue-pc:~/harrypotter$ grep  -w -c 'Hermione' 'Harry Potter and the Goblet of Fire.txt'

821

Dumbledore ->
mountblue@mountblue-pc:~/harrypotter$ grep  -w -c 'Dumbledore' 'Harry Potter and the Goblet of Fire.txt'

500

## 5.Print from line 100 to 200 from book


mountblue@mountblue-pc:~/harrypotter$ cat -n 'Harry Potter and the Goblet of Fire.txt' | grep -A100 '\b100\b'

or sed -n '100,200p' "Harr...."

Output will be :-
 100	　　"Invite him inside, Wormtail. Where are your manners?"
   101	　　The cold voice was coming from the ancient armchair before the fire, but Frank couldn't see the speaker. the snake, on the other hand, was curled up on the rotting hearth rug, like some horrible travesty of a pet dog.
   102	　　Wormtail beckoned Frank into the room. Though still deeply shaken, Frank took a
   103	　　firmer grip on his walking stick and limped over the threshold.
   104	　　The fire was the only source of light in the room; it cast long, spidery shadows upon the walls. Frank stared at the back of the armchair; the man inside it seemed to be even smaller than his servant, for Frank couldn't even see the back of his head.
   105	　　"You heard everything, Muggle?" said the cold voice.
   106	　　"What's that you're calling me?" said Frank defiantly, for now that he was inside the room, now that the time had come for some sort of action, he felt braver; it had always been so in the war.
   107	　　"I am calling you a Muggle," said the voice coolly. "It means that you are not a wizard."
   108	　　"I don't know what you mean by wizard," said Frank, his voice growing steadier.
   109	　　"All I know is I've heard enough to interest the police tonight, I have. You've done murder and you're planning more! And I'll tell youthis too," he added, on a sudden inspiration, "my wife knows I'm up here, and if I don't come back --"
   110	　　"You have no wife," said te cold voice, very quietly. "Nobody knows you are here. You told nobody that you were coming. Do not lie to Lord Voldemort, Muggle, for he knows...he always knows..."
   111	　　"Is that right?" said Frank roughly. "Lord, is it? Well, I don't think much of your manners, My Lord. Turn 'round and face me like a man, why don't you?"
   112	　　"But I am not a man, Muggle," said the cold voice, barely audible now over the crackling of the flames. "I am much, much more than a man. However...why not? I will face you...Wormtail, come turn my chair around."
   113	　　The servant gave a whimper.
   114	　　"You heard me, Wormtail."
   115	　　Slowly, with his face screwed up, as though he would rather have done anything than approach his master and the hearth rug where the snake lay, the small man walked forward and began to turn the chair. The snake lifted its ugly triangular head and hissed slightly as the legs of the chair snagged on its rug.
   116	　　And then the chair was facing Frank, and he saw what was sitting in it. His walking stick fell to the floor with a clatter. He opened his mouth and let out a scream. He was screaming so loudly that he never heard the words the thing in the chair spoke as it raised a wand. There was a flash of green light, a rushing sound, and Frank Bryce crumpled. He was dead before he hit the floor.
   117	　　Two hundred miles away, the boy called Harry Potter woke with a start.
   118	　　CHAPTER TWO - THE SCAR
   119	　　Harry lay flat on his back, breathing hard as though he had been running. He had awoken from a vivid dream with his hands pressed over his face. The old scar on his forehead, which was shaped like a bolt of lightning, was burning beneath his fingers as though someone had just pressed a white-hot wire to his skin.
   120	　　He sat up, one hand still on his scar, the other hand reaching out in the darkness for his glasses, which were on the bedside table. He put them on and his bedroom came into clearer focus, lit by a faint, misty orange light that was filtering through the curtains from the street lamp outside the window.
   121	　　Harry ran his fingers over the scar again. It was still painful. He turned on the lamp beside him, scrambled out of bed, crossed the room, opened his wardrobe, and peered into the mirror on the inside of the door. A skinny boy of fourteen looked back at him, his bright green eyes puzzled under his untidy black hair. He examined the lightning-bolt scar of his reflection more closely. It looked normal, but it was still stinging.
   122	　　harry tried to recall what he had been dreaming about before he had awoken. It had seemed so real...There had been two people he knew and one he didn't ...He concentrated hard, frowning, trying to remember...
   123	　　The dim picture of a darkened room came to him...There had been a snake on a hearth rug...a small man called Peter, nicknamed Wormtail...and a cold, high voice...the voice of Lord Voldemort. Harry felt as though an ice cube had slipped down into his stomach at the very thought...
   124	　　He closed his eyes tightly and tried to remember what Voldemort had looked like, but it was impossible...All Harry knew was that at the moment when Voldemort's chair had swung around, and he, Harry, had seen what was sitting in it, he had felt a spasm of
   125	　　horror, which had awoken him...or had that been the pain in his scar?
   126	　　And who had the old man been? For there had definitely been an old man; Harry had watched him fall to the ground. It was all becoming confused. Harry put his face into his hands, blocking out his bedroom, trying to hold on to the picture of that dimly lit room, but it was like trying to keep water in his cupped hands; the details were now trickling away as fast as he tried to hold on to them...Voldemort and Wormtail had been talking about someone they had killed, though Harry could not remember the name...and they had been plotting to kill someone else...him!
   127	　　Harry took his face out of his hands, opened his eyes, and stared around his bedroom as though expecting to see something unusual there. As it happened, there was an extraordinary number of unusual things in this room. A large wooden trunk stood open at the foot of his bed, revealing a cauldron, broomstick, black robes, and assorted spellbooks. Rolls of parchment littered that part of his desk that was not taken up by the large, empty cage in which his snowy owl, Hedwig, usually perched. On the floor beside his bed a book lay open; Harry had been reading it before he fell asleep last night. The pictures in this book were all moving. Men in bright orange robes were zooming in and out of sight on broomsticks, throwing a red ball to one another.
   128	　　Harry walked over to the book, picked it up, and watched on of the wizards score a spectacular goal by putting the ball through a fifty-foot-high hoop. Then he snapped the book shut. Even Quidditch -- in Harry's opinion, the best sport in the world -- couldn't distract him at the moment. He placed Flying with the Cannons on his bedside table, crossed to the window, and drew back the curtains to survey the street below.
   129	　　Privet Drive looked exactly as a respectable suburban street would be expected to look inthe early hours of Saturday morning. All the curtains were closed. As far as Harry could see through the darkness, there wasn't a living creature in sight, not even a cat.
   130	　　And yet...and yet...Harry went restlessly back to the bed and sat down on it, running a finger over his scar again. It wasn't the pain that bothered him; Harry was no stranger to pain and injury. He had lost all the bones from his right arm once and had them painfully regrown in a night. The same arm had been pierced by a venemous foot-long fang not long afterward. Only last year Harry had fallen fifty feet from an airborn broomstick. He was used to bizarre accidents and injuries; they were unavoidable if you attended Hogwarts School of Witchcraft and Wizardry and had a knack for attracting a lot of trouble.
   131	　　No, the thing that was bothering Harry was the last time his scar had hurt him, it had been because Voldemort had been close by...But Voldemort couldn't be here, now...The idea of Voldemort lurking in Privet Drive was absurd, impossible...
   132	　　Harry listened closely to the silence around him. Was he half expecting to hear the creak of a stair or the swish of a cloak? And then he jumped slightly as he heard his cousin Dudley give a tremendous grunting snore from the next room.
   133	　　Harry shook himself mentally; he was being stupid. There was no one in the house with him except Uncle Vernon, Aunt Petunia, and Dudley, and they were plainly still asleep, their dreams untroubled and painless.
   134	　　Asleep was the way Harry liked the Dursleys best; it wasn't as though they were ever any help to him awake. Uncle Vernon, Aunt Petunia, and Dudley were Harry's only living relatives. They were Muggles who hated and despised magic in any form, which meant that Harry was about as welcome in their house as dry rot. They had explained away Harry's long absences at Hogwarts over the last three years by telling everyone that he went to St. Brutus's Secure Center for Incurably Criminal Boys. They knew perfectly well that, as an underage wizard, Harry wasn't allowed to use magic outside Hogwarts, but they were still apt to blame him for anything that went wrong about the house. Harry had never been able to confide in them or tell them anything about his life in the wizarding world. The very idea of going to them when they awoke, and telling them about his scar hurting him, and about his worries about Voldemort, was laughable.
   135	　　And yet it was because of Voldemort that Harry had come to live with the Dursleys in the first place. If it hadn't been for Voldemort, Harry would not have had the lightning scar on his forehead. If it hadn't been for Voldemort, Harry would still have had parents...
   136	　　Harry had been a year old the night that Voldemort -- the most powerful Dark wizard for a century, a wizard who had been gaining power steadily for eleven years -- arrived at his house and killed his father and mother. Voldemort had then turned his
   137	　　wand on Harry; he had performed the curse that had disposed of many full-grown witches and wizards in his steady rise to power -- and, incredibly, it had not worked. Instead of killing the small boy, the curse had rebounded upon Voldemort. Harry had survived with nothing but a lightning-shaped cut on his forehead, and Voldemort had been reduced to something barely alive. His powers gone, his life almost extinguished, Voldemort had fled; the terror in which the secret community of witches and wizards had lived for so long had lifted, Voldemort's followers had disbanded, and Harry Potter had become famous.
   138	　　It had been enough of a shock for Harry to discover, on his eleventh birthday, that he was a wizard; it had been even more disconcerting to find out that everyone in the hidden wizarding world knew his name. Harry had arrived at Hogwarts to find that heads turned and whispers followed him wherever he went. But he was used to it now: At the end of this summer, he would be starting his fourth year at Hogwarts, and Harry was already counting the days until he would be back at the castle again.
   139	　　But there was still a fortnight to go before he went back to school. He looked hopelessly around his room again, and his eye paused on the birthday cards his two best friends had sent him at the end of July. What would they say if Harry wrote to them and told them about his scar hurting?
   140	　　At once, Hermione Granger's voice seemed to fill his head, shrill and panicky.
   141	　　"Your scar hurt? Harry, that's really serious.... Write to Professor Dumbledore!
   142	　　And I'll go and check Common Magical Ailments and Afflictions.... Maybe there's something in there about curse scars. . . ."
   143	　　Yes, that would be Hermione's advice: Go straight to the headmaster of Hogwarts, and in the meantime, consult a book. Harry stared out of the window at the inky blue-black sky. He doubted very much whether a book could help him now. As far as he knew, he was the only living person to have survived a curse like Voldemort's; it was highly unlikely, therefore, that he would find his symptoms listed in Common Magical Ailments and Afflictions. As for informing the headmaster, Harry had no idea where Dumbledore went during the summer holidays. He amused himself for a moment, picturing Dumbledore, with his long silver beard, full length wizard's robes, and pointed hat, stretched out on a beach somewhere, rubbing suntan lotion onto his long crooked nose.
   144	　　Wherever Dumbledore was, though, Harry was sure that Hedwig would be able to find him; Harry's owl had never yet failed to deliver a letter to anyone, even without an address.
   145	　　But what would he write?
   146	　　Dear Professor Dumbledore, Sorry to bother you, but my scar hurt this morning.
   147	　　Yours sincerely, Harry Potter.
   148	　　Even inside his head the words sounded stupid.
   149	　　And so he tried to imagine his other best friend, Ron Weasley's, reaction, and in a moment, Ron's red hair and long-nosed, freckled face seemed to swim before Harry, wearing a bemused expression.
   150	　　"Your scar hurt? But ... but You-Know-Who can't be near you now, can he? I mean ... you'd know, wouldn't you? He'd be trying to do you in again, wouldn't be? I dunno, Harry, maybe curse scars always twinge a bit... I'll ask Dad. . . ."
   151	　　Mr. Weasley was a fully qualified wizard who worked in the Misuse of Muggle Artifacts Office at the Ministry of Magic, but he didn't have any particular expertise in the matter of curses, as far as Harry knew. In any case, Harry didn't like the idea of the whole Weasley family knowing that he, Harry, was getting jumpy about a few moments' pain. Mrs. Weasley would fuss worse than Hermione, and Fred and George, Ron's sixteen-year- old twin brothers, might think Harry was losing his nerve. The Weasleys were Harry's favorite family in the world; he was hoping that they might invite him to stay any time now (Ron had mentioned something about the Quidditch World Cup), and he somehow didn't want his visit punctuated with anxious inquiries about his scar.
   152	　　Harry kneaded his forehead with his knuckles. What he really wanted (and it felt almost shameful to admit it to himself) was someone like - someone like a parent: an adult wizard whose advice he could ask without feeling stupid, someone who cared about him, who had had experience with Dark Magic....
   153	　　And then the solution came to him. It was so simple, and so obvious, that he couldn't believe it had taken so long - Sirius.
   154	　　Harry leapt up from the bed, hurried across the room, and sat down at his desk; he pulled a piece of parchment toward him, loaded his eagle-feather quill with ink, wrote Dear Sirius, then paused, wondering how best to phrase his problem, still marveling at the fact that he hadn't thought of Sirius straight away. But then, perhaps it wasn't so
   155	　　surprising - after all, he had only found out that Sirius was his godfather two months ago.
   156	　　There was a simple reason for Sirius's complete absence from Harry's life until then - Sirius had been in Azkaban, the terrifying wizard jail guarded by creatures called dementors, sightless, soul-sucking fiends who had come to search for Sirius at Hogwarts when he had escaped. Yet Sirius had been innocent - the murders for which he had been convicted had been committed by Wormtail, Voldemort's supporter, whom nearly everybody now believed dead. Harry, Ron, and Hermione knew otherwise, however; they had come face-to-face with Wormtail only the previous year, though only Professor Dumbledore had believed their story.
   157	　　For one glorious hour, Harry had believed that he was leaving the Dursleys at last, because Sirius had offered him a home once his name had been cleared. But the chance had been snatched away from him - Wormtail had escaped before they could take him to the Ministry of Magic, and Sirius had had to flee for his life. Harry had helped him escape on the back of a hippogriff called Buckbeak, and since then, Sirius had been on the run. The home Harry might have had if Wormtail had not escaped had been haunting him all summer. It had been doubly hard to return to the Dursleys knowing that he had so nearly escaped them forever.
   158	　　Nevertheless, Sirius had been of some help to Harry, even if he couldn't be with him. It was due to Sirius that Harry now had all his school things in his bedroom with him. The Dursleys had never allowed this before; their general wish of keeping Harry as miserable as possible, coupled with their fear of his powers, had led them to lock his school trunk in the cupboard under the stairs every summer prior to this. But their attitude had changed since they had found out that Harry had a dangerous murderer for a godfather - for Harry had conveniently forgotten to tell them that Sirius was innocent.
   159	　　Harry had received two letters from Sirius since he had been back at Privet Drive. Both had been delivered, not by owls (as was usual with wizards), but by large, brightly colored tropical birds. Hedwig had not approved of these flashy intruders; she had been most reluctant to allow them to drink from her water tray before flying off again. Harry, on the other hand, had liked them; they put him in mind of palm trees and white sand, and he hoped that, wherever Sirius was (Sirius never said, in case the letters were intercepted), he was enjoying himself. Somehow, Harry found it hard to imaging dementors surviving for long in bright sunlight, perhapse that was why Sirius had gone South. Sirius's letters, which were now hidden beneath the highly useful loose floorboards under Harry's bed, sounded chearful, and in both of them he had reminded Harry to call on him if ever Harry needed to. Well, he needed to right now, all right...
   160	　　Harry's lamp seemed to grow dimmer as the cold gray light that precedes sunrise slowly crept into the room. Finally, when the sun had risen, when his bedroom walls had turned gold, and when sounds of movement could be heard from Uncle Vernon and Aunt Petunia's room, Harry cleared his desk of crumpled pieces of parchment and reread his finished letter.
   161	　　Dear Sirius, Thanks for your last letter. That bird was enormous; it could hardly get through my window. Things are the same as usual here. Dudley's diet isn't going too well. My aunt found him smuggling doughnuts into his room yesterday. They told him they'd have to cut his pocket money if he keeps doing it, so he got really angry and chucked his PlayStation out of the window. That's a sort of computer thing you can play games on. Bit stupid really, now he hasn't even got Mega-Mutilation Part Three to take his mind off things.
   162	　　I'm okay, mainly because the Dursleys are terrified you might turn up and turn them all into bats if I ask you to.
   163	　　A weird thing happened this morning, though. My scar hurt again. Last time that happened it was because Voldemort was at Hogwarts. But I don't reckon he can be anywhere near me now, can he? Do you know if curse scars sometimes hurt years afterward?
   164	　　I'll send this with Hedwig when she gets back; she's off hunting at the moment.
   165	　　Say hello to Buckbeak for me. Harry Yes, thought Harry, that looked all right. There was no point putting in the dream; he didn't want it to look as though he was too worried. He folded up the parchment and laid it aside on his desk, ready for when Hedwig returned. Then he got to his feet, stretched, and opened his wardrobe once more. Without glancing at his reflection he
   166	　　started to get dressed before going down to breakfast.
   167	　　CHAPTER THREE - THE INVITATION
   168	　　By the time Harry arrived in the kitchen, the three Dursleys were already seated around the table. None of them looked up as he entered or sat down. Uncle Vernon's large red face was hidden behind the morning's Daily Mail, and Aunt Petunia was cutting a grapefruit into quarters, her lips pursed over her horselike teeth.
   169	　　Dudley looked furious and sulky, and somehow seemed to be taking up even more space than usual. This was saying something, as he always took up an entire side of the square table by himself. When Aunt Petunia put a quarter of unsweetened grapefruit onto Dudley's plate with a tremulous "There you are, Diddy darling," Dudley glowered at her.
   170	　　His life had taken a most unpleasant turn since he had come home for the summer with his end-of-year report.
   171	　　Uncle Vernon and Aunt Petunia had managed to find excuses for his bad marks as usual: Aunt Petunia always insisted that Dudley was a very gifted boy whose teachers didn't understand him, while Uncle Vernon maintained that "he didn't want some swotty little nancy boy for a son anyway." They also skated over the accusations of bullying in the report - "He's a boisterous little boy, but he wouldn't hurt a fly!" Aunt Petunia had said tearfully.
   172	　　However, at the bottom of the report there were a few well-chosen comments from the school nurse that not even Uncle Vernon and Aunt Petunia could explain away. No matter how much Aunt Petunia wailed that Dudley was big-boned, and that his poundage was really puppy fat, and that he was a growing boy who needed plenty of food, the fact remained that the school outfitters didn't stock knickerbockers big enough for him anymore. The school nurse had seen what Aunt Petunia's eyes - so sharp when it came to spotting fingerprints on her gleaming walls, and in observing the comings and goings of the neighbors - simply refused to see: that far from needing extra nourishment, Dudley had reached roughly the size and weight of a young killer whale.
   173	　　So - after many tantrums, after arguments that shook Harry's bedroom floor, and many tears from Aunt Petunia - the new regime had begun. The diet sheet that had been sent by the Smeltings school nurse had been taped to the fridge, which had been emptied of all Dudley's favorite things - fizzy drinks and cakes, chocolate bars and burgers and filled instead with fruit and vegetables and the sorts of things that Uncmountblue@mountblue-pc:~/harrypotter$ tr -c '[:alnum:]' '[\n*]' < 'Harry Potter and the Goblet of Fire.txt' | sort | uniq | wc -l
11578
le Vernon called "rabbit food." To make Dudley feel better about it all, Aunt Petunia had insisted that the whole family follow the diet too. She now passed a grapefruit quarter to Harry. He noticed that it was a lot smaller than Dudley's. Aunt Petunia seemed to feet that the best way to keep up Dudley's morale was to make sure that he did, at least, get more to eat than Harry.
   174	　　But Aunt Petunia didn't know what was hidden under the loose floorboard upstairs. She had no idea that Harry was not following the diet at all. The moment he had got wind of the fact that he was expected to survive the summer on carrot sticks, Harry had sent Hedwig to his friends with pleas for help, and they had risen to the occasion magnificently. Hedwig had returned from Hermione's house with a large box stuffed full of sugar-free snacks. (Hermione's parents were dentists.) Hagrid, the Hogwarts gamekeeper, had obliged with a sack full of his own homemade rock cakes. (Harry hadn't touched these; he had had too much experience of Hagrid's cooking.) Mrs. Weasley, however, had sent the family owl, Errol, with an enormous fruitcake and assorted meat pies. Poor Errol, who was elderly and feeble, had needed a full five days to recover from the journey. And then on Harry's birthday (which the Dursleys had completely ignored) he had received four superb birthday cakes, one each from Ron, Hermione, Hagrid, and Sirius. Harry still had two of them left, and so, looking forward to a real breakfast when he got back upstairs, he ate his grapefruit without complaint.
   175	　　Uncle Vernon laid aside his paper with a deep sniff of disapproval and looked down at his own grapefruit quarter.
   176	　　"Is this it?" he said grumpily to Aunt Petunia.
   177	　　Aunt Petunia gave him a severe look, and then nodded pointedly at Dudley, who had already finished his own grapefruit quarter and was eyeing Harry's with a very sour look in his piggy little eyes.
   178	　　Uncle Vernon gave a great sigh, which ruffled his large, bushy mustache, and picked up his spoon.
   179	　　The doorbell rang. Uncle Vernon heaved himself out of his chair and set off down the hall. Quick as a flash, while his mother was occupied with the kettle, Dudley stole the rest of Uncle Vernon's grapefruit.
   180	　　Harry heard talking at the door, and someone laughing, and Uncle Vernon answering curtly.
   181	　　Then the front door closed, and the sound of ripping paper came from the hall.
   182	　　Aunt Petunia set the teapot down on the table and looked curiously around to see where Uncle Vernon had got to. She didn't have to wait long to find out; after about a minute, he was back. He looked livid.
   183	　　"You," he barked at Harry. "In the living room. Now."
   184	　　Bewildered, wondering what on earth he was supposed to have done this time, Harry got up and followed Uncle Vernon out of the kitchen and into the next room. Uncle Vernon closed the door sharply behind both of them.
   185	　　"So," he said, marching over to the fireplace and turning to face Harry as though he were about to pronounce him under arrest. "So."
   186	　　Harry would have dearly loved to have said, "So what?" but he didn't feel that Uncle Vernon's temper should be tested this early in the morning, especially when it was already under severe strain from lack of food. He therefore settled for looking politely puzzled.
   187	　　"This just arrived," said Uncle Vernon. He brandished a piece of purple writing paper at Harry. "A letter. About you."
   188	　　Harry's confusion increased. Who would be writing to Uncle Vernon about him? Who did he know who sent letters by the postman?
   189	　　Uncle Vernon glared at Harry, then looked down at the letter and began to read aloud:
   190	　　Dear Mr. and Mrs. Dursley, We have never been introduced, but I am sure you have heard a great deal from Harry about my son Ron.
   191	　　As Harry might have told you, the final of the Quidditch World Cup takes place this Monday night, and my husband, Arthur, has just managed to get prime tickets through his connections at the Department of Magical Games and Sports.
   192	　　I do hope you will allow us to take Harry to the match, as this really is a once-in-a-lifetime opportunity; Britain hasn't hosted the cup for thirty years, and tickets are extremely hard to come by. We would of course be glad to have Harry stay for the remainder of the summer holidays, and to see him safely onto the train back to school.
   193	　　It would be best for Harry to send us your answer as quickly as possible in the normal way, because the Muggle postman has never delivered to our house, and I am not sure he even knows where it is.
   194	　　Hoping to see Harry soon, Yours sincerely, Molly Weasley P.S. I do hope we've put enough stamps on.
   195	　　Uncle Vernon finished reading, put his hand back into his breast pocket, and drew out something else.
   196	　　"Look at this," he growled.
   197	　　He held up the envelope in which Mrs. Weasley's letter had come, and Harry had to fight down a laugh. Every bit of it was covered in stamps except for a square inch on the front, into which Mrs. Weasley had squeezed the Dursleys' address in minute writing.
   198	　　"She did put enough stamps on, then," said Harry, trying to sound as though Mrs.
   199	　　Weasley's was a mistake anyone could make. His uncle's eyes flashed.
   200	　　"The postman noticed," he said through gritted teeth. "Very interested to know where this letter came from, he was. That's why he rang the doorbell. Seemed to think it was funny."


##6. How many unique words are there in the book 

mountblue@mountblue-pc:~/harrypotter$ sort 'Harry Potter and the Goblet of Fire.txt' | uniq | wc -l

6753


  ##  List your browser's process ids (pid) and parent process ids(ppid)

  mountblue@mountblue-pc:~$ pgrep firefox
  
  1852

  ## Stop the browser application from the command line
  ## List the top 3 processes by CPU usage.

  mountblue@mountblue-pc:~$   ps -eo pid, comm,%cpu --sort=-%cpu | head -n 4
    PIDmm,COMMAND        pu
   1241mm,pulseaudio     pu
   1852mm,firefox-bin    pu
   4688mm,Isolated Web Copu

  ## List the top 3 processes by memory usage.
  ## Start a Python HTTP server on port 8000

     python3 -m http.server 8000

  ## Start a Python HTTP server on port 90
      python3 -m http.server 90

      But I get some error/warning
      Traceback (most recent call last):
  File "/usr/lib/python3.10/runpy.py", line 196, in _run_module_as_main
    return _run_code(code, main_globals, None,
  File "/usr/lib/python3.10/runpy.py", line 86, in _run_code
    exec(code, run_globals)
  File "/usr/lib/python3.10/http/server.py", line 1297, in <module>
    test(
  File "/usr/lib/python3.10/http/server.py", line 1248, in test
    with ServerClass(addr, HandlerClass) as httpd:
  File "/usr/lib/python3.10/socketserver.py", line 452, in __init__
    self.server_bind()
  File "/usr/lib/python3.10/http/server.py", line 1291, in server_bind
    return super().server_bind()
  File "/usr/lib/python3.10/http/server.py", line 136, in server_bind
    socketserver.TCPServer.server_bind(self)
  File "/usr/lib/python3.10/socketserver.py", line 466, in server_bind
    self.socket.bind(self.server_address)
PermissionError: [Errno 13] Permission denied


  ## Display all active connections and the corresponding TCP / UDP ports.

  netstat -at
mountblue@mountblue-pc:~$ netstat -at
Active Internet connections (servers and established)
Proto Recv-Q Send-Q Local Address           Foreign Address         State      
tcp        0      0 localhost:domain        0.0.0.0:*               LISTEN     
tcp        0      0 localhost:ipp           0.0.0.0:*               LISTEN     
tcp        0      0 mountblue-pc:59110      lb-140-82-113-25-:https ESTABLISHED
tcp        0      0 mountblue-pc:34782      lb-140-82-113-25-:https ESTABLISHED
tcp        0      0 mountblue-pc:38456      216.200.232.253:https   ESTABLISHED
tcp        0      0 mountblue-pc:46074      93.243.107.34.bc.:https ESTABLISHED
tcp        0      0 mountblue-pc:55288      162.159.136.234:https   ESTABLISHED
tcp        0      0 mountblue-pc:55288      162.159.136.234:https   ESTABLISHED
tcp6       0      0 ip6-localhost:ipp       [::]:*                  LISTEN   
  

## What's your local IP address?


## Find the IP address of google.com

mountblue@mountblue-pc:~$ nslookup google.com
Server:		127.0.0.53
Address:	127.0.0.53#53

Non-authoritative answer:
Name:	google.com
Address: 142.250.195.142
Name:	google.com
Address: 2404:6800:4007:81d::200e

## How to check if Internet is working using CLI?

Hit any url with browser command it will act as finding and it can only find if internet is there








