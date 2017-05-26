abc

```jsimport React, { PropTypes, Component } from 'react';
import { Components, withList, withCurrentUser, Loading } from 'meteor/vulcan:core';

import Movies from '../../modules/movies/collection.js';
import MoviesItem from './MoviesItem.jsx';

const MoviesList = ({results = [], currentUser, loading, loadMore, count, totalCount}) => 
  
  ...

const options = {
  collection: Movies,
  fragmentName: 'MoviesItemFragment',
  limit: 5
};

export default withList(options)(withCurrentUser(MoviesList))
```

```js import React, { PropTypes, Component } from 'react';
import { Components, withList, withCurrentUser, Loading } from 'meteor/vulcan:core';

import Movies from '../../modules/movies/collection.js';
import MoviesItem from './MoviesItem.jsx';

const MoviesList = ({results = [], currentUser, loading, loadMore, count, totalCount}) => 
  
  ...

const options = {
  collection: Movies,
  fragmentName: 'MoviesItemFragment',
  limit: 5
};

export default withList(options)(withCurrentUser(MoviesList))
```
