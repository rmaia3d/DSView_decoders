# DSView_decoders
 Modified decoders based on the standard I2C and SPI decoders, adding the possibility to display the decoded data in ASCII format as well (not only HEX).

 Sometimes it's easier to just send an ASCII string to test the protocol when debugging, and that's when these mods come in handy.

 # Installation

 Simply copy the folders 1-i2c2 and 1-spi2 to your local decoders folder installed together with [DSView](https://github.com/DreamSourceLab/DSView). These files are not supposed to overwrite anything, they just add extra decoders that you can select.

 There's no need to copy the images folder, they are only the source for the images shown below.

 - On MacOS the decoders folder is usually inside the .app package. You need to navigate to your applications folder, find DSView.app there, right-click and select "Show package contents". The decoders are under Contents/MacOS/decoders.
 
 # Usage

 Some example images. Note that these decoders can be used together with the standard decoders without a problem.

 ![view1]

 ![view2]

 You can select the data display format from the decoder config dialog.

 ![config_opts]

 ![config_ascii]
 
 [view1]: https://github.com/rmaia3d/DSView_decoders/blob/master/images/DSView_I2C.png

 [view2]: https://github.com/rmaia3d/DSView_decoders/blob/master/images/DSView_I2C_b.png

 [config_opts]: https://github.com/rmaia3d/DSView_decoders/blob/master/images/DSView_I2C_opts.png

 [config_ascii]: https://github.com/rmaia3d/DSView_decoders/blob/master/images/DSView_I2C_ascii.png

 

 


