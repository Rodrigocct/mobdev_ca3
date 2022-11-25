Assessment Task: Mobile Development

You are required to build an Ionic application that can consume Breaking Bad API
https://breakingbadapi.com and display the data in 4 tabs – Characters, Episodes, Quotes, Death
Count. Complete the following steps in order to produce a working Breaking Bad Fandom application:
npm i -g @ionic/cli
ionic start mobdev_ca3 blank --type=angular
cd ./mobdev_ca3
ionic serve
ionic g page pages/tab
ionic g page pages/characters
ionic g page pages/characters-details
ionic g page pages/episodes
ionic g page pages/episodes-details
ionic g page pages/quotes
ionic g page pages/death-count

Set up the environment: utilise GitPod scripting to automatically pre-install Ionic and
Angular CLI, install modules and plugins, generate the required pages and service(s).

Pre-install ionic and Angular
-tasks:
  - name: Install Ionic & Angular CLI
    command: npm i -D -E @angular/cli  && npx --yes ionic serve (GitHub Docs, 2022)
-Creating services
ionic g service services/api

 Set up the core app aspects: routing, tabs and introduce a Back-Navigation
functionality for all the required tab subpages (Characters and Episodes).

-To complete this task I have updated the file characters.page.ts and characters page.html respectively as well as the details. 

Consume API data: use Observables, ngFor and ngIf logic provided by Angular.

-at this point I first edited the file api.services.ts and also added the required code on each page.ts file. 

Improve the design: change the default Ionic UI, theming & CSS variables and
showcase the ability to use appropriate Ionic Icons for the tabs.

-to update the Ionic icons I simply edited the .html files from each page  and made some basic color changes by accessing on the folder theme on the file variables.scss

Possess a coherent commit history on GitHub (at least 8 valid and logical commits) and
have your final submission code present in your Git repository. Your GitHub repo containing
the full Ionic project must be called – mobdev_ca3. Also reference here any solution or code
from someone else that you used in your CA by providing links to the original materials either
in Dockerfile comments or inside README.md file.

Record a voiced-over video screencast in MP4 format (10 minutes max) showing how
your app works and how exactly you decided to go about making it.





https://github.com/Rodrigocct/mobdev_ca3
 video link goes here





Bibliography

I consume the API from this link https://breakingbadapi.com 
The icons are from https://ionic.io/ionicons

GitHub Docs, 2022. Quickstart for GitHub Actions - GitHub Docs. [Online] Available at: https://docs.github.com/en/actions/quickstart [Accessed 23 November 2022].



