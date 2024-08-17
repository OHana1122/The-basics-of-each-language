# Traffic Light and Car Animation

信号機と車の3DCGアニメーション version1.0.0

**Creation Date:** 2023/2 
**Programming Language:** C++  
**Library:** OpenGL  

## Demo

https://github.com/user-attachments/assets/3e090116-d265-4027-ae54-d73e91ef75c5


## Overview
### Usage
- **右クリックk:**歩行者側の信号の色が変化
- **左クリック:** 信号に応じて車が進む

### Point
- 車側ではなく歩行者側の信号を描画し、車と信号が同時に見えるように
- 車の挙動を細かく設定:
  - 横断歩道側の信号が赤のとき、車側は青のため走行を継続
  - 横断歩道側の信号が青のとき、車側が赤なので、車は停止線付近で速度を落として停止線手前で停止
  - 信号から離れていたり、停止線を超えている場合、車は信号が変わっても走行を続ける