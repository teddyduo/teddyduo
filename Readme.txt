Run:
java -jar acoecfd.jar E:\\ACOECFD\\fMRI-4.txt 5 10000 E:\\ACOECFD\\DTI.txt 10 1 2 0.2 0.8 10 100 10


Parameters Explanation:
Parmeter1: E:\\ACOECFD\\fMRI-4.txt ; File path of fMRI data which has been Discretized.
Parmeter2: 5 ; Number of brain regions
Parmeter3: 10000  ; Length of fMRI data
Parmeter4: E:\\ACOECFD\\DTI.txt  ;   DTI matrix (5¡Á5£©Number of brain regions¡ÁNumber of brain regions
Parmeter5: 10 ; Running times

Default parameters of ACO algorithm:
Parmeter6: 1 ; alpha 
Parmeter7: 2;  beta
Parmeter8: 0.2 ;  rou
Parmeter9: 0.8  ;  q0
Parmeter10: 100 ; Maximum number of iterations
Parmeter11: 10  ; Optimized generation interval

Note:
Data (fmri data and DTI matrix) are seperated by comma.
Refer to the sample data given.





