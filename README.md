# Simple Text Editor

Welcome to the Simple Text Editor project! This is a web-based text editor that allows you to create, edit, save, load, download, and delete text files. It's a minimalist text editor designed to be easy to use and fully functional.

**Live Demo:** [text.risso.eu](http://text.risso.eu)

## Features

- **Create New Files**: Easily start new files with a default title.
- **Edit Files**: Modify the content of your files using a rich text area.
- **Save Files**: Save changes to existing files or create new ones if none are selected.
- **Load Files**: Load `.txt` files from your local system.
- **Download Files**: Download the currently selected file as a `.txt` file.
- **Delete Files**: Remove files from your list.
- **Search Files**: Quickly find files by title using the search functionality.

## Getting Started

To get started with this project, follow these steps:

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/simple-text-editor.git
cd simple-text-editor
```

### 2. Open the HTML File

You can open `index.html` directly in your web browser. It will run locally without any additional setup.

### 3. Usage

- **Create a New File**: Click the "New File" button.
- **Edit Content**: Type your content in the textarea.
- **Save Changes**: Click the "Save" button to save changes to the currently selected file or create a new file if none is selected.
- **Load a File**: Click the "Load File" button to choose a `.txt` file from your computer.
- **Download File**: Click the "Download" button to download the current file as a `.txt` file.
- **Delete a File**: Click the "Delete File" button to remove the currently selected file.
- **Search Files**: Use the search bar to filter files by title.

## How It Works

The Simple Text Editor uses local storage to keep track of your files. When you create, edit, or delete files, changes are saved in the browser's local storage. This allows you to maintain your files across sessions without a server-side backend.

## Technologies Used

- **HTML5**: For structuring the web page.
- **CSS3**: For styling the editor.
- **JavaScript**: For implementing functionality and interacting with local storage.
- **Font Awesome**: For adding icons to enhance the UI.

## Contributing

Contributions are welcome! If you have suggestions, improvements, or fixes, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
