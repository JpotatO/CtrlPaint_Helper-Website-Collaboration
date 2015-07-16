<h2>How To - Content management and Workaround</h2>
﻿
﻿<em>This content is temporary, it will be updated with pictures and a little guide to know how to work easily.</em>
﻿<hr/>

<h4>Collaboration:</h4>

The main goal of this website is to help «students» following the «Ctrl+Paint Free Video Library Guides» by Matt Kohr to learn easily and have fun while learning.

<strong>Our main objective is:</strong>

<ol><li>All users need to comprehend the subjects, in this case we need a multi-language system for both our «Website-Helper» and for the Original Video Guides content - The subtitles and the text lesson -.</li><br/>
<li>The users need to have more interest, more fun, and more help, it's comparable to "gamified tasks", while keeping in mind the communication and sharing.</li></ol>

<h5>WE NEED YOUR HELP:</h5>

There is a very large quantity of information available, Matt Kohr created a quick and full learning course to learn drawing, painting, and digital arts very simply.

<blockquote>At the moment we have 248 files to transcript (some are already maked) - and need to translate when the original English is complete - theses files goes from a range of 3 to 10 minutes , you can see the list of all the videos, based on the original display structure and with their duration from the **Videos_Tree.md** (this content is actually in the **HOW_TO.md**)</blockquote>

 <strong>- We need you to:</strong>

× Convert to text the Voice of Matt Kohr from the Free Videos Guides using Audio-Transcription.

× Translate the original text content (shown below the videos), and the Speech-to-Text data (a.k.a. subtitles).

× Share our website and [Ctrl+Paint](http://ctrlpaint.com) to help more "eventual" artists progress, and construct a better community.
We will need administrators, Moderators and theses kind of people that can easily work on online projects, and communicate.

× Web Developers and Designers can help us create a multi-lang content, the membership and point system,  the Homework system, the forums and other important things.
<hr/>
<h4>Working with GitHub:</h4>

We created a precise management of files and folders on GitHUb, for Example a root folder containing all translation for the Videos Subtitles, the Video Text Content, the Website Helper… .

It's the simpler way to manage this large quantity of files and data.

<u>What you can do or not:</u>
[-] You can't rename the folders and files except the «Root Translation Folder» (ie: English (Original)).<br/>
[+] Instead you can add the translated name of the Files in the actual file header.

Then if you want to create a new Translation of the existing files:

<ol><li>Create a Branch, and use your Pseudo/Name as his name.</li>

<li>Use GitHub for Desktop and clone the Repository if it's not already the case:</li>

    <ol><li>Open the command run (on windows)</li>
    
    <li>Paste this command: github-windows://openRepo/https://github.com/JpotatO/CtrlPaint_Helper-Website-Collaboration.git</li></ol>

<li>Open the Folder where you saved the repository (start by selecting your Branch in the Github desktop app', it change the structure of folders in real time in your explorer).</li>

<li>Duplicate the Folder Named English (Original), and rename it by the language that you want to make, but the name need to be in english (then German, Italian, French, Russia, etc…).</li>

<li>Now you can edit any of the files (don't rename any other folders) contained in this "Translation Root" folder.</li>

<li>When you finished use GitHub desktop to Submit a new commit to your Branch.</li>

<li>When you have worked a lot, and created things that don't exist in the Master Repository, you can submit a "Pull Request" to Master, we will examine it and see the changes, if all is good we update the Master with your content!</li></ol>

<hr/>
<h4>Working with Audio Transcription and Subtitles:</h4>

Before starting to translate anything we need to «Convert» the voice to text, this method is called Audio-Transcription and there is some tools available.

At the moment we use «Subtitle Edit» by [Nikse.dk](http://www.nikse.dk), you can download a release from their website.

The best thing about this software is that we have full control over the start and end time (like in AHD Subtitle Maker pro but easier), for a perfect control of the times you need to use the «WaveForm window», but to generate a spectrum you need to have VLC 1.1.* or later installed, then go to [videolan.org](http://videolan.org) and download the last VLC Media Player release, then install it.

Another info on the Waveform: Normaly we can see the classic Wave form, but in the parameters of the program you can show a "Real Spectrum" (like we can see in FL Studio for example (I don't know many that have this spectrum feature)), it's more accurate than the simple Waveform.

<blockquote>Think to define the best keyboard Shortcuts for you to work efficiently, for example I use:<br/><br/>

CTRL+ALT+P (or ALT Gr+P), or SPACEBAR: to Play/Pause the playback.<br/>
CTRL+ALT+Left/Right (or ALT Gr.+Left/Right): To move current position by -500ms/+500ms.<br/>
CTRL+ALT+Inser. (or ALT Gr.+Inser.): To add a new Subtitle at the current time position.</blockquote>

<h5><strong>Here's how I work to make the Transcription:</strong></h5>

<ol><li>I use the Waveform to visualy see the speech passages, I create Subtitles at their positions while trying to not have a too long duration (then I search the "Dead Time" parts to set the end time), and I do this for the complete video.</li><br/>
<li>I listen only to the passages that I've marked as subtitles, is more efficient to select the "Next Subtitle" than navigating with the control bar, then I write what I hear in the subtitle text box.<br/>
<em>[!] When I can't seem to understand a word or passage after some try, I use "!???!" to define one word, if I can't understand a passage I use a thing like "!??? ??? ???!", each "???" represent a word, if I don't know how many words are missed I just use the same as unique word "!???!".</em></li><br/>
<li>When I finish to write all sentences, I play the video another time in Subtitle Edit, I read the subtitles while listening, and when I see that I missheard a word I make changes imediately, in normal time I replay 2 times or more to be sure that I've used the maximum of my understanding.</li></ol>

[!]Manual Transcription is a Hard work, and long too, but for now we don't have a perfect (and free) way of doing this programmaticaly.<br/>
Then organize your worksheet, or use my method described above and adapt it if needed, your goal is to be fast and efficient, without making a fully messy work at the end. : )
<hr/>
<h4>Creating the Subtitles:</h4>

Now that we use Subtitle Edit, just creating the transcription correctly - Setting the Start and End times correctly - have created the subtitles, then no more work to do !<br/><br/>
Just saving the subtitles to a .srt format (Sub Rip, it's the default format of the software too), and then copy the content of the file to the Github file related to the video that you've worked on, in the Subtitles section (starting and ending with "```").

<strong>Another last minute Info:</strong><br/><br/>
I think to create a special folder in each Videos categories folders (ie: 01) Digital Painting 101), they will contain the *.srt subtitles files, it can be much simpler than copy-paste each time the content of theses files…<br/><br/>
But I wanted to have One File for One Lesson… well we'll see on it, just keep your .srt for now !
