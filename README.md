# Gestural Resonance
- Name:Ziyi Wang;Ziyu Wang;Qiang Hei
- date:2025.3.11.
## Instructions
- This project applies gesture recognition to sound visualization. Using MediaPipe, hand gestures are detected and processed through CHOP operators, mapping the distance between the thumb and index finger to sound parameters, thereby affecting the audio frequency. Simultaneously, the sound further drives the visual effects. A 3D visual is generated using Render TOP in combination with Geo COMP and Light COMP, while Blur TOP and Lookup TOP are used for post-processing. This creates an interactive loop where gestures influence sound, and sound dynamically controls the visuals.
## Optional blurb
### 1.Installation:Required Software
- TouchDesigner；MediaPipe
### 2.Using the Project
   2.1. Download the entire installation package and open the TouchDesigner file with the ".toe" extension.  
   2.2. Configure the MediaPipe camera according to your setup.  
   2.3. Display the rightmost "bg" node and observe the sound visualization effect in the background.  
   2.4. Test the sound variation using hand distance.  
**Note:** If the "mediapipe" and "Bell4 Rrough Mastered.mp3" nodes do not load after opening the .toe file, you need to manually import these two files from the installation package.
## Acknowledgements (references, links, inspirations, etc)
MediaPipe for hand tracking technology

TouchDesigner community and official documentation
