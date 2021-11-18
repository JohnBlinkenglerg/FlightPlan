from djitellopy import Tello
from time import sleep

tello = Tello()
tello.connect()
sleep(2)
tello.takeoff()
sleep(2)


tello.move_up(102)
sleep(0.5)

tello.move_forward(152)
sleep(0.5)

tello.rotate_clockwise(90)
sleep(0.5)

tello.move_forward(182)
sleep(0.5)

tello.rotate_clockwise(90)
sleep(0.5)

tello.move_down(914)
sleep(0.5)

tello.rotate_clockwise(90)
sleep(0.5)

tello.move_forward(91)
sleep(0.5)

tello.rotate_clockwise(90)
sleep(0.5)

tello.move_up(121)
sleep(0.5)

tello.rotate_counter_clockwise(90)
sleep(0.5)

tello.move_forward(182)
sleep(0.5)

tello.land()
tello.end()
