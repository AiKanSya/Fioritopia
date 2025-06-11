# 🌸 [UTILITAIRES JS](link)

> 🌺 Objectifs
>
> - [ ] Rassembler les features dans un seul fichier Utils.js

## 🌸 BAS

#### 💮 **utils/Utils.js** :

<details>
  <summary>🍧 Details</summary>

```javascript
sap.ui.define(["sap/m/MessageToast"], function (MessageToast) {
  "use strict";

  return {
    _checkInputValue: function (sId) {
      var input = this.byId(sId);
      var hasValue = Boolean(input.getValue());

      if (!hasValue) {
        var i18nMessage = `error.${sId}`;
        let sMessage = this.getResourceText(i18nMessage);

        MessageToast.show(sMessage);

        input.setValueState("Error");
        jQuery.sap.delayedCall(1, this, function () {
          this.getView().byId(sId).focus();
        });
      } else {
        input.setValueState("None");
      }

      return hasValue;
    },

    _clearInputValue: function (sId) {
      this.byId(sId).setValue("");
    },

    _clearModel: function (model, subModel) {
      var oModel = this.getView().getModel(model || undefined);
      if (oModel) {
        oModel.setProperty(subModel, []);
      }
    },

    _getData: function (oEvent) {
      var oContextEwm = oEvent
        .getParameter("listItem")
        .getBindingContext("whTaskModel");
      return oContextEwm.getObject();
    },

    _getModel: function (model) {
      return this.getView().getModel(model || undefined);
    },

    _getRouter: function () {
      return sap.ui.core.UIComponent.getRouterFor(this);
    },

    _setFocusOn: function (sId) {
      jQuery.sap.delayedCall(1, this, function () {
        this.getView().byId(sId).focus();
      });
    },

    _setVisible: function (sId, status) {
      this.byId(sId).setVisible(status);
    },

    _togglePageBusy: function () {
      var oPage = this.byId("page");
      var bCurrentBusy = oPage.getBusy();
      oPage.setBusy(!bCurrentBusy);
    },
  };
});
```

</details>

#### 💮 **Main.Controller.js** :

<details>
  <summary>🍧 Details</summary>

```javascript
sap.ui.define([
     "stms/app/appslib/utils/utils",
     ...
], function (Utils, ...) {
     "use strict";

     return BaseController.extend("stms.app.appslib.controller.Dashboard", {

          functionName: function () {
			if (!Utils._checkInputValue.call(this, fieldId)) {
				return true;
			}
          }
     })
})
```

</details>
