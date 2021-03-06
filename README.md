# react-nest-menu

## Installation

``` shell
npm install --save react-nest-menu
```
#### ![#f03c15](https://placehold.it/15/f03c15/000000?text=+) `Not push to npm yet.`


## Import
```js
import Menu, {  SubMenu , RightSubMenu, MenuItem} from 'react-nest-menu';
```

## Usage

```jsx
ReactDOM.render(<Menu>
    <MenuItem>1</MenuItem>
    <RightSubMenu title="2">
        <SubMenu title="2-1">
            <MenuItem>2</MenuItem>
        </SubMenu>
    </RightSubMenu>
</Menu>, container);
```

## API

### Menu props

<table class="table table-bordered table-striped">
    <thead>
    <tr>
        <th style="width: 100px;">name</th>
        <th style="width: 150px;">type</th>
        <th style="width: 100px;">default</th>
        <th>description</th>
    </tr>
    </thead>
    <tbody>
        <tr>
          <td>className</td>
          <td>String</td>
          <td></td>
          <td>additional css class of root dom node</td>
        </tr>
        <tr>
          <td>width</td>
          <td>String</td>
          <td>150px</td>
          <td>allow user setting width</td>
        </tr>
        <tr>
          <td>maxHeight</td>
          <td>String</td>
          <td></td>
          <td>allow user setting maxHeight.</td>
        </tr>
        <tr>
          <td>onClick</td>
          <td>function</td>
          <td></td>
          <td>called when click a menu item</td>
        </tr>
    </tbody>
</table>

### Menu.SubMenu & Menu.RightSubMenu props

<table class="table table-bordered table-striped">
    <thead>
    <tr>
        <th style="width: 100px;">name</th>
        <th style="width: 150px;">type</th>
        <th style="width: 100px;">default</th>
        <th>description</th>
    </tr>
    </thead>
    <tbody>
        <tr>
          <td>title</td>
          <td>String</td>
          <td></td>
          <td>sub menu's content</td>
        </tr>
    </tbody>
</table>

### Menu.MenuItem props

<table class="table table-bordered table-striped">
    <thead>
    <tr>
        <th style="width: 100px;">name</th>
        <th style="width: 150px;">type</th>
        <th style="width: 100px;">default</th>
        <th>description</th>
    </tr>
    </thead>
    <tbody>
        <tr>
          <td>onClick</td>
          <td>Function</td>
          <td></td>
          <td>called when click a menu item</td>
        </tr>
    </tbody>
</table>


## License

react-nest-menu is released under the MIT license.
