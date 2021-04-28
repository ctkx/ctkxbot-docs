## Welcome to CTKXbot's documentation

You can do lots of things with this bot, but it gets confusing to remember all the commands, right?

## Commands

### General

| Command | Additional Input     | Output |
|---------|----------------------|--------|
| .ping   |                      | Pong!  |

### Clocks

| Command  | Additional Input     | Output |
|----------|----------------------|--------|
| .clock   |                      | Shows a live clock that lasts for 1 minute. |

#### Stock Clocks:

Shows the lime left until market period starts or ends.

| Command | Additional Input     | Output |
|---------|----------------------|--------|
| .clock  | pm                   | premarket  |
| .clock  | mkt                  | market  |
| .clock  | ph                  | power hour (final hour of day)  |
| .clock  | ah/am                  | after hours/after market  |

The stock clocks default to NY Trading hours. You can also specify a country code, or market acronym:

| Command | Additional Input     | Output |
|---------|----------------------|--------| 
| .clock  | <type> US / NYSE / NASDAQ | New York |
| .clock  | <type> CA / TSX           | Toronto |
| .clock  | <type> UK / LSE           | London |
| .clock  | <type> DE / FWB           | Frankfurt |
| .clock  | <type> CN / SSE           | Shanghai |
| .clock  | <type> JP / JPX           | Tokyo |
| .clock  | <type> HK / HKEX          | Hong Kong |
| .clock  | <type> FR / EURONEXT      | Paris | 
| .clock  | <type> CH / SIX           | Zurich |
  
  
#### Fun

| Command | Additional Input     | Output |
|---------|----------------------|--------|
| .advice | @username (optional) | Gives you advice, or the user you mention |
| .compliment | @username (optional) | Compliments you, or the user you mention |
| .shibe | @username (optional) | Sends you a shibe, or the user you mention |



```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/ctkx/ctkxbot-docs/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
