# Github Repos Searcher
- Github Repos Searcher is a npm package where you can fetch repository detail of any developer by their username 


##Installation 

```js
# using npm
npm install github-repo-searcher

# using yarn
yarn add github-repo-searcher
```

## Usage

```js
const { getRepos } = require('github-repo-searcher');
getRepos({username: 'gaearon'}).then((repositories) => console.log(repositories));

```

