# APEX Cloud User Doc Repository

This is a documentation repository for APEX Cloud, written for Documentation Portal, using [docsify](https://docsify.js.org/#/). You can find out what docsify or markdown extensions are supported [here](https://stg.docs.developer.gov.sg/docs/public/238425294/doc-portal-publisher-guide/#/).

> The repository is currently in active development and  contents will change rapidly.

## File Structure

For the repository in particular, we will only use the **files** folder to store any asset (docs, pdf, images). it will produce a url like this:

> {domain}/files/{file-name}.{file-extension}
> e.g.
> http://localhost:3000/files/sample.pdf
> https://docs.developer.tech.gov.sg/docs/apex-cloud-assets/files/sample.pdf

## Running Locally

### Setting Up

- Install docsify cli `npm -g install docsify-cli`
- Download this repository via `git clone`
- Run `docsify serve .`

### Syntax Highlighting

The repository has been pre-configured to pull in the default Developer Portal's styling for Documentations. (See [index.html](./index.html))

## Web Hosting

By default, once you commit and push any changes into github, the contents will be updated automatically. 

## Contributing

Please fork the repository, make your changes and submit a Pull Request.
