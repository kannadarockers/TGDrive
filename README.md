# Google Drive Clone with Telegram Storage

Welcome to the Google Drive Clone with Telegram Storage! This project is a web application that replicates Google Drive's functionalities using Telegram as its storage backend. Users can manage folders and files, perform actions like uploading, renaming, and deleting, utilize trash/bin support, enable permanent deletion, and share public links. The application offers admin login and automatically backs up the database to Telegram.

## Features

- **File Management:** Upload, rename, and delete files with trash/bin functionality and permanent deletion support.
- **Folder Management:** Create, rename, and delete folders effortlessly.
- **Sharing:** Share public links for files and folders seamlessly.
- **Admin Support:** Admin login to efficiently manage the application.
- **Automatic Backups:** Database backups sent to Telegram automatically.
- **Multiple Bots/Clients:** Supports multiple bots/clients for file operations and streaming from Telegram.

## Tech Stack

- **Backend:** Python, FastAPI
- **Frontend:** HTML, CSS, JavaScript
- **Database:** Data stored locally as a class object, saved to a file using the pickle module.
- **Storage:** Telegram

## Deploying Your Own

1. **Clone the repository:**

    ```bash
    git clone https://github.com/TechShreyash/TGDrive
    cd TGDrive
    ```

2. **Edit Configuration Variables:**

    Update all variables mentioned in `config.py` with your specific values.

3. **Install/Update Dependencies:**

    ```bash
    pip install -U -r requirements.txt
    ```

4. **Run the FastAPI application:**

    ```bash
    uvicorn main:app
    ```

    Access the application at `http://127.0.0.1:8000`.

> Note: For deploying the application publicly, refer to online guides on running a FastAPI app.

## Contributing

Contributions are welcome! Fork the repository, make your changes, and create a pull request.

## License

This project is licensed under the MIT License. Refer to the [LICENSE](LICENSE) file for details.