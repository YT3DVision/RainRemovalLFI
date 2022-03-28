## Rain Streak Removal From Light Field Images

@article{ding2021rain,

  title={Rain Streak Removal From Light Field Images},
  
  author={Ding, Yuyang and Li, Mingyue and Yan, Tao and Zhang, Fan and Liu, Yuan and Lau, Rynson WH},
  
  journal={IEEE Transactions on Circuits and Systems for Video Technology},
  
  year={2021},
  
  publisher={IEEE}
  
}

We propose the powerful end-to-end deep learning model for rain-streak removal on a single rain LFI, by decompsing it into rain-free LFI and rain-streak LFI with mist/veiling. At same time, we construct the first rainy light-field dataset, consisting of both synthetic real-world-like LFIs and real-world LFIs for training and evaluation.

## Dataset

        Our dataset can be downloaded from the following link https://cowtransfer.com/s/873bd761954b44. It is also possible to extract these data from cowtransfer.com using the transfer password 4cavo5.

##Dataset Composition：

        --syn_data1 # Rainy light field images synthesized with Blender.

                --input
        
                --gt
        
                --depth # Depth maps exported by Blender.
example:

![image](https://user-images.githubusercontent.com/93031356/160370203-478b7461-230f-43e6-a933-1c9945dd7fb6.png)
        
        --syn_data # Rainy light field images synthesized by taking real-world light field images as clean background.

                --input
        
                --gt
        
                --rain # Rain streak images synthesized with Blender.
        
                --rain_disp # Rain streak images with fog.
                
example:

![image](https://user-images.githubusercontent.com/93031356/160374159-f0c94e98-fdfc-4b31-b795-65021801747d.png)

        --real # real-world rainy light field images captured with Lytro Illum camera.
      
 example:
 
 ![图片1](https://user-images.githubusercontent.com/93031356/160374298-dea4859f-c094-4c8a-acd0-7eb8b120359d.png)

