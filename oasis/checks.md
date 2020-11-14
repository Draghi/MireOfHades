# /moh/oasis/checks/

Checks are performed whenever an action has a chance of failure. Typically either the Gamemaster will decide when a check is required, or the action itself will explicitly call for a check. When a character is asked to make a check, they will be told which skill the character should use for making the check - which affects how many dice they roll and what number they need to roll under.

## Performing a Check

You're running from a hit squad through the sewers, round a corner and nearly run head-first into a deadend. You pause for a brief moment, turn and go to start heading for another branch, but you can already see the beams of their torches hitting the courner's walls. Looking again at the deadend, you notice that just bellow the water's there is a small inlet pipe that you think you could swim into.

You tell the GM what you'd like to do, and they ask you for an "Athletics Check".

In-order to make this check you need to first find the skill on the character sheet. Next to the skill there will be a number, this is the character's "depth" in the skill. The skill will be listed in a training category - master, expert, novice or untrained - and the number written next to the category denotes the character's "breadth" with the skill.

You roll a number of 12-sided dice equal to your breadth with the skill, and discard any dice that are greater than your "depth" in the skill. The number of remaining dice is the "height" of the check, and the highest value amoung the remaining dice is the "degree" of the check. Generally, the "height" of the check determines your success and the "degree" determines secondary effects. You then report both these numbers to the GM.

For example. The character diving into the pipe has a 6 depth in the skill, and 4 breadth. They roll 4d12; giving them 4, 6, 7, 9; they then drop 7 and 9 because they're large than the skill's depth; leaving them with a height of 2 and a degree of 6. The player tells the GM "2 to the 6th degree" or some varation there-of. The GM informs them that they strugge against the pressure coming from the pipe, but manage to swim and pull themselves about half-way through and are now holding their breadth.

### Modifiers

There are a few ways that a check can be modified. Typically, this will only every change the breadth for the roll, but there are a couple cases where the depth will be affected. Modifiers can never take you below 0 on breadth/depth or above 12 on depth.

#### Replacement

The foremost example of this would be firearms. Guns shoot a limited number of bullets within a time period which gives you a fixed number of opprotunities to land a hit. As such, most firearms will provide you with a breadth number to roll with when attacking (ie. a revolver might only be able to reasonably shoot one bullet, which gives you a fixed breadth of 1, where-as a burst fire rifle might have a fixed breadth of 3). In this case the height of the roll determines how many times you apply damage.

#### Advantage/Disadvantage

Certain environmental factors, resource availiability, aid/harrasment and prior actions may affect the number of dice you roll. For example, having access to a library may increase your checks breadth whilst attempting to improvise a lockpick with a bobby pin might decrease the breadth of your check. An enemy could try to push your gun away if you're within point-blank, or an alley could distract an enemy so you can land your blade.

In rare cases, advantage/disadvantage can even modify your skill's depth. In the case of a conventional firearm, taking a moment to steady your aim, look down the scope and get a feel for the wind can grant you a little extra depth, enough to get another bullet in your target. Something like a beam weapon on the otherhand would just hit the target for longer, granting you extra breadth like normal.

In cases where there is no modifier explicitly called, the gamemaster may assign these values however they decide. In general these modifiers will rarely, if ever, exceed +/-3. Additionally, replacements are always applied after advantage/disadvantage.

Advantage and disadvantage cancel out, and you only use the greatest source of advantage/disadvantage - this is mostly to stop out-of-control stacking, and a GM may grant exeception or a lesser extra bonus/penalty in the case of excess sources. Typically when talking about advantage/disadvantage the GM will tell you something like "You've got 2 advantage because of X". Unless mentioned explicitly, assume that the advantage/disadvantage applies breadth and not depth.

## Opposed Check

An opposed check is identical to a regular check, except there is two or more actors attempting to perform a mutally exclusive action (ie. two people diving for a gun, someone trying to break out of a grapple and the grappler trying to prevent them).

All actors make the relevant check for what they're doing. The one with the greatest degree wins. In the case of a tie, each actor discards their highest value die and compare again. This repeats until someone wins, or they lose all of their dice - which means that no actor wins. The winner, with their remaining dice, resolves the action - this means that the winner may still fail the check, particularly in the case of ties.

For example, 6 people are diving for a gun:
- First keeps 3, 7 on their check (height 2, degree 7)
- Second keeps 5, 7, 7 on their check (height 3, degree 7)
- Third keeps 7, 7 on their check (height 2, degree 7)
- Forth keeps 5, 7, 7 on their check (height 3, degree 7)
- Fifth keeps 1 on their check (height 1, degree 1)
- Sixth keeps nothing on their check (height 0, degree 0)

Resolution:
- Sixth and fifth are immediately eliminated because their degree is smaller (0, 1 <  7)
- The first 7 each of them rolled is discardes, this eliminates the first (3 < 7)
- The next die is discarded, this eliminates Third as their degree goes to 0 (0 < 5)
- The next die is discarded, this eliminates no one.
- Since it's a true tie, the outcome is a loss for all participates.

The GM rules that in the scramble, the gun is knocked half-way the the ledge of the building. There's still another chance for them to get their hands on it, or deal with the others, but failing again might knock the gun over the ledge. Failing to make the check after the tie resolution would likely have had the same outcome.

This system is **explicitly** designed to create no-win situations like these when there are a lot of participants.
