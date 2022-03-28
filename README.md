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

        Our dataset can be downloaded at the following link:https://cowtransfer.com/s/873bd761954b44

##Dataset Composition：

        --syn_data1 #Rain light field data made by Blender.

                --input
        
                --gt
        
                --depth
        
        --syn_data #Rain light field data synthesized with the real-world background.

                --input
        
                --gt
        
                --rain
        
                --rain_disp #Rain streak image with fog
        
        --real # real-world rain light field data captured with Lytro Illum camera.
