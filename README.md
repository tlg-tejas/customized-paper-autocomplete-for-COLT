# tlg-paper-autosuggest

This repo has custom autosuggest used for cities and airport autosuggest for TLG

## Running the tutorial code

You'll need to install some command-line tools to manage dependencies and to run the demo.

1.  Download and install Node version 6.x or 7.x from [https://nodejs.org/](https://nodejs.org/). Node includes the node package manager command, `npm`.

2.  Install `bower` and the Polymer CLI:

        npm install -g bower polymer-cli
        
3.  Change directory to your local repo and install dependencies with `bower`:

        cd tlg-paper-autosuggest
        bower install
        
5.  To preview your element, run the Polymer development server from the repo directory:

        polymer serve
        
    Open `localhost:8080/components/tlg-paper-autosuggest/demo/` in your browser. (Note that the path uses `tlg-paper-autosuggest`—the 
    component name listed in this element's `bower.json` file—rather than the actual directory name.) 
