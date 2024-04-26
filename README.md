# Whisper Web

ML-powered speech recognition directly in your browser! Built with [🤗 Transformers.js]([https://github.com/santa116-1](https://github.com/santa116-1/Speech-recognition)/).

Check out the demo site [here](https://github.com/santa116-1/Speech-recognition). 

https://github.com/xenova/whisper-web/assets/26504141/fb170d84-9678-41b5-9248-a112ecc74c27

## Running locally

1. Clone the repo and install dependencies:

    ```bash
    git clone https://github.com/santa116-1/Speech-recognition
    cd Speech-recognition
    npm install
    ```

2. Run the development server:

    ```bash
    npm run dev
    ```
    > Firefox users need to change the `dom.workers.modules.enabled` setting in `about:config` to `true` to enable Web Workers.
    > Check out [this issue](https://github.com/santa116-1/Speech-recognition) for more details.

3. Open the link (e.g., [http://localhost:5173/](http://localhost:5173/)) in your browser.
