# ADC
Simulink models for WiFire ADC

File ADC_UART_Burst is a simulink model compiled for WiFire
  this is a 2-channel ADC with output to matlab via serial.
  Channel 1 is single sample per step (noisy)
  Channel 2 is 256 samples averaged per step (clean)
  Use PICGUI in Matlab, Plot int16
  MCU Utilizatoin (sort of works) is commented out.
