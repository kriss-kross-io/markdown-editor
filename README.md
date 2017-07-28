# \<markdown-editor\>

## Installation

``` bash
bower install markdown-editor --save
```

## Usage

``` html
<link rel="import" href="bower_components/markdown-editor/markdown-editor.html">

<markdown-editor
    markdown="> **Markdown** is _awesome_!"
    placeholder-text="Type here"
    preview></markdown-editor>
```

## Setup

### Prerequisites

Install [npm](https://www.npmjs.com/) (or install [Node](https://nodejs.org/en/download/)):

``` bash
curl -L https://www.npmjs.com/install.sh | sh
```

Install [bower](https://bower.io/):

``` bash
npm install -g bower
```

### Tools

Install [polymer-cli](https://github.com/Polymer/polymer-cli):

``` bash
npm install -g polymer-cli
```

### Start the development server

This command serves the app at `http://localhost:8080/components/markdown-editor/` and provides basic URL
routing for the app:

``` bash
polymer serve
```
