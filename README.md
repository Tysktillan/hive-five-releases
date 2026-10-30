# hive-five-releases

## Launcher news

The **News** tab in the Hive-five launcher reads [`news.json`](news.json).
To post news, open that file on github.com, click the pencil (Edit), add an
entry at the top, and click **Commit changes**. Launchers show it the next time
they open. No new release needed.

```json
{
  "tag": "News",
  "title": "Big update this weekend",
  "date": "2026-11-02",
  "text": "A line or two about what's coming.",
  "image": "https://raw.githubusercontent.com/Tysktillan/hive-five-releases/main/images/my-picture.png",
  "link": "https://example.com"
}
```

- `tag` sets the colour: `News` (amber), `Update` (pink), `Dev` (blue), `Event` (green).
- `image` and `link` are optional. To use your own picture, upload it to the
  `images` folder of this repository and use the address shown above with your file's name.
  PNG or JPG, about 600x370 looks best.
- Keep the commas between entries, and no comma after the last one.
- Each release also shows up in the news by itself.
