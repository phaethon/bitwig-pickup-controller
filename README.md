# bitwig-pickup-controller
Generic controller for bitwig with pickup knobs and selection of parameter pages. Created and tested with AKAI LPD8.

Idea of the controller is to have 8 pads to select parameters and then to use knobs to access them. Pads are configured with CC between 72 and 79. Knobs have CC 32 to 39. You can easily change ranges in the code.

Pressing on a pad selects corresponding parameter page. Pressing the same pad second time for pads 1-3 selects another function per list below:
Pad #1: Page 1 / Macros
Pad #2: Page 2 / Common parameters
Pad #3: Page 3 / Envelope parameters
Pads #4-#8: Parameter page 4-8


