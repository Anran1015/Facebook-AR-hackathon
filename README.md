# Facebook-AR-hackathon
my ar project for Facebook AR hackathon

## Inspiration
I was inspired by the idea of time traveling, and I also find that a lot of people like to bring their photos to the places where it was created to reminisce people and things happened in their life.

## What it does
In the filter, users will first see a floating orb telling them that they have a memory to look back at, and once they tap it, they are able to reveal this memory piece: a post that they created previously, and if they click on it, the picture starts to move as if the memory piece just come alive, as well as audio effect along with the video. Users could choose to go back to the place where they created this post, and create a new story where the old content is on top of the real world layer. The world idea of this filter is to encourage users create new content by leveraging existing posts and support their reminiscing behavior.

## How I built it
The picture showing in the filter is supposed to be pulled from users' old posts. The filter effect I created is a demonstration of my concept, thus I am using my own pictures as a placeholder rather than attempting to get access to people's data. I created most of the visual effect in AE, and convert the video to animation sprite. All the interaction in the project is created in the patch editor.

## Challenges I ran into
As a designer, I don't have solid coding skill, so I tried to make everything in the patch editor which is something quite new to me. Since I don't know how to write code to grab assets hosted somewhere else, I have to include all the assets (2 animation sequences and 1 audio file) in the project which makes the file size very big. It took me quite a long time to reduce the size to 4mb and maintain a decent visual quality at the same time, for example: try to reduce the numbers of frames, resize the picture, convert the picture format. etc.

## Accomplishments that I'm proud of
I am proud that I made this in 2 days as a complete newbie to spark AR, and I also believe that the concept I proposed here is solid and can be an interesting and impactful feature for Facebook: align with the time well-spent strategy and encourage content creation.

## What I learned
Spark AR

## What's next for Revisit Memory
The idea of this project comes from the graduate project I am currently working on as a design new grads. I am building a more refined version in unity with better visual effects and more features (geo-location based, and note writing). I think spark AR helps me to quickly create a MVP and helps me to demonstrate my concept.
