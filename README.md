# 1D-FFT
1D FFT RISC V


As for the project guidelines, it was needed a working Vectorized RISC_V complete 1D FFT [Fast Fourier Transform] code.

We started the project with the basics:

=>Step 1 was the making C files for all the important components for FFT.
-> Bit Reversal
-> Butterfly and twiddle factor

=>Step 2 was converting these chunks into RISC-V scalar and combine them to make a recursive FFT. 

=>Step 3 was to Convert the fully working Scalar to into Vector 1d FFT.


The files attached are of 
Step 1:
1. Bit Reversal C
2. Butterfly_Twiddle-Factor in C
3. FFT Recursive in C
// These files are complete and working
and Step 2:
1. CODE_1_NV1D_FFT[Scalar code try 1]
2. CODE_2_NV1D_FFT_[Scalar code try 2]
3. SCALAR_CODE_FFT1_TRY_NO_999999999
// These files are underdevelopment, needs debugging.


Files:

 1. Bit Reversal C:
This files includes 
    



