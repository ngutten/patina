Some tasks take place over an extended period of time, involving sustained activity by characters. Examples of this could be a long march through the wilderness, the construction of a building, holding their breath underwater as long as possible, or performing a ritual over the course of hours.

Extended tasks have a particular **interval**, and either a fixed or variable number of **intervals** for completion. A continuing activity such as holding one's breath lasts for as many **intervals** as the character wishes to keep their breath held - they can stop at any time (though hopefully somewhere they can take a breath). Something like crafting an item will take a certain number of **intervals** to complete based on the item.

Every time the **interval** comes around, the character must again meet the [[Success Threshold]] of the task, spending additional resources if needed. Bonuses purchased for previous checks as part of the extended task do not carry forward, but in the case of [[Cumulative Difficulty]] the success threshold would increase every **interval**.
#### Going Faster

Extended tasks may be accelerated by voluntarily raising the [[Success Threshold]]. Take the total `ST` summed across all expected **intervals** and divide that by the new `ST` - that is the new number of **intervals** required. Do **not** include additional [[Cumulative Difficulty]] expected to accrue over the course of the task.

E.g. a character performing an `ST 4 (5I)` task needs to make a total of 20 score across the entire task, so they could do this instead as an `ST 10 (2I)` task. They could not however choose to lower the base difficulty and do it as `ST 2 (10I)`. 

In the case of cumulative difficulty, a character might have a `ST 2+3C (4I)` task. If they had no accumulated cost yet, then the total they need is 8 - they could this a single **interval** at `ST 8+3C (1I)`, and only accumulate one level of extra cost if they needed to do this again before a reset. 

If the character already has accumulated cost when going into the task, the math is a bit more complicated. Take the current level of accumulation as determining the base `ST` and then start counting again from zero. So in the above example if the character has already done this once, then it acts as if the task is `ST 5+3C (4I)` but with `C=0` rather than `C=1`. This means that instead of 8 they would need 20 total score. They could choose to do this as four checks at `ST 5, 8, 11, 14` or as two checks at `ST 10, 13`.  At the end, their accumulated cost would be 5 levels in the first case, or 3 levels in the second.
#### Interruption

Some extended tasks require continued attention, whereas others can be interrupted and returned to. A character can't generally 'take a break' from holding their breath. But when crafting an item a character could do some work on it, leave it, and return to it much later even if the same might not be true of a magical ritual. Tasks which are [[INTERRUPTIBLE]] allow the character to step away and retain their progress. 

Alternately, with extended tasks a character may generally interleave multiple tasks together at the same time unless one of the tasks has the [[EXCLUSIVE]] keyword, or the specific actions conflict with each-other such as holding your breath and singing at the same time. For example, a character could hold their breath and fight underwater simultaneously. Each additional simultaneous task a character tries to sustain beyond the first increases the `ST` of all tasks by +2. 

Non-extended tasks cannot generally be interleaved this way.