# AudioRecorder
It's use audio recording functionality with mobile proximity sensor to route the speakers output in mobile. It has day/night toggle theming behavior for better user experience.

Covering Following Points : 

1. Runtime Permission Handling To Record Functionality
   -> Ref : RunTimePermission
2. Record Audio : Capture Audio 
3. Audio Playback : Plays recorded audio instantly
4. Raise-to-Ear : Loudspeaker to Earpiece
   -> Ref : RaiseToEar util class to route switch between speakers
5. Light/Dark Theme : Smart toggle accordingly to daily time.
6. Background Audio Activity : Pause/Resume other app's activity for aduio
   -> Ref : AudioFocus util class for manage logic
7. Clean Architecture Structure + MVVM Pattern

