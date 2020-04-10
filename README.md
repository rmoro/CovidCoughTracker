# CovidCoughTracker
Using audio and standard CCTV video to identify and track possible covid-19 infections and their spread. This is accomplished by tracking and categorizing coughing events in a surveilled space. 

## How
Using audio, coughs can be identified and classified with a convolutional neural network trained on different coughing types (See medial research).  This can be used to estimate the likelihood of a cough being caused by the COVID-19 virus. 

Using video, coughing is detected and tracked with real-time human pose estimation, face/person detection/tracking. Once a coughing event is visually detected with a network trained in human pose estimation, we also have a method to determine if the cough was done into a sleeve/hand or into the air.  We can also estimate the direction of the cough and identify anyone who is likely hit by the expectorant released from the event. This is accomplished through by modeling the space and air flow to determine where any particles released from a cough may land. 

Visual requirements involve tracking multiple subjects’ positions and poses while estimating the distances between them. We combine the visual data with the audio data to attribute audio events to their visual cues in real time.  This will allow us to attribute a risk level to any subjects in the surveilled field.

## Why
This tool will help determine who needs tests, who is following social
distancing guidelines and help contact training efforts of the spread of known infections. The tool can be used by businesses, hospitals and cities to instantly estimate the risk level of anyone who may potentially be infected and provide data on where focused disinfection or containment may be needed.  

