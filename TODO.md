- [x] make Sniffer ridable
- [x] give Sniffer entity attributes config
- [x] fix ridables around water
- [x] test player ridable underwater
- [ ] OPTIONAL: custom damage type instead of magic for scissors & stone cutter patch
- [x] flip the boolean in the "display names from item forms of entities to entities" patch to keep feature parity with vanilla
- [x] uncomment if conditions when including Pufferfish
- [x] entity attributes patch
  - [x] re-implement options for camel
  - [x] re-implement options for donkey
  - [x] re-implement options for horse
  - [x] re-implement options for llama
  - [x] re-implement options for mule
  - [x] re-implement options for skeleton horse
  - [x] re-implement options for trader llama
  - [x] re-implement options for zombie horse

### once above is complete:
- [ ] make announcement about changes
  - flipped defaults ("persistent-droppable-entity-display-names", "set-name-visible-when-placing-with-custom-name")
  - must disable `ridable-settings.use-dismounts-underwater-tag` for `<Mob>RidableInWater` options to work, updated default values to reflect `DISMOUNTS_UNDERWATER` tag.
  - `gameplay-mechanics.player.ridable-in-water` completely ignores `DISMOUNTS_UNDERWATER` tag since you can't ride players in vanilla minecraft.
