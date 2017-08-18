# Udacity Path Planner (Simple)
Self-Driving Car Engineer Nanodegree Program
   
## Descritpion
A simplified path planner, that utilises the Udacity Path Planning simulator, to navigate a highway populated with traffic. This path planner is simplistic in that it attempts to maintain a constant velocity - if it cannot do this, due to other obstructions, it will consider a lane change. In the event that a lane change is not possible, it will slow down. This path planner has not implemented cost functions for the behaviour comparison, nor is the behaviour layer sending desired velocity and next state to a typical trajectory generator (typical meaning that there are pertubations based on the behaviour request to generate multiple possible paths based on jerk minimisation, and choosing the best path based on minimum cost). The behaviour outcome is considered absolute in its determination, and the speed is governed by considering the maximum allowable acceleration per time step. The outcome of the behaviour layer is passed to a trajectory generation specifically catered to the Udacity Path Planning simulator.

## Project Assessment against Rubric



## Dependencies

* cmake >= 3.5
 * All OSes: [click here for installation instructions](https://cmake.org/install/)
* make >= 4.1
  * Linux: make is installed by default on most Linux distros
  * Mac: [install Xcode command line tools to get make](https://developer.apple.com/xcode/features/)
  * Windows: [Click here for installation instructions](http://gnuwin32.sourceforge.net/packages/make.htm)
* gcc/g++ >= 5.4
  * Linux: gcc / g++ is installed by default on most Linux distros
  * Mac: same deal as make - [install Xcode command line tools]((https://developer.apple.com/xcode/features/)
  * Windows: recommend using [MinGW](http://www.mingw.org/)
* [uWebSockets](https://github.com/uWebSockets/uWebSockets)
  * Run either `install-mac.sh` or `install-ubuntu.sh`.
  * If you install from source, checkout to commit `e94b6e1`, i.e.
    ```
    git clone https://github.com/uWebSockets/uWebSockets 
    cd uWebSockets
    git checkout e94b6e1
    ```


