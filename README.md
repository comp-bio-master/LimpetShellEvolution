# LimpetShellEvolution

## Extracting data from 3D scans of limpet shells to test for fisheries-induced evolution

My lab has been studying the evolution of limpets in Hawaii.  They are a local delicacy and are under intense harvesting pressure.  We are interested in the selective pressures applied by overharvesting and how it affects the evolution of phenotypes.  

We found that shell surface area is associate with human harvesting and want to use 3d scans of the limpet shells to more precisely test of effects of harvesting on phenotype. Here are some views of a 3d scan:

![alt text](https://github.com/tamucc-comp-bio-2020/classroom_repo/blob/master/lectures/Week03_files/3Dscan_limpetShell.PNG) ![alt text](https://github.com/tamucc-comp-bio-2020/classroom_repo/blob/master/lectures/Week03_files/3Dscan_limpetShell_left.PNG) ![alt text](https://github.com/tamucc-comp-bio-2020/classroom_repo/blob/master/lectures/Week03_files/3Dscan_limpetShell_right.PNG) ![alt text](https://github.com/tamucc-comp-bio-2020/classroom_repo/blob/master/lectures/Week03_files/3Dscan_limpetShell_top.PNG) ![alt text](https://github.com/tamucc-comp-bio-2020/classroom_repo/blob/master/lectures/Week03_files/3Dscan_limpetShell_bottom.PNG)

#### [Related Publication from my Research Group](https://onlinelibrary.wiley.com/doi/abs/10.1111/jbi.13845?af=R)

---

## Description of Assignment

You will be working in bash to manipulate the 3d scans of limpet shells we discussed in class.  

* Clone the repository for this assignment to your home dir in your terminal. 

* Ensure that the `admesh2tabdelimited.bash` script works by running it on the `admesh.out` data. This script converts the output of `admesh`, a unix command that extracts information from 3D scans stored in `stl` files, into a "tidy" data file.

* Complete the requested updates to the `admesh2tabdelimited.bash` script

* I recommend testing function and troubleshooting as necessary after each change you make to the script

* You may work in groups but each student must submit their own work.


### To `push` your changes to your repository on GitHub, and thus submit the assigment, do the following

* change directories to the directory for this assignment
* type the following:
```
git add *
git commit -m "updating my assignment"
git push origin master
```

Note that 
* you can change the `commit` message to whatever you want (the part in quotations, but keep it brief
* you will have to provide your github username and password for the `push` to `origin master`
