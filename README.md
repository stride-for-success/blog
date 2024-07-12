# Runfluence

This where we store our blog posts for [the website](https://strideforsuccess.org/blog).

## How to make a post:
#### Step 1
Fork the repository and add a blog folder to `/blog` with the name of the post all lowercase and dashes instead of spaces: For example `our-mission`.
#### Step 2
Add an index.md file containing the blog post made in markdown. Add any images to a `blog-post-name/assets` folder.
#### Step 3
Create a `info.json` file with the following format:
```json
{
  "author": "First Last",
  "creation-date": "date",
  "title": "Your Title",
  "description": "blah blah blah....."
}
```
To get the creation date, take the UTC Date Time Format from [here](https://www.utctime.net/)
#### Step 4
Create a pull request!
