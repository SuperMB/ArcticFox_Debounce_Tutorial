# Debounce - Arctic Fox Tutorial

<p align="center">
    <img src="https://icii.io/wp-content/uploads/2022/09/New-Arctic-Fox-Logo.Blue_.For-Animation.WithBehindForGaps-1.svg" alt="Arctic Fox Logo" style="width:300px;"/>
</p>

This repo is a tutorial that implements a button debouncer. The code uses Arctic Fox to easily detect the rising edge of the button and a counter to debounce the button. This example provides a short introduction to Arctic Fox. 

<br>
<br>
<br>

## Setup
To setup the tutorial, follows these steps: 
1) Fork this repo, **make sure to uncheck main branch only** 
2) Launch the repo in a codespace, wait for the codespace to finish building and extensions finish installing
3) Click the Arctic Fox silhouette on the left, click Activate Arctic Fox on the bottom of the Arctic Fox panel, and enter your Arctic Fox email and password, press Activate (enter not yet supported...) 

## Steps
The tutorial contains the following steps in the following files: 
- Verilog/HandwashSensor.v
  - Steps 1, 2, 3, 4
- Verilog/HandwashSensorTest.v 
  - Step 5

You can run the result in a Verilog simulator. We have included the folder IpCores for simulating in Vivado. 

## View Solution
*Before viewing the solution, make sure you've complete the **Setup*** 

To view the solution, git commit changes on the main branch, and then do: 

> git checkout solution

To go back to the tutorial, do: 

> git checkout main

### Trouble Shooting
If you accidentally make changes to the solution and are having trouble switching back to the tutorial, do an add, then stash, then checkout: 
> git add . 

> git stash 

> git checkout main 