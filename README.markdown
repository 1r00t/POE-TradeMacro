**PoE TradeMacro** is an Autohotkey (AHK) script that provides several convinient QoL features for Path of Exile Trading.

This builds on top of [PoE-ItemInfo](https://github.com/aRTy42/POE-ItemInfo) which provides very useful item information on **ctrl+c**.
With TradeMacro, price checking is added via **ctrl+x** or **ctrl+i**. You can also open wiki via **ctrl+w** or open the item search on poe.trade instead via **ctrl+q**.

* For Gems, Quality and Gem Level >= 16 is checked.
* 5-6 Link and 6 Sockets are also checked.
* Corruption is always checked.

**Usage**

**[Dev Version/Beta release](#dev)**

1. Install AHK (http://ahkscript.org)
2. Download the latest [code](https://github.com/thirdy/POE-TradeMacro/archive/master.zip) and extract the zip-file. 
3. Make sure to run PoE in (borderless) windowed mode.
4. Run _run.ahk_ (as admin if hotkeys aren't working, or switch keyboard layout to english if your's is russian for example).
5. Default league is set to `tmpstandard` (Softcore Temp-League).
6. A lot of options, including the league can be changed by editing `trade_config.ini`. 

More features to be included in the future.

* Note that this a fork from the previous TradeMacro found [here](https://github.com/thirdy/trademacro). Motivation for this fork is to leverage ItemInfo's Clipboard Parsing code and to attempt at including Modifiers in price checking. It is also nice that user would only need to run 1 ahk script.

* Another note, in case you don't know, you can edit the file AdditionalMacros.txt to add your simple macro like logout for hardcore players.

![screenshot](https://cloud.githubusercontent.com/assets/75921/19019883/3ad6cb66-88c9-11e6-9592-46a8e4fc5e6b.PNG)
