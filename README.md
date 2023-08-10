Document Scanner using OpenCV in C++

Developed a document scanner application using OpenCV and C++.
The application uses a combination of image processing techniques to automatically scan and crop documents.
The techniques used include:
    Preprocessing: The image is first converted to grayscale, blurred, and then edge detected.
    Contour detection: The edges of the document are detected and a contour is found that encloses the entire document.
    Perspective transform: A perspective transform is used to warp the image so that it is straightened and has a uniform aspect ratio.
    Cropping: The warped image is cropped to remove any extraneous pixels.
The application was tested on a variety of documents, including business cards, letters, and invoices and achieved an accuracy of over 90% in scanning and cropping documents.
