<h1 align="center">Nudebt-Email-Reporter-Node</h1>

```
$ git clone git@code.spritle.com:freshdesk/nudebt-email-reporter-node.git
$ cd nudebt-email-reporter-node

```

Change the lastid.json file with single ticket id from which ticket this application has to fetch ticket during its first run.

```
$ yarn install
$ node app

```
#### Note:Dont run this application using nodemon or any filewatcher. (since lastid.json file is keepon updated it will restart the application before task is completed)
