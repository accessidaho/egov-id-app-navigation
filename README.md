# \<ip-app-navigation\>

Idaho application navigation element

## Installation

Add the following to bower.json.

```JSON
{
  "id-app-navigation": "https://github.com/accessidaho/egov-id-app-navigation.git"
}
```

## Usage

Import the element:

```html
<link rel="import" href="bower_components/id-app-navigation/id-app-navigation.html">
```

Add the element and set properties:

```html
<id-app-navigation
  page="{{page}}"
  items="[{id: 'view1', url: '/#/view1', title: 'DataTable'}]"
  tabbed
  wizard>
</id-app-navigation>
```

## Styling

`<id-alert>` provides the following custom properties for styling:

Custom property | Description | Default
----------------|-------------|----------
`--id-mobile-navigation-height` | Minimum height of mobile navigation | 500px
`--id-primary-border` | Default border color | #255dab
`--id-primary-color` | Default background color | #2968c0
`--id-primary-border-hover` | Default border color on hover | #1a4179
`--id-primary-color-hover` | Default background color on hover | #205196
`--id-link-color` | Default link color | #0027c1
`--id-link-color-hover` | Default link color on hover | #001875
