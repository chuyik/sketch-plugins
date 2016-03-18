Sketch Plugins
---
Best Productivity Plugin Collection.

## Usage
Make sure ` ~/Library/Application\ Support/com.bohemiancoding.sketch3/Plugins` folder is **empty** and proceed by
typing the following cryptic words in `Terminal` app:
```bash
   git clone --recursive https://github.com/chuyik/sketch-plugins.git \
   ~/Library/Application\ Support/com.bohemiancoding.sketch3/Plugins
```

## Other Useful Commands

- Update plugins to latest commit
    ```bash
    git submodule foreach --recursive git pull origin master
    ```

- Add a new plugin
    ```bash
    git submodule add https://github.com/fhuel/Unsplash-It-Sketch.git "Unsplash It"
    ```