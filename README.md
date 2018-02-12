# eventDetector
Epileptiform event and spike detector for cat picrotoxin focal seizure model

The included MATLAB code (eventDetector.m) runs an automated epileptiform event and spike detector on a channel of LFP data. 
It find the start and stop points of epileptiform events on the channel, as well as the start and stop points of all 
detected spikes within each event.
The detector was created to work with ECoG data from a focal, picrotoxin-induced seizure model in anesthetized cats. 

Further details for the operation of the detector can be found in the 2018 Journal of Neurophysiology titled
"Spatiotemporal Evolution of Focal Epileptiform Activity from Surface and Laminar Field Recordings in Cat Neocortex"
by Bink et al.

Experiment1DetectorInputData.mat provides the LFP data from the ECoG detector channel in the first experiment.
It also has the other input variables needed to run the event/spike detector and obtain the results outlined in the 
paper for the first experiment.
