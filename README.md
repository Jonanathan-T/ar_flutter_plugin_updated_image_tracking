### 📦 `ar_flutter_plugin_updated_image_tracking`

**Fork amélioré de `ar_flutter_plugin_updated` (lui-même une adaptation directe du plugin `ar_flutter_plugin`) intégrant la reconnaissance d'image (image tracking) en réalité augmentée.**

Ce plugin Flutter permet d'afficher automatiquement un modèle 3D (`.glb`/`.gltf`) lorsqu'une image cible est reconnue via la caméra, en s'appuyant sur ARCore pour Android.
Fonctionnalité ajoutée :
✅ **Reconnaissance d'image** avec déclenchement automatique de l'affichage d'un objet 3D à la détection de l'image cible.

---

### 🔧 Fonctionnalités principales

* Intégration Flutter avec ARCore (Android)
* Affichage d'objets 3D (.glb, .gltf)
* **Nouvelle fonctionnalité : image tracking (suivi d'image)**
* Affichage automatique du contenu AR lors de la détection d’une image cible

---

## 📥 Installation

### 1. Ajouter le plugin via GitHub dans `pubspec.yaml` :

```yaml
dependencies:
  ar_flutter_plugin_updated_image_tracking:
    git:
      url: https://github.com/Jonanathan-T/ar_flutter_plugin_updated_image_tracking.git
````

### 2. Ajouter les permissions Android requises

Dans `android/app/src/main/AndroidManifest.xml` :

```xml
<uses-permission android:name="android.permission.CAMERA"/>
<uses-feature android:name="android.hardware.camera.ar" android:required="true"/>

```


### 📚 Basé sur

* [`ar_flutter_plugin`](https://pub.dev/packages/ar_flutter_plugin)
* [`ar_flutter_plugin_updated`](https://github.com/HotReload1/ar_flutter_plugin_updated)

---

## 📄 Licence

Ce projet est sous licence MIT — voir le fichier [LICENSE](LICENSE) pour plus de détails.

---

## 🙌 Contribuer

Les contributions sont les bienvenues ! Si vous trouvez un bug ou souhaitez proposer une amélioration, ouvrez une issue ou une pull request.

