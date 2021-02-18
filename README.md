# Drosophila-Active-Granular-Fluid-Model-

      ! The simulation code for our manuscript “Mechanical Feedback 
      ! and Robustness of Apical Constrictions in Drosophila Embryo 
      ! Ventral Furrow Formation” by M.C. Holcomb, G.-J.J. Gao, 
      ! M. Servati, D. Schneider, P.K. McNeely, J.H. Thomas, 
      ! and J. Blawzdziewicz.
      !
      ! The code is written by Dr. Guo-jie Jason Gao and compiled and tested 
      ! using Intel Fortran Compiler.
      !
      ! (G.-J.J. Gao's Contact information)
      ! email: koh.kokketsu@shizuoka.ac.jp
      ! Department of Mathematical and Systems Engineering
      ! Shizuoka University, JAPAN
      !
      !--------------- list of essential input parameters ---------------
      ! (in the program)                 (in the manuscript)
      ! str1              # name of initail configuration file
      ! dt_sigma1         # time step using the small particle diameter 
      !                   # as the length scale
      ! gamman_sigma1     # damping coefficient using the small particle 
      !                   # diameter as the length scale
      ! constriction_rate # constriction factor f_c
      ! Rratio            # diameter ratio r = 1.1
      ! alpha             # The \alpha in the constriction probabilities eqn 
      ! beta              # The \beta  in the constriction probabilities eqn
      ! ave_single_deform # the average tensile deformation
      !                   # experienced by a single particle constricted 
      !                   # in the initial configuration
      ! affected_rate     # the probability reduction constant \alpha_r
      !------------- end of list of essential input parameters ----------
