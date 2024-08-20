# collaborative-code-editor

Collaborative Text Editor example with selection synchronization, active user display, and real time text collaboration using ShareDB. The purpose of this repo is to give a basic example setup for [ShareDB](https://github.com/share/sharedb) with an [Ace Editor](https://github.com/ajaxorg/ace) [client](/clients/ace-editor.html) and [Code-Mirror](https://codemirror.net/) [client](/clients/code-mirror.html).

## Details

Because ShareDB requires precompiling source to load, a pre-built version of sharedb is copied from [this repo](https://github.com/gkjohnson/sharedb-builds).

## How To Run

Run `npm install`.

Then `npm start`.

A static file server will start on port `80`, and the ShareDB connection on port `8080`. Load up `http://localhost/clients/ace-editor.html` or `http://localhost/clients/code-mirror.html` to get collaborating!
