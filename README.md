[![Netlify Status](https://api.netlify.com/api/v1/badges/05e4a477-68a7-42bf-b14b-4810c41f2bbe/deploy-status)](https://app.netlify.com/sites/equinoxunconference/deploys)

[**live site**](https://unconference.hackalong.io/)

1. Install Gridsome CLI tool if you don't have it: `npm install --global @gridsome/cli`
2. Clone the repo: `git@github.com:hack-along/EquinoxUnconf.git`
3. `cd EquinoxUnconf`
4. `npm install`
5. run `gridsome develop` or `npm run dev` to start a local dev server at `http://localhost:8080`
6. Happy coding 🎉🙌

# Events

There are two ways you can change or add events to the Unconference repo.
First one is by adding makdown (`.md`) files to [Content / Events directory](https://github.com/hack-along/EquinoxUnconf/blob/master/content/events/) or by goint to [Netlify CMS admin pannel](https://unconference.hackalong.io/admin).

### Adding Events via Github

To add an event create a .md file in the [content/events directory](https://github.com/hack-along/EquinoxUnconf/blob/master/content/events/).

Use this **front matter** syntax to add any aditonal info before your main content. All of this is optional, but title is strongly recomended. NOTE: this is the human friendly syntax, files generated by NetlifyCMS can be different. If you would like to upload an image, please put it in the uploads/events directory.

    ---
    title: Opening Equinox UnConference
    excerpt: Lorem, ipsum dolor sit amet consectetur adipisicing elit. Necessitatibus quasi natus itaque qui odit. Et, dolorem tempore labore ex expedita laboriosam, ipsam repellat ad quas natus minus sunt magni obcaecati.
    date: 2020-09-22 #year-month-day
    start_time: 1500 #please don't use semicolon in the time format
    end_time: 1530
    thumbnail: /uploads/events/moon.png
    tags: ["community", "self-organization"]
    ---

### Adding Events via NetlifyCMS

Just go to [Netlify CMS admin pannel](https://unconference.hackalong.io/admin) and authorize the github/netlify connection.
From there on you can access the CMS and add or edit your own events. The markdown generated will look slightly different.

    ---
    title: Example Events
    excerpt: Donec eu magna bibendum, placerat nibh vel, facilisis eros. Nullam
    suscipit finibus placerat. Nunc pellentesque augue eu dolor aliquet iaculis.
    Class aptent taciti sociosqu ad litora torquent per conubia nostra, per
    inceptos himenaeos. In mi nisi, laoreet in nisi at, facilisis sodales ante.
    date: 2020-09-22T00:00:00.000Z
    start_time: 1900
    end_time: 2000
    thumbnail: /uploads/events/moon.png
    tags:
        - patterns
        - community
        - new economy
    ---

Have fun!
