# Horus_Browser

#### REQUIRED

- [x] Develop a private search engine powered by [DuckDuckGo](https://duckduckgo.com/).
  - [x] Private search engine should not collect data from user.
- [x] Search engine should be hosted on a server owned by developer.
  - [x] Hosted by: [DigitalOcean - Cloud computing company](https://www.digitalocean.com/)

#### BONUS

- [x] Create a secondary Navigation bar for search engine website.
  - [ ] Implement functionality to secondary navigation bar.

### App Walkthough GIF

- [x] https://gyazo.com/3af3e279d5653944242950472824b793

## Steps to build

### Create your front end and backend code using HTML for webpage and Javascript.
1) Develop HTML website to host the search browser. 
2) Use Javascript as the backened connecting to the [DuckDuckGo](https://duckduckgo.com/) services.

### Create your Database through DigitalOcean
1) Setup an account with [DigitalOcean - Cloud computing company](https://www.digitalocean.com/) to host the server for the website.
2) Create a database using the DigitalOcean components services.

### Create your Registry through DigitalOcean
1) Create a Registry in the control panel of Ocean Digital.
2) Install "doct1" and authenticate it with an API token.
3) Use the "registry create" command to create your registry: "doct1 registry create <my-registry-name>".
  
### Push to your Registry
1) Install "doct1" and authenticate it with an API token.
2) Use the registry login command to authentiacte Docker with your registry: "doct1 registry login"
3) Use the "docker tag" command to tag your image with the fully qualified destination path: "docker tag <my-image> registry.digitalocean.com/<my-registry>/<my-image>
4) Use the "docker push" command to upload your image: "docker push registry.digitalocean.com/<my-registry>/<my-image>"

## Open-source libraries used
- [duckduckgo privacy extension](https://github.com/duckduckgo/duckduckgo-privacy-extension) - DuckDuckGo privacy Essentials browser extension for Edge, Firefox, and Chrome.

## Setup & Use Options

### Option 1 - Use the website.
Go to the website [here](https://horus-browser-878fk.ondigitalocean.app/horusbrowser)

### Option 2 - VSCode server extension.
1) Clone the repository using [Git](https://git-scm.com/).
2) Open the project up in [VSCode](https://code.visualstudio.com/).
3) Install the [Live Extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension to the editor.
4) Press the "Go Live" button in the bottom, right-hand corner of your editor.
