# qb-notify-css-edit

![image](https://user-images.githubusercontent.com/28671568/207623528-f8b72852-e741-4156-a8d3-927ef1fc4f12.png)
![image](https://user-images.githubusercontent.com/28671568/207623670-9787e50a-361b-42fa-b22e-3e3d56aff756.png)

So i changed up the qb notify a little/

go to : qb-core\html\css and you will see a style file. You can download my version and you need to replace that file.

Then you will need to go to qb-core\html\js and open the testing.js file. and change this

```export const BrowserMockConfigData = {
  NotificationStyling: {
    group: true,
    position: "top-right",
    progress: true,
  },
  VariantDefinitions: {
    success: {
      classes: "success",
      icon: "done",
    },
    primary: {
      classes: "primary",
      icon: "info",
    },
    error: {
      classes: "error",
      icon: "dangerous",
    },
    police: {
      classes: "police",
      icon: "local_police",
    },
    ambulance: {
      classes: "ambulance",
      icon: "fas fa-ambulance",
    },
  },
};
```

To this:
```
export const BrowserMockConfigData = {
  NotificationStyling: {
    group: true,
    position: "top-right",
    progress: true,
  },
  VariantDefinitions: {
    success: {
      classes: "success",
    },
    primary: {
      classes: "primary",
    },
    error: {
      classes: "error",
    },
    police: {
      classes: "police",
    },
    ambulance: {
      classes: "ambulance",
    },
  },
};
```

No Support Anymore!
