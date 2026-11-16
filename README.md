# Home One

A phone-first Home Assistant dashboard card for one specific home: status at a glance,
the few controls that are actually used, and a live 3D cut-away of the house.

- `dist/home-one-card.js` registers `custom:home-one-card` (use it in a panel view).
- `dist/home-one-scene.js` is the 3D scene, loaded lazily by the card from the same folder.

Built output only. The entity ids and the house model are specific to the author's home,
so this is not a general-purpose card.

Install a specific commit (`version`) when updating; downloading "latest" right after a push can pick up
GitHub's cached copy of the previous files.
