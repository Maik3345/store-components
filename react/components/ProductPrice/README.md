# Product details

Oie! These are our product detail components.

## Installation

To install this component, you have two ways. Follow the instructions bellow. 

You can install in your workspace and promote to master. 

`vtex install vtex.storecomponents`

Or you can add into the dependencies of your `manifest.json` and use like a npm module. 

And to import it in your code: 

```js
import Price from 'vtex.storecomponents/Price'
```

## Usage

You can use in your code like a React component with the jsx tag: `<ProductPrice />`. See an example at [Product Summary](https://github.com/vtex-apps/product-summary/blob/master/react/ProductSummary.js#L84) app

| Prop name          | Type      | Description                                                                 |
| ------------------ | --------- | --------------------------------------------------------------------------- |
| `sellingPrice`     | `Number!` | Product selling price                                                       |
| `listPrice`        | `Number!` | Product list price                                                          |
| `showListPrice`    | `Boolean` | Determines if the list price is shown or not                                |
| `showLabels`       | `Boolean` | Determines if the labels are shown. If false, only the values will be shown |
| `showInstallments` | `Boolean` | Determines if the installments are shown                                    |
| `installments`     | `Number`  | Available number of installments                                            |
| `installmentPrice` | `Number`  | Single installment price                                                    |
