## Tackling Background Differently - presented at ICVSS-2015
- This work proposes classifying background using a learned threshold. 
- It branches off from the research presented in <a href=http://www.robots.ox.ac.uk/~tvg/publications/2015/bmvc_383_cr.pdf>Prototypical priors, Jetley et.al</a>. 
- An attribute-based continuous embedding space is defined over the category labels to allow test-time mapping of images to unseen classes; in this case the attributes are the prototypical templates of objects such as traffic lights, logos, etc.
- The background class is ill-defined and has a changing definition based on the object categories considered. Establishing an attribute mapping for the background class is non-trivial.
- Thus, existing deep classfication pipelines need to be modified to allow bypassing an attribute mapping for the background.
- We propose one such modification in the current work.
- This architecture affords smooth incorporation of attribute-based embedding space over the non-background category labels in classification models; while bypassing the background label.
