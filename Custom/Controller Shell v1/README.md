The handles are split into two halves. In case you have the old version of the handle (not in the current commit), the `HandleQuickFix` model serves as a glue-in fix for improperly made screw holes.

Depending on the size of screw holes on your MCP23017 chips, you might need to print a few pairs of `MCPScrewFix` to be able to attach them to the M3 screw posts to both sides of the main arduino screw posts and the `HolderHat` (permanent solution pending, that part requires a complete redesign).

The `TPU_Holder` model was made after the fact to cover the back shell's border in order to make it more comfortable when held.

If your hands are relatively small, you might have better off using the controller without handles and instead print two `TPU_Border` to glue to both the top and the bottom halves of the controller shell. Keep in mind to only glue them in the middle area where there are no modules on the frontal part, otherwise you might have issues when removing or placing modules due to a slight overlap used to keep modules more easily secured in place.

`ButtonSupport` is for the Start, Select and Guide buttons in the middle of the controller, as they sit right under the Arduino board and need some support to not apply too much force onto the board itself. It also helps while assembling the device by preventing the buttons from moving once placed.
