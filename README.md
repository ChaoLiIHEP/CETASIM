# CETASim
CETASIm is an open-source C++ code for beam collective effect simulation in electron rings. 
It can deal with 

 The program can simulate the collective effects due to short-range and long-range wakefields 
 for single and coupled-bunch instability studies. It also features to simulate the ion interactions 
 with the trains of electron bunches, including both fast ion and ion trapping effects. 
 As an accelerator design tool, the bunch-by-bunch feedback is also included so that the user can simulate 
 the damping of the unstable motion when its growth rate is faster than the radiation damping rate. 
 The particle dynamics is based on the one-turn map, including the nonlinear effects of amplitude-dependent 
 tune shift, high-order chromaticity, and second-order momentum compaction factor. When required, 
 a skew quadrupole can also be introduced, which is very useful for the emittance sharing and the emittance exchange studies.


##Code compiling 
Two extra numerical libraries, GSL and FFTW are needed for code compiling. 
The version of the GSL library has to be larger than 2.7. 
If the user working with the Linux system, supplying the right path (LIBFLGS) in the Makefile, the source code can be compiled easily by the make command

./make


Any problems, please contact the author li.chao@desy.de supperli.imp@gmail.com.








