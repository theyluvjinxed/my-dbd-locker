# ♡ Easy DBD Locker

You only need to edit **locker.json** when you want to add or remove things from your collection.

## Adding a character/outfit

Open `locker.json`. It looks like this:

```json
[
  {
    "name": "Kate Denson",
    "type": "survivor",
    "item": "Example outfit",
    "image": ""
  }
]
```

Copy an entry and change the information:

```json
{
  "name": "Feng Min",
  "type": "survivor",
  "item": "Bunny Feng",
  "image": "images/feng.jpg"
}
```

For a killer, use:

```json
"type": "killer"
```

For a survivor, use:

```json
"type": "survivor"
```

### Pictures

Put your pictures in the **images** folder.

Example:

```text
images/feng.jpg
```

Then put this in `locker.json`:

```json
"image": "images/feng.jpg"
```

If you don't want a picture, leave it blank:

```json
"image": ""
```

## IMPORTANT: commas

Every entry except the last one needs a comma after the `}`.

Example:

```json
[
  {
    "name": "Kate Denson",
    "type": "survivor",
    "item": "Outfit 1",
    "image": ""
  },
  {
    "name": "Feng Min",
    "type": "survivor",
    "item": "Outfit 2",
    "image": ""
  }
]
```

## GitHub

Upload these to the same repository:

- `index.html`
- `locker.json`
- `images` folder

Then GitHub Pages will display your locker.

**You do not need to edit `index.html` again.**
