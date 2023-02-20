📢 Use this project, [contribute](https://github.com/{OrganizationName}/{AppName}) to it or open issues to help evolve it using [Store Discussion](https://github.com/vtex-apps/store-discussion).

# PDF Reader

![All Contributors](https://img.shields.io/badge/all_contributors-1-orange.svg?style=flat-square)

The pdf-reader component allows you to view pdf-type documents so that they can be read on the page where it is invoked.

![image](https://user-images.githubusercontent.com/90701896/220186277-e72da22c-e283-4fa3-a1be-474aca5574ee.png)

## Configuration 

1. Import the Bullet pdf-reader's app to your theme's dependencies in the manifest.json, for example:
```json
  dependencies: {
    "{vendor}.pdf-reader": "0.x"
  }
 ```
 
 2. Add the pdf-reader block to the store-theme. For example:
```json
  "flex-layout.col#component--pdf-reader":{
    "children": [
      "pdf-reader"
    ]
  },
  "pdf-reader":{
    "props": {
      "pdfUrl":"assets/documents/samplePDF.pdf" ,
      "width": "100%",
      "height":"800"
    }
  }
   ```
| Block name     | Description                                     |
| -------------- | ----------------------------------------------- |
| `pdf-reader` | ![https://img.shields.io/badge/-Mandatory-red](https://img.shields.io/badge/-Mandatory-red)  Top level block that must be declared in the store-theme block to render a default pdf reader viewer.   |

### Pdf-reader props

| Prop name    | Type            | Description    | Default value                                                                                                                               |
| ------------ | --------------- | --------------------------------------------------------------------- | ---------- | 
| `pdfUrl`        | `string`       |  Define the url to render in the pdf-reader file       | `undefined`              |
| `width`        | `number`       | Define the width  to render pdf-reader apps      | `undefined`              |
| `height`        | `number`       | Define the height to render pdf-reader apps         | `undefined`              |

## Customization

No CSS Handles are available yet for the app customization.

## Contributors

Thanks goes to these wonderful people:

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind are welcome!

---- 

Check out some documentation models that are already live: 
- [Breadcrumb](https://github.com/vtex-apps/breadcrumb)
- [Image](https://vtex.io/docs/components/general/vtex.store-components/image)
- [Condition Layout](https://vtex.io/docs/components/all/vtex.condition-layout@1.1.6/)
- [Add To Cart Button](https://vtex.io/docs/components/content-blocks/vtex.add-to-cart-button@0.9.0/)
- [Store Form](https://vtex.io/docs/components/all/vtex.store-form@0.3.4/)