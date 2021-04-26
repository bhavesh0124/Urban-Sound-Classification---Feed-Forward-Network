# Urban-Sound-Classification---Feed-Forward-Network

## Features extracted:
1. MFCCs
2. Chroma
3. Mel
4. Contrast
5. Tonnetz

Split : 70-30

Local Validation Accuracy : 0.90


Model Summary:
Model: "sequential"
_________________________________________________________________
Layer (type)                 Output Shape              Param #   
=================================================================
dense (Dense)                (None, 256)               49664     
_________________________________________________________________
dense_1 (Dense)              (None, 128)               32896     
_________________________________________________________________
dense_2 (Dense)              (None, 64)                8256      
_________________________________________________________________
dense_3 (Dense)              (None, 10)                650       
=================================================================
Total params: 91,466
Trainable params: 91,466
Non-trainable params: 0
