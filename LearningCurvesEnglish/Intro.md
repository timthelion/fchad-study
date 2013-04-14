Learing curves of the FCHAD braille display
===============================

The interesting aspect of this study is the novelty of the task being learned.  The task of using an FCHAD display is both complex and novel.  While the participants of the study all had experience with classical braille text and peizoelectric braille displays none of them had ever heard of, not to mention used, an FCHAD device.  This fact was ensured, by the fact that at the time of the study, only one FCHAD device existed in the entire world and it's invention has remained unknown.

Outline
=============

- [Review of liturature](Theory.md)

- Description of device - theory of device

Notes on building such a device
---------
The device comunicates with brltty with the UOBP driver found here.  The arduino is to be flashed with the FCHAD firmware found here.  The arduino is connected to 8 paralel solenoid circuites as described TODO here, using MOSFETs of type IRF530N.  The solenoid power circute is powered by a 6 volt 4 amp wall power supply of type "Smart Electronic Switching adapter Model:JGS1002-24060-2E".  Touches were detected using a 16 channel MUX of type CMOS4067 connected to 4 digital IO pins and one analog pin.  The analog pin was connected to ground with a 10k ohm resistor of type RM0207 "resistor with metalic layer 1% TK50 0.5W RM 7.5mm".



- Relation to the opticon, optaphone, computer mouse.  Training the dissconnect between the cursor and the center of focus.

 - description of experiment
  - precice description of device
  - Exploratory study:

The device consisted of the FCHAD cell which has 8 dot/holes placed in two collumns of 4, each row virtically seperated, dot to dot 2 cm.  The collumns were horizontally seperated by 5cm[see appendix B picture 2](AppendixB.md).

 - description of how the experiment was run

  The subjects were seated in front of the device, at a table, but with the device pushed away from them, out of easy reach.  They were told to wait while I prepaired the materials, in this time, I turned on brltty, and started the recording. I also placed a single double sided _x_cm sheat of braille printed paper in front of them printed in 6 dot format, with _ collumns.  They were then told to read the text on the paper outloud.  The text is included in [apendix A](../reading_samples/tisk.txt) with the same formatting as was printed in braille.  The subjects were then asked if they consented to the study, and asked biographical questions.

  After the question session was over, the subjects were told that we would now begin.  The device was places within reach, and the subjects hands were placed on the device in the correct possition for reading.  The subjects were verbally told what each part of the device.  Then the subjects were asked to wait.  I then checked to make sure the device was displaying the text properly.  When I made this check, I had to push the subjects right hand out of possition.  This check was necessary, but unfortunate.
  After the test, the subjects were told to try reading with the device.  It was determined in the initial study, that subjects will not be able to continue on their own.  They were given verbal prompting and verbal confirmation.  They were told "now try to read the first letter." Unfortunately, due to my own difficulties with language proficiency, I said "Písmo"(font) instead of "Písmeno"(letter).  I do not know what the effect of such a mistake had on the study, but I made it repeatedly.  I was never told, by my subjects, that they did not understand.  Nor was I corrected in my error.  My command, despite it's error, was always headed.

  Once the subject had told me what they thought the first letter was, they were either told that they were correct, and that they were to proceed with the seccond letter, or they were told that they were wrong.  If they moved their sellecting hand too far, or not far enough, they were told of their error.  Usually, the subjects learned to move their sellecting hand on their own, whithout propmting.  When prompting was not required, they were given a confirmation that they had read the letter correctly, but not prompt to continue.  When the subject made a mistake while reading, they were never told the correct answer.  They were told that they had guessed incorrectly.  If the subject imediately corrected themselves, they were then given a verbal confirmation.  If they did not, they were either asked which points were up, told that they had failed to read one dot(by telling them that a dot remains for them to feel "ještě"(still one more dot), if they guessed incorrectly because the character was a non standard latin character such as a punctuation mark, number, or a character "underlined" with a line begin marker they were sometimes told what that character meant, but this was never in a way as to tell them directly what the answer was.  They were first asked "what dots are raised?" and once they answered correctly they were told, for example "dots 7 and 8 being raised means the beginning of a line."

- Results

 - [Description of each subject, and session.](Subjects.md)
 - Overall conclusions.
 - Dot 3 problems
 - Problem of feeling correctly, but guessing the letter incorrectly.  Relation to  [a study on braille character shapes](http://web.econ.keio.ac.jp/staff/nakanoy/article/braille/BR/chap2/2-6/2-6.html#sect2)

- Compairison to Optocon + results

Thanks,

I would like to thank Samuel Thibalt for his work on designing the low level protocol for the braille device.  David Mieke for his work and advice on the drivers.  The members of Brmlab Prague for their technical assistance and advice.  Colah for the ImplicitCad API which was used in designing physical features of the device.  Members of the freenode IRC channels ##c, #arduino and #haskell for their support.  Tiskarna ... for printing materials used in this study. Gymnasium ... for providing facilities and subjects used in this study. And my advisor Ka.. Duschinska`.


