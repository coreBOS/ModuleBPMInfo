# BPM Process Flow More Information modules

This module is part of the BPM perspective and serves to save a set of additional information that must be given to go from one step to the next.

This module is a template upon which other information modules may be created. The purpose of this module is to hold fields with additional information that is necessary when going through the steps of a business process. In other words, when a record must transition from one step to another it may be required to ask for a set of additional information. This information will be saved in this module.

For example, if we have a business process on the Potentials module, and we need to ask for some fields when the opportunity transitions to closed-won, we can use this module either "as is" or change its' name to `PotentialsBPMInfo` (or anything else) and add the fields we need to capture. Then, we can use the [Process Step Information module](https://github.com/coreBOS/cbProcessInfo) and the master-detail, field dependency and validation maps to configure a popup screen that will be presented to the user when he tries to set the potential record to closed-won.

You can find some additional information in the [Process Flow Perspective](https://github.com/coreBOS/ProcessFlowPerspective).
