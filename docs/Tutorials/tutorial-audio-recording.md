# Tutorial: Audio Recording

This tutorial describes how to record audio and export it to a .WAV or .MP3 file using Adobe Audition software.

## Materials Needed
@TODO: Take pictures that are square

<div class="grid cards" markdown>

- **Your Library Card**
- **iMac Station**
- **Sony Headphones**
- **Blue Yeti Microphone**
</div>

## Prerequisites
- [Tutorial: iMac Login](tutorial-iMac-login.md)

## Hardware Setup

There are two ways to set up the audio recording hardware:

- **With Mic Monitoring:** You will be able to hear what the microphone is picking up in real-time through your headphones.
- **Without Mic Monitoring:** You won't be able to hear what the microphone is picking up while you're recording, but the recording software will still pick it up and you will be able to listen to it after you are finished recording.

Please choose the appropriate monitoring setup for your project and follow the hardware setup diagram accordingly.

!!! note

    The arrowheads represent a plug being plugged into a receptacle.

@TODO: Verify Keyboard/Mouse configuration

=== "Without Mic Monitoring"

    ```mermaid
    graph LR
      Keyboard --> Hub[USB Hub]
      Mouse --> Hub[USB Hub]
      Mic[Blue Yeti Microphone] --> Hub[USB Hub]
      Hub[USB Hub] --> iMac
      Headphones[Sony Headphones] --> iMac
    ```

=== "With Mic Monitoring"

    ```mermaid
    graph LR
      Keyboard --> Hub[USB Hub]
      Mouse --> Hub[USB Hub]
      Mic[Blue Yeti Microphone] --> Hub[USB Hub]
      Hub[USB Hub] --> iMac
      Headphones[Sony Headphones] --> Mic[Blue Yeti Microphone]
    ```

## Microphone Setup

Once the hardware has been set up, ensure the red light labeled **:fontawesome-solid-microphone: Mute** is solidly red and not blinking. If it is blinking, press the button so that it remains solid. If you don't see a red light, then perhaps it wasn't plugged in correctly to begin with.

Please note these knobs:

- **:fontawesome-solid-headphones: Volume** on the front: This control is only relevant if set up with mic monitoring. It increases and decreases the volume of the headphones.
- **Gain** on the back: This control amplifies the mic input volume. If the recording is too quiet or too loud, try adjusting this knob. It is best practice to keep gain knob as low as possible and turn the mic input volume to 100% as described in [iMac System Settings section](#imac-system-settings).
- **Pattern** on the back: This control changes the microphone's configuration according to the *Patterns Chart* in the next section.

### Patterns Chart
| Pattern                  | Symbol                                                                        |Description                                                                                                                                                                                                                        |
| ------------------------ | ----------------------------------------------------------------------------- |---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Stereo Mode**          | ![Symbol for stereo mode](../assets/images/mic-stereo.webp)                   | Uses both the left and right channels to capture a wide, realistic sound image. It is perfect for recording acoustic guitar or choir.                                                                                             |
| **Omnidirectional Mode** | ![Symbol for omnidirectional mode](../assets/images/mic-omnidirectional.webp) | Well-suited to podcasts, vocal performances, voice-overs and instruments. Cardioid mode records sound sources that are directly in front of the microphone, delivering rich, full-bodied sound.                                   |
| **Cardioid Mode**        | ![Symbol for cardioid mode](../assets/images/mic-cardioid.webp)               | Picks up sound equally from all around the mic. It's best used in situations when you want to capture the ambience of "being there" — like a live recording of a band's performance, a multi-person podcast or a conference call. |
| **Bidirectional Mode**   | ![Symbol for bidirectional mode](../assets/images/mic-bidirectional.webp)     | Records from both the front and the rear of the microphone — ideal for recording a duet or a two-person interview.                                                                                                                |

## iMac System Settings
