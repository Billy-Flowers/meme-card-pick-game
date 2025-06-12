# Continuous Deployment using AWS Code Pipeline and S3

Code for the game is hosted on GitHub.  We create an S3 bucket for static website hosting, then create a continuous deployment pipeline (using AWS Code Pipeline) to automatically deploy the code whenever changes are commited to the GitHub repository.

## The Deployment Environment
The code will be deployed and hosted in an S3 bucket.

## The Deployment Pipeline
The pipeline is created using AWS Code Pipeline.  The pipeline pulls the code from GitHub, and deploys it to S3 whenever a change is detected in the code.

## Cost
All services used are eligible for the [AWS Free Tier](https://aws.amazon.com/free/).  However, charges may incur at some point so it's recommended that you shut down resources after completing this project.

## The Game
A simple memory matching game.  The user picks two cards at a time (images of memes) to try and match them.  If there's a match, the cards disappear from the board.  If there's no match, the cards are flipped back to their blank side so the user can try again.

![Image](https://github.com/user-attachments/assets/9c0eaa1b-e98b-4a6f-a3d2-b3ea5ef14ec2)

The game is made using HTML, CSS and JavaScript.

![Image](https://github.com/user-attachments/assets/3612449b-9af1-4f0b-8be7-75b02c344db4)

## New Updates
- added an audio for whenever a card is selected
- new meme cards
- improved JavaScript code in readability and functionality
