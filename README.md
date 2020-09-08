# Virtual Reality_MR that Merges real and Virtual worlds

## Overview
Augmented reality (AR) and Mixed Reality (MR) are significant extensions of the conventional virtual reality (VR) that handle virtual environments constructed by a computer. Originally, VR was
advocated to treat various types of sensory information such as visual, auditory, tactile, and olfactory senses. Auditory VR was achieved by generating a 3-D sound field. On the
other hand, most of the earlier AR/MR systems were primarily designed to cover a visual mixture of real and virtual worlds. Sometimes audio and tactile sensations are added to
visual MR in the form of stage effects. More recently, some AR/MR systems have been developed, which also incorporates 3-D sound. However, all these systems simply added auditory
VR to visual MR. 
This paper implements the development of an MR system using both audio and visual senses. The users of generally wear a see-through head-mounted display (HMD) to experience the MR
space. In addition, the combined sound for is not presented from speakers but from headphones; there are two possible ways to hear the combination of real and artificial sounds—
open-air or closed-air headphones. These are similar to the “optical see-through” and “video seethrough” methods employed in visual MR.

![3d audio](https://user-images.githubusercontent.com/56169161/92506112-90029e80-f1ca-11ea-995d-31459d80a74e.png)

## How it Works?
It is quite difficult to present 3-D sounds to multiple users in an MR space using the transaural method. Consequently, in this study, the binaural method was preferred for 
presenting a 3-D sound field to each subject. When thinking about an auditory mixture of real and virtual worlds, two methods are possible similar to that applicable to a visual
mixture.The “physical mixing” in the below figure can be experienced using open-air headphones. Here, artificial sounds through the headphones, either pre-recorded or synthesized,
and real sounds heard through a pair of gaps between each ear and the headphone’s ear covers, are physically mixed. This is similar to the optical see-through method used in the
visual sense. 

![audio](https://user-images.githubusercontent.com/56169161/92507450-9c87f680-f1cc-11ea-8853-b739c31350a0.PNG)


“Electronic mixing,” as shown above, can be achieved using closed-air headphones. Natural sounds in the real world are gathered by a pair of microphones attached to the outside of
the headphones and then mixed with the artificial sound using a computer. The resultant mixed sound reaches the user through closed-air headphones. This auditory mixing method
corresponds to the video see-through method.  

### Experiment and results
The real and artificial sounds were set as a static sound source. The test subjects heard both sounds simultaneously and answered questions based on sound source localization
and sound quality. The sound quality evaluation used a subjective appraisal scheme based on five-levels, from 1 (bad) to 5 (excellent). For artificial sound, a helicopter
propeller’s sound was chosen. The real sound (classical music) was provided by one of three speakers surrounding the subject. 

## Strengths and Weakness
The introduction of audio into a Mixed Reality environment will provide the user with life-like perspective, depth and atmosphere to direct and immerse them within their virtual
experience.

Duplication in hearing the voice, which is directly transmitted through the subject’s body, as well as via the headphones.

Uncomfortable feelings associated with the negative effects of rustling sounds from the headphones and the microphones

## Conclusion
This paper, describes the development of a system that can simultaneously and consistently manage both visual and auditory MR, in real time. In order to achieve an auditory MR
display, there are two alternatives—the physical mixing method using open-air headphones and electronic mixing method using closed-air headphones. Initially, it was assumed that 
the electronic mixing method would be as appropriate as the video see-through method is in visual MR. However, during the experiments, it was found that open-air headphones are
superior to closed-air headphones. Hence, it was  decided to use the physical mixing method in the development of, namely, the two-by-two audio–visual MR system.
