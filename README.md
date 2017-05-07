# ConnectFour

#### A simple ConnectFour Game in JS using PIXI Library
--

## Have a try !

* Clone repo: ``git clone https://github.com/Shrakka/ConnectFour.git``
* Go to repo: ``cd ~/ConnectFour``
* Start a local server (on port 8000 for example): ``http-server -p 8000``. You will need npm http-server: ``npm install http-server -g`` if not installed yet.
* Go to your favorite web browser: ``http://localhost:8000``
* Enjoy !

## How it works ? 

* There is two grids: FIELD (the model grid) and FIELDVIEW (the viewgrid) which are global variables.
* Setup function produce the FIELDVIEW: it loads overlapping sprites (emptySprite, yellowSprite, redSprite) on each tile. 
* LoopGame function makes the link between model and view. 
* Code is self documented to help you understand the model: I used a minimax algorithm.
* Tokens were made on GIMP. 

## Do not hesitate to report bugs, thank you!

> Send me an email: enzotesta@hotmail.fr
