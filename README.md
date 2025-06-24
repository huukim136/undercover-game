# Undercover Game

Life’s just more fun with social games—and Undercover is one of the best. I tried a similar game from the App Store, but the randomness was off, so I ended up building my own version.

Shoutout to Claude for doing the heavy lifting—about 99% of the code was written by Claude.

## Game Description and Rules

"Undercover" is a social deduction word game where players try to identify each other's roles based on secret words and descriptions, with the goal of uncovering the "Undercover" or "Mr. White" (impostors) or eliminating them. It's similar to party games like Werewolf or Spyfall, but with a focus on wordplay and deduction.

### How it Works

1. **Roles and Words**:
   - Players are secretly assigned roles: Civilians, Undercover, or Mr. White
   - Each player (except Mr. White) receives a secret word
   - Civilians all get the same word
   - The Undercover gets a similar but slightly different word
   - Mr. White gets no word

2. **Describing the Word**:
   - Players take turns giving brief, truthful descriptions of their word
   - Mr. White must improvise and describe something based on the situation

3. **Deduction and Discussion**:
   - Players discuss the descriptions
   - Try to identify who has a different word (the Undercover or Mr. White)

4. **Elimination**:
   - Players vote to eliminate one person
   - The app reveals the eliminated player's role
   - If Mr. White is eliminated, Mr. White has the last chance to guess the word of civilians

5. **Winning Conditions**:
   - **Civilians**: Win by correctly identifying and eliminating Undercover and Mr.White 
   - **Undercover**: Win by either not being identified and eliminated until the end of the game
   - **Mr. White**: Win by either not being identified and eliminated until the end of the game or by correctly guessing the Civilian's word
