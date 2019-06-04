[![Netlify Status](https://api.netlify.com/api/v1/badges/77bca691-dc7b-41dc-af72-2ec04719a6d2/deploy-status)](https://app.netlify.com/sites/summit360-web/deploys)

The 2019 Summit360 website, using [Hugo], deployed via [Netlify]

## Building locally

To work locally with this project, you'll have to follow the steps below:

1. Fork, clone or download this project
1. [Install][] Hugo
1. Preview your project: `hugo server`
1. Add content
1. Generate the website: `hugo` (optional)

Read more at Hugo's [documentation][].

### Preview your site

If you clone or download this project to your local computer and run `hugo server`,
your site can be accessed under `localhost:1313/hugo/`.

The theme used is adapted from http://themes.gohugo.io/beautifulhugo/.

## Troubleshooting

1. CSS is missing! That means two things:

   Either that you have wrongly set up the CSS URL in your templates, or
   your static generator has a configuration option that needs to be explicitly
   set in order to serve static assets under a relative URL.

[ci]: https://about.gitlab.com/gitlab-ci/
[hugo]: https://gohugo.io
[netlify]: https://netlify.com
[install]: https://gohugo.io/overview/installing/
[documentation]: https://gohugo.io/overview/introduction/
[userpages]: http://doc.gitlab.com/ee/pages/README.html#user-or-group-pages
[projpages]: http://doc.gitlab.com/ee/pages/README.html#project-pages
[post]: https://about.gitlab.com/2016/04/07/gitlab-pages-setup/#custom-domains
