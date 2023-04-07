# bai_myaidea
Building AI My Idea

Building AI course project

##Summary
The Idea. AI/ML assisted road traffic recognition and classification. Locate some good-enough quality microphones outside on a roadside. Monitor the recived audio spectrum/noise by a computer. When traffic (cars, lorries, motorcycles etc.) pass by they contribute to received noise by their specific audio fingerprint. Let AI/ML algorithm to analyse the audio signal and learn which sounbd is coming from which vehicule. Some assistance can be provided o teach the algorithm. LAter the algorthm can classify how many vehicles paass the monitor location and can be used for traffic counting instead of cameras.

##Background
Audio signal detection is less intrusive and harmful for privacy than video signal. It can alos provide infromation not available in video stream, so audio and video analysis may complement each other.

##Data and AI techniques
Main source is the gathered audio spectrum and some manual or video-assisted classification. There may be possibiliyt to use prerecorded audio libraries. Approaches studied are unasisted and assisted learning. Probably non-liner ML is the most viable tool here. If we consider audio signal similar to image reckognise problem, tehn CNN or RNN may be applicable.

##How is it used
City authors and law enforcement. Reasearch community when designing better environmental solutions and city plans.

##Challenges
I have no idea how complex (expensive) audio technology system is requred to provide good enoug quality signal for analysis. Teachning the AI/ML algorithm may be challemge due to several unknown parameters. Sound patterns may be so diverse that classsification is very challenging. Audio pattern changes along weather conditions (dry summer, snow/slushhy winter).

##What next
When system is up and running it offers platform for further experimentation: Can we detect the speed of vehicules to monitor how fast thay are moving on avarage (vs. speed limit)? Can we say if a car is using summer or winter tyres 8as winter tyres with spikes may be banned on certain roads)? Analysing in more detail the soun of motors, can we say something about the agae or potential problems with car motors (maybe for privacy purposes we wont identify individual cars)?


##Acknowledgments
Not known yet if open source will be used but probably well known AI libraries like Tensorflow. Mey be worh studying if ChatGPT of something similar can be utilised.
