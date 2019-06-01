# Color_change-
Color change is basically removing the prominent color from an image and then apply it to some other image.Images are mostly in RGB format but Erik Reinhard introduced an format which eases the alteration.The method basically involves subtracting the mean values of target from each component multipying it by the standard ratio and then adding mean value of source in the target image.
If you want to learn more about color transfer algorithm here is paper link:"https://www.cs.tau.ac.il/~turkel/imagepapers/ColorTransfer.pdf"
Thanks to Adrian Rosenbrock of pyimagesearch,the program is refrenced from the blog "https://www.pyimagesearch.com/2014/06/30/super-fast-color-transfer-images/"
