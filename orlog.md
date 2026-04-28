Role: You are an expert Frontend Web Developer and Game Designer.
Task: Create a single-page web app for a simplified version of the Viking dice game "Orlog." The game should be built using a single file (HTML/CSS/JS) or a React/Tailwind sandbox.
Game Rules & Logic:

The Dice: Each player has 6 dice. The faces are weighted based on physical Orlog dice:
2 Faces = Axe (Melee)
1 Face = Arrow (Ranged)
1 Face = Helmet (Melee Defense)
1 Face = Shield (Ranged Defense)
1 Face = Hand (Steal HP)

The Classes:
Bowman: All Axes and Arrows count as Arrows.
Berserker: Axes deal 2 damage, but the player cannot use Shields.
Thief: Hands steal 2 HP. The Thief can click 1 opponent die after the final roll to "Negate" it.

Gameplay Flow:
15 HP per player.
Rolling Phase: 3 rolls per turn. Players can "lock" dice between rolls.
Resolution Phase (Order is vital): 1. Steal (Hands) -> 2. Ranged (Arrows vs Shields) -> 3. Melee (Axes vs Helmets).
Game Modes: - 2-Player: Local pass-and-play.
Single Player: Player vs. an AI Bot that prioritizes dice based on its class (e.g., Berserker Bot hunts for Axes). Technical Requirements:

Visuals: Use a "Viking" aesthetic—dark woods, stone textures (via CSS/Flexbox), and clear icons for the dice.
UI: Show Health bars for both players. Include a "Combat Log" that explains exactly how damage was calculated each round (e.g., "Bowman dealt 3 Arrow damage, 1 was blocked by Shield").
Responsiveness: Must work on both Desktop and Mobile.
Interactivity: Use smooth transitions for rolling dice and updating health. Final Goal: Provide the complete code in a single block that I can save as an .html file and run in my browser immediately.
