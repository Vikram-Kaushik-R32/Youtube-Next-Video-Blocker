# Youtube-Next-Video-Blocker

## Features

- Removes end-screen video recommendations
- Removes suggestion overlays
- Optional filters for cards, annotations, and Shorts

## Installation

1. Open uBlock Origin Dashboard.
2. Go to **My filters**.
3. Copy and paste the filters below.
4. Click **Apply changes**.

## Core Filters

```text
www.youtube.com##.ytp-modern-videowall-still
www.youtube.com##.ytp-suggestion-set
```

## Optional Filters

### End-screen cards

```text
www.youtube.com##.ytp-ce-element
```

### Video cards and teasers

```text
www.youtube.com##.ytp-cards-teaser
www.youtube.com##.ytp-cards-button
```

### Shorts shelf

```text
www.youtube.com##ytd-rich-shelf-renderer
```

## Notes

YouTube occasionally changes its HTML structure and CSS class names. If a filter stops working, inspect the element and update the selector accordingly.

## License

MIT
