# audio_stegano

##Hiding
python wav-steg.py -h -d data.txt -s opera.wav -o opera_steg.wav -n 2

##Recovering
python wav-steg.py -r -s opera_steg.wav -o data_steg.txt -n 2 -b 10
