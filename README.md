# Image-converter
convert image from one format to another in more convenient way

HOW TO USE:

syntax: python3 [filename] -[options] [raw file / directory] [conversion format]

Example:python3 image_converter.py -dir images/ png

Example: python3 image_converter.py -f images/pokemon.jpg tif

OPTIONS:
--dir / -d  convert all image files in that directory to given format.
           NOTE: non image files like .txt, .csv etc might create error

--file / -f convert single given file to given format

--help / -h Show help options 

--syntax / -s Display syntax

SUPPORTED FORMATS:

https://pillow.readthedocs.io/en/stable/handbook/image-file-formats.html
