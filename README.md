# Neural_Style_Transfer
Neural Style Transfer implemented in PyTorch.<br>
NST is a peculiar application of CNNs that is used to impose the style of one image on a target image without distorting its contents.<br>
Many photo editing apps use this model in background of their filters.<br>
I have used a pretrained VGG-19 model as the backbone. Through training we aim to minimise the total loss, which is a weighted sum of the content loss and the style loss.<br>
By tuning the weights of the loss function we can adjust how much of the style/content we want to keep in the output.

### Sample Output:
At epoch 0:<br>
<img src = "https://github.com/AvirupJU/Neural_Style_Transfer/blob/main/stylegan_output/gen0.jpg">

At epoch 2500:<br>
<img src = "https://github.com/AvirupJU/Neural_Style_Transfer/blob/main/stylegan_output/gen2500.jpg">

At epoch 5000:<br>
<img src = "https://github.com/AvirupJU/Neural_Style_Transfer/blob/main/stylegan_output/gen5000.jpg">

