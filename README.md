# chamber-control-for-klipper

### Installation
```
cd ~
git clone https://github.com/Stephan3/chamber-control-for-klipper.git
ln -s ~/chamber-control-for-klipper/chamber.py ~/klipper/klippy/extras/chamber.py
```

### example config:
```
[chamber]
#	heating(chamberheater) or cooling (fan)
control_mode: cooling
sensor_type: NTC 100K beta 3950
sensor_pin: z:P0.23
pin: z:P2.4
max_temp: 80
min_temp: 10
max_delta: 1
```
