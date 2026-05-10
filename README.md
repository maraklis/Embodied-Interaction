# The Role of Movement and Design in Character Perception
This project explores how people emotionally connect with digital characters through **visual appearance and movement**. One character was designed to express five emotions: **joy, sadness, anger, disgust, and fear**, through changes in colour, shape, and motion.
Using theories of **embodied cognition** and **Laban Movement Analysis (LMA)**, the project investigates whether people rely more on how a character looks or how it moves, especially when those elements conflict. The study also explores how embodiment changes emotional perception when participants physically become the character through movement.
The project combines character design, motion capture, embodied interaction, animation, and experimental testing to examine how movement influences perceived personality in digital characters.
As a final outcome, the research was translated into a prototype game called **"*Before the Name*"**, exploring how emotional embodiment and movement-based interaction could support emotional awareness and self-reflection.

## Research question
How does the conflict between visual appearance and movement cues influence perceived personality, and does this influence change after embodiment?

## Process
### Research

### Character Design
<img width="5026" height="3431" alt="IMG_6035" src="https://github.com/user-attachments/assets/4cf43722-fc96-45ce-8038-9eff06022ad0" />

A single character was designed in six emotional states: neutral, joy, sadness, anger, disgust, and fear. Each state used different colours and shapes inspired by emotional association research.
- **Joy** used yellow tones and rounded circular forms.
- **Sadness** used blue tones and soft drooping shapes.
- **Anger** used red colours and sharp square forms.
- **Disgust** used green tones with irregular spiky edges.
- **Fear** used purple tones and unstable asymmetrical forms. \
The aim was to create visual identities that could immediately communicate emotional personality before movement was introduced.

### Character Modelling and Rigging
<img width="1322" height="885" alt="Untitled-2" src="https://github.com/user-attachments/assets/ada9de7b-47d6-4b40-a32e-68ef478e5c98" />


The models were created in Blender and imported into Mixamo for rigging. The rigs were later cleaned and adjusted manually inside Unreal Engine to prepare them for animation retargeting and motion capture integration.

### Motion Capture with Rokoko
<img width="1856" height="592" alt="Untitled-10" src="https://github.com/user-attachments/assets/48b4cdd6-e07e-4cd8-9652-6ebb26688468" />


To express emotions physically, motion capture performances were recorded using Rokoko Vision and Rokoko suits. Ten movement sequences were captured and exported, each representing different emotional qualities connected to the selected emotions.

### Testing Preparation in Unreal Engine
<img width="1670" height="903" alt="Screenshot 2026-05-10 at 19 33 18" src="https://github.com/user-attachments/assets/14cceac0-3e30-4533-b6fe-96619f6011cd" />


The testing environment and interaction flow were developed in Unreal Engine.
The character skeleton was retargeted to Unreal Engine’s default mannequin skeleton. The captured animations were imported and retargeted to the final character models. Different combinations of movement and visual appearance were prepared to either emotionally match or intentionally conflict.

<img width="2231" height="1073" alt="Untitled-4" src="https://github.com/user-attachments/assets/12d48745-8312-45f8-ae5f-d7c237a32f86" />


This setup allowed the project to examine whether participants prioritised movement or visual appearance when interpreting personality and emotion.

### User Testing and Embodied Interaction
The study involved eight participants and combined observation with embodied interaction using Rokoko motion capture and Unreal Engine.

#### Stage One: Observation
Participants first observed animated characters expressing emotions. Some combinations matched emotionally, while others intentionally conflicted. \
After each presentation, participants selected which emotion they believed the character expressed most strongly: 
- Joy
- Sadness
- Anger
- Disgust
- Fear

#### Stage Two: Embodiment
In the second stage, participants physically embodied the character themselves. \
Using Rokoko motion capture, participants performed emotional movement that was applied directly to the digital character in real time. After each embodiment session, participants described their movement using simplified Laban Movement Analysis terminology. \
They then repeated the emotional perception task and rated how strongly their own movement influenced how the character emotionally felt.

#### Test
Test link: https://docs.google.com/forms/d/e/1FAIpQLSe_dhthRZ6LKWrkA_9eZqBAnmjcOnmwupbYBL3ktX_E4JAzLw/viewform?pli=1&pli=1&pli=1 .
  
### Test Outcomes
Main insights
<img width="1536" height="768" alt="Untitled-5" src="https://github.com/user-attachments/assets/6d03892d-811e-48fc-8e18-c11c527c3d57" />


The findings showed a clear shift after embodiment. \
During the observation stage, when movement and visual appearance conflicted, 62.5% of participants relied mainly on visual appearance to identify the character’s emotional personality, while 37.5% prioritised movement. \
After embodying the character themselves, this changed significantly. 87.5% of participants prioritised movement over visual appearance, while only 12.5% continued relying mainly on visual cues. \
Additionally, all participants reported that their own movement influenced how the character emotionally felt to them, with an average rating of 4 out of 5. \
The findings suggest that embodiment strengthens the emotional importance of movement and can fundamentally shift how personality and emotion are perceived in digital characters.

### Framework Connecting Laban Movement Analysis to Emotions
<img width="1232" height="528" alt="Untitled-8" src="https://github.com/user-attachments/assets/72967a7f-55e4-4208-b7fd-d4967618b96b" />
<img width="2942" height="656" alt="Untitled-9" src="https://github.com/user-attachments/assets/3b426f52-afc6-423f-91bb-caacb207446c" />

Based on participant responses and movement analysis, the project developed an experimental framework connecting emotions to specific Laban Movement Analysis qualities.

### Before the Name (Prototype)

#### Idea and Purpose
As a final outcome, the research was translated into an interactive prototype called "*Before the Name*". \
The prototype explores how emotional embodiment could be applied within a real-life emotional awareness experience. Instead of simply identifying emotions cognitively, the experience encourages players to physically feel, visualise, and embody them. \
The experience guides the player through: 
- noticing bodily sensations,
- observing emotional changes in the body,
- imagining emotions as colours, shapes, and movement,
- and physically embodying them. 
The project was inspired by the idea that emotions are often stored physically within the body. By becoming aware of how emotions feel and move internally, players can begin building stronger emotional awareness and emotional intelligence. \
The experience also reframes emotions not as problems to remove, but as companions that communicate needs, boundaries, fears, and desires.

#### Storyboarding and Scripting
<img width="3538" height="2396" alt="Untitled-6-2" src="https://github.com/user-attachments/assets/00ba555b-3c4b-4bb8-bf2f-2e67d47c5071" />

#### Animation
<img width="2905" height="1712" alt="Untitled-7" src="https://github.com/user-attachments/assets/86e0c13c-c883-4b18-9422-adbf1003a181" />


2D frame-by-frame animations were created using Procreate and edited in Premiere Pro. Organic animated transitions were used to visualise emotional transformation and internal emotional states. 

Voice narration was recorded using a phone microphone, while background music and sound effects from Freesound were used to create an immersive atmosphere. 
The visual style intentionally used soft movement, abstract forms, and minimal environments to keep the focus on emotional experience and embodiment.

#### Future Potential
The project opens possibilities for using embodied interaction and emotional visualisation within:
- therapeutic settings,
- emotional education,
- mindfulness practices,
- and interactive storytelling experiences.
With further research and collaboration with clinical professionals, the prototype could evolve into a more advanced interactive system supporting emotional awareness, emotional regulation, and self-reflection through movement and embodiment. \
The project also demonstrates how movement-based design can create stronger emotional connection and empathy within digital experiences, games, and virtual characters.

#### Watch the Gameplay
Gameplay video: https://youtu.be/-1qtKx0DC3o



