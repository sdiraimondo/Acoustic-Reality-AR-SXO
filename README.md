# Acoustic Reality AR-SXO - Minimal audio passive filter

A decade ago Acoustic Reality invented a capacitor-less serial crossover design for 2-way loudspeakers. Acoustic Reality has released the invention under the General Public License (GNU).

Peter Thomsen,  Acoustic Reality - Denmark : *I made the intention in year 2000. After several tests and analysis I released my AR-SXO hardware invention under the General Public License (GNU) in 2001, and it is still working :-)*

Mirror of http://web.archive.org/web/20110902214134/http:/arhifi.dk/store/product.php?id_product=22


## Introduction
Can you imagine a capasitor-less 2-way crossover that consist for just two coils and one resistor?
The crossover is distortion free, because it is capacitor-free and it is phase coherent too.

![Schematic](https://raw.githubusercontent.com/sdiraimondo/Acoustic-Reality-AR-SXO/main/22-76-large.jpg)

Here are the functions of the AR-SXO:
* L1 is controlling the slope of the tweeter - while killing the resonance frequency of it too.
* R1 is avoiding phase errors in the bass frequency area - while damping the tweeter too.
* L2 is just controlling the slope of the bass. 

## Requirements:
* High-end speaker drivers are mandatory, cheap speaker drivers from China will not work.
* To protect the tweeter the L1 coil must have a very low DC resistance. Foil coils of pure copper are recommended.


## Listening Impressions
If you don't believe the AR-SXO is working, then try it your self or listen to the hard core audiophiles and the professionals:

(Morawski) The sound is so smooth you positively cannot hear the transition from lows to highs. The bass is extremely solid and well controlled. The mids are lush but clear and the highs are detailed, airy, and delicate without a hint of brightness.


(Ken L.) How's the sound? A very big improvement, I believe eliminating the electronic xo played a larger part in the improvement. I am hearing things in the high frequencies that I did not know were there. Bells and cymbals are crisp and clear. Information that is down in level is easily heard.

(EdM) Trust me, you will never hear a better crossover at any cost.

(Yair) Regarding sound the sound is very good indeed, never though it can be done with so few parts!

(Jacq) Simply said, it is the best ever sounding crossover.

(Scorpio) Sound? Far better than original! More details, no sharpness, no rough SSS but still no dull sound, much bigger soundstage.....I'm amazed!!

(John P.) I'm a musician and have been building speakers for 25 years. The first thing that struck me was how well the drivers blended. For this combination just guessing at the values the difference was night and day. I'm very impressed.

(Ken P.) They sound pretty damn good.

(Mike F.) The female vocalists were IMO spot-on (good information retrieval with no snaky SSSSSSS's). The end result is indeed beautiful music.

(Dave) I have been designing recording studios and (repeating) crossovers for 37 years or so. More air, dynamics and "they are here" going on.

(Andy G.) With any of the normal series x-os I tried (without that huge LRC trap) there was a definite harshness/grittiness ? round about that frequency, the pillow test indicated it was definitely from the XT25, with the AR-SXO that just doesn't exist. I am now COMPLETELY HAPPY with the result.

(Al J.) I'm an audiophile for about 20 years now but your filter (without C) has amazed me like nothing before...... it was as if I heard my tweeter for the very first time! Although it is a very well known type (scanspeak 9300), it suddenly showed its qualities.

(Kevin W.) And damn, am I impressed!! The sound is so much more open, airy, and detailed. It's very much like listening to electrostatic speakers. The imaging... wow. Makes me want to stop typing and go out and listen some more. Hehe, anybody want to try this crossover? You'll be pleasantly surprised!

## Initial values
* L1=0.1mH
* R1=8.2ohm
* L2=1.5mH

Adjust R1 and L2.
R1 should NEVER be less than 3.9ohm.
The value of L2 depends of how much baffle compensation and how much bass you prefer.

## How to fine-tune the AR-SXO yourself
 
Here are some rules of how to find the values of the AR-SXO only using listening tests.

1. L1 should always be 0.1mH - it does work on almost all tweeters, including ribbons working in from 2kHz and up.

2. You need two coils each stereo speaker, initial values to find the correct values.
- 1mH
- 1.8mH.
Connect L2= 1.8mH in series to the bass unit, nothing else. If the sound is too compressed and there is too much bass on moderate volume level, then try 1mH. If you feel there is still too less midrange, then you have to go down in value, but remember you are not using the tweeter, not yet.

3. You need six cheap resistors each speaker - 5Watt or 10Watt - only to find the value, 3,9ohm, 4.7ohm, 5.6ohm, 6.8ohm, 8.2ohm, 10ohm Now you are using the value of L2 that you did find in step 2. Try all resistors and listen, start with 6.8ohm. You have to set up a pair of stereo speakers.

4. Fine-tune L2 and R1. May be L2 should be bigger than 1.8mH or a smaller than 1mH. If you need more bass, then use a bigger value L2 or reduce the value of R1. If you need less bass, then reduce the value of L2 or increase the value of R1. It is always best to keep the R1 as high as possible. It will let your amplifier an easier handle the load of the speakers (and therefore less distortion).

Important: Change the low power resistor to a high power resistor, 50W or more. Now you have a distortion-free crossover.
