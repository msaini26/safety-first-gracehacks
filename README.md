# safety-first-gracehacks

## Inspiration

Walking alone at night on campus with uncertainty is the worst feeling as a student. As the number of CruzAlerts (Safety Alert System organized by the University of California, Santa Cruz) regarding incidents that have made students and faculty feel unsafe increased, we decided to take matters into our own hands. With Safety First, we aim to help students get home safer feeling empowered.

## What it does
We included a updated newsfeed that highlights recent university safety alerts and events. To guide students and faculty back home safely when walking late at night, we build a map with pinpoints on the UCSC campus that are well-lit and popular walking paths. We also developed an empowerment section where individuals can feel mentally stronger through power yoga poses designed to improve confidence through our machine learning pose detection model. Strike a pose with pride!

## How we built it
We built the structure of our webpage using HTML, design using CSS, and functionality using Javascript. We utilized the Google Map API to pinpoint crucial safety spots on campus with lampost icons to indicate popular walking paths and well-lit regions. For the empowerment feature, we utilized TensorFlow.js to develop our machine learning model that takes visual user input to detect poses. We classified our data set based on each pose type and were able to reach 95% accuracy overall.

## Challenges we ran into
Our goal in GraceHacks was to stretch our learning through learning new technologies and expanding our skillset overall. This was our first time utilizing the Google Maps API to drop pinpoints at frequently used paths and well-lit regions. We ran into issues trying to highlight each cluster of lights (red: more frequent path and well-light; blue: less frequent and possible light) respectively. A solution we found was grouping pinpoints based on their relative location to highlight more frequent walking regions with good lighting. Also, in our first training session for our machine learning pose detection model, we did not include enough data points to account for edge cases. For example, this might include someone doing the pose from far away or closer towards the camera. After spending many hours training and testing our model, we were able to achieve an approximate of 96% accuracy.


## Accomplishments that we're proud of
Starting off with a steep learning curve, we are proud of the final implementation of our safety map and the empowerment feature that we successfully embedded in our webpage; the process was difficult yet rewarding. Although modifying minor design details and image cohesion was tedious, we are proud of what we achieved! 

## What we learned
Parna learned how to start an HTML project from scratch. Managing time properly and breaking down a large project into smaller parts is also something that she learned is beneficial when beginning to hack. Embedding APIs and other software involved a learning curve but it helped make our project more versatile. This was Mansi's first time learning how to integrate the Google Maps API by dropping pinpoints on crucial locations and labeling them accordingly based on their location. She learned the importance of defining a clear project scope and defining its respective components ahead of time before diving straight into the development process. 


## What's next for Safety First
We want to include a discussion forum on our webpage to encourage further community building and discussion amongst UCSC student and staff. Providing additional safety havens across campus is also a goal so having a section on the webpage where students can talk about their experiences would help students feel less isolated. 
