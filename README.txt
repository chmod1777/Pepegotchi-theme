Pepe the Frog Theme for Pwnagotchi
==================================

Generated Pepe faces matching the standard pwnagotchi expressions.
All images are 128x64 PNG with high-contrast black line art on transparent/white background, optimized for e-ink displays.

Required files (all present):
LOOK_R.png, LOOK_L.png, LOOK_R_HAPPY.png, LOOK_L_HAPPY.png,
SLEEP.png, SLEEP2.png, AWAKE.png, BORED.png, INTENSE.png, COOL.png,
HAPPY.png, GRATEFUL.png, EXCITED.png, MOTIVATED.png, DEMOTIVATED.png,
SMART.png, LONELY.png, SAD.png, ANGRY.png, FRIEND.png, BROKEN.png,
DEBUG.png, UPLOAD.png, UPLOAD1.png, UPLOAD2.png

Installation (using Custom Faces Mod - https://github.com/roodriiigooo/PWNAGOTCHI-CUSTOM-FACES-MOD):

1. Create folder on your Pwnagotchi:
   sudo mkdir -p /custom-faces

2. Copy all PNG files into /custom-faces/

3. Edit /etc/pwnagotchi/config.toml and add/replace the faces section with:

ui.faces.look_r = "/custom-faces/LOOK_R.png"
ui.faces.look_l = "/custom-faces/LOOK_L.png"
ui.faces.look_r_happy = "/custom-faces/LOOK_R_HAPPY.png"
ui.faces.look_l_happy = "/custom-faces/LOOK_L_HAPPY.png"
ui.faces.sleep = "/custom-faces/SLEEP.png"
ui.faces.sleep2 = "/custom-faces/SLEEP2.png"
ui.faces.awake = "/custom-faces/AWAKE.png"
ui.faces.bored = "/custom-faces/BORED.png"
ui.faces.intense = "/custom-faces/INTENSE.png"
ui.faces.cool = "/custom-faces/COOL.png"
ui.faces.happy = "/custom-faces/HAPPY.png"
ui.faces.excited = "/custom-faces/EXCITED.png"
ui.faces.grateful = "/custom-faces/GRATEFUL.png"
ui.faces.motivated = "/custom-faces/MOTIVATED.png"
ui.faces.demotivated = "/custom-faces/DEMOTIVATED.png"
ui.faces.smart = "/custom-faces/SMART.png"
ui.faces.lonely = "/custom-faces/LONELY.png"
ui.faces.sad = "/custom-faces/SAD.png"
ui.faces.angry = "/custom-faces/ANGRY.png"
ui.faces.friend = "/custom-faces/FRIEND.png"
ui.faces.broken = "/custom-faces/BROKEN.png"
ui.faces.debug = "/custom-faces/DEBUG.png"
ui.faces.upload = "/custom-faces/UPLOAD.png"
ui.faces.upload1 = "/custom-faces/UPLOAD1.png"
ui.faces.upload2 = "/custom-faces/UPLOAD2.png"
ui.faces.png = true
ui.faces.position_x = 0
ui.faces.position_y = 34

4. Restart:
   sudo systemctl restart pwnagotchi

Adjust position_x / position_y as needed for your display.
If faces are too big/small, resize the PNGs further.
For older Pwnagotchi versions, you may need the full Custom Faces Mod code changes.
