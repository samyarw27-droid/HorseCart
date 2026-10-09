HorseCart  (Paper / Purpur 1.21.x, Java 21)

BUILD:   mvn clean package        -> target/HorseCart-1.0.0.jar
INSTALL: copy the jar into your server's plugins/ folder and restart.

GET A CART: craft it  (P C P / I _ I : planks, chest, iron ingots)  or  /horsecart give
USE:
  Place the item on the ground.
  Right-click cart with a Lead  -> hitch nearest tamed horse (or the one you're riding). Again -> unhitch.
  Ride the horse; the cart follows behind it.
  Right-click cart              -> sit (2 seats)
  Sneak + right-click cart      -> storage (27 slots)
  Hit the cart until it breaks  -> items + cart drop.

RESOURCE PACK:
  Put your pack's direct download URL in plugins/HorseCart/config.yml (resource-pack.url), then /horsecart reload.
  /horsecart pack  -> shows a clickable download link to any player.
  send-link-on-join: link shown on join.   auto-apply: client is asked to install the pack automatically.
