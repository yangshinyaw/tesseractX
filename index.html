document.getElementById('imageUploader').addEventListener('change', function(event) {
    const imageFile = event.target.files[0];
    if (!imageFile) return;

    const outputElement = document.getElementById('output');
    outputElement.innerHTML = 'Processing...';

    Tesseract.recognize(
        imageFile,
        'eng',
        {
            logger: (m) => console.log(m), // Optional logger
        }
    ).then(({ data: { text } }) => {
        outputElement.innerHTML = `<h3>Extracted Text:</h3><p>${text}</p>`;
    }).catch((error) => {
        outputElement.innerHTML = `<p>Error: ${error.message}</p>`;
    });
});
