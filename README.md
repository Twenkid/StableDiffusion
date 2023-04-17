# StableDiffusion
Tips, experience, generations etc.

As of 17.4.2023: A SD 2.1 notebook with GUI:
https://colab.research.google.com/github/qunash/stable-diffusion-2-gui/blob/main/stable_diffusion_2_0.ipynb#scrollTo=6x8gRvmV3ieY


```
biomechanoid cloning starbase landscape with nebula background	
biomechanoid towers on valley landscape with nebula background
blueprints for economically viable nuclear fusion reactor
futuristic geiger space background side scrolling mechanical forest
futuristic geiger space background side scrolling mechanical forest

from torch import autocast
num_images = 3
generator = torch.Generator("cuda").manual_seed(1024)
prompt = ["futuristic geiger space background side scrolling mechanical forest"] * num_images

with autocast("cuda"):
  images = pipe(prompt=prompt, num_inference_steps=70, guidance_scale=10, generator=generator)["sample"]
  #default=50, 7-8.5

grid = image_grid(images, rows=1, cols=3)
grid
futuristic geiger space background side scrolling mechanical forest

from torch import autocast
num_images = 3
generator = torch.Generator("cuda").manual_seed(9876)
prompt = ["futuristic geiger space background side scrolling mechanical forest"] * num_images
...
  images = pipe(prompt=prompt, num_inference_steps=70, guidance_scale=11, generator=generator)["sample"]

futuristic geiger space background side scrolling mechanical forest

  images = pipe(prompt=prompt, num_inference_steps=71, guidance_scale=11, generator=generator)["sample"]
futuristic geiger space background side scrolling mechanical forest

manual_seed(9877)
futuristic giger space mountain perspective tunnel background side scrolling mechanical nanotechnology forest

prompt = ["futuristic giger space mountain perspective tunnel background side scrolling mechanical nanotechnology forest"] * num_images

manual_seed(9877)
  images = pipe(prompt=prompt, num_inference_steps=72, guidance_scale=10, generator=generator)["sample"]
  #default=50, 7-8.5

mechanical insectoid cityscape spindly angelic structure with nebula background

from torch import autocast
num_images = 3
generator = torch.Generator("cuda").manual_seed(9877)
prompt = ["mechanical insectoid cityscape spindly angelic structure with nebula  background"] * num_images

with autocast("cuda"):
  images = pipe(prompt=prompt, num_inference_steps=66, guidance_scale=9, generator=generator)["sample"]
  #default=50, 7-8.5

grid = image_grid(images, rows=1, cols=3)
grid
mechanical insectoid cityscape spindly angelic structure with nebula background

from torch import autocast
num_images = 3
generator = torch.Generator("cuda").manual_seed(1111)
mechanical insectoid cityscape spindly angelic structure with nebula background

Same parameters (little diff.)
photoreal biomechanical space hotel lobby

Same parameters
side scrolling H.R giger alien cityscape roman
```
