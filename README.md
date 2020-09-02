# ImageToAscii
Converts an image to ascii art

## How to run
####Clone the repository:

`git clone https://github.com/horiagug/ImageToAscii.git`

`cd ImageToAscii`

####Install the requirements:

`python3 -m venv venv`

`source /venv/bin/activate`

`pip install -r requirements.txt`

####Run the script
#####Parameters
`--file : (mandatory) path to image file you want converted`

`--scale : Float -  what scale you want, defaults to 0.43 which is fine for most Courier fonts`

`--out : path to output, defaults to ./out.txt`

`--cols : Int - how many columns you want, defaults to 80`

`--morelevels : Bool - use this flag if you want to use 70 levels of grayscale, default is 10 `

#####Example

`python ascii.py --file ~/Pictures/ok.png --cols 60`

converts ok.png (https://i.imgur.com/BoDaBgs.png) to

```
         .::::::::::::::::::::::::::...::::::::::::         
         -++++++++++++++++++++++++=-:::-=++++++++++         
         -+++++++++++++++++++==++=-::::::-+++++++++         
         -+++++++++++++++++=-:::-=--::::::-=+++++++         
         -+++++++++++++++++=::::::--::::::::-=+++++         
         -+++++++++++++++++=::::::----::::::::-++++         
         -++++++++++++++++++-:::::::----:::::::-=++         
         -+++++++++++++++++++=-:::::::---:::::::-++         
         -++++++++++++++++==+++=-::::::--::::::::=+         
         -+++++++++++==--:::::--==-::::---:::::::-+         
         -++++++===-::::::::::::::::::::--::::::::+         
         -++=--:::::::::::::::::::::::::--::::::::+         
         -+=:::::::::::::--:::::::::::::::::::::::=         
         -+=--------========-:::::::::::::::::::::-         
         -::::::--=++++++++++==---::::::::::::::::-         
         ::::::::-=++++++++++++++==:::::::::::::::-         
         ::::::::--++++++++++++++++:::::::::::::::-         
         ::::::::--++++++++++++++=-:::::::::::::::=         
         .:::::::::--==++++++==-:::::::::::::::::-=         
         ::::::::::::::--==-::::::::::::::::::::-=+         
         -=-::::::::::::::::::::::::::::::::::--=++         
         -++=-:::::::::::::::::::::::::::::::--=+++         
         -+++==-:::::::::::::::::::::::::::--=+++++         
         -++++++==--:::::::::::::::::::::--==++++++         
         :--------------:::::::::::::::------------         

``` 
