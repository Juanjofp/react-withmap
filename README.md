# Description
Need to wrap any component inside react with google maps api, I've recopiled the scripts from https://github.com/fullstackreact/google-maps-react. This scripts are very well explained here https://www.fullstackreact.com/articles/how-to-write-a-google-maps-react-component/

This module just wrap a react component and inject the map object from google api as a prop into it.

All the merits are for [fullstackreact](https://www.fullstackreact.com/articles/how-to-write-a-google-maps-react-component/) who are the creators of the scripts.

# Install
```
yarn add withMap
```

# Usage
```
import { withMap } from 'react-withmap';

export default withMap({ apiKey: 'apikeyfromgooglemaps' })(AnyReactComponent);
```