# bai_myaidea
Building AI My Idea

Building AI course project

## Summary

The Idea. AI/ML assisted road traffic audio recognition and classification. Monitor the recived audio from road traffic spectrum/noise by a computer around the clock. When traffic passes by each vehicule (car, lorry, motorcycle, bike etc.) contributes to the received noise by their specific audio fingerprint. Let AI/ML algorithm to analyse the audio signal and learn which sound is coming from which object. Some assistance can be provided to teach the algorithm. Later the algorthm can classify how many vehicles pass the monitor location and can be used for traffic counting instead of cameras. Monitoring wide audio (even extended to infra and ultra sound) spectrum and analysing that with AI/ML may provide more sophisticated results than just measuring audio noise levels in decibels.

## Background

Using cameras alone in public places monitoring what is happenig in nature and in built environment may not be enough to detect all important events. These may be security related, law enforcement, environmental, sustainability or city management related. Traffic is one main contributor for environmental problems like pollution an noise and also potential source for savings in the society. So, audio and video analysis may complement each other. On the other hand, if privacy and human rights are the issue, audio signal detection alone is less intrusive and harmful for privacy than video signal.

## How is it used?

Locate some good-enough quality microphones outside on a roadside. Monitor the recived audio spectrum/noise by a computer around the clock over a long period.
City authors may use this to monitor noise level wheather it is within the limits. Law enforcement may use the analysis resutls to monitor if peed limits are followed on average and focus ticketing to the places where excess speed is more probable. Reasearch community when designing better environmental solutions and city plans.

For example: "The city of Leuven in Belgium limits noise nuisances from nightlife for its citizens and prevent damage to the hearing of the nightlife participants. The city has issued regulations that require establishments that play loud music to limit the sound levels and monitor these levels continuously."
Or: "To reduce noise, cities need new sensor technology that can tell the difference between a dog barking, a garbage truck and a revving motorcycle engine."

## Data and AI techniques

Main source is the gathered audio spectrum and some manual or video-assisted classification. There may be possibility to use prerecorded audio libraries. Approaches studied are unasisted and assisted learning. Probably non-liner ML is the most viable tool here. If we consider audio signal similar to image reckognise problem, tehn CNN or RNN may be applicable.

## Challenges

I have no idea how complex (expensive) audio technology system is requred to provide good enough signal for analysis. Teachning the AI/ML algorithm may be challenging due to several unknown parameters and reliability low. Sound patterns may be so diverse that classsification is very challenging. Audio pattern changes along weather conditions (dry summer, snow/slushhy winter), even similar vehicules may have very different sound (age, mileages), rouad surfaces and tyres are different (slick, spikes).

## What next

When system is up and running it offers platform for further experimentation: Can we detect the speed of vehicules to monitor how fast thay are moving on avarage (vs. speed limit)? Can we say if a car is using summer or winter tyres 8as winter tyres with spikes may be banned on certain roads)? Analysing in more detail the sound of motors, can we say something about the potential problems or need for maintenance (maybe for privacy purposes we wont identify individual cars)? Would be interesting to study what other man-made or natural sounds the system can learn to analyse: earthquakes? atmospheric phenomena like lightning?
Sound/noise sensor range could be extended to cover in addition to audible sounds also infra and ultra sound spectrum to gain more insight into monitered phenomena.

## Acknowledgments

Not known yet if open source will be used but probably well known AI libraries like Tensorflow. Mey be worh studying if ChatGPT of something similar can be utilised.
While checking if my idea was unique I found some very interesting related ideas, products and experiments:
* Noise measurements: Managing noise in Leuven nightlife https://munisense.com/
* Bloomberg: https://www.bloomberg.com/news/features/2021-12-02/can-sensor-technology-cut-noise-pollution-in-cities
* Real-Time Noise Monitoring for Smart Cities https://www.sonitussystems.com/insights/real-time-noise-monitoring-for-smart-cities/
