# Tokyo60 & Hasu HHKB firmware
My custom tokyo60 and Hasu HHKB firmware

* The `json` file contain the keymap in plaintext   
* The `hex` file contain the keymap in firmware form which can be uploaded to the board directly

Using this keymap the tokyo60 can be set into bootloader (DFU) mode using `MO(2)` + `j`
Since the HHKB uses a custom controller it has to be set into bootloader (DFU) mode using the red switch located on the backside.

The underglow (if applicable) can be changed using the following combinations
* `MO(2)` + `q` selects the previous underglow mode
* `MO(2)` + `w` toggles the underglow on or off
* `MO(2)` + `e` selects the next underglow mode

# Tokyo60 & Hasu HHKB layout
The HHKB uses an "invisible" 7th layer to simulate `Esc/~`. This layer is activated using `Left shift` or `Right shift` 

##### Layer 1
![layer 1][layer1]
##### Layer 2
![layer 2][layer2]
##### Layer 3
![layer 3][layer3]

[layer1]: images/layer1.png "Layer 1"
[layer2]: images/layer2.png "Layer 2"
[layer3]: images/layer3.png "Layer 3"