# Github Repos Searcher
- Github Repos Searcher is a npm package where you can fetch repository detail of any developer by their username 


##Installation 

```js
# using npm
npm install github-repos-search

# using yarn
yarn add github-repos-search
```

## Uses

```js
const { getRepos } = require('github-repo-searcher');
getRepos({username: 'gaearon'}).then((repositories) => console.log(repositories));

```

