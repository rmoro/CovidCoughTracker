# CovidCoughTracker
Using audio and standard CCTV video to identify and track possible covid-19 infections and their spread.  
This is accomplished by tracking and catagorizing coughing events in a
surveilled space.
By identifying and classifying coughing sounds using a convolutional neural network
we try to detect and differentiate between coughing events. This can be used to
estimate the likelyhood of a cough being caused by the COVID-19 virus. 
Coughing is detected and tracked visually with real-time human pose estimation, face detection and person tracking.  
Once a coughing event is visually detected with a network trained in human pose estimation. We also have a
method to determine if the cough was done into a sleeve/hand or into the air as
well as the direction of the cough. 
By knowing the direction, type, and whether the cough was blocked or relased into
the air, physics modeling can be used to determine the likelyhood and identification of anyone potentially exposed to
the airbourne particles released by the cough.  This involves tracking multiple
subjects postions and poses while estimating the distances between them in real
time. 
This tool will help determine who needs tests, who is following social
distancing guidelines, and help contact traing efforts or the spread of known
infections. The tool can be used by businesses to estimate their risk level of
spead while giving data on where focused cleaning may be needed.
