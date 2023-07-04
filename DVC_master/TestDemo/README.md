Program Usage:

python  Encoder.py --EncoderModel model/L2048/frozen_model_E.pb  --input_frame image/im002.png --refer_frame  image/im001.png  --output output/feature/folder/


python Decoder.py --DecoderModel model/L2048/frozen_model_D.pb  --refer_frame image/im001.png --loadpath output/feature/folder/
