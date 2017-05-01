## Tackling Background Differently - presented at ICVSS-2015
- This work proposes classifying background using a learned threshold. 
- It branches off from the research presented in <a href=http://www.robots.ox.ac.uk/~tvg/publications/2015/bmvc_383_cr.pdf>Prototypical priors, Jetley et.al</a>. 
- An attribute-based continuous embedding space is defined over the category labels to allow test-time mapping of images to unseen classes; in this case the attributes were the prototypical templates of objects such as traffic lights, logos, etc.
- This affords smooth incorporation of attribute-based embedding space over the non-background category labels in classification models.
