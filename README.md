# Mel-Filter-Banks-on-VHDL

  In this vhdl code pre-ready 1khz signal on frequency domain has been put into a single port rom and for that interval signal has been divided into 13 energy spectrum for 128 data. 
  For this algorithm input data between 0-128 represents 0 - 4KHz band and preapered signal has been considered as 1khz with 3.3 peak to peak voltage value. And signals represenatation in frequency domain has been given as input. 
  Input data 32 bit, and Mel freuqnecy magnitudes has been considered as 8 bit and the result becomes 40 bit.
  For calculation of each bank in total, maximum psossible output has been considered as 64 bit but it is only true for 3.3 V Pk-Pk hanned signal.
