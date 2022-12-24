# Github Repos Searcher
- Github Repos Searcher is a npm package where you can fetch repository detail of any developer by their username 

## Examples

```
const { getRepos } = require('github-repos-searcher');
getRepos({username: 'gaearon'}).then((repositories) => console.log(repositories));

```

