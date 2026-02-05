# gProjects

This repo started after I lost three weeks of work when my laptop died. Now everything Python goes here. It's messy by design - a working space, not a portfolio.

## How It's Organized

Threw everything into three buckets:

- `notebooks/` - Jupyter files where I mess around with data
- `python_modules/` - Python files that survived testing and might get reused
- `writings/` - Text files where I rant about what worked and what didn't

## Contributing Your Own Stuff

Just toss files into the right folder. Notebooks need cell outputs visible (run everything before pushing). Python files should have at minimum a comment block at top saying what they do. Markdown files can be stream-of-consciousness as long as the filename hints at the topic.

## The GitHub Pages Angle

Turns out GitHub can serve this as a website for free. Set up `_config.yml` with basic settings and boom, instant documentation site. Much easier to browse than clicking through GitHub's file viewer.

Local testing:
```bash
git pull origin main
python3 -m jupyter lab notebooks/
```

## My Thoughts on Structure

Keeping everything flat for now. No subdirectories, no categorization. Once there are 50+ files maybe I'll organize further, but premature organization is just busy work. Descriptive filenames beat folder hierarchies until you have massive scale.

This updates irregularly. Sometimes I'll commit daily for a week, then nothing for a month. Depends on whether I'm actively experimenting or just coasting.
