# Udagram Image Filtering Microservice


### Setup Node Environment

You'll need to create a new node server. Open a new terminal within the project directory and run:

1. Initialize a new project: `npm i`
2. run the development server with `npm run dev`



### Create a new endpoint in the server.ts file

The starter code has a task for you to complete an endpoint in `./src/server.ts` which uses query parameter to download an image from a public URL, filter the image, and return the result.

We've included a few helper functions to handle some of these concepts and we're importing it for you at the top of the `./src/server.ts`  file.

```typescript
import {filterImageFromURL, deleteLocalFiles} from './util/util';
```

### Deploying your system

`eb init` -> a new application 

`eb create` a new environment to deploy your image-filter service! 

You can use `eb deploy` to push changes.


For test in EB can use: 

`EB_URL` = image-filter-starter-code-dev2.us-east-2.elasticbeanstalk.com

 

`http://{{EB_URL}}/filteredimage?image_url=https://sm.ign.com/t/ign_br/cover/n/naruto-shi/naruto-shippuden_yj88.128.jpg`

