<!-- PROJECT LOGO -->
<br />
<h1 align="center">slash n bash</h1>

  <p align="center">
    <h4>
      An auto-updating database of upcoming NFT projects with their Twitter engagement analytics.
    A computer vision controlled fighting game with hit priority, combo, and timing mechanics, full animation, and playable levels.
    </h4>
    <br />
  </p>
</div>

<!-- ABOUT THE PROJECT -->
## About The Project

[![slash n bash video demo][video-demo]]
"slash n bash" is a side-scrolling retro themed fighting game controlled by real life body movement.

The project was ideated, designed, and implemented in less than 24 hours for the Carnegie Mellon
Hack112 challenge. The project won 1st place out of 200 participants.

### Features
- Pose estimation controlled action.
- 9 playable and distinct levels with increasing difficult enemies.
- Smooth level transitioning with parallax background and walk animations.
- Fully animated blocks, attacks, hits, walks, idles, deaths, and more.
- Balanced and playtested fighting mechanics with hit priority, block counterdamage to discourage
move spam, and designed for an emphasis on timing/rhythm.
- Full sound effects and background music.
- Levels designed to progressively teach user the game mechanics.
- Instructions, start, win, and death splash screens.

### Design principles
1. Make the user truly feel like a powerful sword wielding fighter.
2. Mirror virtual game to player real life pose as accurately as possible.
3. Provide strong enough challenge where level completion feels like an accomplishment.

### Gameplay Instructions
- Move hands above head to perform a "down slash" attack
[![down slash][down-slash]]
- Move hands from right to left to perform a slash attack
[![spin][spin]]
- Turn back to camera to block
[![block][block]]

### Built With
* [![OpenCV][opencv]][opencv-url]
* [![MediaPipe][mediapipe]][mediapipe-url]
* [![Py Auto GUI][pyautogui]][pyautogui-url]
* [![PyGame][pygame]][pygame-url]
* [![Tkinter][tkinter]][tkiner-url]

## Local Copy
You may run this project locally by following these steps:

1. Clone the repo
   ```sh
   git clone https://github.com/KyleleeSea/slashnbash
   ```
2. Create, set up new virtual environment
```
python -m venv myvenv #create environment
```

3. Install external modules 
1. [OpenCV](https://docs.opencv.org/4.x/d6/d00/tutorial_py_root.html): enables image processing and webcam access
2. [mediapipe](https://google.github.io/mediapipe/solutions/solutions.html): enables pose estimation model
3. [pyautogui](https://pyautogui.readthedocs.io/en/latest/): allows python script to access and controll keyboard
```
pip install opencv-python
pip install mediapipe
pip install pyautogui
```

4. Make sure tikinter is downloaded from cmu_112_graphics.py on the [CMU 15-112 website](https://www.cs.cmu.edu/~112/notes/notes-graphics.html#installingModules).
```
import sys
print(f"sudo '{sys.executable}' -m pip install pillow")
print(f"sudo '{sys.executable}' -m pip install requests")
```
5. Run run.py
```
python3 run.py
```
   
<!-- CONTACT -->
## Contact

Twitter - [@KyleleeSea](https://twitter.com/KyleleeSea)

Project Link: [https://github.com/KyleleeSea/slashnbash](https://github.com/KyleleeSea/slashnbash)

## Contributors
- [Emily Li](https://github.com/emilyjiayaoli/slash_n_bash/commits?author=emilyjiayaoli)
- [Stephen Mao](https://github.com/stephenlearnscode)
- [Evelyn Chen](https://github.com/evelynnchen-cmu)

<!-- MARKDOWN LINKS & IMAGES -->
[video-demo]: https://imgur.com/a/U7V9bVQ
[down-slash]: https://imgur.com/a/3zQBGve
[block]: https://imgur.com/a/3zQBGve
[spin]: https://imgur.com/a/r1PwSq9
[opencv]: https://img.shields.io/badge/OpenCV-fe2a44?style=for-the-badge&logo=opencv&logoColor=ffffff
[opencv-url]: https://opencv.org/
[mediapipe]: https://img.shields.io/badge/Mediapipe-04ABC1?style=for-the-badge&logo=mediapipe&logoColor=ffffff
[mediapipe-url]: https://mediapipe.dev/ 
[tkinter]: https://img.shields.io/badge/Tkinter-FFFFCC?style=for-the-badge&logo=tkinter&logoColor=ffffff
[tkinter-url]: https://docs.python.org/3/library/tkinter.html
[pyautogui]: https://img.shields.io/badge/pyautogui-464646?style=for-the-badge&logo=pyautogui&logoColor=ffffff
[pyautogui-url]: https://pypi.org/project/PyAutoGUI/
[pygame]: https://img.shields.io/badge/pygame-6AEE28?style=for-the-badge&logo=pygame&logoColor=ffffff
[pygame-url]: https://www.pygame.org/docs/
