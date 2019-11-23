Snippets I use for modern React components with Typescript and styled components.

## How to use:
1) Copy snippets from `snippets.json` to clipboard
2) https://code.visualstudio.com/docs/editor/userdefinedsnippets#_create-your-own-snippets


## Examples:

Type `rct` and hit `TAB` key:

```
import React from 'react';
import styled from 'styled-components';

interface [NAME_OF_FILE]Props {

}

const [NAME_OF_FILE] = ({}: [NAME_OF_FILE]Props) => {
   
    return (
      <div>
        
      </div>
    );
  }

export default [NAME_OF_FILE];
```


Type `scgrid` and hit `TAB` key:

```
const Grid = styled.div`
  display: grid;
  grid-template-columns: (3, 1fr);
`
```