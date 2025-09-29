# Building Archetype Model Database (BAM-DB)

This repostitory documents a set of archetype building desings, designed to modern seismic U.S. codes. Each design contains an [OpenSees](https://opensees.berkeley.edu/) model for assessing structural performance and [FEMA P-58](https://femap58.atcouncil.org/) and [ATC-138](https://www.atcouncil.org/atc-138) models for assessing building loss and downtime risk. The archetypes are designed for a general high seismicity, Dmax, site with a soil class of C and follow the [ASCE/SEI 7-16](https://www.asce.org/publications-and-news/asce-7) design provision. The archetype set includes reference models designed to meet minimum base shear and drift requirements as well as enhanced designs that are designed for up to 50% higher strengths and 1% drift limits. Basic properties of each model are contained within the "models.csv" file, with detialed design, model, and response data in subsequent subfolders.

---

This repository is principally developed and maintained by:

1. Dustin Cook, Reserach Structural Engineer
   - Engineering Laboratory, Materials and Structural Systems Division, Earthquake Engineering Group
   - @dustin-cook
   - dustin.cook@nist.gov

Please reach out with questions and comments.

## Disclaimer
Certain equipment, instruments, software, or materials are identified here in order to specify the data/code adequately. Such identification is not intended to imply recommendation or endorsement of any product or service by NIST, nor is it intended to imply that the materials or equipment identified are necessarily the best available for the purpose.

NIST-developed software is provided by NIST as a public service. You may use, copy, and distribute copies of the software in any medium, provided that you keep intact this entire notice. You may improve, modify, and create derivative works of the software or any portion of the software, and you may copy and distribute such modifications or works. Modified works should carry a notice stating that you changed the software and should note the date and nature of any such change. Please explicitly acknowledge the National Institute of Standards and Technology as the source of the software.

NIST-developed software is expressly provided "AS IS." NIST MAKES NO WARRANTY OF ANY KIND, EXPRESS, IMPLIED, IN FACT, OR ARISING BY OPERATION OF LAW, INCLUDING, WITHOUT LIMITATION, THE IMPLIED WARRANTY OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, NON-INFRINGEMENT, AND DATA ACCURACY. NIST NEITHER REPRESENTS NOR WARRANTS THAT THE OPERATION OF THE SOFTWARE WILL BE UNINTERRUPTED OR ERROR-FREE, OR THAT ANY DEFECTS WILL BE CORRECTED. NIST DOES NOT WARRANT OR MAKE ANY REPRESENTATIONS REGARDING THE USE OF THE SOFTWARE OR THE RESULTS THEREOF, INCLUDING BUT NOT LIMITED TO THE CORRECTNESS, ACCURACY, RELIABILITY, OR USEFULNESS OF THE SOFTWARE.

You are solely responsible for determining the appropriateness of using and distributing the software and you assume all risks associated with its use, including but not limited to the risks and costs of program errors, compliance with applicable laws, damage to or loss of data, programs or equipment, and the unavailability or interruption of operation. This software is not intended to be used in any situation where a failure could cause risk of injury or damage to property. The software developed by NIST employees is not subject to copyright protection within the United States.
