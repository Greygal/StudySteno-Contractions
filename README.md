# StudySteno:  Greygal's Contractions Dictionary  
My [Plover](http://www.openstenoproject.org/) steno dictionary of contractions and briefs for the related non-contracted phrase, based on [Waleed Khan](https://waleedkhan.name)'s approach to writing contractions with an asterisk (*). I think his approach is genius, so over time I integrated the use of `*` for contractions into my own dictionary. See https://waleedkhan.name/blog/my-steno-system/#use-asterisks-for-apostrophes-in-contractions for details.  
  
Fair warning, I tend to over-explain the obvious.  
  
## Some definitions  
  
Brief = single-stroke abbreviation of one word  
  
Brief pair = a pair (or set) of briefs that represent similar or related briefs or phrases but for a minor difference between the two (such as "that'll" and "that will" - they are essentially the same words, but with the minor difference being one is a contraction and one is not).  
  
Contraction = a word or group of words resulting from shortening and/or combining two or more words into a single relative word.  Example: It is = it's  _Note:_ "Non-contracted" or "uncontracted" refers to the words used to create the contraction, before contracting it.  "It is" is non-contracted/uncontracted, "it's" is contracted/contraction.  
  
Entries = Refers specifically to entries in Plover's dictionary, but can apply to any steno dictionary.  
  
Phrase = single-stroke brief (abbreviation) that represents more than one word  
  
Plover = A fantastic, completely free, open source steno software program.  Plover has evolved into a full-featured, highly customizable yet simple to use program that lets anyone at all use steno to write, even if they don't have a steno machine. Plover has a great community of self-taught steno fanactics on Discord, too!  For more information about the Open Steno Project and Plover, visit http://www.openstenoproject.org/ and https://github.com/openstenoproject/plover  
  
Star = asterisk (*), specifically, the large center key on a steno keyboard that is represented by the `*` symbol in raw steno.  
  
# WHY  
  
Plover has entries for briefs covering all common English language contractions, and most of the less common/archaic ones.  Many of these entries already use `*`, but many do not.  This makes sense in some ways, since one tends to want the simplest briefs to write to be reserved for the most common words and phrases, and many steno users consider non-* briefs to be simpler to use.  
  
However, you end up with some pattern inconsistencies, where the contracted phrase doesn't use a star sometimes and other times it does use a star.  
  
I think, especially for those learning steno, that *always* using `*` to designate the contracted version of a phrase, plus defining the non-`*` version of that brief to be the non-contracted version of that phrase, is far simpler to learn and remember.  
  
Essentially, all common two word phrases use the most common right-hand (usually) brief for the first word combined with the most common left-hand brief for the second word (the contracted word), to create a brief for a contraction or for a phrase.  
  
> `TH` = "this"  
> `-L` = "'ll"  
  
Therefore, it makes sense that `TH-L` would be "this'll"  
  
But wait! What about a brief for the phrase, "this will"?  Don't we also commonly use `-L` for "will" when creating briefs for phrases?  Well, yes, indeed, we do!  So why don't we just use `TH*L` for "this will?" ... oh, wait, `TH*L` is already in the dictionary for "this'll" and there's no entry at all for "this will" ... wouldn't it make sense to just change either `TH-L` or `TH*L` to be "this will" and "this'll"? Hrm...  
  
So as I dug deep into the dictionary, it did seem that more often than not, the non-`*` version of a pair of related briefs/phrases was the contracted version, and the `*` version was either ALSO the contracted version of the phrase, or it was the non-contracted version. So I made the decision that I'd go with the flow and started to dutifully edit the `*` version of entries that were identical to the non-`*` version to be the non-contracted phrase, or to create a `*` version if it didn't already exist.  
  
Except... the dictionary isn't consistent in its inconsistencies.  For example:  
  
> `WH-L` "when will",  
> `WH*L` "when'll",  
  
> `KH-L` "which will", but no entry whatsoever for "which'll" (granted, it's not a very common contraction).  
  
> `EU` = "I"  
> `AOEUL` = "I'll  
> `HR*EU` "I will"  
  
Then there's the entire would/could/should family of briefs and phrases... sometimes they use `WO`/`CO`/`SHO` as the starter, sometimes `WOU`/`COU`/`SHOU` ... and contracted phrases are usually using `*` while non-contracted phrases are not....  
  
Sigh... while there are patterns within the patterns and virtually every entry whether for a contraction or non-contracted phrase actually does hold true to the principles of steno, **_having a singular, (mostly) all-encompassing approach to briefing contractions and their non-contracted phrase is preferable to trying to remember which brief pair uses which of the various approaches,_** to say the least.  
  
Of course, as many before me can attest to, I quickly realized if one keeps the non-`*` version of a brief pair to be the contracted version, and the `*` version to be the non-contracted version,  you're running into some heavy-duty mental gymnastics trying to remember which common phrase briefs use `*` and which don't... and the simple fact that there's no entry whatsoever for a ton of common non-contracted contractions.  
  
> `TH-L` and `TH*L` both for "this'll", no entry for "this will," but `TH-B` for "this be" ...  
  
There's gotta be a better way, and of course, there is.  **Waleed's way:  Use * for ALL contractions.**  
  
I set out to integrate his approach into my own dictionary, and herein I present to you my contractions dictionary, complete with non-contracted phrases paired with each contraction.  This dictionary is compatible with Plover 4.0x version, and while it probably works with older versions, I don't support the older version and you should seriously, really, like right this very minute update to the latest weekly release of Plover.  
  
# HOW IT WORKS  
  
Non-contracted phrase:  Take the most common left-hand brief for the starter word (note I tend to prefer phoneticly-true briefs) and combine it with the most common right-hand "phrase ender" brief for the ending word.  
  
Contracted phrase: Same thing, but add `*`  
  
## Left-hand phrase starter words:  
Most of these will already be familiar to you, as I utlized existing norms as much as possible.  
  
Brief|Word  
-----|------  
AOEU, EU|I _(see note in the "tricky bits" section.)_  
H|had  
HA|has  
HAOE|he _(note that `HE`-based entries still exist for some phrases, I prefer the phonetic `HAOE` entries)._  
HAOER|here  
HOU|how  
HR-|will  
HRET|let  
K-|can  
KH|which _(note that the most commonly-used brief for the word "which" is `WEU`, but creating phrase/contraction briefs using `WEU` as root creates far too many conflicts.  `KH` on the other hand is already used for a number of phrases in the default dictionary, so used `KH` to create briefs for related/missing contractions.)  
KO-, KOU |could _(`KOU` is preferred.  Note I'm migrating away from using `KO`, as I prefer the `KOU` version, although sorting out conflicts is ongoing.)_  
KWR|why  
PHAOEU|might _(note the dropping of the ending `-T` for purposes of briefing and finger sanity)_  
PHU|must _(note the dropping of the ending `-FT` for purposes of briefing and finger sanity)_  
R-|are  
SHAOE|she _(note that `SHE`-based entries still exist for some phrases, I prefer the phonetic `SHAOE` entries.)_  
SHO, SHOU|should _(note I'm migrating away from using `SHO`, as I prefer the `SHOU` version.)_  
SPH-LG|something  
SPH-PB|someone  
SPH|somebody  
SR-|have  
T-|it  
TH|this  
THA|that  
THAOES|these  
THE|they _(don't get me started on the conflicts caused by a phonetic entry for "they")_  
THOE|those _(basically, drop the `-S` or `-Z` from the base `THOES`/`THOEZ` outline for briefing phrases)  
THR|there  
TK-|did  
TKOE|do  
TKU|does _(By default, "does" is `TKUZ`, `TKOS` or `TKAOS`. For phonetic reasons, I prefer the `TKUZ` entry for "does," and for finger sanity reasons, I drop the `Z` when briefing phrases, therefore, the left-hand starter brief for "does" is `TKU`.)_  
U|you  
W-R, WR-|where - read note in https://github.com/Greygal/StudySteno-Contractions#tricky-bits-to-watch-out-for section below. _(I am seriously considering using `WHR` are root brief for "where" even though its stand-alone brief for "whether" - but `WHR` "fits" the pattern of `WHA`/`WHE`/`WHO` so much nicer than `W-R` does ... sigh...)_  
WAOE|we _(note some `WE`-based entries still exist for some phrases due to conflicts, I do prefer phonetic version of `WAOE`, although still resolving conflicts.)_  
WH|when  
WHA|what  
WHO|who  
WO, WOU|would _(note I'm migrating away from using `WO`, as I prefer the `WOU` version, although sorting out conflicts is ongoing.)_  
WR-|were  
  
## Right-hand phrase enders:  
Again, most of these will already be familar to you.  Simply add/tuck them into the left hand starter brief to use.  
  
Brief|Word  
-----|------  
-BGD|could  
-D|had, also used as contraction for could, should and would, also sometimes did  
-F|have  
-L|will  
-LD|would  
-PBT|not  
-R|are  
-RBD|should  
-S|is, sometimes us such as in "let us", and contraction for "has"  
-Z|has  
  
## To make the phrase a contraction, simply add `*` to the brief.  
  
> `THA` = that  
> `-S` = is  
> `THA-S` = that is  
> `THA*S` = that's  
  
> `TK` = did  
> `-PBT` = not  
> `TK-PBT` = did not  
> `TK*PBT` = didn't  
  
# TRICKY BITS TO WATCH OUT FOR  
  
## Y'all and you all  
  
"y'all" is written phonetically with `*`, not with starter `U`:  `KWRA*UL` = y'all  
  
But since `U-L` is "you will," I use `KWRAUL` for "you all", which is consistent with the pattern for y'all but not phonetically true.  
  
Note: "Y'all" is **_never, ever_** written as "ya'll" and if y'all insist on writing it as "ya'll", y'all can just go eat lemons.  
  
## Won't and will not  
  
Technically, "won't" is the contraction for "will not", so the dictionary contains entries for phonetic "won't" and (semi) logical "will not" contracted:  
  
> `HR-PBT` will not  
> `HR*PBT` won't  
> `WO*PBT` won't  
  
Note that the entry `WOPBT` was changed to the word "wont" which, while it's not a commonly-used word anymore, should remain in the dictionary.  
  
## Anything that starts with I  
Some default entries use `EU`, some  use `AOEU` ... sigh... resolving the conflicts in this family is a challenge that probably dates back to 1911... this is a work in progress.  For the most part, most entries use `AOEU` for I, but there are some noteable exceptions, such as:  
  
> `EULD` I would (because `AOEULD` is "island" and although there are other entries for "island" I kinda like this one...)  
> `EU*LD` I'd (because `*EUD` maps to "Idaho")  
> `AOEUD` I had (because EUD maps to id and just don't get me started whinging on all the variations of I.D. ID id ...)  
> `AO*EUD` I’d  
  
## W-R for "where" exception  
`W-R` is used for "where," except for where `WR-` is used, such as for where are, where have, where will, and a few others.  When using `WR-` would conflict with briefs for the "were" family, we use `W-R` ... yes, this is suboptimal.  We can't use `W-R` for this, since that's the root brief for "where" family, and we don't want to just use `WR` as the brief for "where" because that's the root brief for the "were" family... ideally, we'd use `WHR` as the root brief for all the briefed phrases and contractions that are part of the "where" family ... except the use of `W-R` is *really* well-established for "where", and the potential for a bunch of phrases that start with "whether" is noteable... so for now, "where" is _either_ `W-R` or `WR-` depending on conflicts. Eventually I'll sort out consistency on this.  Example:  
  
> `WR-R` where are  
> `WR*R` where're  
> `W-RS` where is  
> `W*RS` where's  
  
## Double contractions  
  
Fortunately, there are very few double contractions - that is, a root word with two contractions.  They work essentially the same as all other contractions, except you are "tucking" two right-hand endings, and the non-contracted phrase is three words.  
  
> `KOU` could  
> `-PBT` not  
> `-F` have  
> `KOUFPBT` could not have  
> `KO*UFPBT` couldn't've  
  
> `WAO*EFD` we'd've  
  
# HOW TO INSTALL  
Simply download _contractions.json_ file, then add it to your Plover dictionaries by clicking the big, round green `+` button at the bottom of the main screen.  By clicking and dragging, move _contractions.json_ so that it is **higher** priority then _main.json_ and _commands.json_ dictionaries, but either below or above your _user.json_ dictionary file in priority, depending on your preference.  
  
If you would like to view documentation on all the changes/edits/additions/etc. that the contractions.json file overlays on the default dictionary, refer to the "Documentation of Dictionary Changes.md" file.  
  
# NEED TO DO/FIX/FINISH  
  
See the "Coming Soon" section of the "Documentation of Dictionary Changes" file to view the complete to-do list.


  
