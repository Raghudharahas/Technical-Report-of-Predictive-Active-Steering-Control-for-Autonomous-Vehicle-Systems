# Code Install Instructions

1. Download the active predictive steering folder.
2. Open that in Matlab and add the ltv_mpc and nl_mpc into the path.
3. Type the following commands in the command window to install YALMIP.
```
addpath(genpath([pwd filesep 'yalmip']));

savepath
```
4. Ignore if there is any warning in saving the path.
5. If the above steps are done, the package is ready to implement.

# Code Run Instructions

## Paecjka Model
1. To run and see the graphs of Paecjka tire model, expand the nl-mpc folder in the matlab file viewer and select the Paecjka.m file.
2. Click on "Run" to generate the lateral and longitudinal force graphs.

## NL- MPC

1. To run the nl-mpc, go to the nl-mpc directory and run the nl_mpc.m file.
2. This will start the program and will do some iterations to solve the optimization problem.
3. By default, it would take 12 seconds to complete the program and the final graphs will popup

## LTV- MPC

1. To run the ltv-mpc, go to the ltv-mpc directory and run the ltvmpc.m file.
2. This will start the program and will do some iterations to solve the optimization problem.
3. By default, it would take a few seconds to complete the program and the final graphs will popup.

Please contact us if there is any issue in running the code



