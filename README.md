# BookifyPDF

BookifyPDF is a powerful library that enables you to effortlessly transform your static PDF documents into interactive and engaging digital books. With BookifyPDF, you can add captivating page flip effects, create an immersive reading experience, and bring your PDFs to life.

## Features

- PDF to Book Conversion: Convert regular PDF files into dynamic flipbooks with realistic page flipping effects.
- Customization Options: Customize the appearance and behavior of your flipbooks with a wide range of configurable settings.
- Responsive Design: Ensure optimal viewing experiences across various devices and screen sizes, including desktops, tablets, and mobile devices.

## Example Usage

```html
<body>
    <button id="prev-btn">
        <i class="fas fa-arrow-circle-left"></i>
    </button>
    <div id="book" class="book"></div>
    <button id="next-btn">
        <i class="fas fa-arrow-circle-right"></i>
    </button>
</body>
<script src="./bookifyPDF.js" ></script>
<script>
    let url = "TestNumbers.pdf";
    readPDFasBook(url,"prev-btn","next-btn","book",1);
</script>
```html


## Examples

To try out BookifyPDF, follow these steps:

1. Download the folder.
2. Open the `index.html` file in your browser.
3. BookifyPDF should now be running. If anything appears to be off, please ensure that you have the latest version of the pdf.js library.

## Contribution

Contributions are welcome! If you have any ideas, bug fixes, or want to improve BookifyPDF, please submit a pull request or open an issue.

## License

BookifyPDF is released under the MIT License.

## Created By

- Jan Volovšek
- Mihael Donko
