
# BAAAAASSSSEEEEEE

https://civitai.com/models/1854124/mop-mixture-of-perverts-dmd?modelVersionId=2159501 1 base https://civitai.com/api/download/models/2229335?type=Model&format=SafeTensor&size=pruned&fp=fp16

https://civitai.com/models/4201/realistic-vision-v60-b1 1 alt



https://civitai.com/models/1609320/intorealism-xl?modelVersionId=2132539 2 base

https://civitai.com/models/573152/lustify-sdxl-nsfw-checkpoint 3 base
https://civitai.com/models/312530/cyberrealistic-xl?modelVersionId=2152184 3 good

https://civitai.com/models/166609?modelVersionId=2176192 4 base cartoony
https://civitai.com/models/82543/pornmaster 4 base


#### MIDDDD
https://civitai.com/models/790652/uber-realistic-porn-merge-ponyxl-hybrid-urpmorxl-and-pony-loras-orcontrolnet
https://civitai.com/models/1148756/porn-craft-by-stable-yogi-pony


# REFINEERRRRRRR

https://civitai.com/models/22975/erotic-vision 1
https://civitai.com/models/41636?modelVersionId=55319 1

https://civitai.com/models/150961/pornrealistic


https://civitai.com/models/1584358/ultra-realistic-by-stable-yogi-illus


### EMBEDDINGS

Stable Yogis Negative Embeddings
https://civitai.com/api/download/models/2044068?type=Negative&format=Other
https://civitai.com/api/download/models/2044451?type=Negative&format=Other
https://civitai.com/api/download/models/2044454?type=Negative&format=Other
https://civitai.com/api/download/models/1503612?type=Negative&format=Other


# LORAAAAA

https://civitai.com/models/1822984/instagirl-wan-22 instagram lora

https://civitai.com/models/96933/pornmaster-bukkakecreampiecumdripcumafter-analafter-sex cum lora
https://civitai.com/models/9025/nudify-xl-better-bodies bodies lora (no dark skinned)
https://civitai.com/models/973225/better-bodies-by-stable-yogi bodies lora (w embeddings)
https://civitai.com/models/1056450/home-made-raw-pornography-bright-flash-photo-reupload flash lora

!!! https://civitai.com/models/1787799?modelVersionId=2030540 pussy lora





### FINALSSS

BASE - https://civitai.com/models/1854124?modelVersionId=2229335

REFINER - https://civitai.com/models/1513492?modelVersionId=2052057


LORAS - 

INSTAGRAM - https://civitai.com/models/1822984/instagirl-wan-22 

PUSSY - https://civitai.com/models/1787799?modelVersionId=2030540 


### FINALS - 

config:

Base - GonazaLomo XL  , Flux Whatever
+ 2 Loras - BetterBodies, SuperDetailer
Negative Prompt: <YogiAnatNeg>, <YogiRealismNeg>, <YogiGeneralNeg>, <YogiPDXLNeg>, unrealistic, saturated, high contrast, big nose, painting, drawing, sketch, cartoon, anime, manga, render, CG, 3d, watermark, signature, label, hair



ADVANCED:

guidance scale = 1.3
sharpness = 2 (could be less but works well)
+ ADM = 1.4
- ADM = 0.8
ADM end at step = 0.35
refiner swap method = joint
CFG mimicking from TSNR = 1.2
CLIP skip = 2
sample = LCM
scheduler = karras
VAE = Default

FOrced Overwrite Sampling Step = 14-16


<Stable_Yogis_PDXL_Positives>, a young blonde girl drinking coffee in a cafe, soft lighting, photorealistic, cozy atmosphere, detailed eyes, cinematic depth
<lora:Instagirl:0.7>
<lora:BetterBodiesByStableYogi:0.8>


<Stable_Yogis_PDXL_Negatives-neg>, blurry, bad anatomy, lowres, overexposed, deformed hands



    civit api key = cdc57523389bf56bcc5b0df68bb6924f