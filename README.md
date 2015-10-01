# bitwig-pickup-controller
Generic controller for Bitwig Studio with rotary knobs and pads used for selecting parameter pages. To avoid parameter jumping rotary knob works in pickup fashion - value is not changed until knob reaches position of the parameter. Difference amount is visually displayed.

Created and tested with AKAI LPD8, but should work for any controller with rotary knobs and pads.

Pressing on a pad selects parameter page for currently selected device. Pressing currently the same pad for second time selects another function. The list of mapped functions:
Pad #1: Parameter Page 1 / Macros (for primary device of the selected track)
Pad #2: Parameter Page 2 / Common parameters
Pad #3: Parameter Page 3 / Envelope parameters
Pad #4: Parameter Page 4 / Macros (for currently selected device)
Pads #5-#8: Parameter page 5-8 / Parameter Page 9-12

Additional feature (works on LPD8 at least) is to light the pad LED for the currently selected Parameter Page.

Manual configuration of the controller is required:
- Pads should be configured with CC values 72 to 79
- Knobs should be configured with CC values 32 to 39

Values can be easily changed in the beginning of the code. 



