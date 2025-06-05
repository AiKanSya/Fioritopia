# 🌸 [FORCER UNE VERSION UI5 SUR UNE APP CLOUD FOUNDRY](link)

> 🌺 Objectifs
>
> - [ ] Forcer une version UI5 (i.e 1.124.2) d'une tuile Cloud Foundry

## 🌸 BAS

#### 💮 **index.html** :

```html
src="https://ui5.sap.com/1.124.2/resources/sap-ui-core.js"
```

<details>
  <summary>Details</summary>

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Gestion Avis</title>
    <script
      id="sap-ui-bootstrap"
      src="https://ui5.sap.com/1.124.2/resources/sap-ui-core.js"
      data-sap-ui-theme="sap_horizon"
      data-sap-ui-resourceroots='{"delpeyrat.pm.gestionavis": "./"}'
      data-sap-ui-compatVersion="edge"
      data-sap-ui-oninit="module:sap/ui/core/ComponentSupport"
      data-sap-ui-async="true"
      data-sap-ui-preload="async"
      data-sap-ui-frameOptions="trusted"
    ></script>
  </head>
  <body class="sapUiBody">
    <div
      data-sap-ui-component
      data-name="delpeyrat.pm.gestionavis"
      data-id="container"
      data-settings='{"id" : "listenotif"}'
    ></div>
  </body>
</html>
```

</details>

#### 💮 **manifest.json** :

```json
"sap.platform.cf": {
     "ui5VersionNumber": "1.124.2"
},
```

```json
"sap.ui5": {
     "dependencies": {
          "minUI5Version": "1.124.2",
     }
}
```

<details>
  <summary>Details</summary>

```json
    "sap.platform.cf": {
        "ui5VersionNumber": "1.124.2"
    },
    "sap.ui5": {
        "flexEnabled": false,
        "rootView": {
            "viewName": "delpeyrat.pm.gestionavis.view.Root",
            "type": "XML"
        },
        "dependencies": {
            "minUI5Version": "1.124.2",
            "libs": {
                "sap.ui.core": {},
                "sap.m": {},
                "sap.ui.layout": {},
                "sap.f": {},
                "sap.suite.ui.generic.template": {},
                "sap.ui.comp": {},
                "sap.ui.generic.app": {},
                "sap.ui.table": {},
                "sap.ushell": {}
            }
        },
```

</details>

## 🌸 BUILD & DEPLOY

#### 💮 **Build** :

```
Build MTA Project
```

#### 💮 **Deploy** :

```
Deploy MTA Archives
```

## 🌸 LAUNCHPAD CONTENT MANAGER (DEV || QUAL || PROD || INT)

#### 💮 **Gestionnaire de contenu/app/Configuration** :

Parameter Name:

```
sap-ui-version
```

Parameter Value:

```
1.124.2
```

<details>
  <summary>Details</summary>

![](./assets/Capture%20d’écran%202025-06-05%20103240.png)

</details>
