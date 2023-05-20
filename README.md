# Lichess custom theme

Lichess themes have always looked very low contrast to me

This tampermonkey script
- Adds two buttons that can be used to change the board colours in realtime
- Updates the preview of the theme in the dasher

Defaults to the Blue theme on chess.com

# Example
![image](https://github.com/prateeksaini01/lichess-custom-theme/assets/31561310/66cd35a3-cc63-451b-a6fd-37b232868d56)


# Problems
- The buttons are added on the navbar alongside other buttons, they should ideally be in the dasher
- Overrides the blue3 theme (because I hate it the most). I don't see a way to add a new theme because there's an API call to lichess that saves the user's theme preference. I assume it only accepts predefined values.
-  
