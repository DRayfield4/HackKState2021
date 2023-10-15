# HackKState2021
1st place in game design and 2nd overall winner of the K-State 2021 Hackathon

Description
A K-State themed side-scrolling game controlled either hands-free by eyesight or with traditional arrow keys!

Inspiration
We were inspired to make a game that utilized hardware in addition to software, and thought it would be fun to show off our K-State pride! With the help of an electrooculogram (a sensor that measures eye movements), we wanted to create a game that people could use without their hands. This allows for extended accessibility for people with low motor functions or even without the use of their hands.

What it does
Our game has 2 modes: one where you use the keyboard, and one where you literally look right and left to move Willie the Wildcat. You collect falling objects while avoiding those nasty birds to earn points to win the game. To use your eyes, we hook you up to an Arduino Uno with electrodes connected to your temples and forehead. Or, if you prefer, just use the keys for a different experience!

How we built it
Combining our software, hardware, and design capabilities, we were able to have a multifaceted design. The software we used is a combination of GameMaker Studio 2 and Arduino connected by an open-source DLL. Game Maker Studio uses its own language called GML which has similarities to Python, C#, and JavaScript. We have used these languages in the past, so GML wasn't too difficult to learn. We used an Arduino Uno with a breadboard to initially filter the input signal before digital filtering in Arduino IDE. Data acquisition occurs at the electrodes connecting to 3 points on your face to detect your left and right eye movements. In addition to the hardware and software, we wanted to make the game look as cool as possible. This required us to create all of our own animations using Piskel, an online drawing tool. All moving parts required us to have multiple iterations of each design. This means every frame of our game was hand-animated by us, which took up a lot of time and close concentration. GameMaker Studio nicely integrates with multiple frame animations which allowed the conversion into the game to be fairly simple once all the designs were made.

Challenges we ran into
The biggest challenge was dealing with the electrooculogram sensors being difficult to read. When you move your eyes to look right, it reads right, but then when you move back to center you are technically moving left (from right to center). This gave us a big issue trying to filter between true right and left reads. The sensor is still not perfect, but it has come a far way since we started.

Accomplishments that we're proud of
Connecting the Arduino software to the GameMaker software seemed like a big task, yet we have it connected with no errors and we haven't had any issues with the communication. Overall, we are super proud of the game as a whole and love the look and feel just as much as the gameplay. All of the hand animations were very time-consuming, but we couldn't imagine it looking better. The fireworks alone took about 2 hours for one person which is only about a 10-second clip. We are also really proud that this game can be used by lots of different people who may not always have the opportunity to use typical video games due to different motor functions. It has been such a fun weekend and we are all thankful to have bonded as a team and made a really cool product.

What we learned
We had not used GameMaker Language at all, which wasn't a huge learning curve but was definitely something new to learn. Although we had all had a bit of Arduino practice, 3/4 of us didn't feel comfortable with using it at all, and now feel proud of combining it with completely new software. This was the first time we created pixel art and animation. Creating the entire game with new art and animation is a feat we are proud to have accomplished.
