# CMPE 277 Assignment ClapApp
Clap App Android Application

Learning Objective: using Proximity (TYPE_PROXIMITY) sensor, develop mobile clap app. The goal is to simulate clapping using mobile phone and hand.

Clap App Launched Successfully

<img width="394" alt="Screenshot 2024-11-03 at 5 32 40 PM" src="https://github.com/user-attachments/assets/2d8da4a1-fb27-4c49-a685-30d73b390535">

In the onSensorChanged() method, I will check the distance measured by the mProximity sensor with event.values[0]. If the distance is less than or equal to 5, I will display a Toast message saying Clapping Started and play a sound using the MediaPlayer.start() method.

The clap_sound media file is available in the raw directory.

<img width="1440" alt="Screenshot 2024-11-03 at 5 32 29 PM" src="https://github.com/user-attachments/assets/fbf14a10-ec7c-4dde-94e0-b9e5baea9e02">

If the distance is greater than 5, I will display a Toast message saying Clapping Stopped as shown in the below screenshot and mediaPlayer will not play any sound.
<img width="240" alt="Screenshot 2024-11-03 at 5 32 53 PM" src="https://github.com/user-attachments/assets/98c4c58c-4339-4ed0-846e-5df834ecf3ab">




