# OmegaFold
**OmegaFold Singularity container**

**Author:** Darrell O. Ricke, Ph.D. (Darrell.Ricke@ll.mit.edu) 

**RAMS request ID 1022407**

**Overview:**
This is a Singularity container of OmegaFold protein fold prediction tool.

**Citation:** None

**Disclaimer:**
DISTRIBUTION STATEMENT A. Approved for public release. Distribution is unlimited.

This material is based upon work supported by the Department of the Air Force under 
Air Force Contract No. FA8702-15-D-0001. Any opinions, findings, conclusions or 
recommendations expressed in this material are those of the author(s) and do not 
necessarily reflect the views of the Department of the Air Force.

© 2023 Massachusetts Institute of Technology.

Subject to FAR52.227-11 Patent Rights - Ownership by the contractor (May 2014)

The software/firmware is provided to you on an As-Is basis

Delivered to the U.S. Government with Unlimited Rights, as defined in DFARS 
Part 252.227-7013 or 7014 (Feb 2014). Notwithstanding any copyright notice, 
U.S. Government rights in this work are defined by DFARS 252.227-7013 or 
DFARS 252.227-7014 as detailed above. Use of this work other than as specifically 
authorized by the U.S. Government may violate any copyrights that exist in this work.

**To build:** 

          singularity build omega.sif omega.def

          singularity build --sandbox omega omega.def

**To run:**

          singularity run -B io/:/io/ omega.sif /io/hbb_human.fa /io/hbb
