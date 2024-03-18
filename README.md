# Pythonclass
You can use the program spike threshold detector and time stamp generator to detect spikes in your data.
The program is designed to work with matlab data files. If you work with another data type you might have to change the code for data import.
Please indicate the path to your data in the import code and the indices of your rawdata and sampling interval to define the parameters.
The sampling interval should be indicated in μs.
Furthermore indicate the number of channels in the data you imported.
Decide for a threshold from where more extreme data points will be detected as spikes. If you decide for a negative threshold the program will detect more negative points while the program will find positive spikes for positive thresholds
Lastly indicate in which channel you would like to search for spikes.
The output will be a column array with the timestamps of the spikes in miliseconds in the chosen channel.
