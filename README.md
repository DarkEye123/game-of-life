# Game of Life in Python

## prerequisites
install ffmpeg if you want have video from the game

<code>
sudo apt install ffmpeg
</code>

Written in python 3


## Usage

### for video output
<code>
python3 life --frames 90 --movfile test.mp4 
</code>

### change interval in miliseconds
<code>
python3 life --interval 20
</code>

### change interpolation
<code>
python3 life --interval 20 --interpolation nearest
</code>

### change grid size
<code>
python3 life --interval 20 --interpolation gaussian --grid-size 32
</code>
