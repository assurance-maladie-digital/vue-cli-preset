# Contributing

First off, thanks for taking the time to contribute! This is really important to help us improve the library.

## Report bugs

Bugs are reported using [GitHub issues](https://guides.github.com/features/issues/).

Before creating a new issue, [check if your bug hasn't already been reported](https://github.com/assurance-maladie-digital/vue-cli-preset/issues?utf8=%E2%9C%93&q=is%3Aissue). If it's the case and you don't find a solution in the comments, contribute to the issue instead of creating a new one.

### Submit a (good) bug report

Explain the problem and include additional details to help maintainers reproduce the problem:

-   **Use a clear and descriptive title**
-   **Describe the exact steps which reproduce the problem**
-   **Provide specific examples to demonstrate the steps.** Include links to files or projects, or copy/pasteable snippets, which you use in those examples. If you're providing snippets in the issue, use [Markdown code blocks](https://help.github.com/articles/markdown-basics/#multiple-lines).

<br>

[Go to issues](https://github.com/assurance-maladie-digital/vue-cli-preset/issues)

## Suggest changes

Enhancement suggestions are tracked as [GitHub issues](https://guides.github.com/features/issues/).

To create enhancement suggestions, [create a new issue](#submitting-a-good-bug-report).

## Code contribution

You can look for issues labelled with `help-wanted` if you're not sure where to start!

### Vue CLI documentation

Check the [Plugin Development Guide](https://cli.vuejs.org/dev-guide/plugin-dev.html) and the [Preset section](https://cli.vuejs.org/guide/plugins-and-presets.html#presets) of Vue CLI documentation to get information about plugin and preset development.

### Local preset

To generate an application using the local version of the preset, you can run `vue create` with the path to your repo (relative or absolute)

```bash
# ./my-preset should be a directory containing preset.json
vue create --preset ./path/to/repo/ my-project
```

### Local plugin

To use a local plugin with your preset when developing, you can replace it's version by it's path:

```json
"@cnamts/vue-cli-plugin-vue-dash": {
	"version": "path/to/plugin/"
}
```

Be careful to not commit local paths!

### Commit guidelines

Look at the previous commits for inspiration! But you need it to be explicit, and it should follow these rules:

-   Write it in English
-   Start with an emoji from [gitmoji](https://gitmoji.carloscuesta.me/) corresponding to the changes made
-   Do not end the subject line with a period
-   Capitalize the subject line
-   Use the imperative mood
