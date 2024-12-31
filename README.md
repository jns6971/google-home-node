# google-home-node
Custom Google Home Scripts

## Setup Instructions

1. Install the necessary dependencies:
    ```sh
    npm install
    ```

2. Copy and rename the example client secret file:
    ```sh
    cp client_secret.json.example client_secret.json
    ```

3. Open  and replace the placeholder values with your Google Assistant API credentials:
    ```json
    {
      "installed": {
        "client_id": "YOUR_CLIENT_ID",
        "project_id": "YOUR_PROJECT_ID",
        "auth_uri": "https://accounts.google.com/o/oauth2/auth",
        "token_uri": "https://oauth2.googleapis.com/token",
        "auth_provider_x509_cert_url": "https://www.googleapis.com/oauth2/v1/certs",
        "client_secret": "YOUR_CLIENT_SECRET",
        "redirect_uris": ["YOUR_REDIRECT_URIS"]
      }
    }
    ```

