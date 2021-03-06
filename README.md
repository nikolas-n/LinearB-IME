# Online Transliterator of Linear B (another github repo)
If you're interested, I have made (out of a fork) an online transliterator of Linear B whose code is [here](https://github.com/nikolas-n/LinearB-transliterator) and it can be used [here](http://linear-b.kinezika.info).

---

# How to write in Linear B on your GNU/Linux computer
Input method based on the [ibus](https://github.com/phuang/ibus) package for the [Mycenean Greek](https://en.wikipedia.org/wiki/Mycenaean_Greek) script of [Linear B](https://en.wikipedia.org/wiki/Linear_B). The build was guided by [Study Mongolian](http://www.studymongolian.net/technical/how-to-create-linux-input-method-editor/). 

## How to install
1. Install ibus
2. After you clone the repository, run from that folder the following: `sudo ibus-table-createdb -n /usr/share/ibus-table/tables/linearb.db -s linearb.txt` AND `sudo cp linearb.svg /usr/share/ibus-table/icons/`
3. Restart ibus with `ibus-daemon -drx`

Then you can choose Linear B as an input method (usually with Ctrl+Space).

## How to use
You just type the words and the Linear B characters are shown. Those who have used pinyin to type Chinese know exactly what it is meant by the above. So, you can just type wanaka (meaning king) and the three respective characters will show up. There is also the ability to choose among characters. If one types *w* then four choices are listed: *wa*, *we*, *wi*, *wo* and one can choose.

## Notes
The phonetic values of the syllabograms have been taken from the [wikipedia article for Linear B](https://en.wikipedia.org/wiki/Linear_B#The_script). The names of the ideograms have followed the naming found in the same article and, more specifically, from the CIPEM column of the table titled **Ideograms**. For instance, if one types *sus*, the character U+10042 is shown, whose CIPEM is *sus* and means *pig*.
