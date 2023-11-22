GitHub Repo for:

Hold It Close: Male Octopus Hold Their Hectocotylus Closer to Their Body
Willem Lee Weertman^{1, 2}
David Scheel1
1 Alaska Pacific University, 4101 University Drive, Anchorage AK 99508
2 Friday Harbor Lab, University of Washington, 620 University Rd, Friday Harbor, WA 98250

Abstract
The right third arm of the male octopus is the hectocotylized arm. This arm is modified by anatomy specialized to hold and transfer sperm packets to the female, and lacks suckers at the distal end. Male octopus may be distinguished by the skilled eye from their habit of holding their hectocotylus closer to their body in a protective manner, although this observation has never been described quantitatively. We utilized a three-step process of data annotation, pose estimation model training, and model inference to show that this common observation is true of Octopus rubescens. In 2338 images, the eyes, mantle tip, and arm tips of 2 male (n = 1152)  and 3 female (n = 1085) octopuses were annotated by an experimenter. These images were then used to train a DeepLabCut pose estimation model which achieved a RMSE of 1.78 cm. This model was then used to annotate 11.4 hours (n = 408985 images) of 4 female and 8 male octopuses moving across the middle of a large aquarium. We then compared the human annotated data, and the model inference data separately. In both datasets we compared the arm tip to eye centered point distances, as well as the octopus centric arm tip 90% kernel density estimation area. In both the training dataset and the model inference datasets we found a common result. Male O. rubescens hold their third to the right arm closer to their body than all seven other arms while the females do not. 

####

Look in NOTEBOOK for the jupyter notebooks for this project. 
