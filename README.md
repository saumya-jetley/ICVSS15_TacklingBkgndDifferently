## Tackling Background Differently - presented at ICVSS-2015
- This work proposes classifying background using a learned threshold. 
- It branches off from the research presented in <a href=http://www.robots.ox.ac.uk/~tvg/publications/2015/bmvc_383_cr.pdf>Prototypical priors, Jetley et.al</a>. 
- An attribute-based continuous embedding space is defined over the category labels to allow test-time mapping of images to unseen classes; in this case the attributes are the prototypical templates of objects such as traffic lights, logos, etc.
- The background class is ill-defined and has a changing definition based on the object categories considered. Establishing an attribute mapping for the background class is non-trivial.
- Thus, existing deep classfication pipelines need to be modified to allow bypassing an attribute mapping for the background.
- We propose one such modification in the current work.
- This architecture affords smooth incorporation of attribute-based embedding space over the non-background category labels in classification models; while bypassing the background label.


<h2 style=color:gray>
# Licence

TacklingBkgndDifferently © 2015, Torr Vision Group, The University of Oxford (the "Software")
The Software remains the property of the University of Oxford ("the University").
The Software is distributed "AS IS" under this Licence solely for non-commercial use in the hope that it will be useful, but in order that the University as a charitable foundation protects its assets for the benefit of its educational and research purposes, the University makes clear that no condition is made or to be implied, nor is any warranty given or to be implied, as to the accuracy of the Software, or that it will be suitable for any particular purpose or for use under any specific conditions. Furthermore, the University disclaims all responsibility for the use which is made of the Software. It further disclaims any liability for the outcomes arising from using the Software.

The Licensee agrees to indemnify the University and hold the University harmless from and against any and all claims, damages and liabilities asserted by third parties (including claims for negligence), which arise directly or indirectly from the use of the Software or the sale of any products based on the Software.

No part of the Software may be reproduced, modified, transmitted or transferred in any form or by any means, electronic or mechanical, without the express permission of the University. The permission of the University is not required if the said reproduction, modification, transmission or transference is done without financial return, the conditions of this Licence are imposed upon the receiver of the product, and all original and amended source code is included in any transmitted product. You may be held legally responsible for any copyright infringement that is caused or encouraged by your failure to abide by these terms and conditions.

You are not permitted under this Licence to use this Software commercially. Use for which any financial return is received shall be defined as commercial use, and includes:
    integration of all or part of the source code or the Software into a product for sale or license by or on behalf of Licensee to third parties or
    use of the Software or any derivative of it for research with the final aim of developing software products for sale or license to a third party or
    use of the Software or any derivative of it for research with the final aim of developing non-software products for sale or license to a third party, or
    use of the Software to provide any service to an external organisation for which payment is received.
If you are interested in using the Software commercially, please contact Torr Vision Group directly to negotiate a licence.
Contact details are: philip.torr@eng.ox.ac.uk.
</h2>
