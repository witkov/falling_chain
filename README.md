# falling_chain
1.  Open one of the 5 falling chain videos (L1.MOV, L2.MOV, L3.MOV, L4.MOV, L5.MOV) into Tracker (https://physlets.org/tracker/).
2.  Click on Video | Filters | New | Rotate | clockwise 90 degrees to rotate the video so that the chain falls downward.
3.  Click on Video | Filters | New | Brightness and adjust the Brightness and Contrast sliders to make it easier to see both ends of the meter stick.
4.  Click on the Clip Settings icon and set frame rate to 400/s.
5.  Click on the Calibration setting and select New Calibration Stick.
6.  Shift-click the top and bottom of the meter stick and set length to 1m.
7.  Click on the Axes icon and move the cross-hair to the vertical height of the starting chain but well to the left of the chain so the vertical axis line doesn't obscure the chain. 
8.  Move the frame slider to the frame where the chain just starts to fall.  Record the frame number shown at the lower left.  
9.  Let the cursor hover over the end of the chain as it just starts to fall and record the y-displacement shown in the small box that appears. The y-displacement should be close to zero.
10.  Move the frame slider to the frame where the chain is fully extended and not recoiled.  Record the frame number.
11.  Let the cursor hover over the end of the extended chain and record the y-displacement shown in the small box that appears.
12.  Subtract the smaller from the larger frame number and divide the difference by 400.  This is the time the chain took to fall.
13. Subtract the smaller from the larger y-displacement.  This is the length of the chain.
14. Repeat the above steps two more times so you obtain three estimates for the chain length and three estimates for the time to fall. 
15. Repeat the above steps for each of the five falling chain videos.
16. At https://github.com/witkov/scripts click on falling_chain.ipynb and click on Open in Colab.
17. Average the three lengths obtained for each chain. giving five mean values, one for each chain, and substitute these five mean values in the ind_var array. 
18. Substitute the three time values you obtained for each chain in the five dep_var arrays.
19. Run the script by clicking on the encircled right pointing triangle.
20. Save the results displayed at the bottom of the script, e.g., both plots and the numerical results. Observe the value of A_best and compare with the predicted model value.  Also note the value of minchi2 and determine whether the best fit model is a good fit to the data. 
