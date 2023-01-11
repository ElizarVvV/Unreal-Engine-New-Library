# Unreal-Engine-New-Library
we are finishing very long and tiring complex codes. We develop the bp fast, simple and optimized new library together with our team.
=========================================================================================================================================================================

### Nodes that will come with the new version (0.2)

============================================================================================

![LineTraceStraightHitValid](https://user-images.githubusercontent.com/112575364/211874188-5240edb0-dec9-47ab-8349-54f175f746d8.png)

* = Line Trace Straight Hit Valid = The object it hits and the class it selects check with each other. (gives the position the camera is looking at, you can offset)

![LineTraceMouseHitValid](https://user-images.githubusercontent.com/112575364/211873248-f960c04e-1299-4c0e-b552-50c0b79a1d59.png)4

* = Line Trace Mouse Hit Valid = The object it hits and the class it selects check with each other. (The mouse cursor hits its position in the world)

![LoopWithinLoop](https://user-images.githubusercontent.com/112575364/211872392-71aa6b7a-b194-49d0-9616-553f57d80cc4.png)

* = Loop Within Loop = Creates a Loop within a loop. We can choose how many seconds to trigger the loops inside the loop. We can also tell how many Loop Within Loops to spawn. (no optimization problems , Use it comfortably.)

![SpawnLoopDelay](https://user-images.githubusercontent.com/112575364/211871625-bb71a0ba-1072-4e0b-bc82-acb37f0945bf.png)

* = Spawn Loop Delay = loop spawns. (no optimization problems , Use it comfortably.)

![JumpReady](https://user-images.githubusercontent.com/112575364/211870250-5cab369b-71ca-4ef1-8241-44644c15ccd4.png)

* = Jump Ready = used to jump and stop jump

![Merge](https://user-images.githubusercontent.com/112575364/211824486-4e2fa9bb-fadc-4fb7-925e-a3370ca00d3f.png)

* = Merge = Input A and B go to the same output

![bandicam 2023-01-11 00-39-48-798 - Kopya (2)](https://user-images.githubusercontent.com/112575364/211668188-45f8ddfa-f24e-4d37-9e5c-9c2246cf6024.png) 

* = Quality Each Loop = Thanks to the optimized loop system and delay, there is never an infinite loop error, it does not cause stuttering or freezing. It may cause some problems but should be constantly checked while using! 

![bandicam 2023-01-11 00-39-48-798 - Kopya](https://user-images.githubusercontent.com/112575364/211670343-f681f0c6-498c-4827-bd1b-d08055dedbd0.png)

* = For Each Loop Delay = each loop delayed returns and infinite loop and eliminate freezes. It may cause some problems but should be constantly checked while using!

![bandicam 2023-01-11 00-39-48-798](https://user-images.githubusercontent.com/112575364/211671244-2eb26b90-3f2a-4ad9-bb68-64669bfeb9b5.png)

* = Infite Loop Delay = provides unlimited loops with delay but We can turn it off and on whenever we want. Lets you loop inside a loop and very useful for checking a branch by using it as a continuous click.

![ClassOverlap](https://user-images.githubusercontent.com/112575364/211673252-67e8034b-6526-4357-a337-273ff46288af.png)

* = Class Overlap = creates a event actor begin overlap of your chosen class. You can start overlap by calling a class in any code writing and you can get the values of the class.

![ClassOverlapEnd](https://user-images.githubusercontent.com/112575364/211674157-98f40755-f166-41cb-9de6-6a68fbf29262.png)

* = Class Overlap End = creates a actor event end overlap of your chosen class. You can start overlap by calling a class in any code writing and you can get the values of the class.

![ClassHit](https://user-images.githubusercontent.com/112575364/211674765-290ab05e-fc4c-4cea-99ba-3e0b6f99ebec.png)

* = Class Hit = creates a actor hit of your chosen class. You can start overlap by calling a class in any code writing and you can get the values of the class.

![ClassClicked](https://user-images.githubusercontent.com/112575364/211675056-e57f28e8-2bba-43de-aae4-bc3e84edf119.png)

* = Class Clicked = Creates an actor event by clicking on the class of your choice. You can start overlapping and get the values of the class by calling a class in any script.

![ClassSetLocation](https://user-images.githubusercontent.com/112575364/211676364-c595c00a-c270-40c5-bbb5-8294c1aa8f42.png)

* = Class Set Location = Changes the position of the index value of the class you entered

![Line Trace Class](https://user-images.githubusercontent.com/112575364/211677080-25edd4b5-5014-4562-96ce-081ce06356e6.png)

* = Line Trace Class = hits your chosen class. You can get your class values like this and cast successfully Or it can be used for other things.

![LineTraceClassAll](https://user-images.githubusercontent.com/112575364/211677524-19bb5b8e-e439-4326-9fea-f827bf776fb3.png)

* = Line Trace Class All = hits all objects of your chosen class. You can get your class values like this and cast successfully Or it can be used for other things.

![LineTraceMouse](https://user-images.githubusercontent.com/112575364/211678499-786952ba-3028-4ca0-a177-694d5bc9b7d4.png)

* = Line Trace Mouse = The mouse cursor hits its position in the world.

![LineTraceTarget](https://user-images.githubusercontent.com/112575364/211678987-248e24ca-fc73-43b9-b2ed-d8250d11af39.png)

* = Line Trace Target = Hits the selected object. You can get your class values like this and cast successfully Or it can be used for other things.

![LineTraceStraight](https://user-images.githubusercontent.com/112575364/211679096-b34fbfb2-1c17-4c41-976d-e4abd233325a.png)

* = Line Trace Straight = throws a straight hit where the camera is looking. We can shift the position it hits with drift.

![GetMouseCordinateSystem](https://user-images.githubusercontent.com/112575364/211681103-ac9d4518-6ea3-45c9-bef8-39de7f185b1d.png)

* = Get Mouse Cordinate System = Takes value according to the coordinate system. the middle of the screen is the 0 point.

![GetMouseInWorldLocation](https://user-images.githubusercontent.com/112575364/211747065-d5845d86-46af-4287-b1a4-6ef887f7a24e.png)

* = Get Mouse In World Location = Returns the position of the place clicked with the mouse on the world.

![GetStraight](https://user-images.githubusercontent.com/112575364/211747331-d447c654-a63a-4bde-8288-8100e18b5eb8.png)

* = Get Straight = gives the position the camera is looking at, you can offset.

![GetClassAll](https://user-images.githubusercontent.com/112575364/211747637-72ad2be8-bee3-4670-8776-d16daba9f40c.png)

* = Get Class All = Returns the Object and location of the class.

![Hit Valid](https://user-images.githubusercontent.com/112575364/211749953-9e3d762f-ae36-49d8-94ab-4dcf6fa99d84.png)

* = Hit Valid = Checks whether the class you selected and the class you hit are the same and Returns the value of the selected class.

![SwipeScreen2D](https://user-images.githubusercontent.com/112575364/211750407-c8614f0b-ea08-4ce6-8f2a-2b6f320eec2d.png)

* = Swipe Screen 2D = It works as a coordinate system and understands the movements you make on the screen.

![GetMoveSwipeScreen2D](https://user-images.githubusercontent.com/112575364/211750894-0319e62e-93d1-40d7-8712-e566d53b722f.png)

* = Get Move Swipe Screen 2D = this allows you to move by clicking on the screen if Swipe Screen 2D is connected

![TouchSwipeUdrl](https://user-images.githubusercontent.com/112575364/211752261-c01f850e-6839-4af1-8526-175e930d1c7e.png)

* = Touch Swipe Udrl = allows to navigate the upper lower right left by touching the screen

![LaunchController](https://user-images.githubusercontent.com/112575364/211752652-1150031b-3d3e-4d29-a54c-9af6e3dbfcf7.png)

* = Launch Controller = Provides Yaw and Pitch movements on the screen, so it allows you to look around.

![AddTargetMoveSelf](https://user-images.githubusercontent.com/112575364/211753185-408f5973-fd52-496d-b56d-6d163917a458.png)

* = Add Target Move Self = Allows movement according to the target you enter. (Designed for fps games!)

![ViewportLeftAndRight](https://user-images.githubusercontent.com/112575364/211755163-e5b55a85-e566-4b89-9564-24a113b2893c.png)

* = Viewport Left And Right = Depending on where the mouse cursor is Understands viewport left and right it returns bool value accordingly.

![DelayRate](https://user-images.githubusercontent.com/112575364/211755670-48ffee16-7263-46fe-956e-a4aa1830d6d0.png)

* = Delay Rate = Returns an integer value that increases continuously and very fast (There is a loop within a loop, it should not be called too often!)

![ResetOnceLoop](https://user-images.githubusercontent.com/112575364/211757169-f4e89887-a3e7-4c23-a3c7-3d9a8b4c26ba.png)

* = Reset Once Loop = You can use it under what condition you want the place you linked to return.

![objectIn ComponentValid](https://user-images.githubusercontent.com/112575364/211757748-817f5b1c-04dd-41dd-b985-2d8826f296e1.png)

* = Object In Component Valid = Allows you to control the products inside your object.

![SwichValid](https://user-images.githubusercontent.com/112575364/211758215-4aa0b3d3-7c33-4a33-895a-63e2c1ab3e63.png)

* = Swich Valid = Compares two objects with each other.

![GetGunStyle](https://user-images.githubusercontent.com/112575364/211759967-9fb5b7d0-e57e-4823-86e9-1463c4140809.png)

* = Get Gun Style = Gives transform like where she shoots with a gun.

![BranchMulti](https://user-images.githubusercontent.com/112575364/211760545-39bf5845-2f24-4b69-8c94-cbe93ff95008.png)

* = Branch Multi = Provides Branch control with 6 outputs.

![ListVeriables](https://user-images.githubusercontent.com/112575364/211760930-1e344927-91a7-4466-af6d-60ef1743c751.png)

* = List Veriables = For temporary use of variables.

![FlipFlopPlus](https://user-images.githubusercontent.com/112575364/211761134-0b4017d1-49b0-477e-907d-8bfdaef6666c.png)

* = Flip Flop Plus = The FlipFlopPlus node receives one execution output and switches between six execution outputs.

![GetTargetMove](https://user-images.githubusercontent.com/112575364/211761678-12efa513-ade7-4771-a802-e6747d110f2f.png)

* = Get Target Move = Returns the right and forward values of the entered target

![SwichMaterial](https://user-images.githubusercontent.com/112575364/211762022-b2cabb17-5f8b-4ddd-aa5c-8a991f24fea3.png)

* = Get Target Move = Switches between two materials

