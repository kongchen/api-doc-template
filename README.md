Api Document Template
================
The templates are [mustache](http://mustache.github.io/) templates to generate RESTful API Document with the help of [Swagger](https://github.com/wordnik/swagger-core/wiki),
they're used by:

- [swagger maven plugin](https://github.com/kongchen/swagger-maven-plugin), *a maven plugin*
  >can help you generate swagger API document during build phase using these templates.

- [haohao](https://github.com/kongchen/haohao), *a command line tool*
  > can help you generate swagger API document using these template as well as any request & response samples for any of your API operations.

There're 5 templates by now:

1. [wiki.mustache](https://github.com/kongchen/api-doc-template/blob/master/v1.1/wiki.mustache) for [Confluence](http://en.wikipedia.org/wiki/Confluence_(software\)) wiki markup output.
   
2. [wiki-new.mustache](https://github.com/kongchen/api-doc-template/blob/master/v1.1/wiki-new.mustache) another [Confluence](http://en.wikipedia.org/wiki/Confluence_(software\)) wiki markup template.
 
3. [html.mustache](https://github.com/kongchen/api-doc-template/blob/master/v1.1/html.mustache) for html output, [click here](http://htmlpreview.github.io/?https://raw.github.com/kongchen/swagger-maven-plugin/master/GeneratedSamples/apidoc.html) to see a sample output.
 
4. [markdown.mustache](https://github.com/kongchen/api-doc-template/blob/master/v1.1/markdown.mustache) for markdown output, [click here](https://github.com/kongchen/swagger-maven-plugin/wiki/Sample.markdown) to see a sample output.

5. [strapdown.html.mustache](https://github.com/kongchen/api-doc-template/blob/master/v1.1/strapdown.html.mustache) for HTML output, [click here](http://htmlpreview.github.io/?https://raw.github.com/kongchen/swagger-maven-plugin/master/GeneratedSamples/apidoc.strapdown.html) to see a sample output.
    
    >This template actually uses [markdown.mustache](https://github.com/kongchen/api-doc-template/blob/master/v1.1/markdown.mustache) but generates HTML with the help of [Strapdown.js](http://strapdownjs.com/)


# **Welcome to pull new document templates**

If you dissatisfy these templates, write your own and do not foget to [**pull**](https://github.com/kongchen/api-doc-template/pulls)

[Click here](https://github.com/kongchen/api-doc-template/blob/master/template-schema-1.1.json) to see the json schema of the data the template consumes.


