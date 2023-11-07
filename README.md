# segmind/SSD-1B Cog model

This is an implementation of the [segmind/SSD-1B](https://huggingface.co/segmind/SSD-1B) as a Cog model. [Cog packages machine learning models as standard containers.](https://github.com/replicate/cog)

First, download the pre-trained weights:

    cog run script/download-weights

Then, you can run predictions:

    cog predict -i prompt="Wolf, paper, pointed ears, curled tail, sly expression with sharp folded eyes" -i negative_prompt="scary, cartoon, painting"

## Example:

"with smoke, half ice and half fire and ultra realistic in detail.wolf, typography, dark fantasy, wildlife photography, vibrant, cinematic and on a black background"

![alt text](output.0.png)

