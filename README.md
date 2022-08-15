# chasing_your_tail
Tool for using nearby wireless signals to help determine if you're being followed. 


Modified paths to work on DragonOS Pi64. To install without further modification, make sure you are in 
the /home/ubuntu directory. You'll also need an external wireless card plugged into the Pi that's capable of monitor mode.

```
git clone https://github.com/alphafox02/chasing_your_tail.git
cd chasing_your_tail/kismet_logs
start kismet and select/start your wireless interface from the web interface
open another terminal
cd chasing_your_tail
python3 cyt_gui.py
click Run Chasing Your Tail
```

Released under the MIT License https://opensource.org/licenses/MIT
