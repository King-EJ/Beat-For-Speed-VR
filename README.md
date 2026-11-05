# Beat-For-Speed-VR
VR mod for Beat For Speed



<img width="1145" height="1373" alt="Neon VR Speed Racer" src="https://github.com/user-attachments/assets/bedbb719-7b2b-4a36-b29d-c5b7ee6fca71" />

BEAT FOR SPEED VR  -  VR mod (Unity 6000.3, IL2CPP x64, HDRP, BepInEx 6)
=======================================================================
Version 0.1.4 (test build)

INSTALL
  1. unzip to game folder, only tested with virtual desktop XR
  2. Start your OpenXR runtime first (Virtual Desktop / SteamVR / Quest Link), then the game.
     **: launch option -force-d3d11.**
  

VIEW
  * You ride along with the game's own camera - chase view or the game's first-person view (switch them with the
    game's own camera button). Your view turns with the car, so you always face where it goes; looking around is
    your head. ([View] FollowCameraYaw = false: only big camera cuts turn you.)
  * Menus (the game stops time or shows its mouse cursor): the game's picture on a solid screen in front of you.
    While racing, the HUD (speed, position, lap...) floats in front of you with its black parts see-through.

CONTROLS - the Quest controllers are an Xbox controller for the game (its own gamepad controls)
  Sticks, A / B / X / Y, triggers = LT / RT, grips = LB / RB, stick clicks = L3 / R3
  Right stick UP = view switch (first / third person).
  
  A is always A.
  
  A + B together = Start
  
  X + Y together = Back / View
  
  Both stick clicks: tap = re-centre the view, hold = VR settings menu

  Uses Astien's OpenXR bridge. Free, non-commercial.


