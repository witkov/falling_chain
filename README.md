# falling_chain
1.  Load one of the 5 falling chain videos (L1.MOV, L2.MOV, L3.MOV, L4.MOV, L5.MOV) into Tracker (https://physlets.org/tracker/).
2.  Click on the Clip Settings icon and set frame rate to 400/s.
3.  Click on the Calibration setting and select New Calibration Stick.
4.  Shift-click the top and bottom of the meter stick and set length to 1m.
5.  Click on the Axes icon and move the cross-hair to the vertical height of the starting chain but well to the left of the chain so the vertical axis line doesn't obscure the chain. 
6.  Move the frame slider to the frame where the chain just starts to fall.  Record the frame number shown at the lower left.  
7.  Let the cursor hover over the end of the chain as it just starts to fall and record the y-displacement shown in the small box that appears. The y-displacement should be close to zero.
7.  Move the frame slider to the frame where the chain is fully extended and not recoiled.  Record the frame number.
8.  Let the cursor hover over the end of the extended chain and record the y-displacement shown in the small box that appears.
9.  Subtract the smaller from the larger frame number and divide the difference by 400.  This is the time the chain took to fall.
10. Subtract the smaller from the larger y-displacement.  This is the length of the chain.
11. Repeat the above steps two more times so you obtain three estimates for the chain length and three estimates for the time to fall. 
12. Repeat the above steps for each of the five falling chain videos.
13. At https://github.com/witkov/scripts click on falling_chain.ipynb and click on Open in Colab.
14. Average the three lengths obtained for each chain. giving five mean values, one for each chain, and substitute these five mean values in the ind_var array. 
15. Substitute the three time values you obtained for each chain in the five dep_var arrays.
16. Run the script by clicking on the encircled right pointing triangle.
17. Save the results displayed at the bottom of the script, e.g., both plots and the numerical results. Observe the value of A_best and compare with the predicted model value.  Also note the value of minchi2 and determine whether the best fit model is a good fit to the data. 
