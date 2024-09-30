# LLM Output Comparison

## Prompt: 

Your task is to create a 30 second engaging and educational tiktok script based on the following sentence:

Spaceships are the future of human travel.

Expand on this sentence to create an interesting and educational script that most people might not know about.
The tiktok should incorporate an engaging story or example related to the sentence.
Do not include any emojis or hashtags in the script.
The script should be only spoken text, no extra text like [Cut] or [Music].
The script should sound passionate, excited, and happy.

Script:

### Model Comparisons

#### Model 1: Llama-3.2-1B_openvino

##### Chat Mode
Time: 15.7 seconds

Output:
SpaceShips are
    ___________for Humans!

##### Completion Mode
Time: 38.9 seconds

Output:
Spaceships are the future of human travel.
I'm excited to see what the future holds for us.
We're going to be able to travel to other planets and explore new worlds.
We're going to be able to explore the universe and discover new life forms.
We're going to be able to travel to other planets and explore new worlds.
We're going to be able to explore the universe and discover new life forms.
We're going to be able to travel to other planets and explore new worlds.
We're going to be able to explore the universe and discover new life forms.
...

As you can see, the output is useless.

#### Model 2: Llama-3.2-1B_openvino_INT8

##### Chat Mode

Time: 13.9 seconds

Output:
I have decided to go where others cannot fly
and become part of my own journey

In space! I'm feeling so free 
I can feel all things when travelling high up into the heavens above.

##### Completion Mode

Time: 38.6 seconds

Output:
Spaceships are the future of human travel.
I'm excited to see what the future holds for us.
We're going to be able to travel to other planets and explore new worlds.
We're going to be able to explore the universe and discover new life forms.
We're going to be able to travel to other planets and explore new worlds.

#### Model 3: Llama-3.2-1B-instruct_openvino_INT8

##### Chat Mode

Time: 35.3 seconds

Output:
"Imagine you're an astronaut who has just arrived at Mars. As you step out of your spaceship, take in the breathtaking view before you - the rust-red landscape stretches as far as the eye can see. But have you ever stopped to think how humanity got here? 

Did you know that scientists discovered water ice at mid-latitudes above Europe over a million years ago? They thought it would never reach there by land! It took thousands of miles across Africa's Sahara Desert!

And what if I told you that we've already explored parts of our solar system with robotic spacecraft?

We launched Curiosity Rover onto Mars four months after landing in August last year. Since then, its amazing discoveries have rewritten history books for science!"

This script tells a captivating narrative while educating viewers on some fascinating facts that they may not know about spaceships transporting humans beyond Earth.


Additional tips:
- Use natural pauses and emphasis areas to keep engagement high.
- Maintain conversation flow throughout without jumping abruptly between ideas. This will build trust among the audience and make them more likely to engage further.
- Add slight inflections when discussing key points (e.g., excitement, details) so listeners can differentiate voices during their own interpretation.

##### Completion Mode

Time: 12.1 seconds

Output:
"Imagine a world where humanity has finally reached the stars, and we're not just talking about any old spacecraft, but the most advanced, cutting-edge, and sustainable vessels that are changing the game. Spaceships are not just a luxury, they're a necessity. They're the key to unlocking new frontiers, new discoveries, and new possibilities for humanity. But did you know that the first spaceship was actually a hot air balloon? Yes, you heard that right! In 1783, French inventor Montgolfier created the first successful hot air balloon, which carried a group of 20 people to the skies. It was a groundbreaking achievement that paved the way for the development of modern space travel. Fast forward to today, and we have reusable rockets, advanced propulsion systems, and even private space companies like SpaceX and Blue Origin pushing the boundaries of what's possible. But what's even more exciting is that we're not just talking about the technology, we're talking about the people, the communities, and the cultures that are being shaped by space exploration. From the astronauts who are pushing the limits of human endurance to the scientists who are unlocking the secrets of the universe, space travel is not just a dream, it's a reality that's changing our world. So let's get ready to blast off into the unknown, and explore the infinite possibilities that await us in the cosmos!"


#### Model 4: Llama-3.2-1B-instruct_openvino_INT8

##### Chat Mode

Time: 22.9 seconds

Output:
"Imagine living on Mars one day - it's already happening. In fact, NASA has been sending astronauts all over space for decades. But what you may not know is how they're doing exactly as planned."

"But did you know they have to wait years between launches? Because each launch costs millions dollars per seat! That means every dollar going towards building new spaceships and spacecraft is contributing towards making humanity multiplanetary." 

"You see, our planet Earth was facing extinction from asteroids and other dangers, but now we can't let another disaster happen while trying to explore the cosmos with just two small planets nearby: earth and mars." "It could get ugly very fast if there aren't enough resources available elsewhere so humans have made agreements such as the Artemis Program which would help us acquire more resources before being able to establish itself officially"

##### Completion Mode

Time: 12.3 seconds

Output:
"Imagine a world where humanity has finally reached the stars, and we're not just talking about any old spacecraft, but the most advanced, cutting-edge, and sustainable vessels that are changing the game. Spaceships are not just a luxury, they're a necessity. They're the key to unlocking new frontiers, new discoveries, and new possibilities for humanity. But did you know that the first spaceship was actually a hot air balloon? Yes, you heard that right! In 1783, French inventor Montgolfier created the first successful hot air balloon, which carried a group of 20 people to the skies. It was a groundbreaking achievement that paved the way for the development of modern space travel. Fast forward to today, and we have reusable rockets, advanced propulsion systems, and even private space companies like SpaceX and Blue Origin pushing the boundaries of what's possible. But what's even more exciting is that we're not just talking about the technology, we're talking about the people, the communities, and the cultures that are being shaped by space exploration. From the astronauts who are pushing the limits of human endurance to the scientists who are unlocking the secrets of the universe, space travel is not just a dream, it's a reality that's changing our world. So let's get ready to blast off into the unknown, and explore the infinite possibilities that await us in the cosmos!"


