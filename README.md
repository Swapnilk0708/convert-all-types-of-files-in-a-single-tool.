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

1) Document Conversion
    
   . Supported formats: TXT, DOCX, PDF, RTF, etc.
    
   . The program reads the document content and converts it into another format using libraries like:
    
   . python-docx (for DOCX processing)
    
   . pdf2docx (for PDF to DOCX conversion)
    
   . fpdf (for generating PDFs from text or DOCX)
    
   . The converted file is saved in the desired format.

2) Image Conversion
      
   . Supported formats: PNG, JPG, BMP, TIFF, GIF, etc.
   
   . The Pillow (PIL) library is used to open the image and save it in a different format.
   
   . Example: A JPG file can be converted to PNG or BMP.
   
   . The converted image is saved with the chosen format.
   
3) Audio Conversion
      
   . Supported formats: MP3, WAV, AAC, OGG, etc.
   
   . The MoviePy and ffmpy libraries handle the conversion of audio files.
   
   . Example: An MP3 file can be converted to WAV or AAC.

4) Video Conversion
      
   . Supported formats: MP4, AVI, MKV, MOV, etc.
   
   . MoviePy and FFmpeg are used for video processing and format conversion.
   
   . Example: A video in MP4 format can be converted to AVI or MKV.
   
   . The tool also allows video compression and resolution adjustments.
   
# 3) Saving and Exporting the Converted File

   . After conversion, the user selects the output directory to save the converted file.
   
   . The file is then exported and saved in the selected folder.
   
   . A confirmation message is displayed once the conversion is successfully completed.

 # Technologies Used

 | File Type | Libraries Used |
| ------------- | ------------- |
| Documents (TXT, DOCX, PDF)  | python-docx, pdf2docx, fpdf  |
| Images (PNG, JPG, BMP)  | Pillow (PIL)  |
| Audio (MP3, WAV)  | MoviePy, ffmpy  |
| Video (MP4, AVI)  | MoviePy, FFmpeg  |

 # Key Features

 1) Multiple File Type Support – Convert documents, images, audio, and video files.
 
 2) Simple User Interaction – Select files and choose the output format.
 
 3) Efficient Processing – Uses optimized Python libraries for fast conversions.
 
 4) Flexible Output Options – Save converted files in the preferred format and location.



 

