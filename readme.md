Weertman, W.<sup>1,2</sup>, & Scheel, D.<sup>2</sup> (2023). Hold It Close: Male Octopus Hold Their Hectocotylus Closer to Their Body. doi:10.21203/rs.3.rs-2562006/v1

<sup>1</sup> Alaska Pacific University, 4101 University Drive, Anchorage AK 99508  
<sup>2</sup> Friday Harbor Lab, University of Washington, 620 University Rd, Friday Harbor, WA 98250

Abstract
The right third arm of the male octopus is the hectocotylized arm. This arm is modified by anatomy specialized to hold and transfer sperm packets to the female, and lacks suckers at the distal end. Male octopus may be distinguished by the skilled eye from their habit of holding their hectocotylus closer to their body in a protective manner, although this observation has never been described quantitatively. We utilized a three-step process of data annotation, pose estimation model training, and model inference to show that this common observation is true of Octopus rubescens. In 2338 images, the eyes, mantle tip, and arm tips of 2 male (n = 1152)  and 3 female (n = 1085) octopuses were annotated by an experimenter. These images were then used to train a DeepLabCut pose estimation model which achieved a RMSE of 1.78 cm. This model was then used to annotate 11.4 hours (n = 408985 images) of 4 female and 8 male octopuses moving across the middle of a large aquarium. We then compared the human annotated data, and the model inference data separately. In both datasets we compared the arm tip to eye centered point distances, as well as the octopus centric arm tip 90% kernel density estimation area. In both the training dataset and the model inference datasets we found common results. Male O. rubescens hold their third to the right arm closer to their body than all seven other arms while the females do not. Further, in both males and females, the rear arm pairs operate closer to the body than the front arm pairs. Despite their anatomical similarity and potential redundancy, these results indicates functional differences in arm use by octopuses.

![Male octopus hold their hectocotylus closer to their body than other arms](/PLOTS/Figure1.png)

**Figure 1. Male octopus hold their hectocotylus closer to their body than other arms.** *Visual comparison of the third to the right arm tip area distributions of male and female octopus while octopus moved across the center of the aquaria.* (a.) A male octopus viewed from above in the behavior recording aquarium. Standard naming convention for octopus arms is used, right arms R1-4 and left arms L1-4 are shown. The hectocotylus is highlighted in yellow. (b.) Dissected and fixed *Octopus rubescens* hectocotylus showing the arm tip specialization for reproduction. (c.) Unspecialized *O. rubescens* arm tip. (d. & e.) All annotations were rotated into the octopus frame of reference and oriented perpendicular to the left and right eye axis. Sample size (n) for each sex is the number of annotated images (see Methods for details); sample size (N) is the number of individuals of each sex for which data was annotated to train the model. The third to the right arm (R3) is shown in red. (d.) The combined 90% kernel density estimation (90%KDE) contour of arm tips in the expert annotated training set for DeepLabCut. (e.) The individual 90%KDE for of arm tips for each octopus.

_____________________

Please note. Two directories within DATA; dlc_continuous_data and dlc_inference. Have readme.md dropbox file links to the data files required for the code to run. 

---------------------

This project is primarily licensed under the GNU Lesser General Public License v3.0. Note that the software is provided "as is", without warranty of any kind, express or implied. If you use the code or data, please cite us!
