
Built by https://www.blackbox.ai

---

# Gemini - Web App for PDF Generation

## Project Overview
Gemini is a web application designed for generating PDF documents quickly and efficiently. Users can create PDFs by providing a title and content, and then download the generated documents. The application features a user-friendly interface that employs modern web technologies to provide seamless functionality and a pleasing user experience.

## Installation
To set up and run the Gemini web application on your local machine, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/gemini-pdf-generator.git
   cd gemini-pdf-generator
   ```

2. **Open the project in your preferred web browser**:
   Simply double-click `index.html` or open it using your browser's "Open File" option.

## Usage
1. **Navigate to the main page**: Open `index.html` in a web browser.
2. **Sign in**: Click on the "Sign in" button to proceed (currently simulated without actual OAuth integration).
3. **Access the PDF Generator**: Click on the "Generate PDF" button from the Dashboard to create a new PDF.
4. **Fill out the form**: Enter the title and content for the PDF.
5. **Generate and download**: Click on the "Generate PDF" button to preview the document. Use the "Download PDF" button to save it to your device.

## Features
- User-friendly interface with a responsive design.
- PDF generation based on user input (title and content).
- Ability to preview the generated PDF within the application.
- Option to download the created PDF directly to your device.
- A dashboard overview where users can easily navigate to all functionalities.

## Dependencies
While the project is primarily HTML, CSS, and vanilla JavaScript, it utilizes the following library for PDF generation:
- [jsPDF](https://github.com/parallax/jsPDF) - A JavaScript library for generating PDF documents in client-side JavaScript.

The library is included via CDN in the `pdf-generator.html` file:
```html
<script src="https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js"></script>
```

## Project Structure
The project consists of the following files:

```
/gemini-pdf-generator
│
├── index.html         # Main page of the application
├── login.html         # Login page for user sign-in
├── pdf-generator.html # Page for creating PDFs
├── dashboard.html     # Dashboard overview page
├── history.html       # Page to display the user's generated PDFs
└── styles.css         # Stylesheet for styling the application
```

### Style Details
- The `styles.css` file includes base styles and specific styles for components like the navbar, forms, and buttons.

### HTML Files Overview
- **index.html**: Landing page with links to login and dashboard.
- **login.html**: Simple login interface for user access.
- **pdf-generator.html**: Core functionality layout to create PDFs.
- **dashboard.html**: Display various options including PDF generation.
- **history.html**: Shows generated PDFs, initially displays a message when no PDFs are generated.

## Contribution
Feel free to fork the repository and create a pull request with improvements or new features!

## License
This project is open-source and available under the MIT License. See the [LICENSE](LICENSE) file for details.