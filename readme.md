![Slash Packaging](/assets/cover.png)

Slash Packaging is an open source directory of businesses that offer packaging sustainability information on their website at the URL **/packaging**. Learn more at [slashpackaging.org/about](https://www.slashpackaging.org/about)

## Contribute

Visit the [Slash Packaging site](https://www.slashpackaging.org/about) to learn more about what a **/packaging** page should include.

If you would like to submit a new page to the directory, open a pull request following the file format found in `/_directory` ([see examples](https://github.com/kepano/slashpackaging/tree/main/_directory)). Each page is a Markdown file with YAML metadata at the top. Your YAML metadata should include these fields:

| Field     | Required | Description                                 |
| --------- | -------- | ------------------------------------------- |
| layout    | yes      | Set to `page`                               |
| title     | yes      | Name of the business                        |
| permalink | yes      | Unique slug, usually the company's username | 
| status    | yes      | Set to `live` or `404`                      |
| url       | yes      | Full URL of the /packaging page             |
| domain    | yes      | Domain of the website                       |
| date      | yes      | Date of the submission to the directory     |
| tags      | no       | Up to 3 tags that describe the business     |

Alternatively you can [fill out the form here](https://airtable.com/shrBfYGhy7OGUb40S) and I will add your page.

## Run the site locally

Slash Packaging is a static site generated with [Jekyll](https://jekyllrb.com/)

Install the necessary dependencies

```
$ bundle
```

Run Jekyll locally

```
$ bundle exec jekyll serve
```