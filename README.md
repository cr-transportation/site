# HOWTO:

## Add meeting notes:
1. create YYYY-MM-DD-meeting.md file in `meetings/` with notes for meeting
2. create link to file in `meetings/index.md` - `* [YYYY-MM-DD](YYYY-MM-DD-meeting)`

## Add a news article:
1. create YYYY-MM-DD-title_separated_by_underscores.md in `news/` with the article contents
2. create a link to the article in `news/index.md` - `* YYYY-MM-DD [Article Title](YYYY-MM-DD-title_separated_by_underscores)`

## Host the website locally with Docker:
run --rm --label=jekyll --volume=$PWD:/srv/jekyll  -it -p 4000:4000 jekyll/jekyll:pages jekyll serve
