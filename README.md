# Continuous Deployment using AWS Code Pipeline and S3

Code for the game is hosted on GitHub.  We create an S3 bucket for static website hosting, then create a continuous deployment pipeline (using AWS Code Pipeline) to automatically deploy the code whenever changes are commited to the GitHub repository.

## The Game
A simple memory matching game.  The user picks two cards at a time (images of memes) to try and match them.  If there's a match, the cards disappear from the board.  If there's no match, the cards are flipped back to their blank side so the user can try again.

The game is made using HTML, CSS and JavaScript.


## The Deployment Environment
The code will be deployed and hosted in an S3 bucket.

## The Deployment Pipeline
The pipeline is created using AWS Code Pipeline.  The pipeline pulls the code from GitHub, and deploys it to S3 whenever a change is detected in the code.

## Cost
All services used are eligible for the [AWS Free Tier](https://aws.amazon.com/free/).  However, charges may incur at some point so it's recommended that you shut down resources after completing this project.

Changes
- added an audio for whenever a card is selected
- new meme cards
- improved JavaScript code in readability and functionality
