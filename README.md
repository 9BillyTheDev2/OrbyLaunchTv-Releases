# OrbyLaunchTv-Releases

Canal public de distribution d’OrbyLaunchTv. Ce dépôt contient uniquement les versions signées et leurs notes de version.

## Publication sécurisée

Une candidate est d’abord construite et testée sur la TV. Elle ne doit pas être publiée dans une Release officielle avant validation. L’application ne consulte que la dernière Release complète de GitHub ; les brouillons et préversions ne déclenchent donc pas de mise à jour.

Chaque Release officielle doit contenir :

- `OrbyLaunchTv.apk` — APK signé ;
- `latest.json` — métadonnées de la version : `versionCode`, `versionName` et empreinte SHA-256 de l’APK.

La Release officielle ne doit pas être marquée comme préversion.
