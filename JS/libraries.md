# react-typeahead

<p>used for filtering</p>

### Installation

```
npm install --save react-bootstrap-typeahead
```

or

```
yarn add react-bootstrap-typeahead
```

## usage

### Initialize

```
import { Typeahead } from 'react-bootstrap-typeahead'; // ES2015
var Typeahead = require('react-bootstrap-typeahead').Typeahead; // CommonJS
```


### search by passing function
```
<Typeahead
  labelKey={option => `${option.firstName} ${option.lastName}`}
  options={[
    {firstName: 'Art', lastName: 'Blakey'},
    {firstName: 'Jimmy', lastName: 'Cobb'},
    {firstName: 'Elvin', lastName: 'Jones'},
    {firstName: 'Max', lastName: 'Roach'},
    {firstName: 'Tony', lastName: 'Williams'},
  ]}
/>
```