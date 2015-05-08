## Maptime Starter site

Hosting your own Maptime chapter website? **Starter** is a simple Jekyll theme and is desgined to be easily forked and tweaked to suit your own needs. [Jekyll](http://jekyllrb.com/) is a simple, blog-aware, static site generator for personal, project, or organization sites.  
Once cloned into the [Maptime organization](https://github.com/maptime) your site will be hosted at http://maptime.io/**chapter** where **chapter** is the name of your repo.

* If we've finished onboarding your new chapter into the Maptime organization then should already have this template cloned into the `gh-pages` branch of your chapter repo and have been given you privleges to push to it.  Please skip ahead and begin to customize your site.  

* Not yet in the Maptime fold?  Fill out [this form](http://maptime.io/start/#start-form) and we'll get you set up!  

### Customizing your site

Edit the [`_config.yml`](_config.yml) file. Here's a quick rundown of the configuration options.  

| Name | Required | Value | Description |
| --- | --- | --- | --- |
| baseurl | Yes | post | This value should always be the same. |
| permalink | No | how urls are generated | You can learn more about how they are generated [here](http://jekyllrb.com/docs/permalinks/). |
| markdown | No | Determines which markdown engine is used | Generally, you don't need to touch this field for your own needs. |
| paginate | Yes | Number of posts on the front page | Starter supports pagination. Control the number of posts on a given page by changing this value |
| repo | Yes | Name of the repo on GitHub | As an example, the name of the starter repo is `starter` |
| github_org | Yes | Name of the organization or username on GitHub | Most of the time this will be 'maptime' |
| maptime: chapter | Yes | Name of your Maptime meetup | |
| maptime: twitter | No | Your Maptime Twitter username | |
| maptime: disqus | No | Disqus account name | Starter optionally supports comments on posts with [Disqus](http://disqus.com). Create a new Disqus account for a site and fill this field with the account name. |

### Content types

There are two kinds of content in Starter: post and event. You author these types of content in the `_posts` directory. Each content type has unique configuration options that you should declare at the top of the document. This is called [Frontmatter](http://jekyllrb.com/docs/frontmatter/).

#### Event
Events are for actual planned meetups with RSVP information. Note that the filename of the post should match the date of the meetup date.

##### Frontmatter options

| Name | Required | Value | Description |
| --- | --- | --- | --- |
| layout | Yes | event | This value should always be the same. |
| category | Yes | event | This value should always be the same. |
| title | Yes | The title of your event | |
| rsvp | Yes | URL to rsvp | This could link to a page on [Eventbrite](http://eventbrite.com), [Meetup](http://meetup.com) or another service. |

#### Posts

Posts are like blog posts. These are great for meetup follow ups or posts that don't have a meetup event tied to it.

##### Frontmatter options

| Name | Required | Value | Description |
| --- | --- | --- | --- |
| layout | Yes | post | This value should always be the same. |
| title | Yes | The title of your post | |
| author | No | Author's name | |
| image | No | URL path to an image | Images added here will show up as a [Twitter card](https://dev.twitter.com/docs/cards) when a post is shared. |

## Help resources

- [Create an issue](https://github.com/maptime/maptime-admin/issues) at the maptime-admin repo and we'll respond to it.

- The site is powered by Jekyll. To make custom tweaks to your own site, you should read its [documentation](http://jekyllrb.com/docs/home/).

- **Starter** makes the assumption you will be running the site on GitHub pages. You can learn more about [GitHub Pages here](https://guides.github.com/features/pages/).

## Examples in the wild

- [MaptimeDC](http://maptime.io/dc)

- [MaptimeTO](http://maptime.io/toronto)

## Licence

BSD
