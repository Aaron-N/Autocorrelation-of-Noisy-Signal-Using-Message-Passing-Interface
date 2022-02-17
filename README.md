# Autocorrelation-of-a-Noisy-Signal-Using-Message-Passing-Interface
An example of autocorrelation of a noisy signal using Message Passing Interface (MPI) to join multiple machines as MPI Processors for faster analysis.

The program is currently configured to read in signal data in binary or ASCII form and will look for files named bigsignal.bin or bigsignal.txt.

Results are sent to a csv file named plot.csv that can be opened plotted by a spreadsheet program of your choosing.

Performance data in mega-autocorrelations computed per second is also displayed to stderr upon program termination.

A scatterplot of Autocorrelation Sums vs Shift for sample signal data containing a hidden sine wave can be viewed in scatterplot.jpg
