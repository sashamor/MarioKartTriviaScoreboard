# Mario Kart Trivia Dashboard

## What it is
A trivia scoreboard, themed around mario kart.

## Libraries
The scoreboard uses the wonderful [PyGame](http://www.pygame.org/) library, built on [SDL](http://www.libsdl.org/).

## How to use it

### Starting the scoreboard

Run the scoreboard itself with:

```bash
$ ./scoreboard.py
```
or by double-clicking the `scoreboard.py` script.

While its running, you can modify the `scores.txt` file, then hit the **Refresh scores** button (see table below) to update the scoreboard.

### Editing the scores

Edit scores.txt with the scores for each team.

- You can have up to 8 teams
- The first column represents the *team number*
- The second column represents the image file to display (check `images/` for the names)
- The 3rd to nth columns represent the scores
- You can enter positive or negative space-separated numbers
- You can have as many numbers as you'd like

#### Example scores.txt file

```
1 mario 0 18 11 -5 3 4
2 toad 0 22 21 10 -10 -5 3 
3 peach 0 17 20 -5 2 2 2 3 3 1 
4 luigi 0 16 23 10 -5 5 3 4
5 yoshi 0 15 21 4 4 4
6 donkey_kong 0 15 1
7 bowser 0 20 20 -5
```

## Customising it

You can modify the images in the `images/` directory as much as you want to customise the look of the scoreboard!

You can also add your own custom songs to the `sfx/` directory, and the scoreboard will automatically load (and play) them when told to.
    
## Keybindings
    
    +-------------------------------+----------------+
    | Refresh scores                | F12            |
    | Hit/reset item block          | <team number>  |
    | Shake/unshake team number     | F<team number> |
    | Shake all team numbers        | F11            |
    | Stop shaking all team numbers | F10            |
    | Play music                    | P              |
    | Stop music                    | S              |
    | Play starting round music     | Enter or A     |
    | Play ending round music       | F              |
    | Go to high score screen       | L              |
    | Increase scores displayed     | Up arrow       |
    | Decrease scores displayed     | Down arrow     |
    +-------------------------------+----------------+

## Future features

- Ability to customise the keybindings in a configuration file
- Ability to re-layout the images (e.g. if the image sizes change) in a configuration file

## Credits

&copy; 2011-12 Sasha Bermeister