# Lift-Simulation

Create a web app where you can simulate lift mechanics

Run the program:
git clone
cd Lift-Simulation-emberjs
npm install
ember serve

- After server starts open any brower and  write URL localhost:4200
- Execution of program starts from home.hbs
- We have separate components defined for  lift, Floor, game-board.
- Initially all lifts are grounded, when any button is pressed, the floor number and the direction is passed to buttonpressed and it starts to analyse lift. Analysing lift means finding the lift which is closest and then moving the particular lift to the same floor with delicate animation.
