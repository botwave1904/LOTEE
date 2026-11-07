# LOTEE — one world, two games

Official: https://botwave1904.github.io/LOTEE/

- [Lotería del Horror Moderno 2.0](loteria/) — original 54-card mobile/offline PWA.
- [Nadie Mira Arriba](nadie-mira-arriba/) — single-thread Godot web game and Android debug download.

Card-game rules unchanged. English-first UI with Spanish available through the shared explicit language preference (botwave.language.explicit.v1); old implicit Spanish language settings are ignored while sound/accessibility settings remain. Original card-game licence and font notices retained in loteria/LICENSE and loteria/licenses/. Godot/art/music notices available on the NMA credits page. PWA relative scope ./ under /LOTEE/loteria/; cache namespaced to its scope. Godot is not precached. No touch controls for NMA; keyboard/gamepad required. APK debug/sideload, not a Play Store build.

Deploys via GitHub Actions checkout v6, configure-pages v5, upload-pages-artifact v4, deploy-pages v4; pages/id-token permissions, github-pages environment. No paid dependencies, keys or credentials.
