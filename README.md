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

        Our dataset can be downloaded at the following link:https://cowtransfer.com/s/873bd761954b44 or  Open [Cow Express] cowtransfer.com and use the transfer password: 4cavo5 to extract;

##Dataset Composition：

        --syn_data1 # Rainy light field images synthesized with Blender.

                --input
        
                --gt
        
                --depth # Depth maps exported by Blender
example:

![image](https://user-images.githubusercontent.com/93031356/160370203-478b7461-230f-43e6-a933-1c9945dd7fb6.png)
        
        --syn_data # Rainy light field images synthesized by taking real-world light field images as clean background.

                --input
        
                --gt
        
                --rain # Rain streak images synthesized with Blender.
        
                --rain_disp # Rain streak images with fog
                
example:

        
        --real # real-world rainy light field images captured with Lytro Illum camera.
