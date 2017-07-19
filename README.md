# [Thingmonk](https://thingmonk.github.io)
gulp watch
jekyll serve

The ThingMonk website is built using jekyll and hosted on github pages.
To setup and test a local instance you will need to have

a) [Jekyll](https://jekyllrb.com/docs/quickstart/) installed  
b) git installed

git clone http://github.com/thingmonk/thingmonk.github.io 
edit your files
jekyll serve to test the edits
git commit / git add
git push
 
# Adding a news / blog post

`cd _posts`
`cp 2016-04-04-thingmonk-cfp.md <year>-<month>-<day>-title.md`
edit title and categories in the file
update your content

and then commit the file as normal and push.

# Adding a new speaker for thingmonk or Eclipse IoT Day

For ThingMonk add an entry to `_data/speakers.yml`, for Eclipse add an entry to `_data/eclipse_speakers.yml`

Each entry consists of the following
<pre>
- name:
  photo:
  bio:
  talktitle:
  talkabstract:
  twitter:
</pre>

Just use the entries that were done before as your guide. Once commited they will show up automatically in the main page and on the specific talks pages.

 
