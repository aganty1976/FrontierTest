# FrontierTest
FrontierTest - This is just a console app showing the co-ordinates and facing after each move, there is no UI

Pre-Requisites .Netcore 6.0 and preferably VS 2022 to open and run the solution

Download the code from the github location provided or can be opened in visual studio directly from the location

Download the complete zip file of the code.

Run the Console Application and enter the operations below PLAY or the test moves created.

PLAY - Interactive console application with user inputs in the console and prints out the exact co-ordinates and the facing the Robot.

T1 - Test scenario provided in document

      STEPS implemented for this test case
      
            place(0, 0, NORTH)
            move()
            place(0, 1, NORTH)
            left()
            place(1, 2, EAST)
            move()
            move()
            left()
            move()

T2 - Test Scenario for displacing the robot cannot move beyond the grid in the NORTH

      STEPS implemented for this test case
      
            placeRobot(0, 0, "NORTH");
            Report();
            Move();
            Report();
            Move();
            Report();
            Move();
            Report();
            Move();
            Report();
            Move();
            Report();
            Move();
            Report();
            ResetRobot();


T3 - Test placing the robot before moving

      STEPS implemented for this test case
      
            Report();
            Move();
            Report();
            Move();
            Report();
            ResetRobot();

T4 - for placing the robot properly before moving

      STEPS implemented for this Test case
      
            placeRobot(0, 6, "NORTH");
            Report();
            Move();
            Report();
            ResetRobot();

