# LINGI1131 Players
This repository has for aim to store the compiled (.ozf) version of players created by students during the LINGI1131 bomberman project.

This repository is the initiative of **Brieuc de Voghel** and **Nicolas van de Walle**.

## Players' description
| Group | Filename            | Description           |
|-------|---------------------|-----------------------|
| 000   | Player000bomber.ozf | Default random player |
|       |                     |                       |

## How to use ?
Clone/Download the **content** of the repository into your project.

**Warning !** The players must be in the same directory as your other compiled files (``Input.ozf``, ``PlayerManager.ozf``...). Don't place the players in a subdirectory.

The ``.gitignore`` file of this project has been thought such that it ignores every file which does not follow the following pattern: ``Player[0-9]*.ozf`` (Player followed by at least one digit followed by anything .ozf). It won't affect your project.

## How to contribute ?
1. Compile your **working** player into a file having the following name:
   ``Player[GROUP NUMBER]-[PLAYER ID]bomber.ozf`` 

   [PLAYER ID] identifies your different players
2. Add your player and a description of its behavior in the Players' description table of the ``readme``
3. Make a pull request


