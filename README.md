# l4d2_new_generation_scoremod

 * -------------------------------------------------------------------
 * ---------------Introduce of new generation sourcemod---------------
 * -------------------------------------------------------------------
 * 
 * ===================================================================
 * ===========================Main Parts==============================
 * ===================================================================
 * 
 * The score system Includes six parts:
 * 1. Map Distance Bonus;
 * 2. Permanent Health Bonus;
 * 3. Damage Bonus;
 * 4. Great Skill Bonus;
 * 5. Pills Bonus;
 * 6. Condition(When survivors made it to saferoom) Bonus.
 * 
 * ===================================================================
 * ============================Per Parts==============================
 * ===================================================================
 * Ⅰ. Map Distance Bonus:
 *      Comes from map value "VersusMaxCompletionScore", divided by
 *      survivor team size, and plus teamsize(g_iMapDistance);
 * Ⅱ. Permanent Health Bonus:
 *      One basic evidence of surviors` power, come form survior`s 
 *      Permanent health, and once survivor incapacitate, his Bonus
 *      decrease to 0;
 * Ⅲ. Damage Bonus:
 *      Now the damage bonus is more reliable then the origin one which
 *      make survivors lose almost all bonus after a player died, and 
 *      lead to hope even more remote;
 * Ⅳ. Great Skill Bonus:
 *      This part of bonus depend on "l4d2_skill_detect", when survivors
 *      make nice skill they will get SB(skill bonus) until it comes to
 *      the cap, and infected can also do skill to deduct surs` SB;
 * Ⅴ. Pills Bonus:
 *      It`s the same as origin pills bonus, per pills equal distance 
 *      bonuse divided by 20;
 * Ⅵ. Condition Bonus:
 *      Just a consolation prize for survivors so they may not get a "0"
 *      when made it to saferoom after hardships.