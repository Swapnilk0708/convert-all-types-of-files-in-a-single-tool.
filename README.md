# convert-all-types-of-files-in-a-single-tool.
# Overview
This project is a Python-powered universal file converter that allows users to convert multiple file formats within a single application. It supports documents, images, audio, and video conversions, making file format compatibility seamless.

#  Features
. Convert documents (TXT, DOCX, PDF, etc.)
. Process image formats (PNG, JPG, BMP, etc.)
. Convert audio files (MP3, WAV, etc.)
. Handle video files (MP4, AVI, etc.)
. User-friendly interface with batch processing support

# Technologies Used
. Python
. Pillow (PIL) for image processing
. MoviePy for video/audio processing
. Docx, pdf2docx for document conversion

# Working of the Project
# 1) User Input & File Selection
   . The user selects the type of file they want to convert (document, image, audio, video).
   . A file dialog opens, allowing users to choose the file they want to convert.
   . The program reads the file type and validates it to ensure it is supported.

# 2) Processing Based on File Type
 #  . Document Conversion
    . Supported formats: TXT, DOCX, PDF, RTF, etc.
    . The program reads the document content and converts it into another format using libraries like:
    . python-docx (for DOCX processing)
    . pdf2docx (for PDF to DOCX conversion)
    . fpdf (for generating PDFs from text or DOCX)
    . The converted file is saved in the desired format.
