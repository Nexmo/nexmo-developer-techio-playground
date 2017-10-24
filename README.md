# Nexmo Developer Tech.io Playground

Provides code & tests for interactive runnable examples on Nexmo Developer

## Developing (external contributions)

- Setup a [Tech.io](http://tech.io) account
- Create a Playground
- Select "Custom Template"
- Select "Use Tech.io repository"
- Make a note of the repo URL
- Add your SSH key

```
$ git clone git@github.com:Nexmo/nexmo-developer-techio-playground.git
$ cd nexmo-developer-techio-playground
$ git remote add techio <YOUR_TECHIO_REPO_URL>
$ git push techio
```

## Developing (internal contributions)

- Login to the [Tech.io](http://tech.io) account
- Add your SSH key

```
$ git clone git@github.com:Nexmo/nexmo-developer-techio-playground.git
$ cd nexmo-developer-techio-playground
$ git remote add techio git@ssh.git.tech.io:cg2177040/playground-ltwt8trq.git
$ git push techio
```

> Note: Pushing to this repo will not automatically change the examples as the embed URL changes.

## Add example to Nexmo Developer

Copy the embed code and extract the ID from the `<iframe>` URL. The example can be included using a Nexmo Developer plugin:

For example the following `<iframe>` embed code:

```html
<iframe
  width="100%" frameborder="0" scrolling="no" allowtransparency="true" style="visibility: hidden"
  src="https://tech.io/playground-widget/64ad01e8cd132498ea5d285a161c4c584058/welcome/124979/Send%20an%20SMS"
></iframe>
```

Should be added into a Markdown file in Nexmo Developer as:

````markdown
```techio
title: Send an SMS
path: /64ad01e8cd132498ea5d285a161c4c584058/welcome/124979
```
````

## Contributing

Contributions are welcome, please follow [GitHub Flow](https://guides.github.com/introduction/flow/index.html)

## License

The content of this project itself is licensed under the [Creative Commons Attribution 4.0 International license](https://creativecommons.org/licenses/by/4.0/), and the underlying source code used to format and display that content is licensed under the [MIT license](https://github.com/Nexmo/nexmo-developer/blob/master/LICENSE.txt).
