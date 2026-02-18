cription

`ChessBox` is a multiplayer chess game with a twist: the board is shrouded in a **fog of war**, where players select their pieces in a **purchase phase** before the first move to assemble their custom army. Hunt down and kill the opponent's king to win! A **post-match replay** is provided so players can review their game without fog to see the full board from the start.

# Features

### ★ Find a match

- A simple **server browser** for hosting and discovering LAN games. 
- Direct peer-to-peer connection over the internet is also supported by entering an IP address.

<figure>
<img src="" alt="A gif previewing the main menu and server browser" width="800" height="400"/>
</figure>

### ★ Build your army before the first move

- Before the game begins, each player enters a **purchase phase** with 21 pawns worth of currency.
- The **King** is required and is always **free**. All other pieces cost their traditional values in pawns:
  - **Pawn = 1**
  - **Knight = 3**
  - **Bishop = 3**
  - **Rook = 5**
  - **Queen = 9**

<figure>
<img src="" alt="A gif previewing the purchase phase" width="800" height="400"/>
</figure>

### ★ Fog of war based on piece positioning

- Tiles are hidden from a player unless within reach of their pieces.
- Scouting, baits, and discovered threats make information as valuable as the pieces on the board.

<figure>
<img src="" alt="A gif previewing fog of war" width="800" height="400"/>
</figure>

### ★ Post-match replay

- After the game ends, players can watch a **replay of the board** with fog removed.

<figure>
<img src="" alt="A gif previewing the replay feature" width="800" height="400"/>
</figure>

# Notes

`ChessBox` is developed using **Unreal Engine** almost entirely with blueprints. The engine version used during development was 5.4. Lastly, the game has only been tested for Windows.
